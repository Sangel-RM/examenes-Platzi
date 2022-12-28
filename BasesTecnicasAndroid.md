# Curso de Bases Técnicas de Android
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### Si necesitas almacenar datos simples que se componen de clave valor de manera local. ¿Qué tipo de almacenamiento usarías?
		 Shared Preferences
###### Razón: SharedPreferences apunta a un archivo que contiene pares clave-valor y proporciona métodos sencillos para leerlos y escribirlos. El framework administra cada archivo de SharedPreferences , que puede ser privado o compartido.
###### Vídeo: [File y SharedPreferences](https://platzi.com/clases/1264-tecnico-android/10799-file-y-sharedpreferences/ "File y SharedPreferences")
------------
#### Si te piden desarrollar una app móvil de compras, ¿qué tipo de almacenamiento interno usarías para manejar el carrito de un usuario?
		 Base de datos
###### Razón: Las bases de datos sirven para trabajar con datos estructurados, complejos y relacionales. Se almacenan dentro del dispositivo, pero se puede almacenar externamente. Aunque, puede que la información se vea vulnerable. Por lo que, los datos se deben encriptar para proteger la información.
###### Vídeo: [Content Providers Bases de Datos y Network](https://platzi.com/clases/1264-tecnico-android/10800-content-providers-bases-de-datos-y-network/ "Content Providers Bases de Datos y Network")
------------
#### Si tuvieras una aplicación en la que tienes almacenadas preferencias de usuario y deseas que éstas persistan aún si la aplicación es desinstalada o vive en varios dispositivos al mismo tiempo, ¿cuál es el tipo de almacenamiento ideal?
		 Network
###### Razón: En cuanto a Network podemos usar un servidor, dara una persistencia mayor a los datos, sera una forma de backup. Como funciona el network, la aplicación móvil se conectara al servidor a traves de una URL que se conoce como un endpoint que accedera al webservice, envia la solicitud al servidor si quiere enviar datos y el servidor la almacena y le regresa una respuesta a la app movil
###### Vídeo: [Content Providers Bases de Datos y Network](https://platzi.com/clases/1264-tecnico-android/10800-content-providers-bases-de-datos-y-network/ "Content Providers Bases de Datos y Network")
------------
#### Tengo una aplicación en la que la parte superior: un Toolbar y la inferior: un Bottom Bar son elementos que siempre están fijos y donde el único contenido que es dinámico es la parte central, ¿qué componente de aplicación me conviene usar?
		 Fragments
###### Razón: Un fragment podría definirse como una porción de la interfaz de usuario que puede añadirse o eliminarse de la interfaz de forma independiente al resto de elementos de la actividad, y que por supuesto puede reutilizarse en otras actividades.
###### Vídeo: [Fragments](https://platzi.com/clases/1264-tecnico-android/10783-fragments8345/ "Fragments")
------------
#### Mi cliente me está pidiendo cambios sobre una “pantalla” de inicio de sesión, ¿cuál es el término correcto para este componente de aplicación con el cual debo dirigirme al programador para solicitar el cambio?
		 Activity de inicio de sesión
###### Razón: Las activities están formadas por dos partes: la lógica y la gráfica.
###### - La parte lógica es un archivo .java que es la clase que nos permite manipular, interactuar y escribir el código que queremos que esa pantalla realice.
###### - La parte gráfica es un archivo XML que tiene todos los componentes que vemos en la pantalla. Estos se declaran con etiquetas parecidas a las de HTML, es decir, que el diseño de una aplicación en Android es similar al de una pagina web.
###### Vídeo: [Activity](https://platzi.com/clases/1264-tecnico-android/10782-activity/ "Activity")
------------
#### Los usuarios que no tienen un Smart Phone Android podrían aprovechar el Sistema Operativo en otros dispositivos, ¿cuál de estos pertenecen a la gama oficial que maneja Google?
		 AndroidTV y AndroidAuto
###### Razón: En Android existen diferentes tipos de dispositivos que tienen este Sistema Operativo: Notebooks, Tablets, Smartphones, SmartWatch, TV, Autos.
###### Vídeo: [Tipos de dispositivos Android y Soporte](https://platzi.com/clases/1264-tecnico-android/10780-tipos-de-dispositivos-android-y-soporte/ "Tipos de dispositivos Android y Soporte")
------------
#### Tienes un cliente que desea crear una aplicación que reproduzca Podcast, las personas podrán escuchar el audio mientras hacen otras cosas en sus dispositivos, es decir la aplicación no necesita estar visible para que se reproduzca el audio, ¿con cuál de estos componentes resolverías el requerimiento?
		 Servicio
###### Razón: Los servicios son todas esas funciones que se ejecutan en segundo plano, aún cuando el teléfono este en modo suspendido.
###### Vídeo: [Services](https://platzi.com/clases/1264-tecnico-android/10784-services8688/ "Services")
------------
#### Si te están solicitando desarrollar una aplicación que tenga que monitorear si el dispositivo está conectado a una red wifi. ¿Qué componente de aplicación usarías para monitorear el Wifi encendido?
		 Broadcast Receiver
###### Razón: Broadcast Receivers (Receptores de Transmisiones) siempre estan al pendiente de lo que pase en el sistema operativo (batería baja, red wifi disponible, llamadas entrantes, etc).
###### Vídeo: [Broadcast](https://platzi.com/clases/1264-tecnico-android/10786-broadcast/ "Broadcast")
------------
#### ¿Cuál es el mejor componente de aplicación que debería elegir al tener un requerimiento de una aplicación que tenga que mostrar muchas imágenes traídas de internet?
		 La clase AsyncTask
