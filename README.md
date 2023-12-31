# Proyecto Final - Hito 1

En el primer hito, hemos realizado el diseño y prototipo inicial de nuestro proyecto, un PlayMarke diseñado para realizar clases particulares en vivo, de uno a uno, abarcando diferentes materias y edades. En nuestro sistema, los usuarios se podrán  registrar, contratar clases o ofrecer sus servicios como profesores, incluyendo imágenes y descripciones de lo que ofrecen. Además, los usuarios que contraten clases podrán dejar comentarios y calificar el servicio, creando así una red segura para toda la comunidad.

Los puntos que hemos completado en este primer hito son los siguientes:

1. Generar la maqueta de la interfaz gráfica que utilizaremos en la plataforma.

2. Definir la navegación entre las vistas privadas y públicas de la plataforma.

3. Identificar y listar las dependencias tanto del frontend como del backend del proyecto, incluyendo las dependencias de producción y las de desarrollo.

4. Diseñamos la base de datos teniendo en cuenta todos los detalles necesarios para asegurar un sitio ágil y potente.

5. Diseñamos el contrato de datos de la API REST, incluyendo toda la información necesaria para el correcto funcionamiento de nuestro sistema.

Estos avances nos permiten sentar las bases sólidas para el desarrollo de nuestro proyecto y nos acercan cada vez más a nuestra visión de brindar un entorno seguro y eficiente para las clases particulares en vivo.


## Integrantes

- **Diego Lorca** 
  [![github](https://img.shields.io/badge/github%20profile-000?style=for-the-badge)](https://github.com/Dlorcav77)
- **Alex Fernández** 
  [![github](https://img.shields.io/badge/github%20profile-000?style=for-the-badge)](https://github.com/Arekkusu17)

## Diseño de la Interfaz Gráfica
![Pagina Principal](./interfaz-grafica/pagina-principal.png)
![Galería de Productos](./interfaz-grafica/galeria.png)
![Inicio de Sesión](./interfaz-grafica/inicio-de-sesion.png)
![Registro](./interfaz-grafica/registro.png)
![Carro de Compras](./interfaz-grafica/carro-de-compras.png)
![Detalles de Producto](./interfaz-grafica/detalle-productos.png)
![Perfil](./interfaz-grafica/perfil.png)
![Editar Perfil](./interfaz-grafica/editar-perfil.png)
![Favoritos](./interfaz-grafica/favoritos.png)
![Crear Publicación](./interfaz-grafica/crear-publicacion.png)
![Mis Publicaciones](./interfaz-grafica/mis-publicaciones.png)

## Definición de la navegación entre las vistas
![Navegación entre las vistas](./esquema-navegacion/esquema.png)

*Referente al portal de pagos, estamos analizando si tomarlo como una vista o de otra forma*

## Listado de dependencias a utilizar en el proyecto

**FRONTEND**
```
"dependencies": {
    "@emotion/react": "^11.11.1",
    "@emotion/styled": "^11.11.0",
    "@fontsource/roboto": "^5.0.4",
    "@mui/icons-material": "^5.13.7",
    "@mui/material": "^5.13.7",
    "bootstrap": "^5.3.0",
    "react": "^18.2.0",
    "react-bootstrap": "^2.8.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.14.1"
  }
```
**BACKEND**
```
"devDependencies": { 
    "nodemon": "^2.0.22" 
    "jest": "^28.1.3", 
    "supertest": "^6.2.4" 
  },
"dependencies": {
    "bcryptjs": "^2.4.3", 
    "cors": "^2.8.5", 
    "dotenv": "^16.1.4", 
    "express": "^4.18.2", 
    "jsonwebtoken": "^9.0.0", 
    "morgan": "^1.10.0", 
    "pg": "^8.11.0" 
  } 
```

## Diseño las tablas de la base de datos y sus relaciones.
![Base de Datos](./dise%C3%B1o-base-de-datos/base-de-datos.png)

## Diseñar el contrato de datos de la API REST

Para mayor comodidad se utiliza un archivo PDF para hacer entrega del [Contrato de datos para la API REST](./contrato-api-rest/Contrato-API-Rest.pdf), fue realizado mediante Swagger.

De igual forma, se adjuntan capturas:

**GET /users/{id}**
![GET /users/{id}](./contrato-api-rest/get-users-id.png)

**PUT /users/{id}**
![PUT /users/{id}](./contrato-api-rest/put-users-id.png)

**POST /users/register**
![POST /users/register](./contrato-api-rest/post-users-register.png)

**POST /users/login**
![POST /users/login](./contrato-api-rest/post-users-login.png)

**GET /products**
![GET /products](./contrato-api-rest/get-products.png)

**POST /products**
![POST /products](./contrato-api-rest/post-products.png)

**GET /products/{id}**
![GET /products/{id}](./contrato-api-rest/get-products-id.png)

**PUT /products/{id}**
![PUT /products/{id}](./contrato-api-rest/put-products-id.png)

**DELETE /products/{id}**
![DELETE /products/{id}](./contrato-api-rest/delete-products-id.png)

**GET /favorites**
![GET /favorites](./contrato-api-rest/get-favorites.png)

**POST /favorites**
![POST /favorites](./contrato-api-rest/post-favorites.png)

**DELETE /favorites/{id}**
![DELETE /favorites/{id}](./contrato-api-rest/delete-favorites-id.png)