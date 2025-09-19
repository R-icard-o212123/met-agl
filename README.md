# Metodologías Ágiles Para El Desarrollo De Software

## ¿Qué son las Metodologías Ágiles?

Las metodologías ágiles son un conjunto de enfoques y prácticas para el desarrollo de software que se centran en la entrega rápida de software funcional de alta calidad y en la colaboración estrecha entre los miembros del equipo y los clientes. Estas metodologías promueven la adaptabilidad, la flexibilidad y la mejora continua a lo largo del ciclo de vida del desarrollo del software. 

Surgieron como una respuesta directa a las metodologías tradicionales, como el modelo de cascada (waterfall), que eran inflexibles ante los cambios y posponían las pruebas hasta el final del proceso.

## Características y principios clave de las metodologías ágiles:


- **Centradas en el cliente**: Buscan satisfacer al cliente y validar constantemente cada paso y decisión con el usuario.
- **Adaptación al cambio**: Están abiertas a las modificaciones, incluso en etapas avanzadas del desarrollo, lo que las hace útiles cuando los requisitos no están completamente definidos o pueden variar con el tiempo.
- **Entrega continua y temprana**: Priorizan la entrega frecuente y rápida de software que funciona, en lugar de esperar entregas largas y demoradas.
- **Colaboración y comunicación**: Fomentan el trabajo en conjunto, la conversación cara a cara, y una colaboración muy estrecha entre los equipos de desarrollo y los clientes.
- **Equipos autoorganizados y motivados**: Promueven que los individuos estén motivados y que los equipos tengan la capacidad de organizarse para realizar el trabajo.
- **Iterativas e incrementales**: El desarrollo se divide en ciclos cortos (iteraciones o sprints) que producen versiones refinadas o componentes del software.
- **Mejora continua**: Cada iteración permite la adaptación rápida y una mejora constante del software y los procesos.
- **Excelencia técnica y simplicidad**: Se enfocan en mantener un desarrollo sostenible, la excelencia técnica y la simplicidad en el diseño.
- **Documentación esencial**: Priorizan el software funcionando sobre la documentación exhaustiva, produciendo solo los documentos esenciales.

---

## Metodologías Ágiles más Comunes

Las metodologías ágiles más comunes son Scrum, un marco de trabajo que se centra en la entrega rápida y continua de software funcional mediante ciclos cortos llamados Sprints, con roles y eventos definidos para la colaboración y la adaptación al cambio. Otra es Kanban, una subcategoría ágil que busca comprender el estado de un proyecto de un solo vistazo y mejorar el flujo de trabajo, eliminando desperdicios a través de tableros visuales y la limitación del trabajo en progreso. También se destaca el Design Thinking, una metodología de innovación centrada en el usuario que estructura la resolución de problemas en fases como empatizar, definir, idear, prototipar y probar, buscando soluciones creativas y validadas con los usuarios.


### 1. **SCRUM**

#### ¿Qué es SCRUM?
Scrum es un marco de trabajo ágil muy popular y ampliamente utilizado. Es un enfoque iterativo e incremental que se adapta a diferentes tipos de proyectos. Aunque es común en el desarrollo de software, también puede aplicarse a otros campos. A diferencia de metodologías rígidas, Scrum proporciona pautas flexibles que se ajustan a las necesidades específicas de cada proyecto.

#### Roles en SCRUM:

- **Product Owner (PO)**:  
Es la persona que maximiza el valor del producto y actúa como un puente vital entre los tomadores de decisiones (clientes internos o stakeholders) y el equipo de desarrollo. Su responsabilidad es filtrar todos los requerimientos del proyecto y priorizar las tareas que deben realizarse, e incluso decidir qué no se puede hacer o se pospone. No es el dueño del proyecto, sino el cuidador de las tareas y el encargado de la comunicación.

- **Scrum Master (SM)**:  
 Es un experto en Scrum cuya función es establecer y mantener el marco de trabajo Scrum en la organización, facilitando el trabajo del equipo y asegurándose de que se sigan las guías de Scrum. No es un jefe o líder de proyecto en el sentido tradicional, sino un facilitador que indica al equipo cómo trabajar y dirige las ceremonias de Scrum. Se encarga de las fechas, los objetivos y asume la responsabilidad en caso de problemas en las entregas. Su rol implica negociar los tiempos estimados por el equipo con las expectativas del cliente.

