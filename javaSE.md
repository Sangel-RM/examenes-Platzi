# Curso de Introducción a Java SE
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Cuál es el resultado del siguiente programa? int i=1, j=2, k=3, m=2; System.out.println ((j >= i) || (k == m));
		 true
###### Razón: De acuerdo a la tabla de verdad del operador OR (||), el resultado de true y false es true.  Consulta la tabla de verdad [aquí](https://static.platzi.com/media/user_upload/OeradoresLogicos-7e5f4ca4-ade8-410b-968d-827376805921.jpg "aquí").
###### Vídeo: [Operadores Lógicos y Expresiones booleanas](https://platzi.com/clases/1631-java-basico/21191-operadores-logicos-y-expresiones-booleanas/ "Operadores Lógicos y Expresiones booleanas")
------------
#### Windows tiene su propia extensión de archivos ejecutables, los .exe, ¿cuál es el que usa Java?
		 .jar
###### Razón: Los archivos JAR (Java Archive) son archivos de Java con el código compilado de los archivos .class y comprimido con el formato ZIP para que más adelante sean interpretados y ejecutados por la máquina virtual de Java (JVM).
###### Vídeo: [Archivos .JAR](https://platzi.com/clases/1631-java-basico/21188-archivos-jar/ "Archivos .JAR")
------------
#### Si tienes un sistema que correrá en un microcontrolador con memoria limitada y debes guardar una variable de edad. ¿Qué tipo de dato usarías?
		 byte
###### Razón: El byte es la unidad de dato más pequeña, ya que solo ocupa 1 byte y tiene un rango -128 a 127. 
###### Vídeo: [Tipos de datos numéricos](https://platzi.com/clases/1631-java-basico/21182-tipos-de-datos-numericos/ "Tipos de datos numéricos")  
------------
#### Debes desarrollar un programa para una empresa en la que planean integrar nuevos módulos en el futuro, ya que se contempla que estarán en constante crecimiento. ¿Cuál es la mejor característica de Java que hace esto posible?
		 Java un Lenguaje Orientado a Objetos
###### Razón: Es un lenguaje de programación que nos ayuda a desarrollar aplicaciones para distintos dispositivos.
###### Vídeo: [¿Qué es Java?](https://platzi.com/clases/1631-java-basico/21170-que-es-java/ "¿Qué es Java?")
------------
#### ¿Cómo se llama el código que produce Java después de la compilación para que la máquina virtual genere el lenguaje máquina de cada Sistema Operativo?
		 Bytecode
###### Razón: El bytecode Java se encuentra dentro del archivo de extensión .class y es el tipo de instrucciones que la máquina virtual Java espera recibir, para posteriormente ser compiladas a lenguaje de máquina, mediante un compilador JIT a la hora de su ejecución.
###### Vídeo: [Versiones de Java y JDK](https://platzi.com/clases/1631-java-basico/21171-versiones-de-java-y-jdk/ "Versiones de Java y JDK")
------------
#### Este elemento le da a Java la portabilidad con otros Sistemas Operativos.
		 La Java Virtual Machine: la máquina virtual Java que traduce el bytecode para que se ejecute en la plataforma donde está implementada
###### Razón:  La máquina virtual consiste en interpretar el resultado de una compilación del código de Java, conocida como Bytecode, es este último lo que toma la Maquina virtual de Java y permite el funcionamiento del código en cualquier sistema operativo.
###### Vídeo: [Versiones de Java y JDK](https://platzi.com/clases/1631-java-basico/21171-versiones-de-java-y-jdk/ "Versiones de Java y JDK")
------------
#### Si se desarrolla un videojuego estilo Mario Bros donde tuviera que ir ganando monedas que valen 2 puntos, ¿cuál sería la mejor instrucción para llevar el conteo acumulado de monedas en código java?
		 x += 2;
###### Razón: El operador de asignación  +=, es lo mismo que x = x+2, permite simplificar la expresión.
###### Vídeo: [Operadores de Asignación, Incremento y Decremento](https://platzi.com/clases/1631-java-basico/21184-operadores-de-asignacion-incremento-y-decremento/ "Operadores de Asignación, Incremento y Decremento")
------------
#### Cada lenguaje de programación define su código fuente en archivos con extensiones especiales. Por ejemplo: Python y .py, JavaScript y .js o Go .go. ¿Cuál es la extensión para Java?
 		 .java
###### Razón: .java es la extensión de los archivos hechos en Java.
###### Vídeo: [Archivos .JAR](https://platzi.com/clases/1631-java-basico/21188-archivos-jar/ "Archivos .JAR")
------------
#### ¿Cuál es el resultado del siguiente código? byte i = 1; byte j = 1; byte k = i+j;
		 Error cannot convert from int to byte.
###### Razón: El casteo entre byte a int no se puede realizar.
###### Vídeo: [Casteo entre tipos de datos](https://platzi.com/clases/1631-java-basico/21187-casteo-entre-tipos-de-datos/ "Casteo entre tipos de datos")  
------------
#### ¿Cuál es el resultado de la siguiente expresión? int i = 7; char c = ‘w’; System.out.println((i >= 6) && (c == ‘w’));
		 
