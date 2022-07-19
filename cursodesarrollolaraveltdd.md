# Curso de Desarrollo en Laravel con Test Driven Development
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué significa el estado ROJO?
		 Generalmente una prueba que no obtiene el resultado esperado
###### Razón: El test-driven development es una metodología de diseño de software que se basa en test o pruebas para guiar el proceso. Tiene 3 fases:
###### Fase roja (red phase): Se redacta, un test que contenga componentes que aún no hayan sido implementados, para luego decidir qué elementos son realmente necesarios para que el código funcione.
###### Fase verde: Luego de que el test falle y se marque en rojo, se intenta encontrar una solución simple.Es muy importante redactar únicamente la cantidad de código que sea necesaria. El código redactado se integra luego en el código productivo, de forma que el test quede marcado en verde.
###### Refactorización: en este paso, el código productivo se pasa a limpio y se perfecciona su estructura. El código se reestructura de manera que resulte elegante y comprensible para los desarrolladores. Entre otras cosas, se eliminan los duplicados en el código, y se vuelve más profesional.
###### Vídeo: [Todo lo que aprenderás sobre TDD en Laravel](https://platzi.com/clases/2187-laravel-tdd/34512-bienvenida/)
------------
#### ¿Qué clase usamos para probar una relación uno a muchos?
		 Illuminate\Database\Eloquent\Collection
###### Razón: La clase Collection devuelve más de un resultado del modelo devolverá instancias de la clase Illuminate\Database\Eloquent\Collection, incluyendo los resultados recuperados a través del método get o accedidos a través de una relación. 
###### Vídeo: [Relaciones: múltiples](https://platzi.com/clases/2187-laravel-tdd/34515-relaciones-multiples/)
------------
#### ¿Cómo protegemos nuestras rutas?
		 Con el middleware auth
###### Razón: Los middleware proporcionan un mecanismo conveniente para filtrar solicitudes HTTP entrantes a tu aplicación. Por ejemplo, Laravel incluye un middleware que verifica si el usuario de tu aplicación está autenticado.
###### Vídeo: [Proteger rutas](https://platzi.com/clases/2187-laravel-tdd/34517-proteger-rutas/)
------------
#### ¿Qué clase usamos para trabajar con datos falsos -fake- en las pruebas?
		 Illuminate\Foundation\Testing\WithFaker
###### Razón: Faker permite generar distintos tipos de información aleatoria.
###### Vídeo: [Nuevo registro](Illuminate\Foundation\Testing\WithFaker)
------------
#### ¿Qué clase importo a mis rutas para interactuar con Laravel?
		 Tests\TestCase
###### Razón: Tests\TestCase Esta es una clase padre para muchos tipos de pruebas (pueden ser unitarias, de integración o de características) que dependen de la aplicación Laravel para funcionar. Estos escenarios podrían incluir: El uso de factories para crear modelos, el uso de facades y sus datos falsos, componentes de pruebas unitarias que utilizan helpers globales (por ejemplo, config()), usar transacciones de base de datos y/o reinicios para cada prueba.
###### PHPUnit\Framework\TestCase es el padre de Tests\TestCase, por lo que toda la funcionalidad estándar de PHPUnit también está disponible.
###### Vídeo: [Relaciones: múltiples](https://platzi.com/clases/2187-laravel-tdd/34515-relaciones-multiples/)
------------
#### ¿Qué método usamos para trabajar con un usuario logueado?
		 actingAs()
###### Razón: El método actingAs()  proporciona una forma sencilla de autenticar a un usuario dado como el usuario actual.
###### Vídeo: [Nuevo registro](Illuminate\Foundation\Testing\WithFaker)
------------
#### Si deseamos probar una redirección de validación, ¿qué usamos?
		 assertStatus(302)
###### Razón: El método assertStatus(), afirma que la respuesta devuelta debe tener el código de estado HTTP dado, El código de estado 302 es un mensaje de redirección que se produce cuando un recurso o una página que está intentando cargar se ha movido temporalmente a una ubicación diferente.
###### Vídeo: [Validación](https://platzi.com/clases/2187-laravel-tdd/34520-validacion/)
------------
#### ¿Qué estado HTTP usamos para probar una política de acceso?
		 403
###### Razón: Error 403 Forbidden es un código de estado HTTP que indica que el servidor deniega la acción solicitada, página web o servicio. En otras palabras, el servidor ha podido ser contactado, y ha recibido una petición válida, pero ha denegado el acceso a la acción que se solicita.
###### Vídeo: [Proteger: actualizar](https://platzi.com/clases/2187-laravel-tdd/34522-proteger-actualizar/)
------------
#### ¿Qué método uso para comprobar que un texto se imprime en la vista?
		 assertSee()
###### Razón: El método assertSee(), comprueba si el string dado esta contenida en la respuesta.
###### Vídeo: [Listado personal](https://platzi.com/clases/2187-laravel-tdd/34524-listado-personal/)
------------
#### ¿Qué método usamos para trabajar con una política desde el controlador?
		 authorize()