- **Equipo de Desarrollo (Development Team)**:  
Es el grupo de profesionales con todas las habilidades necesarias para crear el valor del producto. Son autoorganizados, autosuficientes y tienen la potestad de decidir qué tareas del backlog van a realizar. Dentro de este equipo se encuentran programadores backend, frontend, desarrolladores móviles, testers, entre otros. Es crucial que posean adaptabilidad al cambio y buena comunicación. 

- **Stakeholders**:  
 Son los tomadores de decisiones internos de la organización (como los equipos de contabilidad, marketing o ventas) que definen lo que el producto debe tener. También pueden ser quienes financian el proyecto y tienen poder para solicitar cambios. El Product Owner filtra sus requerimientos.

- **User**:  
Es el cliente final, la persona que utiliza el producto. Su participación, aunque en menor medida, es fundamental para validar la funcionalidad y utilidad de lo desarrollado.

#### Artefactos de Scrum: 
Scrum utiliza tres artefactos clave para gestionar el trabajo:

- **Product Backlog**: Es una lista ordenada y priorizada de todas las características, funcionalidades y requerimientos que definen el producto a desarrollar. Es un documento vivo y cambiante, adaptándose a las necesidades del proyecto. Lo define el Product Owner.

- **Sprint Backlog**: Es una selección o subconjunto de elementos del Product Backlog que el equipo se compromete a desarrollar durante un Sprint específico, junto con un objetivo y un plan para lograrlo.

- **Incremento**: Es el componente de software funcional y terminado que se produce durante un Sprint y se añade a la construcción del producto. Cada incremento debe ser usable y potencialmente liberable.

#### Eventos en SCRUM:
Scrum define una serie de eventos para estructurar el Sprint y facilitar la comunicación:

- **Sprint**: Es un período de tiempo fijo, generalmente de una a cuatro semanas (siendo una o dos lo ideal), durante el cual se desarrolla un incremento funcional del producto. El objetivo es entregar algo utilizable al final de cada Sprint 

- **Daily Scrum (Daily)**: Una reunión diaria de 15 minutos para que el equipo de desarrollo inspeccione el progreso hacia el objetivo del Sprint y adapte el Sprint Backlog según sea necesario. Se discute qué se hizo el día anterior, qué se hará hoy y si existen obstáculos. Es fundamental identificar impedimentos, pero no resolverlos durante la reunión. Puede ser presencial, remota o escrita.

- **Sprint Planning**: Es el evento con el que inicia cada Sprint, donde se establece el objetivo de esa iteración y se detalla el trabajo a realizar. El equipo de desarrollo colabora con el Product Owner para seleccionar las tareas más importantes del Product Backlog. Puede durar hasta 8 horas para un Sprint de cuatro semanas.

- **Sprint Review**: Se realiza al final del Sprint para inspeccionar el incremento desarrollado y determinar futuras adaptaciones. El equipo comparte los resultados, generalmente con el Product Owner y los stakeholders, para obtener feedback. Dura aproximadamente 4 horas para un Sprint de cuatro semanas. Aquí se validan los requerimientos y pueden surgir bugs o nuevas modificaciones.

- **Sprint Retrospective**: Un evento al final del Sprint donde el equipo reflexiona sobre el Sprint terminado y planifica mejoras en la calidad y efectividad de su trabajo y procesos. Es una reunión interna del equipo para discutir qué fue bien, qué fue mal, qué se debe empezar a hacer, qué hacer menos y qué mantener. Es el momento para que los miembros del equipo expresen sus opiniones y sugerencias de mejora de manera respetuosa. Dura aproximadamente 3 horas para un Sprint de cuatro semanas.

---

### 2. **Kanban**

#### ¿Qué es Kanban?
Kanban es una metodología ágil de gestión de proyectos que se enfoca en la mejora continua del flujo de trabajo y la eliminación de desperdicios. Fue desarrollada por Taiichi Ohno en Toyota en los años 40 para optimizar la producción y el inventario, basándose en el concepto de "justo a tiempo" (just-in-time). Su nombre significa "tarjetas visuales", lo que describe su principal herramienta: el tablero Kanban. Este tablero visualiza las tareas (representadas por tarjetas) moviéndose a través de columnas que simbolizan las etapas del proceso (ej. "Por hacer", "En curso", "Tarea completada"), permitiendo comprender el estado general del proyecto de un solo vistazo. Una característica clave es el flujo de trabajo continuo y la limitación del trabajo en progreso (WIP), lo que evita cuellos de botella y fomenta que el equipo finalice las tareas antes de comenzar otras nuevas. Kanban es flexible, no exige roles especializados fijos y puede aplicarse a cualquier proceso para aumentar la eficiencia y la claridad.

