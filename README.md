# restaurante_app-

# 📋 Sistema de Gestión de Restaurante - Semana 9

**Asignatura:** Programación Orientada a Objetos  
**Estudiante:** Jonny Javier Garces Almeidan 
**Fecha:** Agosto 2026

---

## 🎯 Objetivo
Continuar la evolución del sistema aplicando las estructuras de datos principales de Python: **lista, tupla, diccionario y conjunto**, cada una con una finalidad concreta dentro del programa.

---

## 📁 Estructura del proyecto
restaurante_app/
├── modelos/
│ ├── producto.py # Entidad: código, nombre, categoría, precio
│ └── usuario.py # Entidad: identificación, nombre, correo
├── servicios/
│ └── restaurante.py # Lógica: administra colecciones y operaciones
├── main.py # Menú, entrada de datos y llamada al servicio
└── README.md
plaintext

---

## 🧩 ¿Dónde y para qué se usó cada estructura?

| Estructura | Ubicación | Propósito |
|---|---|---|
| **Lista (`list`)** | `servicios/restaurante.py` | Almacenar colecciones dinámicas de productos y usuarios. Permite registrar, buscar, actualizar, eliminar y listar. |
| **Tupla (`tuple`)** | `main.py` | Contiene las opciones del menú. Es fija y no debe modificarse durante la ejecución. |
| **Diccionario (`dict`)** | `main.py` | Relaciona cada número de menú con su función correspondiente. Facilita llamar operaciones sin usar cadenas de `if/elif`. |
| **Conjunto (`set`)** | `servicios/restaurante.py` | Obtener las categorías de productos **sin valores duplicados**. |

---

## ✅ Funcionalidades disponibles
- Registrar, buscar, actualizar, eliminar y listar productos.
- Registrar y listar usuarios.
- Mostrar categorías únicas de productos.
- Validación de códigos e identificaciones duplicadas.
- Manejo de entradas incorrectas sin detener el programa.

---

## 🚀 Ejecución
```bash
python main.py
💡 Reflexión
Elegir bien la estructura de datos hace que el programa sea más eficiente y claro: usamos listas porque necesitamos agregar, modificar y recorrer elementos; tuplas cuando la información nunca cambia; diccionarios cuando hay una relación directa clave-valor; y conjuntos cuando solo nos interesan valores únicos. Seleccionar la estructura adecuada simplifica el código y evita trabajar de más.
