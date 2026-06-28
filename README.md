# The Style Hub

Proyecto académico — **Taller 4** de Maquetación Web.

Sitio web de una tienda de ropa ficticia, construido con HTML5 y Bootstrap 5, que simula tanto la experiencia de un cliente (catálogo, login, registro) como un panel de administración interno.

## 📋 Descripción

The Style Hub es una maqueta funcional de e-commerce que incluye:

- Página principal con carrusel de imágenes y catálogo por categorías.
- Flujo de autenticación: inicio de sesión, registro y recuperación de contraseña.
- Panel de administrador con tarjetas de resumen, tabla de clientes y modal de edición.
- Panel de cliente con pestañas para ver pedidos e historial.

## 🛠️ Tecnologías

- HTML5
- [Bootstrap 5.3.3](https://getbootstrap.com/)
- [Bootstrap Icons 1.13.1](https://icons.getbootstrap.com/)
- JavaScript (vanilla) para componentes interactivos (offcanvas, modal, tabs)

## 📂 Estructura del proyecto

```
taller_4/
├── index.html              # Página principal (carrusel + categorías)
├── assets/
│   ├── img/                 # Logos, íconos y fotos del catálogo
│   ├── css/
│   └── js/
└── app/
    ├── login.html            # Inicio de sesión
    ├── registro.html         # Crear cuenta
    ├── recuperar.html        # Recuperar contraseña
    ├── admin.html             # Panel de administrador
    └── cliente.html           # Panel de cliente
```

## ✨ Funcionalidades

**Página principal (`index.html`)**
- Navbar responsiva con menú colapsable.
- Carrusel de imágenes con texto superpuesto.
- Tarjetas de categorías (Mujer, Hombre, Accesorios).


**Autenticación (`login.html`, `registro.html`, `recuperar.html`)**
- Formularios con validación visual (`is-invalid`, `invalid-feedback`).
- Atributos `autocomplete` para autollenado del navegador.

**Panel de administrador (`admin.html`)**
- Sidebar fija en pantallas grandes, oculta en celular (`offcanvas-lg`).
- Tarjetas de resumen (Ingresos, Inventario, Personal, Reportes).
- Tabla de clientes responsiva con badges de estado.
- Modal para actualizar datos de cada cliente.

**Panel de cliente (`cliente.html`)**
- Sistema de pestañas (`nav-tabs`) para alternar entre Mis Pedidos e Historial de pedidos activos.
- Alertas informativas sobre el estado de los pedidos.

## 🚀 Cómo ejecutarlo localmente

1. Clona o descarga este repositorio.
2. Abre la carpeta en VS Code.
3. Usa la extensión **Live Server** (clic derecho sobre `index.html` → "Open with Live Server").
4. Navega desde ahí al resto de las páginas usando los enlaces del sitio.

> No requiere instalación de dependencias: Bootstrap y los íconos se cargan desde CDN.

## 🌐 Demo

Publicado con GitHub Pages: [juanpablozapatagonsales-prog.github.io/taller_4](https://juanpablozapatagonsales-prog.github.io/taller_4/)

## 👤 Autor

**Juan Pablo Zapata**

## 📄 Nota académica

Este proyecto fue desarrollado con fines educativos como parte del Taller 4 de la asignatura de Maquetación Web.