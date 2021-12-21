# Fundamentos de Ingeniería de Software
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Cuántos bits utliza una dirección ipv4?
		32
###### Razón: Un byte equivale a 8 bits, ipv4 usa 4bytes, por lo que 4 bytes = 32 bits por ser una dirección ipv4.
###### Vídeo:  [Qué son Bits y Bytes](https://platzi.com/clases/1098-ingenieria/6549-que-son-bits-y-bytes/ "Qué son Bits y Bytes")
------------
#### ¿Cuántos bits tiene un byte?
		8
###### Razón: - 1 Bit: Es un 0 o un 1
###### - 1 Byte: Son 8 Bit
###### - 1 Kilobyte: Son 1024 Bytes
###### - 1 Megabyte: Son 1024 Kilobytes
###### - 1 Gigabyte: Son 1024 Megabytes
###### - 1 Terabyte: Son 1024 Gigabytes
###### Vídeo:  [Qué son Bits y Bytes](https://platzi.com/clases/1098-ingenieria/6549-que-son-bits-y-bytes/ "Qué son Bits y Bytes")
------------
#### ¿Qué es la CPU?
		La unidad central de procesamiento
###### Razón: Existe una arquitectura para computadores de escritorio y laptops, estos internamente tienen:
###### CPUs: ( Central Processing Unit/Unidad Central de Procesamiento) su velocidad de mide en GHz y tienen Cores que son el número de instrucciones en paralelo que pueden hacer.
###### Vídeo:  [Procesadores y arquitecturas de CPU](https://platzi.com/clases/1098-ingenieria/6551-procesadores-y-arquitecturas-de-cpu/ "Procesadores y arquitecturas de CPU")
------------
#### El número 27 representado en binario es
		11011
###### Razón: Para hacer la conversión de decimal a binario, hay que ir dividiendo el número decimal entre dos y anotar en una columna a la derecha el resto (un 0 si el resultado de la división es par y un 1 si es impar).
###### Vídeo: [Conversión decimal a binaria](https://youtu.be/CXKjWbTf9CQ "Conversión decimal a binaria")
------------
#### El procesador solo puede interpretar
		Ceros y unos
###### Razón: Utilizan el sistema binario (o base dos) que solo tiene dos valores (unos y ceros) ya que los procesadores se fabrican con transistores en su interior que dejan pasar o no dejan pasar la electricidad, representando con ello los unos y los ceros respectivamente.
###### Vídeo:  [Procesadores y arquitecturas de CPU](https://platzi.com/clases/1098-ingenieria/6551-procesadores-y-arquitecturas-de-cpu/ "Procesadores y arquitecturas de CPU")
------------
#### La velocidad de los procesadores se mide en
		Hertz
###### Razón: Su velocidad de mide en GHz (GigaHertz) que es la velocidad a la que procesan una instrucción y tienen Cores o núcleos que son el número de instrucciones en paralelo que pueden hacer.
###### Vídeo:  [Procesadores y arquitecturas de CPU](https://platzi.com/clases/1098-ingenieria/6551-procesadores-y-arquitecturas-de-cpu/ "Procesadores y arquitecturas de CPU")
------------
#### Uno de los trabajos más importantes de la BIOS es identificar
		 El hardware y periféricos conectados
###### Razón: BIOS (Basic Input/Output System), es un pequeño sistema que arranca el computador y comprueba la conexión del hardware.
###### Vídeo: [Periféricos y sistemas de entrada de información](https://platzi.com/clases/1098-ingenieria/6555-perifericos-y-sistemas-de-entrada-de-informacion/ "Periféricos y sistemas de entrada de información") 
------------
#### Un archivo de texto con la palabra "Platzi" debe pesar
		6 bytes
###### Razón: Tu computadora utiliza 6 bytes o 48 bits para formar la palabra “Platzi", podemos decir que un byte por carácter. 
###### Vídeo: [Qué son Bits y Bytes](https://platzi.com/clases/1098-ingenieria/6549-que-son-bits-y-bytes/ "Qué son Bits y Bytes")
------------
#### Los primeros sectores de datos de un disco duro guardan
		 Un índice de donde se encuentra guardado los archivos
