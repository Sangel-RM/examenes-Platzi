# Curso Profesional de Git y GitHub Curso Profesional de Git y GitHub
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### Git funciona para muchos tipos de archivo, ¿Qué tal funciona Git con archivos binarios?
		Los puede agregar y versionar pero es mejor usar Git con texto plano.
###### Razón: Git puede hacer seguimiento de archivos binarios sin inconvenientes, el problema es que los cambios que se le hagan a estos archivos no son tan legibles para nosotros debido a que veríamos carácteres raros. 
###### Vídeo:  [Editores de código, archivos binarios y de texto plano](https://platzi.com/clases/1557-git-github/19938-editores-de-codigo-archivos-binarios-y-de-texto-pl/ "Editores de código, archivos binarios y de texto plano")
------------
#### ¿La terminal ideal para usar Git en Windows es?
		Git Bash o una terminal derivada de Linux
###### Razón: GitBash es una herramienta de tipo consola que básicamente nos permite manipular y gestionar todo el proceso a realizar con nuestro proyecto. Git viene con un bash que funciona como el de Linux. Como tal no trae todas la capacidades de una terminal de Linux, pero funciona bastante bien.
###### Vídeo:  [Instalando Git y GitBash en Windows](https://platzi.com/clases/1557-git-github/19933-instalando-git-y-gitbash-en-windows/ "Instalando Git y GitBash en Windows")
------------
#### ¿Qué guarda Git?
  		Los cambios de los archivos de un proyecto
###### Razón: Un sistema de control de versiones como Git nos ayuda a guardar el historial de cambios y crecimiento de los archivos de nuestro proyecto. En realidad, los cambios y diferencias entre las versiones de nuestros proyectos pueden tener similitudes, algunas veces los cambios pueden ser solo una palabra o una parte específica de un archivo específico. Git está optimizado para guardar todos estos cambios de forma atómica e incremental, o sea, aplicando cambios sobre los últimos cambios, estos sobre los cambios anteriores y así hasta el inicio de nuestro proyecto.
###### Vídeo:  [¿Por qué usar un sistema de control de versiones como Git?](https://platzi.com/clases/1557-git-github/19934-por-que-usar-un-sistema-de-control-de-versiones-co/ "¿Por qué usar un sistema de control de versiones como Git?")
------------
#### En un commit, los mensajes del commit son:
		Importantes y obligatorios
###### Razón: git commit envía los archivos modificados al repositorio confirmando los cambios hechos y agregando un mensaje que sirve al usuario para identificar lo hecho.
###### Vídeo: [Crea un repositorio de Git y haz tu primer commit](https://platzi.com/clases/1557-git-github/19936-crea-un-repositorio-de-git-y-haz-tu-primer-commit/ "Crea un repositorio de Git y haz tu primer commit")
------------
#### ¿Qué es un branch o una rama en Git?
		Un repositorio aparte del master donde puedes trabajar en paralelo.
###### Razón: Por defecto, siempre empezamos en la rama main (pero puedes cambiarle el nombre si no te gusta) y creamos nuevas ramas, a partir de esta, para crear flujos de trabajo independientes. Crear una nueva rama se trata de copiar un commit (de cualquier rama), pasarlo a otro lado (a otra rama) y continuar el trabajo de una parte específica de nuestro proyecto sin afectar el flujo de trabajo principal (que continúa en la rama master o la rama principal).
###### Vídeo: [¿Qué es un Branch (rama) y cómo funciona un Merge en Git?](https://platzi.com/clases/1557-git-github/19947-que-es-un-branch-rama-y-como-funciona-un-merge-en-/ "¿Qué es un Branch (rama) y cómo funciona un Merge en Git?")
------------
#### Un repositorio remoto y un repositorio local:
		Tienen ramas similares dependiendo de cuáles haya enviado entre uno y otro.
