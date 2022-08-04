# Curso de Introducción a la Nube con Azure
*Si alguna respuesta esta incorrecta puedes realizar un pull request para colocar la respuesta correcta :D.*
#### ¿Por qué se dice que el cómputo en la nube es más barato que el local (on-premise)?
		 Porque su modelo de consumo se basa en costos operativos que se pagan mes a mes y no se debe invertir en infraestructura física.
###### Razón: Un modelo On-Premise es más costoso debido a que se todo corre por tu cuenta, se debe invertir en Equipos , Adecuación, Mantenimiento, Configuración, Actualización.
###### Vídeo: [Modelos de servicio: IaaS, PaaS, SaaS y serverless](https://platzi.com/clases/2200-introduccion-azure/38232-modelos-de-servicio-iaas-paas-saas-y-serverless/)
------------
#### Es un ejemplo del modelo de consumo CapEx (capital expenditure, gastos de capital):
		 Comprar servidores físicos, instalarlos y adecuar el espacio para los mismos.
###### Razón: CapEx (Capital Expenditure) es Gastos de capital es una inversión en infraestructura física, deducible a largo plazo.
###### Vídeo: [Qué es la nube: ventajas y características](https://platzi.com/clases/2200-introduccion-azure/38229-que-es-la-nube-ventajas-y-caracteristicas/)
------------
#### Supongamos que tienes una máquina virtual la cual comienza a ser lenta y decides escalarla verticalmente su capacidad ¿qué acción tomarías?
		 Aumentar su memoria RAM o CPU para agilizar sus procesos.
###### Razón: El escalar verticalmente o escalar hacia arriba, significa el añadir más recursos a un solo nodo en particular dentro de un sistema, tal como el añadir memoria o un disco duro más rápido a una computadora.
###### Vídeo: [Qué es la nube: ventajas y características](https://platzi.com/clases/2200-introduccion-azure/38229-que-es-la-nube-ventajas-y-caracteristicas/)
------------
#### Son los modelos de servicio básicos en la nube:
		 Infrastructure as a Service (IaaS), Platform as a Service (PaaS) y Software as a Service (SaaS).
###### Razón: Los modelos de servicio que maneja Azure son Infrastructure as a Service (IaaS), Platform as a Service (PaaS) y Software as a Service (SaaS).
###### Vídeo: [Modelos de servicio: IaaS, PaaS, SaaS y serverless](https://platzi.com/clases/2200-introduccion-azure/38232-modelos-de-servicio-iaas-paas-saas-y-serverless/)
------------
#### ¿En qué escenario es más conveniente tener una nube en local (on-premise)?
		 Cuando queremos tener un control al 100% del hardware, podemos permitirnos los costos involucrados y deseamos hacernos cargo de su administración.
###### Razón: Con On-Premise se tiene el control del 100%, se requiere de personal para cada una de las actividades, y que estas trabajen en local. Se debe hacer cargo de:Equipos, adecuación, mantenimiento, configuración, actualización, etc.
###### Vídeo: [Modelos de servicio: IaaS, PaaS, SaaS y serverless](https://platzi.com/clases/2200-introduccion-azure/38232-modelos-de-servicio-iaas-paas-saas-y-serverless/)
------------
#### ¿En qué escenario es más conveniente tener una nube como SaaS (Software as a Service)?
		 Cuando queremos utilizar una solución ya creada en la nube como usuarios, sin tener que desarrollar el producto.
###### Razón: En SaaS todo se delega al proveedor y los usuarios usan la aplicación que se ejecuta en la nube. Algunos ejemplos son Office Online y Outlook.
###### Vídeo: [Modelos de servicio: IaaS, PaaS, SaaS y serverless](https://platzi.com/clases/2200-introduccion-azure/38232-modelos-de-servicio-iaas-paas-saas-y-serverless/)
------------
#### La nube privada se encuentra únicamente en local (on-premise). Esto es:
		 Falso
###### Razón: Una nube privada solo es accesible para algunos miembros de la organización. Puede ser tanto On-Premise o puede estar alojada en un centro de datos. Hay proveedores que se encargan de ofrecer una nube privada. Una de sus desventajas es el costo.
###### Vídeo: [Tipos de nube: pública, privada e híbrida](https://platzi.com/clases/2200-introduccion-azure/38231-tipos-de-nube-publica-privada-e-hibrida/)
------------
#### ¿Qué es la nube híbrida?
		 Una combinación de la nube pública y privada, contando con una parte on-premise y otra provista por un proveedor de servicios en la nube.
###### Razón: Una nube híbrida es la combinanción entre una nube on-premise, nube pública y privada.. Esto es porque alguno de los tipos de nube ofrece ciertas características que la otra no. Como motivos de seguridad, de control o porque la organización que tiene su cómputo de forma local esta migrando a la nube.
###### Vídeo: [Tipos de nube: pública, privada e híbrida](https://platzi.com/clases/2200-introduccion-azure/38231-tipos-de-nube-publica-privada-e-hibrida/)
------------
#### ¿Cuáles son los componentes de una cuenta de Azure?
		 Cuenta/grupo de suscripción, suscripción, grupo de recursos y recursos.
