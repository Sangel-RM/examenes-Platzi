# Curso de Integración de PHP con HTML
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Cómo funciona el Server Side Rendering?
		 Mi servidor procesa toda la página por cada solicitud y manda las plantillas HTML al navegador ya procesadas.
###### Razón: La renderización del lado del servidor (SSR) es una técnica popular para renderizar una aplicación de una sola página (SPA) del lado del cliente en el servidor y enviar una página completamente renderizada al cliente. Esto permite que los componentes dinámicos se presenten como marcado HTML estático.
###### Vídeo: [¿Cómo se renderiza una página web en mi computadora?](https://platzi.com/clases/2947-php-html/48190-como-se-renderiza-una-pagina-web-en-mi-computadora/)
------------
#### ¿Cómo funciona el Client Side Rendering?
		 Mi servidor manda una página en blanco y archivos de JavaScript al cliente para que sea el cliente quien se encargue de renderizar la página.
###### Razón: Client Side Rendering es una estrategia en la que se genera el HTML de las páginas completamente en el lado cliente apoyándose en JavaScript. Toda la responsabilidad sobre la obtención de datos, la creación de templates o el enrutamiento se llevan al lado cliente en lugar del servidor.
###### Vídeo: [¿Cómo se renderiza una página web en mi computadora?](https://platzi.com/clases/2947-php-html/48190-como-se-renderiza-una-pagina-web-en-mi-computadora/)
------------
#### ¿Cómo funciona el Static Site Generation?
		 La computadora del desarrollador se encarga de prerenderizar toda la página y únicamente sube las plantillas al servidor para que este únicamente se encargue de mandar dichas plantillas al cliente.
###### Razón: Todo el HTML es construido en tiempo de build, es decir, desde que se desarrolla, lo que hace que no sea necesario un servidor. Es común verlo con frameworks como Next.js.
###### Vídeo: [¿Cómo se renderiza una página web en mi computadora?](https://platzi.com/clases/2947-php-html/48190-como-se-renderiza-una-pagina-web-en-mi-computadora/)
------------
#### ¿Es posible ejecutar archivos PHP con HTML sin necesidad de un servidor local?
		 Falso, al tener código HTML necesitamos de un servidor que sea capaz de preprocesar el código PHP y HTML.
###### Razón: Un servidor es una herramienta de desarrollo que permite probar el desarrollo web basado en PHP en PC. Y es que PHP es un lenguaje de programación de código de lado del servidor que permite crear páginas web o aplicaciones dinámicas. Es independiente de plataforma y soporta varios sistemas de bases de datos.
###### Vídeo: [Levantando un servidor local](https://platzi.com/clases/2947-php-html/49214-levantando-un-servidor-local/)
------------
#### ¿Es importante usar etiquetas de cierre de PHP cuando empezamos a trabajar con HTML?
		 Verdadero, ya que de esta forma PHP identifica cuándo trabajamos con PHP y cuándo trabajamos con HTML.
###### Razón: Sí es necesario cerrar la etiqueta PHP cuando se usa con HTML o de lo contrario marcaría error.
###### Vídeo: [PHP como preprocesador de HTML](https://platzi.com/clases/2947-php-html/48192-php-como-preprocesador-de-html/)
------------
#### ¿Con qué extensión debemos guardar nuestros archivos de PHP cuando empezamos a incluír HTML dentro?
		 php
###### Razón: Es necesario usar la extensión PHP para realizar el código PHP y HTML en el mismo archivo.
###### Vídeo: [PHP como preprocesador de HTML](https://platzi.com/clases/2947-php-html/48192-php-como-preprocesador-de-html/)
------------
#### ¿Cuál de las siguientes sintaxis es la más recomendada para imprimir texto con PHP dentro de HTML?
		 <?= "Hola, Mundo." ?>
###### Razón: La sintaxis anterior es una versión corta y mejor de < ? php echo="Hola Mundo" ?>
###### Vídeo: [Imprime texto y etiquetas HTML](https://platzi.com/clases/2947-php-html/48193-imprime-texto-y-etiquetas-html/)
------------
#### ¿Cuál de las siguientes sintaxis es la más recomendada para usar condicionales con PHP dentro de HTML?
		 <? php if(condicion){ ?>
		 <!--CODIGO HTML>-->
		 <?php } ?> 
