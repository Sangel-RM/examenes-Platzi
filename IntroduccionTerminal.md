# Curso de Introducción a la Terminal y Línea de Comandos
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### La shell o línea de comandos es:
		 Un programa que nos ayuda a comunicarnos con nuestro sistema operativo.
###### Razón: Es una interfaz gráfica  que simula una línea de comandos. Cuando hablamos de una línea de comandos nos referimos a una shell.
###### Vídeo: [¿Qué es la terminal?](https://platzi.com/clases/2292-terminal/37341-que-es-la-terminal/ "¿Qué es la terminal?")
------------
#### ¿Qué hace el comando pwd?
		 Imprime la ruta del directorio actual de trabajo.
###### Razón: pwd significa Print Working Directory, cuya traducción sería imprimir directorio de trabajo, se usa para saber la ruta en la que estamos situados.
###### Vídeo: [Aprendiendo a caminar en la terminal](https://platzi.com/clases/2292-terminal/37342-aprendiendo-a-caminar-en-la-terminal/ "Aprendiendo a caminar en la terminal")
------------
#### ¿Con cuál comando copiamos un directorio y su contenido? (Esto hace parte de uno de los retos que te dejé)
		 cp -r mi_directorio ruta_destino
###### Razón: cp archivo ruta permite copiar archivos, para copiar directorios con su contenido añadir la flag o parametro -r que indica recursividad
###### Vídeo: [Manipulando archivos y directorios](https://platzi.com/clases/2292-terminal/37344-manipulando-archivos-y-directorios/ "Manipulando archivos y directorios")
------------
#### ¿Qué comando muestra las últimas 5 líneas de texto de un documento?
		 tail -n 5 mi_texto
###### Razón: El comando Tail es una solución práctica para analizar las últimas líneas de un archivo, con el parametro -n seguido de algún numero, nos permite visualizar las últimas lineas que solicitamos. Quizás esta imagen te sirva: [Head-Cat-Tail](https://static.platzi.com/media/user_upload/porque-los-gatos-mueven-la-cola-2-af5d748b-8d4e-42c8-8f8c-133406a01512.jpg "Head-Cat-Tail")
###### Vídeo: [Explorando el contenido de nuestros archivos](https://platzi.com/clases/2292-terminal/37345-explorando-el-contenido-de-nuestros-archivos/ "Explorando el contenido de nuestros archivos")
------------
#### Las wildcards son caracteres que nos permiten definir patrones avanzados de búsqueda en la línea de comandos, esto es:
		 Verdadero
###### Razón: Las wildcards nos sirven para realizar seccionamiento de archivos o directorios, ademas de ls los wildcards tambien pueden usarse con cualquier comando que realize la manipulacion de archivos como mv, cp y rm. El asterisco * significa cualquier STRING o cadena de texto, entonces si ponemos ls *.txt cualquier archivo .txt se listará. Y el signo de interrogación ? significa que ese último dato puede ser cualquier arbitrario, pero sólo ese último. Entonces en resumen, el * se expande de 0 a más caracteres, mientras que ? expande a uno exactamente.
###### Vídeo: [Wildcards](https://platzi.com/clases/2292-terminal/37346-wildcards/ "Wildcards") 
------------
#### Si queremos listar todos los archivos que sean extensión txt podemos usar el comando:
		 ls *.txt
###### Razón: El asterisco * significa cualquier STRING o cadena de texto, entonces si ponemos ls *.txt cualquier archivo .txt se listará. Y el signo de interrogación ? significa que ese último dato puede ser cualquier arbitrario, pero sólo ese último. Entonces en resumen, el * se expande de 0 a más caracteres, mientras que ? expande a uno exactamente.
###### Vídeo: [Wildcards](https://platzi.com/clases/2292-terminal/37346-wildcards/ "Wildcards") 
------------
#### El file descriptor correspondiente al stderr es:
		 2
###### Razón: stdin (0): Entrada estándar, stdout (1): Salida estándar, stderr (2): Salida de errores.
###### Vídeo: [Redirecciones: cómo funciona la shell](https://platzi.com/clases/2292-terminal/37347-redirecciones-como-funciona-la-shell/ "Redirecciones: cómo funciona la shell")
------------
#### ¿Qué operador nos ayuda a concatenar la salida de un comando a un archivo de texto?
		 >>
