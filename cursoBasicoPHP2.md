# Curso Básico de PHP: Arreglos, Funciones y Estructuras de Control
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es lo primero que debería hacer si necesito realizar alguna operación con cualquier arreglo?
		 Buscar en la documentación. PHP tiene la mayoría de operaciones que puedes hacer con los arreglos implementadas nativamente en forma de funciones.

###### Razón: En el siguiente enlace se puede visualizar la lista de funciones de PHP y su descripción [Funciones en PHP](https://www.php.net/manual/es/indexes.functions.php)
###### Vídeo: [Aprende a reutilizar tu código: funciones](https://platzi.com/clases/2794-php-arreglos-funciones/46565-aprende-a-reutilizar-tu-codigo-funciones/)
------------
#### ¿Qué estructura debería utilizar si necesito saber si una persona es mayor o menor de edad?
		 if/else
###### Razón: La condición IF/ELSE ayuda a tomar decisiones si una condición se cumple o no. En este caso si una persona en mayor de edad, entra al bloque if de lo contrario entra al bloque de else.
###### Vídeo: [Aprende a tomar decisiones con if y else](https://platzi.com/clases/2794-php-arreglos-funciones/46557-aprende-a-tomar-decisiones-con-if-y-else/)
------------
#### ¿Qué tipo de dato necesita una sentencia if para poder funcionar?
		 Necesita un tipo de dato booleano. Esto incluye comparaciones numéricas por medio de operadores relacionales, ya que al final acaban siendo operaciones booleanas.
###### Razón: El ciclo IF/ELSE necesita de un valor booleano, es decir TRUE O FALSE, para funcionar ya que si una condición NO se cumple entra a un bloquo y SÍ se cumple entra a otro bloque.
###### Vídeo: [Aprende a tomar decisiones con if y else](https://platzi.com/clases/2794-php-arreglos-funciones/46557-aprende-a-tomar-decisiones-con-if-y-else/)
------------
#### ¿Qué sucede cuando no usamos la palabra reservada `break;` dentro de un caso en la estructura switch/case?
		 Se seguirán ejecutando los demás casos hasta que termine o hasta que se encuentre con un `break;`.
###### Razón: break finaliza la ejecución de la estructura for , foreach , while , do-while o switch en curso. break finaliza la ejecución de la estructura control en curso.
###### Vídeo: [Cómo organizar tu código con switch](https://platzi.com/clases/2794-php-arreglos-funciones/46558-como-organizar-tu-codigo-con-switch/)
------------
#### ¿Es obligatorio siempre poner un caso default en la estructura switch/case?
		 Falso, el caso por defecto es opcional.
###### Razón: La opción default, es opcional, indica la sentencia que se ejecuta en caso de que el valor de la variable $var no se corresponda con ninguna de las casos expresados. 
###### Vídeo: [Cómo organizar tu código con switch](https://platzi.com/clases/2794-php-arreglos-funciones/46558-como-organizar-tu-codigo-con-switch/)
------------
#### Este ciclo se conoce porque es un ciclo indefinido y se basa en una condicional para saber si se debe ejecutar el código que tiene dentro o no.
		 while
###### Razón: El propósito de WHILE es repetir un bloque de código mientras una condición se mantenga verdadera.
###### Vídeo: [Ciclo While](https://platzi.com/clases/2794-php-arreglos-funciones/46560-ciclo-while/)
------------
#### ¿Qué sucede si ponemos un `while(true)`?
		 El ciclo se repetirá de forma infinita, consumiendo recursos de mi computadora hasta que pare el programa manualmente.
###### Razón: Para que un ciclo while se repita necesita que  la condición sea TRUE, y si esta condición se mantiene en TRUE se repetira infinitamente.
###### Vídeo: [Ciclo While](https://platzi.com/clases/2794-php-arreglos-funciones/46560-ciclo-while/)
------------
#### Este ciclo se conoce porque es un ciclo indefinido. Su principal característica es que el código se ejecuta por lo menos una vez, ya después la condición determinará si el ciclo se vuelve a ejecutar o no.
		 do... while
###### Razón: El ciclo do-while es un tipo de estructura repetitiva eficiente. Lo que lo diferencia con el while es que en la estructura do-while la condición se evalúa al finalizar el ciclo, esto hace que las instrucciones se ejecuten cuando menos una vez.
###### Vídeo: [¿Do... While](https://platzi.com/clases/2794-php-arreglos-funciones/46561-do-while/)
------------
#### Este es un ciclo definido porque se sabe exactamente cuándo va a terminar. Es uno de los ciclos más conocidos y se caracteriza por definir e incrementar su contador dentro de sus paréntesis.
		 for
###### Razón: El ciclo for es uno de los más utilizados en programación debido a que permite repetir varias instrucciones  un cierto número de ocasiones (iteraciones). Se emplea en el recorrido de vectores, matrices y estructuras, entre otros.
###### Vídeo: [Ciclo For](https://platzi.com/clases/2794-php-arreglos-funciones/46562-ciclo-for/)
------------
#### ¿Cuál sería el resultado del siguiente código?
         <?php
         $contador = 0;
         while($contador < 10) {
         echo $contador . "\n";
         } 