###### Razón: Cuando se trabaja en equipo se tiene otro repositorio pero esta vez es un repositorio REMOTO alojado en un servidor REMOTO, y en nuestra PC tenemos nuestro repositorio local que podemos hacer las modificaciones que queramos sin afectar el remoto hasta que hagamos un push.
###### Vídeo:  [Flujo de trabajo básico con un repositorio remoto](https://platzi.com/clases/1557-git-github/19935-flujo-de-trabajo-basico-con-un-repositorio-remoto/ "Flujo de trabajo básico con un repositorio remoto")
------------
#### ¿El HEAD en una rama es?
		El apuntador al estado actual del repositorio basado en la rama en la que estoy trabajando.
###### Razón: HEAD se refiere al commit en el que está tu repositorio posicionado en cada momento. Por regla general HEAD suele coincidir con el último commit de la rama en la que estés, ya que habitualmente estás trabajando en lo último.
###### Vídeo:  [Flujo de trabajo básico con un repositorio remoto](https://platzi.com/clases/1557-git-github/19935-flujo-de-trabajo-basico-con-un-repositorio-remoto/ "Flujo de trabajo básico con un repositorio remoto")
------------
#### Cuando hay un conflicto entre archivos lo mejor es:
		Analizar los conflictos tal como los reportó Git y elegir los cambios finales, luego commit.
###### Razón: Git puede resolver algunos conflictos automáticamente: cambios, nuevas líneas, entre otros. Pero algunas veces no sabe cómo resolver estas diferencias, por ejemplo, cuando dos ramas diferentes hacen cambios distintos a una misma línea. Esto lo conocemos como conflicto y lo podemos resolver manualmente, solo debemos hacer el merge, ir a nuestro editor de código y elegir si queremos quedarnos con alguna de estas dos versiones o algo diferente. Recuerda que siempre debemos crear un nuevo commit para aplicar los cambios del merge. Si Git puede resolver el conflicto hará commit automáticamente. Pero, en caso de no pueda resolverlo, debemos solucionarlo y hacer el commit.
###### Vídeo: [Resolución de conflictos al hacer un merge](https://platzi.com/clases/1557-git-github/19941-resolucion-de-conflictos-al-hacer-un-merge/ "Resolución de conflictos al hacer un merge")
------------
#### ¿GitHub es?
		Un sistema online de manejo de repositorios de Git.
###### Razón: GitHub es una plataforma que nos permite guardar repositorios de Git que podemos usar como servidores remotos y ejecutar algunos comandos de forma visual e interactiva (sin necesidad de la consola de comandos).
###### Vídeo: [Uso de GitHub](https://platzi.com/clases/1557-git-github/19942-uso-de-github/ "Uso de GitHub")
------------
#### ¿Las llaves públicas son?
		Fáciles de compartir y sus mensajes imposibles de descifrar.
###### Razón: Las llaves públicas sirven para compartir información en internet de una forma segura incluso si el mensaje es interceptado la probabilidad de que suceda es nula si no se cuenta con la llave privada.
###### Vídeo: [Cómo funcionan las llaves públicas y privadas](https://platzi.com/clases/1557-git-github/19949-como-funcionan-las-llaves-publicas-y-privadas/ "Cómo funcionan las llaves públicas y privadas")
------------
#### Para transmitir cambios seguros entre tu repositorio local y GitHub, ¿qué se recomienda?
		Usar una llave SSH.
###### Razón:SSH o Secure Shell: Es un protocolo de red que permite acceso remoto seguro a través de una conexión encriptada. Este método de autenticación requiere un passphrase (contraseña) o tambien puede funcionar sin passphrase sobre la clave.
###### Vídeo: [Configura tus llaves SSH en local](https://platzi.com/clases/1557-git-github/19950-configurar-llaves-ssh-en-github/ "Configura tus llaves SSH en local")
------------
#### ¿Puedo crear ramas en GitHub que no tenga en mi repositorio local?
		Sí, tú decides si traer esas ramas a tu repositorio local.
###### Razón: Es posible crear las ramas deseadas en el repositorio remoto y que no esten en local, si quisieramos que fuera así tendríamos que hacer un git fetch o pull.
###### Vídeo: 	[Introducción a las ramas o branches de Git](https://platzi.com/clases/1557-git-github/19940-introduccion-a-las-ramas-o-branches-de-git/ "Introducción a las ramas o branches de Git")
------------
#### En un repositorio público en GitHub, ¿qué puede hacer los colaboradores?
		Hacer cambios al repositorio, hacer push/pull, crear ramas, etc.