###### Razón: Mientras que > es para re escribir, >> es para concatenar. Concatena la salida de un comando a un archivo, si no existe el archivo lo crea. comando >> archivo
###### Vídeo: [Redirecciones: cómo funciona la shell](https://platzi.com/clases/2292-terminal/37347-redirecciones-como-funciona-la-shell/ "Redirecciones: cómo funciona la shell")
------------
#### El pipe operator redirecciona la salida de un comando a la entrada de otro comando, esto es:
		 Verdadero
###### Razón:  El pipe operator (|) permite enviar la salida de un comando como entrada del siguiente. Usamos el operado pipe | entre dos comando para direccionar el stdout del primero con el stdin del segundo. Cualquier comando, entre pipes, puede tener opciones o argumentos para construir filtros complejos. Una de las ventajas de los pipes, en Linux y UNIX, es de que pueden variar y generar salidas intermedias de diferentes procesos, generando todo un trace de flujo de información.
###### Vídeo: [Redirecciones: pipe operator](https://platzi.com/clases/2292-terminal/37391-redirecciones-pipe-operator/ "Redirecciones: pipe operator")
------------
#### Si queremos explorar las primeras 100 líneas de un documento de texto lo podemos hacer con:
		 head -n 100 mi_texto | less
###### Razón: El comando head permite analizar las primeras líneas de un archivo, con el parametro -n seguido de algún numero, nos permite visualizar las primeras lineas que solicitamos. Y al pasarlo con el pipe operator (|) al comando less nos permite una mejor legibilidad. Quizás esta imagen te sirva: [Head-Cat-Tail](https://static.platzi.com/media/user_upload/porque-los-gatos-mueven-la-cola-2-af5d748b-8d4e-42c8-8f8c-133406a01512.jpg "Head-Cat-Tail")
###### Vídeo: [Explorando el contenido de nuestros archivos](https://platzi.com/clases/2292-terminal/37345-explorando-el-contenido-de-nuestros-archivos/ "Explorando el contenido de nuestros archivos")
------------
#### Si queremos correr una serie de comandos de manera asíncrona lo hacemos con el operador:
		 &
###### Razón: Comandos separados por & : Se ejecutan todos al mismo tiempo, es decir de forma asíncrona. command1 & command2 & command3 & commandN ...
###### Vídeo: [Encadenando comandos: operadores de control](https://platzi.com/clases/2292-terminal/37349-encadenando-comandos-operadores-de-control/ "Encadenando comandos: operadores de control")
------------
#### Si deseamos condicionar la ejecución de un comando solo si uno anterior se ejecuto de manera exitosa podemos usar:
		 &&
###### Razón: Comandos separados por && : Se ejecutan solo si el comando anterior se haya ejecutado exitosamente. Suponemos que A, B y C son comando: A && B && C El B solo se va ejecutar si el A se ejecuta exitosamente, y el C solo se va ejecutar si el B si ejecuta exitosamente. Si el B no se ejecuta exitosamenta el C no se ejecuta. Si el A no se ejecuta exitomante el B y el C no se ejecutarán.
###### Vídeo: [Encadenando comandos: operadores de control](https://platzi.com/clases/2292-terminal/37349-encadenando-comandos-operadores-de-control/ "Encadenando comandos: operadores de control")
------------
#### El comando chmod u=rwx,go=r mi_archivo ¿qué permisos otorga?
		 Otorga permisos de lectura, escritura y ejecución al usuario. Solo otorga permiso de lectura a los grupos y a otros.
###### Razón: Es el modo simbolico donde u es el user/owner, g es group, y o es others. Los permisos son r de read, w de write y x de execute.
###### Vídeo: [Cómo se manejan los permisos](https://platzi.com/clases/2292-terminal/37348-como-se-manejan-los-permisos/ "Cómo se manejan los permisos")
------------
#### Es una mala práctica de seguridad asignar la siguiente configuración de permisos en modo octal a cualquier archivo o directorio.
		 777