###### Razón: Los 4 componentes de una cuenta Azure son Cuenta/grupo de suscripción: Administran el acceso, las directivas y cumplimiento de las suscripciones. Las suscripciones heredan las condiciones de su grupo.
###### Suscripción: Agrupación de cuentas de usuario y recursos creados por estas cuentas. Puede tener límites o cuotas definidas.
###### Grupo de Recursos: Contenedor lógico donde se implementan y administran recursos de Azure. Un recurso puede pertenecer a un solo Grupo de Recursos pero puede comunicarse con recursos de otro Grupo de Recursos.
###### Recursos: Instancias de los servicios disponibles: Máquinas virtuales, discos duros y bases de datos.
###### Vídeo: [Cuentas de Azure](https://platzi.com/clases/2200-introduccion-azure/38233-cuentas-de-azure/)
------------
#### Agrupación de cuentas de usuario y recursos creados por una cuenta de Azure.
		 Suscripción
###### Razón: Una suscripción es una agrupación de cuentas de usuario y recursos creados por estas cuentas. Puede tener límites o cuotas definidas.
###### Vídeo: [Suscripciones y grupos de administración](https://platzi.com/clases/2200-introduccion-azure/38236-suscripciones-y-grupos-de-administracion/)
------------
#### ¿Qué sucede al eliminarse un grupo de recursos?
		 Se eliminan todos los recursos contenidos.
###### Razón: Al eliminar un grupo de recursos, también se eliminan todos los recursos contenidos.
###### Vídeo: [Recursos y grupos de recursos](https://platzi.com/clases/2200-introduccion-azure/38235-recursos-y-grupos-de-recursos/)
------------
#### ¿Qué es el Azure Resource Manager?
		 Es el administrador de recursos en Azure que nos permite utilizar plantillas para instanciar recursos de forma ágil.
###### Razón: Azure Resource Manager es una herramienta que permite administrar recursos de forma masiva y funciona a través de plantillas.
###### Vídeo: [Recursos y grupos de recursos](https://platzi.com/clases/2200-introduccion-azure/38235-recursos-y-grupos-de-recursos/)
------------
#### ¿Qué es una "región" en Azure?
		 Una área geográfica con por lo menos un data center.
###### Razón: Una región es un area geográfica con por lo menos un data center. Algunos servicios son exclusivos de ciertas regiones. Hay regiones comom Canada East, North Europe, South Africa North.
###### Vídeo: [Regiones](https://platzi.com/clases/2200-introduccion-azure/38239-regiones/)
------------
#### ¿Qué es una zona de disponibilidad?
		 Dos o más data centers independientes en una misma región para brindar redundancia de servicios en casos de emergencia.
###### Razón: Una zona de disponiblidad es donde hay distintos data centers en una misma región equipados con energía de emergencia, refrigeración y redes independientes. Su propósito es permitir redudancia de servicios y datos ante errores, desastres u otros imprevistos.
###### Vídeo: [Regiones](https://platzi.com/clases/2200-introduccion-azure/38239-regiones/)
------------
#### ¿Qué tipos de datos admiten los servicios de almacenamiento en Azure?
		 Estructurados, semi-estructurados y no estructurados.
###### Razón: Los tipos de datos permitidos por Azure son Estructurados, semi-estructurados y no estructurados.
###### Vídeo: [Análisis y bases de datos](https://platzi.com/clases/2200-introduccion-azure/38242-analisis-y-bases-de-datos/)
------------
#### Azure SQL Database permite almacenar bases de dato SQL y NoSQL. Esto es:
		 Verdadero
###### Razón: Azure permite almacenar Base de datos SQL y NoSQL.
###### Vídeo: [Análisis y bases de datos](https://platzi.com/clases/2200-introduccion-azure/38242-analisis-y-bases-de-datos/)
------------
#### ¿Qué es un contenedor?
		 Ambientes aislados para la virtualización del sistema operativo, algunas de sus funciones o procesos.
###### Razón: Un contenedor integra todo lo necesario para ejecutar una aplicación, incluidas bibliotecas, herramientas del sistema, código y tiempo de ejecución.
###### Vídeo: [Servicios de cómputo en la nube](https://platzi.com/clases/2200-introduccion-azure/38241-servicios-de-computo-en-la-nube/)
------------
#### Una contenedor es un ejemplo de:
		 PaaS (Platform as a Service).
###### Razón: Los contenedores en Azure son PaaS debido a que se usa Azure Container Instances.
###### Vídeo: [Servicios de cómputo en la nube](https://platzi.com/clases/2200-introduccion-azure/38241-servicios-de-computo-en-la-nube/)
------------
#### ¿Qué tipo de servicios podemos alojar en Azure Apps?
		 Aplicaciones web, API y backend de apps móviles.
