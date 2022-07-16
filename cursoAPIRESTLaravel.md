# Curso de API REST con Laravel
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es un API?
		 Código preparado en el servidor para que otros sistemas se puedan conectar.
###### Razón: API significa “interfaz de programación de aplicaciones”. En el contexto de las API, la palabra aplicación se refiere a cualquier software con una función distinta. La interfaz puede considerarse como un contrato de servicio entre dos aplicaciones. Este contrato define cómo se comunican entre sí mediante solicitudes y respuestas. La documentación de su API contiene información sobre cómo los desarrolladores deben estructurar esas solicitudes y respuestas.
###### Vídeo: [¿Qué es un API?](https://platzi.com/clases/2185-laravel-api/34816-que-es-un-api/)
------------
#### ¿Cuántas rutas puede manejar normalmente un API?
		 5 rutas.
###### Razón: Las rutas que maneja un controlador API son: index, store, show, update y destroy.
###### Vídeo: [Versión 1: planificación y configuración inicial](https://platzi.com/clases/2185-laravel-api/34821-version-1-planificacion-y-configuracion-inicial/)
------------
#### ¿Cuál es el aspecto típico de los endpoints?
		 http://laravel-api.test/api/v1/posts/1
###### Razón: Un endpoint de API es el lugar donde se realizan esas solicitudes (conocidas como llamadas API).
###### Vídeo: [Versión 1: planificación y configuración inicial](https://platzi.com/clases/2185-laravel-api/34821-version-1-planificacion-y-configuracion-inicial/)
------------
#### ¿Por qué versionamos un API?
		 Así nuestro código nuevo no altera el funcionamiento del código anterior.
###### Razón: El versionado ayuda a iterar más rápido y evitar peticiones inválidas desde endpoints actualizados.
###### Vídeo: [Versión 2: planificación y configuración inicial](https://platzi.com/clases/2185-laravel-api/34825-version-2-planificacion-y-configuracion-inicial/)
------------
#### ¿Qué es un API privada?
		 Un API que requiere de login.
###### Razón: Una API privada, es aquella que requiere de autenticación para acceder a sus recursos.
###### Vídeo: [Introducción a la API privada](https://platzi.com/clases/2185-laravel-api/34828-introduccion-a-la-api-privada/)
------------
#### ¿Para qué usamos Postman?
		 Para probar nuestro código construido en el servidor.
###### Razón: Postman es una aplicación que permite testear APIs a través de una interfaz gráfica de usuario. Entre las ventajas que tiene Postman se encuentra la capacidad de crear colecciones y distintos ambientes de pruebas. Postman es una herramienta fácil de usar que ayuda a optimizar el tiempo de ejecución de pruebas.
###### Vídeo: [Versión 1: planificación y configuración inicial](https://platzi.com/clases/2185-laravel-api/34821-version-1-planificacion-y-configuracion-inicial/)
------------
#### ¿Qué encabezado es importante para obtener un comportamiento API real?
		 Accept: application/json.
###### Razón: Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. El encabezado accept es una petición para enviar datos como un objeto JSON.
###### Vídeo: [Acceso](https://platzi.com/clases/2185-laravel-api/34830-acceso/)
------------
#### ¿Qué método usamos para crear un token de acceso?
		 createToken()
###### Razón: El método createToken devuelve una instancia Laravel\Sanctum\NewAccessToken. Los tokens de la API se codifican utilizando el hash SHA-256 antes de ser almacenados en la base de datos.
###### Vídeo: [Acceso](https://platzi.com/clases/2185-laravel-api/34830-acceso/)
------------
#### ¿Qué necesitamos en un API?
		 Ruta, Controlador y Recurso.
###### Razón: La ruta dispara un controlador, entonces el controlador tiene dentro de si una acción, esta acción retorna ese recurso y eso es lo que es mostrado al usuario o al software que se vaya a conectar a la aplicación.
###### Vídeo: [Versión 1: recurso](https://platzi.com/clases/2185-laravel-api/34822-version-1-recurso/)
------------
#### ¿Qué status HTTP enviamos para indicar que no se puede autorizar el acceso?
		 401
###### Razón: El código 401 Unauthorized, indica que la petición (request) no ha sido ejecutada porque carece de credenciales válidas de autenticación para el recurso solicitado.
###### Vídeo: [Versión 1: colección](https://platzi.com/clases/2185-laravel-api/34823-version-1-coleccion/)
------------
#### ¿Cuántas versiones podría crear?
		 Las necesarias.
