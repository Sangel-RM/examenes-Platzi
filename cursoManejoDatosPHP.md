# Curso de Manejo de Datos en PHP
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es PHP Avanzado?
		 Es conocer en detalle lo que el lenguaje nos ofrece.
###### Razón: PHP avanzado es dominar las funciones que el mismo lenguaje provee para extraer y manipular datos.
###### Vídeo: [Qué aprenderás sobre el manejo de datos en PHP](https://platzi.com/clases/2032-datos-php/32089-introduccion/)
------------
#### ¿Qué signos puedo escapar entre comillas simples?
		 La comilla simple y el backslash
###### Razón: Las comillas simples ('') sirva para manejar datos como strings. Si queremos utilizar una comilla simple dentro de nuestro string utilizamos \ (backslash) para escaparla. [Entrecomillado Simple](https://www.php.net/manual/es/language.types.string.php#language.types.string.syntax.single)
###### Vídeo: [Comillas](https://platzi.com/clases/2032-datos-php/32499-comillas/)
------------
#### ¿Cómo imprimo un elemento complejo?
		 echo "Quiero aprender {$courses['backend'][0]}";
###### Razón: Para acceder a datos complejos como un objeto o un array con varios niveles necesitamos utilizar {} (llaves) que encierren a la variable con los parámetros que indicamos. Se puede dar el caso de cuando es un objeto, y este solo tiene un nivel en su parámetro accedemos sin utilizar {} (llaves) y para indicar el key ponemos →. [Entrecomillado doble](https://www.php.net/manual/es/language.types.string.php#language.types.string.syntax.double)
###### Vídeo: [Comillas](https://platzi.com/clases/2032-datos-php/32499-comillas/)
------------
#### ¿Podemos en PHP extraer textos de una oración?
		 Sí, usando generalmente substr()
###### Razón: La función substr(), devuelve parte de un string de texo en la funcion y ella retorna una cadena de texto que empieza en el carater del segundo parámetro hasta el caracter del tercer parámetro. [substr](https://www.php.net/manual/es/function.substr)
###### Vídeo: [Extracción de datos](https://platzi.com/clases/2032-datos-php/32091-extraccion-de-datos/)
------------
#### ¿Qué formatos podemos dar a los textos con PHP?
		 Alterar, reemplazar y modificar.
###### Razón: Para alterar string en PHP se pueden usar funciones como strtolower(),strtoupper(),ucfirst,lcfirst, etc. Para reemplazar str_replace(), y para modificar, str_pad(). [Funciones de strings](https://www.php.net/manual/es/ref.strings.php)
###### Vídeo: [Formato de datos](https://platzi.com/clases/2032-datos-php/32092-formato-de-datos/)
------------
#### ¿Qué son las expresiones regulares?
		 Son patrones de comparación y se evalúan de izquierda a derecha.
###### Razón: Las expresiones regulares tambien conocidas como regex, son una cadena de caracteres que es utilizada para describir o encontrar patrones dentro de otros strings, en base al uso de delimitadores y ciertas reglas de sintaxis. [Sintaxis de las expresiones regulares](https://support.google.com/a/answer/1371415?hl=es)
###### Vídeo: [Expresiones Regulares](https://platzi.com/clases/2032-datos-php/32093-expresiones-regulares/)
------------
#### ¿Qué tecnologías debemos usar en un proyecto?
		 Lenguaje de programación PHP, Composer y PHPUnit..
###### Razón: PHPUnit es un entorno para realizar pruebas unitarias en el lenguaje de programación PHP
###### Vídeo: [Iniciando nuestro proyecto](https://platzi.com/clases/2032-datos-php/32094-iniciando-nuestro-proyecto/)
------------
#### ¿Qué argumentos podemos configurar en una función?
		 Valores, referencia y predeterminados.
###### Razón: Los argumentos de una función pueden ser parámetros o valores. Los valores se colocan directamente esperando a que se cumpla. Por referencia apunta al comportamiento de otro elemento. Predeterminado, es un valor por defecto el cúal se usará si no se coloca nada en el parámetro.
###### Vídeo: [Argumentos](https://platzi.com/clases/2032-datos-php/32095-argumentos/)
------------
#### ¿Podemos devolver varios resultados con return?
		 Sí, usando un array
###### Razón: La sentencia return finaliza la ejecución de la función y especifica un valor para ser devuelto a quien llama a la función. Para retornan más de un valor se puede realizar a través de un array return ['hola',1];
###### Vídeo: [Return](https://platzi.com/clases/2032-datos-php/32096-return/)
------------
#### ¿Qué es una función anónima?
		 Es lo que usamos cuando una variable tiene necesidad de lógica.
###### Razón: Las funciones anónimas son funciones sin nombre. Una función anónima se usa en una variable que requiere lógica.
###### Vídeo: [Closure](https://platzi.com/clases/2032-datos-php/32097-closure/)
------------
#### ¿Qué es un array simple?
		 Es un array con keys personalizados.
###### Razón: Los arrays estan compuestos por una key-value, un arrays simple solo esta compuesto por valores. $days = ['Lunes','Martes','Miercoles'];
###### Vídeo: [Array simple](https://platzi.com/clases/2032-datos-php/32098-array-simple/)
------------
#### ¿Qué es un array complejo?
		 Es un array con keys personalizados.
###### Razón: Tambien llamados arrays asociativos, son arrays cuyos keys son strings personalizados. $edades = ["Alberto"=>10,"Ana"=>5];
###### Vídeo: [Array Complejo](https://platzi.com/clases/2032-datos-php/32099-array-complejo/)
------------
#### ¿Qué logro con array_chunk?
		 Dividir un array
###### Razón: Divide un array en fragmentos [array_chunk](https://www.php.net/manual/es/function.array-chunk.php)
###### Vídeo: [Funciones PHP para arrays](https://platzi.com/clases/2032-datos-php/32100-funciones-php-para-arrays/)
------------
#### ¿Qué logro con array_diff?
		 Logramos comparar arrays
###### Razón: Calcula la diferencia entre arrays, Compara array1 con uno o más arrays y devuelve los valores de array1 que no estén presentes en ninguno de los otros arrays. [array_diff](https://www.php.net/manual/es/function.array-diff)
###### Vídeo: [Comparación](https://platzi.com/clases/2032-datos-php/32101-comparacion/)
------------
#### ¿Cómo unimos dos array?
		 Usando una función la función array_merge.
###### Razón: Combina los elementos de uno o más arrays juntándolos de modo que los valores de uno se anexan al final del anterior. Retorna el array resultante. [array_merge](https://www.php.net/manual/es/function.array-merge.php)
###### Vídeo: [Unión](https://platzi.com/clases/2032-datos-php/32421-union/)