###### Razón: Ambas expresiones son verdaderas, 7 es mayor que 7 y la variable c equivale a w.
###### Vídeo: [Operadores Lógicos y Expresiones booleanas](https://platzi.com/clases/1631-java-basico/21191-operadores-logicos-y-expresiones-booleanas/ "Operadores Lógicos y Expresiones booleanas")
------------
#### ¿Cuál es la sentencia para declarar e indicar el tamaño de un arreglo?
		 Foo f[] = new Foo[20];
###### Razón: Podemos definir los arrays de 2 formas: 
###### - TipoDato[] nombreVariable;
###### - TipoDato nombreVariable[];
###### Vídeo: [Arrays](https://platzi.com/clases/1631-java-basico/21197-arrays/ "Arrays")
------------
#### ¿En qué formato se generan los java docs?
		 HTML
###### Razón: Los Java Docs son una herramienta usada por muchas otras herramientas y aplicaciones porque nos ayuda a documentar todo nuestro código usando comentarios. Además, nos permite visualizar la documentación en formato HTML.
###### Vídeo: [Java Docs](https://platzi.com/clases/1631-java-basico/21195-java-docs/ "Java Docs")
------------
#### La convención de nombres para las clases es Lower Camel Case
		 Falso
###### Razón: Camel Case es una convención muy popular para nombrar nuestras variables. Podemos usarlo en modo Upper Camel Case o Lower Camel Case, la diferencia es si comenzamos el nombre de la variable con mayúscula o minúscula. Debemos usar Upper Camel Case en los nombres de las clases y archivos. Y Lower Camel Case en los nombres de las variables o métodos.
###### Vídeo: [Técnica de Naming: Camel Case](https://platzi.com/clases/1631-java-basico/21181-tecnica-de-naming-camel-case/ "Técnica de Naming: Camel Case")
------------
#### Hablando del alcance de Variables, si una variable es declarada dentro de un método, ¿esta puede ser accedida desde otro método?
		 No, su alcance es limitado al método
###### Razón: Variables locales: Se encuentran declaradas en el cuerpo de alguna función o método y sólo se utilizan dentro de la misma.
###### Vídeo: [Alcance de las variables y Sentencia ELSE](https://platzi.com/clases/1631-java-basico/21202-alcance-de-las-variables-y-sentencia-else/ "Alcance de las variables y Sentencia ELSE")
------------
#### Si declaramos un arreglo de la siguiente manera: String arreglo[] = new String[10]; ¿Cuál es la forma correcta de asignar el valor ‘hola’ en la primera posición del arreglo?
		 arreglo[0] = "hola";
###### Razón: Agregamos un elemento al arreglo, nombreArreglo[INDICE]  = valor
###### Vídeo: [Declarando Arreglos](https://platzi.com/clases/1631-java-basico/21198-declarando-arreglos/ "Declarando Arreglos")
------------
#### ¿Cuándo entrará el programa en el siguiente bucle?
` while ((x<y) && (a>b)) {  ... } `

		 Si X es menor que Y y si A es mayor que B
###### Razón: La condición del buce while indica que si X es menor que Y y si  es mayor que B, se entrará al bucle.
###### Vídeo: [Operadores Lógicos y Expresiones booleanas](https://platzi.com/clases/1631-java-basico/21191-operadores-logicos-y-expresiones-booleanas/ "Operadores Lógicos y Expresiones booleanas")
------------
#### La sentencia if es un condicional que le da al programa dos opciones o caminos a recorrer
		 Verdadero
###### Razón:  Es la manera en la que una máquina toma decisiones a la hora de ejecutar el código. Funciona de modo “TRUE” o “FALSE".
###### Vídeo: [Sentencia if](https://platzi.com/clases/1631-java-basico/21189-sentencia-if/ "Sentencia if")
------------
#### ¿Cuál es la diferencia entre usar una sentencia if y switch?
		 
###### Razón: La sentencia Switch nos ayuda a tomar decisiones con base en una o más condiciones, en cambio IF, retorna TRUE O FALSE.
###### Vídeo: [Sentencia Switch](https://platzi.com/clases/1631-java-basico/21192-sentencia-switch/ "Sentencia Switch")
------------
#### Según la convención de nombres de Java para constantes, ¿cuál de las siguientes opciones debes usar?
		 Mayúsculas separadas por guión bajo
###### Razón: Las variables constantes son variables cuyo valor nunca va a cambiar, por lo que se deben escribir completamente en mayúsculas y usando el caracter _.
###### Vídeo: [Convención de Nombres en Java](https://platzi.com/clases/1631-java-basico/21180-convencion-de-nombres-en-java/ "Convención de Nombres en Java")
------------
#### ¿Cuál de las siguientes es la palabra reservada para indicar que debo devolver un valor en una función?
		 return
