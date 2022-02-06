# Curso de Kotlin desde Cero
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### Kotlin es un lenguaje fuertemente tipado.
		 Verdadero
###### Razón: Un lenguaje de programación es fuertemente tipado si no se permiten violaciones de los tipos de datos, es decir, dado el valor de una variable de un tipo concreto, no se puede usar como si fuera de otro tipo distinto a menos que se haga una conversión.
###### Vídeo: [Qué es Kotlin](https://platzi.com/clases/2245-kotlin/36585-que-es-kotlin/ "Qué es Kotlin")
------------
#### Kotlin solo sirve para crear aplicaciones Android.
 		 Falso
###### Razón: Kotlin tambien sirva para: 
###### - Backend development con diferentes frameworks (Spring, Micronaut, Ktor)
###### - De forma nativa y correrlo o instalarlo como una aplicación de escritorio ###### - Usarlo en Scripts para ayudarte a no repetir un código manualmente y ejecutarlo en cualquier entorno
###### - Además existe la posibilidad de ser multiplataforma, es decir, puede compartirse entre apps Android e iOS
###### Vídeo: [Qué es Kotlin](https://platzi.com/clases/2245-kotlin/36585-que-es-kotlin/ "Qué es Kotlin")
------------
#### La función main es...
		 El punto de entrada de tu programa.
###### Razón: La función main  sirve como punto de entrada para el desarrollo de nuestra app. Dentro de las llaves se encuentra el código que se ejecuta en la aplicación.
###### Vídeo: [Hola mundo con Kotlin](https://platzi.com/clases/2245-kotlin/36589-hola-mundo-con-kotlin/ "Hola mundo con Kotlin")
------------
#### El tipo de variable val es de lectura y escritura.
		 Falso
###### Razón: val es una variable de solo lectura, dichas variable una vez asignado el valor no puede ser cambiado posteriormente.
###### Vídeo: [Variables en Kotlin](https://platzi.com/clases/2245-kotlin/36590-variables-en-kotlin/ "Variables en Kotlin")
------------
#### ¿Cuántos valores puede tener la siguiente variable? val a : Boolean
		 Tres
###### Razón: Boolean puede tener 3 valores: true, false y null.
###### Vídeo: [Null-Safety en Kotlin](https://platzi.com/clases/2245-kotlin/36599-null-safety-en-kotlin/ "Null-Safety en Kotlin")
------------
#### Las variables de tipo var son de lectura y escritura.
		 Verdadero
###### Razón: var es una variable de lectura y escritura,  el valor de esta variable puede modificarse.
###### Vídeo: [Variables en Kotlin](https://platzi.com/clases/2245-kotlin/36590-variables-en-kotlin/ "Variables en Kotlin")
------------
#### En Kotlin un tipo de dato entero se define como:
		 Int
###### Razón: Para definir valores enteros usamos Int, que sirva para almacenar números enteros de hasta 32 bits.
###### Vídeo: [Kotlin y sus tipos de variables](https://platzi.com/clases/2245-kotlin/36591-kotlin-y-sus-tipos-de-variables/ "Kotlin y sus tipos de variables")
------------
#### Al escribir código en Kotlin debes evitar la mutabilidad y utilizar más la inmutabilidad.
		 Verdadero
###### Razón: La inmutabilidad es un concepto muy potente que nos puede ayudar a simplificar la complejidad de comprensión de nuestro código y, por tanto, a disminuir las probabilidades de que se produzcan errores inesperados.
###### Vídeo: [Variables en Kotlin](https://platzi.com/clases/2245-kotlin/36590-variables-en-kotlin/ "Variables en Kotlin")
------------
#### En Kotlin es posible asignar un valor utilizando un if
		 Verdadero
###### Razón: Kotlin permite asignar estructuras de control a las variables para simplificar el código.
###### Vídeo: [Estructuras de control: if](https://platzi.com/clases/2245-kotlin/36595-estructuras-de-control-if/ "Estructuras de control: if")
------------
#### ¿Cuántas ramas puede tener un when?
		 Dependiendo del tipo de dato que se utilice puede tener desde 2 ramas hasta n cantidad.
###### Razón: No hay límite de ramas con la estructura WHEN.
###### Vídeo: [Estructuras de Control: when](https://platzi.com/clases/2245-kotlin/36596-estructuras-de-control-when/ "Estructuras de Control: when")
------------
#### Con el when siempre tengo que incluir una rama else.
		 Sí, es una buena práctica tener un when exhaustivo.
