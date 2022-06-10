# Introducción

Este proyecto surge no solo por el motivo que la materia presenta con el fin de poder presentar una solución, ya sea un bien o un servicio ante un problema o necesidad. Sino como un conjunto de necesidades tanto de a quién va destinado el uso de proyecto, sino como también necesidades personales de quien lo desarrolla a fin de poder adquirir nuevas habilidades para poder crecer tanto personal como profesionalmente.  
Es así como en el transcurso del desarrollo del proyecto, que comenzó desde cero, tanto en el uso de técnicas, así como de conocimiento, fue un constante aprendizaje en el cual en muchas ocasiones se tuvo que rever y replantear gran parte del mismo. Ha sido una experiencia ardua pero sumamente satisfactoria, plagada de situaciones en las cuales, a modo de ejemplificar, cuando se creía llegar a la cima de la montaña se encontraba con picos aún más altos que no estaban a primera vista.  
Así fue como comenzó y continua mi odisea en el desarrollo de software. Espero que este proyecto no solo sirva como referencia de, sin importar que, aquello que deseamos se puede cumplir si trabajamos lo suficiente en ello, sino que ayude a quien no tenga ninguna experiencia ni conocimiento en el campo de desarrollo de software a poder lograr una idea básica de lo que este arte trata. 

### Una necesidad Personal

Los motivos personales de como comenzó este proyecto se remontan hace muchos años atrás. Toda mi vida me dedique a la informática, trabaje los últimos 20 años en ella. Sin embargo, el desarrollo de software siempre fue un gran pendiente en mi portafolio de habilidades. Nunca me hice de la *voluntad* para empezar a estudiar sobre ello por diferentes motivos. Fue así hasta el año 2021 en el cual decidí dar un giro a mi carrera y empezar el camino hacia ser un desarrollador de software a tiempo completo.  
Fue ahí cuando en esa etapa tan temprana de no saber absolutamente nada empecé a buscar en mi día a día una idea, de que poder crear, necesitaba tener metas fijas las cuales poder utilizar para aprender lo que era conveniente y no todo lo que existe ya que el campo del desarrollo de software es inmensamente amplio. Para poder llegar a mi misión, necesitaba un proyecto, el cual me llevara paso a paso a descubrir todas las etapas las cuales me iba a enfrentar.

> El desarrollo completo de este proyecto fue basado en la forma más básica y más potente que tiene cualquier persona de lograr sus objetivos.
>
> 1. Informarse.
> 2. Estudiar.
> 3. Aplicar.
> 4. ***Fallar***.
> 5. Corregir.
> 6. Controlar o mejorar.
> 7. Volver al paso 1.  


# Identificación del problema

Trabajo en una escuela desde hace más de 10 años, en la cual mi actividad es la de mantener toda la infraestructura informática. Eso contempla, computadoras de las diferentes áreas, así como también toda la estructura de red y los servidores asociados a ella. En este tiempo fueron muchos los problemas que surgieron, sin embargo, hay uno puntualmente que nunca se le pudo dar solución. Este problema se refiere al manejo de la información dentro de la escuela y la coordinación de dicha información entre las diferentes áreas.  

La información a la cual me refiero es la siguiente:

- Matricula de alumnos
- Calificaciones
- Asistencia
- Legajos
- Reportes de diferentes indoles
- Informes
- Estadísticas
- Actas y notas 

Esta información siempre fue manejada utilizando Excel y Word. Se detallará a continuación cuales son los problemas y dificultades que el uso de estas tecnologías genera. Algunas son por una limitación de tecnología en sí y otras por el factor de su complejidad de uso en ciertas circunstancias.

- Es sumamente difícil estandarizar nombres de archivos y locación donde los mismos se guardan. Esto puede ser ya sea por omisión del usuario de seguir estándar al guardar o escribir el nombre del archivo. O por error involuntario del mismo.
- Si bien tanto Excel como Word presentan la posibilidad de generar plantillas para que se intente tener para todos la misma estructura en la cual se muestra la información, es posible que ya sea por el error humano mencionado con anterioridad o un error de compatibilidad entre las diferentes versiones de Word o Excel instaladas en las diferentes maquinas (de bien de uso de la escuela así como particulares) esta plantilla se "rompa" y termine siendo un verdadero dolor de cabeza corregir esos errores más cuando el archivo ya fue cargado con información.
- Cuando la cantidad de información es muy grande, por ejemplo, una matrícula la cual cuenta con cientos o miles de entradas se corre un gran riesgo al utilizar esa información sobre un Excel. Algunos de los motivos se detallan a continuación:  

  - Es posible modificar valores sin darse cuenta y guardarlos junto cambios realizados legítimos.
  - No se puede tener control de quien o cuando se cambió la información.
  - Lentitud en general, estas planillas son grandes y pesadas. El problema aumenta al trabajar con archivos en una red o más aun cuando se trabaja con estos archivos por internet.
  - Uso de filtros complejo y poco amigable. Además, los filtros pueden quedar guardados generando que quien abre después la planilla no tenga toda la información disponible.