###### Razón: Indica el dato que está devolviendo una función.
###### Vídeo: [Break, Continue y Return](https://platzi.com/clases/1631-java-basico/21167-break-continue-y-return/ "Break, Continue y Return")
------------
#### La sentencia break rompe un ciclo y sale de él.
		 Verdadero
###### Razón: Breaj rompe, detiene el bucle y sale de el.
###### Vídeo: [Break, Continue y Return](https://platzi.com/clases/1631-java-basico/21167-break-continue-y-return/ "Break, Continue y Return")
------------
#### La sentencia continue no rompe el ciclo, solo omite el resto del código.
		 
###### Razón: Continue en cierto modo también nos va a servir para detener un ciclo pero en lugar de terminarlo como en el caso de break, este volverá directo a la condición.
###### Vídeo: [Break, Continue y Return](https://platzi.com/clases/1631-java-basico/21167-break-continue-y-return/ "Break, Continue y Return")
------------
#### ¿Por qué usamos Java Docs?
		 Nos ayuda a documentar nuestro código para comprender su utilidad con descripción y/o argumentos de entrada y salida.
###### Razón: Los Java Docs son una herramienta usada por muchas otras herramientas y aplicaciones porque nos ayuda a documentar todo nuestro código usando comentarios. Además, nos permite visualizar la documentación en formato HTML.
###### Vídeo: [Java Docs](https://platzi.com/clases/1631-java-basico/21195-java-docs/ "Java Docs")
------------
#### ¿Para qué sirve Java SE?
		 Para construir aplicaciones de escritorio o consola (terminal).
###### Razón: Java Standar Edition sirve para construir aplicaciones de escritorio o consola.
###### Vídeo: [¿Qué es Java?](https://platzi.com/clases/1631-java-basico/21170-que-es-java/ "¿Qué es Java?")
------------
#### ¿Para qué sirve Java EE?
		 Para que las empresas trabajen aplicaciones web de última generación.
###### Razón: Java Enterprise Edition sirve para que las empresas trabajen aplicaciones web de última generación.
###### Vídeo: [¿Qué es Java?](https://platzi.com/clases/1631-java-basico/21170-que-es-java/ "¿Qué es Java?")
------------
#### ¿Qué es WORA?
		 Write Once, Run Anywhere.
###### Razón: Java usa la filosofia WORA (Write once Run Anywhere)  lo que se haga en Java SE, se puede llevar a Java EE.
###### Vídeo: [¿Qué es Java?](https://platzi.com/clases/1631-java-basico/21170-que-es-java/ "¿Qué es Java?")
------------
#### ¿Qué es JDK?
		 Java Development Kit: El kit de desarrollo de Java.
###### Razón: El JDK o Java Development Kit se compone de los siguientes elementos:
##### - Java Runtime Environment (JRE): La máquina virtual de Java, lo que nos permite que al escribir el mismo código funcione igual en todos los dispositivos y sistemas operativos.
##### - Compilador de Java: El encargado de traducir nuestro código en Java a un lenguaje que puede entender e interpretar nuestra máquina virtual.
##### - APIs de desarrollo: Una base de código lista para ayudarnos a desarrollar.
###### Vídeo: [Versiones de Java y JDK](https://platzi.com/clases/1631-java-basico/21171-versiones-de-java-y-jdk/ "Versiones de Java y JDK")
------------
#### ¿Qué significa LTS?
		 Long Term Support.
###### Razón: El soporte a largo plazo es un término usado para nombrar versiones o ediciones especiales de software diseñadas para tener soportes durante un período más largo que el normal.
###### Vídeo: [Versiones de Java y JDK](https://platzi.com/clases/1631-java-basico/21171-versiones-de-java-y-jdk/ "Versiones de Java y JDK")
------------
#### ¿Qué convención de nombres sigue la siguiente variable? java int soyUnaVariable = 10;
		 Lower Camel Case
###### Razón: La diferencia entre Upper Camel Case o Lower Camel Case, es si comenzamos el nombre de la variable con mayúscula o minúscula. Debemos usar Upper Camel Case en los nombres de las clases y archivos. Y Lower Camel Case en los nombres de las variables o métodos.
###### Vídeo: [Técnica de Naming: Camel Case](https://platzi.com/clases/1631-java-basico/21181-tecnica-de-naming-camel-case/ "Técnica de Naming: Camel Case")
------------
#### ¿Qué convención de nombres sigue la siguiente clase? java public class HelloWorld { // ... }
		 Upper Camel Case
###### Razón: La diferencia entre Upper Camel Case o Lower Camel Case, es si comenzamos el nombre de la variable con mayúscula o minúscula. Debemos usar Upper Camel Case en los nombres de las clases y archivos. Y Lower Camel Case en los nombres de las variables o métodos.
###### Vídeo: [Técnica de Naming: Camel Case](https://platzi.com/clases/1631-java-basico/21181-tecnica-de-naming-camel-case/ "Técnica de Naming: Camel Case")
