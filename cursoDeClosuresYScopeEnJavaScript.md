# Curso de Closures y Scope en JavaScript
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### 1. Término que se refiere a la accesibilidad que tiene una variable, función u objeto.
        Scope
###### Razón: El scope determina en qué parte del programa una variable, función u objeto puede ser utilizada o accedida. 
###### Vídeo: [Global Scope](https://platzi.com/clases/3213-javascript-closures-scope/50361-que-es-el-scope-global-scope/)
------------
#### 2. ¿Qué sucederá si ejecutamos el siguiente código?
#### nameOfDog("Elmo"); function nameOfDog(name) { console.log(name); }; 
        Se muestra en consola el siguiente mensaje: "Elmo".
###### Razón: Esto se debe a que en JavaScript, las funciones pueden ser llamadas antes de que se declaren. En este caso, la función nameOfDog() se declara después de haber sido llamada, pero aún así funciona correctamente debido a que las declaraciones de funciones son cargadas antes de la ejecución del código. Esto se conoce como hoisting de funciones en JavaScript.
###### Vídeo: [¿Qué es el Hoisting?](https://platzi.com/clases/3213-javascript-closures-scope/50368-que-es-el-hoisting/)
------------
#### 3. ¿Cuál de las siguientes opciones NO se puede considerar como una variable global?
        var = “I am global”;
###### Razón: la siguiente línea no es una variable global válida en JavaScript, ya que falta un nombre para la variable.
###### Vídeo: [Global Scope](https://platzi.com/clases/3213-javascript-closures-scope/50361-que-es-el-scope-global-scope/)
------------
#### 4. ¿Cuál es el alcance que tiene el function scope?
        Se puede acceder a una variable que se ubica dentro de una función, pero no podemos llamarla desde el ámbito global.
###### Razón: sto significa que, si una variable se define dentro de una función, sólo se puede acceder a ella dentro de esa función. Si se intenta acceder a esa variable desde fuera de la función, en el ámbito global, se producirá un error de referencia, ya que la variable no existe en ese ámbito.
###### Vídeo: [Function Scope](https://platzi.com/clases/3213-javascript-closures-scope/50362-function-scope/)
------------
#### 5. Variables declaradas con "let" y "const" son de "block scope"
        Verdadero
###### Razón: En JavaScript las variables declaradas con las palabras clave let y const tienen alcance (scope) de bloque, lo que significa que su alcance se limita al bloque de código en el que se definen.
###### Vídeo: [Block Scope](https://platzi.com/clases/3213-javascript-closures-scope/50363-block-scope/)
------------
#### 6. Es el tipo de dato que se asigna por defecto al declarar una variable.
        Undefined
###### Razón: undefined es un valor especial en JavaScript que se utiliza para indicar que una variable no tiene un valor definido. Es recomendable inicializar siempre las variables al declararlas, para evitar errores y confusiones debidos al valor undefined.
###### Vídeo: [¿Qué es el Hoisting?](https://platzi.com/clases/3213-javascript-closures-scope/50368-que-es-el-hoisting/)
------------
#### 7. ¿Para qué se utiliza el modo estricto en JavaScript?
        Es un modo de trabajo que nos asegura que cada variable está definida al momento de crear nuestro código.
###### Razón: El modo estricto es una herramienta que ayuda a escribir código más seguro y robusto, evitando errores comunes y promoviendo buenas prácticas de programación.
###### Vídeo: [Strict Mode](https://platzi.com/clases/3213-javascript-closures-scope/50365-strict-mode/)
------------
#### 8. ¿En qué momento se genera una closure?
        Cuando una función accede a una variable fuera de su contexto y la recuerda.
###### Razón: En términos más técnicos, una closure se crea cuando una función interna (anidada) hace referencia a una variable de la función externa en la que se encuentra, y esa función interna se devuelve o se pasa como argumento a otra función.
###### Vídeo: [¿Qué es un Closure?](https://platzi.com/clases/3213-javascript-closures-scope/50366-que-es-un-closure/)
------------
#### 9. Las variables declaradas con let y const, NO se pueden volver a declarar en el mismo ámbito.
        Verdadero
###### Razón: Cuando se utiliza let o const para declarar una variable, se está definiendo una variable de bloque (block-scoped variable), lo que significa que la variable sólo existe dentro del bloque en el que se declaró 
###### Vídeo: [Reasignación y redeclaración](https://platzi.com/clases/3213-javascript-closures-scope/50364-reasignacion-y-redeclaracion/)
------------
#### 10. ¿Qué es Code Runner?
        Es un plugin de Visual Studio Code que permite ejecutar el código dentro del editor.
###### Razón: Es eso mismo y no lo mencionan en ningún video pero está en la descripción de la primera clase.  
###### Vídeo: [Bienvenida al Curso de Closures y Scope](https://platzi.com/clases/3213-javascript-closures-scope/50360-bienvenida-al-curso-de-closures-y-scope/)
------------
#### 11. Analiza el siguiente código e identifica la variable declarada en el alcance de la función:
#### const fruits = () => { if (true) { var fruit1 = 'apple'; const fruit2 = 'banana'; let fruit3 = 'kiwi'; } }
        var fruit1 = ‘apple’;
###### Razón: Debido al uso de var, la variable fruit1 no está limitada al ámbito de la función if, sino que se declara en el ámbito de la función fruits.
###### Vídeo: [Function Scope](https://platzi.com/clases/3213-javascript-closures-scope/50362-function-scope/)
------------
#### 12. JavaScript solo utiliza el hoisting en declaraciones, mas no en inicializaciones
        Verdadero
###### Razón: El hoisting en JavaScript se refiere al comportamiento por el cual las declaraciones de variables y funciones se mueven al principio de su ámbito de alcance, lo que permite que estas puedan ser utilizadas antes de su declaración explícita en el código.
###### Vídeo: [¿Qué es el Hoisting?](https://platzi.com/clases/3213-javascript-closures-scope/50368-que-es-el-hoisting/)
------------
#### 13. ¿La herramienta de Google Chrome que nos permite hacer debugging se llama?
        Chrome DevTools
###### Razón: Es una herramienta de desarrollo integrada en el navegador web Google Chrome que permite a los desarrolladores web depurar y analizar su código. 
###### Vídeo: [Debugging](https://platzi.com/clases/3213-javascript-closures-scope/50369-debugging/)
------------