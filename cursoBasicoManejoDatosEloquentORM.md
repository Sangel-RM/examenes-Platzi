# Curso Básico de Manejo de Datos en Laravel con Eloquent ORM
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué significa ORM?
		 Object Relational Mapping
###### Razón: Un ORM (Object Relational Mappings) es un modelo de programación que permite mapear las estructuras de una base de datos relacional (SQL Server, Oracle, MySQL, etc.), en adelante RDBMS (Relational Database Management System), sobre una estructura lógica de entidades con el objeto de simplificar y acelerar el desarrollo de nuestras aplicaciones.
###### Vídeo: [¿Qué es un ORM y para qué sirve Eloquent?](https://platzi.com/clases/1920-eloquent-laravel/28515-que-es-un-orm-y-para-que-sirve-eloquent/)
------------
#### ¿Para qué sirve Eloquent?
		 Mapear los objetos de la base de datos y facilitar el acceso a sus objetos.
###### Razón: Eloquent es el ORM que incluye Laravel para manejar de una forma fácil y sencilla los procesos correspondientes al manejo de bases de datos en un proyecto, gracias a las funciones que provee es posible realizar complejas consultas y peticiones de base de datos sin escribir una sola línea de código SQL.
###### Vídeo: [¿Qué es un ORM y para qué sirve Eloquent?](https://platzi.com/clases/1920-eloquent-laravel/28515-que-es-un-orm-y-para-que-sirve-eloquent/)
------------
#### ¿Cómo funciona el flujo de una petición usando un modelo?
		 Recibir información - Controlador - Modelo - Acción
###### Razón: El navagador recibe la información por ejemplo /getAllProjects, entonces este va al controlador quien será el encargado de manejar las operaciones que se necesiten, entonces en el controlador se hace al llamado al modelo que representará a la tabla que se contultará y finalmente la acción, que es la respuesta al usuario.
###### Vídeo: [Estructura de modelos, rutas y controladores para consultar datos](https://platzi.com/clases/1920-eloquent-laravel/28517-estructura-de-modelos-rutas-y-controladores-para-c/)
------------
#### ¿Qué acciones se ejecutan en un CRUD?
		 Agregar - Listar - Modificar - Eliminar
###### Razón: CRUD es el acrónimo de Cread, Read, Update and Delete. Se usa para referirse a las funciones básicas en bases de datos o la capa de persistencia en un software.
###### Vídeo: [Cómo insertar nuevos registros](https://platzi.com/clases/1920-eloquent-laravel/28518-como-insertar-nuevos-registros/)
------------
#### ¿Qué archivo debe configurarse para la conexión a la base de datos?
		 .env
###### Razón: El archivo .env contiene las variables de entorno.
###### Vídeo: [Crea un proyecto Laravel y configura una base de datos MySQL](https://platzi.com/clases/1920-eloquent-laravel/29204-crea-un-proyecto-laravel-y-configura-una-base-de-d/)
------------
#### ¿Qué es Tinker?
		 Es una consola única de Laravel para realizar pruebas de funcionamiento independientes.
###### Razón: Tinker es un REPL de Laravel. REPL por las siglas en inglés de «Read-Eval-Print-Loop», también conocido como alto nivel interactivo o consola de lenguaje, es un entorno de programación interactiva basado en un proceso cíclico donde se lee un fragmento de código ingresado por el usuario, se evalúa y se devuelve un resultado al usuario; las partes de programa escrito en un entorno pueden compartir un estado global mientras el programa esté activo.
###### Vídeo: [Crea un proyecto Laravel y configura una base de datos MySQL](https://platzi.com/clases/1920-eloquent-laravel/29204-crea-un-proyecto-laravel-y-configura-una-base-de-d/)
------------
#### ¿Tinker es una consola única de Laravel?
		 Verdadero
###### Razón: Tinker es un REPL de Laravel. REPL por las siglas en inglés de «Read-Eval-Print-Loop», también conocido como alto nivel interactivo o consola de lenguaje, es un entorno de programación interactiva basado en un proceso cíclico donde se lee un fragmento de código ingresado por el usuario, se evalúa y se devuelve un resultado al usuario; las partes de programa escrito en un entorno pueden compartir un estado global mientras el programa esté activo.
###### Vídeo: [Crea un proyecto Laravel y configura una base de datos MySQL](https://platzi.com/clases/1920-eloquent-laravel/29204-crea-un-proyecto-laravel-y-configura-una-base-de-d/)
------------
#### ¿Qué comando se utiliza para crear un modelo?
		 php artisan make:model NombreDelModelo
