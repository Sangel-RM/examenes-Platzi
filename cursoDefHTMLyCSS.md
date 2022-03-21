# Curso Definitivo de HTML y CSS
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Cuál es el tamaño promedio de una imagen para su uso en la web?
		 70kb
###### Razón: 70 Kilobytes es el tamaño recomendado para las imágenes, debido a que si son imágenes con pesos superiores harán que se ralentice la carga de la página.
###### Vídeo: [Optimización de imágenes](https://platzi.com/clases/2008-html-css/31083-optimizacion-de-imagenes/ "Optimización de imágenes")
------------
#### ¿Cuál es una de las principales diferencias de una página estática a una dinámica?
		 Las páginas estáticas son sólo informativas. 
###### Razón:  La información que contiene, se mantiene constante y estática. No se actualiza con la interacción del usuario. Conveniente para landing pages (Páginas informativas) o Blogs. Serán siempre iguales para todos los usuarios.
###### Vídeo: [Páginas Estáticas vs. Dinámicas](https://platzi.com/clases/2008-html-css/31090-paginas-estaticas-vs-dinamicas/ "Páginas Estáticas vs. Dinámicas")
------------
#### ¿Cuál es la etiqueta de HTML que se utiliza como contenedor del contenido principal?
		 main
###### Razón: < main> representa el contenido principal del < body> de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación.
###### Vídeo: [HTML: anatomía de una página web](https://platzi.com/clases/2008-html-css/31089-html-anatomia-de-una-pagina-web/ "HTML: anatomía de una página web")
------------
#### ¿Qué formato de imagen utilizaremos para fotos?
 		 JPG
###### Razón: : Formato de imagen con pérdida, perdemos calidad a la hora de comprimirlas, pero llegan a ser óptimas para la carga en la página web.
###### Vídeo: [Tipos de imágenes](https://platzi.com/clases/2008-html-css/31084-tipos-de-imagenes/ "Tipos de imágenes")
------------
#### ¿Qué formato de imagen es ideal para utilizar con transparente?
		 PNG
###### Razón: PNG (Portable Network Graphics) es un formato de imagen sin pérdida, uso de colores de 256, se utiliza para logotipos e iconos para la página. 
###### Vídeo: [Tipos de imágenes](https://platzi.com/clases/2008-html-css/31084-tipos-de-imagenes/ "Tipos de imágenes")
------------
#### ¿A qué nos referimos cuando decimos que una imagen es categoría Lossy?
		 Son imágenes que reducen la cantidad de colores y eliminan datos necesarios para recortar su tamaño.
###### Razón: Los formatos de imagen con pérdida se aproximan a su imagen original. Por ejemplo, una imagen con pérdida podría reducir la cantidad de colores en su imagen o analizar la imagen en busca de datos innecesarios. Estos reducirá el tamaño del archivo, aunque pueden reducir la calidad de su imagen
###### Vídeo: [Tipos de imágenes](https://platzi.com/clases/2008-html-css/31084-tipos-de-imagenes/ "Tipos de imágenes")
------------
#### ¿Cuál es la paleta de colores en una imagen PNG 8?
		 Máximo 256 colores
###### Razón: PNG 8 (Portable Network Graphics): Formato de imagen sin pérdida, uso de colores de 256, se utiliza para logotipos e iconos para la página.
###### Vídeo: [Tipos de imágenes](https://platzi.com/clases/2008-html-css/31084-tipos-de-imagenes/ "Tipos de imágenes")
------------
#### ¿Cuál es la paleta de colores en una imagen JPG?
		 Millones de colores
###### Razón: JPG / JPEG (Photographic Experts Group): Formato de imagen con pérdida, perdemos calidad a la hora de comprimirlas, pero llegan a ser óptimas para la carga en la página web. Puede mostrar millones de colores, usa un complejo algoritmo de comprensión.
###### Vídeo: [Tipos de imágenes](https://platzi.com/clases/2008-html-css/31084-tipos-de-imagenes/ "Tipos de imágenes")
------------
#### ¿Cuál es la principal diferencia de una pseudo clase?
		 Definen el estilo de un estado especial de un elemento.
