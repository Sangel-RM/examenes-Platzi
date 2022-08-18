# Curso de CSS Grid Básico
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### CSS Grid Layout es una especificación de CSS para implementar grillas usando un sistema de tres dimensiones
		 Falso
###### Razón: El CSS grid se puede utilizar para lograr muchos diseños diferentes. También se destaca por permitir dividir una página en áreas o regiones principales, por definir la relación en términos de tamaño, posición y capas. Usando un sistema de dos dimensiones columnas y filas. 
###### Vídeo: [¿Qué es CSS Grid Layout?](https://platzi.com/clases/2474-css-grid/42182-que-es-css-grid-layout/)
------------
#### En un grid usamos las filas y columnas como referencia para ubicar nuestros elementos
		 Verdadero
###### Razón: El CSS grid se puede utilizar para lograr muchos diseños diferentes. También se destaca por permitir dividir una página en áreas o regiones principales, por definir la relación en términos de tamaño, posición y capas. Usando un sistema de dos dimensiones columnas y filas. 
###### Vídeo: [¿Qué es CSS Grid Layout?](https://platzi.com/clases/2474-css-grid/42182-que-es-css-grid-layout/)
------------
#### Las áreas son un grupo de celdas que pueden pertenecer a varias filas o columnas
		 Verdadero
###### Razón: En área pueden usar varias filas o varias columnas al mismo tiempo, mientras que los track son un grupo de celdas que estan en una misma fila o una misma columna 
###### Vídeo: [Conceptos para comenzar](https://platzi.com/clases/2474-css-grid/42183-conceptos-para-comenzar/)
------------
#### Para definir los espacios entre columnas o filas usas la propiedad
		 gap
###### Razón: La propiedad gap ajusta los gaps / espaciado de rows y columns, es un atajo rapido de row-gap y column-gap.
###### Vídeo: [Propiedades del contenedor](https://platzi.com/clases/2474-css-grid/42184-propiedades-del-contenedor/)
------------
#### Para crear un grid de 3 filas y 2 columnas debes usar
		 grid-template-columns: 100px 200px; grid-template-rows: repeat(3, 1fr);
###### Razón: La propiedad grid-template-columns define los nombres de las líneas y las funciones del tamaño del track, y se crean dos columnas una de 100px y 200 px, y lo mismo para rows, con repeat; se repite 3 veces, con un tamaño de 1fr.
###### Vídeo: [Propiedades del contenedor](https://platzi.com/clases/2474-css-grid/42184-propiedades-del-contenedor/)
------------
#### place-items es la propiedad usada para alinear horizontalmente los elementos de la grilla
		 Falso
###### Razón: place-items sirve para alineación de elementos individuales. Para alinear horizontalmente un item se debe usar justify-items.
###### Vídeo: [Propiedades de alineación](https://platzi.com/clases/2474-css-grid/42185-propiedades-de-alineacion/)
------------
#### Si tenemos una grilla de 3x3 y queremos crear un área que ocupe las filas 2 y 3 completas debemos usar
		 2/1/2/4
###### Razón: grid-area especifica un el tamaño y localización de un item del grid. Para grid area hay 4 valores especificados que deben ir en el siguiente orden: grid-row-start/grid-column-start/grid-row-end/grid-column-end
###### Vídeo: [Propiedads de ubicación](https://platzi.com/clases/2474-css-grid/42186-propiedades-de-ubicacion/)
------------
#### grid-column-start y grid-column-end son las propiedades que le indican a un elemento en qué columna comienza y en cuál termina
		 Verdadero
###### Razón: Como el nombre de las propiedades lo dice, estas indican el inicio y fin de la columna en la que será ubicado.
###### Vídeo: [Propiedads de ubicación](https://platzi.com/clases/2474-css-grid/42186-propiedades-de-ubicacion/)
------------
#### Si quieres que una columna tenga un ancho mínimo de 50 pixeles y un máximo definido por la cantidad de contenido debes usar
		 minmax(50px,max-content)
###### Razón: La función minmax() define un rango de tamaña mayor o igual a min, y menor o igual a max. max-content representa la anchura o altura máxima intrínseca del contenido.
###### Vídeo: [Funciones especiales](https://platzi.com/clases/2474-css-grid/42187-funciones-especiales/)
------------
#### Para generar columnas extra que llenen el 100% del espacio disponible pero no sean visibles se usa
		auto-fill
###### Razón: La propiedad autofill agrega columnas "fantasmas" que rellenan el espacio sobrante del contenedor.
###### Vídeo: [Keywords especiales](https://platzi.com/clases/2474-css-grid/42188-keywords-especiales/)
------------
#### Para determinar las columnas y filas de la grilla debemos comenzar por fijarnos en los elementos más grandes a posicionar que se podrían considerar celdas
		 Falso
###### Razón: No es necesario fijarse en los elementos más grandes a posicionar debido a que estos se pueden acomodar con el grid a realizar.
###### Vídeo: [Propiedades del contenedor](https://platzi.com/clases/2474-css-grid/42184-propiedades-del-contenedor/)
------------
#### Los tracks de una grilla son conjuntos de celdas que ocupan varias filas y columnas
		 Falso
###### Razón: En área pueden usar varias filas o varias columnas al mismo tiempo, mientras que los track son un grupo de celdas que estan en una misma fila o una misma columna.
###### Vídeo: [Conceptos para comenzar](https://platzi.com/clases/2474-css-grid/42183-conceptos-para-comenzar/)
------------
#### La propiedad que determina el orden de llenado de la grilla es
		 grid-auto-flow
