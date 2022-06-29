# Curso Intermedio de PHP: Cookies, Sesiones y Modularización
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué son las cookies?
		 Son pedacitos de información que se guardan en la memoria de la computadora del usuario para personalizar su experiencia en un sitio web.
###### Razón: Las cookies son pequeños fragmentos de texto que los sitios web que visitas envían al navegador. Permiten que los sitios web recuerden información sobre tu visita, lo que puede hacer que sea más fácil volver a visitar los sitios y hacer que estos te resulten más útiles.
###### Vídeo: [¿Qué son las cookies?](https://platzi.com/clases/3144-php-cookies-sesiones/49693-que-son-las-cookies/)
------------
#### ¿Puedo usar cookies sin notificarle al usuario?
		 No. Siempre hay que tener un aviso de cookies para que el usuario esté consciente de la información que estamos almacenando.
###### Razón: Es importante notificarle al usuario, si proporciona su consentimiento para almacenar su información.
###### Vídeo: [¿Qué son las cookies?](https://platzi.com/clases/3144-php-cookies-sesiones/49693-que-son-las-cookies/)
------------
#### ¿Cómo puedo acceder al id de una sesión que ya fue definido previamente?
		 $_SESSION["id"];
###### Razón: A través de la variable global $_SESSION, se puede acceder a un array asociativo que contiene variables de sesión disponibles para el script actual. 
###### Vídeo: [¿Qué son las sesiones?](https://platzi.com/clases/3144-php-cookies-sesiones/49695-que-son-las-sesiones/)
------------
#### ¿Con cuál función podemos finalizar una sesión?
		 session_destroy();
###### Razón: session_destroy() destruye toda la información asociada con la sesión actual.
###### Vídeo: [Trabajando con sesiones](https://platzi.com/clases/3144-php-cookies-sesiones/49696-trabajando-con-sesiones/)
------------
#### ¿Cuál estructura nos permite manejar excepciones en PHP?
		 try/catch
###### Razón: Un bloque catch contiene sentencias que especifican que hacer si una excepción es lanzada en el bloque try . Si cualquier sentencia dentro del bloque try (o en una funcion llamada desde dentro del bloque try ) lanza una excepción, el control cambia inmediatamente al bloque catch.
###### Vídeo: [¿Qué son las excepciones?](https://platzi.com/clases/3144-php-cookies-sesiones/49697-que-son-las-excepciones/)
------------
#### ¿A través de cuál método podríamos obtener la línea de código desde la cual una excepción fue lanzada?
		 getLine()
###### Razón: Devuelve el número de la línea donde se creó la excepción.
###### Vídeo: [Revisando los métodos de las excepciones](https://platzi.com/clases/3144-php-cookies-sesiones/49699-revisando-los-metodos-de-las-excepciones/)
------------
#### ¿Cómo puedo crear mis propias excepciones personalizadas en PHP?
		 Extendiendo la clase base Exception de PHP.
###### Razón: Una clase de Excepción definida por el usuario puede ser definida ampliando la clase Exception
###### Vídeo: [Crea tus propias excepciones](https://platzi.com/clases/3144-php-cookies-sesiones/49700-crea-tus-propias-excepciones/)
------------
#### ¿Puedo atrapar distintas excepciones en un mismo bloque de código?
		 Verdadero. Puedo poner varios bloques catch en los cuales, por medio de la clase de la excepción, puedo indicar cuál atrapar.
###### Razón: Colocando diversos bloques catch, se pueden atrapar diversas excepciones que se especifiquen.
###### Vídeo: [Crea tus propias excepciones](https://platzi.com/clases/3144-php-cookies-sesiones/49700-crea-tus-propias-excepciones/)
------------
#### ¿Cuál función me permite añadir y quitar días a una fecha de forma dinámica?
		 date_modify