###### Razón: Por lo general en los primeros sectores del disco se encuentra el indice (también llamado cabecera), ahí estan todas las direcciones de todos los archivos. Los índices a traves de los drivers le indican sistema operativo como darle una orden al CPU para la cabeza de lectura del disco duro se mueva hasta el lugar donde está el archivo.
###### Vídeo:  [Qué es la memoria RAM y cómo funcionan los discos duros](https://platzi.com/clases/1098-ingenieria/6553-que-es-la-memoria-ram-y-como-funcionan-los-discos-/ "Qué es la memoria RAM y cómo funcionan los discos duros")
------------
#### ¿Qué es un driver?
		Es el software que permite al sistema operativo interpretar las señales del hardware.
###### Razón: El kernel, inmediatamente después de ser cargado en RAM, se encarga de cargar los drivers: pequeñas piezas de software que permiten interpretar las señales eléctricas del hardware, para que el sistema operativo pueda comunicarse con ellos.
###### Vídeo:  [Periféricos y sistemas de entrada de información](https://platzi.com/clases/1098-ingenieria/6555-perifericos-y-sistemas-de-entrada-de-informacion/ "Periféricos y sistemas de entrada de información")
------------
#### ¿Qué es una IP?
		Es un número asignado para identificar los computadoras en la red
###### Razón: IP es la sigla de Internet Protocol y una dirección IP es un número único con el cual una computadora o un dispositivo se identifica cuando está conectada a una red con el protocolo IP.
###### Vídeo:  [Qué es una dirección IP y el protocolo de Internet](https://platzi.com/clases/1098-ingenieria/6559-que-es-una-direccion-ip-y-el-protocolo-de-internet/ "Qué es una dirección IP y el protocolo de Internet")
------------
#### ¿Cuál es la IP que normalmente se refiere al mismo equipo o localhost?
		127.0.0.1
###### Razón: 127.0.0.1 es una dirección IP de loopback, con el cual nos referimos a un enrutamiento de flujo propio, con el cual el host accede a sus propios servicios independientemente de la configuración de red en la que se encuentre.
###### Vídeo:  [Qué es una dirección IP y el protocolo de Internet](https://platzi.com/clases/1098-ingenieria/6559-que-es-una-direccion-ip-y-el-protocolo-de-internet/ "Qué es una dirección IP y el protocolo de Internet")
------------
#### El router asigna ips de forma automática usando el protocolo
		DHCP
###### Razón: El router es quien asigna una ip a nuestra computadora, a través del DHCP (Dynamic Host Configuration Protocol/Protocolo de Configuración Dinámica de Host) , esté debe tener una ip maestra que también lo identifique en la red, gracias a esta ip es que se permite que todos los dispositivos puedan intercambiar información y persistir en la red.
###### Vídeo:  [Qué es una dirección IP y el protocolo de Internet](https://platzi.com/clases/1098-ingenieria/6559-que-es-una-direccion-ip-y-el-protocolo-de-internet/ "Qué es una dirección IP y el protocolo de Internet")
------------
#### ¿Qué rango de puertos de red requieren permisos de administrador en el sistema operativo para ser usados?
		1-1024
###### Razón: Los puertos son redes virtuales dentro del SO. En un SO funcionan los puertos del 1 al 1024 (llamados bien conocidos) están reservados para ser ejecutados por el SO a través del admin. Ejemplos; Protocolo HTTP => Puerto 80 y Protocolo HTTPS => Puerto 443.
###### Vídeo:  [Puertos y protocolos de red](https://platzi.com/clases/1098-ingenieria/6558-puertos-y-protocolos-de-red/ "Puertos y protocolos de red")
------------
#### Si compras una conexión de 100 Mbps en teoria cuál es la máxima velocidad de descarga
		~12.5 MB/s
###### Razón: 1 Mbps (Mega bits por segundo) equivale a 8 bytes, por lo que 100/8 es igual 12.5 MB/s
###### Vídeo: [Cómo funciona la velocidad en internet](https://platzi.com/clases/1098-ingenieria/6563-como-funciona-la-velocidad-en-internet/ "Cómo funciona la velocidad en internet")
------------
#### Para que una app móvil tenga acceso al hardware de tu dispositivo debe tener un
		Manifiesto de permisos
