# Curso Práctico de Maquetación en CSS
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es emmet?
		 Es un plugin que nos ayuda a escribir código HTML y CSS a base de abreviaciones.
###### Razón: Emmet es un plugin de diseño que se adapta a los editores de texto y permite escribir código HTML de forma abreviada.
###### Vídeo: [Arquitectura del header en HTML](https://platzi.com/clases/1744-practico-css/24714-arquitectura-del-header-en-html/)
------------
#### ¿Qué etiqueta utilizarías para crear la barra de navegación de tu proyecto?
		 nav
###### Razón: El elemento HTML <nav> representa una sección de una página cuyo propósito es proporcionar enlaces de navegación, ya sea dentro del documento actual o a otros documentos. Ejemplos comunes de secciones de navegación son menús, tablas de contenido e índices.
###### Vídeo: [Arquitectura del header en HTML](https://platzi.com/clases/1744-practico-css/24714-arquitectura-del-header-en-html/)
------------
#### ¿Cuál de los siguientes doctype es el que utilizarías para un documento HTML5?
		 <!Doctype html>
###### Razón: La declaración <!Doctype html> es información para el navegador sobre el tipo de documento que espera.
###### Vídeo: [Setup del proyecto](https://platzi.com/clases/1744-practico-css/24713-setup-del-proyecto/)
------------
#### ¿Qué metodología podríamos utilizar para nombrar de mejor forma tus clases en CSS?
		 BEM
###### Razón: La metodología BEM divide la interfaz de usuario en bloques independientes para crear componentes escalables y reutilizables. BEM (Block, Element, Modifier o Bloque, Elemento, Modificador) es una metodología ágil de desarrollo basada en componentes.
###### Vídeo: [Manejo de clases](https://platzi.com/clases/1744-practico-css/24718-manejo-de-clases/)
------------
#### ¿A qué nos referimos cuando hablamos de HTML5 Semántico?
		 Describir con mayor precisión cuál es su contenido.
###### Razón: HTML brinda una serie de etiquetas con mayor significado, para cada parte, sección, o elemento de una página, y aunque en la práctica no generen un resultado distinto, tiene ventajas como código más claro y fácil de mantener, ayuda a ser el sitio accesible y mejora el posicionamiento SEO.
###### Vídeo: [Arquitectura del header en HTML](https://platzi.com/clases/1744-practico-css/24714-arquitectura-del-header-en-html/)
------------
#### ¿De qué forma puedo darle el mismo estilo a más de un elemento en css?
		 Utilizando la “,” después de cada selector.
###### Razón: para aplicar el mismo estilo a más de un elemento en CSS se debe usar la coma (,), ejemplo: .contact-main-container .contact-left, .contact-right{}
###### Vídeo: [Sección de contacto](https://platzi.com/clases/1744-practico-css/24726-seccion-de-contacto/)
------------
#### ¿De qué forma podría generar estilos en css que pueda reutilizar para otros selectores sin que tenga que replicar propiedades?
		 Utilizando variables de CSS.
###### Razón: Son entidades definidas por autores de CSS que contienen valores específicos que se pueden volver a utilizar en un documento. Se establecen --mi-color: #ff5858, y se usan mediante la función var(--mi-color)
###### Vídeo: [Sección de contacto](https://platzi.com/clases/1744-practico-css/24726-seccion-de-contacto/)
------------
#### ¿Qué etiquetas de HTML5 tienen "display: block;" por defecto?
		 header, footer, div, p, nav, h1.
###### Razón: En display block, son elementos que generan un cuadro de elemento de bloque, es decir que ocupan todo el ancho disponible.
###### Vídeo: [Blog page](https://platzi.com/clases/1744-practico-css/24709-blog-page/)
------------
#### ¿Cual es la forma adecuada de llamar un media query?
		 @media (condicional)
###### Razón: Las media queries son útiles cuando se deseen modificar la página web o aplicación en función del tipo de dispositivo (como una impresora o una pantalla) o de características y parámetros específicos (como la resolución de la pantalla o el ancho del viewport del navegador). Ejemplo, @media(max-width:600px)
###### Vídeo: [Media queries](https://platzi.com/clases/1744-practico-css/24729-media-queries/)
------------
#### ¿Para qué nos puede ayudar implementar CSS Grid Layout en nuestros estilos?
		 Nos facilita posicionar contenedores creando una cuadrícula y alineando elementos en filas y columnas.
