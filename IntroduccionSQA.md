# Aseguramiento de la calidad de Software - SQA
SQA es la sigla de Software Quality Assurance que traducido al español significa Aseguramiento de calidad del Software.

El aseguramiento de la calidad del software es un medio y una práctica para monitorear los procesos y métodos de ingeniería del software utilizados en un proyecto para garantizar la calidad adecuada del software. Puede incluir asegurar la conformidad con estándares o modelos, como ISO / IEC 9126, SPICE o CMMI.
### Calidad de software:
> **Según IEEE 610**
Grado en el cual un componente, sistema o proceso satisface los requisitos especificados y/o necesidades y expectativas del usuario/cliente.
{.is-info}

Si nos fijamos ya se introduce el concepto de  **requisitos**  y lo importante que es cumplirlos. Es algo muy ligado a la calidad.

> **Según ISO/ IEC 9126**
> 
>  ISO 9126  es un estándar internacional para definir los procesos de evaluación de la Calidad de Software.
> 
> Este modelo indica que la calidad de software se debe medir en base a 6 características:
> 
> *Funcionalidad*: cumplimiento de los requisitos funcionales.
> Fiabilidad: cumplimiento de las prestaciones requeridas.
> Usabilidad: esfuerzo requerido por el usuario para utilizar el producto satisfactoriamente.
> Eficiencia: relación entre las prestaciones del software y los requisitos necesarios para su utilización.
> Mantenibilidad: facilidad para adaptarse a las nuevas especificaciones.
> Portabilidad: capacidad del software para poder portarse de un entorno a otro.
{.is-info}

Por lo tanto, son cosas a tener muy en cuenta a la hora de garantizar la calidad de un producto.

# Fundamentos Control de Calidad de Software
Dentro de las bases comunicacionales de la Gestion de calidad de softawre, es necesario conocer las actividades que se realizan en cada uno de los apartados, a continuacion vemos como la Gestión  de calidad de software trabaja dentro del proceso analitico que viene dentro del proceso del Aseguramiento de calidad del software, y este a su vez con el proceso de Control de calidad de software donde se realiza el proceso de Medición con base a lo que se tiene en marcha, contra los requerimientos definidos dentro de los procesos de gestion.

![gestion_aseguramiento_calidad.png](/calidad/gestion_aseguramiento_calidad.png)

Analisis comparativo entre Gestion de calidad de software, Aseguramiento de calidad de software y Control de calidad de software.

![tabla_comparativa_qm_qc_qa.png](/calidad/tabla_comparativa_qm_qc_qa.png)



### ¿Qué es Control de calidad de software? - Quality Control
El control de la calidad (Quality Control – QC) es un proceso (dentro del ciclo de vida de un proyecto) que se encarga de garantizar que los entregables del proyecto cumplen con los estándares de calidad definidos.
QC  se encarga de que los  entregables  del proyecto cumplan con los criterios de calidad definidos, tiene como objetivo garantizar un producto final de calidad.

### ¿Qué es Aseguramiento de calidad de software? - Quality Assurance
Se puede decir que el aseguramiento de la calidad (Quality Assurance – QA) es un proceso dentro de la gestión de proyectos que  monitoriza y verifica que el resto de procesos, métodos y actividades usados para generar los entregables del proyecto han sido seguidos y ejecutados correctamente.

- QA  se centra en asegurar que los  procesos  que intervienen en el desarrollo de software se cumplen.
- QA se encarga de la calidad en los procesos de desarrollo del producto, procesos de desarrollo de software.

### ¿Qué es Gestion de calidad de software? - Quality management

La gestión de la calidad establece que el 90% de los defectos o problemas de calidad son generados por los propios procesos y no por el personal. De esta manera, se entiende que una vez que los procesos se han mejorado de acuerdo con las opiniones de los operadores, diseñadores y gerentes, en los últimos años la gestión de la calidad se ha profundizado en la fabricación de productos competitivos en el mercado, a través de sistemas de comercialización, que cubren las necesidades del consumidor.  Se plantea la importancia de una buena comunicación empresarial para transmitir la misión y la visión de la empresa.

---


## 7 principales pruebas
Cuando pensamos en lo que podría salir mal, tenemos que considerar los defectos y fallas que surgen de:
- Errores en la especificación, diseño e implementación del software y sistema;
- Errores en el uso del sistema;
- Condiciones ambientales;
- Daño intencional;
- Posibles consecuencias de los errores anteriores, daño intencional, defectos y fracasos.
### ¿Cuál es el costo de los defectos?
El costo de encontrar y corregir defectos se eleva considerablemente en todo el ciclo de vida.

![costo_en_el_tiempo.png](/calidad/costo_en_el_tiempo.png)

Si se comete un error y el consiguiente defecto se detecta en los requisitos en la etapa de especificación, entonces es relativamente barato para encontrar y corregir.

A continuación se detallan los 7 principios de las pruebas:

![7_principios.png](/calidad/7_principios.png)

 
### Error - Defecto - Falla

- **Error**: Lo comete un humano durante el Proceso de Desarrollo. 
- **Defecto**: Es la consecuencia de un error. 
- **Falla**: Es un defecto no detectado y que no está eliminado. **Fallo**: Defecto que se manifiesta durante la ejecución.

### Códigos de estado de respuesta HTTP
Una de las herramientas basicas y esenciales es la Consola de nuestro navegador (web aplication) mediante esta herramienta nos permitira ver de manera inicial cual es el estado de las respuestas que tenemos de las acciones que se van realizando con la aplicación web. Entre ellas tenemos las siguientes: 

![tabla_de_respuestas_codes.png](/calidad/tabla_de_respuestas_codes.png)


## Procesos fundamentales de control de calidad
> **“Estos comienzan con la planificación de la prueba y continúan hasta el cierre de la prueba.”**
{.is-success}

### Actividades dentro del proceso de pruebas fundamental

![atividades_del_proceso_de_pruebas.png](/calidad/atividades_del_proceso_de_pruebas.png)

### 1. Planificación y control de pruebas
Durante la planificación de la prueba, nos aseguramos de comprender las metas y los objetivos de los clientes, las partes interesadas y el proyecto, y los riesgos que las pruebas deben abordar. 

Para ayudarnos, podemos tener políticas de prueba de organización o programa y una estrategia de prueba.

La planificación de pruebas tiene las siguientes tareas principales, dadas aproximadamente en orden, que nos ayudan a construir un plan de prueba:
• Determinar el alcance y los riesgos e identificar los objetivos de las pruebas.
• Determinar el enfoque de la prueba (técnicas, elementos de prueba, cobertura, identificación e interfaz con los equipos involucrados en las pruebas, software de prueba)
• Implementar la política de prueba y / o la estrategia de prueba.
• Determine los recursos de prueba necesarios (por ejemplo, personas, entorno de prueba, PC)
• Programar tareas de análisis y diseño de pruebas, implementación, ejecución y evaluación de pruebas
• Determine los criterios de salida

> La gestión de cualquier actividad no se limita a planificarla
{.is-success}

Necesitamos controlar y medir el progreso con respecto al plan.Entonces, el control de pruebas es una actividad continua.

El control de pruebas tiene las siguientes tareas principales:
• Medir y analizar los resultados de las revisiones y las pruebas
• Monitorear y documentar el progreso, la cobertura de la prueba y los criterios de salida
• Proporcionar información sobre las pruebas
• Iniciar acciones correctivas
• Tomar decisiones