> Un ciclo infinito
###### Razón: La condición del ciclo WHILe es que mientras la variable $contadador sea menor a 0 se imprimira el valor de la variable, pero el valor de la variable nunca cambia ya que se estableció en 0, por lo que se ciclara infinitamente.
###### Vídeo: [Ciclo For](https://platzi.com/clases/2794-php-arreglos-funciones/46562-ciclo-for/)
------------
#### Este ciclo es capaz de recorrer cada elemento de un arreglo sin necesidad de decirle cuántos elementos tiene:
		 foreach
###### Razón: El bucle foreach es un tipo especial de bucle que permite recorrer estructuras que contienen varios elementos (como matrices, recursos u objetos) sin necesidad de preocuparse por el número de elementos.
###### Vídeo: [Ciclo foreach](https://platzi.com/clases/2794-php-arreglos-funciones/46563-ciclo-foreach/)
------------
#### ¿Cuál de las siguientes funciones me permite convertir un string en un array?
		 explode()
###### Razón: Devuelve un array de string, siendo cada uno un substring del parámetro string formado por la división realizada por los delimitadores indicados en el parámetro string separator.
###### Vídeo: [Manipulando arreglos](https://platzi.com/clases/2794-php-arreglos-funciones/46555-manipulando-arreglos/)
------------
#### ¿Cómo podemos visualizar a las funciones?
		 Como cajas mágicas a las cuales les damos ciertos datos y nos devuelven el resultado que estamos esperando.
###### Razón: Una función es un bloque de código que realiza alguna operación. Una función puede definir opcionalmente parámetros de entrada que permiten a los llamadores pasar argumentos a la función. Una función también puede devolver un valor como salida
###### Vídeo: [Aprende a reutilizar tu código: funciones](https://platzi.com/clases/2794-php-arreglos-funciones/46565-aprende-a-reutilizar-tu-codigo-funciones/)
------------
#### ¿Para qué me sirven los parámetros en las funciones de PHP?
		 Para poder permitirle a cualquier programador enviar los datos que mi función necesita para trabajar.
###### Razón: Los parámetros se usan para mandar valores a las funciones. Una función trabajará con los parámetros para realizar las acciones. Por decirlo de otra manera, los parámetros son los valores de entrada que recibe una función.
###### Vídeo: [Parámetros en las funciones](https://platzi.com/clases/2794-php-arreglos-funciones/46566-parametros-en-las-funciones/)
------------
#### ¿Cómo programarías una función para multiplicar dos números, pero que el segundo número por defecto es 1?
		<?php
		function multiplicar($numero1, $numero2 = 1) {
		return $numero1 * $numero2;
		}
###### Razón: Para establecer un valor por defecto de algún parámetro se asigna con el signo =, al parámetro que se desea.
###### Vídeo: [Profundicemos en los parámetros](https://platzi.com/clases/2794-php-arreglos-funciones/46567-profundicemos-en-los-parametros/)
------------
#### ¿Cómo funciona el operador de nave espacial? `<=>`
		 Devuelve -1 si el número de la izquierda es menor que el de la derecha, devuelve 0 si ambos son iguales o devuelve 1 si el número de la izquierda es mayor que el de la derecha.
###### Razón: El operador nave espacial se emplea para comparar dos expresiones. Devuelve -1, 0 o 1 cuando  a es respectivamente menor, igual, o mayor que b. [Operador Nave Espacial](https://www.php.net/manual/es/migration70.new-features.php#migration70.new-features.spaceship-op)
###### Vídeo: [Operador de nave espacial](https://platzi.com/clases/2794-php-arreglos-funciones/46569-operador-de-nave-espacial/)
------------
#### ¿Es posible utilizar las estructuras de control de PHP cuando trabajamos con HTML?
		 Verdadero. Basta con poner las etiquetas de apertura y cierre de PHP para empezar a usar dichas estructuras.
###### Razón: PHP es un lenguaje de scripting del lado del servidor. Esto significa que un script de PHP se ejecuta en el servidor, la salida se genera en el servidor, y el resultado se envía como HTML al navegador del cliente para ser desplegado.
###### Vídeo: [Cómo interactúa PHP con HTML](https://platzi.com/clases/2794-php-arreglos-funciones/46575-como-interactua-php-con-html/)
------------
#### Cuando trabajamos con HTML dentro de PHP, ¿qué extensión debería tener mi archivo?
		 PHP
###### Razón: Si se desea trabajar con html y php simultaneamente en el mismo archivo, este debe de llevar la  extensión PHP.
###### Vídeo: [Cómo interactúa PHP con HTML](https://platzi.com/clases/2794-php-arreglos-funciones/46575-como-interactua-php-con-html/)
------------
#### ¿Puedo declarar dos variables contadoras dentro de un ciclo for?
		 Verdadero. Simplemente separamos cada variable contadora con una coma.
###### Razón: Se puede usar más de una variable dentro de la condición del for, solo que estos deben ser separados por ','. for($i=0,$j=2;$i<$j;i++,j--){}
###### Vídeo: [Ciclo For](https://platzi.com/clases/2794-php-arreglos-funciones/46562-ciclo-for/)
------------
#### ¿Qué función me ayuda a determinar si cierto elemento se encuentra dentro de un array en PHP?
		 in_array()
###### Razón: Comprueba si un valor existe en un array. Busca la aguja (needle) en el pajar (haystack) usando una comparación flexible a menos que esté establecido strict. [in_array](https://www.php.net/manual/es/function.in-array.php)
###### Vídeo: [Validando las letras de los usuarios](https://platzi.com/clases/2794-php-arreglos-funciones/46573-validando-las-letras-de-los-usuarios/)