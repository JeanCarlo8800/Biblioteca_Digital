# Biblioteca Digital

Este proyecto es una aplicación web para la gestión de una biblioteca digital. Permite a los usuarios gestionar libros y categorías, así como realizar operaciones básicas como agregar, listar, buscar y eliminar libros.

## Estructura del Proyecto

## Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura de la interfaz de usuario.
- **CSS3**: Estilos personalizados con diseño responsivo.
- **JavaScript**: Lógica del cliente para la interacción con el servidor y la manipulación del DOM.
- **Font Awesome**: Iconos para mejorar la experiencia visual.

### Backend
- **Java EE**: Desarrollo de servlets para manejar las peticiones HTTP.
- **MySQL**: Base de datos para almacenar información de libros y categorías.
- **Gson**: Librería para serialización y deserialización de objetos JSON.

### Servidor
- **Apache Tomcat**: Servidor de aplicaciones para desplegar la aplicación web.

### Herramientas de Construcción
- **Maven**: Gestión de dependencias y construcción del proyecto.

## Configuración de la Base de Datos

El archivo de configuración de la base de datos se encuentra en `WEB-INF/classes/config/db.properties`:

```properties
db.host=localhost
db.port=3306
db.name=biblioteca_digital
db.user=root
db.password=