### 2. Análisis y diseño de pruebas
Durante el análisis y el diseño de la prueba, tomamos los objetivos generales de la prueba identificados durante la planificación y construimos diseños de prueba y procedimientos de prueba (scripts)
 El análisis y el diseño de pruebas tienen las siguientes tareas principales, aproximadamente en el siguiente orden:

- Revisar la base de la prueba (como el análisis de riesgos del producto, los requisitos, la arquitectura, las especificaciones de diseño y las interfaces)
- 
- Identificar condiciones de prueba basadas en el análisis de elementos de prueba, sus especificaciones y lo que sabemos sobre su comportamiento y estructura.
- 
- Diseñe las pruebas utilizando técnicas para ayudar a seleccionar pruebas representativas que se relacionen con aspectos particulares del software que conllevan riesgos o que son de particular interés, según las condiciones de prueba y entrando en más detalles
- 
- Evaluar la capacidad de prueba de los requisitos y el sistema. Los requisitos pueden estar escritos de manera que permitan al evaluador diseñar pruebas.
- 
- Diseñe la configuración del entorno de prueba e identifique la infraestructura y las herramientas necesarias. 

### 3. Prueba de implementación y ejecución
 Durante la implementación y ejecución de la prueba, tomamos las condiciones de la prueba y las convertimos en casos de prueba y software de prueba y configuramos el entorno de prueba.

La implementación y ejecución de la prueba tienen las siguientes tareas principales:

#### 3.1. Implementación
- Desarrolle y priorice nuestros casos de prueba.
- Cree conjuntos de pruebas a partir de los casos de prueba para una ejecución de prueba eficiente.
- Implementar y verificar el entorno.


#### 3.2. Ejecución
- Ejecute las suites de prueba y los casos de prueba individuales.
- Registre el resultado de la ejecución de la prueba y registre las identidades y versiones del software bajo prueba.
- Compare los resultados reales con los resultados esperados.
- Cuando haya diferencias entre los resultados reales y esperados, notifique las discrepancias como incidentes.
- Repetir las actividades de prueba como resultado de la acción tomada para cada discrepancia. 

### 4. Evaluación de criterios de salida e informes
La evaluación de los criterios de salida es la actividad en la que la ejecución de la prueba se evalúa frente a los objetivos definidos, deben hacerse para cada nivel de prueba, ya que para cada uno necesitamos saber si hemos realizado suficientes pruebas. 

La evaluación de los criterios de salida tiene las siguientes tareas principales:
- Verifique los registros de prueba con los criterios de salida especificados en la planificación de la prueba.
- Evaluar si se necesitan más pruebas o si se deben cambiar los criterios de salida especificados.
- Escriba un informe resumido de la prueba para las partes interesadas

### 5. Actividades de cierre de prueba

Durante las actividades de cierre de la prueba, recopilamos datos de las actividades de prueba completadas para consolidar la experiencia, incluida la verificación y el archivo del software de prueba y el análisis de hechos y números.

Las actividades de cierre de la prueba incluyen las siguientes tareas principales:
- Verifique qué entregables planificados entregamos realmente.
- Finalice y archive el software de prueba, como los scripts.
- Entregue el software de prueba a la organización de mantenimiento.
- Evaluar cómo fueron las pruebas y analizar las lecciones aprendidas para futuros lanzamientos y proyectos.

# Prueba a lo largo del ciclo de vida del software

## Niveles de prueba
> 
> *La prueba no es una actividad independiente. Tiene su lugar dentro de un modelo de ciclo de vida de desarrollo de software y, por lo tanto, el ciclo de vida aplicado determinará en gran medida cómo se organizan las pruebas.*

### Modelos de desarrollo de software
El proceso de desarrollo adoptado para un proyecto dependerá de los objetivos y metas del proyecto. Existen numerosos ciclos de vida de desarrollo que se han desarrollado con el fin de lograr diferentes objetivos requeridos.

> **Las pruebas no existen de forma aislada**
{.is-danger}

#### Verificación - Validación
En cada ciclo de vida de desarrollo, una parte de las pruebas se centra en las pruebas de verificación y una parte se centra en las pruebas de validación.

- la verificación se centra en la pregunta ¿El entregable se construye de acuerdo con la especificación?
-
- La validación se centra en la pregunta ¿Es el entregable adecuado para el propósito? ¿Proporciona una solución al problema?


El ciclo de vida que seguira el proyecto, es orientado de acuerdo a la metodología que el equipo sigue, sea esta una metodología ágil y/o metodología tradicional.

## Tipos de pruebas
### Objetivo
Los tipos de prueba se introducen como un medio para definir claramente el objetivo de un determinado nivel de prueba para un programa o proyecto. 
Enfocar la prueba en un objetivo de prueba específico y, por lo tanto, seleccionar el tipo de prueba apropiado ayuda a tomar decisiones y comunicarlas con respecto a los objetivos de la prueba más fácilmente.

### 1. Prueba de funcionamiento (prueba funcional)
La función de un sistema (o componente) es 'lo que hace'. Esto se describe normalmente en una especificación de requisitos, una especificación funcional o en casos de uso.
Puede haber algunas funciones que se 'asume'que se proporcionarán que no están documentadas y que también son parte del requisito de un sistema, aunque es difícil de probar con requisitos no documentados e implícitos. Las pruebas funcionales se basan en estas funciones, se describen en documentos o son entendidas por los probadores y pueden realizarse.
Estas estan basadas en:
![pruebasfuncionales.png](/calidad/pruebasfuncionales.png)

Las técnicas utilizadas para las pruebas funcionales a menudo se basan en especificaciones, pero también se pueden utilizar técnicas basadas en la *experiencia*. 


### 2. Prueba no funcional
Atributos no funcionales del sistema (o componente o grupo de integración).
Aquí nos interesa saber qué tan bien o qué tan rápido se hace algo.
Las pruebas no funcionales incluyen, entre otras, pruebas de rendimiento, pruebas de carga, pruebas de estrés, pruebas de usabilidad, pruebas de mantenimiento, pruebas de confiabilidad y pruebas de portabilidad.

#### La norma ISO 9126
De acuerdo a la norma del estandar de calidad ISO 9126, para que las pruebas funcionales puedan ser cubiertas, estas deben contener los siguientes atributos cualitativos:

![iso9126-cualitativos6.png](/calidad/iso9126-cualitativos6.png)


### 3. Prueba de estructura / arquitectura de software (prueba estructural)
Las pruebas estructurales a menudo se denomina 'caja blanca' o 'caja de vidrio' porque estamos interesados en lo que está sucediendo 'dentro de la caja'.
A nivel de integración de componentes, puede basarse en la arquitectura del sistema, como una jerarquía de llamadas, integración de sistema o aceptación podría ser un modelo de negocio o una estructura de menú.
Las técnicas utilizadas para las pruebas estructurales son técnicas basadas en estructuras, también denominadas técnicas de caja blanca. 
> 
> El tercer objetivo de las pruebas *es la estructura* del sistema o componente.
{.is-success}

Las pruebas estructurales se utilizan con mayor frecuencia como una forma de medir la rigurosidad de las pruebas a través de la cobertura de un conjunto de elementos estructurales o elementos de cobertura. 

---------
Dentro de las caracteristicas principales contamos con las siguientes:

- Las Pruebas Estructurales es el término usado por ISTQB para las pruebas de “Caja Blanca”.
- Se realizan aplicando técnicas de pruebas estructurales y técnicas estáticas, en lugar de técnicas basadas en especificación.
- Utiliza el concepto de “Cobertura” para definir la extensión con la cual la estructura ha sido cubierta por el conjunto de pruebas, expresado como un porcentaje del elemento probado.
- Si la cobertura no es del 100%, se pueden diseñar pruebas adicionales.
- Las pruebas estructurales se basan en la arquitectura del sistema, por ejemplo arquitectura de “Jerarquía de llamadas”.

### 4. Pruebas relacionadas con cambios (pruebas de confirmación y regresión)

Dentro de las pruebas relacionadas con los cambios, nos encontramos con re testing y las pruebas de regresión, mismas que a continuación mencionamos:

#### 4.1 Prueba de confirmación (re testing)
- Las Re-Pruebas son aplicadas después que un defecto es identificado y corregido, con la finalidad de verificar que el defecto ya no se está presentando.

#### 4.2 Pruebas de regresión

- Las Pruebas de Regresión se realizan sobre un componente ya probado, para verificar que no presenta nuevos defectos cuando se realiza una modificación después de dichas pruebas. 
- Deben buscarse nuevos defectos tanto en en el componente que se está probando cómo otros componentes afectados por el cambio.
- Se necesita tener claridad de las piezas de software que resultan afectadas por el cambio.
- Las pruebas deben ser repetibles si han de usarse para pruebas de confirmación y regresión.
- Incluyen pruebas funcionales, no funcionales y estructurales.
- Dado que las pruebas se ejecutan repetidas veces, las pruebas de regresión son candidatas a la automatización de pruebas por medio de herramientas. Para ello podemos consultar el siguiente enlace: [introduccion-herramientasSQA](/capacitacion/calidad/introduccion-herramientasSQA)

### 5. Pruebas de mantenimiento

Una vez implementado, un sistema suele estar en servicio durante años o incluso décadas. Durante este tiempo, el sistema y su entorno operativo a menudo se corrigen, cambian o amplían. Las pruebas que se ejecutan durante esta fase del ciclo de vida se denominan "pruebas de mantenimiento".


Un proceso de prueba de mantenimiento generalmente comienza con la recepción de una solicitud de cambio o un plan de lanzamiento. El administrador de pruebas usará esto como base para producir un plan de prueba. Al recibir las especificaciones nuevas o modificadas, los casos de prueba correspondientes se especifican o adaptan.

![notapruebas.png](/calidad/notapruebas.png)

Las pruebas de mantenimiento, refieren a pruebas bajo las siguientes caracteristicas:
- Aplicadas sobre sistemas que están operativos en ambiente de producción.
- Se ejecutan como resultado de modificaciones, migraciones o desincorporación de software.
- Las Pruebas de Modificaciones incluyen mejoras planificadas, correctivas o de emergencia, así como cambios en el entorno de sistema operativo, bases de datos, actualizaciones o parches.
- Las Pruebas de Migración debe incluir pruebas operativas del nuevo entorno (Sistema operativo, base de datos, etc.) así como pruebas sobre el software modificado. Si existe migración y conversión de datos, también serán necesarias pruebas sobre estos.
- Las Pruebas por Desincorporación incluyen pruebas de migración de datos o su archivo si se requieren largos períodos de retención.
- Incluye también pruebas de regresión sobre las partes del sistema que no se están cambiando.
- Pueden ser difíciles de realizar si las especificaciones están desactualizadas o no existen, o si no se cuenta con Testers con conocimiento del sistema.



#### Análisis de impacto y pruebas de regresión
Cuando se inicia el análisis de impacto del sistema, iniciamos las pruebas de regresión para demostrar que el resto del sistema no se ha visto afectado por los trabajos de mantenimiento.

Dentro de las pruebas de mantenimiento es importante el análisis de impacto. sobre el cambio que se aplica al proyecto.

> **NOTA**: Es posible que las pruebas aplicadas a anteriores planes de pruebas, se puedan reutilizar para las pruebas de regresión y adaptarlas a los cambios del sistema.
{.is-info}


# Técnicas estáticas

## Técnica estática y procesos de casos de prueba
## Revisión de procesos
Las revisiones varían de muy informales a formales (es decir, bien estructuradas y reguladas). Aunque la inspección es quizás la técnica de revisión más documentada y formal, ciertamente no es la única. La formalidad de un proceso de revisión está relacionada con factores como la madurez del proceso de desarrollo, cualquier requisito legal o reglamentario o la necesidad de una pista de auditoría.

### Fases de una revisión formal
#### 1 Planificación
El proceso de revisión para una revisión en particular comienza con una "solicitud de revisión" del autor al moderador (o líder de la inspección). A menudo se asigna un moderador para que se encargue de la programación (fechas, hora, lugar e invitación) de la revisión. A nivel de proyecto, la planificación del proyecto debe permitir tiempo para las actividades de revisión y reelaboración, lo que proporciona a los ingenieros tiempo para participar a fondo en las revisiones.

Dentro de las revisiones se pueden identificar los siguientes enfoques:
- Centrarse en documentos de nivel superior, p. Ej. ¿El diseño cumple con los requisitos?
- Centrarse en los estándares, p. Ej. consistencia interna, claridad, convenciones de nomenclatura, plantillas;
- Centrarse en documentos relacionados al mismo nivel, p. Ej. interfaces entre funciones de software;
- Centrarse en el uso, p. Ej. para su capacidad de prueba o mantenibilidad.

#### 2 Inicio
Un paso opcional en un procedimiento de revisión es una reunión inicial. El objetivo de esta reunión es que todos estén en la misma linea con respecto al documento que se está revisando y comprometerse con el tiempo que se dedicará a la verificación. También se discuten el resultado de la verificación de entrada y los criterios de salida definidos en caso de una revisión más formal.

- Durante la reunión inicial, los revisores reciben una breve introducción sobre los objetivos de la revisión y los documentos.
- Las asignaciones de roles, la tasa de verificación, las páginas a verificar, los cambios de proceso y otras posibles preguntas también se discuten durante esta reunión.

#### 3 Preparación
Los participantes trabajan individualmente en el documento bajo revisión utilizando los documentos, procedimientos, reglas y listas de verificación relacionados proporcionados. Los participantes individuales identifican defectos, preguntas y comentarios, de acuerdo con su comprensión del documento y la función. Todos los problemas se registran, preferiblemente mediante un formulario de registro.

#### 4 Reunión de revisión
La reunión generalmente consta de los siguientes elementos (en parte dependiendo del tipo de revisión): 
- **Fase de registro**
Durante la fase de registro, los problemas, p. Ej. los defectos que se han identificado durante la preparación se mencionan página por página, revisor por revisor y son registrados por el autor o por un escriba. Una persona separada para hacer el registro (un escriba) es especialmente útil para tipos de revisión formales como una inspección. Las clases de gravedad pueden ser:
• Crítico: los defectos causarán daños corriente abajo; el alcance y el impacto del defecto están más allá del documento bajo inspección.
• Los defectos graves podrían causar un efecto posterior (por ejemplo, una falla en un diseño puede resultar en un error en la implementación).
• Leves, es poco probable que los defectos causen daños posteriores (por ejemplo, incumplimiento de las normas y plantillas).

- **Fase de discusión**
Los revisores que no necesiten participar en la discusión pueden irse o quedarse como ejercicio de aprendizaje. El moderador también marca el ritmo de esta parte de la reunión y se asegura de que todos los elementos discutidos tengan un resultado al final de la reunión o se definan como un punto de acción si una discusión no se puede resolver durante la reunión. El resultado de las discusiones está documentado para referencia futura.
Al final de la reunión, los participantes deben tomar una decisión sobre el documento que se está revisando, a veces basándose en criterios formales de salida.