###### Razón: Una pseudoclase CSS es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado. Por ejemplo,  :hover aplicará un estilo cuando el usuario haga hover sobre el elemento especificado por el selector. [Pseudo clases y pseudo elementos](https://developer.mozilla.org/es/d "Pseudo clases y pseudo elementos")
###### Vídeo: [Pseudo clases y pseudo elementos](https://platzi.com/clases/2008-html-css/31072-pseudo-clases-y-pseudo-elementos/ "Pseudo clases y pseudo elementos")
------------
#### ¿Cuál es la principal diferencia de un pseudo elemento?
		 Definen el estilo de una parte específica de un elemento.
###### Razón: Los pseudo-elementos se añaden a los selectores, pero en cambio, no describen un estado especial sino que, permiten añadir estilos a una parte concreta del documento. Por ejemplo, el pseudoelemento ::first-line selecciona solo la primera línea del elemento especificado por el selector.
###### Vídeo: [Pseudo clases y pseudo elementos](https://platzi.com/clases/2008-html-css/31072-pseudo-clases-y-pseudo-elementos/ "Pseudo clases y pseudo elementos")
------------
#### ¿Cuál es el orden correcto de declaración en CSS?
		 Importancia, especificidad y orden en las fuentes
###### Razón: La especificidad es la manera mediante la cual los navegadores deciden qué valores de una propiedad CSS son más relevantes para un elemento y, por lo tanto, serán aplicados. La especificidad está basada en las reglas de coincidencia que están compuestas por diferentes tipos de selectores CSS. Orden de declaración en CSS: 
###### - Importancia: Hoja de estilo de agente de usuario (Estilos del navegador): primero el navegador va a implementar los estilos que ya trae por defecto. Declaraciones normales en hojas de estilo de autor (nuestro .css) que son los estilos que nosotros colocamos en nuestro proyecto. Declaraciones importantes en hojas de estilos de autor (utilizar el !important)
###### - Especificidad: !important, inline styles, #id, .class, tag.
###### - Orden de las fuentes: Las declaraciones finales son las que se se van a ejecutar en el caso que los estilos tienen la misma especificidad. 
###### Vídeo: [Especificidad en selectores](https://platzi.com/clases/2008-html-css/31068-especificidad-en-selectores/)
------------
#### ¿Cuál de estos selectores o regla es más importante para CSS?
		 !important
###### Razón: Orden de especificidad: !important, inline styles, #id, .class, tag. Mientras más espécífico sea, mayor importancia le dará CSS, y todos los estilos que le sigan debajo de otros serán reemplazados en dado caso de que tengan la misma especificidad.
###### Vídeo: [Especificidad en selectores](https://platzi.com/clases/2008-html-css/31068-especificidad-en-selectores/)
------------
#### ¿Cual de estas declaraciones tiene más peso en CSS?
		 #id
###### Razón: Orden de especificidad: !important, inline styles, #id, .class, tag. Mientras más espécífico sea, mayor importancia le dará CSS, y todos los estilos que le sigan debajo de otros serán reemplazados en dado caso de que tengan la misma especificidad.
###### Vídeo: [Especificidad en selectores](https://platzi.com/clases/2008-html-css/31068-especificidad-en-selectores/)
------------
#### ¿Qué símbolo representa al combinador General Sibling (Hermano general)?
		 ~
###### Razón: El combinador ~ separa dos selectores y selecciona el segundo elemento sólo si está precedido por el primero y ambos comparten un padre común. [Selectores de hermanos generales](https://developer.mozilla.org/es/docs/Web/CSS/General_sibling_combinator "Selectores de hermanos generales")
###### Vídeo: [Combinadores: General Sibling](https://platzi.com/clases/2008-html-css/31064-combinadores-general-sibling/ "Combinadores: General Sibling")
------------
#### ¿Qué símbolo representa al combinador Adjacent Sibling (Hermano cercano)?
		 +
