# Curso de Introducción a Frameworks de PHP
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Por qué necesito un framework?
		 Principalmente para no reinventar la rueda y enfocarnos en la necesidad real.
###### Razón: Un framework es un esquema o marco de trabajo que ofrece una estructura base para elaborar un proyecto con objetivos específicos, una especie de plantilla que sirve como punto de partida para la organización y desarrollo de software.
###### Vídeo: [Ventajas de usar frameworks](https://platzi.com/clases/2033-php-frameworks/32789-ventajas-de-usar-frameworks/)
------------
#### ¿Qué ofrece Laravel?
		 Administración de plantillas, manejo de datos un sistema de rutas y seguridad.
###### Razón: La ventaja de usar Laravel como su marco es que proporciona seguridad de clase alta. El uso de Laravel hace que las aplicaciones web sean seguras, ya que no permite que ningún malware o amenaza de seguridad ingrese a las aplicaciones. Eso también significa que su código de desarrollo web está seguro y protegido.
###### Vídeo: [Los frameworks modernos](https://platzi.com/clases/2033-php-frameworks/32623-los-frameworks-modernos/)
------------
#### ¿Cuál es la función de Vendor?
		 Guardar los paquetes descargados que usamos en cada proyecto.
###### Razón: La carpeta vendor es el directorio donde Composer almacenará los paquetes y dependencias descargadas.
###### Vídeo: [Estructura de carpetas](https://platzi.com/clases/2033-php-frameworks/32614-estructura-de-carpetas/)
------------
#### ¿Quién maneja el acceso a nuestro sistema?
		 El archivo index.php
###### Razón: Front Controller es un patrón que ayuda a solucionar el problema de acceso único en la web. Este se utiliza para proporcionar un mecanismo centralizado para manejar solicitudes, todas las solicitudes son procesadas por un solo controlador.
###### Vídeo: [Front Controller](https://platzi.com/clases/2033-php-frameworks/32615-front-controller/)
------------
#### ¿Qué es Front Controller?
		 Es un patrón para centralizar las solicitudes de los usuarios.
###### Razón: Front Controller es un patrón que ayuda a solucionar el problema de acceso único en la web. Este se utiliza para proporcionar un mecanismo centralizado para manejar solicitudes, todas las solicitudes son procesadas por un solo controlador.
###### Vídeo: [Front Controller](https://platzi.com/clases/2033-php-frameworks/32615-front-controller/)
------------
#### ¿Qué es Request?
		 Significa solicitud, es lo que requerimos para procesar lo que los usuarios pidan.
###### Razón: Request se usa para entender que quiere el usuario y otorgar una respuesta. Es un objeto sobre el que se puede consultar información sobre el cliente que realiza la solicitud y datos que pueda estar enviando.
###### Vídeo: [Request](https://platzi.com/clases/2033-php-frameworks/32616-request/)
------------
#### ¿Qué es Response?
		 Significa respuesta, es una clase usada para programar la respuesta correcta.
###### Razón: El response se encarga de ofrecer una respuesta al controller.
###### Vídeo: [Response](https://platzi.com/clases/2033-php-frameworks/32618-response/)
------------
#### ¿Qué es un controlador?
		 Es el intermediario entre la petición y la respuesta.
###### Razón: Un controlador es la clase que se encarga de hacer todo el procesamiento del request del usuario, ahí es en donde en la mayoría de las veces se ejecuta la lógica, y por su puesto, se retorna el resultado.
###### Vídeo: [Controllers](https://platzi.com/clases/2033-php-frameworks/32619-controllers/)
------------
#### ¿Cuál es el papel de la vista?
		 Su papel es tener  dentro de sus elementos mínimos de PHP.
###### Razón: La vista, o interfaz de usuario, compone la información que se envía al cliente y los mecanismos interacción con éste.
###### Vídeo: [Views](https://platzi.com/clases/2033-php-frameworks/32620-views/)
------------
#### ¿Qué es un helper?
		 Es un ayudante con tareas específicas y repetitivas.
###### Razón: Un helper es una forma de agrupar funciones de uso común, destinadas a servir de ayuda a otros procesos. Un Helper se compone de funciones genéricas que se encargan de realizar acciones complementarias, aplicables a cualquier elemento del sistema.
###### Vídeo: [Helpers](https://platzi.com/clases/2033-php-frameworks/32621-helpers/)
------------
#### ¿Cuál es la función principal de la carpeta views?
		 Organizar nuestras vistas.
###### Razón: En la carpeta views, van las plantillas de archivos que servirá para la información que verá el usario final.
###### Vídeo: [Views](https://platzi.com/clases/2033-php-frameworks/32620-views/)
------------
#### Aquí vivirán nuestras vistas, archivos pequeños con lo mínimo posible para funcionar a nivel visual:
		 views
###### Razón: En la carpeta views, van las plantillas de archivos que servirá para la información que verá el usario final.
###### Vídeo: [Views](https://platzi.com/clases/2033-php-frameworks/32620-views/)
------------
#### Carpeta que contiene todos los paquetes descargados que usamos en nuestro sistema:
		 vendor
###### Razón: La carpeta vendor es el directorio donde Composer almacenará los paquetes y dependencias descargadas.
###### Vídeo: [Estructura de carpetas](https://platzi.com/clases/2033-php-frameworks/32614-estructura-de-carpetas/)
------------
#### Carpeta principal de todos nuestros archivos y carpetas públicas del sistema:
		 public
###### Razón: La carpeta public sirve como punto de acceso al sistema. 
###### Vídeo: [Estructura de carpetas](https://platzi.com/clases/2033-php-frameworks/32614-estructura-de-carpetas/)
------------
#### Archivo de configuración del proyecto:
		 composer.json
###### Razón: En este archivo se describen las dependencias del proyecto y también puede contener otro tipo de información como descripción del proyecto.
###### Vídeo: [Estructura de carpetas](https://platzi.com/clases/2033-php-frameworks/32614-estructura-de-carpetas/)
------------
#### Esta carpeta contendrá nuestras clases, controladores y programación principal:
		 app
###### Razón: En carpeta app, van distintas carpetas como Http, Controllers, para administras las solicitudes y respuestas.
###### Vídeo: [Estructura de carpetas](https://platzi.com/clases/2033-php-frameworks/32614-estructura-de-carpetas/)
------------
#### ¿Qué queremos decir con: "name": "italomoralesf/basic" en composer.json?
		 Proveedor y nombre del paquete.
###### Razón: Al ejecutar la instrucción composer init, solicita el proveedor y nombre el paquete
###### Vídeo: [Estructura de carpetas](https://platzi.com/clases/2033-php-frameworks/32614-estructura-de-carpetas/)
------------
#### ¿La siguiente configuración está correcta?
```
"psr-4": {
	"app/helpers.php"
}

```
		 No
###### Razón:  Es una especificación para la auto carga de clases desde la ruta de los archivos. Describe dónde se encuentran ubicados los archivos que serán autocargados. En ese espacio se registra el namespace a usar.
###### Vídeo:
------------
#### ¿Quién se encarga de segmentar nuestra ruta?
		 Request.php
###### Razón: Request se usa para entender que quiere el usuario y otorgar una respuesta.
###### Vídeo: [Request](https://platzi.com/clases/2033-php-frameworks/32616-request/)
------------
#### ¿Quién se encarga de configurar la respuesta para el usuario?
		 Response.php
###### Razón: Las responses son las "respuestas" que se devuelven ante cualquier solicitud que se realice al servidor. 
###### Vídeo: [Response](https://platzi.com/clases/2033-php-frameworks/32618-response/)