- No existen tecnologías que vengan ya con Excel y Word que hagan un respaldo de la información, esta debe ser aplicada de forma externa al mismo.
- Serias limitaciones de esta tecnología para poder compartirlas a través de internet. Este es un factor sumamente importante.
- Si bien en las planillas de Excel se pueden crear macros (código de programación dentro de una planilla de Excel) esta es sumamente lenta e inestable. Pude romperse el código con facilidad dejando la planilla inútil.
- Cuando las planillas de Excel aumentan en complejidad, las cuales tienen varias hojas y vínculos entre ellas se corre un gran riesgo de que se rompan los mismos dejando las planillas inútiles.
- Corregir cualquier tipo de problema que tenga una planilla de Excel o incluso una simple tabla en Word lleva mucho tiempo.

De lo mencionado anteriormente se puede determinar que los problemas son los siguientes:

- Minimizar la posibilidad de falla humana.
- Falta de estandarización de una forma de trabajo.
- Falta de estandarización en la manera que se ingresan datos.
- Falta de control de quien puede o cuando cambio datos.
- Falta de un lugar único donde todos los datos este disponibles y ordenados.
- Falta de accesibilidad de la información a través de internet.
- Falta de preservación de datos.

Como problemas secundarios se puede mencionar:

- Lentitud de la tecnología.
- Lentitud al trabajar sobre la misma.
- Disconformidad de parte de usuario por fallas recurrentes.
- Desmotivación.
- Se pierde mucho tiempo en corregir errores y fallas.

# Búsqueda de información (primera parte)

Dentro de la información que se recaudó a fin de obtener una posible solución se utilizó:

- Búsquedas en general en internet, foros, blogs, buscando como poder mejorar la situación utilizando en primera medida las herramientas y tecnologías que ya estaban en uso.
- Consultas a otras instituciones para ver si alguna de ellas tenía una solución digital ya funcionando. Ninguna de ellas contaba con una digitalización de su información, y de tener alguna estaban en la misma situación, utilizaban Excel o Word.
- Búsquedas en internet de software [^software] empaquetado (El software empaquetado es aquel que ya viene terminado y cerrado, no se pueden realizar cambios sobre el mismo, se debe utilizar como viene)
- Búsquedas de proveedores de soluciones digitales de software empaquetado y a medida.
- Consultas a profesionales en desarrollo de software a fin de pedir presupuestos para la realización de un software a medida.

# Identificación de las soluciones 

Durante el transcurso de los años se intentó incorporar otra tecnología o métodos que dieran solución a los problemas mencionados con anterioridad. De la búsqueda de información se pusieron en juicio varias posibles soluciones, algunas de ellas fueron implementadas y otras descartadas de inmediato al analizar que no iban a poder ser implementadas. Las posibles soluciones las cuales se detallan a continuación y cuáles fueron los motivos por las que fallaron.

- Capacitación al personal para lograr estandarizar las formas de trabajo. FALLO (falta de predisposición tanto de directivos como personal en recibir capacitación)
- Generar carpetas donde guardar la información en los servidores [^servidor] y tener un espacio de trabajo único. FALLO a medias (si bien el personal empezó a utilizar dicho espacio, no hubo forma de estandarizar la manera que lo hacía, guardaba o escribía la información.)
- Adquirir un software de gestión ya echo que se utilizara en otras instituciones educativas. FALLO (debido a la particularidad de la institución hacía falta que el software tuviera un formato muy específico)

Fue aquí, después de agotar todas estas opciones cuando decidí plantear crear un software a medida, era la situación ideal para poder crear mi propio proyecto, el mencionado anteriormente y poder satisfacer las necesidades de la institución.

Dentro de las ventajas de que alguien que está trabajando dentro de la institución haga un software así son:

- Conocimiento profundo de las necesidades institucionales.
- Conocer al personal.
- Comunicación directa con los futuros usuarios.
- ***Acceso a la información ya echa con otras tecnologías y adaptarlas a una nueva. ***
- Crear una aplicación en conjunto desarrollador/usuario.
- Confianza.
- Sin costos extras.

# Búsqueda de la información (segunda parte)

Una vez decidido que se iba a realizar un software a medida, y que iba a ser desarrollado por mí. Seguía buscar la mayor cantidad de información posible teniendo en cuenta los siguientes puntos:

- En que lenguaje [^lenguaje] se iba a realizar el desarrollo.
- Que herramientas se iban a utilizar.
- Cuales eran las tecnologías que se iban a asociar al lenguaje a fin de obtener los mejores resultados.
- Como iba a ser el diseño de la aplicación.

Esta etapa fue bastante larga y en ciertos momentos abrumadora. Partiendo desde cero se vio en primera instancia que iba a ser un camino recto y fácil de llevar a cabo, sin embargo, con el correr de la investigación se izó cada vez más evidente de la enorme cantidad de información que había por delante.  

#### El lenguaje

En primera medida había que definir de forma clara que lenguaje se iba a utilizar. Como se mencionó en la parte de palabras técnicas, existen cientos de lenguajes diferentes. La búsqueda de información acerca de cuál elegir se basó en los siguientes conceptos:

- Popularidad 
- Acceso a grandes fuentes de información de cómo utilizar el lenguaje. Ya sea documentación oficial, foros, tutoriales en YouTube.
- Una enorme y predispuesta comunidad. Todos los lenguajes tienen una comunidad de gente que está dispuesta a brindar sus conocimientos y experiencias de forma abierta y gratuita. Esto es de vital importancia ya que se trataba de un proyecto independiente.
- Que sea multipropósito (Tanto para crear el Frontend [^frontend] como el Backend [^backend])
- Que sea multiplataforma (Se refiere a que se pueda ejecutar el software en cualquier tipo de pc, sin importar que sistema operativo [^operativo] tenga, o que tipo de dispositivo sea, computadora, celular o Tablet)

Después de una larga búsqueda el lenguaje seleccionado y que cumplía todas estas pautas fue el llamado JavaScript. JavaScript es un lenguaje el cual tiene una gran flexibilidad y es el lenguaje más popular en la actualidad, según la página www.stackoverflow.com el foro más popular a nivel mundial de programación.

![JavaScript popularidad](../assets/JavaScript.jpg)

Sin embargo, un solo lenguaje no es suficiente para crear una aplicación con todas las características que este proyecto necesita. Además de JavaScript los lenguajes HTML y CSS son necesarios también para logar crear un Frontend que sea funcional e intuitivo. Cabe resaltar que HTML y CSS ocupan el segundo lugar de los lenguajes más utilizados a nivel mundial.

#### Herramientas

Dentro de las herramientas hay que separar dos categorías:

- Herramienta física/hardware (Una computadora, cualquiera sea es suficiente, no hace falta una computadora especial para crear software y ni tiene que ser la más potente o moderna, tampoco es necesario un sistema operativo especial, cualquiera sirve, el único requerimiento es que tenga conexión a internet)