#### Principios de Kanban:
La implementación de Kanban se guía por cuatro principios fundamentales que orientan la mentalidad del equipo 


- **Empezar con lo que se hace ahora**: Se puede implementar el marco Kanban en cualquier proceso o flujo de trabajo existente sin necesidad de cambios radicales. Es lo suficientemente flexible para adaptarse a las prácticas centrales de cualquier equipo.
- **Comprometerse a buscar e implementar cambios progresivos y evolutivos:**: Fomenta la mejora continua a través de pequeños ajustes, evitando grandes transformaciones disruptivas que podrían ser perjudiciales. Los cambios graduales permiten que los procesos evolucionen con el tiempo.
- **Respetar los procesos, los roles y las responsabilidades actuales:**: A diferencia de otras metodologías, Kanban no tiene roles integrados y puede funcionar con la estructura y los procesos existentes del equipo. Se valora que los procesos actuales pueden tener elementos excelentes que no deben ser descartados.
- **Impulsar el liderazgo en todos los niveles:**: El método Kanban reconoce que el cambio y la innovación pueden provenir de cualquier miembro del equipo, no solo de la dirección. Se alienta a todos a participar, proponer nuevas formas de evolucionar los procesos y emprender nuevas iniciativas.


#### Prácticas de Kanban:
Para implementar Kanban de manera efectiva y lograr un crecimiento progresivo, se siguen seis prácticas clave:
   
1. Visualizar el trabajo: Consiste en utilizar el tablero Kanban como una herramienta visual donde las tareas se representan con tarjetas y avanzan a través de columnas que simbolizan las etapas del proceso (como "Por hacer", "En curso", "Completado"). Esto permite a todos los miembros del equipo comprender el estado del proyecto de un vistazo y facilita la identificación de cuellos de botella. Un ejemplo básico de un tablero Kanban podría ser:

| Por Hacer | En Curso | Completado |
|-----------|----------|------------|
| Tarea 1   | Tarea 4  | Tarea 7    |
| Tarea 2   | Tarea 5  | Tarea 8    |
| Tarea 3   | Tarea 6  | Tarea 9    |



También pueden existir variaciones como:

| Urgente   | Esta Semana | Próxima Semana |
|-----------|-------------|----------------|
| Bug Fix   | Feature A   | Feature B      |
| Hot Fix   | Testing     | Planning       |

O tableros de equipo con columnas de revisión:

| Desarrollo | Revisión | Producción |
|------------|----------|------------|
| Código     | QA Test  | Deploy     |
| Build      | Review   | Live       |


2. Limitar el trabajo en curso (WIP - Work In Progress): Esta práctica esencial establece un número máximo de tareas que pueden estar "en curso" en un momento dado. Su objetivo es evitar cuellos de botella, fomentar que el equipo se enfoque en finalizar las tareas individuales antes de empezar otras nuevas, y evitar la multitarea.

3. Gestionar el flujo de trabajo: Busca optimizar el movimiento de las tareas en el tablero para reducir el tiempo de entrega (el tiempo entre el inicio y la finalización de una tarea) y asegurar la relevancia del producto. Es una forma de controlar el tiempo predestinado para el trabajo.

4. Implementar políticas de procesos explícitas: Se refiere a establecer y comunicar claramente las reglas y convenciones que guían al equipo en la aplicación de Kanban. Estas políticas deben ser claras y se debe alentar a todos a participar e innovar en ellas.

5. Implementar ciclos de comentarios (feedback): Implica recopilar feedback tanto de los clientes (sobre la calidad y eficacia de la solución producida) como del equipo (sobre el proceso de ejecución del marco Kanban) para identificar áreas de mejora. Esto ayuda a adaptar la solución y a mejorar las políticas del equipo.

6. Mejorar colaborando y evolucionar experimentando: Kanban es, en esencia, una metodología de mejora continua. Por ello, fomenta la colaboración, la experimentación y la adaptación de los procesos si es necesario, incluso combinando Kanban con otras metodologías ágiles como Scrum.

#### Roles en Kanban:
Kanban no exige roles especializados fijos como Scrum, lo que le otorga mayor flexibilidad. Sin embargo, se sugieren dos roles para facilitar la gestión:

1. Service Request Manager: Este rol se encarga de establecer un número máximo de tareas que pueden estar "en curso" en un momento dado. Su objetivo es evitar cuellos de botella, fomentar que el equipo se enfoque en finalizar las tareas individuales antes de empezar otras nuevas, y evitar la multitarea.

2.  Service Delivery Manager: Supervisa la parte operacional, identifica posibles cuellos de botella, verifica el cumplimiento de los plazos de entrega, recoge métricas y valora la efectividad de la metodología. En proyectos de menor magnitud, un solo jefe de equipo puede asumir ambas funciones.



### Pasos para Implementar Kanban:
1. Establecer el flujo de trabajo: Crear un tablero Kanban y compartirlo con el equipo.
2. Definir las fases de producción: Crear columnas que representen las etapas del proceso (ej. 'Por hacer', 'En curso', 'Tarea completada').
3. Añadir las tareas: Plasmar cada tarea en una tarjeta Kanban con información relevante y moverla a través de las columnas a medida que avanza.
4. Realizar un seguimiento adecuado: Monitorear el ritmo de trabajo y reasignar tareas si es necesario, priorizando la finalización de las tareas en curso.
5. Evaluación de procesos y áreas de mejora: Al finalizar el proyecto, analizar el proceso para detectar áreas de mejora para futuras ocasiones.
Tipos de Tableros Kanban: Existen diferentes formas de organizar un tablero Kanban, como:
• Básico: Con columnas simples como 'Por hacer', 'En curso' y 'Tarea terminada'.
• Basado en el tiempo: Organiza tareas según la urgencia (ej. 'En curso', 'Para hoy', 'Para esta semana').
• De equipo: Utiliza columnas de amortiguamiento para revisiones y coordinación entre equipos. Además, pueden existir tableros específicos para áreas como ventas, desarrollo de productos o marketing.


---

# 3. El Design Thinking (DT)

El Design Thinking (DT) es una metodología ágil de innovación centrada en el usuario. Permite estructurar la manera en que comprendemos un problema y definimos la solución que debe crearse.
A continuación, se detalla la visión general del DT, sus fases, un mini-caso práctico y su relación con el ciclo de vida del desarrollo de software (SDLC) y las metodologías ágiles.

---

## 1. Visión General: Principios del DT y su Encaje en el Desarrollo de Software

### Principios Fundamentales del Design Thinking

El Design Thinking se fundamenta en varios principios clave que buscan resolver problemas complejos:

1. **Enfoque Centrado en el Humano (Usuario):** El usuario es el centro del proceso. Las decisiones que se toman siempre deben responder a sus necesidades o deseos. El objetivo es generar un impacto positivo en las personas.
2. **Generación de Innovación y Creatividad:** Se busca crear ideas que nunca antes se habían implementado. La meta no es solo responder a las necesidades, sino hacerlo de una forma que sea diferente y mejore las maneras anteriores de satisfacerlas. Esto requiere ser creativo y pensar "fuera de la caja".
3. **Proceso Iterativo y Empírico:** El DT asume que lo más probable es que nos equivoquemos a la primera. Por lo tanto, es un proceso cíclico, no lineal, que nos lleva a probar nuestras ideas e iterar rápidamente antes de llegar al desarrollo final.
4. **Colaboración:** El DT introduce equipos muy motivados y que ponen al ser humano como centro del proceso. Requiere la participación de diferentes perfiles profesionales que aportan visiones únicas y necesarias para encontrar soluciones.

### Encaje con el Desarrollo de Software

El Design Thinking es especialmente útil en el desarrollo de software porque ataca el riesgo inherente de construir la solución incorrecta.

• **Validación Temprana:** El DT permite validar las ideas con usuarios antes de invertir tiempo y dinero en el desarrollo completo.
• **Mayor Certeza:** Al iterar y probar, se obtiene mayor certeza sobre qué producto construir antes de liberar recursos para el desarrollo.
• **Viabilidad Técnica:** Durante la fase de prototipado, se aborda la viabilidad técnica y financiera del producto, lo cual es crucial antes de que el equipo de desarrollo inicie la codificación.

---

## 2. Fases del Design Thinking

El proceso de Design Thinking se compone generalmente de cinco fases fundamentales: Empatizar, Definir, Idear, Prototipar y Probar (o Validar).

