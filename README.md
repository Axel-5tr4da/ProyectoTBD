Para trabajar este proyecto debemos crear una carpeta en la memoria con el nombre que quieran, y dentro de ella una sub-carpeta llamada public donde meteremos los archivos .html que seran las paginas a las cuales accederemos desde el navegador y con las cuales vamos a interactuar, para la estructura quedaria algo mas o menos asi 
 ```
   ProyectoTBD/
   ├── public/
   │   ├── admin.html
   │   ├── busqueda.html
   │   ├── equipos.html
   │   ├── error.html
   │   ├── index.html
   │   ├── login.html
   │   ├── pacientes.html
   │   ├── registro.html
   │   ├── regmed.html
   │   └── styles.css
   ├── uploads/
   ├── server.js
   ├── nodemon.json
   ├── package-lock.json
   ├── package.json
   └── .env
   ```
Los archivos fuera de public nos ayudaran para el funcionamiento. En cada archivo tomaremos el contenido del apartado homonimo y lo pegaremos en el, para las dependencias vamos a acceder a la terminal y meter el comando
```
NPM INIT -Y
```
despues 
```
npm install express mysql2 body-parser express-session bcrypt dotenv multer xlsx nodemon bcrypt, que es toda la paqueteria necesaria para que funcione
```
