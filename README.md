# NodeSend Backend

_Backend de una aplicación de un clon de Dropzone._

## Instalación 🔧

_Escribe el siguiente comando para instalar los módulos de Node.js_

```
npm install
```

_Crear una archivo en la raíz llamado variables.env con las sig. variables_

```
DB_URL=La cadena de conexión de tu BD
SECRETA=Un "password" cualquiera
FRONTEND_URL=El URL de tu frontend
```

_Iniciar la aplicación (modo desarrollo)_

```
npm run dev
```

_Iniciar la aplicación (modo "producción")_

```
npm start
```

## Construido con 🛠️

* [Node](https://nodejs.org/en/) - Entorno de desarrollo de JS
* [Express](http://expressjs.com/) - Framework para Node
* [express-validator](https://express-validator.github.io/docs/) - Librería para validaciones en Express
* [dotenv](https://www.npmjs.com/package/dotenv) - Librería para manejar variables de entorno
* [cors](https://www.npmjs.com/package/cors) - Librería para habilitar el cors
* [Mongoose](https://mongoosejs.com/) - Librería para trabajar con MongoDB
* [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Librería para trabajar con JWT
* [bcrypt](https://www.npmjs.com/package/bcrypt) - Librería para hashing de passwords
* [multer](https://www.npmjs.com/package/multer) - Librería para subida de archivos
* [shortid](https://www.npmjs.com/package/shortid) - Librería para generar ids únicos
