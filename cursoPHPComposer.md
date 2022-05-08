# Curso de PHP con Composer
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### Todo sistema se basa en:
		 Petición, procesamiento y respuesta
###### Razón: El mundo del desarrollo web, siempre requerira una petición, procesamiento y respuesta. En la petición el usuario realiza una acción sobre una página web, lo cual se lanza una petición y es enviada al servidor. El procesamiento, la petición es enviada para ser procesada por el servidor. Y respuesta, el servidor prepara la respuesta y es enviada de vuelta al usuario.
###### Vídeo: [Qué aprenderás sobre PHP con Composer](https://platzi.com/clases/2024-php-composer/32051-presentacion-del-curso/)
------------
#### ¿En qué equipo desarrollamos el código?
		 En nuestro equipo convertido en cliente / servidor
###### Razón: El mundo del desarrollo web funciona en una arquitectura cliente-servidor, en donde un cliente envía una petición hacía un servidor, en ese servidor se encuentra instalado PHP y a su vez una base de datos.
###### Vídeo: [El mundo del desarrollo web](https://platzi.com/clases/2024-php-composer/32054-el-mundo-del-desarrollo-web/)
------------
#### ¿Qué es un programador?
		 Es quien resuelve problemas usando un lenguaje de programación
###### Razón: Un programador es aquella persona que elabora programas de computadora, ​ es decir escribe, depura y mantiene el código fuente de un programa informático, que ejecuta el hardware de una computadora, para realizar una tarea determinada.
###### Vídeo: [Ser programador](https://platzi.com/clases/2024-php-composer/32053-ser-programador/)
------------
#### ¿Cuáles son los elementos de un sistema cliente / servidor?
		 Un servidor con el código y un sistema de base de datos. Un cliente que se conecta al servidor (navegador web).
###### Razón: Las peticiones que envia el cliente (navegador web), van hacia el servidor que es donde está alojado el proyecto.
###### Vídeo: [El mundo del desarollo web](https://platzi.com/clases/2024-php-composer/32054-el-mundo-del-desarrollo-web/)
------------
#### ¿Qué es sintaxis?
		 La forma correcta y adecuada de escribir para que una computadora entienda
###### Razón: 
###### Vídeo: [Sintaxis Básico de PHP: Asignación y arimética](https://platzi.com/clases/2024-php-composer/32528-sintaxis-basica-de-php-asignacion-y-aritmetica/)
------------
#### ¿Qué es la asignación por referencia?
		 Es apuntar sin hacer copia, significa observar
###### Razón: Asignación por referencia significa que ambas variables terminan apuntando a los mismos datos y nada es copiado en ninguna parte.
###### Vídeo: [Sintaxis básica de PHP: asignación y aritmética](https://platzi.com/clases/2024-php-composer/32528-sintaxis-basica-de-php-asignacion-y-aritmetica/)
------------
#### ¿Qué es variables variables?
		 Es lo que nos permite definir variables de forma dinámica
###### Razón:  Las variables variables son nombres de variables que se pueden definir y usar dinámicamente. 
###### Vídeo: [Sintaxis básica de PHP: comparación y variables](https://platzi.com/clases/2024-php-composer/32490-sintaxis-basica-de-php-comparacion-y-variables/)
------------
#### ¿Qué son los bloques de códigos en PHP?
		 Es lo que nos permite alterar el flujo de nuestro código o proyecto en PHP
###### Razón: Estos bloques de código tambien son estructuras de control, son sentencias que permiten controlar cómo el código, basándose en ciertos factores. Por ejemplo, si se desea realizar una acción sólo si cierta variable está definida.
###### Vídeo: [Bloques de códigos sencillos en PHP](https://platzi.com/clases/2024-php-composer/32057-bloques-de-codigos-sencillos-en-php/)
------------
#### ¿Qué es Composer?
		 Es el sistema empleado para mantener un estándar profesional en nuestros proyectos web en PHP