- **Fase de decisión**
Establecer y acordar criterios de nivel de salida cuantificados ayuda al moderador a tomar decisiones firmes en todo momento.

#### 5 Revisión
En base a los defectos detectados, el autor irá mejorando paso a paso el documento bajo revisión. No todos los defectos que se encuentran conducen a un reproceso. Es responsabilidad del autor juzgar si se debe reparar un defecto. Si no se hace nada acerca de un problema por una determinada razón, se debe informar al menos para indicar que el autor ha considerado el problema.

#### 6 Seguimiento
El moderador es responsable de garantizar que se hayan tomado medidas satisfactorias en todos los defectos (registrados), sugerencias de mejora de procesos y solicitudes de cambio.

### Funciones y responsabilidades
#### Jefe
El jefe participa en las revisiones cuando decide la ejecución de las revisiones, asigna tiempo en los cronogramas del proyecto y determina si se han cumplido los objetivos del proceso de revisión. El gerente también se ocupará de cualquier capacitación de revisión solicitada por los participantes. Por supuesto, un gerente también puede participar en la revisión en sí, dependiendo de sus antecedentes, desempeñando el papel de revisor si esto fuera útil.

#### Moderador
El moderador (o líder de la revisión) dirige el proceso de revisión. Él o ella determina, en cooperación con el autor, el tipo de revisión, el enfoque y la composición del equipo de revisión. El moderador realiza la verificación de entrada y el seguimiento de la reelaboración, con el fin de controlar la calidad de la entrada y salida del proceso de revisión. El moderador también programa la reunión, difunde documentos antes de la reunión, entrena a otros miembros del equipo, marca el ritmo de la reunión, dirige posibles discusiones y almacena los datos que se recopilan.

#### Autores
Como autor del documento en revisión, el objetivo básico del autor debe sea aprender tanto como sea posible con respecto a la mejora de la calidad del documento, sino también para mejorar su capacidad para redactar documentos futuros.
La tarea del autor es iluminar las áreas poco claras y comprender los defectos encontrados.

#### Revisores
La tarea de los revisores (también llamados verificadores o inspectores) es verificar cualquier material en busca de defectos, principalmente antes de la reunión. El nivel de minuciosidad requerido depende del tipo de revisión. El nivel de conocimiento del dominio o experiencia técnica que necesitan los revisores también depende del tipo de revisión. Los revisores deben elegirse para representar diferentes perspectivas y roles en el proceso de revisión. Además del documento bajo revisión, el material que reciben los revisores incluye documentos fuente, estándares, listas de verificación, etc. En general, cuantos menos documentos fuente y de referencia se proporcionen, más experiencia en el dominio con respecto al contenido del documento bajo revisión se necesita.

#### Registrador (Escriba)
Durante la reunión de registro, el escriba (o registrador) debe registrar cada defecto mencionado y cualquier sugerencia para la mejora del proceso. En la práctica, a menudo es el autor quien desempeña este papel, asegurando que el registro sea legible y comprensible. Si los autores registran sus propios defectos, o al menos toman sus propias notas con sus propias palabras, les ayuda a comprender mejor el registro durante la reelaboración. Sin embargo, que alguien que no sea el autor tome el papel del escriba (por ejemplo, el moderador) puede tener ventajas significativas, ya que el autor tiene la libertad de pensar en el documento en lugar de estar atado con mucho escrito.

### Tipos de revisión
Un solo documento puede ser objeto de más de una revisión.
- Tutoriales
- Revisiones técnicas de documentación existente
- Técnicas sobre informacion disponible para el inicio de la revisión

### Factores críticos de éxito que mejoran las posibilidades de éxito al implementar revisiones. Su objetivo es responder a la pregunta "¿Cómo se inician las revisiones (formales)?"
- Encuentra un 'campeón' - Se necesita un campeón, uno que lidere el proceso a nivel de proyecto o de organización.
- Elige cosas que realmente cuenten
- Planifique y realice un seguimiento explícito de las actividades de revisión
- Capacitar a los participantes
- Gestionar problemas de personas
- Sigue las reglas pero mantenlo simple
- Informe de resultados
- ¡Simplemente hazlo!


# Técnicas de diseño de prueba
## Experiencia basada en técnicas
En esta sección veremos dos técnicas basadas en la experiencia, por qué y cuándo son útiles y cómo encajan con las técnicas basadas en especificaciones.
Si bien es cierto que las pruebas deben ser rigurosas, exhaustivas y sistemáticas, esto no es todo lo que hay que hacer. Existe un papel definido para las técnicas no sistemáticas, es decir, pruebas basadas en el conocimiento, la experiencia, la imaginación y la intuición de una persona. La razón es que algunos defectos son difíciles de encontrar usando enfoques más sistemáticos, por lo que un buen "cazador de errores" puede ser muy creativo para encontrar esos defectos esquivos.

### Tipos de tecnicas:
#### Adivinación de errores
La adivinación de errores es una técnica que siempre debe utilizarse como complemento de otras técnicas más formales. El éxito de la adivinación de errores depende en gran medida de la habilidad del evaluador, ya que los buenos evaluadores saben dónde es más probable que se escondan los defectos. 
Algunas personas parecen ser naturalmente buenas en las pruebas y otras son buenas probadoras porque tienen mucha experiencia ya sea como probadores o trabajando con un sistema en particular y, por lo tanto, son capaces de identificar sus debilidades.

Al utilizar técnicas más formales, es probable que el evaluador obtenga una mejor comprensión del sistema, lo que hace y cómo funciona. Con esta mejor comprensión, es probable que adivine mejor las formas en que el sistema puede no funcionar
No hay reglas para adivinar errores. Se anima al evaluador a pensar en situaciones en las que el software puede no ser capaz de hacer frente.


#### Prueba exploratoria
Las pruebas exploratorias son un enfoque práctico en el que los probadores participan en la planificación mínima y la ejecución máxima de la prueba. La planificación implica la creación de un estatuto de prueba, una breve declaración del alcance de un esfuerzo de prueba breve (de 1 a 2 horas) en el tiempo, los objetivos y los posibles enfoques que se utilizarán.

El diseño de la prueba y las actividades de ejecución de la prueba se realizan en paralelo normalmente sin documentar formalmente las condiciones de la prueba, los casos de prueba o los scripts de prueba. Esto no significa que no se utilizarán otras técnicas de prueba más formales. Por ejemplo, el evaluador puede decidir utilizar el análisis de valor límite, pero pensará y probará los valores límite más importantes sin necesariamente escribirlos.

El registro de pruebas se lleva a cabo a medida que se realiza la ejecución de la prueba, documentando los aspectos clave de lo que se prueba, cualquier defecto encontrado y cualquier idea sobre posibles pruebas adicionales. Un aspecto clave de las pruebas exploratorias es el aprendizaje: que el evaluador aprenda sobre el software, su uso, sus fortalezas y sus debilidades.

> Cada técnica es buena para ciertas cosas y no tan buena para otras.
{.is-success}

### Factores a considerar
La elección de qué técnicas de prueba utilizar depende de una serie de factores:
**COMO**:  El tipo de sistema, las normas reglamentarias, los requisitos contractuales o del cliente, el nivel de riesgo, el tipo de riesgo, el objetivo de la prueba, la documentación disponible, el conocimiento de los probadores, el tiempo y presupuesto, ciclo de vida de desarrollo, modelos de casos de uso y experiencia previa de los tipos de defectos encontrados.