###### Razón: Si se desea autorizar una acción, se debe trabajar con un Policy. Si el usuario no está autorizado a realizar la acción dada, puede utilizar el método authorize. Las instancias de AuthorizationException son convertidas automáticamente en una respuesta HTTP 403 por el manejador de excepciones de Laravel.
###### Vídeo: [Políticas de acceso](https://platzi.com/clases/2187-laravel-tdd/34533-politicas-de-acceso/)
------------
#### ¿Qué es refactorizar?
		 Es mejorar el código sin alterar la prueba
###### Razón: La refactorización es una técnica para reestructurar un código fuente, alterando su estructura interna sin cambiar su comportamiento externo
###### Vídeo: [Todo lo que aprenderás sobre TDD en Laravel](https://platzi.com/clases/2187-laravel-tdd/34512-bienvenida/)
------------
#### ¿Qué significa el estado VERDE?
		 Significa que hemos escrito el código que satisface la prueba
###### Razón: El test-driven development es una metodología de diseño de software que se basa en test o pruebas para guiar el proceso. Tiene 3 fases:
###### Fase roja (red phase): Se redacta, un test que contenga componentes que aún no hayan sido implementados, para luego decidir qué elementos son realmente necesarios para que el código funcione.
###### Fase verde: Luego de que el test falle y se marque en rojo, se intenta encontrar una solución simple.Es muy importante redactar únicamente la cantidad de código que sea necesaria. El código redactado se integra luego en el código productivo, de forma que el test quede marcado en verde.
###### Refactorización: en este paso, el código productivo se pasa a limpio y se perfecciona su estructura. El código se reestructura de manera que resulte elegante y comprensible para los desarrolladores. Entre otras cosas, se eliminan los duplicados en el código, y se vuelve más profesional.###### Vídeo: [Todo lo que aprenderás sobre TDD en Laravel](https://platzi.com/clases/2187-laravel-tdd/34512-bienvenida/)
------------
#### ¿Con qué método vefiricamos en PHPUnit que contamos con el objeto esperado?
		 $this->assertInstanceOf()
###### Razón: El método assertInstanceOf comprueba si el segundo parámetro es una instancia del primer parámetro.
###### Vídeo: [Relaciones: múltiples](https://platzi.com/clases/2187-laravel-tdd/34515-relaciones-multiples/)
------------
#### ¿Qué base de datos usamos generalmente para el testing?
		 SQLite
###### Razón: SQLite permite almacenar información en dispositivos empotrados de una forma sencilla, eficaz, potente, rápida. Laravel lo usa para realizar los test, esto se debe configurar en el archivo phpunit.xml
###### Vídeo: [Configuración Inicial del proyecto](https://platzi.com/clases/2187-laravel-tdd/34514-configuracion-inicial-del-proyecto/)
------------
#### ¿Con qué middleware protegemos nuestrar rutas?
		 Auth
###### Razón: Los middleware proporcionan un mecanismo conveniente para filtrar solicitudes HTTP entrantes a tu aplicación. Laravel incluye el middleware auth, que verifica si el usuario de tu aplicación está autenticado.
###### Vídeo: [Proteger rutas](https://platzi.com/clases/2187-laravel-tdd/34517-proteger-rutas/)
------------
#### ¿Qué método usamos para verificar que contamos con un registro en una tabla?
		 $this->assertDatabaseHas()
###### Razón: El método assertDatabaseHas afirmar que una tabla de la base de datos contiene registros que coinciden con las restricciones de consulta de clave/valor dadas.
###### Vídeo: [Nuevo registro](Illuminate\Foundation\Testing\WithFaker)
------------
#### ¿Qué estado HTTP usamos para probar una validación?
		 302
###### Razón: El método assertStatus(), afirma que la respuesta devuelta debe tener el código de estado HTTP dado, El código de estado 302 es un mensaje de redirección que se produce cuando un recurso o una página que está intentando cargar se ha movido temporalmente a una ubicación diferente.
###### Vídeo: [Validación](https://platzi.com/clases/2187-laravel-tdd/34520-validacion/)
------------
#### ¿Qué método usamos para verificar que hemos eliminado un registro?
		 $this->assertDatabaseMissing()
###### Razón: El método assetDatabaseMissing(), afirmar que una tabla de la base de datos no contiene registros que coincidan con las restricciones de consulta de clave/valor dadas.
###### Vídeo: [Eliminar registro](https://platzi.com/clases/2187-laravel-tdd/34521-eliminar-registro/)
------------
#### ¿Con qué comando creamos un archivo para la validación?
		  php artisan make:request
###### Razón: Este comando ayuda a crear un archivo para validar los requests. Es útil en caso de que no se desee validar los request desde el controller.
###### Vídeo: [Validación de datos](https://platzi.com/clases/2187-laravel-tdd/34531-validacion-de-datos/)
------------
#### ¿Con qué comando creamos un archivo con políticas?
		 php artisan make:policy
###### Razón: Las políticas son clases que organizan la lógica de autorización en torno a un modelo o recurso concreto.
###### Vídeo: [Políticas de acceso](https://platzi.com/clases/2187-laravel-tdd/34533-politicas-de-acceso/)
