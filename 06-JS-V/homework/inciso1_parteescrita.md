# Homework: Javascript V

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `prototype` : un prototipo quiere decir que todos los objetos tienen una referencia a otro objeto que se llama proto. Cuando javascript no encuentra una propiedad del objeto puede ir al proto y buscar la propiedad ahi, si la encuentra la usa, sino la encuentra tira error. Lo que se logra con esto es que las clases tienen una forma única de establecer un método una vez y dar acceso a cada objeto de esa clase a esos métodos, ahorrando asi la memoria ocupada para cada operacion.

* _Constructors_ (de Clases): Los constructores son funciones que crean objetos, con determinadas propiedades para crear una clase de este objeto, estas funciones constructoras tendran como caracteristica que utilizaran la mayuscula en la primer letra de la funcion y en cuanto a sus propiedades debera anteponerse el operador this. Cuando se desea tener una instancia de este objeto se usa el operador new pero esto ya sera parte de otra operacion. Veamos un ejemplo a continuacion:

function Heladera(marca, altura, capacidad) {
	this.marca = marca,
	this.altura = altura,
    this.capacidad = capacidad,
}

Esta funcion no devuelve nada, cuando implementemos la siguiente linea de codigo podremos tener una devolucion:

var electrolux = new Heladera('electrolux', 180, 55)

2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSV.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/06-JS-V/homework/homework.js)