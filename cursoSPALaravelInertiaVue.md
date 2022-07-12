# Curso de Single Page Applications en Laravel con Inertia y Vue.js
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Qué es Inertia.js?
		 Es lo que nos permite usar a Vue con el poder de las rutas en Laravel.
###### Razón: Inertiajs es una librería que combina lo mejor del server side render y client side render, permitiéndonos construir SPAs usando el render clásico de vistas, controladores y el routing del backend, sin tener que definir una API y un sistema de routing en el frontend.
###### Vídeo: [Introducción a Jetstream](https://platzi.com/clases/2183-laravel-spa/35250-introduccion-a-jetstream/)
------------
#### ¿Cuál es el objetivo de Laravel?
		 Ser un Framework que te permita una sintaxis elegante y expresiva.
###### Razón: El objetivo de Laravel es el de ser un framework que permita el uso de una sintaxis refinada y expresiva para crear código de forma sencilla, evitando el «código espagueti» y permitiendo multitud de funcionalidades.
###### Vídeo: [Sistema basado en componentes](https://platzi.com/clases/2183-laravel-spa/35253-sistema-basado-en-componentes/)
------------
#### ¿Dónde se guardan las vistas cuando usamos Inertia?
		 resources/js
###### Razón: Los archivos de la vista al usar Inertia son guardados en resources/js
###### Vídeo: [Jetstream: configuración inicial](https://platzi.com/clases/2183-laravel-spa/35254-jetstream-configuracion-inicial/)
------------
#### ¿Cuál es el uso del comando npm run watch?
		 Genera un archivo js pero permanece activo y "observa" las actualizacioneso futuros cambios.
###### Razón: npm run watch compila los cambios realizacos en tiempo real, para la aplicación de cambios inmediatos.
###### Vídeo: [Jetstream: personalización](https://platzi.com/clases/2183-laravel-spa/35255-jetstream-personalizacion/)
------------
#### ¿Cómo lanzamos una vista escrita en Vue.js?
		 Con Inertia\Inertia::render()
###### Razón: Al usar Inertia, las rutas de la aplicación responderan renderizando una página de inerta, con el método render().
###### Vídeo: [Listado de notas: configuración inicial](https://platzi.com/clases/2183-laravel-spa/35256-listado-de-notas-configuracion-inicial/)
------------
#### ¿Cómo creamos un enlace al trabajar con Inertia?
		 Con la etiqueta <inertia-link>.
###### Razón: Para crear hipervinculos en Vue se hacen inertia-link, en Vue 3 esto cambia a <Link :href="" ></Link>
###### Vídeo: [Listado de notas: personalización](https://platzi.com/clases/2183-laravel-spa/35257-listado-de-notas-personalizacion/)
------------
#### ¿En qué propiedad de Vue.js recibimos los datos?
		 props
###### Razón: Los props sirven para para pasar información desde un componente padre a un componente hijo, también se pueden pasar props a una ruta cualquiera siempre y cuando estén activados. A partir de Vue 3 los props se definen a través de una constante const props = defineProps({ notes : Array, });
###### Vídeo: [Listado de notas: personalización](https://platzi.com/clases/2183-laravel-spa/35257-listado-de-notas-personalizacion/)
------------
#### ¿Qué método de Inertia usamos para configurar los flash message?
		 share
###### Razón: Los mensajes flash son usados para notificar al usuario sobre el estado de acciones que ha hecho o simplemente muestra información a los usuarios. Con inertia se puede realizar gracias al metodo share.
###### Vídeo: [Flash message](https://platzi.com/clases/2183-laravel-spa/35264-flash-message/)
------------
#### ¿Cómo enviamos un flash message desde un controlador?
		 Con el método with()
###### Razón: En el controlador se puede enviar el flash message con el método with pasandole el nombre del flash message, with('status', 'Nota eliminada');
###### Vídeo: [Flash message](https://platzi.com/clases/2183-laravel-spa/35264-flash-message/)
------------
#### ¿Qué método usamos para alterar la URL sin refrescar la página?
		 replace
