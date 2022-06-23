# Curso de Buenas Prácticas en PHP
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿A quién beneficia contar con código bien escrito?
		 A todos los involucrados en el proyecto
###### Razón: El código bien escrito beneficia a todos los involucrados en el proyecto, debido a que el código será legible, coherente, mantenible, y testeable.
###### Vídeo: [¿A quién beneficia contar con código bien escrito?](https://platzi.com/clases/1630-mejor-codigo/21488-a-quien-beneficia-contar-con-codigo-bien-escrito/)
------------
#### ¿En qué nos basamos para decir que un código es de alta calidad?
		 Legibilidad, mantenibilidad y testeabilidad
###### Razón: La legibilidad permite interpretar lo que él código dice. Mantenibilidad: será fácil de añadir nuevas características. Testeabilidad: Será fácil realizar pruebas en el código.
###### Vídeo: [Ejes que hacen a la calidad del código](https://platzi.com/clases/1630-mejor-codigo/21489-ejes-que-hacen-a-la-calidad-del-codigo/)
------------
#### ¿Qué hace a la prolijidad del código?
		 Respeto de estándares
###### Razón: Prolijo significa llevar acabo algo con mucho cuidado, el código prolijo es aquel que cuenta con estándares para facilitar la legibilidad de este.
###### Vídeo: [Código Prolijo](https://platzi.com/clases/1630-mejor-codigo/21490-codigo-prolijo/)
------------
#### ¿Cuáles de estos identificadores son mnemotécnicos, específicos y precisos?
		 enviarClavesSecretas()
###### Razón: La mnemotecnia es una oración corta y fácil de recordar que ayuda de manera artificiosa a relacionar palabras. En el código esto se aplica con variables, funciones, clases, módulos y componentes dandoles nombres que describan con lo que se realiza.
###### Vídeo: [Identificadores mnemotécnicos, específicos y precisos](https://platzi.com/clases/1630-mejor-codigo/21491-identificadores-mnemotecnicos-especificos-y-precis/)
------------
#### ¿Cuál es la principal característica del código correctamente modularizado?
		 Muchos bloques pequeños
###### Razón: El código modular son pedazos de códigos divididos que pueden ser utilizados en cualquier lugar para evitar tener un solo archivo con un bloque de código gigante.
###### Vídeo: [Código modular](https://platzi.com/clases/1630-mejor-codigo/21492-codigo-modular/)
------------
#### ¿Cómo se logra código reutilizable?
		 Mediante el uso de funciones o procedimientos que reciben parámetros
###### Razón: Escribir código reutilizable ayuda a que en lugar de copiar y pegar una misma línea de código pero con diferentes parámetros se haga a través de una función que retorne los valores que necesitamos y luego se podrá llamar en cualquier lugar del código que se necesite pasándole los parámetros deseados.
###### Vídeo: [Código reutilizable](https://platzi.com/clases/1630-mejor-codigo/21510-codigo-reutilizable/)
------------
#### ¿Cómo se determina si un código está correctamente organizado?
		 Sus archivos contienen elementos relacionados de forma lógica (Y sus directorios contienen archivos también relacionados de forma lógica)
###### Razón: El código organizado se refiere a cómo esta distribuido los archivos en la raíz del proyecto. A mayor organización, mayor entendimiento del código.
###### Vídeo: [Código organizado](https://platzi.com/clases/1630-mejor-codigo/21511-codigo-organizado/)
------------
#### ¿Cuál de estos no es un problema del hardcoding?
		 Mediante el uso de constantes y archivos de configuración
###### Razón: El hardcoding es escribir código que deberia ser automatizado usando variables o constantes, es decir colocando los valores directos en lugar de colocarlos en variables para un fácil mantenimiento.
###### Vídeo: [Evitar el hardocing](https://platzi.com/clases/1630-mejor-codigo/21512-evitar-el-hardcoding/)
------------
#### ¿Cuál es el principal problema derivado de la existencia de efectos colaterales?
		 Resultados poco predecibles.
###### Razón: Modificar variables que no pertenecen al alcance(scope) del bloque de codigo (if, funciones, etc) correspondiente. Cada variable debe estar dentro de su alcance, sin verse afectada por fuera de dicho alcance. Y una mala práctica es usar variables globales que si son modificadas en consecuencia se tendría un resultado distinto a lo esperado.
###### Vídeo: [Evitar efectos colaterales](https://platzi.com/clases/1630-mejor-codigo/21513-evitar-efectos-colaterales/)
------------
#### ¿Qué son los principios SOLID?
		 Buenas prácticas del diseño Orientado a Objetos