###### Razón: Es mala práctica imprimir código de HTML, desde echo. La sintaxis anterior es la mejor forma.
###### Vídeo: [Condicionales](https://platzi.com/clases/2947-php-html/48194-condicionales/)
------------
#### ¿Cuál de las siguientes sintaxis es la más recomendada para usar ciclos con PHP dentro de HTML?
		<? php for( condicion ): ?>
		<!-- Código HTML -->
		<?php endfor; ?>
###### Razón: La sintaxis anterior es la mejor forma de usar ciclos for, foreach, usando PHP en HTML sin necesidad de usar echo.
###### Vídeo: [Ciclos](https://platzi.com/clases/2947-php-html/48195-ciclos/)
------------
#### ¿Es posible pasar variables de PHP hacia JavaScript?
		 Verdadero, PHP, al ser un preprocesador, es capaz de hardcodear código JavaScript en el HTML final que se manda al navegador. Sin embargo, solo está imprimiendo los valores, como código JavaScript directamente.
###### Razón: PHP es capaz preprocesar código JavaScript, permitiéndo pasar variables de PHP a JavaScript.
###### Vídeo: [¿Es posible pasar variables de PHP hacia JavaScript?](https://platzi.com/clases/2947-php-html/48196-como-pasar-variables-de-php-a-javascript/)
------------
#### ¿Es posible pasar variables de JavaScript a PHP?
		 Verdadero, esto es conocido como una solicitud asíncrona al servidor. Hay que plantearse bien por qué se desea hacer esto, ya que PHP se ejecuta mucho antes de que JavaScript entre en acción.
###### Razón: Pasar variables desde JavaScript a PHP es más complejo, ya que cuando Javascript se ejecuta en el cliente, PHP se ejecutó mucho tiempo antes en el servidor. Una petición asíncrona es una operación que, mientras esté siendo procesada, deja libre al navegador para que pueda hacer otras operaciones. Las peticiones asíncronas son las operaciones que tengan que ver con realizadas llamadas a servidores. Las peticiones asíncronas en el navegador se realizan con la función XMLHttpRequest.
###### Vídeo: [¿Es posible pasar variables de PHP hacia JavaScript?](https://platzi.com/clases/2947-php-html/48196-como-pasar-variables-de-php-a-javascript/)
------------
#### ¿Cuál de las siguientes es una buena práctica para evitar código espagueti?
		  Usar las etiquetas de PHP diseñadas para imprimr en HTML.
###### Razón: El código espagueti es aquel que tiene una estructura de control de flujo compleja e incomprensible. Se debe evitar lo más posible el código ya que evita que a largo plazo el código no sea mantenible. Por consiguiente se debe usar las etiquetas html par imprimir html, como los ciclos, condiciones y no imprimr todo desde un echo.
###### Vídeo: [Evita el código espagueti](¿Cuál de las siguientes es una buena práctica para evitar código espagueti?)
------------
#### ¿Cuáles son las 3 variables superglobales que nos da PHP para obtener una solicitud?
		 `$_GET`, `$_POST` y `$_REQUEST`
###### Razón: Las variables superglobale están disponibles en todos los ámbitos a lo largo del script. No es necesario emplear global $variable; para acceder a ellas dentro de las funciones o métodos. Las variables superglobals para obtener una soliciutd son: $_GET,$_POST,$_REQUEST. $_GET: Es un array asociativo de variables pasado al script actual vía parámetros URL (también conocida como cadena de consulta). Tenga en cuenta que el array no solo se rellena para las solicitudes GET, sino para todas las solicitudes con una cadena de consulta. $POST: Un array asociativo de variables pasadas al script actual a través del método POST de HTTP cuando se emplea application/x-www-form-urlencoded o multipart/form-data como Content-Type de HTTP en la petición. $_REQUEST: Un array asociativo que por defecto contiene el contenido de $_GET, $_POST y $_COOKIE.
###### Vídeo: [Cómo obtener una solicitud al servidor con PHP](https://platzi.com/clases/2947-php-html/48199-como-obtener-una-solicitud-al-servidor-con-php/)
------------
#### ¿Cuál de las siguientes es una característica del método `$_GET`?
		 Cualquier parámetro que se mande al servidor será enviado a través de la URL.
