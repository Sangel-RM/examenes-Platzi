# Curso Intermedio de PHP: Entornos Virtuales y Funciones Avanzadas
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### Entro a trabajar a una empresa que tiene un sistema desarrollado con PHP 5. ¿Qué debería hacer para decidir si vale la pena actualizar?
		 Evaluar cuál sería el costo de actualizar el sistema, si vale la pena hacerlo para las necesidades de la empresa en cuestión y qué tanto tiempo tomaría hacer esa actualización.
###### Razón: Actualizar un sistema aveces puede llevar mucho tiempo, es por eso que antes de realizar esa tarea se debe realizar una evaluación para saber el costo de actualizar el sistema. 
###### Vídeo: [¿Debería seguir usando versiones antiguas de PHP?](https://platzi.com/clases/3151-php-entornos-funciones/49747-deberia-seguir-usando-versiones-antiguas-de-php/)
------------
#### ¿Qué versión de PHP debería elegir si quiero experimentar con las cosas más nuevas del lenguaje o incluso con implementaciones futuras?
		 La versión más reciente que se haya lanzado, o incluso versiones beta, ya que estas nos permiten dar un vistazo al futuro del lenguaje.
###### Razón: Para saber las últimas características de PHP, se pueden obtener a través de la última versión de PHP o versiones beta. [Versiones de PHP](https://www.php.net/downloads)
###### Vídeo: [¿Debería seguir usando versiones antiguas de PHP?](https://platzi.com/clases/3151-php-entornos-funciones/49747-deberia-seguir-usando-versiones-antiguas-de-php/)
------------
#### Quiero empezar a desarrollar mi propio proyecto en PHP que en un futuro pondré en producción. ¿Qué versión de PHP debería usar?
		 La última versión oficial o LTS, ya que esa versión nos asegura que tendrá soporte a futuro o que ya es una versión que tiene menor probabilidad de bugs.
###### Razón: Una versión LTS (Long Term Support) son versiones o ediciones especiales diseñadas para tener soportes durante un período más largo que el normal. La información sobre las versiones LTS de PHP se puede consultar a través de: [Supported Versions](https://www.php.net/supported-versions.php)
###### Vídeo: [¿Debería seguir usando versiones antiguas de PHP?](https://platzi.com/clases/3151-php-entornos-funciones/49747-deberia-seguir-usando-versiones-antiguas-de-php/)
------------
#### Si necesito saber cómo funciona una función que PHP ya tiene predefinida, ¿en dónde debería buscar información?
		 En la documentación oficial de PHP.
###### Razón: La documentación oficial se puede encontrar en [Manual de PHP](https://www.php.net/manual/es/). En la documentación se puede encontrar principalmente referencias de funciones, aunque también contiene una referencia del lenguaje, explicaciones de algunas de las características importantes de PHP, y otra información suplementaria.
###### Vídeo: [Documentación: la biblia de PHP](https://platzi.com/clases/3151-php-entornos-funciones/49748-documentacion-la-biblia-de-php/)
------------
#### ¿Para qué nos sirve PHPDoc?
		 Para documentar nuestras clases o funciones. Ayudan al editor de código a dar sugerencias con mayor información o incluso podemos usar generadores de documentación que lean PHPDoc.
###### Razón: PHPDoc es una adaptación de javadoc para php que define un estándar oficial para comentar código php. Ofrece ventajas como; Hace comentarios que pueda leerse en un método estándar para animar a los programadores a definir y comentar los aspectos del código que normalmente se ignoran. Permite que los generadores de documentos externos como phpDocumentor puedan crear la documentación API en buen formato y fácil de entender. 
###### Vídeo: [¿Qué es PHP Doc?](https://platzi.com/clases/3151-php-entornos-funciones/49749-que-es-php-doc/)
------------
#### Si tengo varios proyectos que usan diferentes versiones de PHP, ¿qué debería hacer para que mi versión de PHP instalada no rompa mis proyectos que usan otras versiones?
		 Usar entornos virtuales.