###### Razón: Por defecto, cualquier persona puede clonar o descargar tu proyecto desde GitHub, pero no pueden crear commits, ni ramas, ni nada. Existen varias formas de solucionar esto para poder aceptar contribuciones. Una de ellas es añadir a cada persona de nuestro equipo como colaborador de nuestro repositorio.
###### Vídeo: [Configurar múltiples colaboradores en un repositorio de GitHub](https://platzi.com/clases/1557-git-github/19954-configurar-multiples-colaboradores-en-un-repositor/ "Configurar múltiples colaboradores en un repositorio de GitHub")
------------
#### Para que dos personas trabajen en paralelo sobre el mismo archivo se recomienda:
		Una rama independiente por cada persona y sus cambios que luego con verificación se hace merge a master.
###### Razón: Es recomendado trabajar en ramas paralelas, para luego hacer un merge con la rama principal, y así evitar conflictos. 
###### Vídeo: [Manejo de ramas en GitHub](https://platzi.com/clases/1557-git-github/19953-manejo-de-ramas-en-github/ "Manejo de ramas en GitHub")
------------
#### Un pull request es:
		 Un cambio sugerido a un repositorio que el dueño del repositorio puede autorizar y hacer merge a la rama que elija.
###### Razón: Es una funcionalidad de github (en gitlab llamada merge request y en bitbucket push request), en la que un colaborador pide que revisen sus cambios antes de hacer merge a una rama, normalmente master. Al hacer un pull request se genera una conversación que pueden seguir los demás usuarios del repositorio, así como autorizar y rechazar los cambios.
###### Vídeo: [Utilizando Pull Requests en GitHub](https://platzi.com/clases/1557-git-github/19957-utilizando-pull-requests-en-github/ "Utilizando Pull Requests en GitHub") 
------------
#### El dueño de un repositorio al ver un pull request puede:
		Editarlo, aceptarlo, darle merge, comentarlo para pedir cambios.
###### Razón: Es una funcionalidad de github (en gitlab llamada merge request y en bitbucket push request), en la que un colaborador pide que revisen sus cambios antes de hacer merge a una rama, normalmente master. Al hacer un pull request se genera una conversación que pueden seguir los demás usuarios del repositorio, así como autorizar y rechazar los cambios.
###### Vídeo: [Utilizando Pull Requests en GitHub](https://platzi.com/clases/1557-git-github/19957-utilizando-pull-requests-en-github/ "Utilizando Pull Requests en GitHub") 
------------
#### Si ya hiciste el desafío de “Hazme un pull request,” ¿dentro de cuál etiqueta tenías que agregar el cambio?
		<divid="post">
###### Razón: Freddy indica que en ese div, escribamos nuestros nombres del archivo blogspost.html disponible en https://github.com/freddier/hyperblog
###### Vídeo: [Hazme un pull request](https://platzi.com/clases/1557-git-github/19959-hazme-un-pull-request/ "Hazme un pull request")
------------
#### Si en el .gitignore agrego esto: images/*.js. ¿Cuál de los siguientes archivos sería ignorado?
		 images/jquery.js
###### Razón: Colocar * en el gitignore sirve para que este haga una excepción con aquellos archivos terminen con las extensión js
###### Vídeo: [Ignorar archivos en el repositorio con .gitignore](https://platzi.com/clases/1557-git-github/19960-ignorar-archivos-en-el-repositorio-con-gitignore/ "Ignorar archivos en el repositorio con .gitignore") 
------------
#### ¿Cuándo deberías usar cherry-pick?
		 Cuando quiero los cambios de un commit pasado sin dañar la historia de la rama.
###### Razón: Este comando permite coger uno o varios commits de otra rama sin tener que hacer un merge completo. Así, gracias a cherry-pick, podríamos aplicar los commits relacionados con nuestra funcionalidad en nuestra rama master sin necesidad de hacer un merge.
###### Vídeo: [Git cherry-pick: traer commits viejos al head de un branch](https://platzi.com/clases/1557-git-github/19982-git-cherry-pick-traer-commits-viejos-al-head-de-un/ "Git cherry-pick: traer commits viejos al head de un branch") 
------------
#### Si usas: 
> git config --global alias.platzi "shortlog"

