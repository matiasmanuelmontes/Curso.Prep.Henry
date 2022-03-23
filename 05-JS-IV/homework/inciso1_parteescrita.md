# Homework: Javascript IV

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Objetos: Los objetos son contenedores de datos, como lo son los arrays. Pero con la diferencia es que los objetos pueden contener mucha informacion sobre una sola cosa, sin considerar indices numericos. Para invocar un objeto usaremos una estructura como la siguiente:

	var objeto = {
		nombre: 'pepe'
		apellido: 'honguito'
		pesokg: 42
		alturacm: 182 
	}

	Donde lo que se encuentra entre llaves son las propiedades del objeto (nombre, apellido, etc)

	* Propiedades: Las propiedades son la asociacion de una palabra clave (por ejemplo  nombre en el caso descripto) y un valor ( para nombre el valor seria 'pepe'). El par clave-valor puede aparecer en un objeto reiteradas veces para detallar prodiedades del objeto, con la salvedad de que la clave no debe repetirse. Los valores por su parte pueden ser: string, numeros, booleanos, cadena, matrices, funciones o incluso otros objetos.

	* Métodos: Los metodos son en caso de que un valor tome la forma de funcion, veremos como insertamos la funcion felicitar en nuestro objeto anterior. La funcion tomara el nombre que habremos establecido anteriormente.

	var objeto = {
		nombre: 'pepe'
		apellido: 'honguito'
		pesokg: 42
		alturacm: 182
		felicitar: function() {
			return 'felicidades ' + this.nombre;
		}
	}

	* Bucle `for…in`: Los bucles de este tipo sirven para recorrer cada una de los pares clave-valor del objeto e iterarlos. La estructura de este bucle seria la siguiente, suponiendo que tenemos el objeto ya antes utilizado:

    var objeto = {
		nombre: 'pepe'
		apellido: 'honguito'
		pesokg: 42
		alturacm: 182
		felicitar: function() {
			return 'felicidades ' + this.nombre;
		}
	}

	for(let a in objeto) {
		console.log(a);
		console.log(objeto[a])
	}


	* Notación de puntos vs notación de corchetes: Para acceder a los valores tenemos la notacion de puntos o de corchetes. La notacion de puntos es mas comoda y rapida de utilizar pero puede introducir a errores sino se presta atencion durante su uso, su uso se da en caso de que no hagamos referecia a variables. La notacion de corchetes es como si estuvieramos llamando al elemento de una matriz. Daremos ejemplos de cada notacion:

	notacion con punto: objeto.nombre
	notacion con corchetes: objeto['nombre'] 
	notacion con punto: objeto.felicitar()
    notacion con corchetes: objeto[felicitar()]


2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSIV.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/05-JS-IV/homework/homework.js)