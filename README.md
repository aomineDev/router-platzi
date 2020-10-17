# Router - Platzi

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/245px-Unofficial_JavaScript_logo_2.svg.png" alt="javascript logo" height="300px">
  <h3>Router | Vanilla JavaScript</h3>
</div>

## Index
- [1. Introducción](#introducción)
  - [¿Qué es un router para una spa?](#qué-es-un-router-para-una-spa)
- [2. Proyecto](#proyecto)
  - [Métodologia del proyecto](#métodologia-del-proyecto)

## Introducción

### ¿Qué es un router para una spa?

Es la forma en al cual podremos navegar entre secciones de nuestra página sin que se genere un full reload

De esta manera el sitio no va a recargar cada vez que queramos ir a otras secciones de nuestro sitio haciendo de nuestra aplicación una __single page aplication__ todo nuestro sitio funcionara dentro de una sola página, y sera JS quien se encargara de modificar el contenido de nuestro sitio dinamicamente según los requerimientos del usuario

## Proyecto

### Métodologia del proyecto

* Identificar en donde nos encontramos en el sitio
  * Lo haremos con una carga inicial de la ruta

* Comparar una URL con una ruta
  * La URL a la que nos queremos mover se debe comprar con la ruta que tenemos

* Actualizar la ruta en la barra de navegación
  * Para esto utilizaremos el método de HTML push.state

* Actualizar el DOM con el nuevo contenido
  *  Para esto vamos a utilizar el método innerHTML

### Arquitectura


<div align="right">
  <small><a href="#index">🡡 volver al inicio</a></small>
</div>