#### ¿Cómo invocar ese comando?
		git platzi
###### Razón: Los alias son sinónimos de accesos rapidos permite darle un nombre a alguna instrucción para realizarlo de forma más eficaz.
###### Vídeo: [Crea un repositorio de Git y haz tu primer commit](https://platzi.com/clases/1557-git-github/19936-crea-un-repositorio-de-git-y-haz-tu-primer-commit/ "Crea un repositorio de Git y haz tu primer commit")
------------
#### ¿Cómo instalas Gitk?
 		 Viene por defecto 
###### Razón: Podemos ver gráficamente nuestro entorno y flujo de trabajo local con Git usando el comando gitk.
###### Vídeo: [Manejo de ramas en GitHub](https://platzi.com/clases/1557-git-github/19953-manejo-de-ramas-en-github/ "Manejo de ramas en GitHub")
------------
#### Es mejor aprender a manejar Git con la terminal antes de hacerlo con herramientas visuales como Gitk porque:
		 Debemos aprender Git con sus comandos de la terminal para resolver problemas o conflictos más avanzados. Gitk funciona bien, pero no nos permite realizar operaciones tan complejas.
###### Razón: GitK nos permite visualizar de manera gráfica pero no realiza acciones complejas que son posibles en bash.
###### Vídeo: [Manejo de ramas en GitHub](https://platzi.com/clases/1557-git-github/19953-manejo-de-ramas-en-github/ "Manejo de ramas en GitHub")
------------
#### ¿Cómo llaman GitHub y GitLab a los "merges" (propuestas de cambios desde otra rama o repositorio)?
		 GitHub los llama Pull Request y GitLab Merge Request.
###### Razón: Es una funcionalidad de github (en gitlab llamada merge request y en bitbucket push request), en la que un colaborador pide que revisen sus cambios antes de hacer merge a una rama, normalmente master. Al hacer un pull request se genera una conversación que pueden seguir los demás usuarios del repositorio, así como autorizar y rechazar los cambios.
###### Vídeo: [Utilizando Pull Requests en GitHub](https://platzi.com/clases/1557-git-github/19957-utilizando-pull-requests-en-github/ "Utilizando Pull Requests en GitHub")  
------------
#### ¿Puedes conectar tu repositorio local con más de un repositorio remoto?
		 Verdadero 
###### Razón: Se puede crear una copia del estado actual de un repositorio remoto, éste repositorio podrá servir como otro origen y se podrá clonar (como cualquier otro repositorio), en pocas palabras, lo podremos utilizar como un git cualquiera
###### Vídeo: [Creando un Fork, contribuyendo a un repositorio](https://platzi.com/clases/1557-git-github/19978-creando-un-fork-contribuyendo-a-un-repositorio/ "Creando un Fork, contribuyendo a un repositorio")
------------
#### Estás en la rama master y quieres mandar los últimos cambios que guardaste con git stash a la rama retomando-los-cambios (la rama no ha sido creada aún). ¿Cuál de las siguientes soluciones es incorrecta?
		git stash apply retomando-los-cambios
###### Razón: Esta instrucción no es posible.
###### Vídeo: [Manejo de ramas en GitHub](https://platzi.com/clases/1557-git-github/19953-manejo-de-ramas-en-github/ "Manejo de ramas en GitHub")
------------
#### ¿Cuál es la diferencia entre git rm y git reset HEAD?
		git rm saca los archivos del repositorio y (opcionalmente) del disco duro. git reset head saca los archivos de Staging, pero no del disco duro.
###### Razón: git rm --cached elimina un archivo de staging. Es como si nunca le hubieses hecho git add a ese archivo. Mientras que git reset HEAD devuelve el archivo a su último commit, por si quiere modificar algo y luego le puedes hacer git add o git commit otra vez.
###### Vídeo:[Git reset vs. Git rm](https://platzi.com/clases/1557-git-github/23295-git-reset-vs-git-rm/ "Git reset vs. Git rm")
------------
#### ¿Para qué sirve git grep?
		Para encontrar las veces que hemos usado una palabra en los archivos del repositorio.