- Herramientas lógicas/software (Uno de los motivos de por el cual se eligieron los lenguajes anteriormente mencionados fue que estos tienen la enorme flexibilidad de poder ser escritos literalmente en cualquier aplicación de texto, es decir, se puede programar utilizando el bloc de notas de Windows, o Word, aunque sea muy irónico nombrarlo. Es decir, no es necesario una aplicación especial para escribir el código. Sin embargo, existen aplicaciones especializadas que ayudan al trabajo en gran medida.)  
Dentro de las herramientas que se van a utilizar se pueden mencionar:  

    - NeoVim (Un editor de código. Si bien su uso es complejo, ya que de entrada no viene con nada más que la posibilidad de escribir texto, y no se utiliza el mouse, todo debe realizarse con comandos de teclado. Cuenta con una enorme flexibilidad de poder adaptar el mismo al capricho del usuario volviéndose una herramienta a medida muy poderosa y llena de plugins [^plugin] que se pueden instalar a fin de aumentar la productividad)  

    ![nvim](../assets/nvim.jpg)

    *Terminal de nvim con código fuente, se puede apreciar como el texto debe ser ordenado a fines de facilitar su lectura, así como también los colores que se ven son el resultado de la herramienta que colorea palabras según un patrón para facilitar también su letura.*  

    - Una terminal (Un terminal es un programa en sí mismo que viene en todos los sistemas operativos, se utiliza principalmente para leer y ejecutar comandos que el usuario envía mediante el teclado. Además, en desarrollo de software se vuelve esencial ya que a través de la terminal se leen problemas detectados al momento de ejecutar un software) 

    ![terminal Vacía](../assets/terminalVacia.jpg)

    *Una terminal vacía esperando un comando.*

    ![terminal Llena](../assets/terminalLlena.jpg)

    *Una terminal con información en tiempo real de la ejecución de un software.* 

    - Un navegador web: Ya que esta aplicación estaba pensada para realizarse de entrada con acceso a internet era necesario programarla para que se ejecute en un navegador web. El más popular de todos es Google Chrome, pero también puede utilizarse otros como Mozilla Firefox, Internet Explorer, Edge, etc.

    ![Google Chrome](../assets/chrome.jpg)

    *Una ventana de Chrome vacía*

    No solo se necesita el navegador, hay una herramienta que viene con todos los navegadores que se llama consola. En esta herramienta se muestra en formato de código todo lo que en ese navegador está pasando. Si tiene curiosidad abran cualquier página web que Uds. frecuenten y presionen la tecla f12 en su teclado. Automáticamente una consola se abre mostrando como lo que Uds. ven como resultado final debe ser escrito para que así sea.

    ![consola Chrome](../assets/consolaDeChrome.jpg)

    *Una consola de Chrome mostrando el contenido de una página*

#### Tecnologías

JavaScript, HTML, CSS, NeoVim, Chrome de por sí ya son tecnologías, así como un serrucho lo es también, sin embargo, una sierra eléctrica es una tecnología evolucionada que extiende la utilidad de la misma, la hace más funcional y lograr el mismo trabajo con mucho menor esfuerzo. Esto no es ajeno a las tecnologías en desarrollo, es por ello que como fruto de la búsqueda de la información se llegó a adoptar las siguientes tecnologías "evolucionadas" para realizar el proyecto.

- MongoDb (MongoDb es una base de datos especialmente diseñada para crear ámbitos modernos, escalables y sumamente potentes)

- Express (Es un framework especialmente diseñado para NodeJs el cual está pensado especialmente para crear aplicaciones web y APIs [^apis])

- NodeJs (Utiliza JavaScript para crear aplicaciones del lado del backend, tiene como principal objetivo ser multiplataforma y que tenga una gran escalabilidad. NodeJs se basa en el motor V8 de Google)

- React (React nace de la mano de un monstruo del campo. Fueron los ingenieros de Facebook los que crearon esta librería [^librería] que combina JavaScript, HTML y CSS en un solo archivo. React fue especialmente diseñado para la creación de Frontend y sus interfaces de usuario.)

De la combinación de estas 4 tecnologías si se toma la primera letra de cada una conforma un conjunto llamado MERN. Toda la aplicación se basa en la combinación de estas 4 tecnologías.

![MERN](../assets/MERN.jpg)


# Diseño 

La siguiente lista de pautas a cumplir fue la primera etapa del diseño. Donde se preguntó, como quiero que sea la aplicación.

- La aplicación será en primera medida diseñada para correr sobre un navegador web.
- Esta debe ser accedida a través de internet internet.
- Debe tener una seguridad por usuario y privilegios de acceso dentro de la aplicación.
- Debe encriptar las claves de usuario.
- Debe usar un token[^token] a fin de garantizar una seguridad optima.
- Debe ser escalable.
- Debe ser modular.[^modular]
- Debe implementar el patrón REST.[^rest]
- Debe ser un servicio montado en la nube y no de forma local.
- Debe tener una interfaz de usuario simple y fácil de entender.

#### Mas tecnologías

Para poder garantizar los requerimientos del diseño se deben adoptar más tecnologías las cuales se nombran a continuación:

- Firebase: Firebase es un servicio de Google que permite la implementación de aplicaciones web tanto para el Frontend como para el Backend. Esto soluciona varios puntos. La aplicación puede ser accedida desde internet, es un servicio en la nube y este puede ser accedido por un navegador web.

- JWToken: Jason Web Token se utiliza para esconder información sensible y que esta no pueda ser alterada ya que posee una firma digital que se encuentra escondida en el backend y esta se compara cada vez que se manda una acción en la aplicación.