###### Razón: SOLID son cinco principios básicos de la programación orientada a objetos que ayudan a crear software mantenible en el tiempo.SOLID significa: S: Single Reponsibility Principle | O: Open/Closed Principle | L: Liskov Substitution Principle |I: Interface Segregation Principle |D: Dependency Inversion Principle
###### Vídeo: [Principios SOLID: Single Responsibility Principle](https://platzi.com/clases/1630-mejor-codigo/21514-principios-solid-single-responsibility-principle/)
------------
#### ¿Qué beneficios aporta usar los principios SOLID?
		 Código más reutilizable y testeable
###### Razón: Usar los principios de SOLID, ayudara a escribir software de calidad en cualquier lenguaje de programación orientada a objetos. Gracias a ellos, el código que será más fácil de leer, testear y mantener.
###### Vídeo: [Principios SOLID: Single Responsibility Principle](https://platzi.com/clases/1630-mejor-codigo/21514-principios-solid-single-responsibility-principle/)
------------
#### ¿Qué nos enseña el Single Responsibility Principle?
		 A crear objetos que sepan muy bien como hacer una cosa específica
###### Razón: Las clases deben tener una única responsabilidad. También, se le puede conocer como la alta cohesión.
###### Vídeo: [Principios SOLID: Single Responsibility Principle](https://platzi.com/clases/1630-mejor-codigo/21514-principios-solid-single-responsibility-principle/)
------------
#### ¿Qué nos enseña el Open Closed Principle?
		 Que una clase debe poder adaptarse a nuevos escenarios sin necesidad de agregar o modificar su código
###### Razón: Este principio establece que los componentes del software deben estar abiertos para extender a partir de ellos, pero cerrados para evitar que se modifiquen. 
###### Vídeo: [Open/Closed Principle](https://platzi.com/clases/1630-mejor-codigo/21515-openclosed-principle/)
------------
#### ¿Qué nos enseña el Liskov Substitution Principle?
		 Cómo debe comportarse una clase que hereda de otra
###### Razón: Este principio establece que una subclase puede ser sustituida por su superclase. Es decir, que si se crea una subclase llamada Auto, la cual deriva de la superclase Vehículo.  Si al usar la superclase el programa falla, este principio no se cumple. 
###### Vídeo: [Liskov Substitution Principle](https://platzi.com/clases/1630-mejor-codigo/22210-liskov-substitution-principle/)
------------
#### ¿Qué nos enseña el Interface Segregation Principle?
		 A crear interfaces específicas
###### Razón: Este principio establece que los clientes no deben ser forzados a depender de interfaces que no utilizan. Es importante que cada clase implemente las interfaces que va a utilizar. De este modo, agregar nuevas funcionalidades o modificar las existentes será más fácil. 
###### Vídeo: [Interface Segregation Principle](https://platzi.com/clases/1630-mejor-codigo/21517-interface-segregation-principle/)
------------
#### ¿Qué nos enseña el Dependency Inversion Principle?
		 Que los componentes de alto nivel no deben depender de implementaciones particulares de componentes de bajo nivel
###### Razón: Este principio establece que los módulos de alto nivel no deben de depender de los de bajo nivel. En ambos casos deben depender de las abstracciones. Alto nivel se refiere a operaciones cuya naturaleza es más amplia o abarca un contexto más general y bajo nivel son componentes individuales más específicos.
###### Vídeo: [Dependency Inversion Principle](https://platzi.com/clases/1630-mejor-codigo/22211-dependency-inversion-principle/)
------------
#### ¿Qué es un patrón de diseño?
		 Un modelo de solución a una problemática común
###### Razón: Los patrones de diseño (design patterns) son soluciones habituales a problemas comunes en el diseño de software. Cada patrón es como un plano que se puede personalizar para resolver un problema de diseño particular del código.
###### Vídeo: [Patrones de diseño: Singleton](https://platzi.com/clases/1630-mejor-codigo/22212-patrones-de-diseno-singleton/)
------------
#### ¿Cuántas instancias de un Singleton existen en una aplicación?
		 1
###### Razón: Singleton es un patrón de diseño creacional que permite de que una clase tenga una única instancia, a la vez que proporciona un punto de acceso global a dicha instancia.
###### Vídeo: [Patrones de diseño: Singleton](https://platzi.com/clases/1630-mejor-codigo/22212-patrones-de-diseno-singleton/)
------------
#### ¿En qué casos conviene utilizar el patrón Factory?
		 Cuando la creación de instancias de una clase es especialmente compleja
###### Razón: Factory es un patrón de diseño creacional que proporciona una interfaz para crear objetos en una superclase, mientras permite a las subclases alterar el tipo de objetos que se crearán.
###### Vídeo: [Factory](https://platzi.com/clases/1630-mejor-codigo/22213-factory/)
------------
#### ¿En qué casos conviene utilizar el patrón Command?
		 Cuando se requiera realizar una misma funcionalidad independientemente del modo en que se ejecuta la aplicación