###### Razón: CSS grid se puede utilizar para lograr muchos diseños diferentes. También se destaca por permitir dividir una página en áreas o regiones principales, por definir la relación en términos de tamaño, posición y capas entre partes de un control construido a partir de primitivas HTML.
###### Vídeo: [Media queries](https://platzi.com/clases/1744-practico-css/24729-media-queries/)
------------
#### ¿De qué forma podría crear una cuadrícula de 3 x 3 utilizando Grid Layout?
		 display: grid; grid-template-columns: 1fr 1fr 1fr; grid -template-rows: 1fr 1fr 1fr;
###### Razón: Primero s establace que se trabajara con un display grid, para luego crear un template de 3 columnas y filas que tengan de tamaño 1 fracción de la pantalla.
###### Vídeo: [Manejo de Grid para posicionar contenedores](https://platzi.com/clases/1744-practico-css/24705-manejo-de-grid-para-posicionar-contenedores/)
------------
#### ¿Para qué nos ayuda colocar el “alt” en una img?
		 Ayuda a usuarios con problemas visuales que utilizan herramientas de lectura de pantalla.
###### Razón: Este atributo define el texto alternativo que describe la imagen, texto que los usuarios verán si la URL de la imagen es errónea o la imagen tiene un formato no soportado o si la imagen aún no se ha descargado.
###### Vídeo: [Agregando imágenes al header](https://platzi.com/clases/1744-practico-css/24717-agregando-imagenes-al-header/)
------------
#### ¿Cuál es la forma de agregar una imagen de fondo con css?
		 background-image: url(" ");
###### Razón: background-image estable una imagen de fondo. 
###### Vídeo: [Agregando imágenes al header](https://platzi.com/clases/1744-practico-css/24717-agregando-imagenes-al-header/)
------------
#### ¿Cuál sería una forma de agregar fuentes a nuestro proyecto?
		 @import url(' ');
###### Razón: @import permite importar reglas desde otras hojas de estilo. Y con url representa la ubicación del recurso a importar. La url puede ser absoluta o relativ
###### Vídeo: [Agregando fuentes](https://platzi.com/clases/1744-practico-css/24707-agregando-fuentes/)
------------
#### ¿Cuál sería una regla en css para limitar el tamaño máximo de algún contenedor?
		 max-width
###### Razón: max-width indica que cuando el valor que se especifique en width sea mayor que max-width, este último sobrescribirá el ancho del elemento al valor que tiene max-width. Así max-width define el ancho máximo que un elemento puede tener
###### Vídeo: [Media queries](https://platzi.com/clases/1744-practico-css/24729-media-queries/)
------------
#### ¿Qué podría esperar al utilizar la regla de “margin: 0 auto;”?
		 Centrar de forma horizontal un contenedor.
###### Razón: En margin: 0 auto , el margen superior / inferior es 0, y el margen izquierdo / derecho es automático, donde auto significa que el navegador establece automáticamente los márgenes izquierdo y derecho en función del contenedor, para centrar el elemento. 
###### Vídeo: [Manejo de Grid para posicionar contenedores](https://platzi.com/clases/1744-practico-css/24705-manejo-de-grid-para-posicionar-contenedores/)
------------
#### ¿De qué forma podría centrar la imágen de fondo?
		 background-position: center;
###### Razón: background-position define la posición inicial de la imagen de fondo especificada.
###### Vídeo: [Agregando imágenes al header](https://platzi.com/clases/1744-practico-css/24717-agregando-imagenes-al-header/)
------------
#### ¿Cómo puedo generar espacio entre las letras de un texto?
		 letter-spacing
###### Razón: letter-spacing establece el comportamiento del espaciado horizontal entre los caracteres del texto.
###### Vídeo: [Terminando el Home](https://platzi.com/clases/1744-practico-css/24708-terminando-el-home/)
------------
#### En nuestro ejemplo del Nav, ¿qué propiedad de CSS utilizamos para posicionar contenido hacia algún extremo?
		 justify-items
###### Razón: justify-items define el justify-self por defecto para todos los elementos de la caja, dándoles a todos una forma por defecto de justificar cada caja a lo largo del eje apropiado.
###### Vídeo: [Arquitectura del header en HTML](https://platzi.com/clases/1744-practico-css/24714-arquitectura-del-header-en-html/)
------------
#### ¿Cuál es la atributo que utilizamos en la etiqueta "a" para crear un hipervínculo?
		 href
###### Razón:  Anchor <a> crea un enlace a otras páginas de internet, archivos o ubicaciones dentro de la misma página, direcciones de correo, o cualquier otra URL.
###### Vídeo: [Agregando íconos](https://platzi.com/clases/1744-practico-css/24716-agregando-iconos/)