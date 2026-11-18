# SistemasVirtuales
Proyecto final de la materia Sistemas Virtuales

## Descripción
El sistema sirve para registrar alumnos en una base de datos, mas haya de la funcionalidad, esta pensado para poner a prueba nuestros conocimientos sobre docker por lo que tendremos que hacer uso de conceptos aprendidos como el docker file, el docker compose, las imagenes y los puertos.

## Caracteristicas
* Registro de alumnos
* Informacón persistente aunque se apague el sistema
* Hace uso de compose (solo para levantar y especificar rutas)

## Notas (Leer antes de editar el repositorio)

El docker compose solo se usa para levantar la imagen, ahi solo se edita la ubicacion de volumenes, puertos y otras cosas.

En la carpeta development hay que hacer el docker file y ahi ponemos todo lo que se necesita para armar la imagen

En la carpeta AppData se debe de guardar la base de datos, ahi es donde estara la permanencia de nuestros datos