**Entonces, ¿cómo podemos elegir las técnicas de prueba más adecuadas para usar?**
La decisión se basará en una serie de factores:
- Internos
- Externos

### Los factores internos que influyen en la decisión sobre qué técnica utilizar son:

• **Modelos utilizados**: dado que las técnicas de prueba se basan en modelos, los modelos disponibles (es decir, desarrollados y utilizados durante la especificación, diseño e implementación del sistema) gobernarán en cierta medida qué técnicas de prueba se pueden utilizar. Por ejemplo, si la especificación contiene un diagrama de transición de estado, la prueba de transición de estado sería una buena técnica a utilizar.
• **Conocimiento de los probadores que experimento**: la cantidad de conocimientos de los probadores sobre el sistema y las técnicas de prueba influirá claramente en su elección de técnicas de prueba. Este conocimiento en sí mismo estará influenciado por su experiencia de prueba y del sistema bajo prueba.
• **Probables defectos**: el conocimiento de los probables defectos será muy útil para elegir las técnicas de prueba (ya que cada técnica es buena para encontrar un tipo particular de defecto). Este conocimiento podría obtenerse a través de la experiencia de probar una versión anterior del sistema y niveles previos de prueba en la versión actual.
• **Objetivo de la prueba**: si el objetivo de la prueba es simplemente ganar confianza en que el software hará frente a las tareas operativas típicas, los casos de uso serían un enfoque sensato. Si el objetivo es realizar pruebas muy exhaustivas, se deben elegir técnicas más rigurosas y detalladas (incluidas técnicas basadas en estructuras).
• **Documentación**: la existencia o no de documentación (por ejemplo, una especificación de requisitos) y si está actualizada afectará la elección de las técnicas de prueba. El contenido y el estilo de la documentación también influirán en la elección de las técnicas (por ejemplo, si se han utilizado tablas de decisión o gráficos de estado, deben utilizarse las técnicas de prueba asociadas).
• **Modelo de ciclo de vida**: un modelo de ciclo de vida secuencial se prestará al uso de técnicas más formales, mientras que un modelo de ciclo de vida iterativo puede ser más adecuado para utilizar un enfoque de prueba exploratorio.

### Los factores externos que influyen en la decisión sobre qué técnica utilizar son:
• **Riesgo**: cuanto mayor sea el riesgo (p. Ej., Sistemas críticos para la seguridad), mayor será la necesidad de realizar pruebas más completas y formales. El riesgo comercial puede verse influido por problemas de calidad (por lo que sería apropiado realizar pruebas más exhaustivas) o por problemas de tiempo de comercialización (por lo que las pruebas exploratorias serían una opción más apropiada).
• **Requisitos contractuales del cliente**: en ocasiones, los contratos especifican técnicas de prueba particulares a utilizar (más comúnmente cobertura de sucursales o declaraciones).
• **Tipo de sistema**: el tipo de sistema (por ejemplo, integrado, gráfico, financiero, etc.) influirá en la elección de las técnicas. Por ejemplo, una aplicación financiera que implique muchos cálculos se beneficiaría del análisis de valor límite.
• **Requisitos reglamentarios**: algunas industrias tienen normas o pautas reglamentarias que rigen las técnicas de prueba utilizadas. Por ejemplo, la industria aeronáutica requiere el uso de partición de equivalencia, análisis de valor límite y pruebas de transición de estado para sistemas de alta integridad junto con declaración, decisión o cobertura de decisión de condición modificada según el nivel de integridad del software requerido.
• **Tiempo y presupuesto**: en última instancia, la cantidad de tiempo disponible siempre afectará la elección de las técnicas de prueba. Cuando haya más tiempo disponible, podremos permitirnos seleccionar más técnicas y cuando el tiempo sea muy limitado, estaremos limitados a aquellas que sabemos que tienen una buena posibilidad de ayudarnos a encontrar los defectos más importantes.


# Gestión de pruebas
## Organización de casos de prueba
Hay mucho por hacer para examinar los productos de trabajo de software sin ejecutar realmente el sistema. Por ejemplo, vimos en la sección anterior que podemos revisar cuidadosamente los requisitos, diseños, códigos, planes de prueba y más, para encontrar defectos y corregirlos antes de entregar un producto a un cliente. 

En esta sección, nos enfocamos en un tipo diferente de prueba estática, donde examinamos cuidadosamente los requisitos, los diseños y el código, generalmente con asistencia automatizada para descubrir defectos adicionales antes de que el código se ejecute realmente. Por lo tanto, lo que se llama análisis estático es solo otra forma de prueba.


De acuerdo al estandar IEEE 829 STANDARD, contemplamos la siguiente estructura:

![casodepruebaieee.png](/calidad/casodepruebaieee.png)

Cabe recalcar que para dicha estructura mucho depende de la herramienta que facilitara la organización de nuestros casos de prueba, (con mas o menos campos) con base a lo mencionado, el estandar IEEE 829 muestra una descripcion troncal de la estructura de Caso de Prueba.

## Estructura para el registro de un Bug
Debemos tomar encuenta los siguiente campos:
- ID del Bug
- Titulo : >> Estructura base: QA : Seccion>(subseccion, si existiera): Titulo del fallo
- Pre condición 
- Resumen
- Pasos a seguir y reproducir el error.
- Resultado actual
- Resultado esperado
- Ambiente de prueba
- Caso de prueba
- Evidencia

**PLANTILLA DE ESPECIFICACIONES DEL CASO DE PRUEBA**
- Identificador de especificación de caso de prueba
- Especificaciones de salida
- Elementos de prueba
- Necesidades ambientales
- Especificaciones de entrada
- Requisitos procesales especiales
- Dependencias entre casos

**PLANTILLA DE ESPECIFICACIONES DEL PROCEDIMIENTO DE PRUEBA**
- Identificador de especificación del procedimiento de prueba
- Propósito
- Requisitos especiales
- Pasos del procedimiento

El cómo organizar un esfuerzo de prueba dentro de un proyecto, muestra el trabajo de un equipo donde los distintos roles de los miembros del equipo de prueba que podríamos querer en un equipo de prueba. Y nos familiarizaremos con las tareas típicas que realizan los líderes de prueba y los evaluadores.

## Roles en Testing
Hemos visto que la ubicación de un equipo de prueba dentro de la organización de un proyecto puede variar ampliamente. De manera similar, existe una amplia variación en los roles que desempeñan las personas dentro del equipo de prueba. Algunos de estos roles ocurren con frecuencia, otros con poca frecuencia. Dos roles que se encuentran dentro de muchos equipos de prueba son los del líder de la prueba y el evaluador, aunque las mismas personas pueden desempeñar ambos roles en varios puntos durante el proyecto. Echemos un vistazo al trabajo realizado en estos roles, comenzando con el líder de la prueba.

### Lideres de prueba
Los líderes de prueba tienden a participar en la planificación, el seguimiento y el control de las actividades y tareas de prueba sobre el proceso de prueba fundamental. Al comienzo del proyecto, los líderes de prueba, en colaboración con las otras partes interesadas, diseñan los objetivos de la prueba, las políticas de prueba de la organización (si no están ya implementadas), las estrategias de prueba y los planes de prueba. Ellos estiman las pruebas a realizar y negocian con la gerencia para adquirir los recursos necesarios. Reconocen cuándo es apropiada la automatización de pruebas y, si lo es, planifican el esfuerzo, seleccionan las herramientas y garantizan la formación del equipo.
A veces, los líderes de las pruebas llevan títulos diferentes, como administrador de pruebas o coordinador de pruebas.