###### Razón: Requieren que tu app pida de manera manifiesta y directa los permisos de acceso a las cosas que quieres usar, entonces por ejemplo si quieres instalar una app como uber tienes que decir que te permiso al gps, contactos, a la camara, al microfono, archivos, etc…
###### Vídeo: [Fundamentos de sistemas operativos móviles](https://platzi.com/clases/1098-ingenieria/6569-fundamentos-de-sistemas-operativos-moviles/ "Fundamentos de sistemas operativos móviles")
------------
#### ¿Cuál es el sistema operativo por defecto de un Arduino?
		Ninguno
###### Razón: Los arduinos son una herramienta que permite crear prototipos de sistemas, desde automatizar un horno antiguo hasta controlar una cámara por IoT, por esto son tan populares. El sistema operativo es cargado por el usuario.
###### Vídeo: [Sistemas operativos embebidos e Internet of Things](https://platzi.com/clases/1098-ingenieria/6570-sistemas-operativos-embebidos-e-internet-of-things/ "Sistemas operativos embebidos e Internet of Things")
------------
#### ¿Cómo un sistema operativo sabe que software usar para un tipo de archivo?
		El sistema operativo lee la cabecera del archivo donde encuentra el tipo de archivo y tiene una base de datos que asocia las extensiones con un software.
###### Razón: Un sistema operativo lee los primeros bytes del archivo para entender a que archivo corresponde, esta información se llama cabecera. Cada sistema operativo tiene una base de datos de que programa abre que tipo de archivo.
###### Vídeo:  [Metadatos, cabeceras y extensiones de archivos](https://platzi.com/clases/1098-ingenieria/6571-metadatos-cabeceras-y-extensiones-de-archivos/ "Metadatos, cabeceras y extensiones de archivos")
------------
#### Para tener una imagen con calidad de color de 32 bits, cada pixel debe ser representado con
		4 Bytes
###### Razón:  1 Bit representa como número máximo es el 256: Por lo tanto en un .bmp tiene 256 colores y para determinar su tamaño se debe multiplicar el ancho por el alto de la imagen. Para representar colores de 16 bits: Se necesitan 2 bytes, para representar colores (ultra-reales) de 32 bits: Se necesitan 4 bytes, entonces si cada byte tiene 8 bits, entonces; 16 bits es igual a 2 bytes y 32 bits es igual a 4 bytes.
###### Vídeo:  [Cómo funciona el formato JPG](https://platzi.com/clases/1098-ingenieria/6572-como-funciona-el-formato-jpg/ "Cómo funciona el formato JPG")
------------
#### Un contenedor de vídeos es
		El formato que agrupa el vídeo y audio con un enconding.
###### Razón: Los contenedores son los tipos de archivos donde se guardan los videos, no son simples formatos como el jpg, dado que un video tiene la animación en movimiento, el sonido, subtitulo. Por lo cual se han creado múltiples contenedores, por ejemplo: el .avi, .mp4, .flv, .mpg, webm; cada uno de estos formatos, tienen fragmentos internos que los optimizan para cada caso.
###### Vídeo: [Videos, contenedores, codecs y protocolos](https://platzi.com/clases/1098-ingenieria/6573-videos-contenedores-codecs-y-protocolos/ "Videos, contenedores, codecs y protocolos")
------------
#### ¿Que es un Sytem-on-a-Chip?
		 Un chip especial que agrupa CPU/GPU y otros chips de un dispositivo.
###### Razón: System on a Chip es todo el sistema de funcionamiento de un CPU normal de computadora, integrado en un Chip.
###### Vídeo: [Qué es un system on a chip](https://platzi.com/clases/1098-ingenieria/6552-que-es-un-system-on-a-chip/ "Qué es un system on a chip")
------------
#### Un disco de estado sólido es especial porque
		 Es persistente, aleatorio y rápido.
###### Razón: Los discos duros de estado sólido no tienen el cabezal ni los discos que giran, sino que son más parecidos a las memorias RAM: funcionan electrónicamente. A pesar de eso guardan los datos en memorias flash, que son un poco más lentas que las RAM.
###### Vídeo: [Qué es la memoria RAM y cómo funcionan los discos duros](https://platzi.com/clases/1098-ingenieria/6553-que-es-la-memoria-ram-y-como-funcionan-los-discos-/ "Qué es la memoria RAM y cómo funcionan los discos duros")  
------------
#### La mayor parte del tráfico de internet viaja a través de 
		Cables submarinos
