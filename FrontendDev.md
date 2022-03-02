# Curso de Frontend Developer
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### HTML es un lenguaje de marcado de hipertexto. Este enunciado es:
		 Verdadero
###### Razón: HTML, siglas en inglés de HyperText Markup Language, hace referencia al lenguaje de marcado para la elaboración de páginas web
###### Vídeo: [¿Qué es HTML y CSS? ¿Para qué sirven?](https://platzi.com/clases/2467-frontend-developer/40829-que-es-html-y-css-para-que-sirven/ "¿Qué es HTML y CSS? ¿Para qué sirven?")
------------
#### CSS son hojas de estilo en cascada. Este enunciado es:
		 Verdadero
###### Razón: Son siglas en inglés de Cascading Style Sheets u Hoja de estilos en cascada, ayuda a darle estilos a los componentes de la estructura de HTML.
###### Vídeo: [¿Qué es HTML y CSS? ¿Para qué sirven?](https://platzi.com/clases/2467-frontend-developer/40829-que-es-html-y-css-para-que-sirven/ "¿Qué es HTML y CSS? ¿Para qué sirven?")
------------
#### ¿Para qué nos sirven los motores de renderizado?
		 Para pasar los archivos a píxeles en pantalla.
###### Razón: Pasa los archivos de HTML a objetos (El DOM). Esto para que el navegador pueda entenderlo. Calcula el estilo correspondiente a cada nodo en el DOM. Calcula las dimensiones de cada nodo y va a empezar a estructurar la página web. Pinta las diferentes cajas. Toma las capas y las convierte en una imagen, para finalmente mostrar esta imagen en la pantalla
###### Vídeo: [Motores de render: de archivos a píxeles](https://platzi.com/clases/2467-frontend-developer/40830-motores-de-render-de-archivos-a-pixeles/ "Motores de render: de archivos a píxeles")
------------
#### Un ejemplo de elemento vacío en HTML es:
		 <img>
###### Razón: Un elemento vacío es un elemento de HTML,  que no puede tener nodos secundarios (es decir, elementos anidados o nodos de texto).
###### Vídeo: [Anatomía de un documento HTML y sus elementos](https://platzi.com/clases/2467-frontend-developer/40831-anatomia-de-un-documento-html-y-sus-elementos/ "Anatomía de un documento HTML y sus elementos")
------------
#### El HTML semántico NO nos permite:
		 Determinar qué reglas de CSS deben aplicarse a las etiquetas de HTML
###### Razón: El html semántico indica las propiedades adecuadas que se deben usar para los textos, párrafos, imágenes, secciones, etc. Al hacer esto vamos a lograr tener un código accesible, tenemos el tema de posicionamiento SEO, nos permite tener un código mucho más claro, ligero y fácil de leer.
###### Vídeo: [¿Qué es HTML semántico?](https://platzi.com/clases/2467-frontend-developer/40832-que-es-html-semantico/ "¿Qué es HTML semántico?")
------------
#### Con HTML semántico, usar una etiqueta < div> en lugar de una específica como < article> para escribir un artículo es:
		 Incorrecto
###### Razón: El html semántico indica las propiedades adecuadas que se deben usar para los textos, párrafos, imágenes, secciones, etc. Se debe saber en que momento se ponen ciertas etiquetas y cual es su funcionamiento.
###### Vídeo: [¿Qué es HTML semántico?](https://platzi.com/clases/2467-frontend-developer/40832-que-es-html-semantico/ "¿Qué es HTML semántico?")
------------
#### La definición de "cascada" significa que:
		 El orden de las reglas en CSS importa.
###### Razón: Significa que el orden de las reglas CSS importa; cuando se aplican dos reglas que tienen igual especificidad, la que viene en último lugar en el CSS es la que se utilizará.
###### Vídeo: [Cascada y especificidad en CSS](https://platzi.com/clases/2467-frontend-developer/40837-cascada-y-especificidad-en-css/ "Cascada y especificidad en CSS")
------------
#### Las reglas de CSS que tienen menor especificidad (sin tener en cuenta el selector universal), son:
		 Elementos y pseudoelementos.
###### Razón: Posterior al selector universal, sigue los elementos pseudoelementos, Clases-atributos-pseudoclases, #ID, estilos en linea, ¡important
###### Vídeo: [Cascada y especificidad en CSS](https://platzi.com/clases/2467-frontend-developer/40837-cascada-y-especificidad-en-css/ "Cascada y especificidad en CSS")
------------
#### #id h1::first-letter es más específico que p .sidemenu div:hover
		 verdadero
