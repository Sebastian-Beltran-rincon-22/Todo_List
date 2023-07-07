
# CRUD ToDo-List - Express

![Logo](https://www.pullrequest.com/blog/nodejs-express-tutorial-for-2021/images/nodejs-express-tutorial-2021.png)

## Descripción

Este proyecto es un ejemplo de una API RESTful desarrollada con Express-Js que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en un modelo de un ToDo-List

## Funcionalidades

- Obtener todos los datos de la DB En la pagina de inicio
- Creacion de nuevas tareas 
- Eliminar Tareas ya realizadas
- Actualizacion de tareas DB

## Tecnologias Usadas
- NodeJs
- Express-Js
- MongoDB
- CSS

## Librerias 
- Moongose
- Dotenv 
- Body Parser
- Nodemon
- Ejs
## Instalacion

1 Clona el repositorio en tu maquina local
```bash
$ git clone git@github.com:Sebastian-Beltran-rincon-22/Todo_List.git
```

2 Navega en el directorio del proyecto 
```bash
$ cd Todo_List
```

3 Puedes cambiar el origen del proyecto con los siguientes comand

```bash
$ git remote -v
$ git remote remove origin
$ git remote add origin <nueva_url_del_repositorio>
```

4 Instalar las dependecias necesarias
- Recuerda tener el package.json y el package-lock.json en el root de la carpeta y ejecutas

```bash
$ npm i
```
5 Debe crear un archivo (.env) en la ruta raiz del proyecto y en el crear una variable de entorno llamada (MONGO_DB_URI) y se le agrega la conexion a su cluster de Mongo

## Uso

1 Inicia la app con 
```bash
$ npm start nodemon
```

2 Puedes acceder a ella desde el puerto configurado:

http://localhost:3000

3 Prueba las diferentes rutas disponibles para realizar operaciones CRUD en el ToDo-List

## Contacto

Si tienes alguna pregunta o sugerencia o quieres la documentacion para desarrollar este proyecto, no dudes en contactarme en [sebastianrincon834@gmail.com](sebastianrincon834@gmail.com).


## Autors

- [@sebastian beltran](https://github.com/Sebastian-Beltran-rincon-22)