###### Razón: Los satélites están destinados sólo para áreas remotas. Internet funciona a partir de cables que atraviesan diferentes lugares del mundo. Cuando usas un dispositivo, este se conecta a un ISP o un prestador de servicios de Internet. De ahí, la conexión con diferentes puntos en el mundo a través de cables submarinos, que pueden ser de fibra óptica o cobre.
###### Vídeo:  [Cables submarinos, antenas y satelites en Internet](https://platzi.com/clases/1098-ingenieria/6560-cables-submarinos-antenas-y-satelites-en-internet/ "Cables submarinos, antenas y satelites en Internet")
------------
#### Quality of Service es
		Como los ISP reforman el tráfico para degradar ciertas conexiones
###### Razón: Los proveedores de internet establecen prioridades sobre la red, entonces reducen la conexión, enfocándose en los clientes que dan más dinero que son las empresas y manejando los servicios más solicitados (email, archivos, llamadas), entonces configuran los routers internos a través de una tecnología llamada firewalls y otras como network shaping.
###### Vídeo: [Cómo los ISP hacen Quality of Service o QoS](https://platzi.com/clases/1098-ingenieria/6562-como-los-isp-hacen-quality-of-service-o-qos/ "Cómo los ISP hacen Quality of Service o QoS")
------------
#### A nivel físico, la limitación de velocidad de una red depende de
		La velocidad de la luz
###### Razón: La velocidad de internet se mide en la cantidad de bits no bytes que transmite por segundo La forma de medir la velocidad de un ping es divididiendo la distancia entre un punto de conexión y otro entre la velocidad de la luz 300 km/ms.
###### Vídeo:  [Cómo funciona la velocidad en internet](https://platzi.com/clases/1098-ingenieria/6563-como-funciona-la-velocidad-en-internet/ "Cómo funciona la velocidad en internet")
------------
#### Tu dispositivo móvil puede ser un servidor en Internet
		Verdadero
###### Razón: Los servidores son computadores que almacenan páginas web, sitios o aplicaciones.
###### Vídeo: [Qué es el Modelo Cliente/Servidor](https://platzi.com/clases/1098-ingenieria/6564-que-es-el-modelo-clienteservidor/ "Qué es el Modelo Cliente/Servidor")
------------
#### El router de internet de tu casa puede ser un servidor en Internet
		Verdadero
###### Razón: Los servidores son computadores que almacenan páginas web, sitios o aplicaciones.
###### Vídeo: [Qué es el Modelo Cliente/Servidor](https://platzi.com/clases/1098-ingenieria/6564-que-es-el-modelo-clienteservidor/ "Qué es el Modelo Cliente/Servidor")
------------
#### Un Raspeberry Pi con wifi puede ser un servidor en Internet
		Verdadero
###### Razón: Raspberry Pi, contiene un SoC, que controla todos los procesos de la tarjeta, un puerto hdmi, lector de tarjeta SD, GPIO - entradas y salidas de propósito general. Creado con la intención de proveer un acercamiento con el software y hardware de manera fácil y barato, con un enfoque a la educación contiene todos los componentes para ser una computadora completa.
###### Vídeo: [El poder de un Raspberry Pi](https://platzi.com/clases/1098-ingenieria/6751-el-poder-de-un-raspberry-pi/ "El poder de un Raspberry Pi")
------------
#### Cuando ves algo como: video/mp4 ¿Que estás viendo?
		Un MIME type una definición de tipo´de archivo
###### Razón: Cuando estas transmitiendo un archivo por Internet se especifica el tipo de archivo con MIME types (MUltipurpose Internet Mail Extensions) , el cual se transmite en la cabecera de un paquete http.
###### Vídeo:  [Metadatos, cabeceras y extensiones de archivos](https://platzi.com/clases/1098-ingenieria/6571-metadatos-cabeceras-y-extensiones-de-archivos/ "Metadatos, cabeceras y extensiones de archivos")
------------
#### ¿De qué forma fluyen dentro de un computador los ceros y unos?
		Con pulsos eléctricos
###### Razón: La electricidad en general es un flujo de electrones por un medio físico. El voltaje es la fuerza o tensión que lleva ese flujo, y la corriente la cantidad de electrones que se mueven en ese flujo. 
###### Vídeo:  [Cómo funcionan los circuitos electrónicos](https://platzi.com/clases/1098-ingenieria/6550-como-funcionan-los-circuitos-electronicos/ "Cómo funcionan los circuitos electrónicos")
------------
#### ¿En dónde se almacena los archivos del sistema operativo?
		Disco duro