###### Razón: El método GET es adecuado para la personalización de páginas web: el usuario puede guardar búsquedas, configuraciones de filtros y ordenaciones de listas junto al URL como marcadores, de manera que en su próxima visita la página web se mostrará según sus preferencias.
###### Vídeo: [Envío de un formulario a través de GET](https://platzi.com/clases/2947-php-html/48200-envio-de-un-formulario-a-traves-de-get/)
------------
#### ¿Cuál de las siguientes es una característica del método `$_POST`?
		 Cualquier parámetro que se mande al servidor será enviado "por detrás" de forma que no sea visible a simple vista para los usuarios.
###### Razón: El método POST es aconsejable cuando el usuario debe enviar datos o archivos al servidor, como, por ejemplo, cuando se rellenan formularios o se suben fotos.
###### Vídeo: [Envío de un formulario a través de POST](https://platzi.com/clases/2947-php-html/48286-envio-de-un-formulario-a-traves-de-post/)
------------
#### ¿Los formularios nativos de HTML son capaces de enviar solicitudes al servidor?
		 Verdadero, a través del atributo `action` y un botón de tipo `submit` podemos mandar una solicitud al servidor con los datos del formulario.
###### Razón: El atributo action define la ubicación (URL) donde se envían los datos que el formulario ha recopilado cuando se validan.
###### Vídeo: [Haciendo la lógica de recepción del formulario](https://platzi.com/clases/2947-php-html/48205-haciendo-la-logica-de-recepcion-del-formulario/)
------------
#### ¿Qué tipo de encriptación debemos usar en nuestro formulario si queremos subir imágenes a nuestro servidor?
		 multipart/form-data
###### Razón: El atributo enctype del elemento FORM especifica el tipo de codificación utilizado cuando los datos del formulario se envían al servidor. El valor predeterminado es "application / x-www-form-urlencoded". Sin embargo, este método de codificación es ineficiente cuando se envían grandes cantidades de texto, texto que contiene caracteres no ASCII o datos binarios al servidor. Un tipo de contenido utilizado frecuentemente para enviar archivos a través de un formulario HTML es multipart/form-data. Al cargar archivos, el tipo de codificación utilizado debe ser "multipart / form-data", que puede enviar datos de texto y también admite la carga de datos binarios.
###### Vídeo: [Envío de imágenes](https://platzi.com/clases/2947-php-html/48201-envio-de-imagenes/)
------------
#### Cuando subimos una imagen al servidor ¿estás se guardan automáticamente?
		 Flaso. Estas imágenes se guardan en una carpeta temporal que es limpiada cada cierto tiempo. Depende de nosotros guardarlas en alguna carpeta para evitar que se borre.
###### Razón: Las imágenes enviadas son guardadas en una carpeta temporal que es limpiada cada cierto tiempo, si se desea guardar las imágenes estan debe ser movidas.
###### Vídeo: [Guardando imágenes en el servidor](https://platzi.com/clases/2947-php-html/48287-guardando-imagenes-en-el-servidor/)
------------
#### ¿Desde cuál variable superglobal podemos tener acceso a la ruta temporal de mi archivo subido?
		 `$_FILES`
###### Razón: El array global $_FILES contendrá toda la información de los los ficheros subidos.
###### Vídeo: [Envío de imágenes](https://platzi.com/clases/2947-php-html/48201-envio-de-imagenes/)
------------
#### ¿Podemos enviar arreglos desde un formulario HTML al servidor?
		 Verdadero. Basta con agregar corchetes `[]` en el atributo `name` para que en el servidor se interprete como un arreglo.
###### Razón: Si se desea enviar un arreglo basta con agregar corchetes el atributo name. Ejemplo: name="persona[]"
###### Vídeo: [Otros tipos de inputs](https://platzi.com/clases/2947-php-html/48288-tipos-de-inputs/)
------------
#### ¿Cuáles funciones me permiten validar si un campo ha sido enviado y si dicho campo está vacío?
		 `isset()` y `empty()`
###### Razón: isset  Determina si una variable está definida y no es null, empty: Se usa para determinar si la variable existe y si su valor no se evalúa como false 
###### Vídeo: [Valida si un formulario ha sido enviado](https://platzi.com/clases/2947-php-html/48202-valida-si-un-formulario-ha-sido-enviado/)
------------
#### ¿Por qué es importante sanitizar los datos que recibo de mis usuarios?
		 Porque puedo tener usuarios malintencionados que quieran inyectar código en mi página web.