###### Razón: Un entorno virtual permite encapsular todo lo necesario para que un proyecto pueda funcionar con las versiones que este mismo requiere. Esto a su vez permite que se pueda tener varios proyectos con distintas versiones.
###### Vídeo: [¿Para qué sirven los entornos virtuales?](https://platzi.com/clases/3151-php-entornos-funciones/49750-para-que-sirven-los-entornos-virtuales/)
------------
#### ¿Para qué nos sirve un Virtual Host?
		 Nos ayuda a generar una URL ficticia que solo funciona en nuestra computadora para enlazar con algún proyecto que tenga en mi servidor local.
###### Razón: Es una forma de que varias páginas web puedan funcionar al mismo tiempo en un mismo servidor. Se pueden definir por direcciones IP o por nombres de dominio
###### Vídeo: [¿Qué son los Virtual Hosts?](https://platzi.com/clases/3151-php-entornos-funciones/49806-que-son-los-virtual-hosts/)
------------
#### Si yo declaré una constante dentro de un bloque if, ¿de qué forma declaré esa constante?
		 Usando la función declare().
###### Razón: Una constante es un identificador para un valor simple. Como el nombre sugiere, este valor no puede variar durante la ejecución del script. define("Constante","HOLA") Define una constante con nombre en tiempo de ejecución.
###### Vídeo: [Constantes en PHP](https://platzi.com/clases/3151-php-entornos-funciones/49807-constantes-en-php/)
------------
#### Si yo declaré una constante dentro una clase, ¿de qué forma declaré esa constante?
		 Usando la palabra reservada const.
###### Razón: Al emplear la palabra reservada const, solamente los datos escalares (boolean, integer, float y string) pueder estar contenidos en constante. const HOLA = 'HELLO';
###### Vídeo: [Constantes en PHP](https://platzi.com/clases/3151-php-entornos-funciones/49807-constantes-en-php/)
------------
#### ¿Qué es una constante mágica?
		 Una constante que puede cambiar su valor dependiendo del entorno en la que es invocada. Realmente para PHP no son constantes.
###### Razón: Hay nueve constantes mágicas que cambian dependiendo de dónde se emplean. Por ejemplo, el valor de __LINE__ depende de la línea en que se use en el script. Todas estas constantes «mágicas» se resuelven durante la compilación, a diferencia de las constantes normales que lo hacen durante la ejecución. [Constantes predefinidas](https://www.php.net/manual/es/language.constants.predefined.php)
###### Vídeo: [Constantes en PHP](https://platzi.com/clases/3151-php-entornos-funciones/49807-constantes-en-php/)
------------
#### ¿Qué pasaría si, en lugar de ponerle un nombre a una variable después del signo de dólar, escribo otra variable?
		 PHP primero evaluaría el valor de esa otra variable para determinar el nombre de la variable que originalmente estaba escribiendo. Se llaman variables variables.
###### Razón: Una variable variable toma el valor de una variable y lo trata como el nombre de una variable. 
###### Vídeo: [¿Variables... variables?](https://platzi.com/clases/3151-php-entornos-funciones/49757-variables-variables/)
------------
#### ¿Cuál sería el resultado del siguiente código?
```php
<?php
$variable = "edad";
$$variable = 14;
echo $edad;
```
		 
		 14
###### Razón: En ese ejemplo se ha definido $variale con el valor de "edad", entonces en la siguiente línea se accede a la variable variable colocando el doble signo de dolar, entonces a la variable de edad se le asigna el valor de 14, y al imprimirlo sale 14.
###### Vídeo: [¿Variables... variables?](https://platzi.com/clases/3151-php-entornos-funciones/49757-variables-variables/)
------------
#### Si necesito usar una variable externa dentro de una función de PHP, ¿qué opciones tengo?
		 Puedo pasarla como parámetro, usar la palabra reservada global o usar el arreglo $GLOBALS.