### Tester
Al igual que con los líderes de prueba, los proyectos deben incluir probadores desde el principio, aunque a menudo el proyecto no necesita un complemento completo de probadores hasta el período de ejecución de la prueba. En las fases de planificación y preparación de las pruebas, los probadores deben revisar y contribuir a los planes de prueba, así como analizar, revisar y evaluar los requisitos y especificaciones de diseño. Pueden participar o incluso ser las personas principales que identifican las condiciones de prueba y crean diseños de prueba, casos de prueba, especificaciones de procedimientos de prueba y datos de prueba, y pueden automatizar o ayudar a automatizar las pruebas.

A medida que comienza la ejecución de la prueba, el número de probadores a menudo aumenta, comenzando con el trabajo requerido para implementar las pruebas en el entorno de prueba. (Pueden desempeñar ese papel en todos los niveles de prueba, incluso aquellos que no están bajo el control directo del grupo de prueba; por ejemplo, podrían implementar pruebas unitarias diseñadas por programadores). Los probadores ejecutan y registran las pruebas, evalúan los resultados y documentar problemas encontrados. Supervisan las pruebas y el entorno de prueba, a menudo utilizando herramientas para esta tarea y, a menudo, recopilan métricas de rendimiento. A lo largo del ciclo de vida de las pruebas, revisan el trabajo de los demás, incluidas las especificaciones de las pruebas, los informes de defectos y los resultados de las pruebas.

### Definición de las necesidades del personal de la prueba de habilidades

Hacer las pruebas correctamente requiere más que definir los puestos correctos y la cantidad de personas para esos puestos. Los buenos equipos de prueba tienen la combinación adecuada de habilidades en función de las tareas y actividades que necesitan realizar, y las personas ajenas al equipo de prueba que están a cargo de las tareas de prueba también necesitan las habilidades adecuadas.
Las personas involucradas en las pruebas necesitan calificaciones profesionales y sociales básicas como alfabetización, la capacidad de preparar y entregar informes escritos y verbales, la capacidad de comunicarse de manera efectiva, etc.

Ademas de poder ver el siguiente video : [qa.mp4](/calidad/qa.mp4)

## Técnicas de Testing: métodos para  generar un caso de prueba

Dentro de las Tecnicas de pruebas en el aseguramiento de la calidad de software, nos encontramos con Pruebas Estaticas y Dinamicas.

![procesos_de_casos_de_prueba1.png](/calidad/procesos_de_casos_de_prueba1.png)

Como mostramos en la imagen, podemos constatar que **las pruebas estáticas** incluyen todas esas revisiones que implican el analisis del flujo de nuestro proyecto ademas del flujo de datos, ademas de analizar las métricas definidas en los requerimientos delimitados de manera explícita e implícita.

Las pruebas dinamicas es donde nos encontramos con pruebas de Caja Negra y de Caja Blanca (tecnicas basadas en experiencia).

![procesos_de_construccion_de_casos_de_prueba1.png](/calidad/procesos_de_construccion_de_casos_de_prueba1.png)

### Pruebas estáticas
Dichas pruebas son realizadas  sin ejecutar el código de la aplicación y su objetivo son realizar documentación y códigos fuente, incluye revisiones y análisis estático.

**OBJETIVO**: Mejorar la calidad del producto y reducir propagación de errores entre fases  (modelo-v)

La detección temprana de errores ahorra costes a posteriori.
Defectos potencialmente detectables en:
- Documentos de especificación y arquitectura
- Especificaciones de interfaces
- Desviaciones respecto a estándares acordados  (e.g. Guías de programación)
Tarea eminentemente manual.

![pruebas_estaticas.png](/calidad/pruebas_estaticas.png)

**OBJETIVO**: Buscar errores en la especificación de objetos de prueba (e.g. Código fuente, script,  etc.) sin ejecutar el objeto de prueba.

Aspectos a detectar:

- Reglas y estándares de programación
- Diseño de un programa (análisis del flujo de control)
- Uso de datos (análisis flujo de datos)
- Complejidad de la estructura de un programa (métricas, e.g., nº ciclomático)

Existen herramientas compiladores, analizadores

- Detectar lógica errónea (bucles potencialmente infinitos)
- Detectar estructuras lógicas complejas, inconsistencias entre interfaces, etc.
- Supone menor esfuerzo que una inspección


### Pruebas dinámicas
#### Caja Negra
El tester observa el objeto de prueba como una caja negra.
*-- La estructura interna del objeto de prueba es irrelevante o desconocida.*

Los casos de prueba se obtienen a partir del análisis de la especificación (funcional o no  funcional) de un componente o sistema
*-- Prueba de comportamiento entrada/salida*

> ¡La utilidad es el foco de atención!
{.is-info}

-- La técnica de caja negra también se denomina prueba funcional o prueba orientada a la  especificación

![caja_negra.png](/calidad/caja_negra.png)


##### Métodos de caja negra:

- Partición de equivalencias o clases de equivalencia.
- Análisis de valores límite.
- Pruebas de casos de uso.
- Tablas de decisión, de transición de estado, …

De manera general, la ejecución de casos de prueba debería ser ejecutados con una baja
redundancia, pero con carácter completo.

- Probar lo **menos** posible, pero
- Probar **tanto** como sea necesario

###### Método: Clases de equivalencia (CE)

Consiste en dividir los valores de entrada en clases de datos para derivar casos de prueba.
Se asume que el resultado de una prueba con un valor representativo de cada CE equivale a  realizar la misma prueba con cualquier otro valor de la CE.

Pasos para diseñar casos de prueba:

1. Identificar clases de equivalencia.
1. Identificar los casos de prueba. Minimizando nº casos de prueba, considerar tantas  condiciones como sea posible. Pasos:

-- Asignar a cada CE un representante único.
-- Definir casos de prueba que cubran tantas CE válidas como sea posible. Repetir  hasta que todas las CE estén cubiertas.
-- Definir un caso de prueba para cubrir una única CE no válida. Repetir hasta que  todas estén cubiertas.

**Ejemplo**: un programa requiere un número entero [0…100]. Posibles clases de equivalencia:

*Identificar clases de equivalencia. Definir clases de datos válidos y no válidos.*

-- CE válida: 0 <= X <= 100
-- 1ra CE no válida: X > 100
-- 2da CE no válida: X < 0
-- 3ra CE no válida: X = decimal
-- 4ta CE no válida: X = alfanumérico

##### Método: Análisis de Valores Límite

La experiencia demuestra que casos de prueba sobre condiciones límite infieren mejores  resultado.
Condiciones límite = márgenes de las clases de equivalencia (CE).
Esta técnica complementada técnica de CE:
- Identificar las condiciones límite para los datos de entrada
- Generar tantos casos de prueba como sean necesarios para ejercitar las condiciones  límites.

**Ejemplo**: Construcción de una batería de pruebas para detectar posibles errores en la construcción de  los identificadores de un hipotético lenguaje de programación. La regla que determina sus  construcción sintáctica es: 'No debe tener mas de 15 ni menos de 5 caracteres'

![analisis_de_valores_limite.png](/calidad/analisis_de_valores_limite.png)

##### Método: Pruebas de Casos de Uso

