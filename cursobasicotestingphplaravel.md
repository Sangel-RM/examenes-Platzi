# Curso Básico de Testing con PHP y Laravel
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es una prueba en Unit?
		 Aquella que se centra en una parte muy pequeña y aislada de código.
###### Razón: Las pruebas unitarias consisten en verificar el comportamiento de las unidades más pequeñas de su aplicación. Usualmente son métodos de una clase.
###### Vídeo: [Unit y Feature](https://platzi.com/clases/2186-laravel-testing/34775-unit-y-feature/)
------------
#### ¿Qué es una prueba en Feature?
		 Aquella que prueba una parte mayor del código, esta puede incluir rutas, controladores y vistas.
###### Razón:  En feature van los test en que se realizan comprobaciones más complejas
###### Vídeo: [Unit y Feature](https://platzi.com/clases/2186-laravel-testing/34775-unit-y-feature/)
------------
#### Si espero "true" en algún proceso, ¿qué método puedo usar en las pruebas?
		 assertTrue()
###### Razón: Reporta un error identificado por el $message si la condición es falsa.
###### Vídeo: [El resultado](https://platzi.com/clases/2186-laravel-testing/34776-el-resultado/)
------------
#### ¿Cuál es el objetivo de las pruebas?
		 Garantizar que obtenemos el resultado esperado.
###### Razón: El testing evita que los errores o puntos vulnerables en el desarrollo del proyecto lleguen al cliente, o al usuario. Por lo que las pruebas frecuentes, y un testing de gran calidad es vital en el proceso de desarrollo.
###### Vídeo: [La función del testing](https://platzi.com/clases/2186-laravel-testing/34773-la-funcion-del-testing/)
------------
#### ¿Cómo creamos una imagen fake para probar?
		 Con la clase UploadedFile y el método fake().
###### Razón: La clase UploadedFile proporciona el método fake el cuál puede ser usado para generar archivos o imágenes ficticias para las pruebas.
###### Vídeo: [Carga de archivos](https://platzi.com/clases/2186-laravel-testing/34780-carga-de-archivos/)
------------
#### ¿Qué es la refactorización?
		 Es mejorar el código sin cambiar su comportamiento.
###### Razón: Refactorizar el código es cambiar el código con dos restricciones cruciales: Los cambios hacen que el código sea más fácil de entender y, por tanto, más fácil de modificar. Los cambios nunca modifican la funcionalidad, el comportamiento observable, del código.
###### Vídeo: [TDD](https://platzi.com/clases/2186-laravel-testing/34785-tdd/)
------------
#### ¿Qué método usamos normalmente para probar una validación?
		 assertSessionHasErrors()
###### Razón: El método assertSessionHasErrors() afirma si la sesión contiene algún error.
###### Vídeo: [Validación](https://platzi.com/clases/2186-laravel-testing/34783-validacion/)
------------
#### ¿Qué base de datos debo usar para probar mediante PHPUnit?
		 Una independiente normalmente configurada en SQLite.
###### Razón: Para configurar una base de datos de pruebas, se debe descomentar las líneas respecto a la base de datos en el archivo de phpunit.xml
###### Vídeo: [Database](https://platzi.com/clases/2186-laravel-testing/34784-database/)
------------
#### Si voy a probar la entidad User, ¿cómo crearía la prueba?
		 php artisan make:test Models/UserTest --unit
###### Razón: Las entidades son los modelos del proyecto, es por ello que deben ir en la carpeta Models.
###### Vídeo: [Database](https://platzi.com/clases/2186-laravel-testing/34784-database/)
------------
#### ¿Qué método usamos para ver si contamos con data en alguna tabla?
		 assertDatabaseHas()
###### Razón: Comprueba si el registro dado se encuentra en la base de datos. 
###### Vídeo: [Database](https://platzi.com/clases/2186-laravel-testing/34784-database/)
------------
#### ¿Donde configuramos a PHPUnit?
		 En el archivo phpunit.xml.
###### Razón: Los atributos del elemento <phpunit> se pueden usar para configurar la funcionalidad del núcleo de PHPUnit. El XML de configuración corresponde al comportamiento por defecto del ejecutor de pruebas.
###### Vídeo: [Database](https://platzi.com/clases/2186-laravel-testing/34784-database/)
------------
#### ¿Qué pruebas puedo crear por defecto en Laravel?
		 Unit y Feature.
###### Razón: Las pruebas unitarias consisten en verificar el comportamiento de las unidades más pequeñas de su aplicación. Usualmente son métodos de una clase.  En feature van los test en que se realizan comprobaciones más complejas.
###### Vídeo: [Unit y Feature](https://platzi.com/clases/2186-laravel-testing/34775-unit-y-feature/)
------------
#### ¿Debemos instalar a PHPUnit en Laravel?
		 No, está instalado por defecto.
###### Razón: La librería de PHPUnit en Laravel se incluye por defecto al crear un nuevo proyecto Laravel.
###### Vídeo: [PHPUnit en Laravel](https://platzi.com/clases/2186-laravel-testing/34774-phpunit-en-laravel/)
------------
#### ¿Cómo se llama el archivo de testing por defecto?
		 ExampleTest
###### Razón: El archivo de Test por defecto se puede encontrar en la carpeta de tests del proyecto Laravel.
###### Vídeo: [PHPUnit en Laravel](https://platzi.com/clases/2186-laravel-testing/34774-phpunit-en-laravel/)
------------
#### ¿Puedo probar solicitudes HTTP?
		 Si, lo hacemos en Feature.
###### Razón: Las solictudes HTTP pueden ser probabas, mediante el métodos post y get.
###### Vídeo: [Nuevo registro](https://platzi.com/clases/2186-laravel-testing/34789-nuevo-registro/)
------------
#### ¿Cuál es el estándar para los métodos de un test?
		 Estos deben comenzar con la palabra test
###### Razón: Los métodos en las clases test deben inciar con la palabra test. Por ejemplo: testHome()
###### Vídeo: [El resultado](https://platzi.com/clases/2186-laravel-testing/34776-el-resultado/)
------------
#### ¿Cuál es el estándar para una clase test?
		 Estas deben terminar con la palabra Test.
###### Razón: Los nombre de las clases test deben terminar con la palabra test. Por ejemplo: UserTest.php
###### Vídeo: [El resultado](https://platzi.com/clases/2186-laravel-testing/34776-el-resultado/)
------------
#### ¿Qué comando usamos para ejecutar los test en laravel?
		 php artisan test
###### Razón: El comando php artisan test, ejecuta todos las clases tests.
###### Vídeo: [El resultado](https://platzi.com/clases/2186-laravel-testing/34776-el-resultado/)
------------
#### ¿Qué comprobamos con un test?
		 Un resultado
###### Razón: El testing es una herramienta que ayuda a respaldar el código hecho, evitando que se envíen errores a producción. De la misma manera al hacer cambios en código, las pruebas deben ser actualizadas para que coincidan con estos cambios.
###### Vídeo: [La función del testing](https://platzi.com/clases/2186-laravel-testing/34773-la-funcion-del-testing/)
------------
#### Si tenemos muchos métodos, ¿podemos probar uno expecífico?
		 Si, usando --filter.
###### Razón: Si se desea ejecutar los test de un clase, se puede especificar mediante el flag, --filter. Por ejemplo: php artisan test --filter testMiMetodo
###### Vídeo: [El resultado](https://platzi.com/clases/2186-laravel-testing/34776-el-resultado/)
