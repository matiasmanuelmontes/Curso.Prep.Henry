1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Variables: Se refiere a todo parametro que generes que puede adquirir distintos valores, ya sea strings, numericos o booleanos. Pueden adoptar distintos valores segun la instruccion que le asigne un valor. Deben ser definidas previamente para poder tomar distintos valores. Para definir las variables utilizamos el comando var

	* Strings: Hacen referencia a las variables que toman como valor una palabra o una serie de palabras. Deben ir entre comillas'  '

	* Funciones (argumentos, `return`): Las Funciones son una agrupacion de variables que con un sentido logico hace interactuar esas variables que dan como resultado una accion con estas variables. La funcion tendra entonces una forma de comando como: function miFuncion() {}. Donde function es el comando para invocar a la funcion, mientras que mifuncion sera el nombre que se le da a la funcion. Entre parentesis va una variable. Entre llavas ira lo que queremos que nuestra funcion ejecute. El resultdo puede ser visible o no segun usemos el comando return en la instruccion de las funciones o no, sera necesario entonces el comando return al final de lo que va entre llaves para hacer visible el resultado de la ejecucion.

	* Declaraciones `if` : Las declaraciones if son utilizados para dar condiciones a la ejecucion de funciones, se engloban en dentro de los que son controladores de flujo y comparacion. Pueden presentarse dentro de las funciones de la siguiente manera:

	 function puedeManejar(edad) {
    if (edad > 18) {
        return true;
    }

    return false;
    } 

    Con esta estructura tiene entre () el condicional que debe cumplirse y lo que esta en llaves {} representa que de un resultado boleano en caso de que la edad sea + de 18 años y en caso contrario tambien esta contemplado. 

	* Valores booleanos (`true`, `false`): los valores booleanos son referencia a los resultados que pueden obtener ciertas variables. True sera para identificar cuando algo es verdadero y false sera para representar cuando algo es falso