###### Razón: Altera la marca temporal de un objeto DateTime aumentando o disminuyendo.
###### Vídeo: [Funciones para fechas](https://platzi.com/clases/3144-php-cookies-sesiones/49703-funciones-para-fechas/)
------------
#### ¿Por qué es importante modularizar el código?
		 Porque nos permite dividir el problema en pequeños pedacitos a su vez que hará un código más fácil de leer y mantener.
###### Razón: Un código Modularizado permite realizar o introducir cambios de forma más sencilla pues cada bloque o archivo se encargará de una tarea especifica. Permitiendo que sea escalable, optimizado y reutilizable para diferentes partes de la aplicación.
###### Vídeo: [Modularización del código](https://platzi.com/clases/3144-php-cookies-sesiones/49706-modularizacion-del-codigo/)
------------
#### ¿Qué es un Front Controller?
		 Es el punto de entrada de mi aplicación en cual gestionará las solicitudes y responderá con la página o datos que el usuario necesite.
###### Razón: Un Front Controller actúa como un único punto de entrada a una página web desde el cual se pueden cargar las páginas solicitadas.
###### Vídeo: [Front Controller](https://platzi.com/clases/3144-php-cookies-sesiones/49709-front-controller/)
------------
#### ¿Qué me permite hacer el archivo .htaccess?
		 Me permite reescribir ciertas reglas de Apache para poder hacer modificaciones como la reescritura de URL, teniendo así URL más amigables.
###### Razón: El archivo htaccess (acceso de hipertexto) es un archivo oculto que se utiliza para configurar funciones adicionales para sitios web alojados en el servidor web Apache. Con él, es posible reescribir la URL, proteger directorios con contraseña, habilitar la protección de enlaces directos, no permitir el acceso a direcciones IP específicas, cambiar la zona horaria de tu sitio web o alterar la página de índice predeterminada.
###### Vídeo: [El archivo .htaccess](https://platzi.com/clases/3144-php-cookies-sesiones/49710-el-archivo-htaccess/)
------------
#### Si tengo una clase `Perro` y una clase `Gato`, y ambas tienen un método llamado `jugar()` que tiene el mismo comportamiento para ambas clases... ¿qué feature de PHP debería usar para declarar dicho método?
		 Traits
###### Razón: Los traits son un mecanismo de reutilización de código en leguajes que tienen herencia simple, como PHP. El objetivo de los traits es reducir las limitaciones de la herencia simple permitiendo reutilizar métodos en varias clases independientes y de distintas jerarquías. Un trait es similar a una clase, pero su objetivo es agrupar funcionalidades específicas. Un trait, al igual que las clases abstractas, no se puede instanciar, simplemente facilita comportamientos a las clases sin necesidad de usar la herencia
###### Vídeo: [Traits](https://platzi.com/clases/3144-php-cookies-sesiones/49711-traits/)
------------
#### ¿Qué son los traits?
		 Son una alternativa a la herencia en PHP. Permite definir métodos que pueden ser compartidos o reutilizados por varias clases.
###### Razón: Los traits son un mecanismo de reutilización de código en leguajes que tienen herencia simple, como PHP. El objetivo de los traits es reducir las limitaciones de la herencia simple permitiendo reutilizar métodos en varias clases independientes y de distintas jerarquías. Un trait es similar a una clase, pero su objetivo es agrupar funcionalidades específicas. Un trait, al igual que las clases abstractas, no se puede instanciar, simplemente facilita comportamientos a las clases sin necesidad de usar la herencia
###### Vídeo: [Traits](https://platzi.com/clases/3144-php-cookies-sesiones/49711-traits/)
------------
#### ¿Cuál de las siguientes funciones daría un Fatal Error en caso de que no encuentre el archivo a importar?
		 require()
###### Razón: require, incluye el archivo que se le especifique sin problemas. Si no se encuentra dicho archivo, se generará un error fatal.
###### Vídeo: [Modularización del código](https://platzi.com/clases/3144-php-cookies-sesiones/49706-modularizacion-del-codigo/)