###### Razón: Composer es un sistema de gestión de paquetes para programar en PHP el cual provee los formatos estándar necesarios para manejar dependencias y librerías de PHP. 
###### Vídeo: [Composer](https://platzi.com/clases/2024-php-composer/32058-composer/)
------------
#### ¿Qué es la gestión de paquetes?
		 Es la principal virtud de Composer, este descarga, instala y se asegura directamente todas las dependencias
###### Razón: Un sistema de gestión de paquetes, también conocido como gestor de paquetes, es una colección de herramientas que sirven para automatizar el proceso de instalación, actualización, configuración y eliminación de paquetes de software. Para gestionar los paquetes en PHP es usado composer y para  buscar paquetes dispnibles [Packagist](https://packagist.org/).
###### Vídeo: [Gestión de paquetes PHP](https://platzi.com/clases/2024-php-composer/32059-gestion-de-paquetes-php/)
------------
#### Dentro de un paquete, ¿Qué significa italomoralesf/slug?
		 Hace referencia al nombre de un paquete, indica el nombre del proveedor y luego el nombre del paquete directamente
###### Razón: En [Packagist](https://packagist.org/) la forma en que se bajan las dependencias tiene el formato que primero indica el proveedor y ahí el nombre del paquete. nesbot/carbon. El proveedor es nesbot y el paquete que se requiere es carbon.
###### Vídeo: [Gestión de paquetes PHP](https://platzi.com/clases/2024-php-composer/32059-gestion-de-paquetes-php/)
------------
#### ¿Cómo logramos la carga automática de clases?
		 Usando el archivo autoload.php, ejemplo require_once 'vendor/autoload.php';
###### Razón:  autoload.php es el archivo que contiene todas las clases y archivos precargados de tal forma que es posible acceder a cualquiera de sus clases/funciones usando sus namespaces. El autoload permite en PHP mantener un código más limpio y organizado mediante la carga automática de clases.
###### Vídeo: [Autoload](https://platzi.com/clases/2024-php-composer/32062-autoload/)
------------
#### ¿Qué es JSON?
		 Es un estándar usado para la transferencia de datos, siendo este muy legible y ligero
###### Razón: JSON es un formato de texto sencillo para el intercambio de datos. Se trata de un subconjunto de la notación literal de objetos de JavaScript, aunque, debido a su amplia adopción como alternativa a XML, se considera un formato independiente del lenguaje.
###### Vídeo: [Introducción a JSON](https://platzi.com/clases/2024-php-composer/32061-introduccion-a-json/)
------------
#### ¿Para qué se usa la llave autoload de composer?
		 Para la configuración de carga automática propia de archivos y clases
###### Razón:  autoload.php es el archivo que contiene todas las clases y archivos precargados de tal forma que es posible acceder a cualquiera de sus clases/funciones usando sus namespaces. El autoload permite en PHP mantener un código más limpio y organizado mediante la carga automática de clases.
###### Vídeo: [Autoload](https://platzi.com/clases/2024-php-composer/32062-autoload/)
------------
#### ¿Qué comando usamos para crear un proyecto?
		 composer init
###### Razón: Al ejecutar este comando solicitará cierta información que servirá para crear el archivo composer.json del proyecto, es la información requerida es básica para el archivo, como el nombre del paquete, descripción, autor(es), página del proyecto y las dependencias.
###### Vídeo: [Como iniciar un proyecto](https://platzi.com/clases/2024-php-composer/32060-como-iniciar-un-proyecto/)
------------
#### ¿Cuál es la función del archivo composer.lock?
		 Registrar exactamente las versiones de paquetes instalados
###### Razón: Gracias al archivo composer.lock, cualquier persona que se descargue el proyecto tendrá exactamente las mismas versiones de las dependencias. Si no existe el archivo composer.lock, Composer determina las dependencias a partir del archivo composer.json y después crea el archivo composer.lock.
###### Vídeo: [composer.lock](https://platzi.com/clases/2024-php-composer/32064-composerlock/)
