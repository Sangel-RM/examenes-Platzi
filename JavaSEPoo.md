# Curso de Java SE Orientado a Objetos
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Para qué sirve el paradigma orientado a objetos?
 		 Nos ayuda a analizar problemas para plasmar su solución en código.
###### Razón: La Programación Orientada a Objetos (POO) nos ayuda a analizar y entender todos estos problemas para resolverlos de la forma más sostenible en el futuro. Java surgió con este paradigma y es uno de los lenguajes que define en gran manera el rumbo que sigue la POO.
###### Vídeo: [Programación orientada a objetos en Java](https://platzi.com/clases/1629-java-oop/21576-programacion-orientada-a-objetos-en-java/ "Programación orientada a objetos en Java")
------------
#### ¿Cuál es la palabra clave que define una clase en Java?
		 class
###### Razón: La palabra reservada class, define una clase en Java.
###### Vídeo: [Creando nuestra primera Clase](https://platzi.com/clases/1629-java-oop/21580-creando-nuestra-primera-clase/ "Creando nuestra primera Clase")
------------
#### ¿Puedo usar atributos static para no tener que instanciar un objeto y así ahorrar memoria?
		 Verdadero
###### Razón: Las variables static no pertenecen al objeto si no a la clase, si se modifica la variable static esto se verá reflejado en todos los objetos que hayan sido creados con esa clase. Se puede accesar a ellos usando el nombre de la clase, al no crear un objeto ahorra memoria.
###### Vídeo: [Static: Variables y Métodos Estáticos](https://platzi.com/clases/1629-java-oop/21582-static-variables-y-metodos-estaticos/ "Static: Variables y Métodos Estáticos")
------------
#### ¿Cuál es la palabra clave para declarar constantes en Java?
		 final
###### Razón: final quiere decir que solamente podemos hacer una sola asignación, lo podemos definir sin asignar un valor, pero después en algún momento se tiene que inicializar y ese valor no podrá cambiar.
###### Vídeo: [Final: Variables Constantes](https://platzi.com/clases/1629-java-oop/21584-final-variables-constantes/ "Final: Variables Constantes") 
------------
#### ¿Cuál es la palabra reservada para referirme a la clase padre?
		 super
###### Razón: Super indica que una variable o método es de la clase padre, la superclase de cual heredan nuestras subclases, solo la usamos cuando aplicamos herencia.
###### Vídeo: [Super y This](https://platzi.com/clases/1629-java-oop/21575-super-y-this/ "Super y This")
------------
#### En Java es permitida la herencia múltiple
		 falso
###### Razón: La Herencia consiste en crear nuevas clases a partir de otras clases, establecemos una relación padre e hijo entre nuestras clases. Es diferente a las clases anidadas, ya que, en vez de crear clases dentro de clases, le indicamos a nuestras subclases de qué superclase pueden heredar (extends) para reutilizar el código de algunos de sus métodos. Nuestras clases no pueden heredar de más de una clase.
###### Vídeo: [¿Qué es la Herencia? Don't repeat Yourself](https://platzi.com/clases/1629-java-oop/21574-que-es-la-herencia-dont-repeat-yourself/ "¿Qué es la Herencia? Don't repeat Yourself")
------------
#### ¿El nivel de abstracción de una interfaz sobre un programa es?
		 Abstracción de los comportamientos
###### Razón: Interfaz: pensamos en acciones que pueden compartir muchos objetos. 
###### Vídeo: [Diferencias entre las Interfaces y las Clases Abstractas](https://platzi.com/clases/1629-java-oop/21601-diferencias-entre-las-interfaces-y-las-clases-abst/ "Diferencias entre las Interfaces y las Clases Abstractas")
------------
#### ¿Cuándo es el momento correcto para crear una clase abstracta?
		 Cuando no hay necesidad de crear instancias de la clase
###### Razón: Las clases abstractas son una combinación entre interfaces y herencia donde no implementaremos todos los métodos ni tampoco crearemos instancias
###### Vídeo: [Clases Abstractas](https://platzi.com/clases/1629-java-oop/21598-clases-abstractas/ "Clases Abstractas")
------------
#### ¿Por qué es una buena práctica usar modularidad?
 		 Porque así nos aseguramos de que cada clase tenga una sola responsabilidad
###### Razón: La Modularidad consiste en dividir nuestro programa en diferentes módulos de forma que puedan unirse o separarse sin romperse entre ellos o perder alguna funcionalidad.
###### Vídeo: [Modularidad](https://platzi.com/clases/1629-java-oop/21579-modularidad/ "Modularidad")
------------
#### ¿En qué tipo de memoria se almacenan los objetos en Java?
 		 Heap
###### Razón: La memoria Heap es un poco más lenta y nos permite guardar grandes cantidades de información. En esta memoria guardamos los valores de los objetos, las instancias de nuestras clases.
###### Vídeo: [Variable vs. Objeto: Un vistazo a la memoria](https://platzi.com/clases/1629-java-oop/21795-variable-vs-objeto-un-vistazo-a-la-memoria/ "Variable vs. Objeto: Un vistazo a la memoria")
------------
#### ¿Para qué sirven los métodos getters y setters?
		 Para Leer/Escribir en las variables miembro de la clase sin alterarlas directamente
###### Razón: Los Getters y Setters nos permiten leer y escribir (respectivamente) los valores de nuestras variables privadas desde fuera de la clase donde fueron creadas. Con los Getters obtenemos los datos de las variables y con los Setters asignamos o cambiamos su valor.
###### Vídeo: [Getters y Setters](https://platzi.com/clases/1629-java-oop/21587-getters-y-setters/ "Getters y Setters")  
------------
#### Un objeto es lo mismo que una clase
		 Falso
###### Razón: Los Objetos son todas las cosas físicas o conceptuales que tienen propiedades y comportamientos. Por ejemplo: usuario, sesión, auto, etc. Las Propiedades o atributos son las características de nuestros objetos. Estos atributos siempre serán sustantivos y pueden tener diferentes valores que harán referencia a nombres, tamaños, formas y estados.
###### Vídeo: [¿Qué es un Objeto?](https://platzi.com/clases/1629-java-oop/21577-que-es-un-objeto/ "¿Qué es un Objeto?")
------------
#### ¿Cuál es la mayor utilidad de los Enumerations?
		 Definir una colección de constantes
###### Razón: Es un tipo de dato que sirve para declarar una colección de constantes, al ser así estaremos obligados a escribirlos con mayúsculas.
###### Vídeo: [Enumerations](https://platzi.com/clases/1629-java-oop/21592-enumerations/ "Enumerations")
------------
#### ¿Qué tipo de conjunto de elementos pueden almacenar los Collections?
		 Tipo Objeto
###### Razón: Los Collections sirven para trabajar con colecciones de datos, específicamente y solamente con objetos. Los collections se diferencian de los arrays en que su tamaño no es fijo y por el contrario es dinámico.
###### Vídeo: [Collections](https://platzi.com/clases/1629-java-oop/21597-collections/ "Collections")  
------------
#### ¿Cuál es la palabra clave para aplicar herencia de una interfaz a otra?
		 extends
###### Razón: Las interfaces pueden heredar de otras interfaces utilizando la palabra clave extends, el concepto de herencia se aplicará como naturalmente se practica en clases, es decir, la interfaz heredará y adquirirá los métodos de la interfaz padre.
###### Vídeo: [Herencia en interfaces](https://platzi.com/clases/1629-java-oop/21603-herencia-en-interfaces/ "Herencia en interfaces")