###### Razón: grid-auto-flow controla el funcionamiento del algoritmo de autocolocación, especificando exactamente cómo se colocan los elementos autocolocados en la cuadrícula.
###### Vídeo: [Propiedades del contenedor](https://platzi.com/clases/2474-css-grid/42184-propiedades-del-contenedor/)
------------
#### En una grilla todos los elementos deben ocupar una sola celda
		 Falso
###### Razón: Un elemento puede ocupar varias celdas.
###### Vídeo: [Propiedades del contenedor](https://platzi.com/clases/2474-css-grid/42184-propiedades-del-contenedor/)
------------
#### Para crear un grid de 3 columnas y 2 filas debes usar
		 grid-template-rows:100px 200px;grid-template-columns:repeat(3,1fr);
###### Razón: Con la propiedad de grid-template-rows se crean 2 filas una de 100px y otra de 200 px, con grid-template-columns, se usa la función repeat(3,1fr) en esta función  se representa un fragmento repetido.
###### Vídeo: [Hagamos nuestra primera sección](https://platzi.com/clases/2474-css-grid/42190-hagamos-nuestra-primera-seccion/)
------------
#### El espacio entre cuatro líneas que representa la unidad mínima que puede tener un grid se llama
		 Celda
###### Razón: Una celda es la unidad de los grids.
###### Vídeo: [Conceptos para comenzar](https://platzi.com/clases/2474-css-grid/42183-conceptos-para-comenzar/)
------------
#### El contenedor de la grilla siempre debe tener la propiedad
		 display: grid
###### Razón: Para poder usar un grid layout, se debe especificar el valor grid, en la propiedad display.
###### Vídeo: [Hagamos nuestra primera sección](https://platzi.com/clases/2474-css-grid/42190-hagamos-nuestra-primera-seccion/)
------------
#### Para crear 3 filas de un mismo ancho debes usar la función
		 repeat(3,1fr)
###### Razón: La función CSS repeat() representa un fragmento repetido de la lista de pistas, lo que permite escribir de forma más compacta un gran número de columnas o filas que presentan un patrón recurrente.
###### Vídeo: [Funciones especiales](https://platzi.com/clases/2474-css-grid/42187-funciones-especiales/)
------------
#### minmax() nos permite determinar el tamaño de una columna o fila usando valores mínimos y máximos como parámetros
		 Verdadero
###### Razón: La función minmax() define un rango de tamaña mayor o igual a min, y menor o igual a max. max-content representa la anchura o altura máxima intrínseca del contenido.
###### Vídeo: [Funciones especiales](https://platzi.com/clases/2474-css-grid/42187-funciones-especiales/)
------------
#### Esta unidad representa una fracción del espacio de la grilla
		 fr
###### Razón:  fr representa una fracción del espacio disponible en el contenedor de la cuadrícula. 
###### Vídeo: [Funciones especiales](https://platzi.com/clases/2474-css-grid/42187-funciones-especiales/)
------------
#### Si un grid tiene la propiedad grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); su comportamiento va a ser
		 Sus columnas se van a ajustar al espacio disponible haciéndose mas anchas o estrechas
###### Razón: Con grid-template-columns se indica cuantas columnas tendrá y su tamaño, en este caso el ancho es auto-fit que hará que el contenido se ajuste al espacio disponible.
###### Vídeo: [Propiedades del contenedor](https://platzi.com/clases/2474-css-grid/42184-propiedades-del-contenedor/)
------------
#### Para ajustar un elemento de la grilla horizontalmente y verticalmente con una sola propiedad se usa
		 place-items
###### Razón: La propiedad place-items permite alinear los elementos a lo largo de las direcciones horizontal y vertical a la vez (es decir, las propiedades align-items y justify-items).
###### Vídeo: [Propiedades de alineación](https://platzi.com/clases/2474-css-grid/42185-propiedades-de-alineacion/)
------------
#### ¿Qué características tendría una grilla creada con el siguiente código? display: grid; gap: 10px; align-content: center; height: 800px; grid-template-columns: minmax(50px, 100px) minmax(100px, auto); grid-auto-rows: 50px;
		 Todas las opciones son correctas
###### Razón: El grid tendría dos columnas, sus filas serían de 50px, estarían centradas verticalmente y el espaciado entre filas y columnas sería de 10px.
###### Vídeo: [Creando la grilla con área](https://platzi.com/clases/2474-css-grid/42191-creando-la-grilla-con-area/)
------------
#### Para definir el tamaño de los espacios entre columnas de la grilla debes usar row-gap
		 Falso
###### Razón:  row-gap establece el tamaño del espacio entre las filas de un elemento. Si se desea definir el espacio entre columnas se debe usar column-gap
###### Vídeo: [Creando la grilla con área](https://platzi.com/clases/2474-css-grid/42191-creando-la-grilla-con-area/)
------------
#### Para crear 3 columnas de 3 fracciones de ancho del espacio disponible debes usar
		 repeat(3, 3fr)
###### Razón: La función CSS repeat() representa un fragmento repetido de la lista de pistas, lo que permite escribir de forma más compacta un gran número de columnas o filas que presentan un patrón recurrente.
###### Vídeo: [Funciones especiales](https://platzi.com/clases/2474-css-grid/42187-funciones-especiales/)
------------
#### Ítems es el nombre que se le da a los hijos del contenedor
		 Verdadero
###### Razón: Los items son los elementos contenidos en el contenedor.
###### Vídeo: [Conceptos para comenzar](https://platzi.com/clases/2474-css-grid/42183-conceptos-para-comenzar/)
------------