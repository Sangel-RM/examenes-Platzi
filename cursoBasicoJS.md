# Curso Básico de JavaScript
*Si alguna respuesta está incorrecta, puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es un array?
		 Es una estructura de datos de tipo objeto.
###### Razón: Son estructuras de datos de tipo objeto. Pueden contener números, strings, otros arrays, otros objetos, etc.
###### Vídeo: [Arrays](https://platzi.com/clases/1814-basico-javascript/26303-arrays/ "Arrays")
------------
#### ¿Qué resultado podría esperar de esta validación?
> 4 == "4"

		 TRUE 
###### Razón: El operador de comparación con doble símbolo de igualdad compara solo los valores, sin tomar en cuenta su tipo. Ambos valores son 6, por ello el resultado de compararlos con este operador es true.
###### Vídeo: [Operadores: Asignación, Comparación y Aritméticos](https://platzi.com/clases/1814-basico-javascript/26300-operadores-asignacion-comparacion-y-aritmeticos/ "Operadores: Asignación, Comparación y Aritméticos")
------------
#### ¿Es correcta la siguiente sentencia?
~~~
switch (false) {
 	case false: console.log("Soy falso :(")
 	case true: console.log("Soy verdadero!")
}
~~~

		 No.
###### Razón: Hay que colocar la sentencia break; después de cada caso. Si no se coloca, el código ejecutará todos los casos dento del switch.
###### Vídeo: [Switch](https://platzi.com/clases/1814-basico-javascript/26302-switch/31089-html-anatomia-de-una-pagina-web/ "Switch")
------------
#### ¿Cuáles son los tipos de scope que tenemos?
 		 Scope global y Scope local.
###### Razón: Existen dos tipos de scope en JavaScrit. El scope local existe por ejemplo cuando creamos una función, dentro de la cual podemos crear variables que estarán disponibles solo para ese entorno local, y desde donde también podremos acceder a variables creadas en el entorno global. Por el contrario, desde el entorno global no podemos acceder a variables creadas en un entorno local.
###### Vídeo: [Scope](https://platzi.com/clases/1814-basico-javascript/26296-scope/ "Scope")
------------
#### ¿Qué resultado podría esperar de esta validación?
> 1 = "1"

		 Syntax Error.
###### Razón: No se está usando la sintaxis adecuada en JavaScript para asignar un valor. 
###### Vídeo: [Operadores: Asignación, Comparación y Aritméticos](https://platzi.com/clases/1814-basico-javascript/26300-operadores-asignacion-comparacion-y-aritmeticos/ "Operadores: Asignación, Comparación y Aritméticos")
------------
#### ¿Qué es una variable?
		 Es la representación de un espacio en memoria.
###### Razón: Cuando creamos una variable reservamos un lugar en memoria para que guarde un valor.
###### Vídeo: [Variables en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/ "Variables en JavaScript")
------------
#### ¿Qué podemos esperar al llamar al método .pop();?
		 Borrar el último elemento de mi array.
###### Razón: El método .pop(); eliminará el último elemento de un array. En este sentido, si tenemos un array de 5 elementos, .pop() eliminará el elemento en el índice 4.
###### Lectura: [Eliminando elementos de un array](https://platzi.com/clases/1814-basico-javascript/28608-eliminando-elementos-de-un-array/ "Eliminando elementos de un array")
------------
#### ¿Qué resultado podría esperar de esta validación?
> 6 === "6"

		 FALSE.
###### Razón: El operador de comparación con triple símbolo de igualdad compara, además de los valores, el tipo de valores. El primer valor 6 es de tipo número y el segundo es de tipo string, por ello el resultado de compararlos con este operador es false.
###### Vídeo: [Operadores: Asignación, Comparación y Aritméticos](https://platzi.com/clases/1814-basico-javascript/26300-operadores-asignacion-comparacion-y-aritmeticos/ "[Operadores: Asignación, Comparación y Aritméticos")
------------
#### ¿Qué método llamaríamos para saber el index de un elemento de mi array?
		 indexOf()
