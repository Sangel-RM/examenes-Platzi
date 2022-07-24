# Curso Básico de Tailwind 2 y 3
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### Define un framework
		 Es un conjunto de herramientas para construir una interfaz web con CSS, que nos permite agilizar el desarrollo.
###### Razón: Un framework de CSS es una biblioteca de estilos genéricos que puede ser usada para implementar diseños web. Aportan una serie de utilidades que pueden ser aprovechadas frecuentemente en los distintos diseños web.
###### Vídeo: [¿Cómo funciona Tailwind? Y otros frameworks de CSS](https://platzi.com/clases/2702-tailwind/45490-como-funciona-tailwind-y-otros-frameworks-de-css/)
------------
#### ¿Cuáles son las ventajas de un framework basado en el principio de utility first?
		 Permite tener una estructura más ordenada y agiliza el desarrollo
###### Razón:  El principio Utility First esta basado en utilidades el cuál permite tener una estructura más limpia de los estilos, el desarrollo es más rápido ya que todo se trabaja dentro del mismo archivo. Es la forma en que se nombran y se crean las clases de estilos. Se trata de construir componentes a partir de clases con nombres descriptivos.
###### Vídeo: [Mobile First y Utility First](https://platzi.com/clases/2702-tailwind/45491-mobile-first-y-utility-first/)
------------
#### Menciona 2 ventajas de utilizar tailwind mediante instalación en lugar de CDN
		 Es posible crear un archivo de configuración y personalizar clases. Se puede hacer uso de todas las directivas de tailwind
###### Razón: Usar Tailwind por CDN solo es para fines de desarrollo, no es la mejor opción para la producción. En cambio al instalar Tailwind permite sobre escribir los estilos.
###### Vídeo: [Creación del proyecto e instalación de Tailwind](https://platzi.com/clases/2702-tailwind/45492-creacion-del-proyecto-e-instalacion-de-tailwind/)
------------
#### Menciona 3 directivas vistas en clase
		 @tailwind base; @tailwind components; @tailwind utilities;
###### Razón: Directiva es una instrucción que utiliza tailwind para insertar código en el archivo final de css que genera. Esto inyecta los estilos base de Tailwind y cualquier estilo base registrado por plugins. Esto inyecta las clases de componentes de Tailwind y cualquier clase de componente registrado por los plugins.
###### Vídeo: [Directivas de Tailwind](https://platzi.com/clases/2702-tailwind/45493-directivas-de-tailwind/)
------------
#### ¿Cuál es la manera correcta de agregar un color al fondo?
		 bg-red-200
###### Razón: Para colocar un color de fondo, se usa la clase bg-color-intensidad, bg-gray-600 [Background Color](https://tailwindcss.com/docs/background-color)
###### Vídeo: [Nueva paleta de colores extendida](https://platzi.com/clases/2702-tailwind/45494-nueva-paleta-de-colores-extendida/)
------------
#### ¿Qué es un breakpoint?
		 Un breakpoint es el salto en el que cambia la pantalla de Layout.
###### Razón: Un breakpoint son las medidas de anchura en donde se realizan saltos para el diseño responsive y se aplican los estilos CSS concretos para unas determinadas media queries. Es decir, los breakpoints son los saltos en los que la pantalla cambia de layout.
###### Vídeo: [Medidas y Breakpoints](https://platzi.com/clases/2702-tailwind/45495-medidas-y-breakpoints/)
------------
#### Las medidas más comunes dentro de tailwind son: sm, md,lg, xl
		 verdadero
###### Razón: Las medidas que tailwind maneja son sm =small ,md = medium ,lg = large,xl =extra large [Font Size](https://tailwindcss.com/docs/font-size)
###### Vídeo: [Medidas y Breakpoints](https://platzi.com/clases/2702-tailwind/45495-medidas-y-breakpoints/)
------------
#### En el archivo de configuración es dónde se trabajan todos los estilos del proyecto
		 Falso
###### Razón: Los estilos del proyecto son realizados en las clases html que se diseñen.
###### Vídeo: [Creación del proyecto e instalación de Tailwind](https://platzi.com/clases/2702-tailwind/45492-creacion-del-proyecto-e-instalacion-de-tailwind/)
------------
#### ¿Con qué directiva es posible agrupar clases para extraerlas a un componente?
		 @apply
###### Razón: La directiva @apply permite escribir CSS personalizado, agrupandolo para usarlo como clases en distintos componentes.
###### Vídeo: [Extracción de componentes a clases para nuestra card](https://platzi.com/clases/2702-tailwind/45503-extraccion-de-componentes-a-clases-para-nuestra-ca/)
------------
#### ¿Cómo funciona flexbox?
		 Funciona principalmente con filas y columnas
###### Razón: Flexbox esta diseñado como un modelo unidimensional de layout, y como un método que pueda ayudar a distribuir el espacio entre los ítems de una interfaz y mejorar las capacidades de alineación.
###### Vídeo: [Flexbox](https://platzi.com/clases/2702-tailwind/45496-flexbox-y-grid/)
------------
#### ¿Cuál es el nombre del archivo de configuración?
		 tailwind.config.js
###### Razón: El archivo de configuración se llama tailwind.config.js, este es diseñado para añadir una propia paleta de colores, configurar el modo oscuro, agregar las rutas de las plantillas. [Presets](https://tailwindcss.com/docs/presets#merging-logic-in-depth)
###### Vídeo: [Creación del proyecto e instalación de Tailwind](https://platzi.com/clases/2702-tailwind/45492-creacion-del-proyecto-e-instalacion-de-tailwind/)
------------
#### ¿Con cuál clase se inicializan las transiciones dentro de tailwind?
		 transition
###### Razón: Para agregar una transición al componente, se usa la clase transition [Transition Property](https://tailwindcss.com/docs/transition-property)
###### Vídeo: [Agregando animaciones al proyecto](https://platzi.com/clases/2702-tailwind/45505-agregando-animaciones-al-proyecto/)
------------
#### ¿Cuál de las siguientes clases nos permite que nuestros elementos se comporten en fila con un espaciado horizontal entre los elementos?
		flex space-x-4
###### Razón: Para agregar espaciado horizontal entre los elementos se usa la clase space-x-valor[Space Between](https://tailwindcss.com/docs/space)
###### Vídeo: [Creando la sección de Recomendados](https://platzi.com/clases/2702-tailwind/45504-creando-la-seccion-de-recomendados/)
------------
#### Dentro del proyecto se utiliza el dark mode configurado mediante la clase dark
		 verdadero
###### Razón: Para configurar el mode oscuro, se hace a través del archivo tailwind.config.js. [Dark Mode](https://tailwindcss.com/docs/dark-mode)
###### Vídeo: [Agregando el Dark Mode](https://platzi.com/clases/2702-tailwind/45513-agregando-el-dark-mode/)
------------
#### ¿Cómo especificamos los estilos para versión web del proyecto?
		 Especificando el breakpoint antes de agregar las clases ej. lg:w-full lg:h-full
###### Razón: Para especificar como se comportará en una pantalla específicar se usa el nombre de la clase del breakpoint, luego el comportamiento. [Customizing Screens](https://tailwindcss.com/docs/screens)
###### Vídeo: [Haciendo responsivo nuestro proyecto: rentas destacadas](https://platzi.com/clases/2702-tailwind/45511-haciendo-responsivo-nuestro-proyecto-rentas-destac/)