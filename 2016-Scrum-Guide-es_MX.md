# La Guía de Scrum &trade; 

----

Esta versión HTML de la Guía de Scrum es una traducción al Español (México) de
la versión de julio de 2016

##### Tabla de Contenidos

* [Propósito de la Guía de Scrum](#purpose) 
* [Definición de Scrum](#definition)
* [Teoría de Scrum](#theory)
* [Los Valores de Scrum](#values)
* [El Equipo Scrum (_Scrum Team_)](#team)
    * [El Dueño del Producto (_Product Owner_)](#team-po)
    * [El Equipo de Desarrollo (_Development Team_)](#team-dev)
    * [El Scrum Master](#team-sm)
* [Eventos de Scrum](#events)
    * [El Sprint](#events-sprint)
    * [Planificación del Sprint (_Sprint Planning_)](#events-planning)
    * [Scrum Diario (_Daily Scrum_)](#events-daily)
    * [Revisión del Sprint (_Sprint Review_)](#events-review)
    * [Retrospectiva del Sprint (_Sprint Retrospective_)](#events-retro)
* [Artefactos de Scrum](#artifacts)
    * [Lista de Trabajo del Producto (_Product
      Backlog_)](#artifacts-productbacklog)
    * [Lista de Trabajo del Sprint (_Sprint Backlog_)](#artifacts-sprintbacklog)
    * [Incremento del Producto](#artifacts-increment)
* [La Transparencia de los Artefactos](#artifact-transparency)
    * [Definición de "Terminado" (_Definition of
      "Done"_)](#artifact-transparency-done)
* [Nota Final](#endnote)
* [Agradecimientos](#acknowledgements)
    * [Personas](#acknowledgements-people)
    * [Historia](#acknowledgements-history)
    * [Traducción](#acknowledgements-translation)

## <a name="purpose"></a>Propósito de la Guía de Scrum 

Scrum es un marco de trabajo para el desarrollo y mantenimiento de productos
complejos. Esta guía contiene la definición de Scrum. Esta definición se compone
de los roles, eventos, artefactos, y las reglas que los relacionan. Ken Schwaber
y Jeff Sutherland desarrollaron Scrum;  la Guía de Scrum está escrita y
preparada por ellos. Juntos, respaldan la Guía de Scrum.

## <a name="definition"></a> Definición de Scrum 

Scrum (sustantivo): Un marco de trabajo con el cual la gente puede hacer frente
a problemas complejos adaptativos, mientras entrega productos con el valor más
alto posible productiva y creativamente.

Scrum es:

* Ligero
* Sencillo de entender
* Difícil de dominar

Scrum es un marco de trabajo que se ha utilizado para gestionar el desarrollo de
productos complejos desde principio de los años 90. Scrum no es un proceso o una
técnica para la construcción de productos; más bien es un marco de trabajo en el
que se pueden emplear varios procesos y técnicas. Scrum deja clara la eficacia
relativa de sus prácticas de gestión y desarrollo de productos, de manera que se
puedan mejorar.

El marco de trabajo Scrum consiste en Equipos de Scrum y sus roles asociados,
eventos, artefactos y reglas. Cada componente en el marco sirve para un
propósito específico y es esencial para el éxito y el uso de Scrum.

Las reglas de Scrum relacionan entre sí los eventos, los roles y los artefactos,
regulando las relaciones e interacciones entre ellos. Las reglas de Scrum se
describen en este documento.

Las estrategias específicas para usar el marco de trabajo Scrum son diversas y
están descritas en otra parte.

## <a name="theory"></a> Teoría de Scrum 

Scrum se basa en la teoría empírica del control de procesos empírico, o el
empirismo. El empirismo afirma que conocimiento proviene de la experiencia y la
toma de decisiones se hace con base a lo que se conoce. Scrum emplea un enfoque
iterativo e incremental para optimizar la predictibilidad y el control de
riesgos.

Tres pilares sostienen toda implementación del control empírico de procesos:
transparencia, inspección y adaptación.

### Transparencia

Los aspectos significativos del proceso deben ser visibles a los responsables de
los resultados. La transparencia requiere que dichos aspectos se definan por una
norma común de tal modo que los observadores compartan un entendimiento en común
de lo que se está viendo.

Por ejemplo:

* Un lenguaje común que se refiere al proceso debe ser compartido por todos los
  participantes; y,
* Aquellos que realizan el trabajo y aquellos que aceptan el producto del
  trabajo deben compartir una definición común de "Terminado".

### Inspección

Los practicantes de Scrum deben inspeccionar frecuentemente los artefactos de
Scrum y el progreso hacia un objetivo para detectar variaciones indeseadas.  Su
inspección no deben ser tan frecuente como para que se interponga en el camino
del trabajo. Las inspecciones son más benéficas cuando se realizan con
diligencia por inspectores calificados en el mismo lugar de trabajo.

### Adaptación

Si un inspector determina que uno o más aspectos de un proceso se desvían fuera
de los límites aceptables y que el producto resultante será inaceptable, el
proceso o el material procesado debe ser ajustado. Un ajuste debe realizarse tan
pronto como sea posible para reducir al mínimo la desviación.

Scrum prescribe cuatro eventos formales para la inspección y la adaptación, tal
como se describe en la sección de eventos de este documento:

* Planificación del Sprint (_Sprint Planning_)
* Scrum diario (_Daily Scrum_)
* Revisión del Sprint (_Sprint Review_)
* Retrospectiva de Sprint (_Sprint Retrospective_)

## <a name="values"></a> Los Valores de Scrum 

Cuando los valores como el compromiso, el coraje, la concentración, la apertura
y el respeto están incorporados y son vivencias del Equipo Scrum, los pilares de
Scrum: transparencia, inspección y adaptación cobran vida y generan confianza
para todo el mundo. Los miembros del Equipo Scrum aprenden y exploran estos
valores, conforme van trabajando con los eventos, roles y artefactos.

El uso exitoso de Scrum depende de que la gente se vuelva cada vez más
competente en practicar los cinco valores. La gente se compromete de manera
individual a lograr los objetivos del equipo Scrum. Los miembros del equipo
Scrum tienen coraje para hacer las cosas bien y trabajar en los problemas
difíciles. Todo el mundo se concentra en el trabajo del Sprint y en los
objetivos del Equipo Scrum. El Equipo Scrum y sus grupos de interés están de
acuerdo en ser abiertos sobre el trabajo y los desafíos que se presentan al
realizar el trabajo. Los miembros del Equipo Scrum se respetan entre sí por ser
personas capaces e independientes.

## <a name="team"></a>El Equipo Scrum (_Scrum Team_) 

El Equipo Scrum consiste en un Dueño del Producto (_Product Owner_), el Equipo
de Desarrollo (_Development Team_), y un Scrum Master. Los Equipos Scrum son
auto-organizados y multifuncionales. Los equipos auto-organizados eligen la
mejor manera de realizar su trabajo en lugar de ser dirigidos por personas
externas al equipo.  Los equipos multifuncionales tienen todas las competencias
necesarias para realizar el trabajo sin depender de otras personas que no forman
parte del equipo. El modelo de equipo en Scrum está diseñado para optimizar la
flexibilidad, la creatividad y la productividad.

Los Equipos Scrum entregan productos de manera incremental e iterativa,
maximizando las oportunidades de obtener retroalimentación. Las entregas
incrementales de producto "Terminado" garantizan una versión potencialmente
utilizable y funcional del producto.

### <a name="team-po"></a>El Dueño del Producto (_Product Owner_) 

El Dueño del Producto es responsable de maximizar el valor del producto y el
trabajo del Equipo de Desarrollo. El modo de hacer esto puede variar ampliamente
a través de las organizaciones, Equipos Scrum y los individuos.

El Dueño del Producto es la única persona responsable de la gestión de la Lista
de Trabajo del Producto (_Product Backlog_). La administración de la Lista de
Trabajo del Producto incluye:

* Expresar claramente cada elemento de la Lista de Trabajo del Producto;
* Ordenar los elementos de la Lista de Trabajo del Producto para alcanzar los
  objetivos y misiones de la mejor manera posible;
* Optimizar el valor del trabajo que el Equipo de Desarrollo lleva a cabo;
* Asegurar que la Lista de Trabajo del Producto es visible, transparente y clara
  para todos y que muestra lo que el Equipo Scrum trabajará a continuación; y,
* Asegurar que el Equipo de Desarrollo comprende los elementos de la Lista de
  Trabajo del Producto al nivel requerido.

El Dueño del Producto puede hacer el trabajo anterior o dejar que el Equipo de
Desarrollo lo haga. Sin embargo, el Dueño del Producto sigue siendo responsable
de dicho trabajo en cualquiera de los casos.

El Dueño del Producto es una sola persona, no un comité. El Dueño del Producto
puede representar los intereses de un comité en la Lista de Trabajo del
Producto, pero aquellos que quieren cambiar la prioridad de un elemento de la
Lista deben hacerlo a través del Dueño del Producto.

Para que el Dueño del Producto pueda hacer bien su trabajo, toda la organización
debe respetar sus decisiones. Las decisiones del Dueño del Producto son visibles
en el contenido y el orden de la Lista de Trabajo del Producto. No se le permite
a nadie más indicar al Equipo de Desarrollo que trabaje en un conjunto diferente
de requerimientos y no está permitido que el Equipo de Desarrollo haga lo que
diga cualquier otra persona.

### <a name="team-dev"></a>El Equipo de Desarrollo (_Development Team_) 

El Equipo de Desarrollo está formado por profesionales que trabajan para
entregar un Incremento de Producto “Terminado” al final de cada Sprint. Sólo los
miembros del Equipo de Desarrollo trabajan en la creación del Incremento.

La organización es la encargada de estructurar y empoderar a los Equipos de
Desarrollo para que estos se organicen y gestionen su propio trabajo. La
sinergia resultante optimiza la eficiencia y efectividad del Equipo de
Desarrollo.

Los equipos de desarrollo tienen las siguientes características:

* Son auto-organizados. Nadie (ni siquiera el Scrum Master) le indica al Equipo
  de Desarrollo cómo convertir elementos de la Lista de Trabajo del Producto en
  Incrementos de funcionalidad potencialmente desplegable;
* Los Equipos de Desarrollo son multi-funcionales, con todas las habilidades
  necesarias para crear un incremento de producto;
* Scrum no reconoce títulos para los miembros del Equipo de Desarrollo distintos
  al de “Desarrollador”, independientemente de la participación por parte de la
  persona; no hay excepciones para esta regla;
* Scrum no reconoce sub-equipos en el Equipo de Desarrollo, independientemente
  de los dominios particulares que deben abordarse como pruebas o análisis de
  negocios; no hay excepciones para esta regla; y,
* Los miembros del Equipo de Desarrollo pueden tener habilidades especializadas
  y áreas de interés particulares, pero la responsabilidad pertenece en conjunto
  al Equipo de Desarrollo.

### Tamaño del Equipo de Desarrollo

El tamaño óptimo del Equipo de Desarrollo es lo suficientemente pequeño como
para permanecer ágil y lo suficientemente grande para completar un trabajo
significativo dentro de la duración de un Sprint. Tener menos de tres miembros
en el Equipo de Desarrollo disminuye la interacción y resulta en ganancias de
productividad más pequeñas. Los Equipos de Desarrollo más pequeños pueden
encontrarse con limitaciones en cuanto a las habilidades necesarias durante un
Sprint, provocando que el Equipo de Desarrollo no pueda entregar un Incremento
potencialmente liberable. Tener más de nueve miembros requiere demasiada
coordinación. Los Equipos grandes de Desarrollo generan demasiada complejidad en
la gestión de un proceso empírico. Los roles del Dueño del Producto y del Scrum
Master no se incluyen en el cálculo del tamaño del equipo a menos de que ellos
también estén ejecutando los trabajos de la Lista de Trabajo del Sprint.

### <a name="team-sm"></a>El Scrum Master 

El Scrum Master es responsable de asegurar que Scrum se entiende y se practica.
Los Scrum Masters hacen esto asegurando que el Equipo Scrum se adhiere a la
teoría, prácticas y reglas de Scrum. 

El Scrum Master es un líder que está al servicio del Equipo Scrum. El Scrum
Master ayuda a aquellos fuera del Equipo Scrum a entender cuáles de sus
interacciones con el Equipo Scrum son útiles y cuáles no. El Scrum Master ayuda
a todos a cambiar estas interacciones para maximizar el valor creado por el
Equipo Scrum.

#### El servicio del Scrum Master al Dueño del Producto

El Scrum Master sirve al Dueño del Producto de varias maneras, incluyendo:

* Encontrar técnicas para la gestión eficaz de la Lista de Trabajo del Producto;
* Ayudar al Equipo de Scrum a entender la necesidad de que los elementos de la
  Lista de Trabajo del Producto sean claros y concisos;
* La comprensión de la planificación de productos en un entorno empírico;
* Asegurar que el Dueño del Producto conozca cómo organizar la Lista de Trabajo
  del Producto para maximizar el valor;
* Entender y practicar la agilidad; y,
* Facilitar eventos Scrum conforme a lo solicitado o necesario.

#### El servicio del Scrum Master al Equipo de Desarrollo

El Scrum Master sirve al Equipo de Desarrollo de varias maneras, incluyendo:

* Guiar al Equipo de Desarrollo en los temas de auto-organización y
  multi-funcionalidad;
* Ayudar al Equipo de Desarrollo para crear productos de alto valor;
* Eliminar obstáculos en el avance del Equipo de Desarrollo;
* Dirigir los eventos Scrum cuando sean solicitados o necesarios; y,
* Guiar al Equipo de Desarrollo en entornos organizacionales en los que la
  práctica de Scrum aún no es plenamente adoptada y entendida.

#### El servicio Scrum Master a la Organización

El Scrum Master sirve la organización de varias maneras, incluyendo:

* Dirigiendo y guiando a la organización en su adopción de la práctica de Scrum;
* La planificación de implementaciones de Scrum dentro de la organización;
* Ayudar a los empleados y partes interesadas a entender y poner en práctica
  Scrum y el desarrollo empírico de productos;
* Consiguiendo los cambios que aumentan la productividad del equipo Scrum; y,
* Trabajar con otros Scrum Masters para aumentar la eficacia de la práctica de
  Scrum en la organización.

## <a name="events"></a>Eventos de Scrum 

Los eventos predefinidos se utilizan en Scrum para crear la regularidad y
reducir al mínimo la necesidad de reuniones no definidas en la práctica de
Scrum. Todos los eventos son bloques de tiempo (time-boxes), de tal manera que
cada evento tiene una duración máxima. Una vez que comienza un Sprint, su
duración es fija y no puede acortarse o alargarse. El resto de los eventos
pueden terminar una vez que se consigue el objetivo del evento, asegurando que
se dedica una cantidad adecuada de tiempo sin permitir desperdicio en el
proceso.

Aparte del propio Sprint, que es un contenedor para todos los demás eventos,
cada evento en Scrum es una oportunidad formal para inspeccionar y adaptar algún
aspecto. Estos eventos están diseñados específicamente para permitir la
transparencia e inspección; fundamentos de la práctica de Scrum. No incluir
cualquiera de estos eventos resulta en pérdida de transparencia y es una
oportunidad perdida de inspección y adaptación.

### <a name="events-sprint"></a>El Sprint 

El corazón de Scrum es el Sprint, un bloque de tiempo (_time-box_) de un mes o
menos durante el cual se crea un Incremento de Producto "Terminado" utilizable y
potencialmente liberable. Es mejor si los Sprints tienen una duración uniforme a
lo largo de un periodo de desarrollo. Un nuevo Sprint se inicia inmediatamente
después de la conclusión del Sprint anterior.

Los Sprints contienen y consisten en la Planificación del Sprint (_Sprint
Planning_), los Scrum Diarios (_Daily Scrums_), el trabajo de desarrollo, la
Revisión del Sprint (_Sprint Review_), y la Retrospectiva del Sprint (_Sprint
Retrospective_).

Durante el Sprint:

* No se realizan cambios que pondría en peligro el objetivo del Sprint (_Sprint
  Goal_);
* Los objetivos de calidad no disminuyen; y,
* El alcance puede aclararse y re-negociarse entre el Dueño del Producto y el
  Equipo de Desarrollo conforme se aprende más.

Cada Sprint puede considerarse un proyecto con un horizonte no mayor de un mes.
Al igual que los proyectos, los Sprints se utilizan para completar algo. Cada
Sprint tiene una definición de lo que se va a construir, un diseño y un plan
flexible que guiará su construcción, el trabajo del equipo, y el producto
resultante.

Los Sprints se limitan a un mes calendario. Cuando el horizonte de un Sprint es
demasiado grande la definición de lo que se está construyendo puede cambiar, la
complejidad y el riesgo podrían aumentar. Los Sprints permiten previsibilidad
garantizando la inspección y la adaptación de progreso hacia al objetivo del
Sprint al menos cada mes calendario. Los Sprints también limitan costo del
riesgo a un mes natural de trabajo.

#### Cancelación de un Sprint

Un Sprint puede ser cancelado antes de que el tiempo asignado haya terminado.
Sólo el Dueño del Producto tiene la autoridad para cancelar el Sprint, aunque
puede hacerlo en acuerdo con las partes interesadas, el Equipo de Desarrollo, o
el Scrum Master.

Un Sprint podría ser cancelado si el objetivo se vuelve obsoleto. Esto podría
ocurrir si la empresa cambia de dirección o si cambian las condiciones del
mercado o de la tecnología. En general, un Sprint debe ser cancelado si dadas
las circunstancias ya no tiene sentido continar. Pero, debido a la corta
duración de los Sprints, una cancelación rara vez tiene sentido.

Cuando se cancela un Sprint, se revisan todos los elementos de la Lista de
Trabajo del Producto que se hayan completado y "Terminado".  Si parte del
trabajo es potencialmente liberable, el Dueño del Producto generalmente acepta
el avance. Todos los elementos de la Lista de Trabajo del Producto sin completar
se vuelven a estimar y a poner de vuelta en la Lista de Trabajo del Producto. El
trabajo realizado sobre los elementos se pierde valor rápidamente y con
frecuencia deben volver a ser estimados.

Cancelar un Sprint consume recursos, ya que todos los involucrados tienen que
reagruparse en otra reunión de Planificación del Sprint para emprezar un nuevo
Sprint. Muy a menudo las cancelaciones de Sprint son traumáticos para el Equipo
Scrum, por lo tanto son muy poco frecuentes.

### <a name="events-planning"></a>Planificación del Sprint (_Sprint Planning_) 

El trabajo a realizar en el Sprint se proyecta en la Planificación del Sprint.
Este plan de trabajo es creado colaborativamente entre todo el Equipo Scrum.

La Planificación del Sprint está limitada a un máximo de ocho horas para un
Sprint de un mes de duración. Para Sprints más cortos la duración del evento es
por lo general más corta. El Scrum Master asegura que el evento se lleva a cabo
y que los asistentes comprendan su propósito. El Scrum Master ayuda al Equipo
Scrum a mantenerse dentro del límite de tiempo.

En la Planificación del Sprint se responde las siguientes preguntas:

* ¿Que se puede entregar en el Incremento resultante del Sprint que comienza?
* ¿Cómo se conseguirá hacer el trabajo necesario para entregar el Incremento?

#### Tema Uno: ¿Qué puede hacerse en este Sprint?

El Equipo de Desarrollo trabaja para proyectar la funcionalidad que se
desarrollará durante el Sprint. El Dueño del Producto expone el objetivo que
debe conseguir el Sprint y los elementos de la Lista de Trabajo del Producto
que, si se completa en el Sprint, permitan lograr el objetivo del Sprint. Todo
el equipo Scrum colabora en la comprensión del trabajo del Sprint.

Los insumos de esta reunión son la Lista de Trabajo del Producto, el último
Incremento del Producto, la capacidad proyectada del Equipo de Desarrollo
durante el Sprint, y el rendimiento anterior del Equipo de Desarrollo. El número
de elementos seleccionados de la Lista de Trabajo del Producto para el Sprint
depende únicamente del Equipo de Desarrollo. Sólo el Equipo de Desarrollo puede
evaluar lo que puede conseguir terminar en el siguiente Sprint.

Después de que el Equipo de Desarrollo indica cuales elementos de la Lista de
Trabajo del Producto se entregarán al terminar el Sprint, el equipo Scrum
prepara un objetivo del Sprint (_Sprint Goal_). La meta del Sprint es un La meta
del Sprint se conseguirá durante la ejecución del Sprint a través de la
implementación de la Lista de Trabajo del Producto y proporciona guía al Equipo
de Desarrollo de por qué se está construyendo el Incremento.

#### Tema Dos: ¿Cómo se conseguirá completar el trabajo?

Después de haber establecido el objetivo del Sprint y de seleccionar los
elementos de la Lista de de Trabajo del Producto para el Sprint, el Equipo de
Desarrollo decide cómo va a construir esta funcionalidad para tener un
Incremento de producto "Terminado" durante el Sprint. Los elementos
seleccionados de la Lista de Trabajo del Producto para construir en este Sprint
más el plan para la entrega se conocen como la Lista de Trabajo del Sprint
(_Sprint Backlog_).

El Equipo de Desarrollo por lo general comienza por el diseño del sistema y el
trabajo necesario para convertir la Lista de Trabajo del Producto en un
Incremento del Producto funcional. El trabajo puede ser de tamaño variable, o
esfuerzo estimado. Sin embargo, se incluye suficiente trabajo para el Equipo de
Desarrollo durante la Planificación del Sprint para estimar lo que cree que
puede hacer en el próximo Sprint. El trabajo previsto para los primeros días del
Sprint por el Equipo de Desarrollo se descompone al término de esta reunión, a
menudo en unidades de un día o menos. El Equipo de Desarrollo se auto-organiza
para realizar el trabajo de la Lista de Trabajo del Sprint, tanto durante la
Planificación del Sprint y cada vez que sea necesario. 

El Dueño del Producto puede ayudar a aclarar los elementos seleccionados de la
Lista de Trabajo del Producto y hacer concesiones. Si el Equipo de Desarrollo
determina que tiene demasiado o muy poco trabajo, puede volver a negociar los
selementos eleccionados de la Lista de Trabajo del Producto con el Dueño del
Producto. El Equipo de Desarrollo también puede invitar a otras personas que
asisten a fin de proporcionar asesoramiento técnico o de conocimiento del
dominio.

Hacia el final de la reunión de Planificación del Sprint, el Equipo de
Desarrollo debe ser capaz de explicar al Dueño del Producto y al Scrum Master
cómo se propone trabajar como un equipo auto-organizado para lograr el objetivo
del Sprint y crear el Incremento esperado.

#### <a name="events-goal"></a> Objetivo del Sprint (_Sprint Goal_) 

El objetivo del Sprint es un conjunto de actividades que pueden ser conseguidas
a través de la implementación de la Lista de Trabajo del Sprint. Proporciona una
guía para el Equipo de Desarrollo de por qué se está construyendo el Incremento
del Producto. Se crea durante la reunión de Planificación de Sprint. El Objetivo
del Sprint brinda al Equipo de Desarrollo cierta flexibilidad en cuanto a la
funcionalidad implementada al término del Sprint. Los elementos seleccionados de
la Lista de Trabajo del Producto ofrecen una función coherente que puede ser el
Objetivo del Sprint. El Objetivo del Sprint puede ser otro punto de unión que
haga que el Equipo de Desarrollo trabaje en conjunto en lugar de en iniciativas
independientes.

Mientras trabaja el Equipo de Desarrollo debe mantener el Objetivo del Sprint en
mente. Se implementa la funcionalidad y la tecnología con el fin de cumplir el
Objetivo del Sprint. Si el trabajo resulta ser diferente de lo que esperaba el
Equipo de Desarrollo, ellos colaboran con el Dueño del Producto para negociar el
alcance de la Lista de Trabajo del Sprint (_Sprint Backlog_).

### <a name="events-daily"></a> Scrum Diario (_Daily Scrum_) 

El Scrum Diario es un evento de 15 minutos para que el Equipo de Desarrollo
sincronice sus actividades y cree un plan de trabajo para las próximas 24 horas.
Esto se realiza mediante la inspección del trabajo desde el último Scrum Diario
y la planificación de los trabajos que se podía terminar antes de la siguiente.

Para reducir la complejidad, el Scrum Diario se lleva a cabo en el mismo lugar y
hora todos los días. Durante las  reuniones, los miembros del Equipo de
Desarrollo explican lo siguiente:

* ¿Qué hice ayer que ayudó al Equipo de Desarrollo de cumplir con el Objetivo
  del Sprint?
* ¿Qué voy a hacer hoy para ayudar al Equipo de Desarrollo de cumplir con el
  Objetivo del Sprint?
* ¿Veo algún impedimento que me impide o al Equipo de Desarrollo el cumplimiento
  del Objetivo del Sprint?

El Equipo de Desarrollo utiliza el Scrum Diario para evaluar el progreso hacia
el Objetivo del Sprint y para inspeccionar cómo el progreso es una tendencia
hacia la conclusión del trabajo en la Lista de Trabajo del Sprint. El Scrum
Diario aumenta la probabilidad de que el Equipo de Desarrollo cumplirá el
Objetivo del Sprint. Cada día, el Equipo de Desarrollo debe entender cómo se
propone trabajar juntos como un equipo auto-organizado para lograr el objetivo
del Sprint y crear el Incremento previsto para el final del Sprint. Los miembros
del Equipo de Desarrollo o del equipo a menudo se reúnen inmediatamente después
del Scrum Diario para tener discusiones detalladas, o para adaptar o
re-planificar el resto del trabajo del Sprint.

El Scrum Master se asegura de que el Equipo de Desarrollo tiene la reunión, pero
el Equipo de Desarrollo es responsable de llevar a cabo el Scrum Diario. El
Scrum Master enseña al Equipo de Desarrollo a mantener el Scrum Diario dentro
del límite de tiempo de 15 minutos.

El Scrum Master hace cumplir la regla de que sólo los miembros del Equipo de
Desarrollo participan en el Scrum Diario (_Daily Scrum_).

El Scrum Diario ayuda a mejorar la comunicación, elimina la necesidad de otras
reuniones, a identificar y eliminar los obstáculos para el desarrollo, destacar
y promover la toma rápida de decisiones, y a mejorar el nivel de conocimiento
del equipo. El Scrum Diario es una reunión clave de inspección y adaptación.

### <a name="events-review"></a> Revisión del Sprint (_Sprint Review_) 

Una Revisión de Sprint se lleva a cabo al final del Sprint para inspeccionar el
Incremento y actualizar, si es necesario, la Lista de Trabajo del Producto.
Durante la Revisión del Sprint, el Equipo Scrum y las partes interesadas
colaboran sobre lo que se hizo en el Sprint. En base a eso y a cualquier cambio
en la Lista de Trabajo del Producto durante el Sprint, los asistentes colaboran
para determinar las siguientes cosas que se podrían hacer para optimizar el
valor.  Esta es una reunión informal, no una reunión de avance, y la
presentación del Incremento tiene la intención de obtener retroalimentación y
fomentar la colaboración.

Esta es una reunión con un límite de tiempo de cuatro horas para un Sprint de un
mes de duración. Para Sprints más cortos, el evento es por lo general más corto.
El Scrum Master se asegura de que el evento se lleva a cabo y que los asistentes
comprenden el propósito. El Scrum Master enseña a todos a mantener el evento
dentro del límite de tiempo.

La Revisión del Sprint incluye los siguientes elementos:

* Los asistentes incluyen el Equipo Scrum y las partes clave interesadas
  invitadas por el Dueño del Producto;
* El Dueño del Producto explica qué elementos de la Lista de Trabajo del
  Producto han sido "Terminados" y cuales no se han "Terminado";
* El Equipo de Desarrollo comenta acerca de lo que se hizo bien durante el
  Sprint, qué problemas aparecieron, y cómo se resolvieron esos problemas;
* El Equipo de Desarrollo demuestra el trabajo que tiene "Terminado" y responde
  preguntas sobre el Incremento;
* El Dueño del Producto discute la Lista de Trabajo del Producto en su estado
  actual. Estima fechas de terminación probables con base en los avances
  conseguidos hasta la fecha (si es necesario);
* Todo el grupo colabora en qué hacer a continuación, de manera que la Revisión
  del Sprint ofrece una valiosa aportación a la siguiente Planificación del
  Sprint;
* Revisión de cómo el mercado o el uso potencial del producto podría haber
  cambiado lo que es más valioso que debe hacer a continuación; y,
* Revisión de la línea de tiempo, presupuesto, capacidades potenciales, y el
  mercado para el siguiente lanzamiento anticipado del producto.

El resultado de la Revisión del Sprint es una Lista de Trabajo del Producto
revisada que define los elementos probables de la Lista de Trabajo para el
próximo Sprint. La Lista de Trabajo del Producto también se puede ajustar para
satisfacer nuevas oportunidades globales.

### <a name="events-retro"></a> Retrospectiva del Sprint (_Sprint Retrospective_) 

La Retrospectiva del Sprint es una oportunidad para que el Equipo Scrum se
inspeccione a sí mismo y crear un plan de mejoras para ser aplicadas durante el
siguiente Sprint.

La Retrospectiva de Sprint se realiza después de la Revisión del Sprint y antes
de la próxima Planificación del Sprint. Esta es una reunión tiene un límite de
tres horas para los Sprints de un mes de duración. Para Sprints más cortos, el
evento es por lo general más corto. El Scrum Master se asegura de que el evento
se lleva a cabo y que los asistentes comprenden su propósito. El Scrum Master
enseña a todos a mantener el evento dentro del límite de tiempo. El Scrum Master
participa como un miembro del equipo en la reunión ya que es el resposable del
proceso de Scrum.

El propósito de la Retrospectiva del Sprint es:

* Revisar cómo fue el último Sprint en cuanto a personas, relaciones, procesos y
  herramientas;
* Identificar y ordenar los principales elementos que salieron bien y las
  potenciales mejoras; y,
* Crear un plan para la implementación de mejoras a la forma en que el Equipo
  Scrum hace su trabajo.

El Scrum Master alienta al Equipo Scrum para mejorar, dentro del proceso de
Scrum, su proceso y las prácticas de desarrollo para que sea más eficaz y
agradable para el siguiente Sprint. Durante cada Retrospectiva del Sprint, el
Equipo Scrum planea maneras de aumentar la calidad del producto ajustando la
definición de "Terminado" (_Definition of "Done"_) como sea necesario.

Hacia el final de la Retrospectiva del Sprint, el Equipo Scrum debería haber
identificado mejoras que implementará en el siguiente Sprint. La implementación
de estas mejoras en el siguiente Sprint es la adaptación a la revisión del
propio equipo Scrum. Aunque las mejoras pueden ser implementadas en cualquier
momento, la Retrospectiva del Sprint ofrece una oportunidad formal para
centrarse en revisión y adaptación.

## <a name="artifacts"></a> Artefactos de Scrum

Los Artefactos de Scrum representan trabajo o valor que son útiles para ofrecer
transparencia y oportunidades para la revisión y adaptación. Los artefactos
definidos por Scrum están diseñados específicamente para maximizar la
transparencia de la información clave de manera que todos tengan la misma
comprensión del artefacto.

### <a name="artifacts-productbacklog"></a> Lista de Trabajo del Producto (_Product Backlog_) 

La Lista de Trabajo del Producto es una lista ordenada de todo lo que podría ser
necesario en el producto y es la única fuente de requisitos para cualquier
cambio que se introduzca en el producto. El Dueño del Producto es responsable de
la Lista de Trabajo del Producto, incluyendo su contenido, la disponibilidad, y
el orden.

Una Lista de Trabajo del Producto nunca está completa. El primer desarrollo de
la misma sólo se expone los requerimientos conocidos y los mejor entendidos. La
Lista de Trabajo del Producto evoluciona a medida que el producto y el entorno
en el que se va a utilizar evoluciona. La Lista de Trabajo del Producto es
dinámica; constantemente cambia para identificar lo que el producto necesita
para ser adecuado, competitivo, y útil. Mientras exista el producto, también
existe la Lista de Trabajo del Producto.

La Lista de Trabajo del Producto enumera todas las características, funciones,
requisitos, mejoras y correcciones que constituyen los cambios que deben
introducirse en el producto en futuras versiones. Los elementos de la Lista de
Trabajo del Producto tienen como atributos de la descripción, el orden, la
estimación y el valor.

Conforme el producto se utiliza, obtiene valor y el mercado proporciona
retroalimentación, la Lista de Trabajo del Producto se convierte en una lista
más grande y exhaustiva. Los requerimientos nunca dejan de cambiar, por lo que
una Lista de Trabajo del Producto es un artefacto que se actualiza
continuamente. Los cambios en los requerimientos del negocio, las condiciones
del mercado, o en la tecnología pueden causar cambios en la Lista de Trabajo de
Producto.

Múltiples Equipos Scrum a menudo trabajan juntos en el mismo producto. Se
utiliza una Lista de Trabajo del Producto para describir el trabajo futuro en el
producto. Un atributo de la Lista de Trabajo del Producto agrupa los elementos
que podrían ser utilizados.

El refinamiento de la Lista de Trabajo del Producto es el acto de añadir
detalles, estimaciones, y establecer el orden de los elementos. Este es un
proceso continuo en el que el Dueño del Producto y el Equipo de Desarrollo
colaboran en los detalles de los elementos de la Lista de Trabajo del producto.
Durante el refinamiento de la Lista de Trabajo del Producto los elementos son
revisados y examinados. El Equipo Scrum decide cómo y cuándo se realiza el
refinamiento. El Refinamiento suele consumir no más del 10% de la capacidad del
Equipo de Desarrollo. Sin embargo, los elementos de la Lista de Trabajo del
producto pueden ser actualizados en cualquier momento por el Dueño del Producto
o criterio suyo.

Los primeros elementos de la Lista de Trabajo del Producto son por lo general
más claros y más detallados que los últimos.  Las estimaciones más precisas se
realizan con base a la mayor claridad y mayor detalle; al bajar el orden, el
detalle es menor. Los elementos de la Lista de Trabajo del Producto que vaya a
ocupar el Equipo de Desarrollo para el siguiente Sprint se refinan para que
cualquier elemento pueda ser razonablemente "Terminado" dentro de la duración
del Sprint. Los elementos de la Lista de Trabajo del Producto que pueden ser
"Terminados" por el Equipo de Desarrollo dentro de un Sprint se onsideran
"Listos" o "Accionables" para incluirse en la Planificación del Sprint. Los
elementos de la Lista del Trabajo del producto por lo general adquieren este
grado de transparencia a través de las actividades de refinamiento descritas
anteriormente.

El Equipo de Desarrollo es responsable de todas las estimaciones. El Dueño del
Producto puede influir en el Equipo de Desarrollo ayudándolo a comprender y
seleccionar soluciones de compromiso, pero la gente que realizará el trabajo se
encarga de hacer la estimación final.

#### Monitorear el progreso hacia una meta

En cualquier punto en el tiempo, se puede resumir el trabajo total restante para
alcanzar una meta. El Dueño del Producto hace seguimiento de este trabajo total
restante al menos en cada Revisión del Sprint. El Dueño del Producto compara
esta cantidad con el trabajo restante en Sprint anteriores para evaluar el
progreso hacia la conclusión del trabajo proyectado en el tiempo deseado para el
objetivo. Esta información se hace transparente para todas las partes
interesadas.

Diversas prácticas de proyección de tendencias se han utilizado para pronosticar
el progreso, como trabajo por hacer (_burndown_), completado (_burnup_), o
flujos acumulados (_cumulative flow_). Estos han demostrado ser útiles. Sin
embargo, éstas no reemplazan la importancia del empirismo. En ambientes
complejos, lo que sucederá es desconocido. Solamente lo que ha sucedido puede
ser utilizado para la toma de decisiones a futuro.

### <a name="artifacts-sprintbacklog"></a>Lista de Trabajo del Sprint (_Sprint Backlog_) 

La Lista de Trabajo del Sprint es el conjunto de elementos de la Lista de
Trabajo de Producto seleccionado para el Sprint, además de un plan de trabajo
para entregar el Incremento del Producto y conseguir el Objetivo del Sprint. La
Lista de Trabajo del Sprint es un pronóstico preparado por el Equipo de
Desarrollo de la funcionalidad que estará en el siguiente Incremento y el
trabajo necesario para ofrecer esta funcionalidad en un Incremento "Terminado".

La Lista de Trabajo del Sprint hace visible todo el trabajo que el Equipo de
Desarrollo identifica como necesario para cumplir el objetivo del Sprint.

La Lista de Trabajo del Sprint es un plan con suficiente detalle para que los
cambios en curso pueden entenderse en el Scrum Diario. El Equipo de Desarrollo
modifica la Lista de Trabajo del Sprint durante la ejecución el Sprint y la
Lista de Trabajo del Sprint surge durante el Sprint. Esto ocurre 
mientras el Equipo de Desarrollo avanza a través del plan y conoce más sobre el
trabajo necesario para lograr el objetivo del Sprint.

Cuando se requiere nuevo trabajo, el Equipo de Desarrollo lo añade a la Lista
del Trabajo del Sprint. A medida que el trabajo es realizado o completado, el
trabajo restante estimado se actualiza. Cuando los elementos del plan se
consideren innecesarias, es eliminado. Sólo el Equipo de Desarrollo puede cambiar
la Lista de Trabajo del Sprint durante un Sprint. La Lista de Trabajo del Sprint
es una imagen muy visible en tiempo real del trabajo que el Equipo de
Desarrollo planea llevar a cabo durante el Sprint, y pertenece únicamente al
Equipo de Desarrollo.

#### Monitoreando el progreso del Sprint

En cualquier punto en el tiempo en un Sprint, el trabajo total que queda en la
Lista de Trabajo del Sprint se puede resumir.  El Equipo de Desarrollo hace 
seguimiento de este trabajo restante total en cada Scrum Diario para
estimar la probabilidad de alcanzar el Objetivo del Sprint. Mediante el
seguimiento de los trabajos pendientes durante el Sprint, el Equipo de
Desarrollo puede gestionar su progreso.

### <a name="artifacts-increment"></a> Incremento del Producto 

El Incremento de Producto es la suma de todos los elementos de la Lista de
Trabajo del Producto terminados durante un Sprint y el valor de los Incrementos
de los Sprints anteriores. Al final de un Sprint, el nuevo Incremento debe estar
"Terminado", lo que significa que debe estar en un estado usable y cumplir con
la definición de "Terminado" del Equipo Scrum. El Incremento de Producto debe 
estar en condiciones de ser utilizado sin importar que el Dueño del Producto 
decida en realidad liberarlo o no.

## <a name="artifact-transparency"></a> La Transparencia de los Artefactos 

Scrum se basa en la transparencia. Las decisiones para optimizar el valor y 
controlar el riesgo se realizan basándose en el estado percibido de los
artefactos. En la medida en que la transparencia es completa, estas decisiones
tienen una base sólida. En la medida en que los artefactos son completamente
transparente, estas decisiones pueden ser incorrectas, el valor puede disminuir
y el riesgo puede aumentar.

El Scrum Master debe trabajar con el Dueño del Producto, el Equipo de
Desarrollo, y otros participantes implicados para entender si los artefactos son
completamente transparentes. Hay prácticas para hacer frente a la transparencia
incompleta; el Scrum Master debe ayudar a todos a aplicar las prácticas más
adecuadas en la ausencia de una transparencia total. Un Scrum Master puede
detectar transparencia incompleta mediante la inspección de los artefactos,
identificación de patrones, y escuchando con atención lo que se dice, y detectar
diferencias entre los resultados esperados y los resultados reales.

El trabajo de Scrum Master es trabajar con el Equipo Scrum y la organización
para aumentar la la transparencia de los artefactos. Este trabajo generalmente
implica el aprendizaje, convencimiento, y el cambio. La transparencia no se
produce de la noche a la mañana, pero es un camino.

### <a name="artifact-transparency-done"></a> Definición de "Terminado" (_Definition of "Done"_) 

Cuando un elemento de la Lista de Producto o un Incremento de Producto se
describen como "Terminado", todos en el equipo deben entender lo que significa.
Aunque esto varía significativamente para cada Equipo Scrum, los miembros deben
tener una comprensión compartida de lo que significa que el trabajo esté
terminado para garantizar transparencia. Esta es la definición de "Terminado"
para el Equipo Scrum y se utiliza para evaluar cuándo se ha completado el
trabajo del Incremento de Producto.

La misma definición guía al Equipo de Desarrollo para saber cuántos elementos de
la Lista de Trabajo del Producto se pueden seleccionar durante la Planificación
del Sprint. El propósito de cada Sprint es entregar incrementos de funcionalidad
potencialmente utilizables que se adhieren a la definición actual de "Terminado"
del Equipo Scrum.

Los Equipos de Desarrollo entregan un Incremento de funcionalidad de
producto en cada Sprint. Este Incremento es utilizable, por lo que un Dueño del
Producto puede optar por liberar inmediatamente. Si la definición de "Terminado"
para un Incremento de Producto forma parte de los acuerdos, normas o directrices
de la organización, todos los equipos de Scrum deben seguirla como mínimo. Si
"Terminado" para un Incremento no es una regla de la organización, el
Equipo de Desarrollo del Equipo Scrum debe definir una definición de "Terminado"
apropiada para el producto. Si hay varios Equipos Scrum trabajando en una
versión del sistema o producto, los Equipos de Desarrollo en todos los equipos
Scrum debe definir en conjunto la definición de "Terminado".

Cada Incremento es adicionable para todos los incrementos anteriores y probado a
fondo, asegurando que todos los Incrementos trabajan juntos.

A medida que los Equipos Scrum maduran, se espera que sus definiciones de
"Terminado" se amplien para incluir criterios más estrictos para obtener una 
mayor calidad. Cualquier producto o sistema deben tener una definición de
"Terminado" que es un estándar para cualquier trabajo realizado en el.

## <a name="endnote"></a> Nota final 

Scrum es gratuito y se ofrece en esta guía. Los roles, artefactos, eventos y
reglas de Scrum son inmutables y aunque la aplicación parcial de Scrum es
posible, el resultado no es Scrum. Scrum sólo existe como un todo y funciona
bien como un contenedor para otras técnicas, metodologías y prácticas.

## <a name="acknowledgements"></a> Agradecimientos 

### <a name="acknowledgements-people"></a> Personas 

De los miles de personas que han contribuido a Scrum, debemos destacar a los que
jugaron un papel decisivo en sus primeros diez años. Primero fue Jeff Sutherland
trabajando con Jeff McKenna, también Ken Schwaber trabajando con Mike Smith y Chris
Martin. Muchos otros contribuyeron en los siguientes años y sin su ayuda Scrum no se
hubiera perfeccionado hasta lo que es hoy.

### <a name="acknowledgements-history"></a> Historia 

Ken Schwaber y Jeff Sutherland presentaron Scrum por primera vez en la
conferencia OOPSLA en 1995. Esta presentación esencialmente documentó el
aprendizaje sobre la práctica de Scrum que Ken y Jeff adquirieron a lo largo de
los años anteriores.

La historia de Scrum ya lleva mucho tiempo. Para reconocer a los primeros
lugares en los que fue usado y mejorado, reconocemos Individual, Inc., Fidelity
Investments y IDX (ahora GE Medical).

La Guía de Scrum documenta Scrum tal y como fue desarrollado y mantenido por Jeff
Sutherland y Ken Schwaber por más de 20 años.  Otras fuentes proporcionan
patrones, procesos y conocimientos que complementan el marco de trabajo Scrum. 
Estas optimizan la productividad, el valor, la creatividad y el orgullo.

### <a name="acknowledgements-translation"></a> Traducción

Esta guía ha sido traducida al Español (México) a partir de la versión original en ingles proporcionada por
Ken Schwaber y Jeff Sutherland. La persona que ha contribuido a esta traducción
es: Martín Trejo Chávez

&copy;2017 Scrum.org y ScrumInc. 

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img
alt="Licencia Creative Commons" style="border-width:0"
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Esta obra
está bajo una <a rel="license"
href="http://creativecommons.org/licenses/by-sa/4.0/">Licencia Creative Commons
Atribución-CompartirIgual 4.0 Internacional</a>.