###### Razón: Es verdero debido a que los #id son mas importantes que los elementos y pseudoelementos.
###### Vídeo: [Cascada y especificidad en CSS](https://platzi.com/clases/2467-frontend-developer/40837-cascada-y-especificidad-en-css/ "Cascada y especificidad en CSS")
------------
#### ¿Cuál de los siguientes NO es un tipo de selector combinador?
		 a[href="…"]
###### Razón:  a[href="…"] es un selector básico de atributo. [Selectores de atributos](https://developer.mozilla.org/es/docs/Web/CSS/Attribute_selectors "Selectores de atributos")
###### Vídeo: [Tipos de selectores: básicos y combinadores](https://platzi.com/clases/2467-frontend-developer/40835-tipos-de-selectores-basicos-y-combinadores/ "Tipos de selectores: básicos y combinadores")
------------
#### El colapso de márgenes sucede cuando:
		 Hay dos elementos bloque adyacentes.
###### Razón: Sucede con las margenes verticales de los elementos en bloque (contenedores), el colapso de margenes verticales significa que dichas margenes se solapan, osea, se pone un margen encima de otro. el colapsado de margenes verticales no ocurre en elementos en bloque que tengan los atributos flexbox o grid.
###### Vídeo: [Colapso de márgenes](https://platzi.com/clases/2467-frontend-developer/40957-colapso-de-margenes/ "Colapso de márgenes")
------------
#### La metodología que nos sugiere tener una sintaxis donde se pueda diferenciar el bloque de los elementos y de los modificadores es:
		 BEM
###### Razón: La metodología BEM divide la interfaz de usuario en bloques independientes para crear componentes escalables y reutilizables.
###### Vídeo: [OOCSS, BEM, SMACSS, ITCSS y Atomic Design](https://platzi.com/clases/2467-frontend-developer/40847-oocss-bem-smacss-itcss-y-atomic-design/ "OOCSS, BEM, SMACSS, ITCSS y Atomic Design")
------------
#### :hover es:
		 Una pseudoclase
###### Razón: Una pseudoclase CSS es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado. Por ejemplo,  :hover aplicará un estilo cuando el usuario haga hover sobre el elemento especificado por el selector. [Pseudo-classes](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes "Pseudo-classes")
###### Vídeo: [Tipos de selectores: pseudoclases y pseudoelementos](https://platzi.com/clases/2467-frontend-developer/40836-tipos-de-selectores-pseudoclases-y-pseudoelementos/ "Tipos de selectores: pseudoclases y pseudoelementos")
------------
#### ¿Qué es ::before?
		 Un pseudoelemento
###### Razón: Los pseudo-elementos se añaden a los selectores, pero en cambio, no describen un estado especial sino que, permiten añadir estilos a una parte concreta del documento. Por ejemplo, el pseudoelemento ::first-line selecciona solo la primera línea del elemento especificado por el selector. [Pseudoelementos](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-elements "Pseudoelementos")
###### Vídeo: [Tipos de selectores: pseudoclases y pseudoelementos](https://platzi.com/clases/2467-frontend-developer/40836-tipos-de-selectores-pseudoclases-y-pseudoelementos/ "Tipos de selectores: pseudoclases y pseudoelementos")
------------
#### El selector que selecciona todos los elementos < span> donde el padre es un elemento < p> es:
		 p > span
###### Razón: El simbolo > es un selector combinador que solo agarrará a los hijos que este directamente adentro del padre. [Selectores combinadores](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/Selectors/Combinators "Selectores combinadores")
###### Vídeo: [Tipos de selectores: básicos y combinadores](https://platzi.com/clases/2467-frontend-developer/40835-tipos-de-selectores-basicos-y-combinadores/ "Tipos de selectores: básicos y combinadores")
------------
#### Si debes de colocar una barra de navegación con HTML semántico, ¿cuál etiqueta usarías?
		<nav>
###### Razón: < nav> representa una sección de una página cuyo propósito es proporcionar enlaces de navegación, ya sea dentro del documento actual o a otros documentos. Ejemplos comunes de secciones de navegación son menús, tablas de contenido e índices.
###### Vídeo: [¿Qué es HTML semántico?](https://platzi.com/clases/2467-frontend-developer/40832-que-es-html-semantico/ "¿Qué es HTML semántico?")