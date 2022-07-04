# Curso de Fundamentos de Bases de Datos
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Por que es importante tener un registro de información que perdure en el tiempo?
		 Permiten que el conocimiento se perpetué
###### Razón: Históricamente la información se pasaba de boca en boca, lo cual termina distorsionando la información de una manera muy rápida. A través del tiempo la transmisión de información a evolucionado, pasando por la escritura en piedra, el papiro, papel, microfilm, medios digitales. Y es importante a que el conocimiento perpetúe debido a que nos hace saber de lo que ha sucedido y permite estudiar esto.
###### Vídeo: [Bienvenida conceptos básicos y contexto histórico de las Bases de Datos](https://platzi.com/clases/1566-bd/19781-bienvenida-conceptos-basicos-y-contexto-historico-/)
------------
#### ¿Cuál es el otro nombre que se le da a las 12 reglas de Codd?
		 Mandamientos
###### Razón: Las 12 reglas de Codd son un sistema de 13 reglas —numeradas del 0 al 12— propuestas por el creador del modelo relacional de bases de datos, Edgar F. Sirven para definir los requerimientos que un sistema de administración de base de datos ha de cumplir para poder ser considerado relacional como lo son, por ejemplo, las bases de datos relacionales.
###### Vídeo: [Historia de las bases de datos relacionales](https://platzi.com/clases/1566-bd/20196-historia-de-las-rdb/)
------------
#### ¿Cuáles son las formas en que una entidad puede ser débil?
		 Identidad y existencia
###### Razón: Las entidades débiles no pueden existir sin una entidad fuerte y se representan con un cuadrado con doble línea. Hay 2 tipos las entidades débiles por identidad estas no se diferencian entre sí más que por la clave de su identidad fuerte y las entidades débiles por existencia estas se les asigna una clave propia.
###### Vídeo: [Entidades y atributos](https://platzi.com/clases/1566-bd/20197-entidades-y-atributos/)
------------
#### ¿Qué tipo de palabra se utiliza para denotar una relación entre dos entidades de una base de datos?
		 Verbo
###### Razón: Las relaciones, representadas por un rombo, sirven para crear relaciones entre entidades.
###### Vídeo: [Relaciones](https://platzi.com/clases/1566-bd/20199-relaciones/)
------------
#### Diferencia original entre char y varchar
		 Char reserva estáticamente en memoria y varchar reserva variablemente
###### Razón:  Al usar CHAR se indica a la memoria que se reservará para la cantidad de bytes que se indique, por ejemplo si se declará un char de longitud 20, y se guarda un hola solo se ocuparán 4 bytes y los otros 16 se llenarán con espacios, el límite de char es 255, en cambio con varchar es una longitud variable, solo reservará en memoria los datos que se coloquen, anque se declare un varchar de 100, y se escriba hola solo guardará 4 bytes, el límite de varchar es 65,535 bytes.
###### Vídeo: [Diagrama Físico: tipos de datos y constraints](https://platzi.com/clases/1566-bd/20202-diagrama-fisico-y-tipos-datos-y-constraints0863/)
------------
#### ¿Cuántas formas normales vimos en clase?
		 4
###### Razón: La normalización ayuda a dejar todo de una forma normal. Esto obedece a las 12 reglas de Codd y nos permiten separar componentes en la base de datos, gracias a la normalización se evita redundancia de datos, disminuye problemas de actualización de los datos en las tablas, protege la integridad de los datos.
###### Vídeo: [Diagrama Físico: normalización](https://platzi.com/clases/1566-bd/20203-diagrama-fisico-normalizacion8011/)
------------
#### ¿Cuál de los siguientes es un RDBMS open source?
		 MariaDB
###### Razón: RDBMS (Relational DataBase Magement System) Sistema Manejador de Bases de datos relacionales. MariaDB es un sistema de gestión de bases de datos que está muy relacionado con MySQL, ya que fue desarrollado por uno de los desarrolladores, Michael “Monty” Widenius. El objetivo de su desarrollo fue el de mantener el software de gestión de base de datos en un modelo de software libre.
###### Vídeo: [¿Qué es RDB y RDBMS?](https://platzi.com/clases/1566-bd/20205-rdb-que4374/)
------------
#### ¿Por qué se les llama servicios administrados?
		 Los administra una compañía dedicada
###### Razón: Los servicios de administración se encargan de minimizar riesgos y fortalecer la seguridad informática. 
###### Vídeo: [Servicios Administrados](https://platzi.com/clases/1566-bd/20209-servicios-administrados9920/)
------------
#### ¿Qué significa la “S” en SQL?
		 Structured