###### Razón: Azure App Seervice es de tipo PaaS, sirve para crear y alojar aplicaciones conectadas a la web. Es compatible con Windows, Linux e implementaciones automatizadas.
###### Vídeo: [Servicios de cómputo en la nube](https://platzi.com/clases/2200-introduccion-azure/38241-servicios-de-computo-en-la-nube/)
------------
#### ¿Cuál es el modelo de pago de Azure Functions?
		 Pago solo por funciones ejecutadas.
###### Razón: Azure Functions son funciones que responden a eventos: Peticiones REST, Temporizador, Mensajes de otro servicio. Y su modelo de pago es solo por las funciones ejecutadas.
###### Vídeo: [Servicios de cómputo en la nube](https://platzi.com/clases/2200-introduccion-azure/38241-servicios-de-computo-en-la-nube/)
------------
#### Este servicio nos permite evaluar recursos y tener recomendaciones sobre cómo podemos optimizar nuestras instancias en Azure.
		 Azure Advisor.
###### Razón: Azure brinda consejos y evalúa recursos a través del portal de Azure o su API.
###### Vídeo: [Monitoreo y supervisión](https://platzi.com/clases/2200-introduccion-azure/38249-monitoreo-y-supervision/)
------------
#### ¿Qué tipo de herramientas nos ofrece Azure para administrar nuestro entorno?
		 Visuales y basadas en código.
###### Razón: Azure brinda herramientas visuales y basadas en código para administrar el entorno, como Azure Mobile App, Azure PowerShell, Azure CLI y Cloud Shell.
###### Vídeo: [Administración y configuración de entorno](https://platzi.com/clases/2200-introduccion-azure/38248-administracion-y-configuracion-de-entorno/)
------------
#### Azure Functions es únicamente compatible con .NET. Esto es:
		 Falso
###### Razón: Azure Functions permite trabajar con distintos entones de programación.
###### Vídeo: [Servicios de cómputo en la nube](https://platzi.com/clases/2200-introduccion-azure/38241-servicios-de-computo-en-la-nube/)
------------
#### El costo de usar Azure Logic Apps puede variar según los conectores utilizados. Esto es:
		 Verdadero
###### Razón: Varia dependiendo de los conectores usados debido a que algunos conectores sus precios son variados.
###### Vídeo: [Servicios de cómputo en la nube](https://platzi.com/clases/2200-introduccion-azure/38241-servicios-de-computo-en-la-nube/)
------------
#### ¿Por qué Microsoft cuenta con un kit de desarrollo para IoT?
		 Porque aún quedan muchos estándares por definir en IoT, el contar con un SDK y software propio de Microsoft brinda mayor seguridad.
###### Razón: El Internet of Things (IoT), describe la red de objetos físicos (cosas), que llevan sensores integrados, software y otras tecnologías, con el fin de conectar e intercambiar datos con otros dispositivos y sistemas a través de internet.
###### Vídeo: [IoT](https://platzi.com/clases/2200-introduccion-azure/38250-iot/)
------------
#### ¿Qué representa una puntuación de seguridad alta en Azure Security Center?
		 Que nuestro entorno se encuentra protegido.
###### Razón: La puntuación de seguridad es la medida del nivel de seguridad y permite: Notificar el estado actual, Mejorar el nivel, Compara puntos de referencia.
###### Vídeo: [Seguridad](https://platzi.com/clases/2200-introduccion-azure/38253-seguridad/)
------------
#### ¿Qué servicio de Azure nos permite almacenar información confidencial como claves, certificados y respaldos?
		 Azure Key Vault.
###### Razón: Azure Key Vault es un servicio centralizado para almacenar datos confidenciales.
###### Vídeo: [Seguridad](https://platzi.com/clases/2200-introduccion-azure/38253-seguridad/)
------------
#### ¿Qué es "cumplimiento"/"compliance"?
		 Cumplir con una ley, estándar, conjunto de normas o requerimientos.
###### Razón: Es un Contrato formal entre empresa de servicios y cliente. Define estándares de rendimiento que Microsoft se compromete a brindar.
###### Vídeo: [Acuerdos de nivel de servicio y ciclo de vida](https://platzi.com/clases/2200-introduccion-azure/38254-acuerdos-de-nivel-de-servicio-y-ciclo-de-vida/)
------------
#### ¿Qué información nos brinda los términos de los servicios en línea de Microsoft?
		 Contrato legal entre Microsoft y el cliente. Detalla las obligaciones de ambas partes respecto al procesamiento y seguridad de los datos.
###### Razón: Es un Contrato formal entre empresa de servicios y cliente. Define estándares de rendimiento que Microsoft se compromete a brindar.
###### Vídeo: [Acuerdos de nivel de servicio y ciclo de vida](https://platzi.com/clases/2200-introduccion-azure/38254-acuerdos-de-nivel-de-servicio-y-ciclo-de-vida/)
------------
#### La región donde se encuentren nuestros recursos de Azure afectan a sus costos. Esto es:
		 Verdadero
###### Razón: El costo por región puede variar debido a que algunos servicios son exclusivos de ciertas regiones y por lo que contratar un servicio exclusivo en una región costaría mas.
###### Vídeo: [Regiones](https://platzi.com/clases/2200-introduccion-azure/38239-regiones/)