###### Razón: El permiso 777 asigna todos los permisos de read, write y execute al owner/user, group y other. Entonces es una mala práctica debido a que otorga todos los permisos a todos.
###### Vídeo: [Cómo se manejan los permisos](https://platzi.com/clases/2292-terminal/37348-como-se-manejan-los-permisos/ "Cómo se manejan los permisos")
------------
#### Con el siguiente comando podemos ver la ruta del directorio Home de nuestro usuario:
		 echo $HOME
###### Razón: La terminal cuenta con una configuración con diferentes valores, que se pueden acceder con las variables de entorno. Estas son muy importantes para la configuración general del sistema. En este caso se imprime la ruta de nuestro HOME.
###### Vídeo: [Cómo configurar variables de entorno](https://platzi.com/clases/2292-terminal/37350-variables-de-entorno/ "Cómo configurar variables de entorno")
------------
#### Para guardar todas nuestras variables de entorno en un archivo de texto podemos ejecutar el comando:
		 env > environment.txt
###### Razón: env nos muestra todas las variables de entorno que tenemos configuradas, y lo redirigimos con > al archivo enviroment.txt
###### Vídeo: [Cómo configurar variables de entorno](https://platzi.com/clases/2292-terminal/37350-variables-de-entorno/ "Cómo configurar variables de entorno")
------------
#### Es un comando que nos ayuda a buscar la ruta de binarios o ejecutables en nuestro sistema.
		 which
###### Razón: which programa busca en todas las rutas del PATH para encontrar donde está alojado algún archivo binario 
###### Vídeo: [Comandos de búsqueda](https://platzi.com/clases/2292-terminal/37351-comandos-de-busqueda/ "Comandos de búsqueda")
------------
#### Para usar grep sin distinción de mayúsculas o minúsculas usamos:
		 -i
###### Razón: La flag o bandera -i, ignora si son letras mayúsculas o minúsculas, es decir que deja de ser case sensitive. Por ejemplo grep -i bu animales.txt, traera las palabaras sin importar que sean mayusculas o minusculas lo solicitado que fue la sílaba 'bu'.
###### Vídeo: [Su majestad: grep](https://platzi.com/clases/2292-terminal/37352-su-majestad-grep/ "Su majestad: grep")
------------
#### ¿Qué comando nos ayuda consultar la disponibilidad de un equipo en una red?
		ping
###### Razón:  ejecutar el comando ping , el protocolo ICMP envía al host un determinado datagrama para solicitar una respuesta.  Es decir nos muestra si una ip o página esta activa, si recibe paquetes es porque hay conexión.
###### Vídeo: [Utilidades de red](https://platzi.com/clases/2292-terminal/37353-utilidades-de-red/ "Utilidades de red")
------------
#### ¿Qué comando muestra los procesos que consumen más recursos en nuestro sistema?
 		 top
###### Razón: El comando top nos permite conocer los procesos de ejecución del sistema en tiempo real.
###### Vídeo: [Manejo de procesos](https://platzi.com/clases/2292-terminal/37355-manejo-de-procesos/ "Manejo de procesos")
------------
#### Para crear un archivo usamos el comando:
		 touch mi_archivo
###### Razón: El comando touch permite crear un archivo, si no indicas la extension por defecto sera .txt
###### Vídeo: [Manipulando archivos y directorios](https://platzi.com/clases/2292-terminal/37344-manipulando-archivos-y-directorios/ "Manipulando archivos y directorios")
------------
#### Para leer el manual de usuario de un comando usamos:
		 man
###### Razón: Man es una herramienta que se utiliza para documentar y aprender sobre comandos, archivos, llamadas de sistema.
###### Vídeo: [¿Qué es un comando?](https://platzi.com/clases/2292-terminal/37343-que-es-un-comando/ "¿Qué es un comando?")
------------
#### Para buscar todas las imágenes png dentro de nuestra computadora podemos ejecutar:
		 find / -name *.png
###### Razón: El comando find nos ayuda a realizar búsquedas, seguida de la ruta donde búscara en este caso / indica la raíz de nuestra sistema, la flag -name indica que se realizará la búsqueda por nombre de archivo, después el archivo a buscar, en este caso se hace uso de wild cards que son todos los archivos que terminen en .png
###### Vídeo: [Comandos de búsqueda](https://platzi.com/clases/2292-terminal/37351-comandos-de-busqueda/ "Comandos de búsqueda")