###### Razón: Con el método indexOf() podemos conocer la posición dentro de un array del elemento que le indiquemos.
###### Vídeo: [Arrays](https://platzi.com/clases/1814-basico-javascript/26303-arrays/ "Arrays")
------------
#### ¿Cómo se le conoce a la siguiente sentencia?
> var nombre;

		 Declarar una variable.
###### Razón: Para declarar una variable se escribe la palabra reservada var seguida del nombre que le queramos dar a la variable y por último un punto y coma (;).
###### Vídeo: [Variables en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/ "Variables en JavaScript")
------------
#### ¿Por qué decimos que JavaScript es un lenguaje dinámico?
		 Porque es un lenguaje que corre en tiempo de ejecución.
###### Razón: JavaScript es un lenguaje dinámico, pues puedes escribirlo y correrlo inmediatamente (runtime) en el navegador para ver su resultado, sin esperar que alguna herramienta externa lo compile.
###### Vídeo: [¿Qué es JavaScript?](https://platzi.com/clases/1814-basico-javascript/26290-que-es-javascript/ "¿Qué es JavaScript?")
------------
#### ¿Cómo se le llama al siguiente ejemplo de funciones?
~~~
function myfunction() {
	...
}
~~~
		 Función declarativa.
###### Razón: Las funciones declarativas son aquellas que se declaran o definen con la palabra reservada function, seguida del nombre que queramos darle a la función, entre paréntesis la lista de parámetros de la función separados por comas, y entre llaves las declaraciones de JavaScript que definen la función.
###### Vídeo: [Funciones en JavaScript](https://platzi.com/clases/1814-basico-javascript/26294-funciones/ "Funciones en JavaScript")
------------
#### ¿Cómo podemos crear notas o comentarios en nuestro JavaScript?
		 // …
###### Razón: Para generar comentarios en JavaScript que no serán corridos como código por el navegador, se escribe doble slash "//".
###### Vídeo: [Variables en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/ "Variables en JavaScript")
------------
#### ¿¿Cómo se llama al siguiente ejemplo de funciones?
~~~
var myFunction = function() {
	...
}
~~~
		 Función expresiva.
###### Razón: Las funciones expresivas son aquellas que se declaran o definen con la palabra reservada var, seguida del nombre que queramos darle a la variable que contendrá a la función, luego la palabra reservada function, entre paréntesis la lista de parámetros de la función separados por comas, y entre llaves las declaraciones de JavaScript que definen la función. La función puede o no tener un nombre, en caso de no tenerlo, es llamada función anónima.
###### Vídeo: [Funciones en JavaScript](https://platzi.com/clases/1814-basico-javascript/26294-funciones/ "Funciones en JavaScript")
------------
#### ¿Cómo se le conoce a la siguiente sentencia?
> nombre = "Diego"

		 Inicializar una variable.
###### Razón: Inicializar una variable consiste en escribir el nombre de la variable, seguido del símbolo de igualdad y luego el valor que se le asignará.
###### Vídeo: [Variables en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/ "Variables en JavaScript")
------------
#### ¿Qué significa Coerción en JS?
		 Es el proceso de convertir el valor de un tipo a otro.
###### Razón: La coerción consiste en cambiarle el tipo a un valor dado. Ésta puede ser implícita o explícita.
###### Vídeo: [Coerción](https://platzi.com/clases/1814-basico-javascript/26298-coercion/ "Coerción")
------------
#### ¿Qué es el hoisting en Javascript?
		 Es cuando las declaraciones de variables y funciones se procesan antes de ejecutar cualquier código.
###### Razón: El hositing es el proceso mediante el cual JS procesa en memoria a las variables (palabra reservada var) y las funciones (palabra reservada function) antes de que se procese cualquier otro tipo de código.
###### Vídeo: [Hoisting](https://platzi.com/clases/1814-basico-javascript/26297-hoisting/ "Hoisting")