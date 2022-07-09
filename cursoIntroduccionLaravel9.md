# Curso de Introducción a Laravel 9
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Cómo podemos iniciar un proyecto?
		 php artisan serve
###### Razón: El comando php artisan serve, sirve para iniciar la aplicación en el servidor de desarollo PHP
###### Vídeo: [Artisan](https://platzi.com/clases/3039-laravel/49359-artisan/)
------------
#### ¿En qué carpeta creamos a nuestras clases?
		 app
###### Razón: En la carpeta app, tiene a su vez muchas carpetas adicionales para diversas cosas. Donde se encuentran carpetas para comandos, para comandos de consola, control de eventos, control de excepciones, proveedores, servicios, modelos y vistas.
###### Vídeo: [Estructura principal de Laravel](https://platzi.com/clases/3039-laravel/49358-estructura-principal-de-laravel/)
------------
#### ¿Qué es Artisan?
		 Interfaz de línea de comandos.
###### Razón: Artisan es el interfaz de línea de comandos incluido con Laravel. Artisan existe en la raíz de la aplicación, y proporciona muchos comandos útiles para asistir en el desarrollo de la construcción de la aplicación.
###### Vídeo: [Artisan](https://platzi.com/clases/3039-laravel/49359-artisan/)
------------
#### Método HTTP de consulta
		 GET
###### Razón: El método de petición GET, solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.
###### Vídeo: [Routes](https://platzi.com/clases/3039-laravel/49360-routes/)
------------
#### ¿Cuál es la extensión de mis vistas?
		 .blade.php
###### Razón: Blade es el motor de plantillas incluidos con Laravel, los archivos deben llebar la extensión  .blade.php
###### Vídeo: [Views](https://platzi.com/clases/3039-laravel/49361-views/)
------------
#### ¿Cómo podemos usar una plantilla desde alguna vista?
		 @extends('plantilla')
###### Razón: Cuando se define una vista se puede utilizar la directiva @extends(''), para que la vista herede la vista extendida. Las vistas que extienden un diseño Blade pueden inyectar contenido en las secciones del diseño utilizando las directivas @section.
###### Vídeo: [Templates](https://platzi.com/clases/3039-laravel/49362-templates/)
------------
#### ¿Cuál es el comando para crear un controlador?
		 php artisan make:controller
###### Razón: Para crear un controlador se usa el comando, php artisan make:controller ProductoController. Los controladores pueden agrupar la lógica de manejo de solicitudes relacionadas en una sola clase.
###### Vídeo: [Controllers](https://platzi.com/clases/3039-laravel/49363-controllers/)
------------
#### ¿Qué son las migraciones?
		 Archivos PHP que llevan el registro detallado de la base de datos.
###### Razón: Las migraciones son como un control de versiones para su base de datos, que permite al equipo definir y compartir la definición del esquema de la base de datos de la aplicación.
###### Vídeo: [Migraciones](https://platzi.com/clases/3039-laravel/49364-migrations/)
------------
#### ¿Qué es un módelo (Model)?
		 Es una clase que representa a una tabla y a partir de allí podemos interactuar con ella.
###### Razón: Cada tabla de la base de datos corresponde a un modelo, que es usada para interactuar con ella, un modelo puede ser creado con el comando: php artisan make:model MiModelo
###### Vídeo: [Models](https://platzi.com/clases/3039-laravel/49365-models/)
------------
#### ¿Qué es Eloquent?
		 Es el ORM que proporciona Laravel para manejar y administrar de manera sencilla a nuestras bases de datos.
###### Razón: Eloquent es el ORM (Object-Relational Mapper) que incluye Laravel para manejar de una forma fácil y sencilla los procesos correspondientes al manejo de bases de datos en un proyecto, gracias a las funciones que provee es posible realizar complejas consultas y peticiones de base de datos sin escribir una sola línea de código SQL.
###### Vídeo: [Eloquent](https://platzi.com/clases/3039-laravel/49366-eloquent/)
------------
#### ¿Qué método podemos usar para decir que un Post pertenece a un User?
		 belongsTo
###### Razón: El método belongsTo permite trabajar con relaciones donde un registro pertenece a otro registro. Este método acepta como primer argumento el nombre de la clase que se vinculará.
###### Vídeo: [Relationships](https://platzi.com/clases/3039-laravel/49367-relationships/)
------------
#### ¿Qué método usamos para decir que un User tiene muchos Posts?
		 hasMany
###### Razón: Una relación uno a muchos es utilizada cuando un modelo puede tener muchos otros modelos relacionados. Por ejemplo, una profesión puede tener un número indeterminado de usuarios asociados a ésta.
###### Vídeo: [Relationships](https://platzi.com/clases/3039-laravel/49367-relationships/)
------------
#### ¿Con qué comando instalamos a Breeze?
		 composer require laravel/breeze --dev
###### Razón: Laravel Breeze es una implementación mínima y sencilla de todas las características de autenticación de Laravel, incluyendo el inicio de sesión, el registro, el restablecimiento de la contraseña, la verificación por correo electrónico y la confirmación de la contraseña. La capa de vista por defecto de Laravel Breeze se compone de simples plantillas Blade estilizadas con Tailwind CSS.
###### Vídeo: [Inicio de sesión](https://platzi.com/clases/3039-laravel/49369-inicio-de-sesion/)
------------
#### ¿Cómo instalamos al componente para hacer debug en Laravel?
		 composer require barryvdh/laravel-debugbar --dev
###### Razón: Debugbar es un paquete para integrar la barra de depuración de PHP con Laravel. Incluye un ServiceProvider para registrar la barra de depuración y adjuntarla a la salida.
###### Vídeo: [Optimización](https://platzi.com/clases/3039-laravel/49386-optimizacion/)
------------
#### ¿Qué es un ORM?
		 Es una herramienta que nos ayuda a trabajar con los datos como si estos fueran objetos.
###### Razón: Un ORM (Object-Relational Mapper) es un modelo de programación que permite mapear las estructuras de una base de datos relacional (SQL Server, Oracle, MySQL, etc.), en adelante RDBMS (Relational Database Management System), sobre una estructura lógica de entidades con el objeto de simplificar y acelerar el desarrollo de las aplicaciones.
###### Vídeo: [Eloquent](https://platzi.com/clases/3039-laravel/49366-eloquent/)
------------
#### ¿Cómo podemos crear un slug?
		 Con la clase Str y el método slug().
###### Razón: Los slugs son formas «amigables» de representar el texto de un enlace de tal manera que no se muestren caracteres extraños o variables confusas y que pueda ser leído y entendido por una persona.Haciendo uso del método Str::slug(), esta clase permite trabajar con cadenas de texto y específicamente el método slug convierte un texto dado en una cadena en minúsculas, sin acentos y separado por guiones.
###### Vídeo: [Función de guardar](https://platzi.com/clases/3039-laravel/49376-funcion-de-guardar/)