- Bcrypt: Bcrypt es un encriptador que se utiliza para que los usuarios una vez creada la clave, esta se encripta y no pueda volverse a su estado anterior. Para comprar 2 claves ambas deben de ser encriptadas a fin de saber si son coincidentes.

- Mongoose: Es un framework especializado para trabajar en conjunto con NodeJs y MongoDb. Simplifica el trabajo de realizar consultas a la base de datos.

- Bootstrap: Bootstrap es un framework [^framework] creado por Twitter, fue pensado para crear el layout [^layout], especialmente pensado para que sea un diseño que se adapte a los diferentes tipos de pantalla y sus tamaños.

- React-Bootstrap: Es la implementación de Bootstrap pensado especialmente para el uso con React.

- Redux: Redux es un manejador de estado[^estado] que abstrae el estado de un componente para que este pueda ser accedido desde cualquier otro sin necesidad de pasar la información de padre a hijo[^padreahijo]. 

- React-Redux: Es la implementación de Redux especializada al uso con React.

### Etapas del proyecto

Para garantizar una forma de trabajo segura se determinaron las siguientes etapas, algunas de ellas ya están terminadas y otras deben ser creadas.

##### BackEnd

- Crear un servidor que maneje la seguridad, la conexión a la base de datos y la API.  
    - [x] Loing.  
    - [x] Seguridad.
    - [x] Matricula
    - [x] Usuarios.
    - [ ] Calificaciones.
    - [ ] Asistencia.
    - [ ] Reportes.
    - [ ] Informes.
    - [ ] Tutores.

- Crear una base de datos en MongoDb con su estructura y datos.
    - [x] Loing.  
    - [x] Seguridad.
    - [x] Matricula
    - [x] Usuarios.
    - [ ] Calificaciones.
    - [ ] Asistencia.
    - [ ] Reportes.
    - [ ] Informes.
    - [ ] Tutores.

- [x] Implementar el servidor en la nube para que la API pueda empezar a utilizarse.



##### FrontEnd

- [x] Crear el módulo de ingreso de los usuarios. (Módulo de login)

![login](../assets/login.jpg)
- [x] Crear el módulo de administración de usuarios, privilegios y claves. 

![admpannel1](../assets/admpannel1.jpg)

![admpannel2](../assets/admpannel2.jpg)

- [x] Crear el módulo de panel general. 

![homepannel](../assets/homepannel.jpg)

- [x] Crear el módulo de Matricula. Con sus filtros y posibilidad de edición de datos.

![matricula1](../assets/matricula1.jpg)

![matricula2](../assets/matricula2.jpg)

- [x] Crear el módulo de ingreso de nuevo alumno a la base de datos.

![nuevoalumno](../assets/nuevoalumno.jpg)

- [ ] Crear el módulo de legajos digitales.

- [ ] Crear el módulo de asistencia.

- [ ] Crear el módulo de calificaciones.

- [ ] Crear el módulo de reportes.

- [ ] Crear el módulo de informes.

- [ ] Adaptar el diseño para hacerlo compatible con pantallas chicas.

- [ ] Crear la versión móvil.

- [ ] Extender el acceso de la aplicación a los alumnos.

- [ ] Extender el acceso de la aplicación a los tutores.

- [ ] Adaptar el diseño para que pueda ser usado por varias instituciones educativas.

 










[^servidor]: Servidor (Un servidor es una computadora especializada para estar encendida las 24 hs y que esta pueda ser accedida desde una red local o por internet. Para hacerse una idea, cada vez que alguien quiere entrar a www.google.com.ar un servidor responde a esa solicitud envidando la información necesaria para que el usuario vea en su pantalla dicha página. Cuando el usuario realiza una búsqueda, es el servidor quien en primera medida recibe los parámetros de búsqueda y ejecuta la misma para posteriormente enviar los resultados al usuario y que este los vea en pantalla.)  

[^software]: Software (Se refiere a todo programa, código, aplicación, que corre o se ejecuta en un equipo informático, ya sea, una computadora, celular o Tablet. Si bien el campo es más amplio a cuantos equipos posibles existe para que corra un software, solo nos limitaremos a computadoras, celular o tabletas) *El software es todo aquello que no es tangible, existe, pero no de forma fisica.*

