# Introduccion

Este proyecto surge no solo por el motivo que la materia presenta con el fin de poder presentar una solucion, ya sea un bien o un servicio ante un problema o necesidad. Sino como un conjunto de necesidades tanto de a quien va destinado el uso de proyecto, sino como tambien necesidades personales de quien lo desarrolla a fin de poder adquirir nuevas habilidades para poder crecer tanto personal como profesionalmente.  
Es asi como en el transcurso del desarrollo del proyecto, que comenzo desde cero, tanto en el uso de tecnicas asi como de conocimiento, fue un constante aprendizaje en el cual en muchas ocaciones se tuvo que reveer y replantear gran parte del mismo. A sido una experiencia ardua pero sumamente satisfactoria, plagada de situaciones en las cuales a modo de ejemplificar, cuando se creia llegar a la cima de la montaña se encontraba con picos aun mas altos que no estaban a primera vista.  
Asi fue como comenzo y continua mi odisea en el desarrollo de software. Espero que este proyecto no solo sirva como referencia de, sin importar que, aquello que deseamos se puede cumplir si trabajamos lo suficiente en ello, sino que ayude a quien no tenga ninguna experiencia ni conocimiento en el campo de desarrollo de software a poder lograr una idea basica de lo que este arte trata. 

### Una necesidad Personal

Los motivos personales de como comenzo este proyecto se remontan hace muchos años atras. Toda mi vida me dedique a la informatica, trabaje los ultimos 20 años en ella. Sin embargo el desarrollo de software siempre fue un gran pendiente en mi portafolio de habilidades. Nunca me hice de la *voluntad* para empezar a estudiar sobre ello por diferentes motivos. Fue asi hasta el año 2021 en el cual decidi dar un giro a mi carrera y empezar el camino hacia ser un desarrollador de software a tiempo completo.  
Fue ahi cuando en esa etapa tan temprana de no saber absolutamente nada empece a buscar en mi dia a dia una idea, de que poder crear, necesitaba tener metas fijas las cuales poder utilizar para aprender lo que era conveniente y no todo lo que existe ya que el campo del desarrollo de software es inmensamente amplio.Para poder llegar a mi mision, necesitaba un proyecto, el cual me llebara paso a paso a descubrir todas las etapas las cuales me iba a enfrentar.

> El desarrollo completo de este proyecto fue basado en la forma mas basica y mas potente que tiene cualquier persona de lograr sus objetivos.
>
> 1. Informarce.
> 2. Estudiar.
> 3. Aplicar.
> 4. ***Fallar***.
> 5. Corregir.
> 6. Controlar o mejorar.
> 7. Volver al paso 1.  

# Indentificacion del problema

Trabajo en una escuela desde hace mas de 10 años, en la cual mi actividad es la de mantener toda la infraestructura informatica. Eso contempla, computadoras de las diferentes areas, asi como tambien toda la estructura de red y los servidores asociados a ella. En este tiempo fueron muchos los problemas que surgieron, sin embargo hay uno puntualmente que nunca se le pudo dar solucion. Este problema se refiere al manejo de la informacion dentro de la escuela y la coordinacion de dicha informacion entre las diferentes areas.  

La informacion a la cual me refiero es la siguiente:

- Matricula de alumnos
- Calificaciones
- Asistencia
- Legajos
- Reportes de diferentes indoles
- Informes
- Estadisticas
- Actas y notas 

Esta informacion siempre fue manejada utilizando Excel y Word. Se detallara a continuacion cuales son los problemas y dificultades que el uso de estas tecnologias genera. Algunas son por una limitacion de tecnologia en si y otras por el factor de su complejidad de uso en ciertas circunstancias.

- Es sumamente dificil estandarizar nombres de archivos y locacion donde los mismos se guardan. Esto puede ser ya sea por omision del usuario de seguir estandar al guardar o escribir el nombre del archivo. O por error involuntario del mismo.

- Si bien tanto Excel como Word presentan la posibilidad de generar plantillas para que se intente tener para todos la misma estructura en la cual se muestra la informacion, es posible que ya sea por el error humano mencionado con anterioridad o un error de compatibilidad entre las diferentes versiones de Word o Excel instaladas en las diferentes maquinas (de bien de uso de la escuela asi como particulares) esta plantilla se "rompa" y termine siendo un verdadero dolor de cabeza corregir esos errores mas cuando el archivo ya fue cargado con informacion.