Los casos de prueba son obtenidos desde los casos de uso.
- Cada caso de uso puede ser utilizado como fuente para un caso de prueba, pero cada paso alternativo del caso de uso, se traduce en una prueba distinta.

Cada caso de uso describe una cierta interacción usuario-sistema. Elementos:
- Precondiciones, pasos del comportamiento del sistema, post condiciones.

![caso_de_uso11.png](/calidad/caso_de_uso11.png)

**Beneficios**
    - Pruebas apropiadas para pruebas de aceptación y  de sistema.
    - Útil para diseñar pruebas con el cliente/usuario.
    - Pueden ser combinadas con otras técnicas basadas en la especificación.

**Desventajas**
		- No es posible obtener casos de prueba más allá de la información de los casos de uso.

**Ejemplo**: Cajero automático
Prueba 1. Insertar tarjeta (no válida); fin
Prueba 2. Insertar tarjeta (válida);  introduce código (no válido); fin
Prueba 3. Insertar tarjeta (válida);  introduce código (válido);…; fin
Prueba 4. Insertar tarjeta (válida);  introduce código (no válido);  introduce código (no válido); fin
Prueba 5. …

![flujo_de_caso_de_prueba11.png](/calidad/flujo_de_caso_de_prueba11.png)


#### Caja Blanca
El tester conoce la estructura interna del código, i.e., la jerarquía de componentes, flujo de control y datos, etc.
Los casos de prueba son seleccionados en base a la estructura del código.

> ¡La estructura del trabajo es el foco de atención!
{.is-info}

La técnica de caja blanca también es conocida como prueba basada en la estructura o prueba basada en el flujo de control.

Los métodos de caja blanca requieren el apoyo de herramientas, lo que asegura la calidad de las pruebas e incrementa su eficiencia.
> Dada la complejidad de las mediciones necesarias para las pruebas de caja blanca, la ejecución manual implica: consumo de tiempo y recursos, dificultad en la implementación y propensión a  errores.

Métodos de caja blanca (basados en la cobertura)

> Cobertura de sentencias.
> Cobertura de decisión.
> Cobertura de condición (simple y múltiple).
> Cobertura de caminos.
{.is-info}
      
##### Método: Cobertura de Sentencias

Técnica basada en el análisis del gráfico del flujo de control (sentencias = nodos; flujo de  control = aristas). El foco de atención es la sentencia del código !!
Objetivo: lograr la cobertura de un porcentaje específico (C0) de todas las sentencias. Cada  sentencia se debe ejecutar, al menos, una vez.

> C~0~ = 100% * (nº sentencias ejecutadas / nº total sentencias)

**Ejemplo**:
Todas las sentencias pueden  ser alcanzadas haciendo uso  de un único camino 100%  de cobertura de sentencia. **Un único caso prueba**.
![cobertura_de_sentencias.png](/calidad/cobertura_de_sentencias.png)


##### Método: Cobertura de Decisión
Se centra en el flujo de control (aristas del diagrama de flujo)
Objetivo: Todas las aristas del diagrama de flujo tiene que ser cubiertas al menos una vez.  Lograr un porcentaje de cobertura de todas las decisiones (C~1~)
> C~1~ = 100% * (nº decisiones ejecutadas / nº total decisiones)

**Ejemplo:**

En la siguiente imagen:
**¿Cuántos caminos consigue una cobertura  de precisión del 100%?**
    - Una cobertura de decisión del 100%  requiere, al menos, los mismos casos de  prueba que una cobertura sentencia.

![cobertura_de_decisión.png](/calidad/cobertura_de_decisión.png)

##### Método: Cobertura de Condición

**Objetivo**: detectar defectos en la implantación de condiciones.

- En este criterio es necesario presentar un número suficiente de casos de prueba de modo  que cada condición en una decisión tenga, al menos una vez, todos los resultados posibles.

**Tipos**:

> Cobertura de condición simple.
> Cobertura de condición múltiple.
{.is-info}

    
###### Método: Cobertura de Condición SIMPLE

Cada subcondición atómica de una sentencia condicional tiene que tomar, al menos una vez,  los valores verdadero ("true") y falso ("false").

**Ejemplo**: considerar la condición A>2 OR B<6. En los casos de prueba para la cobertura de condición  simple podrían ser (por ejemplo):
- Con sólo dos casos de prueba se puede  lograr una cobertura de condición  simple.
- Cada subcondición ha tomado los  valores verdadero y falso.
- Sin embargo, el resultado combinado es  verdadero en ambos casos.

![coberturasimple.png](/calidad/coberturasimple.png)

######  Método: Cobertura de Condición MÚLTIPLE

Todas las combinaciones que pueden ser creadas utilizando permutaciones de las  subcondiciones atómicas deben formar parte de las pruebas.

**Ejemplo**: considerar la condición A>2 OR B<6. En los casos de prueba para la cobertura de condición  múltiple podrían ser (por ejemplo):
- Con sólo 4 casos de prueba se puede lograr  una cobertura de condición múltiple.
- Se han creado todas las combinaciones  verdadero/falso.
- Se han logrado todos los posibles  resultados de la condición.
- nº casos de prueba exponencial: 2^n^, donde n
- = nº condiciones atómicas

![coberturamultiple.png](/calidad/coberturamultiple.png)

###### Método: Cobertura de Camino

Consiste en ejecutar todos los posibles cambios a través de un programa. Esto puede  conducir a un nº muy alto de casos de prueba.

- *Camino*: secuencia de instrucciones en el flujo de control (nodos y aristas en el  diagrama de control).
- Cada camino va desde el nodo inicial al final del diagrama de flujo de control.

Para una cobertura de decisión, un solo camino a través de un bucle es suficiente. Sin  embargo, en la cobertura por caminos hay más casos de prueba:

- Un caso prueba no entrante en el bucle
- Un caso prueba adicional para cada ejecución del bucle

*Objetivo*: alcanzar un porcentaje definido de cobertura de camino (CC):

> CC = 100% * (nº caminos cubiertos / nº total caminos)


**Ejemplo**:
Observar la siguiente imagen y responder las siguientes preguntas:

1. **¿Cuántos casos de prueba para una cobertura de camino del  100%?**
1. **¿Cuántos casos de prueba para una cobertura de sentencia  del 100%?**
1. **¿Cuántos casos de prueba para una cobertura de decisión  del 100%?**

![cobertura_de_camino.png](/calidad/cobertura_de_camino.png)

**Respuestas**:
1. 5 casos de prueba
1. 2 casos de prueba
1. 3 casos de prueba

**Aspectos a tener en cuenta:**

> El 100% de cobertura de caminos sólo en programas muy simples.
> La cobertura de camino es más exhaustiva que la cobertura de sentencia y de decisión.
> El 100% de cobertura de camino incluye el 100% de cobertura de decisión que a su  vez incluye el 100% de cobertura de sentencia.
{.is-success}


Actualmente el número de herramientas para pruebas de software  disponibles, tanto en el mercado como de manera gratuita (herramientas  de código abierto), se pueden organizar de la siguiente manera:
**- Herramientas de gestión de pruebas**
**- Herramientas para pruebas funcionales**
**- Herramientas para pruebas de carga y rendimiento**
**- Herramientas de calidad del producto software**


# Estándares / modelos en SQA
## Metodologías ágiles
Podemos definir las metodologías ágiles como un conjunto tareas y procedimientos dirigidos a la gestión de proyectos. Son aquellos métodos de desarrollo en los cuales tanto las necesidades como las soluciones a estas evolucionan con el pasar del tiempo, a través del trabajo en equipo de grupos multidisciplinarios que se caracterizan por tener las siguientes cualidades:

- Desarrollo evolutivo y flexible.
- Autonomía de los equipos.
- Planificación.
- Comunicación.

Existen diferentes opciones ágiles entre las cuales podemos destacar las siguientes: Scrum, programación extrema (XP) y Kanban, siendo estas tres (03) las alternativas más utilizadas. Es importante mencionar, que todas las metodologías ágiles cumplen con el Manifiesto ágil, el cual se encuentra compuesto por doce (12) principios agrupado en cuatro (04) valores fundamentales:
- Individuos e interacciones sobre procesos y herramientas.
- Software funcionando sobre documentación extensiva.
- Colaboración con el cliente sobre negociación contractual.
- Respuesta ante el cambio sobre seguir un plan.
### XP (eXtreme Programming)
Conocida por sus siglas XP (eXtreme Programming), es una metodología basada en un conjunto de reglas y buenas prácticas para el desarrollo de software en ambientes muy cambiantes con requisitos imprecisos, por ende está enfocada en la retroalimentación continua entre el equipo de desarrollo y el cliente.

Es por ello que iniciando el proyecto se deben definir todos los requisitos, para luego invertir el esfuerzo en manejar los cambios que se presenten y así minimizar las posibilidades de error. XP tiene como base la simplicidad y como objetivo la satisfacción del cliente.

![xp.png](/calidad/xp.png)

**CARACTERÍSTICAS DE XP**
En resumen las principales características de la programación extrema son:

1. Desarrollo iterativo e incremental.
1. Programación en parejas.
1. Pruebas unitarias continuas.
1. Corrección periódica de errores.
1. Integración del equipo de programación con el cliente.
1. Simplicidad, propiedad del código compartida y refactorización del código.

### Scrum
Esta metodología, es un marco de trabajo de procesos ágiles que trabaja con el ciclo de vida iterativo e incremental, donde se va liberando el producto por pares de forma periódica, aplicando las buenas prácticas de trabajo colaborativo (en equipo), facilitando el hallazgo de soluciones óptimas a los problemas que pueden ir surgiendo en el proceso de desarrollo del proyecto.

Con Scrum se realizan entregas regulares y parciales (sprint) del producto final, todas ellas con una prioridad previamente establecida que nace según el beneficio que aporten al cliente, minimizando los riesgos que pueden surgir de desarrollos extremadamente largos. Es por tal motivo, que Scrum está especialmente indicado para proyectos en entornos complejos, donde se necesitan obtener resultados de manera inmediata y donde son fundamentales los siguientes aspectos: la innovación, la productividad, la flexibilidad y la competitividad.

![scrum.png](/calidad/scrum.png)

**¿QUIÉN CONFORMA EL EQUIPO SCRUM?**
En los Equipos Scrum, se cuenta con roles específicos y cada uno de ellos es imprescindible para que se lleve a cabo el proceso de forma satisfactoria:

- **Stakeholder**: Es el cliente, su responsabilidad radica en definir los requerimientos (Product Backlog), recibir el producto al final de cada iteración y proporcionar el feedback correspondiente.
- **Product Owner**: Es el intermediario de la comunicación entre el cliente (stakeholder) y el equipo de desarrollo. Este debe priorizar los requerimientos según sean las necesidades de la solicitud.
- **Scrum Master**: Actúa como facilitador ante todo el equipo de desarrollo, elimina todos aquellos impedimentos que identifique durante el proceso, así mismo se encarga de que el equipo siga los valores y los principios ágiles, las reglas y los procesos de Scrum, incentivando al grupo de trabajo.
- **Scrum Team (Equipo de desarrollo):** Se encarga de desarrollar los casos de uso definidos en el Product Backlog, es un equipo auto gestionado lo que quiere decir que no existe un de jefe de equipo, motivo por el cual todos los miembros se deben de encargar de realizar las estimaciones y en base a la velocidad obtenida en las iteraciones irán construyendo el Sprint Backlog.

### Kanban
Proveniente de una palabra japonesa cuyo significado es “Tarjeta Visual” es un marco de trabajo que requiere una comunicación en tiempo real sobre la capacidad del equipo, utilizado para controlar el avance de trabajo en una línea de producción, en la cual se clasifican las tareas en sub estatus, esto con la intención de determinar los niveles de productividad en cada fase del proyecto.

Para el desarrollo de software, gracias a su sencillez KANBAN, simplifica la planificación y la asignación de responsabilidades, en un tablero se representan los procesos del flujo de trabajo, cómo mínimo deben existir tres columnas (Pendiente, En Progreso, Terminado), la cantidad de tarjetas en estatus pendiente forma parte de lo solicitado por el cliente, aquellas colocadas en progreso dependerán de la capacidad del equipo de trabajo.

![canvan.png](/calidad/canvan.png)

**VENTAJAS KANBAN**
A continuación se listan las principales ventajas:

1. Planificación de tareas.
1. Tiempos de ciclos reducidos.
1. Rendimiento del equipo de trabajo.
1. Métricas visuales.
1. Menos cuellos de botella.
1. Entrega continua.

Las metodologías ágiles comparten ciertas características, buscan la interacción de los miembros del grupo de trabajo, siempre con la meta de satisfacer los requisitos del cliente. Estas no se limitan tan sólo a desarrollos de software, con ellas se pueden gestionar cualquier tipo de proyectos. 


## Estandares de Calidad de Software
Modelos y estandares de software:
![tablastandares.png](/calidad/tablastandares.png)

## Modelo de calidad CMMI
Integración de los Modelos de Madurez de Capacidades (Por sis siglas en ingles : Capability Maturity Model Integration)

El propósito del Aseguramiento de la Calidad del Proceso y del Producto (PPQA) es proporcionar al personal y a la gerencia una visión objetiva de los procesos y de los productos de trabajo asociados.

**Áreas de procesos relacionadas**

![screen_shot_2021-07-13_at_15.38.24.png](/calidad/screen_shot_2021-07-13_at_15.38.24.png)

Dentro de las areas mencionadas en la imagen, nos encontramos los KPA – Key Process Area.

**Metas y practicas específicas **

SG 1 Evaluar objetivamente los procesos y los productos de trabajo.
- SP 1.1 Evaluar objetivamente los procesos.
- SP 1.2 Evaluar objetivamente los productos de trabajo.

SG 2 Proporcionar una visión objetiva.
- SP 2.1 Comunicar y resolver las no conformidades.
- SP 2.2 Establecer los registros.

Que van de la mano de PPQA del inglés Process and Product Quality Assurance.

# Referencias:
- Implementación de los circulos de la calidad en el Instituto Superior Tecnológico ITEC, by Gutarra Montalvo, Victor Alberto, https://sisbib.unmsm.edu.pe/BibVirtualData/Tesis/Ingenie/Gutarra_M_V/pag34.pdf
- Control de calidad Vs Aseguramiento de la calidad, https://testerhouse.com/procesos-testing/qa-qc/
- Barbara K. Immel. "Quality Assurance of pharmaceuticals". Encyclopedia of pharmaceutical technology 2002.
- Alfonso C.Montero; Pedro I. Rodríguez."Calidad". Ed Editex España 2003.
- Norma ISO 9000:2005 Sistemas de gestión de la calidad -Fundamentos y vocabulario.
- FOUNDATIONS OF SOFTWARE TESTING ISTQB CERTIFICATION by Dorothy Graham Erik van Veenendaal,Isabel Evans Rex Black