[^hardware]: Hardware (Se refiere a todo componente físico que conforma un equipo informático, teclado, mouse, pantalla, parlantes, botones, etc.)

[^lenguaje]: Lenguaje (Cuando se habla de lenguaje de programación se hace referencia a cuál será el "idioma" que el desarrollador utilizará para darle indicaciones al equipo informático. Existe cientos de lenguajes diferentes, algunos generales y otros específicos, todos tienen sus ventajas y falencias.)

[^frontend]: Frontend (Hace referencia a la parte del software con la cual interactúa el usuario)

[^backend]: Backend (Hace referencia a la parte del software que está alojado en servidor, ejecuta y coordina como se va a entregar la información al Frontend, así como también maneja la seguridad)

[^operativo]: Sistema operativo (El sistema operativo es con lo primero que un usuario se encuentra al otilar un equipo informático, es en este sistema operativo que se ejecutan las aplicaciones o software, es el sistema operativo el encargado de realizar la unión entre software y hardware en caso de una computadora, este puede ser Windows o Linux, en caso de un teléfono puede ser Android, IOS -Para iPhone- o Windows Phone, para tabletas este puede ser Windows Mobile, Android o IOS)

[^plugin]: Plugin o complemento es una aplicación que permite extender el funcionamiento de otra aplicación. Sin tener que escribir código, es como pequeños ladrillos de plástico que se van uniendo para formar una estructura más compleja.

[^librería]: Una librería es un conjunto de funciones ya creadas de antemano que facilitan el trabajo de crear de cero las mismas, es decir, es un código ya escrito, probado y refinado que se puede reutilizar a criterio con el fin de acelerar la producción. 

[^framework]: Un framework no dista mucho de una librería, establece un marco de trabajo y herramientas ya creadas para facilitar la creación de contenido. La principal diferencia entre un framework y una biblioteca es que el framework está enmarcado, ya está hecho de una manera determinada y solo se puede usar lo que este contiene, mientras que una biblioteca no está ligada a nada, se pueden combinar infinitas bibliotecas sin importar quien las creo a fin de obtener el resultado deseado.

[^layout]: La palabra layout hace referencia a la manera de como los elementos que conforman una página web se disponen en el espacio en que se muestran.

[^apis]: Una API es una capa de abstracción de algo mucho más complejo que corre por detrás. Tomemos como ejemplo una casa de repuestos del automotor. Cuando vamos a comprar algo, no necesitamos saber dónde están los repuestos, de que tipo son, cuanto salen, cuantos hay, etc. Esto lo sabe quién nos atiende en el mostrador, esta persona es la API, nos abstrae a nosotros como usuarios de saber cómo funciona lo que está por detrás, solo tenemos que saber dónde ir y como pedirlo.

[^modular]: Un diseño modular quiere decir que la aplicación se fragmenta en muchos componentes más chicos capaces de combinarse de muchas maneras sin necesidad de que uno dependa del otro. Un diseño modular implementa la idea que cualquier modulo se puede reemplazar o modificar sin afectar al resto. Esto permite tener un mantenimiento más sencillo y una posibilidad de crecimiento óptimo.

[^rest]: REST es un patrón de diseño para la World Wide Web (www) en el cual se dictan pautas y modos de trabajo bien específicos a fin de obtener aplicaciones estandarizadas.

[^token]: Un token es una forma de esconder información, se toma una información sensible y se cambia por un algoritmo a algo sin sentido que luego puede ser devuelto a su estado original realizando el algoritmo en sentido contrario.

[^estado]: Un estado en una aplicación de React es como una fotografía de la aplicación en un momento dado, al cambiar algo por ejemplo llenar un formulario y hacer clic en un evento, un botón, por ejemplo, se vuelve a sacar otra fotografía de la aplicación en ese momento. Luego se comparan las 2 y solo se cambia en pantalla los objetos que tuvieron diferencia. Esto hace mucho más rápido el proceso que tener que enviar toda la página de nuevo desde el servidor y esperar que se cargue.

[^padreahijo]: Se conoce como pasar de padre a hijo cuando un módulo contiene otro en su interior. Para que el que está dentro acceda a la información de su modulo padre, este debe pasarle la información al hijo a fin de que esté disponible para ese. Esto plantea un problema cuando se tienen muchos hijos o niveles de anidamiento muy grandes en los cuales hay un ancestro común general , varios padres y varios hijos de cada uno y todos deben acceder a la misma información.
