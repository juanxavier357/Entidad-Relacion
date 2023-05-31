# Entidad-Relacion Sprint 4

# Make It Real - Ejercicios Modelo Entidad Relación
This is a solution to the Modelo Entidad Relación project of the Make It Real course.

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

**The challenge**
Diagramas en Draw.io para construir bases de datos:

Problema 1: Zoológicos
Se quiere diseñar una base de datos relacional que almacene información relativa a los zoológicos existentes en el mundo, así como las especies animales que éstos albergan. De cada zoológicos se conoce el nombre, ciudad y país donde se encuentra, tamaño (en m2) y presupuesto anual. De cada especie animal se almacena el nombre vulgar y nombre científico, familia a la que pertenece y si se encuentra en peligro de extinción. Además, se debe guardar información sobre cada animal que los zoológicos poseen, como su número de identificación, especie, sexo, año de nacimiento, país de origen y continente.

Problema 2: Gabinete de abogados
Se quiere diseñar una base de datos relacional para almacenar información sobre los asuntos que lleva un gabinete de abogados. Cada asunto tiene un número de expediente que lo identifica, y corresponde a un solo cliente. Del asunto se debe almacenar el período (fecha de inicio y fecha de archivo o finalización), su estado (en trámite, archivado, etc.), así como los datos personales del cliente al que pertenece (DNI, nombre, dirección, etc.). Algunos asuntos son llevados por uno o varios abogados, de los que nos interesa también los datos personales.

Problema 3: Sistema de ventas
Le contratan para hacer una BD que permita apoyar la gestión de un sistema de ventas. La empresa necesita llevar un control de proveedores, clientes, productos y ventas.
Un proveedor tiene un RUT, nombre, dirección, teléfono y página web. Un cliente también tiene RUT, nombre, dirección, pero puede tener varios teléfonos de contacto. La dirección se entiende por calle, número, comuna y ciudad.
Un producto tiene un id único, nombre, precio actual, stock y nombre del proveedor. Además se organizan en categorías, y cada producto va sólo en una categoría. Una categoría tiene id, nombre y descripción.
Por razones de contabilidad, se debe registrar la información de cada venta con un id, fecha, cliente, descuento y monto final. Además se debe guardar el precio al momento de la venta, la cantidad vendida y el monto total por el producto.

Entregables:
Crear un diagrama por cada problema, para ello puede utilizar herramientas como https://draw.io/, https://excalidraw.com/, https://www.lucidchart.com/ entre otras.

**Screenshot**

  ![Solución 1 - Zoológicos](https://github.com/juanxavier357/Entidad-Relacion/blob/main/Problema%201%20-%20Zoologicos.JPG)
  
  ![Solución 2 - Gabinete de Abogados](https://github.com/juanxavier357/Entidad-Relacion/blob/main/Problema%201%20-%20Zoologicos.JPG)
  
  ![Solución 3 - Sistema de Ventas](https://github.com/juanxavier357/Entidad-Relacion/blob/main/Problema%201%20-%20Zoologicos.JPG)


## My process

**Built with**
* Visual Studio Code
* Semantic HTML5 markup
* Node
* Jest

**What I learned**
* A poner en práctica los conocimientos adquiridos en el Curso de Preparación de Make It Real.
* A usar Jest para testear aplicaciones de forma correcta con el método TDD.

**Continued development**
  Seguiré revisando la documentación de Jest para poder testear mis aplicaciones y encontrar si ay errores.

**Useful resources**
  Git, GitHub, Repositorio GitHub de Make It Real

## Author
  Website - www.agenciawebmovil.com/
  GitHub - @juanxavier357

## Acknowledgments
  Agradezco a mis mentores Sergio, Cristian y Juan Lorza por sus enseñanzas y revisiones de este trabajo.