###### Razón: Sanitizar los datos sirve para evitar inyecciones de código en el sitio web, en PHP estan disponibles filtros de saneamiento: [Filtros de saneamiento](https://www.php.net/manual/es/filter.filters.sanitize.php)
###### Vídeo: [Sanitizando datos de mi formulario](https://platzi.com/clases/2947-php-html/48203-sanitizando-datos-de-mi-formulario/)
------------
#### ¿Cuál de las siguientes funciones podemos utilizar para validar datos que recibo de mis usuarios?
		 `filter_var()`
###### Razón: Filtra una variable con el filtro que se indique. La función filter_var() filtra una variable con el filtro especificado. Esta función se utiliza para validar y sanitizar los datos.
###### Vídeo: [Validando datos](https://platzi.com/clases/2947-php-html/48290-validando-datos/)
------------
#### ¿Podemos usar la función `mail()` de PHP?
		 Verdadero, pero requiere de una configuración muy avanzada en nuestra computadora para poder usarla, por eso es mejor usar alternativas como PHP Mailer.
###### Razón: La función mail() invoca un programa Sendmail, generalmente configurado por el administrador del sistema, que permite enviar correos electrónicos. Para usar esta función, se debe asegurar que el proveedor de alojamiento permita administrar manualmente la opción del servicio Sendmail.
###### Vídeo: [Integrando PHPMailer](https://platzi.com/clases/2947-php-html/48206-integrando-phpmailer/)
------------
#### ¿Qué es Composer?
		 Es un manejador de paquetes similar a NPM de JavaScript que nos sirve para utilizar librerías de terceros en PHP.
###### Razón: Composer es un sistema de gestión de paquetes para programar en PHP el cual provee los formatos estándar necesarios para manejar dependencias y librerías de PHP. 
###### Vídeo: [Integrando PHPMailer](https://platzi.com/clases/2947-php-html/48206-integrando-phpmailer/)
------------
#### ¿Qué tipo de rendering utiliza PHP?
		 Server Side Rendering (SSR)
###### Razón: Es el tipo de renderizado más común en la web. Este renderizado se basa en que el servidor procesa todo el código y manda  todo el código ya procesado al navegador.
###### Vídeo: [¿Cómo se renderiza una página web en mi computadora?](https://platzi.com/clases/2947-php-html/48190-como-se-renderiza-una-pagina-web-en-mi-computadora/)
------------
#### Si necesito realizar cálculos con PHP para después imprimir en HTML... ¿Qué debería hacer?
		 Separar la lógica de la vista, hacer todos los cálculos al inicio de nuestro documento para después únicamente imprimir los resultados en nuestro HTML.
###### Razón: Es mala práctica combiar la vista y la lógica se recomienda separarlos para tener un código legible.
###### Vídeo: [Refactorizando código espagueti](https://platzi.com/clases/2947-php-html/48198-refactorizando-codigo-espagueti/)
------------
#### ¿Es posible ver los datos enviados por medio de una solicitud POST?
		 Verdadero. Usando la consola de desarrolladores podemos inspeccionar cada solicitud que es enviada al servidor y ver que datos se están mandando.
###### Razón: A través de la consola incluidas en los navegadores es posible ver los datos que son enviados, especificamente en la sección RED.
###### Vídeo: [Envío de un formulario a través de POST](https://platzi.com/clases/2947-php-html/48286-envio-de-un-formulario-a-traves-de-post/)
------------
#### ¿Cuál es el archivo que mi servidor buscará por defecto para cargar incluso si no se especifica en la URL?
		 index.php o index.html
###### Razón: Index. html es la página por defecto dentro de los directorios de los servidores de cualquier sitio web que se carga siempre que se solicita un dominio y no se especifica el nombre de un archivo específico. En este caso el propio servidor web es el que se encarga de buscar el archivo index.
###### Vídeo: [Creando el maquetado](https://platzi.com/clases/2947-php-html/48204-creando-el-maquetado/)
------------
#### ¿Podemos mandar una solicitud hacia la misma página desde la que se manda?
		 Verdadero. Simplemente en el action de mi formulario apuntó hacia la misma página y con PHP puedo validar y obtener dicha solicitud.
###### Razón: En el action va includi un URI que indica la ubicación del programa responsable de la manipulación de los datos enviados por el formulario. Si el script se encuentra en el mismo archivo se puede usar ./ o < ?php echo $_SERVER['PHP_SELF']; ?> en el action, para apuntar al mismo archivo.
###### Vídeo: [Haciendo la lógica de recepción del formulario](https://platzi.com/clases/2947-php-html/48205-haciendo-la-logica-de-recepcion-del-formulario/)
------------