- Cuando la cantidad de informacion es muy grande, por ejemplo una matricula la cual cuenta con cientos o miles de entradas se corre un gran riesgo al utilizar esa informacion sobre un Excel. Algunos de los motivos se detallan a continuacion:  

  - Es posible modificar valores sin darse cuenta y guardarlos junto cambios realizados legitimos.
  - No se puede tener control de quien o cuando se cambio la informacion.
  - Lentitud en general, estas planillas son grandes y pesadas. El problema aumenta al trabajar con archivos en una red o mas aun cuando se trabaja con estos archivos por internet.
  - Uso de filtros complejo y poco amigable. Ademas los filtros pueden quedar guardados generando que quien abre despues la planilla no tenga toda la informacion disponible.

- No existen tecnologias que vengan ya con Excel y Word que hagan un respaldo de la informacion, esta debe ser aplicada de forma externa al mismo.

- Serias limitaciones de esta tecnologia para poder compartirlas a travez de internet. Este es un factor sumamente importante.

- Si bien en las planillas de Excel se pueden crear macros (codigo de programacion dentro de una planilla de excel) esta es sumamente lenta e inestable. Pude romperse el codigo con facilidad dejando la planilla inutil.

- Cuando las planillas de Excel aumentan en complejidad, las cuales tienen varias hojas y vinculos entre ellas se corre un gran riesgo de que se rompan los mismos dejando las planillas inutles.

- Corregir cualquier tipo de problema que tenga una planilla de Excel o incluso una simple tabla en Word lleva mucho tiempo.

De lo mencionado anteriormente se puede determinar que los problemas son los siguientes:

- Minimizar la posibilidad de falla humana.
- Falta de estandarizacion de una forma de trabajo .
- Falta de estandarizacion en la manera que se ingresan datos.
- Falta de control de quien puede o cuando cambio datos.
- Falta de un lugar unico donde toda los datos este disponibles y ordenados.
- Falta de accesibilidad de la informacion a travez de internet.
- Falta de preservacion de datos.

Como problemas secundarios se puede mencionar:

- Lentitud de la tecnologia.
- Lentitud al trabajar sobre la misma.
- Diconformidad de parte de usuario por fallas recurrentes.
- Desmotivacion.
- Se pierde mucho tiempo en corregir errores y fallas.

# Indentificacion de las soluciones 

Durante el transcurso de los años se intento incorporar otra tecnologia o metodos que dieran solucion a los problemas mencionados con anterioridad. De la busqueda de informacion se pusieron en juicio varias posibles soluciones, algunas de ellas fueron implementadas y otras descartadas de inmediato al analizar que no iban a poder ser implementadas. Las posibles soluciones las cuales cuales se detallan a continuacion y cuales fueron los motivos por los cuales fallaron.

- Capacitacion al personal para lograr estandarizar las formas de trabajo. FALLO (falta de predisposicion tanto de directivos como personal en recibir capacitacion)
- Generar carpetas donde guardar la informacion en los servidores y tener un espacio de trabajo unico. FALLO a medias (si bien el personal empezo a utilizar dicho espacio, no hubo forma de estandarizar la manera que lo hacia, guardaba o escribia la informacion.)
- Adquirir un software de gestion ya echo que se utilizara en otras instituciones educativas. FALLO (debido a la particularidad de la institucion hacia falta que el software tuviera un formato muy especifico)
- Adquirir un software de gestion a medida. FALLO (de todos las empresas consultadas ninguna pudo dar un presupuesto que se pudiera acomodar a la institucion, eran sumamente caros y de parte de la institucion no se confiaba en quienres representaban dichas empreas.)

Fue aqui, despues de agotar todas estas opciones cuando decidi plantear crear un software a medida, era la situacion ideal para poder crear mi propio proyecto, el mecionado anteriormente y poder satisfacer las necesidades de la institucion.

Dentro de las ventajas de que alguien que esta trabajando dentro de la institucion haga un software asi son:

- Conocimiento profundo de las necesidades institucionales.
- Conocer al personal.
- Comunicacion directa con los futuros usuarios.
- Acceso a la informacion ya echa con otras tecnologias y adaptarlas a una nueva.
- Crear una aplicacion en conjunto desarrollador/usuario.
- Confianza.
- Sin costos extras.