**Fase**
**Objetivo Principal**
**Técnicas Sugeridas**
**Entregable(s) Mínimo(s)**

| Fase                         | Objetivo Principal                                                                                                                                                      | Técnicas Sugeridas                                                                                                                               | Entregable(s) Mínimo(s)                                                                                                                                       |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. Empatizar (Investigación) | Comprender en profundidad las necesidades, motivaciones, dolores y el entorno de los usuarios, dejando el ego de lado.                                                  | Entrevistas (uno a uno, en profundidad, incluyendo usuarios extremos), Observación de usuarios, Research etnográfico, Grupos focales, Encuestas. | Información recopilada sobre el usuario (motivaciones, contexto, dolores).                                                                                    |
| 2. Definir (Síntesis)        | Sintetizar la información para identificar el problema real y las necesidades más importantes. Delimitar el alcance y el público a solucionar.                          | Análisis de la información para comprender su viabilidad, Establecer requerimientos o limitantes (concerns), Refinar el reto inicial.            | Declaración clara del problema/insight, Reto refinado (Ej: ¿Cómo podríamos hacer para que...?), o Áreas de oportunidad.                                       |
| 3. Idear                     | Generar la mayor cantidad de ideas creativas y posibles soluciones que respondan al reto definido. Fomentar el pensamiento expansivo.                                   | Brainstorming (lluvia de ideas), SCAMPER, Preguntar por la peor idea posible, Metodología de las 10 estrellas.                                   | Conjunto de ideas creativas, de las cuales se selecciona la más valiosa basándose en valor para el usuario, facilidad de implementación e impacto de negocio. |
| 4. Prototipar                | Convertir la idea elegida en algo tangible de forma económica. Aterrizar y desarrollar la idea lo suficiente para que sea comprensible y evaluar su viabilidad técnica. | Creación de prototipos de baja fidelidad como bocetos en papel (wireframes), modelos simples o dibujos, o maquetas de cartón.                    | Prototipo de baja fidelidad que muestre la forma de la idea y sus problemas potenciales.                                                                      |
| 5. Probar (Validación)       | Validar el prototipo con usuarios reales para obtener feedback temprano, identificar mejoras o fallos y verificar si las hipótesis planteadas son ciertas.              | Pruebas de usabilidad, Testing (presencial o a distancia), Five Second Test.                                                                     | Feedback de usuario, Hipótesis validadas o descartadas. Esto conduce a la iteración del proceso.                                                              |



---

## 3. Mini-Caso de Estudio: Hash Hoteles y el "Welcome Pack" Familiar

Este ejemplo ilustra cómo se aplicaron las fases del DT para generar una solución diferenciadora en una cadena hotelera (caso hipotético).

**Problema Inicial:** Diseñar una solución para la cadena Hash Hoteles que genere una experiencia de usuario diferenciadora y fomente una relación duradera con sus clientes.

### Actividades por Fase

1. **Fase 1: Empatizar (Investigación)**

   ◦ Actividades: Se realizó un trabajo de investigación con usuarios para comprender sus necesidades y deseos en relación con la experiencia hotelera.
   ◦ Resultado: Se encontró que un deseo recurrente era "sentirse como en casa".

2. **Fase 2: Definir (Síntesis)**

   ◦ Actividades: Se analizó la información recopilada. Se identificó que para algunos usuarios, "sentirse como en casa" significaba tener la "sensación de que la familia está muy cerca".
   ◦ Reto Refinado: Se redefinió el enfoque del problema a: "¿Cómo podríamos hacer para que los usuarios de nuestros hoteles sientan a su familia muy cerca?".

3. **Fase 3: Idear**

   ◦ Actividades: Se generaron múltiples ideas para responder al reto refinado.
   ◦ Idea Seleccionada: Se eligió la idea de un "welcome pack" especial que, a diferencia de los habituales, su contenido fuera elegido por la familia de la persona que se va a hospedar.