###### Razón: Si queremos bucar la palabra 'color 'utilizamos el comando git grep color y nos buscará en todo el proyecto los archivos en donde está la palabra color.
###### Vídeo: [Buscar en archivos y commits de Git con Grep y log](https://platzi.com/clases/1557-git-github/19987-buscar-en-archivos-y-commits-de-git-con-grep-y-log/ "Buscar en archivos y commits de Git con Grep y log")
------------
#### Por defecto, GitHub usa la rama main como la rama principal. ¿Podemos cambiar la rama principal?
		Verdadero
###### Razón: Es posible cambiar el nombre por defecto de nuestra rama principal o seleccionar otra rama como principal.
###### Vídeo: [Cambios en GitHub: de master a main](https://platzi.com/clases/1557-git-github/35869-cambios-en-github-de-master-a-main/ "Cambios en GitHub: de master a main")
------------
#### ¿Para qué sirve GitHub Pages?
		Es un servicio de GitHub que nos permite publicar nuestros repositorios en internet (por ejemplo, nombre.github.io o nombre.github.io/proyecto).
###### Razón: Con GitHub es posible albergar tu sitio web directamente desde un repositiorio. 
###### Vídeo: [Tu sitio web público con GitHub Pages](https://platzi.com/clases/1557-git-github/19976-tu-sitio-web-publico-con-github-pages/ "Tu sitio web público con GitHub Pages")
------------
#### El Jefe Freddy despidió a Anita y no piensa volver a contratarla. ¿Qué debe hacer Anita para seguir haciendo contribuciones a los proyectos públicos de Platzi?
		Crear un Fork del proyecto y enviar Pull Request al proyecto original.
###### Razón: Al hacer un fork de un poryecto en GitHub, te conviertes en dueño del repositorio fork, puedes trabajar en éste con todos los permisos, pero es un repositorio completamente diferente que el original, teniendo alguna historia en común. Los forks son importantes porque es la manera en la que funciona el open source, ya que, una persona puede no ser colaborador de un proyecto, pero puede contribuír al mismo, haciendo mejor software que pueda ser utilizado por cualquiera. Al hacer un fork, GitHub sabe que se hizo el fork del proyecto, por lo que se le permite al colaborador hacer pull request desde su repositorio propio.
###### Vídeo: [Creando un Fork, contribuyendo a un repositorio](https://platzi.com/clases/1557-git-github/19978-creando-un-fork-contribuyendo-a-un-repositorio/ "Creando un Fork, contribuyendo a un repositorio")
------------
#### Los cambios a un archivo que están en “staging” están en:
		Un área temporal en memoria antes de llegar al repositorio.
###### Razón:Hay 4 estados en Git los cuales son:
###### - Tracked: son los archivos que viven dentro de Git, no tienen cambios pendientes y sus últimas actualizaciones han sido guardadas en el repositorio gracias a los comandos git add y git commit.
###### - Staged: son archivos en Staging. Viven dentro de Git y hay registro de ellos porque han sido afectados por el comando git add, aunque no sus últimos cambios. Git ya sabe de la existencia de estos últimos cambios, pero todavía no han sido guardados definitivamente en el repositorio porque falta ejecutar el comando git commit.
###### -Unstaged: entiéndelos como archivos “Tracked pero Unstaged”. Son archivos que viven dentro de Git pero no han sido afectados por el comando git add ni mucho menos por git commit. Git tiene un registro de estos archivos, pero está desactualizado, sus últimas versiones solo están guardadas en el disco duro.
###### - Untracked: son archivos que NO viven dentro de Git, solo en el disco duro. Nunca han sido afectados por git add, así que Git no tiene registros de su existencia. Recuerda que hay un caso muy raro donde los archivos tienen dos estados al mismo tiempo: staged y untracked. Esto pasa cuando guardas los cambios de un archivo en el área de Staging (con el comando git add), pero antes de hacer commit para guardar los cambios en el repositorio haces nuevos cambios que todavía no han sido guardados en el área de Staging (en realidad, todo sigue funcionando igual pero es un poco divertido).
###### Vídeo: [¿Qué es el staging y los repositorios? Ciclo básico de trabajo en Git](https://platzi.com/clases/1557-git-github/19946-que-es-el-staging-y-los-repositorios-ciclo-basico-/ "¿Qué es el staging y los repositorios? Ciclo básico de trabajo en Git")
------------
#### Con checkout puedo:
		Ver todos los archivos de mi proyecto como los dejé en otras ramas.