###### Razón: Se pueden crear tantas versiones de API como uno desee, debido a que depende de lo que le solicitan.
###### Vídeo: [Versión 2: planificación y configuración inicial](https://platzi.com/clases/2185-laravel-api/34825-version-2-planificacion-y-configuracion-inicial/)
------------
#### ¿Qué es Laravel Sanctum?
		 Sistema de login basado en tokens.
###### Razón: Laravel Sanctum proporciona un sistema de autenticación para SPA (aplicaciones de una sola página), aplicaciones móviles y API simples basadas en tokens. Sanctum permite que cada usuario de su aplicación genere múltiples tokens API para su cuenta.
###### Vídeo: [Introducción a la API privada](https://platzi.com/clases/2185-laravel-api/34828-introduccion-a-la-api-privada/)
------------
#### ¿Cómo se retorna una respuesta en JSON?
		 return response()->json(array, status)
###### Razón: Se puede retornar un mensaje, junto al código de status HTTP, ante una petición hecha.
###### Vídeo: [Versión 1: colección](https://platzi.com/clases/2185-laravel-api/34823-version-1-coleccion/)
------------
#### ¿Cómo retornamos un token de autenticación?
		 $request->user()->createToken(string)->plainTextToken
###### Razón: Con el método createToken devuelve una instancia Laravel\Sanctum\NewAccessToken. Los tokens de la API se codifican utilizando el hash SHA-256 antes de ser almacenados en la base de datos. Y se puede acceder como texto plano mediante la propiedad plainTextToken.
###### Vídeo: [Acceso](https://platzi.com/clases/2185-laravel-api/34830-acceso/)
------------
#### ¿Qué trait usamos desde el modelo User?
		 HasApiTokens
###### Razón: Los traits permiten agrupar funcionalidades para utilizarlas en clases sin necesidad de utilizar herencia. Sanctum permite emitir tokens de API / tokens de acceso personal que pueden ser utilizados para autenticar las solicitudes de API a su aplicación. Al realizar solicitudes utilizando tokens de API, el token debe incluirse en la cabecera de autorización como un Bearer. Para comenzar a emitir tokens para los usuarios, el modelo de usuario debe utilizar el trait LaravelSanctum\HasApiTokens.
###### Vídeo: [Autenticación](https://platzi.com/clases/2185-laravel-api/34829-autenticacion/)
------------
#### ¿Cómo protegemos a nuestrar rutas?
		 Usando el midleware auth.
###### Razón: Los middleware proporcionan un mecanismo conveniente para filtrar solicitudes HTTP entrantes a tu aplicación. Por ejemplo, Laravel incluye un middleware que verifica si el usuario de tu aplicación está autenticado.
###### Vídeo: [Introducción a la API privada](https://platzi.com/clases/2185-laravel-api/34828-introduccion-a-la-api-privada/)
------------
#### ¿Podemos crear una clase para personalizar nuestros recursos?
		 Sí.
###### Razón: Para crear un resource se usa el comando el php artisan make:resource MyResource, y se pueden personalizar como uno desee.
###### Vídeo: [Versión 1: recurso](https://platzi.com/clases/2185-laravel-api/34822-version-1-recurso/)
------------
#### ¿Qué comando me muestra todas las rutas creadas?
		 php artisan route:list
###### Razón: El comando route:list muestra una lista de todas las rutas registradas en la aplicación. Este comando mostrará el dominio, el método, el URI, el nombre, la acción y el middleware de las rutas.
###### Vídeo: [Versión 1: planificación y configuración inicial](https://platzi.com/clases/2185-laravel-api/34821-version-1-planificacion-y-configuracion-inicial/)
------------
#### ¿Qué estatos HTTP indica un error en el servidor?
		 500
###### Razón: El código de respuesta 500 Error Interno del Servidor del Protocolo de Transferencia de Hipertexto (HTTP) indica que el servidor encontró una condición inesperada que le impide completar la petición.
###### Vídeo: [Términos](https://platzi.com/clases/2185-laravel-api/34820-terminos/)
------------
#### ¿Con qué número comienza la serie de redirección?
		 3xx
###### Razón: Los códigos 3xx, indican que es necesario tomar otras medidas para completar la solicitud.
###### Vídeo: [Términos](https://platzi.com/clases/2185-laravel-api/34820-terminos/)
