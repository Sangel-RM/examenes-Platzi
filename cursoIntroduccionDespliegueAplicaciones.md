# Curso de Introducción al Despliegue de Aplicaciones
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Cuál de estos lenguajes fue uno de los primeros para hacer aplicaciones web?
		 PHP
###### Razón: PHP apareció en 1995, es un lenguaje de programación de uso general que se adapta especialmente al desarrollo web.
###### Vídeo: [Apps Monolíticas vs microservicios](https://platzi.com/clases/2011-despliegue-apps/32289-apps-monoliticas-vs-microservicios/)
------------
#### ¿Cuál es una desventaja de las apps monolíticas?
		 Si falla un componente en el código, puede fallar toda la aplicación.
###### Razón: Una aplicación monolítica tiene todas o la mayoría de sus funcionalidades en un único proceso o contenedor y está formada por capas internas o bibliotecas.
###### Vídeo: [Apps Monolíticas vs microservicios](https://platzi.com/clases/2011-despliegue-apps/32289-apps-monoliticas-vs-microservicios/)
------------
#### ¿Cuál de las siguientes NO es una ventaja de los microservicios?
		 Todos los componentes de la app van en un solo servidor.
###### Razón: Los microservicios son un enfoque arquitectónico y organizativo para el desarrollo de software donde el software está compuesto por pequeños servicios independientes que se comunican a través de API bien definidas.
###### Vídeo: [Apps Monolíticas vs microservicios](https://platzi.com/clases/2011-despliegue-apps/32289-apps-monoliticas-vs-microservicios/)
------------
#### ¿Qué contiene el stack LAMP?
		 Linux, Apache, MySQL, PHP
###### Razón: LAMP es el acrónimo usado para describir un sistema de infraestructura de internet que usa las siguientes herramientas:​​Linux, el sistema operativo; Apache, el servidor web; MySQL/MariaDB, el gestor de bases de datos; PHP, el lenguaje de programación.
###### Vídeo: [Stacks LAMP, MERN, JOTL, JAM](https://platzi.com/clases/2011-despliegue-apps/31605-stacks-lamp-mern-jotl-jam/)
------------
#### ¿Qué contiene el stack MERN?
		 MongoDB, Express, React, Node.js
###### Razón:  MERN es un conjunto de marcos/tecnologías utilizados para el desarrollo web de aplicaciones que consta de MongoDB, React JS, Express JS y Node JS como sus componentes.
###### Vídeo: [Stacks LAMP, MERN, JOTL, JAM](https://platzi.com/clases/2011-despliegue-apps/31605-stacks-lamp-mern-jotl-jam/)
------------
#### ¿Qué contiene el stack JAM?
		 Javascript, APIs y Markup
###### Razón: JAM hace referencia al conjunto de tecnologías que componen el JAMStack, JavaScript, APIs y Markup.
###### Vídeo: [Stacks LAMP, MERN, JOTL, JAM](https://platzi.com/clases/2011-despliegue-apps/31605-stacks-lamp-mern-jotl-jam/)
------------
#### ¿Cuál de estas tecnologías NO hace parte del stack LAMP?
		 MongoDB
###### Razón: MongoDB no es una tecnología usada en stacK LAMP.
###### Vídeo: [Stacks LAMP, MERN, JOTL, JAM](https://platzi.com/clases/2011-despliegue-apps/31605-stacks-lamp-mern-jotl-jam/)
------------
#### ¿Cuál de estas tecnologías NO hace parte del stack JOTL?
		 PHP
###### Razón: El esta JOTL usa las tecnologías de Java, Oracle, Tomcat, Linux.
###### Vídeo: [Stacks LAMP, MERN, JOTL, JAM](https://platzi.com/clases/2011-despliegue-apps/31605-stacks-lamp-mern-jotl-jam/)
------------
#### ¿Qué estructura debe llevar el nombre de mi repositorio para poderse usar con github pages?
		 usuario.github.io
###### Razón: GitHub Pages es un servicio de GitHub que permite alojar proyectos y mostrarlos en una página web estática sin necesidad de pagar por hosting o siquiera tener conocimientos en servidores o DevOps.
###### Vídeo: [Despliegue en Github pages](https://platzi.com/clases/2011-despliegue-apps/31606-despliegue-en-github-pages/)
------------
#### ¿Cuál es la forma de desplegar una aplicación estática en Surge?
		Usando la terminal
###### Razón: Situandose en la carpeta del proyecto que se publicará, se debe instalar surge, mediante npm.
###### Vídeo: [Despliegue en Surge](https://platzi.com/clases/2011-despliegue-apps/31607-despliegue-en-surge/)
------------
#### ¿Qué tipo de aplicación podemos desplegar en Netlify?
		 Aplicaciones estáticas