###### Razón: Los archivos se almacenan en el disco duro, ya que los discos duros no son volátiles: guardan la información de manera persistente aunque se les quite el suministro de energía.
###### Vídeo: [Qué es la memoria RAM y cómo funcionan los discos duros](https://platzi.com/clases/1098-ingenieria/6553-que-es-la-memoria-ram-y-como-funcionan-los-discos-/ "Qué es la memoria RAM y cómo funcionan los discos duros") 
------------
#### La memoria RAM accede a los datos de forma
		Aleatoria
###### Razón: RAM (Random Access Memory) La memoria RAM es más rápida ya que puede acceder a los datos almacenados de manera instantánea.
###### Vídeo: [Qué es la memoria RAM y cómo funcionan los discos duros](https://platzi.com/clases/1098-ingenieria/6553-que-es-la-memoria-ram-y-como-funcionan-los-discos-/ "Qué es la memoria RAM y cómo funcionan los discos duros") 
------------
#### El chip ideal para procesar la representación gráfica de datos en pantalla es
		GPU
###### Razón: GPU (Graphics Processing Unit), la GPU divide la pantalla en una matriz y cada núcleo se encarga de dibujar una parte de esa matriz, para lograr un mejor desempeño.
###### Vídeo:  [GPUs, tarjetas de video y sonido](https://platzi.com/clases/1098-ingenieria/6554-gpus-tarjetas-de-video-y-sonido/ "GPUs, tarjetas de video y sonido")
------------
#### ¿Cuál no es una característica de discos duros?
		Almacena los datos de forma temporal
###### Razón: Los discos duros no son volátiles: guardan la información de manera persistente aunque se les quite el suministro de energía.
###### Vídeo: [Qué es la memoria RAM y cómo funcionan los discos duros](https://platzi.com/clases/1098-ingenieria/6553-que-es-la-memoria-ram-y-como-funcionan-los-discos-/ "Qué es la memoria RAM y cómo funcionan los discos duros") 
------------
#### ¿Qué es un switch en una red?
		El dispositivo que conecta múltiples dispositivos a la misma red
###### Razón: Switch o conmutador es el dispositivo digital lógico de interconexión de equipos que opera en la capa de enlace de datos del modelo OSI. Su función es interconectar dos o más segmentos de red, de manera similar a los puentes de red, pasando datos de un segmento a otro de acuerdo con la dirección MAC de destino de las tramas en la red y eliminando la conexión una vez finalizada ésta.
###### Vídeo: [Introducción a las redes, protocolos e Internet](https://platzi.com/clases/1098-ingenieria/6557-introduccion-a-las-redes-protocolos-e-internet/ "Introducción a las redes, protocolos e Internet")
------------
#### ¿Qué es un DNS?
		Es un sistema que asocia los nombres de dominio con la IP del servidor
###### Razón: DNS (Sistema de Nombres de Dominio/Domain Name System). Son servidores que tienen una base de datos en la cual saben a que ip corresponde un nombre. Nosotros debemos hacerle una peticion al dns antes de abrir cualquier sitio web. Hay muchos servidores de DNS por todo el mundo.
###### Vídeo:  [Qué es un dominio, DNS o Domain Name System](https://platzi.com/clases/1098-ingenieria/6561-que-es-un-dominio-dns-o-domain-name-system/ "Qué es un dominio, DNS o Domain Name System")
------------
#### Si un archivo tiene los permisos 750 que usuarios lo pueden editar
		Administrador
###### Razón: Cada dígito  de derecha a izquierda corresponde a Admin/Team/ Public. Por lo que: 
###### - 7 representa permisos de escritura, lectura y ejecucion
###### - 6 representa lectura y escritura
###### - 5 representa lectura y ejecucion
###### - 4 representa lectura
###### - 3 representa escritura y ejecucion
###### - 2 representa escritura
###### - 1 representa ejecucion
###### - 0 representa ningun permiso
###### Vídeo:  [Permisos, niveles de procesos y privilegios de ejecución](https://platzi.com/clases/1098-ingenieria/6568-permisos-niveles-de-procesos-y-privilegios-de-ejec/ "Permisos, niveles de procesos y privilegios de ejecución")


