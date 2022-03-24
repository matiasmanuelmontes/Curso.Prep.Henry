# Homework: Javascript VI

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* Funciones Callback: Cuando las funciones son argumentos de otras funciones estas se llaman callback. La convención es usar cb como argumento para la variable que se usará de callback.

function aproboelexamen(alumno) {
    return alumno + ' ha aprobado el examen!';
}

function desaproboelexamen(alumno) {
    return alumno + ' ha desaprobado el examen';
}

function darResultado(alumno, cb) {
    return cb(alumno);
}

darResultado('pablo', aproboelexamen); // 'pablo ha aprobado el examen!'
darResultado('pablo', desaproboelexamen); // 'pablo ha desaprobado el examen'

Vemos en este ejemplo que las funciones en los argumentos ( aproboelexamen y desaproboelexamen ) no son invocadas en esta forma de programar, sino que solo se las refiere. 

2. Desde el nivel superior de la carpeta `tests` dentro de esta carpeta `homework`, ingresa el comando `npm test JSVI.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/07-JS-VI/homework/homework.js)