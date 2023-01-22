Curso Básico de JavaScript
#### ¿Qué es un array?
		 Es una estructura de datos de tipo objeto.
###### Razón: Un array es una estructura de datos que permite almacenar una serie de datos localizados por índices y separados por comas.
###### Vídeo: [¿Qué es un array?](https://platzi.com/clases/1814-basico-javascript/26303-arrays/)
------------
#### ¿Qué resultado podría esperar de ésta validación? 4 == “4”
		 TRUE
###### Razón: El operador  de comparación == compara dos variables solamente por su valor. Por ejemplo: "4" de tipo string y 4 de tipo número son iguales.
###### Vídeo: [Operadores: Asignación, Comparación y Aritméticos.](https://platzi.com/clases/1814-basico-javascript/26300-operadores-asignacion-comparacion-y-aritmeticos/)
------------
#### ¿Es correcta la siguiente sentencia ? 
#### switch (false) { 
#### case false: console.log("Soy falso :( ") 
#### case true: console.log("Soy verdadero!") 
#### }
		 No
###### Razón: Es incorrecta debido a que falta el break.
###### Vídeo: [Switch](https://platzi.com/clases/1814-basico-javascript/26302-switch/)
------------
#### ¿Cuáles son los tipos de scope tenemos?
		 Scope global y Scope local.
###### Razón: Existen dos tipos de scope: global y local. El scope local puede ser de función o de bloque. Un bloque es toda porción de código que está encerrada entre llaves {}, estos pueden ser los bloques: función, if, else, while, y for. Las variables globales son aquellas que se encuentran declaradas fuera de los bloques de código o funciones .El scope global es el entorno donde las variables globales pueden ser accedidas desde cualquier lugar del código.
###### Vídeo: [Scope](https://platzi.com/clases/1814-basico-javascript/26296-scope/)
------------
#### ¿Qué resultado podría esperar de ésta validación? 1 = "1"
		 Syntax Error
###### Razón: Para asignar valor a una variable se hace mediante el operador = , no es posible asignar un valor a 1.
###### Vídeo: [Operadores: Asignación, Comparación y Aritméticos.](https://platzi.com/clases/1814-basico-javascript/26300-operadores-asignacion-comparacion-y-aritmeticos/)
------------
#### ¿Qué es una variable?
		 Es la representación de un espacio en memoria.
###### Razón: Una variable es la representación de un lugar que reserse reservavamos en memoria para guardar un valor. El valor puede ser cualquier tipo de dato, inclusive objetos o funciones.
###### Vídeo: [Qué es una variable en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/)
------------
#### ¿Qué podemos esperar al llamar al método .pop(); ?
		 Borrar el último elemento de mi array.
###### Razón: El método pop elimina el elemento del final del array original.
###### Vídeo: [¿Qué es un array?](https://platzi.com/clases/1814-basico-javascript/26303-arrays/)
------------
#### ¿Qué resultado podría esperar de ésta validación? 6 === "6"
		 False
###### Razón: El operador ===, compara dos variables por su valor y tipo de dato. Por ejemplo: "6" de tipo string y 6 de tipo número no son iguales. Solamente 6 y 6, ambos de tipo número son iguales.
###### Vídeo: [Operadores: Asignación, Comparación y Aritméticos.](https://platzi.com/clases/1814-basico-javascript/26300-operadores-asignacion-comparacion-y-aritmeticos/)
------------
#### ¿Qué método llamaríamos para saber el index de un elemento de mi array?
		 indexOf()
###### Razón: El método indexOf muestra el índice del elemento especificado como argumento.
###### Vídeo: [¿Qué es un array?](https://platzi.com/clases/1814-basico-javascript/26303-arrays/)
------------
#### ¿Cómo se le conoce a la siguiente sentencia? var nombre;
		 Declarar una variable.
###### Razón: Para declarar una variable se usa la palabra reservada var seguido del nombre de la variable.
###### Vídeo: [Qué es una variable en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/)
------------
#### ¿Por qué decimos que JavaScript es un lenguaje dinámico?
		 Porque es un lenguaje que corre en tiempo de ejecución.
###### Razón: JavaScript corre directamente en la etapa de runtime sin una etapa de compilación previa. Esto permite probar código inmediatamente.
###### Vídeo: [¿Qué es JavaScript y para qué sirve?](https://platzi.com/clases/1814-basico-javascript/26290-que-es-javascript/)
------------
#### ¿Cómo se le llama al siguiente ejemplo de funciones?
#### function myfunction() { 
#### ...
#### }
		 Función declarativa.
###### Razón: En las funciones declarativas, se usa la palabra reservada function al inicio para poder declarar la función: function saludar(nombre){...}
###### Vídeo: [Qué son las funciones en JavaScript](https://platzi.com/clases/1814-basico-javascript/26294-funciones/)
------------
#### ¿Cómo podemos crear notas o comentarios en nuestro JavaScript?
		 //...
###### Razón: Para realizar comentarios en JavaScript se puede mediante //, y para comentar multiples líneas /* ... */
###### Vídeo:
------------
#### ¿Cómo se llama al siguiente ejemplo de funciones?
#### var myFunction = function() { 
#### ...
#### }
		 Función expresiva.
###### Razón: En la expresión de función o expresiva la declaración se inicia con la palabra reservada var, donde se generará una variable que guardará una función anónima.
###### Vídeo: [Qué son las funciones en JavaScript](https://platzi.com/clases/1814-basico-javascript/26294-funciones/)
------------
#### ¿Cómo se le conoce a la siguiente sentencia? nombre = "Diego"
		 Inicializar una variable.
###### Razón: Para inicializar una variable se usa el operador de asignación seguido del valor deseado.
###### Vídeo: [Qué es una variable en JavaScript](https://platzi.com/clases/1814-basico-javascript/26293-variables/)
------------
#### ¿Qué significa Coerción en JS?
		 Es el proceso de convertir el valor de un tipo a otro.
###### Razón: La coerción consiste en transformar de un tipo de dato a otro de una variable. Existen dos tipos de coerción: implícita y explícita.
###### Vídeo: [Coerción](https://platzi.com/clases/1814-basico-javascript/26298-coercion/)
------------
#### ¿Qué es el hoisting en Javascript?
		 Es cuando las declaraciones de variables y funciones se procesan antes de ejecutar cualquier código.
###### Razón: Hoisting es un término para describir que las declaraciones de variables y funciones son desplazadas a la parte superior del scope más cercano, scope global o de función. Esto sucede solamente con las declaraciones y no con las asignaciones.
###### Vídeo: [Hoisting](https://platzi.com/clases/1814-basico-javascript/26297-hoisting/)