###### Razón: El combinador hermano adyacente ( +) separa dos selectores y coincide con el segundo elemento solo si sigue inmediatamente al primer elemento, y ambos son hijos del mismo padre element. [Selectores de hermanos adyacentes](https://developer.mozilla.org/es/docs/Web/CSS/Adjacent_sibling_combinator "Selectores de hermanos adyacentes")
###### Vídeo: [Combinadores: Adjacent Siblings (combinators)](https://platzi.com/clases/2008-html-css/31065-combinadores-adjacent-siblings-combinators/ "Combinadores: Adjacent Siblings (combinators)")
------------
#### ¿Qué significa REM?
		 Root element font-size
###### Razón: Funciona igual que el em, con la diferencia que es relativo al valor de la fuente del elemento html, y no tiene en cuenta el valor heredado o del elemento que lo contiene. Por defecto el html viene con un tamaño de fuente de 16px asi que 1 REM  = 16 PX.
###### Vídeo: [Medidas REM](https://platzi.com/clases/2008-html-css/31060-medidas-rem/ "Medidas REM")
------------
#### ¿Cuales de estas es una medida absoluta?
		 px
###### Razón: El valor de este no cambia y siempre sera el mismo asi la página cambie su tamaño.
###### Vídeo: [Medidas](https://platzi.com/clases/2008-html-css/31062-medidas/ "Medidas")
------------
#### ¿Cuál es la posición que viene por defecto en todos los elementos de HTML?
		 static
###### Razón: Posición por defecto de los elementos, conservan la posición y espacio de donde son colocados (estáticos). No se puede usar top, right, bottom y left en esta posición.
###### Vídeo: [Position](https://platzi.com/clases/2008-html-css/31058-position/ "Position")
------------
#### ¿Cuál es la diferencia entre display block e inline?
		 Inline: muestra en la misma línea (respetando el flujo) todos los elementos y no acepta las propiedades width, height ni márgenes verticales. Block: muestra los elementos en líneas independientes y acepta las propiedades width, height y márgenes verticales.
###### Razón: En un elemento con display:inline no es posible usar margin ni padding bottom ni top, solo right e left. Tampoco se puede aplicar width o height. En un elemento con display:block el contenido del elemento toma el 100% del width, se puede usar margin y padding por todos los lados.
###### Vídeo: [Display](https://platzi.com/clases/2008-html-css/31057-display/ "Display")
------------
#### ¿Al estar utilizando Display Flex, cómo puedo alinear de forma vertical a los elementos hijos?
		 align-items: center;
###### Razón: align-items establece el valor align-self sobre todos los descendientes directos de un grupo. La propiedad align-self indica la alineación de un elemento dentro del bloque que lo contiene. [align-items](https://developer.mozilla.org/es/docs/Web/CSS/align-items "align-items")
###### Vídeo: [Flexbox layouts](https://platzi.com/clases/2008-html-css/31231-flexbox-layouts/ "Flexbox layouts")
------------
#### ¿Por qué es importante utilizar siempre medidas relativas en fuentes?
		 Para que usuarios con problemas de visibilidad puedan incrementar el tamaño de fuente en caso de que lo necesiten.
###### Razón: Se deben usar medidas relativas como rem, para poder incrementar el tamaño del texto para personas con problemas de visión. Las opciones de navegador que cambian el tamaño de las fuentes no funcionan cuando las fuentes de html en el texto están en pixeles (px)
###### Vídeo: [Textos](https://platzi.com/clases/2008-html-css/31220-textos/ "Textos")
------------
#### ¿Para qué utilizamos la regla de box-sizing: border-box; en nuestros estilos?
		 Nos ayuda a decirle al navegador que tenga en cuenta el border y padding en los valores que especifique para el width y height de un elemento. Esto normalmente hace que sea mucho más fácil dimensionar elementos.