###### Razón: Command es un patrón de diseño de comportamiento que convierte una solicitud en un objeto independiente que contiene toda la información sobre la solicitud. Esta transformación te permite parametrizar los métodos con diferentes solicitudes, retrasar o poner en cola la ejecución de una solicitud y soportar operaciones que no se pueden realizar.
###### Vídeo: [Command](https://platzi.com/clases/1630-mejor-codigo/22214-command/)
------------
#### ¿Para qué sirve el Testing Automatizado?
		 Para mejorar las chances de atrapar errores antes de que lleguen a producción
###### Razón: El testing automatizado trata de escribir programas que sean capaces de probrar los programas y reportar los fallos. Existeng 2 tipos, unitarios: Es tomar cada unidad de software por separado y analizarla fuera de su contexto para validar que hace lo que tiene que hacer. En php esta disponilbe PHPUnit para realzar las pruebas unitarias. Integración: Vaida la interacción entre los componentes y el sistema completo.
###### Vídeo: [Introducción al Testing Automatizado](https://platzi.com/clases/1630-mejor-codigo/22215-introduccion-al-testing-automatizado/)
------------
#### ¿Qué ventaja tiene el testing automatizado respecto del testing manual?
		 Es más confiable
###### Razón: La automatización no requiere de intervención humana, por lo que se puede ejecutar la prueba automatizada de forma desatendida, fiabilidad técnica en procesos y en operación de equipos.
###### Vídeo: [Introducción al Testing Automatizado](https://platzi.com/clases/1630-mejor-codigo/22215-introduccion-al-testing-automatizado/)
------------
#### ¿Qué prueba el Unit Testing?
		 Unidades aisladas de software
###### Razón: Las pruebas unitarias, es tomar cada unidad de software por separado y analizarla fuera de su contexto para validar que hace lo que tiene que hacer. En php esta disponilbe PHPUnit para realzar las pruebas unitarias.
###### Vídeo: [Introducción al Testing Automatizado](https://platzi.com/clases/1630-mejor-codigo/22215-introduccion-al-testing-automatizado/)
------------
#### ¿Qué prueba el Integration Testing?
		 El modo en que las unidades (que se suponen correctas) interactúan entre sí
###### Razón: Una vez que se han aprobado las pruebas unitarias y lo que prueban es que todos los elementos unitarios que componen el software, funcionan juntos correctamente probándolos en grupo
###### Vídeo: [Introducción al Testing Automatizado](https://platzi.com/clases/1630-mejor-codigo/22215-introduccion-al-testing-automatizado/)
------------
#### ¿Qué propone el Test Driven Development?
		 Escribir primero las pruebas y luego el código
###### Razón: TDD (Desarrollo guiado por pruebas) es una práctica de programación que consiste en escribir primero las pruebas (generalmente unitarias), después escribir el código fuente que pase la prueba satisfactoriamente y, por último, refactorizar el código escrito.
###### Vídeo: [Test Driven Development](https://platzi.com/clases/1630-mejor-codigo/22216-test-driven-development/)
------------
#### ¿Cuál de esos es un beneficio de usar Test Driven Development?
		 Se escribe únicamente el código necesario
###### Razón: Al usar TDD se evita escribir codigo innecesario. En muchas ocasiones un programador crea más código del que necesita. Usando TDD, se va solucionando pequeñas tareas, superando test concretos, que ayudan a optimizar el tiempo y ser mucho más concretos durante la creación.
###### Vídeo: [Test Driven Development](https://platzi.com/clases/1630-mejor-codigo/22216-test-driven-development/)
------------
#### ¿Para qué sirve un Pull Request?
		 Para dar a otro miembro del equipo la posibilidad de revisar el código antes de integrarlo al repositorio principal
###### Razón: Un pull request es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork
###### Vídeo: [Pull rquests](https://platzi.com/clases/1630-mejor-codigo/21525-pull-requests/)
------------
#### ¿Para qué sirve documentar nuestro código?
		 Para facilitar la continuación del desarrollo por otro miembro del equipo o por el mismo aún si no se ha estado trabajando activamente por un tiempo
###### Razón: Documentar es una de las mejores prácticas que se pueden realizar. Dejar por escrito cómo se han hecho algunas funcionalidades, cómo podría ser mejorado el código y por sobretodo dejar comentarios en el código que ayuden a las personas a ubicarse en qué parte de la aplicación están y qué hacen esas líneas de código.
###### Vídeo: [Documentación](https://platzi.com/clases/1630-mejor-codigo/22217-documentacion/)
------------
#### ¿Qué tan complejo es escribir código de alta calidad?
		 Medianamente complejo
###### Razón: Para escribir código de calidad se debe girar entorno a la legibilidad, mantenibilidad, y testeabilidad.
###### Vídeo: [A quién beneficia el código bien escrito](https://platzi.com/clases/1630-mejor-codigo/22218-a-quien-beneficia-el-codigo-bien-escrito/)