###### Razón: Al usar WHEN es obligatorio usar un else al finar de nuestras ramas.
###### Vídeo: [Estructuras de Control: when](https://platzi.com/clases/2245-kotlin/36596-estructuras-de-control-when/ "Estructuras de Control: when")
------------
#### Cuando quiero iterar sobre una lista para modificar elementos y devolver elementos modificados debe utilizarse la función:
		 map 
###### Razón: Los mapas asocian claves con valores. Las claves deben ser únicas, pero los valores asociados no. De este modo, cada valor puede ser usado para identificar de manera única el valor asociado, ya que el mapa asegura que no puedes duplicar claves en la colección.
###### Vídeo: [Maps](https://platzi.com/clases/2245-kotlin/36605-maps/ "Maps")
------------
#### ¿Por qué debo utilizar la función map en lugar de un for normal?
		 Porque al utilizar la función map evito estar creando una lista mutable y estar agregando elementos a dicha lista.
###### Razón: La función de orden superior map{ } te permite aplicar una función sobre todos los elementos de una colección con el fin de una nueva colección con el cálculo final.
###### Vídeo: [Maps](https://platzi.com/clases/2245-kotlin/36605-maps/ "Maps")
----------- 
#### Si quiero filtrar los elementos de una lista por una condición, debo utilizar la función:
		 filter
###### Razón: La función de extensión filter te permite filtrar los ítems de una colección de elementos a partir de un predicado como argumento. El predicado afirma o niega expresiones sobre el sujeto (cada elemento de la colección). Si un elemento satisface al predicado, entonces es incluido en el resultado final.
###### Vídeo: [Como ordenar listas con las funciones que tiene Kotlin](https://platzi.com/clases/2245-kotlin/36604-como-ordenar-listas-con-las-funciones-que-tiene-ko/ "Como ordenar listas con las funciones que tiene Kotlin")
------------
#### Los nullables son:
		 Como toda herramienta, pueden ser buenas o malas dependiendo de su uso.
###### Razón: En Kotlin los objetos por defecto no aceptan valores nulos, para que le podamos asignar un null tendremos que indicar que ese objeto realmente puede ser null. De esta forma vamos a poder garantizar que no se no producirá un NullPointerException en tiempo de ejecución sin necesidad de llenar todo el código de comprobaciones i
###### Vídeo: [Valores nulos, Double bang y cómo solucionarlos.](https://platzi.com/clases/2245-kotlin/36600-valores-nulos-double-bang-y-como-solucionarlos/ "Valores nulos, Double bang y cómo solucionarlos.")
------------
#### El operador double bang !! es...
		 Considerado una mala práctica y debemos evitar utilizarlo lo más posible.
###### Razón: Este operador se indica con dos símbolos de exclamación !! Con esto le dices al compilador que sabes que en este punto la variable no puede ser nula.
###### Vídeo: [Valores nulos, Double bang y cómo solucionarlos.](https://platzi.com/clases/2245-kotlin/36600-valores-nulos-double-bang-y-como-solucionarlos/ "Valores nulos, Double bang y cómo solucionarlos.")
------------
#### Este operador ?: es llamado el operador:
		 Elvis
###### Razón: El Elvis operator ?: Es una versión segura de una expresión if. Devuelve el valor a su izquierda si no es nulo. De lo contrario, devuelve el valor a su derecha.
###### Vídeo: [Elvis operator](https://platzi.com/clases/2245-kotlin/36602-elvis-operator/ "Elvis operator")
------------
#### En Kotlin el operador ternario no existe porque:
		 Con un If podemos replicar el comportamiento.
###### Razón: El operador Elvis ?: , puede servir de remplazo para el operador ternerario que se suele usar en Java.
###### Vídeo: [Elvis operator](https://platzi.com/clases/2245-kotlin/36602-elvis-operator/ "Elvis operator")
------------
#### Dada la siguiente lista: val lista = listOf(1,2,3,4) si quisiera eliminar el primer elemento de la lista ¿que tendría que hacer?
		 No podría porque la lista es inmutable.
###### Razón: Las listas inmutables son de solo lectura, si se desea modificar una lista debe hacerse uso de mutableListOf()
###### Vídeo: [Listas](https://platzi.com/clases/2245-kotlin/36603-listas/ "Listas")
------------
#### Si tengo un MutableMap con un elemento que tiene como clave "RazaDePerro" y el valor es "Corgi". Al intentar asignar un nuevo elemento con la clave "RazaDePerro" y el valor "Pitbull" ¿Cuál sería el resultado?
		 El primer valor será sobreescrito por el segundo valor.
		 ###### Razón: Los maps son elementos de clave,valor, y solo puede haber una clave.