###### Razón: $GLOBALS, Hace referencia a todas las variables disponibles en el ámbito global. Es un array asociativo que contiene las referencias a todas la variables que están definidas en el ámbito global del script. Los nombres de las variables son las claves del array. 
[$GLOBALS](https://www.php.net/manual/es/reserved.variables.globals.php)
###### Vídeo: [Scope de PHP](https://platzi.com/clases/3151-php-entornos-funciones/49761-scope-de-php/)
------------
#### ¿Qué función de PHP deberíamos usar para hacer redirecciones a otras páginas?
		 header()
###### Razón: header() es usado para enviar encabezados HTTP sin formato. 
###### Vídeo: [Redirecciones](https://platzi.com/clases/3151-php-entornos-funciones/49809-redirecciones/)
------------
#### Si necesito definir el valor de una variable con base en un caso u otro, ¿qué estructura de control debería utilizar?
		 match
###### Razón: La expresión match ramifica la evaluación basada en una comprobación de identidad de un valor. De forma similar a una sentencia switch, una expresión match tiene una expresión de sujeto que se compara con múltiples alternativas. A diferencia de switch, se evaluará a un valor muy parecido al de las expresiones ternarias. A diferencia de switch, la comparación es una comprobación de identidad (===) en lugar de una comprobación de igualdad débil (==). [match](https://www.php.net/manual/es/control-structures.match.php)
###### Vídeo: [Match](https://platzi.com/clases/3151-php-entornos-funciones/49810-match/)
------------
#### 
##### <?php
##### function bark() {
##### return "woof!";
##### }
##### $function = "bark";
##### echo $function();

		 woof
###### Razón: Si un nombre de variable tiene paréntesis anexos a él, PHP buscará una función con el mismo nombre que lo evaluado por la variable, e intentará ejecutarla. Como la variable $function es igual a "bark", entonces al hacer al echo y colocando los paréntesis, busca si el valor corresponde a una función, en esta caso sí, la función bark sí existe e imprime "woof".
###### Vídeo: [Funciones variables](https://platzi.com/clases/3151-php-entornos-funciones/49758-funciones-variables/)
------------
#### ¿Qué significa pasar un parámetro por referencia?
		 Significa que, en lugar de hacer una copia de una variable, estoy pasando la referencia en memoria de la variable orignal. Esto me permite tener control sobre la variable original.
###### Razón: Pasar por referencia significa que además de pasar el valor a la función, se pasa la referencia a la variable original. De este modo, si el valor cambia dentro de la función, también cambiará en la variable original. Para indicar que el argumento de una función se pasa por referencia, se utiliza el símbolo & (ampersand, et) delante del argumento. &$valor1
###### Vídeo: [Parámetros por referencia](https://platzi.com/clases/3151-php-entornos-funciones/49811-parametros-por-referencia/)
------------
#### ¿Cuál sería la forma correcta de pasar parámetros por defecto a una función?
		 function suma($n1, $n2 = 5)...
###### Razón: Para asignar un valor por defecto a un parámetro se asigna mediante el signo de igual, seguido del valor por defecto, y como buena práctica los parámetros que iran por defecto deben ir a lo último.
###### Vídeo: [Argumentos a profundidad](https://platzi.com/clases/3151-php-entornos-funciones/49812-argumentos-a-profundidad/)
------------
#### ¿Cuál es la forma correcta de llamar a esta función usando named arguments? 
function suma ( $n1, $n2) 
{ return $n1 + $n2; }

		 suma( n1: 4, n2: 6, );
###### Razón: Los named arguments permiten pasar argumentos a una función basandose en el nombre del parámetro. En el ejemplo el nombre de los parámetros es $n1 y n$2, entonces al llamar la función se coloca el nombre del parámetro y su valor.
###### Vídeo: [Named arguments](https://platzi.com/clases/3151-php-entornos-funciones/49759-named-arguments/)
------------
#### Las funciones anónimas son similares a los callbacks de JavaScript, sin embargo, en PHP también se llaman...
		 Closures
###### Razón: Las funciones anónimas, también conocidas como cierres/closures, permiten la creación de funciones que no tienen un nombre especificado. Son más útiles como valor de los parámetros de callback/llamadas de retorno, pero tienen muchos otros usos. Las funciones anónimas están implementadas utilizando la clase Closure. [Funciones anónimas](https://www.php.net/manual/es/functions.anonymous.php)
###### Vídeo: [Funciones anónimas](https://platzi.com/clases/3151-php-entornos-funciones/49762-funciones-anonimas/)
------------
#### Si necesito usar una variable externa dentro de una función anónima de PHP, ¿qué opciones tengo?
		 Debo agregar la palabra reservada use junto con la variable en mi función.
###### Razón: Las funciones anónimas también pueden usar variables fuera de su alcance. Cualquier variable debe ser pasada al constructor use.$name = function() use ($name1){};
###### Vídeo: [Funciones anónimas](https://platzi.com/clases/3151-php-entornos-funciones/49762-funciones-anonimas/)
------------
#### ¿Cómo simplificarías el siguiente código usando arrow functions? $multiplied = array_map(function($current) { return $current * 2; }, [2, 3, 4]);
		 $multiplied = array_map( fn($current) => $current * 2, [2, 3, 4] );
###### Razón: Las funciones de flecha/arrow functions fueron introducidas en PHP 7.4 como una sintaxis más concisa para las funciones anónimas. En este caso la función en un arrow function se coloca sola el fn, seguido de los parámetros, después la flecha => y el código a ejecutar.
###### Vídeo: [Arrow functions](https://platzi.com/clases/3151-php-entornos-funciones/49760-arrow-functions/)
------------
#### ¿Es posible especificar qué tipo de dato queremos recibir en nuestras funciones?
		 Verdadero, PHP permite declaraciones de tipo escalar las cuales nos permiten definir el tipo de dato que esperamos recibir en una función.
###### Razón: Para especificar el tipo de dato a recibir se debe colocar antes del nombre de parámetro el tipo de dato que se recibirá. function datos_personales(strig $nombre,int $edad){}. A esto se le llama declaración de tipo escalar, estas declaraciones permiten a las funciones requerir que los parámetros sean de cierto tipo durante una llamada. Si el valor dado es de un tipo incorrecto, se generará un error: en PHP 5, este error es un error fatal recuperable, mientras que a partir de PHP 7 lanzará una excepción TypeError.
###### Vídeo: [Declaraciones de tipo escalar](https://platzi.com/clases/3151-php-entornos-funciones/49764-declaraciones-de-tipo-escalar/)
------------
#### ¿Cómo definirías que en el primer parámetro de la siguiente función quieres recibir un tipo de dato entero? 
function suma($n1, $n2) { return $n1 + $n2; }

		 function suma(int $n1, $n2) { return $n1 + $n2; } 
###### Razón:  Para especificar el tipo de dato a recibir se debe colocar antes del nombre de parámetro el tipo de dato que se recibirá. function datos_personales(strig $nombre,int $edad){}.
###### Vídeo: [Declaraciones de tipo escalar](https://platzi.com/clases/3151-php-entornos-funciones/49764-declaraciones-de-tipo-escalar/)
------------
#### ¿Cómo expresarías que la siguiente función va a devolver sí o sí un entero? function suma($n1, $n2) { return $n1 + $n2; }

		 function suma($n1, $n2) : int { return $n1 + $n2; }
###### Razón: Luego de que se han terminando de incluir los parámetros, se coloca : seguido del tipo de dato que se desea retornar. function saludo(string $msj):string{}
###### Vídeo: [Declaraciones de tipo devolución](https://platzi.com/clases/3151-php-entornos-funciones/49765-declaraciones-de-tipo-devolucion/)

