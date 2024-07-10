# PROYECTO-FINAL
 # Aplicación Web de Tienda 
 ## Descripción 
Esta es una aplicación web de tienda desarrollada para facilitar la compra en línea, con características avanzadas de seguridad y notificación. La aplicación utiliza Docker para montar el entorno de desarrollo, que consta de cuatro contenedores: MySQL, phpMyAdmin, Nextcloud y un contenedor de la tienda. Además, se emplea la librería phpMailer para enviar correos electrónicos y la API de PayPal en modo de prueba para simular pagos. 
## Características - 

- **MySQL:** Base de datos para almacenar la información de la tienda.
-  **phpMyAdmin:** Herramienta de gestión de bases de datos para administrar MySQL.
-  **Nextcloud:** Alojamiento del login de administrador con varios métodos de seguridad.
- **Tienda:** Contenedor principal que interactúa con la tienda.
- **Notificaciones por Correo Electrónico:** - Uso de phpMailer para enviar correos a través de Gmail. - Notificaciones para compras, inicios de sesión y recuperación de contraseña.
- **Método de Pago Simulado:** - Implementación de la API de PayPal en modo de prueba para simular transacciones.
- **Medidas de seguridad:** - Uso de tokens para validar compras y registros de usuarios. - Acceso restringido a funciones y datos sensibles solo para usuarios autorizados.
 