###### Razón:  Le dice al navegador tomar en cuenta para cualquier valor que se especifique de borde o de relleno para el ancho o alto de un elemento. Es decir, si se define un elemento con un ancho de 100 pixeles. Esos 100 pixeles incluíran cualquier borde o relleno que se añadan, y la caja de contenido se encogerá para absorber ese ancho extra. Esto típicamente hace mucho más fácil dimensionar elementos.
###### Vídeo: [Modelo de caja](https://platzi.com/clases/2008-html-css/31070-modelo-de-caja/ "Modelo de caja")
------------
#### ¿Cuál es la diferencia entre rem y em?
		 rem toma como medida base el tamaño de fuente que está en el elemento root que sería la etiqueta html, y em toma como medida base el tamaño de fuente de su padre directo.
###### Razón: Funciona igual que el em, con la diferencia que es relativo al valor de la fuente del elemento html, y no tiene en cuenta el valor heredado o del elemento que lo contiene. Por defecto el html viene con un tamaño de fuente de 16px asi que 1 REM  = 16 PX.
###### Vídeo: [Medidas REM](https://platzi.com/clases/2008-html-css/31060-medidas-rem/ "Medidas REM")
------------
#### Si estoy creando un formulario y quiero preguntar por una fecha y hora exacta, cuál sería la mejor forma de hacerlo?
		 Input type=”datetime-local”
###### Razón: Este tipo de elemento permite escoger una fecha y hora, sin especificar la zona horaria en la que se encuentra. 
###### Vídeo: [Etiqueta form e input](https://platzi.com/clases/2008-html-css/31079-etiqueta-form-e-input/ "Etiqueta form e input")
------------
#### ¿Cuál es la forma de pedirle al navegador que nos ayude en llenar la información que el usuario utiliza de forma frecuente en formularios?
		 Utilizando el atributo autocomplete y el valor que buscamos.
###### Razón: El atributo autocomplete = “tipo-del-input” hace que el navegador auto-complete los formularios, según el tipo de input. El atributo se coloca en la etiqueta < input>.
###### Vídeo: [Autocomplete y require](https://platzi.com/clases/2008-html-css/31078-autocomplete-y-require/ "Autocomplete y require")
------------
#### ¿Qué meta utilizamos para asegurar una buena experiencia en responsive?
		 meta name="viewport" content="width=device-width, initial-scale=1"
###### Razón: Es la configuración para que la página se vea bien en todos los dispositivos.
###### Vídeo: [Index y su estructura básica: head](https://platzi.com/clases/2008-html-css/31088-index-y-su-estructura-basica-head/ "Index y su estructura básica: head")
------------
#### ¿Para qué utilizamos el atributo alt en las etiquetas img?
		 Con position: relative; podemos posicionar un elemento respecto al flujo normal de la página. Con position: absolute; el elemento no estará dentro del flujo normal de la página y tomará como referencia la ventana del navegador o el elemento padre posicionado más cercano.
###### Razón: El atributo alt en las imágenes proporciona una descripción para un screen readers.
###### Vídeo: [Labels, alt y title](https://platzi.com/clases/2008-html-css/31219-labels-alt-y-title/ "Labels, alt y title")
------------
#### ¿Cuál es el tamaño de fuente que viene por defecto en el navegador?
		 16 px
###### Razón: Por defecto el font size de los navegadores viene con un tamaño de fuente de 16px.
###### Vídeo: [Medidas](https://platzi.com/clases/2008-html-css/31062-medidas/ "Medidas")
------------
#### ¿Cuál de estos no es un patrón de diseño responsive?
		 Layout fluid
###### Razón: Los patrones en Reponsive Design: Mostly Fluid, Colocación de columnas, Layout shifter, Tiny tweaks, Off canvas
###### Vídeo: [Responsive design: media queries](https://platzi.com/clases/2008-html-css/31228-responsive-design-media-queries/ "Responsive design: media queries")