###### Razón: Netlify es una plataforma que nace para automatizar proyectos webs estáticos.
###### Vídeo: [Despliegue en Netlify](https://platzi.com/clases/2011-despliegue-apps/31608-despliegue-en-netlify/)
------------
#### ¿Cuál de estos subdominios se podría utilizar en Vercel?
		 misitio.now.sh
###### Razón: Vercel es una plataforma para frameworks frontend y sitios estáticos, construida para integrarse con contenido, comercio o base de datos. Actualmente el subdominio now.sh esta obsoleto, ahora debe usarse vercel.app
###### Vídeo: [Despliegue en Vercel](https://platzi.com/clases/2011-despliegue-apps/31609-despliegue-en-vercel/)
------------
#### ¿Qué tipo de base de datos podemos desplegar en Mongo Atlas?
		 MongoDB
###### Razón: MongoDB Atlas es el primer servicio de “Database as a Services” (DaS) para bases de datos MongoDB, en el cual es posible crear completos clusteres (Replica Set) de bases de datos.
###### Vídeo: [Desplegando una base de datos NoSql en Mongo Atlas](https://platzi.com/clases/2011-despliegue-apps/31610-desplegando-una-base-de-datos-nosql-en-mongo-atlas/)
------------
#### ¿Qué debemos configurar en MongoDB atlas para acceder a la BD desde nuestro equipo?
		 Agregar nuestra dirección IP.
###### Razón: Para acceder a la base de datos, se debe agregar la dirección IP, y así obtener acceso.
###### Vídeo: [Desplegando una base de datos NoSql en Mongo Atlas](https://platzi.com/clases/2011-despliegue-apps/31610-desplegando-una-base-de-datos-nosql-en-mongo-atlas/)
------------
#### ¿Qué formato de dirección IP debemos agregar en Mongo Atlas si queremos acceder a la BD desde cualquier aplicación o servidor en internet?
		 0.0.0.0/0
###### Razón: Si se desconoce cuales son las IPs desde las cuales, la aplicación, se conectará al servidor de MongoDB, se debe utilizar la IP 0.0.0.0/0. Permitiendo que cualquier IP pueda conectarse a MongoDB.
###### Vídeo: [Desplegando una base de datos NoSql en Mongo Atlas](https://platzi.com/clases/2011-despliegue-apps/31610-desplegando-una-base-de-datos-nosql-en-mongo-atlas/)
------------
#### ¿Qué es ElephantSQL?
		 PostgreSQL as a Service.
###### Razón:  ElephantSQL proporciona una herramienta de navegador para consultas SQL en la que se pueden crear, leer, actualizar y eliminar datos directamente desde el navegador web. PostgreSQL, es un sistema de gestión de bases de datos relacional orientado a objetos y de código abierto.
###### Vídeo: [Desplegando una base de datos relacional en ElephantSQL](https://platzi.com/clases/2011-despliegue-apps/31611-desplegando-una-base-de-datos-relacional-en-elepha/)
------------
#### ¿Qué tipo de bases de datos podemos alojar en ElephantSQL?
		 PostgreSQL
###### Razón:  ElephantSQL proporciona una herramienta de navegador para consultas SQL en la que se pueden crear, leer, actualizar y eliminar datos directamente desde el navegador web. PostgreSQL, es un sistema de gestión de bases de datos relacional orientado a objetos y de código abierto.
###### Vídeo: [Desplegando una base de datos relacional en ElephantSQL](https://platzi.com/clases/2011-despliegue-apps/31611-desplegando-una-base-de-datos-relacional-en-elepha/)
------------
#### ¿Qué es Heroku?
		 Un Platform as a Service.
###### Razón: La plataforma como servicio o PaaS es un conjunto de servicios basados en la nube que permite a los desarrolladores y usuarios empresariales crear aplicaciones a una velocidad que las soluciones en las instalaciones no pueden alcanzar.
###### Vídeo: [Qué es Heroku](https://platzi.com/clases/2011-despliegue-apps/31612-que-es-heroku/)
------------
#### ¿Cuál de estos lenguajes no es soportado en Heroku?
		 Cobol
###### Razón: Las siglas COBOL responden a Common Business-Oriented Language, un lenguaje de programación basado en el idioma inglés que lleva más de medio siglo sustentando todo tipo de operaciones, sobre todo en Estados Unidos. Es utilizado por sistemas financieros, compañías de seguros y un gran número de instituciones.
###### Vídeo: [Qué es Heroku](https://platzi.com/clases/2011-despliegue-apps/31612-que-es-heroku/)
------------
#### ¿Cómo se llama en Heroku la sección para agregar las variables de entorno de nuestra aplicación?
		 Config Vars
