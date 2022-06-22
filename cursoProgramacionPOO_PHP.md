# Curso de Programación Orientada a Objetos en PHP
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es la programación orientada a objetos?
		 Es un paradigma de programación, actualmente uno de los más populares.
###### Razón: La Programación Orientada a Objetos (POO), es un paradigma de programación, es decir, un modelo o un estilo de programación. Se basa en el concepto de clases y objetos. Este tipo de programación se utiliza para estructurar un programa de software en piezas simples y reutilizables de planos de código (clases) para crear instancias individuales de objetos. 
###### Vídeo: [Introducción a clases y objetos](https://platzi.com/clases/2034-php-poo/32129-introduccion-a-clases-y-objetos/)
------------
#### ¿Qué es la deuda técnica?
		 Es el re-trabajo ocasionado por programar algo que "simplemente funciona".
###### Razón: La deuda técnica es el coste y los intereses a pagar por hacer mal las cosas. El sobre esfuerzo a pagar para mantener un producto software mal hecho, y lo que conlleva, como el coste de la mala imagen frente a los clientes.
###### Vídeo: [Deuda técnica](https://platzi.com/clases/2034-php-poo/32125-deuda-tecnica/)
------------
#### ¿Qué queremos decir con code smell?
		 Que nuestro sistema tiene problemas de orden y diseño.
###### Razón: Hace referencia al mal olor del código. Este concepto no se refiere a errores técnicos, sino a errores de orden y diseño. Esto sucede mucho cuando se intenta crear soluciones a partir de otras soluciones.
###### Vídeo: [Code smell](https://platzi.com/clases/2034-php-poo/32126-code-smell/)
------------
#### ¿Cómo debemos abordar un proyecto?
		 Primero resolvemos el problema, luego organizo de manera coherente sin alterar el resultado.
###### Razón: Cuando no se aborda un proyecto de la manera correcta, es probable que el proyecto contenga código espagueti. El código espagueti es un término “despectivo” que se utiliza cuando el código tiene una estructura de control de flujo compleja y cuando se ve este código se parece mucho a un plato de espagueti, como si fuera un montón de hilos enredados.
###### Vídeo: [Código espagueti](https://platzi.com/clases/2034-php-poo/32127-codigo-espagueti/)
------------
#### ¿Cómo podemos incluir códigos de otros archivos?
		 Usando include, require o require_once.
###### Razón: En PHP es posible incluir archivos dentro de otro. include: Permite incluir un archivo dentro de otro. Sino lo encuentra solo genera un warning que permite continuar. Require: en caso de no encontrar el archivo producirá un error fatal, no permitirá continuar con el proceso. Require_once, al igual que Require pero además verificará si el archivo ya ha sido incluido y si es así, no se incluye.
###### Vídeo: [Inclusión de archivos](https://platzi.com/clases/2034-php-poo/32128-inclusion-de-archivos/)
------------
#### ¿Qué es un objeto?
		 Es la instancia de una clase.
###### Razón: Un objeto en POO representa alguna entidad de la vida real, es decir, alguno de los objetos únicos que pertenecen al problema a resolver. Cada objeto, de igual modo que la entidad de la vida real a la que representa, tiene un estado (es decir, unos atributos con unos valores concretos) y un comportamiento (es decir, tiene funcionalidades o sabe hacer unas acciones concretas).
###### Vídeo: [Introducción a clases y objetos](https://platzi.com/clases/2034-php-poo/32129-introduccion-a-clases-y-objetos/)
------------
#### ¿Cuáles son las características de la programación orientada a objetos?
		 Herencia, abstracción, polimorfismo, modularidad y encapsulamiento.
