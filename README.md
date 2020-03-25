# REST API SUBIDA DE IMAGENES

Este proyecto es un servidor web creado con Nodejs, Typescript y Mongodb, con el propósito de almacenar imágenes.

## Instalacion

* Clonar este repo y los submodulos con `git clone https://github.com/alejandrogvillarreal/REST-API-Subida-Imagenes.git`
* Correr el comando npm install.
* Luego correr el comando npm start.

## Alcance

### Funcionalidades

Con la App podremos:

* Cargar imagenes con titulo y descripción en nuestra base de datos.

## Tecnologias usadas

### Back-End:

* [nodejs](https://nodejs.org/en/)
* [express](https://expressjs.com/en/)
* [typescript](https://www.typescriptlang.org/)
* [mongodb](https://www.mongodb.com/en/)

### Rutas Back-End

* `/photos`: 
    - `GET`: Obtiene el listado de imagenes.
    - `POST`: Cargar una imagen.
* `/photos/:id`:
    - `GET`: Obtiene los datos de una imagenes.
    - `PUT`: Edita los datos de una imagen.
    - `DELETE`: Elimina una imagen.

## Puertos

El servidor se levanta en el puerto 4000, por lo tanto, para enviar los request lo haremos a http://localhost:4000.