###### Vídeo: [Maps](https://platzi.com/clases/2245-kotlin/36605-maps/ "Maps")
------------
#### Si tenemos: val set = setOf("a","b","c") y ejecutamos la función set.remove(0) ¿Qué ocurrirá?
		 No ocurre nada porque no se pueden eliminar elementos de un set.
###### Razón: Si se quiere elimnar elementos del set debe usarse un mutableSetOf()
###### Vídeo: [Sets](https://platzi.com/clases/2245-kotlin/36606-sets/ "Sets")
------------
#### Las funciones en Kotlin siempre devuelven un tipo.
		 Sí, siempre devuelven un valor aunque sea implícito.
###### Razón: Aunque no le asignemos un valor de retorno a alguna función, implicítamente retorna Unit sin necesidad de especificarse.
###### Vídeo: [¿Qué son las funciones?](https://platzi.com/clases/2245-kotlin/36607-que-son-las-funciones/ "¿Qué son las funciones?")
------------
#### La palabra reservada para crear una función en Kotlin es:
		 fun
###### Razón: fun es usado para crear funciones. fun miFuncion()
###### Vídeo: [¿Qué son las funciones?](https://platzi.com/clases/2245-kotlin/36607-que-son-las-funciones/ "¿Qué son las funciones?")
------------
#### ¿Cuál es el resultado de la siguiente función? fun miFuncion(val nombre: String, val apellido: String) = nombre + apellido
		 Si utilizamos los parámetros Andrea Gómez el resultado sería: AndreaGómez
###### Razón: Al concatenar las variables se imprimen juntas ya que no se coloco ninguna cadena para separarlas.
###### Vídeo: [Funciones y funciones de extensión](https://platzi.com/clases/2245-kotlin/36608-funciones-y-funciones-de-extension/ "Funciones y funciones de extensión")
------------
#### Las high order functions son llamadas así porque:
		 Son funciones que reciben como parámetro otras funciones.
###### Razón: Las funciones de orden superior son funciones que pueden recibir como parámetros otras funciones y/o devolverlas como resultados.
###### Vídeo:  [High Order functions](https://platzi.com/clases/2245-kotlin/36611-high-order-functions/ "High Order functions")
------------
#### Las funciones de extensión nos permiten:
		 Extender del lenguaje y añadir funcionalidades a objetos, creando un código entendible y conciso.
###### Razón:  Las funcionas de extensión ayudan a extender la funcionalidad de clases sin necesidad de tocar su código.
###### Vídeo: [Funciones y funciones de extensión](https://platzi.com/clases/2245-kotlin/36608-funciones-y-funciones-de-extension/ "Funciones y funciones de extensión")
------------
#### El siguiente código miVariableNullable?.let{ it -> it.length } nos ayuda a:
		 Ejecutar el código dentro de las llaves solamente cuando miVariableNullable no sea nulo.
###### Razón: ?.let nos permite correr el código para un valor que no es nulo
###### Vídeo: [Let](https://platzi.com/clases/2245-kotlin/36612-let/ "Let")
------------
#### Las lambdas se pueden crear y pasar como parámetros a otras funciones, pero no se pueden almacenar en variables.
 		 Falso, las lambdas se pueden crear y almacenar en variables así como también se pueden pasar como parámetros a otras funciones.
###### Razón: Las lambdas son funciones que no se declaran sino que se pasan inmediatamente como una expresión.
###### Vídeo: [Lambdas](https://platzi.com/clases/2245-kotlin/36610-lambdas/ "Lambdas")
------------
#### La función apply nos permite:
		 Realizar modificaciones a una variable y devolver la misma variable con las propiedades modificadas.
###### Razón: Apply es similar a with, solo que apply es una función de extensión y retorna el objeto recibidor como resultado. Suele usarse cuando se desea modificar propiedades de una variable.
###### Vídeo: [Apply](https://platzi.com/clases/2245-kotlin/36615-apply/ "Apply")
------------
#### Cuando quiero iterar sobre una lista sin necesariamente modificar sus elementos puedo usar la función:
		 forEach
###### Razón: Los ForEach se utilizan para realizar una acción en cada uno de los elementos de la lista. Es como un enfoque de la función hacia la forma tradicional de bucle for. Tanto los bucles For como los ForEach son iguales cuando se genera la salida de un array o una lista.
###### Vídeo: [Ciclos](https://platzi.com/clases/2245-kotlin/36598-ciclos/ "Ciclos")