###### Razón: Para crear un modelo en el proyecto, se debe ejecutar el comando php artisan make:model NombreDelModelo desde el cmd, ubicandose en el proyecto en el que se trabaja.
###### Vídeo: [Generar el modelo para la tabla de proyectos](https://platzi.com/clases/1920-eloquent-laravel/28516-generar-el-modelo-para-la-tabla-de-proyectos/)
------------
#### Un modelo es un archivo que extiende de:
		 Illuminate\Database\Eloquent\Model
###### Razón: Illuminate es el motor de base de datos de Laravel. Viene en paquete con el ORM Eloquent en Laravel.
###### Vídeo: [Generar el modelo para la tabla de proyectos](https://platzi.com/clases/1920-eloquent-laravel/28516-generar-el-modelo-para-la-tabla-de-proyectos/)
------------
#### Para configurar una conexión a base de datos desde un modelo se utiliza:
		 protected $connection = 'connection-name';
###### Razón: Si por alguna razón se desea que un modelo se conecte a otra base de datos puede indicarse a cuál apuntar: protected $connection = 'connection-name';.
###### Vídeo: [Convenciones para los modelos](https://platzi.com/clases/1920-eloquent-laravel/29207-convenciones-para-los-modelos/)
------------
#### ¿De qué forma se pueden asignar valores por defecto desde un modelo?
		 Con un array de atributos indicando llave y valor.
###### Razón: Para asignar valores por defecto de algún atributo del modelo, se puede hacer lo siguiente 
###### protected $attributes = [
######    'name' => 'hola',
###### ];
###### Vídeo: [Atributos por defecto en un modelo](https://platzi.com/clases/1920-eloquent-laravel/29208-atributos-por-defecto-en-un-modelo/)
------------
#### La sentencia Project::all(); nos devolverá:
		 Todos los proyectos de la tabla projects.
###### Razón: El método all(), retornará todos los registros de la tabla.
###### Vídeo: [Estructura de modelos, rutas y controladores para consultar datos](https://platzi.com/clases/1920-eloquent-laravel/28517-estructura-de-modelos-rutas-y-controladores-para-c/)
------------
#### ¿Para qué nos sirve el comando chunk?
		 Para traer de manera optimizada grandes volúmenes de datos.
###### Razón: Un chunk (del inglés «trozo»o «pedazo») es un fragmento de información.
###### Vídeo: [Chunk: fragmentando múltiples registros](https://platzi.com/clases/1920-eloquent-laravel/29210-chunk-fragmentando-multiples-registros/)
------------
#### ¿Qué comando se utiliza para crear un nuevo registro?
		 save()
###### Razón: El método save() sirve para guardar/actualizar un registro con la información que se proporcione.
###### Vídeo: [Cómo insertar nuevos registros](https://platzi.com/clases/1920-eloquent-laravel/28518-como-insertar-nuevos-registros/)
------------
#### ¿Qué comando se utiliza para actualizar un registro ya existente?
		 Agregar el nuevo valor al campo y save().
###### Razón: El método save() sirve para guardar/actualizar un registro con la información que se proporcione.
###### Vídeo: [Actualizando registros de la base de datos](https://platzi.com/clases/1920-eloquent-laravel/29212-actualizando-registros-de-la-base-de-datos/)
------------
#### ¿Qué es más recomendable para "eliminar" valores visualmente?
		 Desactivar el registro a través del campo is_active.
###### Razón: La eliminación de datos definitivos solo de debe realizar cuando sea realmente necesario y se tenga la seguridad que no afectará en el futuro. Lo recomendable es esconder el registro mediante algún campo que indique si el registro está activo o no.
###### Vídeo: [Consideraciones y buenas prácticas para eliminar datos](https://platzi.com/clases/1920-eloquent-laravel/29213-consideraciones-y-buenas-practicas-para-eliminar-d/)
------------
#### ¿Cómo se llama la herramienta para construir sentencias sin usar SQL?
		 Query Builder
###### Razón: Query Builder, proporciona una interfaz fluida y conveniente para la creación y ejecución de consultas de bases de datos.
###### Vídeo: [Query Builder](https://platzi.com/clases/1920-eloquent-laravel/29215-query-builder/)