4. **Fase 4: Prototipar (Prototipo de Baja Fidelidad)**

   ◦ Actividades: Se aterrizó la idea para hacerla tangible y comprensible. Se definieron los detalles del proceso:
   ▪ El personal del hotel se contacta con un familiar del huésped.
   ▪ El familiar sugiere qué incluir en el welcome pack.
   ▪ El personal del hotel puede comprar los ítems sugeridos o el familiar puede enviar objetos o archivos al hotel.

   ◦ Prototipo de Baja Fidelidad (Descripción Textual o Boceto):
   ▪ El prototipo inicial de baja fidelidad no sería el producto final lujoso, sino la descripción detallada del proceso logístico y la caja simple. Se utilizaría un boceto en papel o una maqueta simple de cartón para visualizar el tamaño de la caja (si es física) y la "tarjeta de bienvenida" que explique que el contenido fue personalizado por sus seres queridos. La clave de la baja fidelidad es probar la mecánica de la idea (la colaboración familiar) para validar su comprensión y viabilidad inicial.

5. **Fase 5: Probar (Validación)**

   ◦ Actividades: Se evaluó la idea del welcome pack especial con usuarios que tienen las mismas características que el grupo de diseño. Se recopiló feedback para determinar si la solución aporta valor.

   ◦ Resultado: Con el feedback se toma la decisión de iterar, simplificar la idea o transformarla, ya que el DT no debe enfocarse en la viabilidad económica en esta etapa, sino en resolver la necesidad del usuario.

---

## 4. Relación con SDLC/Ágil

El Design Thinking se articula perfectamente con el Ciclo de Vida del Desarrollo de Software (SDLC) y las metodologías ágiles como Scrum y Kanban, actuando principalmente como una fase de descubrimiento e innovación temprana.

### Cómo DT Reduce Riesgos de Construir lo Incorrecto

El Design Thinking minimiza el riesgo de construir un producto que no satisface al cliente al incorporar la validación continua y la flexibilidad en las etapas iniciales:

1. **Validación Constante vs. Waterfall:** En los modelos secuenciales tradicionales, como el de Cascada (Waterfall), la prueba y la corrección de errores ocurre al final. Si en esta etapa tardía se detectan riesgos o que los requerimientos iniciales cambiaron, esto puede generar sobrecostos y retrasos. El DT, en cambio, exige la constante validación con el usuario en cada paso y decisión, permitiendo ajustes rápidos (iteración) y minimizando los riesgos dentro del proyecto.
2. **Enfoque en el Problema Real:** El DT obliga a los equipos a dejar sus suposiciones y a enfocarse en entender el problema real del usuario. Esto evita que se construya una solución que el usuario no necesita o que no resuelve el problema subyacente.
3. **Ahorro de Inversión:** Al crear prototipos baratos y sencillos antes del desarrollo completo, el DT permite fallar de manera económica y rápida. Si la idea se descarta, se evita la inversión significativa de tiempo y recursos de los desarrolladores.

### Articulación con Scrum y Kanban

El Design Thinking (DT) se alinea con la filosofía Ágil, cuyo enfoque es la entrega rápida y continua de software funcional. Mientras que el DT se enfoca en qué construir (descubrimiento/ideación), Scrum y Kanban se enfocan en cómo construirlo (ejecución/entrega).

#### Metodología Ágil

##### Articulación con DT

**Scrum**

Scrum se centra en la entrega de software a través de ciclos cortos llamados Sprints (generalmente de 1 a 4 semanas). El DT puede alimentar la planificación de Scrum:

<ul>
<li><strong>Generación del Backlog:</strong> El Product Backlog es una lista priorizada de características del producto. Las ideas validadas y los prototipos probados generados por el DT se transforman en las historias de usuario que componen este backlog.</li>
<li><strong>Enfoque Continuo:</strong> Scrum prioriza la inspección y adaptación. El DT informa estas adaptaciones al proporcionar un mecanismo iterativo de validación con el usuario.</li>
</ul>

**Kanban**

Kanban es un marco que se enfoca en la mejora continua del flujo de trabajo mediante la visualización de tareas en un tablero.

<ul>
<li><strong>Flujo de Valor:</strong> Las ideas que provienen del DT se integran en el flujo continuo de trabajo de Kanban.</li>
<li><strong>Limitación de WIP:</strong> Kanban busca limitar el trabajo en progreso (WIP) para reducir los cuellos de botella. Al asegurar que solo se idean y se definen las soluciones con mayor certeza (gracias al DT), se garantiza que el equipo de desarrollo se centre en construir valor, sin desperdiciar esfuerzo en funcionalidades que no han sido validadas.</li>
</ul>

En resumen, el DT sienta las bases para la innovación, asegurando que la estrategia del producto esté alineada con el valor real para el usuario, y provee a los marcos de ejecución (Scrum/Kanban) las características priorizadas para su implementación ágil y continua.