###### Razón: checkout significa “Revisar” por lo que tiene mucho sentido que hacer checkout a un commit o branch sea cambiar a el para ir a revisarlo. Sirve para cambiar de rama en pocas palabras.
###### Vídeo:[Introducción a las ramas o branches de Git](https://platzi.com/clases/1557-git-github/19940-introduccion-a-las-ramas-o-branches-de-git/ "Introducción a las ramas o branches de Git")
------------
#### ¿Cuándo debería hacer un merge?
		Cuando quiero fusionar los cambios de una rama con otra.
###### Razón: El comando git merge nos permite crear un nuevo commit con la combinación de dos ramas (la rama donde nos encontramos cuando ejecutamos el comando y la rama que indiquemos después del comando).
###### Vídeo: [Fusión de ramas con Git merge](https://platzi.com/clases/1557-git-github/19939-funcion-de-ramas-con-git-mer-7/ "Fusión de ramas con Git merge")
------------
#### ¿Con amend puedo?
		Corregir los mensajes de un commit que hice mal sin que quede en la historia del repositorio.
###### Razón: Utilizamos git commit --amend, amend en inglés es remendar y lo que hará es que los cambios que hicimos nos los agregará al commit anterior.
###### Vídeo: [Reconstruir commits en Git con amend](https://platzi.com/clases/1557-git-github/19981-reconstruir-commits-en-git-con-amend/ "Reconstruir commits en Git con amend")
------------
#### Cuando hago un fork de un proyecto en GitHub, ¿lo que logro es?
		Copiar un repositorio público a mis repositorios en GitHub, con todas sus ramas e historia anterior.
###### Razón: Al hacer un fork de un poryecto en GitHub, te conviertes en dueño del repositorio fork, puedes trabajar en éste con todos los permisos, pero es un repositorio completamente diferente que el original, teniendo alguna historia en común. Los forks son importantes porque es la manera en la que funciona el open source, ya que, una persona puede no ser colaborador de un proyecto, pero puede contribuír al mismo, haciendo mejor software que pueda ser utilizado por cualquiera. Al hacer un fork, GitHub sabe que se hizo el fork del proyecto, por lo que se le permite al colaborador hacer pull request desde su repositorio propio.
###### Vídeo: [Creando un Fork, contribuyendo a un repositorio](https://platzi.com/clases/1557-git-github/19978-creando-un-fork-contribuyendo-a-un-repositorio/ "Creando un Fork, contribuyendo a un repositorio")
------------
#### Cuando usas git stash, los cambios que “guardas” temporalmente se guardan en:
		Memoria RAM
###### Razón: El stashed nos sirve para guardar cambios para después. Es una lista de estados que nos guarda algunos cambios que hicimos en Staging para poder cambiar de rama sin perder el trabajo que todavía no guardamos en un commit
###### Vídeo: [Git Stash: Guardar cambios en memoria y recuperarlos después](https://platzi.com/clases/1557-git-github/19984-stash/ "Git Stash: Guardar cambios en memoria y recuperarlos después")
------------
#### ¿Qué crean los tags en Git?
		Versiones descargables y puntos únicos en una rama de un repositorio.
###### Razón: Los tags o etiquetas nos permiten asignar versiones a los commits con cambios más importantes o significativos de nuestro proyecto.
###### Vídeo: [Tags y versiones en Git y GitHub](https://platzi.com/clases/1557-git-github/19952-tags-y-versiones-en-git-y-github/ "Tags y versiones en Git y GitHub")