###### Razón: Herencia: La herencia permite reutilizar el código programado en cada clase “heredando” o extendiendo las características de un objeto a sus “descendientes” o derivados. Abstracción: La abstracción es un procedimiento que permite la elección de una determinada entidad de la realidad, sus características y funciones que desempeñan, la cual es representada mediante clases que contienen atributos y métodos de dicha clase. Polimorfismo: El polimorfismo, en una colección de objetos con herencia, si las clases especializadas de una superclase tienen un método con la misma definición, reaccionarán de la manera adecuada cuando reciban el mismo mensaje. Modularidad: La modularidad es separar partes del código de modo que se vuelvan independientes, pero que en conjunto cumplan sus funciones principales. Encapsulamiento: El encapsulamiento es proteger la información o el estado de los atributos para que no se pueda ver o modificar la información del objeto sin el mecanismo adecuado. Para ello, se utilizan métodos para recuperar la información (getters) y asegurar que la información proporcionada sea consistente con el objeto; y a su vez, poder asignar (setters) un nuevo valor y verificar que no afecte la integridad del objeto.
###### Vídeo: [Introducción a clases y objetos](https://platzi.com/clases/2034-php-poo/32129-introduccion-a-clases-y-objetos/)
------------
#### ¿Qué es la abstracción?
		 Es aislar, separar o sacar con el fin de organizar.
###### Razón:  La abstracción es un procedimiento que permite la elección de una determinada entidad de la realidad, sus características y funciones que desempeñan, la cual es representada mediante clases que contienen atributos y métodos de dicha clase.
###### Vídeo: [Abstracción](https://platzi.com/clases/2034-php-poo/32130-abstraccion/)
------------
#### ¿Qué garantizamos con el encapsulamiento?
		 La integridad de los datos o propiedades de un objeto.
###### Razón: El alcance hace referencia al encapsulamiento o principio de ocultación. Para ello, se utilizan métodos para recuperar la información (getters) y asegurar que la información proporcionada sea consistente con el objeto; y a su vez, poder asignar (setters) un nuevo valor y verificar que no afecte la integridad del objeto.
###### Vídeo: [Alcance o Encapsulamiento](https://platzi.com/clases/2034-php-poo/32131-alcance-o-encapsulamiento/)
------------
#### ¿Qué es la modularidad?
		 Es desarrollar un módulo que unido a otros forman un proyecto.
###### Razón: La modularidad es separar partes del código de modo que se vuelvan independientes, pero que en conjunto cumplan sus funciones principales.
###### Vídeo: [Modularidad](https://platzi.com/clases/2034-php-poo/32132-modularidad/)
------------
#### ¿Qué entendemos por polimorfismo?
		 Es la virtud que tienen algunos elementos para comportarse de diferentes maneras y emitir diferentes resultados.
###### Razón: Es la capacidad de invocar al mismo método desde distintos objetos, y que cada uno de esos objetos pueda responder a esa función o método de forma distinta.
###### Vídeo: [Polimorfismo](https://platzi.com/clases/2034-php-poo/32133-polimorfismo/)
------------
#### ¿Qué es la herencia?
		 Es unir mis propios métodos con los métodos de una clase padre.
###### Razón: Es un mecanismo que permite derivar una clase a otra clase. En otras palabras, habrá unas clases que serán hijos, y otras clases que serán padres.
###### Vídeo: [Herencia](https://platzi.com/clases/2034-php-poo/32135-herencia/)
------------
#### ¿Qué es una interface?
		  Es un contrato que deben cumplir las clases al implementarlas.
###### Razón: Es un tipo de clase en la que se declaran los métodos sin definir ninguna funcionalidad y estos cuando se implemente la interfaz en una clase hija, se deben declarar de nuevo, esta vez si, definiendo la funcionalidad que se necesite.
###### Vídeo: [Interfaces](https://platzi.com/clases/2034-php-poo/32136-interfaces/)
------------
#### ¿Qué es PHPUnit?
		 Es un framework para respaldar a nuestro código con pruebas.
###### Razón: PHPUnit es el framework para implementar las pruebas unitarias en lenguaje PHP.
###### Vídeo: [Iniciando nuestro proyecto: PHPUnit y clases heredadas](https://platzi.com/clases/2034-php-poo/32137-iniciando-nuestro-proyecto-phpunit-y-clases-hereda/)
------------
#### ¿Por qué creamos pruebas?
		 Para tener garantía en el futuro de que no hemos dañado o alterado un código antiguo.
###### Razón: Las pruebas unitarias es un elemento fundamental en el desarrollo de cualquier sistema, de esta manera se garantiza que cada una de las partes delcódigo interno, clases,métodos, interfaces esté probado y funciona correctamente, esto es importante para prevenir cualquier imperfecto de alguna validación o seguridad del funcionamiento del sistema.
###### Vídeo: [Revisión del proyecto](https://platzi.com/clases/2034-php-poo/32138-revision-del-proyecto/)