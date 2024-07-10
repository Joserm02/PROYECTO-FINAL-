# PROYECTO-FINAL
 # 🛒Aplicación Web de Tienda 
 ## 📋Descripción 
Esta es una aplicación web de tienda desarrollada para facilitar la compra en línea, con características avanzadas de seguridad y notificación. La aplicación utiliza Docker para montar el entorno de desarrollo, que consta de cuatro contenedores: MySQL, phpMyAdmin, Nextcloud y un contenedor de la tienda. Además, se emplea la librería phpMailer para enviar correos electrónicos y la API de PayPal en modo de prueba para simular pagos.  
 ## Fronted:
- **PHP:** Para la lógica del lado del servidor.
-  **JavaScript:** Para la interactividad del lado del cliente.
-  **CSS,HTML, Bootstrap:** Para el diseño y estructura de la interfaz de usuario.
- **Google Authenticator:** Para escaneo del código QR e ingreso del código.
- **Recaptcha de google:** - Presentación del captcha e ingreso de la respuesta.
- **Nextcloud:** - Para interactuar con el administrador.

## Backend: 
- **MySQL:** Para la base de datos principal.
-  **Docker:** Para la creación de entornos de desarrollo y despliegue.
-  **Google Authenticator:** para generación de la clave secreta y verificación del
código.
- **Recaptcha de google:** - Para generación del captcha y verificación de la
respuesta.
- **Nextcloud:** Para almacenamiento de datos.

## Librerías y APIs: 
- ** 📧 PhpMailer :** Para el envío de correos electrónicos, proporcionando
notificaciones de compra, confirmación de registro y recuperación de contraseñas.
-  ** 💳API de PayPal:**  Para simular pagos, utilizando cuentas y contraseñas de prueba,
lo que proporcionará una experiencia de compra simulada y realista para los usuarios.