###### Razón: Actualmente replace es un método obsoleto, que fue reemplazo por get. Y así evitar que se recargue la página al buscar.
###### Vídeo: [Buscador](https://platzi.com/clases/2183-laravel-spa/35266-buscador/)
------------
#### ¿Cuál es el motor de plantillas al usar Inertia?
		 Vue.js
###### Razón: El motr de plantillas de Inertia es Vue.js, y de Livewire es Blade.
###### Vídeo: [Cómo aprenderás a crear SPAs en Laravel](https://platzi.com/clases/2183-laravel-spa/35249-presentacion-del-curso/)
------------
#### ¿Qué enrutador usamos al trabajar con Inertia?
		 Sistema de rutas de Laravel.
###### Razón: Inertiajs es una librería que combina lo mejor del server side render y client side render, permitiéndonos construir SPAs usando el render clásico de vistas, controladores y el routing del backend, sin tener que definir una API y un sistema de routing en el frontend.
###### Vídeo: [Introducción a Jetstream](https://platzi.com/clases/2183-laravel-spa/35250-introduccion-a-jetstream/)
------------
#### ¿Qué nos brinda Inertia?
		 El poder de Vue.js sin la complejidad del enrutador del lado del cliente.
###### Razón: Inertiajs es una librería que combina lo mejor del server side render y client side render, permitiéndonos construir SPAs usando el render clásico de vistas, controladores y el routing del backend, sin tener que definir una API y un sistema de routing en el frontend.
###### Vídeo: [Introducción a Jetstream](https://platzi.com/clases/2183-laravel-spa/35250-introduccion-a-jetstream/)
------------
#### ¿Debería usar Inertia?
		 Si, si te sientes cómodo con Vue.js.
###### Razón: Sí uno se siente cómodo con Vue.js debería usar Inertia, debido a que tiene algo de experiencia trabajando con ese motor de plantillas.
###### Vídeo: [Cómo aprenderás a crear SPAs en Laravel](https://platzi.com/clases/2183-laravel-spa/35249-presentacion-del-curso/)
------------
#### Si vamos a trabajar con un listado de datos en la vista, ¿de qué tipo debe ser la propiedad?
		 Array
###### Razón: Se debe usar un Array  para recorrer los registros.
###### Vídeo: [Listado de notas: personalización](https://platzi.com/clases/2183-laravel-spa/35257-listado-de-notas-personalizacion/)
------------
#### Si vamos a trabajar con un elemento en la vista, ¿de qué tipo debe ser la propiedad?
		 Object
###### Razón: Si solo se trabajará con un elemento de una vista, se debe usar Objetc, para así solo conocer los valores de un objeto en específico.
###### Vídeo: [Formulario de editar](https://platzi.com/clases/2183-laravel-spa/35259-formulario-de-editar/)
------------
#### ¿Cómo podemos observar y reaccionar en Vue.js?
		 Usando watch.
###### Razón: npm run watch compila los cambios realizacos en tiempo real, para la aplicación de cambios inmediatos.
###### Vídeo: [Jetstream: personalización](https://platzi.com/clases/2183-laravel-spa/35255-jetstream-personalizacion/)
------------
#### ¿Se puede combinar Inertia con Blade?
		 No
###### Razón: Blade es un motor de plantillas de Livewire, y Vue de Inertia. Por lo que no se pueden combinar.
###### Vídeo: [Cómo aprenderás a crear SPAs en Laravel](https://platzi.com/clases/2183-laravel-spa/35249-presentacion-del-curso/)
------------
#### ¿Podemos mediante Jetstream usar Livewire e Inertia al mismo tiempo?
		 No
###### Razón: Blade es un motor de plantillas de Livewire, y Vue de Inertia. Por lo que no se pueden combinar.
###### Vídeo: [Cómo aprenderás a crear SPAs en Laravel](https://platzi.com/clases/2183-laravel-spa/35249-presentacion-del-curso/)