###### Razón: SQL (Structured Query Language/ Lenguaje de Consulta Estructurada) es un lenguaje de dominio específico, diseñado para administrar, y recuperar información de sistemas de gestión de bases de datos relacionales.
###### Vídeo: [Historia de SQL](https://platzi.com/clases/1566-bd/20210-historia-de-sql/)
------------
#### ¿En qué fase de un proyecto se utiliza más fuertemente el lenguaje DDL?
		 Al inicio
###### Razón: DDL (Data Definition Language) ayuda a crear la estructura de una base de datos. Existen 3 grandes comandos Create, Alter y Drop. Es por eso que se suele ocupar al inicio debido a que permite crear las bases de datos y tablas.
###### Vídeo: [DDL Create](https://platzi.com/clases/1566-bd/20211-ddl-create8613/)
------------
#### ¿Cuál de los siguientes objetos se puede crear con la sentencia “create”?
		 Tabla
###### Razón: Para crear una tabla en SQL se usa la instrucción CREATE TABLE miTabla;
###### Vídeo: [DDL Create](https://platzi.com/clases/1566-bd/20211-ddl-create8613/)
------------
#### ¿Qué de lo siguiente se puede lograr con la sentencia "ALTER TABLE"?
		 Agregar una columna
###### Razón: AlLTER TABLE es usadlo para añadir, eliminar o modificar columnas de una table. También es usdado para añadir o eliminar restricciones de una tabla.
###### Vídeo: [CREATE VIEW y DDL ALTER](https://platzi.com/clases/1566-bd/20212-create-view-y-ddl-alter/)
------------
#### La sentencia DROP puede borrar una base de datos (schema) completa
		 Cierto
###### Razón: DROP es usado para eliminar tablas y bases de datos.
###### Vídeo: [DDL DROP](https://platzi.com/clases/1566-bd/20213-ddl-drop7001/)
------------
#### ¿En qué fase de un proyecto se utiliza más fuertemente el lenguaje DML?
		 En el día a día
###### Razón: DML (Data Manipulation Language/Lenguaje de Manipulación de Datos) son un conjunto de instrucciones que apoyarán al proceso de construcción de la BD y afectan los registros en una tabla. Estas son operaciones básicas que se realizan sobre datos tales como seleccionar algunos registros de una tabla, añadir nuevos registros, eliminar registros innecesarios y actualizar / modificar registros existentes. Y es por eso que se ocupa en el día a día las operaciones de DML.
###### Vídeo: [DML](https://platzi.com/clases/1566-bd/20214-dml/)
------------
#### La sentencia UPDATE sirve para crear una nueva tupla si no existe
		 Falso
###### Razón: UPDATE actualiza o modifica los datos existentes, si se neceista crear un nuevo registro/tupla se debe usar INSERT.
###### Vídeo: [DML](https://platzi.com/clases/1566-bd/20214-dml/)
------------
#### ¿Qué sentencia debemos agregar a la sentencia "DELETE" a manera de red de protección?
		 WHERE
###### Razón: DELETE sirve para eliminar registros existentes, se debe usar con WHERE debido a que así se eliminaran dados una condición.
###### Vídeo: [DML](https://platzi.com/clases/1566-bd/20214-dml/)
------------
#### La mayoría de sentencias SQL corren con mínimas modificaciones en cualquier RDBMS
		 Cierto
###### Razón: Sin importar que RDBMS se use (IBM, Oracle, MySQL, SQLServer, PostgreSQL) estos siguen el mismo estándar de SQL.
###### Vídeo: [¿Qué tan standard es SQL?](https://platzi.com/clases/1566-bd/19808-que-tan-standard-es-sql/)
------------
#### ¿Cuál es la principal sentencia de consulta?
		 SELECT
###### Razón: SELECT se encarga de proyectar o mostrar datos.
###### Vídeo: [SELECT](https://platzi.com/clases/1566-bd/19818-select/)
------------
#### ¿Cuál es la estructura básica de un query de consulta?
		SELECT FROM WHERE
###### Razón: Los queries son la forma en la que se realizan preguntas a la base de datos. El query tiene básicamente 2 partes: SELECT y FROM y puede aparecer una tercera como WHERE. Con SELECT se seleccionan las columnas, FROM la tabla y WHERE la condición.
###### Vídeo: [Estructura básica de un Query](https://platzi.com/clases/1566-bd/19817-estructura-basica-de-un-query/)
------------
#### ¿Cuál es un ejemplo de base de datos optimizada para búsqueda?
		 Big Query
