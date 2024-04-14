---

---
---
# UPC
# INGENIERÍA DE SISTEMAS DE SOFTWARE
## CURSO: SI730 Aplicaciones Web | SECCIÓN WX54 
 Profesor: Alex Humberto Sánchez Ponce
# Informe de TB1
Startup: **YESI (Yielding Efficient Software Implementations)**  
Producto: **AidManager**
### Integrantes:
- Peña Rivera, Manuel Sebastian - U202210138
- Ramírez Hoffmann, Sebastián - U202211894
- Rodriguez Vargas, Arian Martin - U202212096
- Esteban Garcia, Nicolas Sebastián - U202217485
- Herrera Aguirre, Fabia Alejandra - U202219422   

---
# Registro de Versiones del Informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 19/03/2024 |Grupo 1 |Se crea el documento |

# Project Report Collaboration Insights
[URL del repositorio](https://github.com/AplicacionesWeb-WX54/si730-WX54-Grupo1-Repository.git)

(Imagenes de los commits cada entrega)


# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.|<br> *TB1:* Manuel Sebastian Peña Rivera: Participe en secciones del capitulo 2, 3 y 4 que contienen entrevistas, product backlog, impact map, user task matrix, style guidelines *TB2:* texto etc.. |Realizar la investigación necesaria para el proyecto permite conocer la realidad de los desafíos que presentan y como nuestro programa puede solucionar el problema es nuestro objetivo en mente|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|Manuel Sebastian Peña Rivera: No solo la investigación realizada, sino que la entrevista que realice me permitió conocer sobre las dificultades y experiencia como voluntario en la ONG. <br> *TB2:* texto etc.. |Con la información reunida de la entrevista espero poder adaptar las necesidades al proyecto y que nuestro proyecto le sirva para mejorar la eficiencia de su trabajo|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Nuestra startup **AidManager** se basa en una herramienta enfocada en gestionar los proyectos de ONG, esto se hara al recibir informacion de los mismos asistentes asignados al evento y por medio de nosotros se hara un analisis intensivo en oportunidades de mejora, reportes de inventario, asistentes del eveto entre otros. Adicionalmente la herramienta servira para planificar futuros eventos usando la misma informacion previamente registrada. 

#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-| 
|Ramírez Hoffmann, Sebastián  <img src="https://avatars.githubusercontent.com/u/129230632?v=4" alt="Imagen del compañero" style="width:60%">|U20221894|Ingenieria de software|C++, Python, Js, Reactjs, NodeJs, expressjs, MongoDB, SQL.  Paciencia, Liderazgo, Logico|
|Rodriguez Vargas, Arian Martin <img src="../assets/members-profile/arigeimpleis.jpg" alt="Imagen del compañero" style="width:60%">|U202212096|Ingenieria de software|C++, Python, persistente y amigable|
|Esteban Garcia, Nicolas Sebastian <img src="../assets/members-profile/nekolas-profile.png" alt="Imagen del compañero" style="width:60%">|U202217485|Ingenieria de software|HTML, CSS Y JS. Sociable.|
|Herrera Aguirre, Fabia Alejandra 	<img src="../assets/members-profile/pelufoto.png" alt="Imagen del compañero" style="width:60%">|U202219422|Ingenieria de software|C++, Python. Creativa.|
|Peña Rivera, Manuel Sebastian	<img src="../assets/members-profile/Manuel.jpg" alt="Imagen del compañero" style="width:60%">|U202210138|Ingenieria de software|C++, Python, MongoDB, SQL, Assembler. Responsabilidad y Buena Comunicación| 

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

Segun la Oficina de Naciones Unidas para la Coordinación de Asuntos Humanitarios (OCHA) en 2023 se reportaron 801,425 personas en necesidades de alimentacion, servicios de agua, saneamiento e higiene.
En el Peru existen 978 Organizaciones privadas sin fines de lucro de las cuales principalmente 428 se han categorizado como de salud, 19 de educacion y 35 de vivienda (SIGCTI, 2024), esto nos demuestra que existe un alto rango de organizaciones privadas sin fines de lucro. No obstante cuando buscamos organizaciones ONDG(Organizaciones No Gubernamentales de Desarollo) encontramos un total de 1835 (SIGCTI, 2024). Aun con muchas instituciones el alcance que se logra resulta ser preocupante, en la encuesta que se realizo por equillibrium CenDE en 2023 de entre casi 1,200 personas un 80% de estas reconocia que es una ONG no obstante 71% o no sabia o no conocia iniciativas realizadas por las ONGs en ese año, en esta misma encuesta solo un 7% no tenia interes alguno en participar en el abordamiento de problemas publicos ni socialmente es decir un 93% de las 1,200 estaban dispuestas a apoyar. Adicionalmente cuando estas mismas ONG reciben grandes cantidades de datos normalmente solo son para obtener una cifra que represente los asistentes a algun evento o cuanto se logro de un objetivo de donacion omitiendo lo enriquecedor de esta data recolectada, como se menciona en el articulo "Data Analytics for Nonprofits" (DigitalForNonprofits, 2023), en el mundo de hoy para realizar acciones estrategicas y maximisar recursos distintas empresas utilizan lo llamado analisis de datos, esta practica se puede aplicar a un modelo de negocios sin fines de lucro como las ONG donde se consiguen los mismos beneficios que brindan los analisis de datos.

Es aqui donde nosotros ideamos la propuesta de **AidManager**, es una aplicacion web que se basa en una herramienta de gestion utilizada por los encargados de gestionar el proyecto y los asistentes del proyecto haciendo uso de su informacion recopilada por medio de nosotros quienes por nuestro servicio de analisis de datos y gestion de proyectos le proporcionaremos oportunidades de mejora, graficas relevantes respecto a la data y recomendaciones en como pueden implementar una recolecion de datos mas efectiva para amplificar el impacto deseado, de misma manera de que se presentaran espacios donde el gestor pueda planificar su siguiente proyecto facilitando el seguimiento de este mismo y haciendo un registro mas efficiente. 

What (¿Que se está haciendo?): Se facilita el proceso de planeacion para actividades orientadas al apoyo social y donacion de bienes. Asimismo se proporciona un servicio de gestion avanzado para las ONG con el objetivo de aumentar el impacto de estas.

Why (¿Porque se está haciendo?): Se hace esta aplicacion web con el objetivo de darle una herramienta a las ONG para aumentar la eficiencia de sus proyectos de ayuda social proporcionando adicionalmente una plataforma donde sus mismos ayudantes puedan recopilar la informacion de manera efectiva.

When (¿Cuándo se usa?): Se usa cuando se tengan los datos recopilados del proyecto mas reciente y se busque ver las oportunidades de mejora e ideas para la eficacia de un siguiente proyecto en un formato visual que sea facil de entender. Asi como tambien se hara uso de la herramienta cuando este proyecto este en ejecucion donde los asistentes del mismo recopilaran los datos para que consecuentemente el supervisor asignado a gestionar del proyecto pueda observar las oportunidades de mejora.

Where (¿Dónde se usa?): El uso esta diseñado para Perú ya que se recompilara informacion de ONG's que esten actuando en este pais, de esta manera se podran hacer recomendaciones mas locales. Asimismo esta App Web se puede usar facilmente desde el telefono o escritorio.

Who (¿Quién lo usa?): El usuario principal para nosotros son los supervisores y ayudantes de las ONG ya que son estos los mismos que nos proporcionaran los datos recopilados para mejorar su impacto y requieren de una mejor organizacion, nuestro usuario principal entonces se divide en el segmento de supervisor / gerente y el ayudante / recolector de data.

How Much (¿Cuánto costaría?): La aplicacion web tendra sus funcionalidades core a medio de pago es decir el proceso de gestion recopilacion y refinamiento de datos junto con las mejores oportunidades de mejora para estas. Tanto el core de la app web como la subscripcion se tendran que renovar cada cierto tiempo donde las organizaciones se tendran que escoger un plan anual o mensual.

How (¿Cómo se lleva al cabo?)

Se hara un proceso de inscripcion y seguidamente se les presentara con la oportunidad de crear o importar un proyecto
seguidamente solicitara los datos recopilados de su proyecto mas reciente, de estos datos se mostraran graficos representando la demografica, gastos, junto con explicaciones, recomendaciones y oportunidades de mejora. Asimismo se proporcionara la herramienta para gestionar futuros proyectos la cual se podra usar de manera opcional para poder estructurar mejor los encargados, el presupuesto y objetivos del siguiente proyecto. Cuando se inicie un proyecto se dependera de los ayudantes de estos eventos a que recopilen la informacion de los usuarios por medio de nuestro aplicativo web, donde tendran que registrarse y coleccionar la data de los participantes a eventos.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
Se identifica una falta de organizacion por parte de las ONG donde existen distintas oportunidades para mejorar el alcance con una buena planificacion. No obstante, muchas organizaciones no tienen conocimiento del potencial que se puede obtener de esta informacion o no cuentan con un equipo dedicado al analisis de datos a niveles de Big Data o formas efectivas de recolectar esta misma informacion. Asimismo hemos identificado que existen diferentes factores los cuales llevan a un usuario interesado en una ONG a no tener motivos suficientes para participar de actividades sociales o de hacer donativos a estas mismas, una de estas siendo la falta de informacion y la carencia de visibilidad que estan tienen siendo que aun asi habiendo mas de 1000 ONG's en el Perú no se conocen muchas de estas ni de como poder ayudarlas. Frente a esta problematica nos planteamos la siguiente pregunta:
¿Como facilitamos el proceso de gestion de un proyecto de ayuda social para aumentar el flujo de participantes en las actividades que ofrecen las distintas ONG's a la poblacion de nuestro país de manera eficiente?
#### 1.2.2.2. Lean UX Assumptions.

Después de analizar la problemática y los factores que la ocasionan, podemos tener un panorama de cómo solucionar la necesidad del usuario declarando supuestos, lo cual corresponde al siguiente paso de la Lean UX. Por ello, es necesario tener un conocimiento previo de las empresas que tienen características similares a las nuestras y cómo estas se han desarrollado con el paso del tiempo. 

Se mencionan a tres potenciales competidores:

CauseVox:
Plataforma que facilita el crowdfunding no solo de bienes monetarios, sino también de recursos como víveres y vestimenta. Plataforma de recaudación de fondos que brinda herramientas necesarias para crear campañas llamativas para cumplir su meta de donación. su diversificacion de bienes junto con sus campañas muestran su capacidad para ser competidores.

Donadora:
Es una plataforma mexicana en la que se pueden financiar proyectos de caridad, así como proyectos de tipo artístico, científico, entre otros. Al entrar en la financiacion para diferentes proyectos fuera de la caridad presenta una aptidud para ser competidor.

Logalto:
Es un Programa web colaborativo para el monitoreo y la evaluación de proyectos de desarrollo internacional la cual proporciona una alta gama de herramientas de gestion de proyectos.

|Business Assumptions|User Assumptions|
|-|-|
|Creemos que nuestros usuarios tienen la necesidad de aumentar el flujo de personas a sus eventos y facilitar la creasion de estos gestionando sus datos y proyectos de manera efectiva. |Los usuarios de este producto son el personal encargado de gestion de proyecto y los ayudantes que participan de estos eventos de Organizaciones no gubernamentales. |
|Este problema se puede solucionar con una plataforma donde se pueda organizar y supervizar proyectos donde se pueda generar un analisis de datos con recomendaciones y oportunidedes de mejora con infromacion recoleccionada por los mismos ayudantes de estos eventos. Ademas de que se presente toda la informacion necesaria para un proceso de inscripcion o donacion |Nuestro producto encajaría en la vida cotidiana debido a que sera accesible, economicamente viable y facil de utilizar tanto para las personas que tengan que supervizar el proyecto como para los mismos ayudantes para la recoleccion de datos |
|Los usuarios iniciales Organizaciones no gubernamentales sin fines de lucro que deseen mejorar su impacto y alcance.  |Este producto resolverá la necesidad de gestionar proyectos mientras que se recopila y analiza informacion de manera efectiva, simple y facil de entender para tener mayores oportunidades de mejora. |
|El valor #1 de nuestro servicio es el analisis de datos comprensible, el registro de informacion relevante y la interfaz amigable y simple de usar. |El producto se utilizará al momento que se tenga que realizar un nuevo proyecto de ayuda social y se deba realizar un planeamiento.|
|El aplicativo adicionalmente contara con el sistema de registro de ayudantes y gerentes que tendran un limite segun los distintos planes que tenemos para las ONG de distintos tamaños |Las funciones mas importantes son, la capacidad de manejar y presentar los datos de manera que sean visualmente coherentes y poco abrumadores. La planificacion de proyectos haciendo un registrod de todo lo necesario para que se pueda ejecutar. Y finalmente, una interfaz facil de usar para tanto el ayudante como para el gestor del proyecto|
|Se conseguirán la mayoría de los usuarios por medio de marketing digital (como las redes sociales) y Noticieros. |Nuestro producto debe verse como una herramienta de gestion y analisis de datos. Asimismo siendo una herramienta que se usa para planificar proyectos de ayuda benefica de alta calidad y monitoreo |
|Conseguiremos ingresos de la aplicación por medio de la compra del servicio para las ONG y los distintos planes proporcionales al tamaño de las necesidades de la organizacion.||
|Nuestros competidores principales serán CauseVox, Donadora y Logalto. ||
|Los venceremos al tener una mejor interactividad y experiencia de usuario, una herramienta de gestion para proyectos futuros simple de entender y el proceso amigable y facil de utilizar para adquirir la informacion. ||
|El mayor riesgo del producto es la falta de alcance inicial, la capacidad de datos, la precicion de datos y la competencia. ||
|Solucionaremos esto por medio de campañas de publicidad, contactar a las ONG y dandoles a los recolectores las pautas a seguir para reducir el margen de error.||
|Pensamos que un assumption que si se prueba falso puede causar que el proyecto falle es la demanda actual de nuestro producto y la necesidad estimada.||

#### 1.2.2.3. Lean UX Hypothesis Statements.
- Creemos que, al brindar una interfaz poco compleja de usar para nuestros usuarios, podrán tener una mejor experiencia al gestionar sus datos y  proyectos de ayuda social.
  Sabremos que hemos tenido éxito cuando se incremente la cantidad de proyectos efectivos por parte de las ONG que usen nuestra herramienta. 

- Creemos que la aplicación facilitara la gestion y creacion de proyectos de ayuda social proporcionando mejores resultados y un mayor flujo de personas participando de estas actividades.  
  Sabremos que tuvimos exito cuando distintos proyectos de ONG reciban mas relevancia y participantes.

- Creemos que ayudar a las ONG a tener una mejor gestion y planeamiento en sus proyectos ayudara a mejorar la visibilidad y aumentar la cantidad de personas motivadas a participar.
  Sabremos que hemos tenido éxito, cuando a nivel nacional se empiece a notar un incremento en la ayuda social proporcionada. 

#### 1.2.2.4. Lean UX Canvas.
|-|-|-|
|-|-|-|
| Business Problem <br>¿Qué problema has identificado que necesitas resolver? Las ONG estan perdiendo conexion y requieren optimizar sus proyectos para mejorar su impacto. <br>Según CenDe de 1200 personas 72% de estas no han participado en alguna actividad de actividad de ayuda social.<br> Segun "Digital for non Profits" 78% de organizaciones nonprofit con capacidades analiticas tienen mejoras tales como mejora de reclutamiento, mejoras en el alcance y hacer seguimiento de presupuestos| Solution ideas <br>Herramienta de gestion de proyectos recopilando datos y recomendaciones de accion.<br><br>Ofrecer planes de pago a las para ONG cuyos proyectos tienen diferentes cantidades de personas.<br><br>Mejorar y optimizar los procesos de recoleccion de datos para un analisis mas exacto. | Business Outcomes <br>(Cambios en el comportamiento del usuario) <br>¿Qué cambios en el comportamiento del usuario indicarán que has solucionado un problema real de manera que añada valor a tus clientes? <br> El comportamiento que refleje que se ha solucionado un problema real sera cuando las actividades de ayuda social consigan ser mas efectivas y que los participantes de estas aumenten.|
| User & Customers <br>¿En qué tipo de usuarios y clientes tienes que centrarte primero? <br>Usuario: <br>Personas encargadas de la gestion y recoleccion de datos de un proyecto orientado a las ONG. <br>Cliente: la Organizacion sin fines de lucro que adquiere nuestra herramienta. <br> ONG que busquen una optimizacion en la cantidad de gastos y tiempo invertidos.  <br> |  UX Canvas| User benefits <br>¿Cuáles son los objetivos que los usuarios intentan obtener? <br> \- Se busca gestionar un proyecto de manera que se pueda entender las oportunidades de mejora, los datos registrados, las planificaciones del proyecto y como pueden llegar a mas con menos. <br> ¿Qué les motiva a buscar tu solución? <br> \- Los usuarios están motivados a buscar esta solución debido la interfaz intuitiva, las oportunidades de optimizacion economica y el seguimiento de las acciones, gastos y personal que participara. <br>Nuestra interfaz resulta intuitiva para el usuario en todo el proceso. <br> |
| Hyphotheses: <br>  \- Creemos que, al brindar una interfaz poco compleja de usar para nuestros usuarios, podrán tener una mejor experiencia al gestionar sus datos y  proyectos de ayuda social. <br><br>Sabremos que hemos tenido éxito cuando se incremente la cantidad de proyectos efectivos por parte de las ONG que usen nuestra herramienta. <br><br> \- Creemos que la aplicación facilitara la gestion y creacion de proyectos de ayuda social proporcionando mejores resultados y un mayor flujo de personas participando de estas actividades. <br><br> Sabremos que tuvimos exito cuando distintos proyectos de ONG reciban mas relevancia y participantes. <br><br> \- Creemos que ayudar a las ONG a tener una mejor gestion y planeamiento en sus proyectos ayudara a mejorar la visibilidad y aumentar la cantidad de personas motivadas a participar. <br><br> Sabremos que hemos tenido éxito, cuando a nivel nacional se empiece a notar un incremento en la ayuda social proporcionada. | ¿Qué es la cosa más importante que nosotros necesitamos aprender primero? <br> Lo principal que necesitamos aprender es generar un modelo de gestion el cual sea efectivo a nivel visual y de gestion, y adicionalmente, un repaso en lo que viene siendo la gestión del proyecto| <br> ¿Cuál es la mínima cantidad de trabajo que nosotros necesitamos hacer para aprender la siguiente cosa más importante? <br> Asistir a las clases y solicitar que se nos revise los avances del proyecto para poder hacer un seguimiento saludable del proyecto|


## 1.3. Segmentos objetivo.
| |Segmento 1 | Segmento 2  |
| - | - |-|
| Variables                 |  Usuarios interesados en participar de actividades de ayuda social o en donar | ONG |
| Geográfica                | En el Perú, de entre 1,200 personas el 93% de estas estan interesadas en participar en actividades de ayuda social (CenDE, 2023) | Existen más de 1000 ONG en el Perú (SIGCTI,2024), no obstante solo se reconocen de 10 principalmente (CenDE ,2023) |
| Demográfica               | Edades de entre 17 a 50+ años <br> Genero: Masculino y Femenino | Organizaciones registradas como ONG |
| Psicológica               | Piensa en participar de actividades sociales o de donaciones en algun momento mas las limitaciones como el tiempo, la disponibilidad economica, la fiabilidad de las ONG que busca o el proceso de inscripcion terminan desanimandolo | Estas Organizaciones requieren de mas donaciones o participantes para sus campañas u eventos y buscan formas de aumentar el impacto general de estos mismos. |
| Función de comportamiento | Actitudes: Tiene una idea de que es una ONG pero en su mayoria no sabe como puede participar o no sabe de los eventos actuales en los cuales puede formar parte, algunos no conocen otras ONG y otros tienen la motivacion pero no saben si las ONG que encuentren haran correcto uso de lo donado <br> Conocimientos: Sabe que es una ONG, tiene entendido que existen organizaciones fraudulentas que se hacen pasar por ONG, normalmente no sabe si se cumplio el objetivo despues de participar| Actitudes: Hacen todo lo posible para que las donaciones lleguen en su mayor porcentaje a los más necesitados, hacen proyectos de ayuda social sin hacer mucho uso de data analitics<br> Conoce: Saben quienes requieren de ayuda, un estimado de cuanto se necesita o que se necesita para considerar donaciones, organizan eventos para concientizar y poder apoyar. |

---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | Realizamos este análisis a fin de poder conocer el mercado al que nos enfrentamos en un inicio, para de esta manera poder evaluar las estrategias adoptadas por plataformas ya existentes, y así aprender de sus aciertos y errores. |


| |  | (Nosotros)| CauseVox|  Bloomerang | Logalto |
|-|-|-|-|-|-|
| PERFIL| Overview | Plataforma que facilita el proceso de gestionar proyectos y recolectar datos de estos mismos proporcionando asi una herramienta versatil para un objetivo concreto.  | Plataforma de recaudación de fondos que brinda herramientas necesarias para crear campañas llamativas para cumplir su meta de donación. | Cuenta con distintas herramientas de gestion, es de alcance global y tiene mas de una forma de apoyar a las ONG. |Es un Programa web colaborativo para el monitoreo y la evaluación de proyectos de desarrollo internacional la cual proporciona una alta gama de herramientas de gestion de proyectos.|
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? | Mientras que facilita el proceso de gestion de proyectos y ofrece oportunidades de mejora. Tambien facilita y optimiza la recolecion de datos. | Cuenta con herramientas que le permiten al usuario personalizar su propia campaña para recaudar fondos con su logo e imágenes con las que atraer potenciales donantes. |Permite categorizar los proyectos en 9 categorías, por lo que le facilita al usuario la búsqueda de iniciativas afines a este.| Cuenta con distintas herramientas de gestion, es de alcance global y tiene mas de una forma de apoyar a las ONG.
|| Mercado Objetivo                                        | ONG peruanas, de estas mismas mas especificamente sus gestores y ayudantes del proyecto. | Organizaciones sin fines de lucro, grupos comunitarios y empresas, e individuos que deseen financiar dichas iniciativas. | Personas de México que quieran apoyo para financiar un proyecto, organizaciones sin fines de lucro, e individuos que deseen financiar dichas iniciativas. | proyectos de desarrollo, ONG y fundaciones, ministerios, instituciones de gobierno y proveedores de fondos.|
| Perfil de marketing                                     | Estrategia de Marketing | Se hacen uso de redes sociales y de publicidad en línea | Publicidad por redes y publicidad en línea | Marketing por influencia, publicidad por redes |Publicidad por redes sociales.|
| Perfil del producto                                    | Productos y servicios | Aplicación web orientada a la gestion de proyectos de Organizaciones sin fines de lucro haciendo anlisis de datos, ofreciendo sugerencias y oportunidades de mejora, al mismo tiempo que facilita y agiliza el proceso de recoleccion de datos.| CauseVox es una plataforma de recaudación de fondos que facilita la creación y gestión de campañas de recaudación de fondos en línea. | Bloomerang ayuda a organizaciones sin fines de lucro a mejorar la experiencia de donación, ahorrar tiempo y a recaudar más fondos.| Loaglto es programa web colaborativo para el monitoreo y la evaluación de proyectos de desarrollo
 || Precios y costos                                        | Para las ONG se implementa un modelo estrictamente de pago el cual debe variar segun la cantidad de participantes en el proyecto o por el tamaño de la ONG | De pago | Gratuito | De pago|
|| Canales de distribución (Web y/o Móvil)                 | Web y Móvil Web | Móvil Web | Web y móvil Web ||
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores |  | Nosotros | CauseVox| Bloomerang | Logalto |
|-|-|-|-|-| - |
| Análisis SWOT | Fortalezas |- La aplicación cuenta con una función de gestion efectiva.<br>- Se presenta un modelo de organizacion facil de entender.<br>- Facil recolecion de datos y analisis.| - Permite la personalización completa del aspecto de las páginas de campaña.<br>- Herramientas para la promoción en redes sociales. | - Cuenta con servicio al cliente en tiempo real.<br>- La plataforma es accesible y fácil de usar para crear y gestionar campañas, y realizar estrategias de marketing por correo. | - Diferentes Funcionalidades para gestion de proyectos <br> -Multiples herramientas de seguimiento y planificacion <br> -Mas tiempo en el mercado. |
|| Debilidades   | - Limitación de recursos para el financiamiento de la promoción de la aplicación.<br>- Competencia con plataformas similares. | - Limitaciones en su alcance de mercado. | - Los precios de su servicio es elevado. | - Saturacion de herramientas. <br> - Proceso agobiante <br> - No es muy intuitivo. | 
|| Oportunidades | - Crear alianzas con ONGs o empresas podría mejorar el alcance de la aplicación.<br>- El aumento de conciencia social y de la disposición para apoyar a ONGs.<br>- La expansión de la aplicación a regiones extranjeras. | Desarrollar nuevas funcionalidades para mejorar la experiencia de usuario. |  La expansión de la aplicación a un público más amplio al ofrecer tipos de suscripción alternos y a menor precio.| - Separar las herramientas por paquetes que necesite el usuario. | 
|| Amenazas      | - La existencia de competidores establecidos.<br>- Preocupaciones sobre la seguridad de datos y las transacciones de las donaciones. | - Al ser un servicio de pago, potenciales organizaciones podrían optar por opciones accesibles. | - La aparición de competencia emergente.<br>- La desconfianza hacia algunas organizaciones benéficas por la percepción del mal manejo de fondos. | - La necesidad de una herramienta facil de usar que no requiera gran cantidad de funciones para lograr un solo objetivo. |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿Que navegadores y dispositivos usa? 

**Entrevistas usuario segmento 1**
1. ¿Cuando piensa en gestionar un proyecto en que piensa principalmente?
2. ¿Que metodos utiliza para organizar a sus ayudantes y como les asigna tareas?
3. ¿Que herramientas usa para gestionar o planificar proyectos?
4. ¿Como analiza sus datos, que herramientas/metodos usa?  
   
**Entrevistas usuario segmento 2**
1. ¿Que actividades son las principales en los eventos y como se las asignan? 
2. ¿Como recolectan informacion de los participantes, que herramientas?
3. ¿Como hacen llegar esta informacion a los gestores de proyecto?
4. ¿Si sucede un inconveniente el cual se debe de notificar al gestor del proyecto como se comunica con este, cree que la comunicacion con el gestor de proyecto es efectiva? 
### 2.2.2. Registro de entrevistas.
**Segmento 1**  
Nombre: Maria Jose Melendez
Edad: 53 años 
Ocupación: Directora de Hogar (CAEF)
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS1E1.png)  
[Seg1 - Entrevista - 1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ERgJ0_AWCqVErNukgws7eiIBIgGIeuzeYyiSeb76MeGP9w?e=f7I1Pt&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

En la entrevista Maria nos cuenta de como su ONG no tiene una herramienta de gestion determinada y como normalmente usan Excel para los analisis de sus datos, tambien relata que para la planificacion se hacen reuniones anuales y mensuales.

Nombre: Cesar Alva Posada
Edad: 57 años 
Ocupación: Sociologo encargado de Gestion de Proyectos  
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS1E2.png)  
[Seg1 -Entrevista - 2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESDqRfzRGHFMsuxKkO5AzPgB5n2DN_YAREAKth0-NdKi-A?e=2FxzuN&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

En esta entrevista Cesar explica como la metodologia que se usa es importante a la hora de organizarse asimismo nos comento de otras herramientas que se implementan para la gestion, no obstante tambien menciona que todos estos procesos se hacen de manera separada. Asimismo para la gestion de datos utiliza excel.

Nombre: Guilder Quiñones Aldean
Edad: 54 años 
Ocupación: Jefe de Proyectos  
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS1E3.png)  
[Seg1 - Entrevista - 3](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESDqRfzRGHFMsuxKkO5AzPgB5n2DN_YAREAKth0-NdKi-A?e=2FxzuN&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

El Jefe de Proyecto Guilder comparte su vision respecto a las herramientas usadas, de manera parecida a la entrevista anterior el usa excel para manejar sus datos mas tambien hace uso de programas de gestion como trello.

**Segmento 2**  
Nombre: Luis Herrera Gonzales
Edad: 19 años 
Ocupación: Estudiante - Ayudante 
![Imagen de entrevista](../assets/Entrevistas/EntrevistaS2E1.png)  
[Seg2 - Entrevista - 1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESesnqbIKNBIj2P7j6CMxpsBuPL5ecH8TMAAxZh29afhHw?e=pCWved&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Luis nos cuenta de como participa de estas actividades usando whatsapp como su principal fuente de recoleccion de datos y comunicacion con su gerente, menciona que tanto el uso del correo electronico y uso de whatsapp son obsoletos, toman mucho tiempo y no demuestran el nivel de formalidad deseado.

Nombre: Alvaro Jimenez
Edad: 19 años
Ocupación: Estudiante - Ayudante 
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS2E2.png)  
[Seg2 - Entrevista - 2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESskiDGzwCZLrHJVscTBOOoBK0Bx2Q6u2aFn2dDAv0RB8w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=smRneZ)

Alvaro comenta sobre su experiencia como voluntario ayudante en una ONG. Se menciona como es la distribucion de tareas y la comunicacion entre los ayudantes y el gestor del proyecto. Tambien menciona que no es eficiente ni rapida la gestion de la organizacion y que el espera se pueda mejorar en algun futuro.

Nombre: Pol Landeo
Edad: 27 años 
Ocupación: Ayudante en una ONG
![Imagen de entrevista](../assets/Entrevistas/EntrevistaS2E3.png)  
[Seg2 - Entrevista - 3](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/EVTCV3Z3klZEunW6DHRtpU4BIwJk7OE6UEs4NEG5tWiMpQ?e=l3SrWz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Pol nos cuenta que en su día a día hace uso de las herramientas de google para la administración de tareas y la comunicación con el gestor del proyecto, menciona que la comunicación con el gestor del proyecto es efectiva pero que la gestión de tareas no es tan eficiente. En cuanto a la recolección de datos, menciona que se hace de manera manual, por lo que sería de gran ayuda contar con una herramienta que facilite este proceso.


### 2.2.3. Análisis de entrevistas.
**Segmento 1:**

En el segmento 1 existe una preferencia en usar excel para el analisis de datos recibidos, las multiples herramientas para un proyecto y en base a que entregan sus tareas a sus colaboradores. Se puede observar que la mayoria no utiliza tecnologia y que a escala de necesidad sienten que puede resultar util. Mas no tienen mucho conocimiento de la tecnologia implementada.

**Segmento 2:**
Respecto al segmento 2 se nota una tendencia respecto a la necesidad de una herramienta la cual pueda obtener la informacion y mandarla al proyecto de manera efectiva y rapida, Asimismo de como se requiere de una plataforma para poder comunicarse con el supervisor.

## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento 1:**  
![Imagen User Persona 1](../assets/requirements-images/user%20persona_jefe.png)
**Segmento 2:**
![Imagen User Persona 1](../assets/requirements-images/user%20persona_organizadores.png)


### 2.3.2. User Task Matrix.
| ‎ | ‎  | Segmento 1  | Saul BuenHombre | Segmento 2  | Manuel Torres |
| --- | ------ | ----------- | ------------ | ----------- | ---------- |
| ID  | Titulo | Importancia | Frecuencia   | Importancia | Frecuencia |
| HU01 | Listado de proyectos a realizar | Alta | Alta | Media | Baja |
| HU02 | Actualizaciones de nuevos proyectos | Media | Media | Alta | Media |
| HU03 | Asignación de tareas del proyecto | Alta | Alta | Alta | Alta |
| HU04 | Calendario con fechas importantes | Media | Media | Alta | Alta |
| HU05 | Dashboard estadístico simple | Alta | Media | Media | Baja |
| HU06 | Lista de tareas completadas | Alta | Media | Alta | Media |
| HU07 | Generación de resúmenes | Alta | Alta | Media | Baja |
| HU08 | Status automático del proyecto | Media | Baja | Media | Media |
| HU09 | Registro de detalles en el proyecto | Alta | Baja | Alta | Media |
| HU10 | Solicitud de recursos | Alta | Media | Media | Media |
| HU11 | Fechas a expirar | Baja | Baja | Media | Baja |
| HU12 | Estimación de gastos  | Alta | Alta | Alta | Media |
| HU13 | Límite máximo de presupuesto | Alta | Media | Alta | Media |
| HU14 | Registro de gastos | Alta | Alta | Alta | Media |
| HU15 | Directorio de contactos | Media | Alta | Media | Alta |
| HU16 | Recomendaciones sobre el buen manejo de proyectos | Alta | Media | Alta | Alta |
| HU17 | Picos de riesgo | Alta | Alta | Alta | Media |
| HU18 | Documentos legales | Alta | Media | Media | Baja |
| HU19 | Gestión de donaciones | Alta | Media | Alta | Media |
| HU20 | Promoción y seguimiento | Media | Media | Baja | Baja |
### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?

Good

- Herramienta multi usos
- Devuelve un analisis completo
- Mantiene Comunicacion entre segmentos
  
Bad

- Concepto de codigo probablemente complicado la primera vez
- Acostrumbrarse al workflow
- Innovacion

**Onboarding and first use:**

Good

How can they feel successful?
- Se reduce el tiempo de planificacion
- Se asignan tareas facilmente
- Se pueden gestionar multiples proyectos

Bad  

- Multiples proyectos al mismo tiempo
- Falta de conocimiento en la gestion del software

**Sharing:**

Good

Why would they invite others?
- Organizacion con mejores resultados.
- Resultados que se pueden demostrar por estadisticas.
- Servicio economicamente accesible.

Bad

- Nuevo para las ONG mas antiguas
- Requerimiento de data para funcionar al 100%

### 2.3.4. Empathy Mapping.
**Segmento 1:**
![Empathy Map Segmento1](../assets/requirements-images/user_persona-segmento1.png)

**Segmento 2:**
![Empathy Map Segmento1](../assets/requirements-images/user_persona-segmento2.png)

### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: Gestor de proyecto realiza su labor sin una herramienta que lo beneficie

As Is:
| Fases|        |       |      |     |
|----------|---------------|----------|--------------|-------------|
| Doing          | Realizando tareas de gestión de proyectos manualmente | Investigando posibles beneficiarios de donaciones | Contactando a los ayudantes que van a participar | Realizando seguimiento de datos en hojas de cálculo o documentos físicos |
| Thinking       | Considerando la eficacia de los procesos manuales actuales | Evaluando la credibilidad de las fuentes de información sobre beneficiarios | Reflexionando sobre la necesidad de una conexion mas profesional y continua con sus compañeros | Pensando en la necesidad de herramientas digitales para mejorar la gestión de proyectos |
| Feeling        | Preocupado por la eficiencia y precisión de los métodos manuales | Inquieto por la falta de garantías en la calidad de la información recopilada | Preocupado por la posibilidad de que suceda algo y no pueda contactarse | Frustrado por la falta de herramientas digitales que agilicen y optimicen el proceso de gestión de proyectos |



**Segmento 2**  
Escenario: Ayudante del proyecto es enviado a manejar el proyecto de manera presencial

As Is:
| Fases     |       |       |        |    |
|----------|----------------|------|---------|-----|
| Doing          | Realizando entrevistas en persona con posibles beneficiarios de donaciones | Implementando métodos manuales para la recolección de datos en el terreno | Colaborando activamente con el segmento objetivo 1 para entender las necesidades de información específicas | Explorando opciones de recolección de datos |
| Thinking       | Reflexionando sobre la relevancia de los datos recopilados en el contexto local | Evaluando la eficacia de los métodos manuales utilizados en el terreno | Considerando estrategias para mejorar la comunicación y colaboración con el segmento objetivo 1 de manera presencial | Evaluando la utilidad y seguridad de las herramientas de recolección de datos |
| Feeling        | Comprometido con la precisión y relevancia de los datos recopilados de manera presencial | Optimista sobre la efectividad de los métodos de recolección de datos en terreno | Satisfecho al contribuir de manera activa al proceso de gestión de proyectos en el lugar | Esperanzado por encontrar herramientas eficaces para la recolección de datos en entornos presenciales |



## 2.4. Ubiquitous Language.
```
Texto ubiquo: Se trata de un glosario de términos 
del dominio para mantenernos comunicados y actualizados, 
tanto el equipo como los stakeholders, relacionados al sector 
en el que se especializa la startup.
```

**1. Organización benéfica:** Una entidad sin fines de lucro que busca apoyar causas sociales, humanitarias o ambientales a través de donaciones.

**2. Necesidades benéficas:** Los artículos, suministros o recursos específicos que una organización benéfica requiere para llevar a cabo sus actividades o programas.

**3. Gestor de Proyecto:** Segmento Objetivo que representa a los gestores o supervisores del proyecto los cuales son encargados por las ONG en realizar un proyecto estos pueden trabajar solos o en grupos dependiendo de los objetivos de la ONG, finitamente estos son los que deberan revisar y analisar los datos recolectados.

**4. Lista de necesidades:** Una lista detallada de los artículos o suministros específicos que una organización benéfica necesita recibir como donación.

**5. Proyecto:** El proyecto se define como la idea de crear un evento ya sea de accion social o de donacion como lo que puede ser una recolecta de basura en la playa o un evento de donacion de polos. En nuestra aplicacion web se debera definir si se hace un evento de donacion o de accion social.

**6. Registro de costos:** Un registro de los costos asociados con la realización de un proyecto o evento benéfico.

**7. Ayudante de proyecto:** Segmento objetivo que representa a los ayudantes reclutados por la ONG para que esten en el evento para que se mantenga el orden y se siga lo planeado segun el proyecto, estos seran asignados de recolectar los datos.

**8. Usuario receptor:** Una organización benéfica que está registrada en la plataforma y que busca aumentar su impacto.

**9. Registro de asistentes:** Un registro de los participantes de los proyectos realizados por los usuarios, que puede incluir información demografica, geografica o incluso encuestas de opinion.

**9. Asignación de tareas:** La distribución de tareas específicas a los miembros del equipo de la ONG para llevar a cabo un proyecto o evento benéfico.

**10. Registro de costos:** Un registro de los costos asociados con la realización de un proyecto o evento benéfico.
