# Tienda de Tecnología - Web App E-Commerce

###  ¿Qué problema resuelve?
Ofrece una plataforma web interactiva y moderna para la exhibición y venta de productos tecnológicos, permitiendo a los usuarios explorar catálogo, filtrar productos y gestionar sus compras en un carrito funcional de manera rápida e intuitiva.

### Tecnologías utilizadas
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), FontAwesome.
- **Backend:** PHP 8 (API RESTful para procesamiento de datos JSON).
- **Base de Datos:** MySQL / MariaDB.
- **Servidor Local:** XAMPP (Apache).

###  Descripción del Proyecto
La aplicación cuenta con una interfaz dinámica orientada a la experiencia de usuario:
- **Interfaz y Catálogo:** Catálogo interactivo con ordenamiento por precio, filtro por categorías, buscador en tiempo real y modal con vista rápida de detalles por producto.
- **Carrito de Compras:** Drawer lateral desplegable que calcula automáticamente subtotal, costos de envío y total, con ajuste dinámico de cantidades y badges interactivos.
- **Backend y Procesamiento:** Integración con API en PHP mediante peticiones `fetch` asíncronas para el guardado de órdenes y registro de clientes en la base de datos MySQL (`tienda_db`).

###  ¿Cómo se ejecuta?
1. Copia la carpeta del proyecto dentro del directorio de tu servidor local (ej. `htdocs` en XAMPP).
2. Importa el archivo `tienda_db.sql` en phpMyAdmin / MySQL para crear la base de datos y la tabla `pedidos`.
3. Inicia los servicios de **Apache** y **MySQL** desde el XAMPP Control Panel.
4. Abre tu navegador e ingresa a `http://localhost/tienda-tecnologia`.

### 🎯 Resultado
Una tienda virtual completamente responsiva y funcional que procesa compras, valida datos del cliente y almacena de forma persistente cada pedido en MySQL con confirmaciones visuales (*toast notifications*).
