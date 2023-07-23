# Natufriend - backend
 
## Proyecto final para la materia Backend de [CoderHouse](https://www.coderhouse.com), comisión #39685
 
### Alumno: Martín Pacheco
 
## Brief

Sitio e-commerce de productos naturales para mascotas.

## Comentarios

Por problemas utilzando la plataforma de Render.com (bloqueo de cookies por estar registrada en la Public Suffix List) y la imposibilidad de utilizar Railway.app, se tuvo que descartar la utilización del front creado para el uso de este server. 
Se dejan las URLS correspondientes, pero se recomienda correr el servidor en local para testeo vía POSTMAN.

API URL: https://natufriend-server.onrender.com
FRONT URL: https://natufriend.onrender.com

## Instrucciones para entrega final

- Colocar los archivos .env enviados por privado en la raiz del proyecto
- Correr el servidor con `npm run prod`
- Testear vía POSTMAN en localhost:3000 utilizando el archivo JSON con las HTTP request específicas, enviado por privado

### API docs:

Los endpoints y su funcionalidad se visualizan en la ruta /apidocs una vez lanzado el server.

### Testing:

En terminal #1: en /backend correr el comando `npm run testing` para lanzar el sv en modo TESTING

En terminal #2: en /backend correr el comando `npm run supertest` para ejecutar el test integral de session/cart/products
  
## Dependencias utilizadas:

Instalación completa con el comando `npm i`

- bcrypt
- commander
- connect-mongo
- cookie-parser
- dotenv
- express
- express-session
- jsonwebtoken
- mongoose
- mongoose-paginate-v2
- nodemailer
- passport
- passport-github2
- passport-local
- socket.io
- swagger-jsdoc
- swagger-ui-express
- winston
- multer

devDependencies:
- @faker-js/faker
- nodemon
- chai
- mocha
- supertest