###### Razón: BigQuery es un almacén de datos sin servidor totalmente administrado que permite un análisis escalable en petabytes de datos. Es una plataforma como servicio que admite consultas mediante ANSI SQL. También tiene capacidades de aprendizaje automático integradas.
###### Vídeo: [¿Qué son y cuáles son los tipos de bases de datos no relacionales?](https://platzi.com/clases/1566-bd/19813-que-son-y-cuales-son-los-tipos-de-base-datos-no-re/)
------------
#### ¿Cual es el objeto principal en la base de datos Firestore?
		 Documento
###### Razón: Los documentos son una implementación de clave valor que varía en la forma semiestructurada en que se trata la información es ideal para almacenar datos JSON y XML
###### Vídeo: [Servicios administrados y jerarquía de datos](https://platzi.com/clases/1566-bd/19814-servicios-administrados-y-jerarquia-de-datos/)
------------
#### Las top level collection son las colecciones que tienen un documento padre
		 Falso
###### Razón: Las top level collections son las colecciones que se tienen de inmediato o entrada en el proyecto
###### Vídeo: [Top level collection con Firebase](https://platzi.com/clases/1566-bd/19815-top-level-collection-con-firebase/)
------------
#### ¿Cuál de los siguientes es un tipo de dato en Firestore?
		 String
###### Razón: Los tipos de datos en FireStore disponibles son: String, Number, Boolean, Map, Array, Null, Geopoint, Reference y Timestamp.
###### Vídeo: [Creando y borrando documentos en Firestore](https://platzi.com/clases/1566-bd/19816-creando-y-borrando-documentos-en-firestore/)
------------
#### Utilizamos subcolecciones cuando queremos acceder a sus documentos de manera independiente o son referenciados desde otras colecciones
		 Falso
###### Razón: El uso de sub-colecciones es mas recomendado para cuando se requiere acceder a esos documentos o cuando se accede al documento padre y no se requiere referenciar desde otro documento padre.
###### Vídeo: [Colecciones vs subcolecciones](https://platzi.com/clases/1566-bd/19828-colecciones-vs-subcolecciones/)
------------
#### ¿A que se traducen las entidades de un RDBMS en Firestore?
		 Colecciones
###### Razón: La colección en Firestore está compuesta por un objeto cuyas propiedades son el índice de la colección y el valor es el objeto de cada item. Entonces si se tiene una entidad separada que se referenciará desde muchos lugares es recomendado usar una colección.
###### Vídeo: [Colecciones vs subcolecciones](https://platzi.com/clases/1566-bd/19828-colecciones-vs-subcolecciones/)
------------
#### ¿A que se traducen las tuplas de un RDBMS en Firestore?
		 Documentos
###### Razón: Los documentos pueden contener muchos pares de clave-valor distintos, o pares de clave-matriz, o incluso documentos anidados.
###### Vídeo: [Creando y borrando documentos en Firestore](https://platzi.com/clases/1566-bd/19816-creando-y-borrando-documentos-en-firestore/)
------------
#### ¿Cuál es el caso de uso principal de una base de datos basada en documentos?
		 El estado actual de una aplicación
###### Razón: Las bases de datos no relacionales, no están optimizadas para hacer “queries”, sino mantener el estado de la aplicación por ende si se desean luego hacer reportes en la aplicación de diferentes datos, no es recomendable usar NoSQL. 
###### Vídeo: [Top level collection con Firebase](https://platzi.com/clases/1566-bd/19815-top-level-collection-con-firebase/)
------------
#### ¿Cuál es el caso de uso principal de una base de datos basada en grafos?
		 Relaciones complejas y machine learning
###### Razón: Una base de datos orientada a grafos representa la información como nodos de un grafo y sus relaciones con las aristas del mismo, de manera que se pueda usar teoría de grafos para recorrer la base de datos ya que esta puede describir atributos de los nodos y las aristas.
###### Vídeo: [¿Qué son y cuáles son los tipos de bases de datos no relacionales?](https://platzi.com/clases/1566-bd/19813-que-son-y-cuales-son-los-tipos-de-base-datos-no-re/)
------------
#### ¿Cuál es el propósito principal del Business Intelligence?
		 Ayudar a tomar mejores decisiones
###### Razón: Hace referencia al uso de estrategias y herramientas que sirven para transformar información en conocimiento, con el objetivo de mejorar el proceso de toma de decisiones en una empresa.
###### Vídeo: [Business intelligence](https://platzi.com/clases/1566-bd/19834-business-intelligence/)
------------
#### ¿Cuáles son las dos funciones básicas de la mayoría de servicios de machine learning?
		 Predicción y clasificación
###### Razón: El Machine Learning es una disciplina del campo de la Inteligencia Artificial que, a través de algoritmos, dota a los ordenadores de la capacidad de identificar patrones en datos masivos y elaborar prediccione
###### Vídeo: [Machine Learning](https://platzi.com/clases/1566-bd/19835-machine-learning3347/) 