###### Razón: Para configuar las variables de entorno de heroku, se deben cambiar desde la sección de Config Vars > Reveal Config Vars
###### Vídeo: [Desplegando Api en Heroku](https://platzi.com/clases/2011-despliegue-apps/31613-desplegando-api-en-heroku/)
------------
#### ¿Cuál es una forma fácil de desplegar un proyecto en Heroku?
		 Crear la app en Heroku, conectar un repositorio en Github y desplegar.
###### Razón: Heroku permite conectar la cuenta de GitHub, para realizar desplieges más sencillos.
###### Vídeo: [Desplegando Api en Heroku](https://platzi.com/clases/2011-despliegue-apps/31613-desplegando-api-en-heroku/)
------------
#### ¿Cuál es el método HTTP para leer/listar información?
		 GET
###### Razón: El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.
###### Vídeo: [Consultando nuestra API desde Postman](https://platzi.com/clases/2011-despliegue-apps/31614-consultando-nuestra-api-desde-postman/)
------------
#### ¿Cuál es el método HTTP para crear información?
		 POST
###### Razón: El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.
###### Vídeo: [Consultando nuestra API desde Postman](https://platzi.com/clases/2011-despliegue-apps/31614-consultando-nuestra-api-desde-postman/)
------------
#### ¿Cuál es el método HTTP para eliminar información?
		 DELETE
###### Razón: El método DELETE borra un recurso en específico.
###### Vídeo: [Consultando nuestra API desde Postman](https://platzi.com/clases/2011-despliegue-apps/31614-consultando-nuestra-api-desde-postman/)
------------
#### ¿Qué son las colecciones en Postman?
		 Son carpetas para agrupar peticiones HTTP en común.
###### Razón: Postam permite organizar los tests en colecciones, la cual permite agrupar diferentes servicios y mediante archivos que se llaman environments es posible probar los servicios en diferentes servidores.
###### Vídeo: [Generar documentación de API con Postman](https://platzi.com/clases/2011-despliegue-apps/31615-generar-documentacion-de-api-con-postman/)
------------
#### ¿Cuál es una ventaja de publicar la documentación de una API usando Postman?
		 Gratis, rápido y fácil, con dos clics.
###### Razón: Para publicar la documentación de una API, solo se debe seleccionar la colección, View Documentation y Publish.
###### Vídeo: [Generar documentación de API con Postman](https://platzi.com/clases/2011-despliegue-apps/31615-generar-documentacion-de-api-con-postman/)
------------
#### ¿Qué debemos hacer para publicar la documentación de una API usando Postman?
		 Seleccionar la colección e ir a la opción: Publish Docs
###### Razón: Actualmente solo se debe seleccionar la colección, View Documentation y Publish.
###### Vídeo: [Generar documentación de API con Postman](https://platzi.com/clases/2011-despliegue-apps/31615-generar-documentacion-de-api-con-postman/)
------------
#### ¿Cuál de los siguientes no es proveedor considerado grande?
		 Bare Metal Servers
###### Razón: Un servidor Bare Metal consiste en un equipo informático cuyos recursos, como memoria RAM, potencia de cálculo y almacenamiento son para un solo destino, pues está dedicado de forma integral a una sola compañía. 
###### Vídeo: [Capas gratuitas de grandes proveedores](https://platzi.com/clases/2011-despliegue-apps/31616-capas-gratuitas-de-grandes-proveedores/)
------------
#### ¿Cuál de estas es una desventaja para usar la capa gratuita de un proveedor grande de cloud computing?
		 Necesitas tarjeta de crédito
###### Razón: Muchos servicios de Cloud Computing te dan crédito gratis para probar sus aplicaciones, pero luego de que el crédito se agota, es necesario pagar por el servicio.
###### Vídeo: [Capas gratuitas de grandes proveedores](https://platzi.com/clases/2011-despliegue-apps/31616-capas-gratuitas-de-grandes-proveedores/)
------------
#### ¿En cuál de estos casos NO conviene usar Heroku?
		 Cuando queremos tener control total de la infraestructura, tal como el servidor con SSH.
###### Razón: Heroku es una plataforma como servicio o PaaS es un conjunto de servicios basados en la nube que permite a los desarrolladores y usuarios empresariales crear aplicaciones a una velocidad que las soluciones en las instalaciones no pueden alcanzar. Es este tipo de plataformas, no se tiene control de la infraestructura. si se necesitara control de la infraestructura sería necesario un IaaS :Infraestructure as a Service, en español infraestructura como servicio.
###### Vídeo: [Qué es Heroku](https://platzi.com/clases/2011-despliegue-apps/31612-que-es-heroku/)