###### Razón: Es una clase para trabajar con hilos (Son multiprocesos al mismo tiempo) AsyncTask es recomendable para operaciones de corta duración. Actualmente AsyncTask está obsoleta desde la API 30 de android. En su lugar se deben usar las librerías de concurrencia de java o de kotlin.
###### Vídeo: [Asynctask](https://platzi.com/clases/1264-tecnico-android/10787-asynctask/ "Asynctask")
------------
#### ¿Cuál es el IDE oficial de Android?
		 Android Studio
###### Razón: Android Studio es el IDE oficial de Android, está basado totalmente en el entorno IntelliJ IDEA, es el más recomendado pues está diseñado totalmente para desarrollar aplicaciones móviles muy rápido.
###### Vídeo: [IDE Oficial de Android](https://platzi.com/clases/1264-tecnico-android/10788-ide-oficial-de-android/ "IDE Oficial de Android")
------------
#### ¿Cuál es la extensión de archivo ejecutable de Android?
		 apk
###### Razón: APK es la extensión de los archivos ejecutables en Android su significado es application package.
###### Vídeo: [Generación de un apk en Android](https://platzi.com/clases/1264-tecnico-android/10790-generacion-de-un-apk-en-android/ "Generación de un apk en Android")
------------
#### Tienes un proyecto que usa autenticación con Facebook, ya integraste la librería en el archivo clave del proyecto. ¿Qué motor se encargará de integrarla en el ejecutable de la aplicación, archivo apk?
		 gradle
###### Razón: Gradle toma el código, las dependencias y librerías externas; las reune y construye un archivo ejecutable (APK)
###### Vídeo: [Qué es y Cómo funciona Gradle](https://platzi.com/clases/1264-tecnico-android/10789-que-es-y-como-funciona-gradle/ "Qué es y Cómo funciona Gradle")
------------
#### Integrar la librería de Google Play Services a mis desarrollos Android hará que:
		 Tenga acceso a los servicios específicos de Google de la librería integrada
###### Razón: Google Play Services son los servicios de aplicaciones de google para interconectarlas con nuestras app.
###### Vídeo: [Google Play Services](https://platzi.com/clases/1264-tecnico-android/10791-google-play-services/ "Google Play Services")
------------
#### La aplicación de Google Play Services que está instalada en mi teléfono hará que:
		 Los servicios de google que estoy utilizando en mi aplicación tengan soporte por medio de la app
###### Razón: Google Play Services son los servicios de aplicaciones de google para interconectarlas con nuestras app.
###### Vídeo: [Google Play Services](https://platzi.com/clases/1264-tecnico-android/10791-google-play-services/ "Google Play Services")
------------
#### Estos son algunos lenguajes de programación para el desarrollar aplicaciones Android:
		 Java, kotlin, c# y js
###### Razón: Hay varios lenguajes que podemos usar para el desarrollo de app en android uno de ellos y el mas antiguo es Java, también existe otro lenguaje que trabaja de forma nativa y es Kotlin .
###### Vídeo: [Lenguajes para programar en Android](https://platzi.com/clases/1264-tecnico-android/10793-lenguajes-para-programar-en-android/ "Lenguajes para programar en Android")
------------
#### Cuando tengas que desarrollar una app para Android, ¿cuáles son las métricas de diseño que debe seguir el diseñador de interfaces móviles de tu equipo?
		 Material Design
###### Razón: Material Design son las métricas de diseño de aplicaciones fueron construidas por Google y traídas a Android a partir de la versión 5.0 Lollipop.
###### Vídeo: [Qué es Material Design](https://platzi.com/clases/1264-tecnico-android/10794-que-es-material-design/ "Qué es Material Design")
------------
#### ¿Cuál es la tienda de aplicaciones Android?
		 Play Store
###### Razón: Google Play Store es la tienda oficial de aplicaciones android, en ella encontrarás todo el catálogo de aplicaciones que puedes instalar en tu dispositivo.
###### Vídeo: [Tienda de Aplicaciones Android](https://platzi.com/clases/1264-tecnico-android/10804-tienda-de-aplicaciones-android/ "Tienda de Aplicaciones Android")
------------
#### ¿Qué necesito para poder subir aplicaciones a la Play Store?
		 Una cuenta de desarrollador
###### Razón:  El único requisito para lograr esto es obtener una cuenta de desarrollador de Google Play.
###### Vídeo: [Tienda de Aplicaciones Android](https://platzi.com/clases/1264-tecnico-android/10804-tienda-de-aplicaciones-android/ "Tienda de Aplicaciones Android")
------------
#### Si quisieras testear tu app, ¿cuál sería el mejor camino para hacerlo?
		 Empezar con test pequeños, luego test medianos que integren los pequeños hasta pasar a los largos que testean flujos e interfaces
###### Razón: Existen 3 tipos de pruebas: UI TEST - INTEGRATION TEST - UNIT TESTS
###### Vídeo: [Tipos de Testing en Android y UI Test](https://platzi.com/clases/1264-tecnico-android/10801-tipos-de-testing-en-android-y-ui-test/ "Tipos de Testing en Android y UI Test")
------------
#### ¿Cuál es el nombre del sitio donde puedes probar tus apps y recopilar estadísticos incluso antes de lanzar?
		 Google Play Console
###### Razón: En la Google Play Console podrás administrar todas las fases de publicación de tu app, además de probar y recopilar datos antes de lanzar o incluso una vez que ya lo hiciste, puedes asignar precios y manejar informes de ventas, ver y administrar comentarios de tus usuarios, tener estadísticos y datos para entender y mejorar la estabilidad de tu producto.
###### Vídeo: [Tienda de Aplicaciones Android](https://platzi.com/clases/1264-tecnico-android/10804-tienda-de-aplicaciones-android/ "Tienda de Aplicaciones Android")
