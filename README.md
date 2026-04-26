# 🏪 Sistema de Gestión de Tienda

Aplicación de escritorio desarrollada en **Python** con interfaz gráfica usando **Tkinter**, diseñada para gestionar los recursos básicos de una tienda: productos, clientes y facturas. Utiliza **SQLite** como base de datos local.

---

## 📋 Características

- **Gestión de Productos** – Agrega, edita y elimina productos del inventario.
- **Gestión de Clientes** – Administra la información de los clientes registrados.
- **Gestión de Facturas** – Crea y visualiza facturas asociadas a clientes y productos.
- **Base de datos local** – Toda la información se almacena en un archivo `Tienda.db` (SQLite), sin necesidad de conexión a internet.
- **Interfaz amigable** – Ventana principal con navegación clara hacia cada módulo.

---

## 🗂️ Estructura del Proyecto

```
Proyecto.py/
│
├── App.py                  # Punto de entrada principal de la aplicación
├── Databases.py            # Conexión y configuración de la base de datos
├── Tienda.db               # Base de datos SQLite (se genera automáticamente)
├── package-lock.json
│
├── GUI/                    # Módulos de interfaz gráfica
│   ├── Gui_Clientes.py     # Ventana de gestión de clientes
│   ├── Gui_Facturas.py     # Ventana de gestión de facturas
│   └── Gui_Productos.py    # Ventana de gestión de productos
│
└── MODELS/                 # Modelos de datos
    ├── CLIENTES.py         # Modelo Cliente
    └── main.py             # Modelos principales
```

---

## 🚀 Cómo ejecutar

### Requisitos previos

- Python 3.x instalado ([descargar aquí](https://www.python.org/downloads/))
- `tkinter` (incluido por defecto en la mayoría de instalaciones de Python)

### Pasos

1. Clona o descarga el repositorio:
   ```bash
   git clone https://github.com/AlejaR522/Sistema-Gestion-de-Tienda.git
   cd Proyecto.py
   ```

2. Ejecuta la aplicación:
   ```bash
   python App.py
   ```

> La base de datos `Tienda.db` se crea automáticamente al iniciar la aplicación si no existe.

---

## 🖥️ Uso

Al iniciar la aplicación, verás la ventana principal **"Gestión de Tienda"** con tres opciones:

| Botón | Descripción |
|---|---|
| **Gestionar Productos** | Abre el módulo para administrar el inventario |
| **Gestionar Clientes** | Abre el módulo para administrar clientes |
| **Gestionar Facturas** | Abre el módulo para crear y ver facturas |
| **Salir** | Cierra la aplicación |

---

## 🛠️ Tecnologías utilizadas

- **Python 3** – Lenguaje principal
- **Tkinter** – Interfaz gráfica de usuario (GUI)
- **SQLite3** – Base de datos local embebida

---

## 📌 Notas

- Los datos de ejemplo (como clientes predeterminados) se insertan automáticamente si la base de datos está vacía.
- El proyecto está pensado para uso local/educativo.

---

## 👤 Autor

Desarrollado por **Alejandra Ruiz**  
📧 [aleja.dev2004@gmail.com]  

