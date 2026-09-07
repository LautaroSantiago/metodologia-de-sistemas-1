# <font color="#1F6FEB">Metodología de Sistemas I</font>

Apuntes de cursada, material de clase y seguimiento del Trabajo Práctico grupal de la materia **Metodología de Sistemas I** (Tecnicatura Universitaria en Programación, UTN Facultad Regional Avellaneda). El objetivo del repositorio es centralizar lo visto en cada clase, dejar registro de las decisiones tomadas para el TP y servir de referencia rápida antes de cada entrega.

**Cursada:** 2do. cuatrimestre 2026

[![Ver en Figma](https://img.shields.io/badge/🎨_Ver_en_Figma-Pizarra_de_la_materia-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/board/25UDE2ECBBLU19Vzs7cfEb/Met-I---132?node-id=0-1&p=f)
[![Ver documento del TP](https://img.shields.io/badge/📝_Documento_del_TP-Grupo_5-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/document/d/1_fh0JCqxTOB4g7RQvXyYY3_fwekXTQJEdVI5M4X70cM/edit?tab=t.0)

---

## <font color="#8250DF">🧭 Índice</font>

- [<font color="#8250DF"><strong>Funcionamiento de la materia</strong></font>](#funcionamiento)
  - [<font color="#1A7F37">Modalidad</font>](#funcionamiento-modalidad)
  - [<font color="#1A7F37">Herramientas</font>](#funcionamiento-herramientas)
  - [<font color="#1A7F37">Etapas y entrega del TP</font>](#funcionamiento-etapas)
- [<font color="#8250DF"><strong>Clase 1 — 24/8 · Presentación de la materia y primeros conceptos</strong></font>](#clase-1)
- [<font color="#8250DF"><strong>Clase 2 — 31/8 · SMART, toma de decisiones y cronograma del TP</strong></font>](#clase-2)
- [<font color="#8250DF"><strong>Clase 3 — 7/9 · Ciclo de vida del producto, MVP y gestión de stakeholders</strong></font>](#clase-3)
- [<font color="#8250DF"><strong>Material de referencia</strong></font>](#material-de-referencia)

---

## <a id="funcionamiento"></a><font color="#8250DF">🗓️ Funcionamiento de la materia</font>

### <a id="funcionamiento-modalidad"></a><font color="#1A7F37">Modalidad</font>

- La materia no es de programación: el objetivo es **diseñar** un sistema, no construirlo. Esa parte queda para las materias de programación del resto de la carrera.
- Se busca que cada estudiante sume una experiencia real al recorrido de la carrera: haber relevado, analizado y diseñado un sistema para un cliente concreto, aunque sea de alcance chico.
- El eje del cuatrimestre es un **Trabajo Práctico grupal**: diseñar un sistema informático para optimizar un proceso real de una empresa o persona, siguiendo la metodología vista en clase (no se llega a programar, sí a dejar un diseño que facilite la programación posterior).
- **Grupos de 3 personas.** Se recomienda número impar para poder destrabar decisiones por mayoría si el grupo no se pone de acuerdo.
- **El cliente tiene que ser real**, no un caso ficticio. Debe ser alguien accesible (familiar, conocido, empleador, etc.) que pueda dedicarle tiempo real al equipo — con media hora por mes no alcanza. La interacción con ese cliente es en sí misma valiosa: ayuda a que el propio cliente termine de entender qué necesita.
- **Idea de proyecto**: tiene que ser algo chico y acotado. Se insistió en no abarcar demasiado (por ejemplo, "gestión de gimnasio" es demasiado amplio si se le suman turnos, facturación y abonos) para poder concentrarse en aplicar bien las técnicas de la materia sin perderse en el tamaño del problema.
- Cada clase se toma asistencia y se dedican un par de minutos a una dinámica de feedback tipo retro (qué gustó, qué no, y propuestas de mejora), para poder ajustar la cursada sobre la marcha y no recién al final del cuatrimestre.

### <a id="funcionamiento-herramientas"></a><font color="#1A7F37">Herramientas</font>

`Figma` · `GitHub Projects` · `Google Docs`

- **Figma** — pizarrón virtual compartido para dinámicas de grupo, brainstorming y diagramas en clase (botón de acceso arriba, en el encabezado del repo).
- **GitHub Projects** — planificación y seguimiento de tareas del TP (tablero tipo Kanban):
  - Columnas: *To Do* → *In Progress* → *Resol* (a revisión) → *Done*. Si una tarea entregada no está a la altura, vuelve a *In Progress* con comentarios.
  - Cada tarea (issue) lleva un **label con el número de grupo**, imprescindible para que después funcionen los filtros por grupo.
  - Cada tarea tiene **un único responsable asignado** (ni todos, ni nadie).
  - Se arman **vistas filtradas por grupo** para que cada equipo gestione solo lo suyo.
- **Google Docs** — documentación del TP centralizada en un documento de solo lectura, donde se va agregando todo lo producido durante la cursada (botón de acceso arriba, en el encabezado del repo).

### <a id="funcionamiento-etapas"></a><font color="#1A7F37">Etapas y entrega del TP</font>

<details>
<summary><font color="#1A7F37">Prototipo inicial</font></summary>

**Se entrega:** conjunto de pantallas que reflejen la información a procesar — puede hacerse con Figma, HTML directo o incluso con herramientas de IA generativa; no se pide programar, solo mostrarle al cliente la parte visual del sistema.
**Fecha confirmada:** 7/9.

Se resuelve aplicando **Design Thinking**, en sus 5 etapas: Empatizar → Definir → Idear → Prototipar → Evaluar (las dos primeras y las dos últimas son de pensamiento convergente; Idear es la etapa divergente, de generación de opciones).

⭐ **Lo que el material marca como importante:** al diseñar algo nuevo, el principal riesgo a evitar es *construir algo que nadie quiere o usa*. Por eso todo el proceso arranca en **Empatizar** — entender necesidades y motivaciones reales del cliente (mapa de actores, mapa de empatía) — antes de pasar a idear o prototipar soluciones.

</details>

<details>
<summary><font color="#1A7F37">Análisis</font></summary>

**Se entrega:** listado de requerimientos funcionales y no funcionales, vinculado a las interfaces de usuario diseñadas en el prototipo.
**Fecha confirmada:** 21/9.

⭐ Esta entrega se apoya directamente en el material de **Unidad 2** (ver [Material de referencia](#material-de-referencia)): la definición de requerimiento funcional (comportamiento del sistema ante un evento) vs. no funcional (performance, seguridad, tecnología, legales, documentación), y las herramientas para comunicarlos (casos de uso UML o historias de usuario).

</details>

<details>
<summary><font color="#1A7F37">Diseño</font></summary>

**Se entrega:** detalle de casos de uso, modelo de clases y modelo de datos.
**Fecha confirmada:** 12/10.

⭐ El formato de caso de uso que pide esta entrega (título descriptivo, actor, escenario) y su notación UML (asociación, extends, include, límite del sistema) están detallados en el material de **Unidad 2**.

</details>

<details>
<summary><font color="#1A7F37">Desarrollo</font></summary>

**Se entrega:** detalle de las formas de trabajo grupal y su documentación (buenas prácticas de desarrollo).
**Fecha confirmada:** 19/10.

</details>

<details>
<summary><font color="#1A7F37">Pruebas</font></summary>

**Se entrega:** diseño de pruebas unitarias, funcionales, de regresión y de performance.
**Fecha confirmada:** 9/11.

</details>

<details>
<summary><font color="#1A7F37">Implementación</font></summary>

**Se entrega:** configuración de ambientes (usuarios, recursos, seguridad y variables).
**Fecha confirmada:** 23/11.

</details>

**Corrección:** las entregas se revisan en el tablero de GitHub Projects. Una tarea pasa de *In Progress* a *Resol* cuando el grupo la da por terminada; si queda bien resuelta pasa a *Done*, y si no, vuelve a *In Progress* con comentarios para corregir. Además, llegar tarde a una entrega no solo penaliza esa nota puntual: baja el techo máximo alcanzable en las entregas siguientes, aunque el contenido de esas próximas esté perfecto.

---

## <font color="#8250DF">📅 Cronograma de clases</font>

Cada clase se despliega individualmente con su desarrollo completo adentro. Se va actualizando a medida que avanza la cursada.

<details>
<summary><a id="clase-1"></a><font color="#1A7F37"><strong>Clase 1 — 24/8 · Presentación de la materia y primeros conceptos</strong></font></summary>

### Temas vistos

- El Trabajo Práctico: grupos, cliente real, documentación y gestión con GitHub Projects
- Ideas de proyecto (brainstorming) y candidatas propias del grupo
- Diferencia de expectativas entre lo que se pide y lo que se entiende
- Tipos de contratación: locación de servicio vs. locación de obra
- Alcance (límite) de un sistema
- Objetivos de corto, mediano y largo plazo

#### El Trabajo Práctico (TP)

**Consigna general:** diseñar un sistema informático para optimizar un proceso real de una empresa o persona, siguiendo la metodología vista en clase.

- **Documentación**: se centraliza en un Google Docs de solo lectura, donde se va agregando todo lo producido durante la cursada.
- **Gestión de tareas con GitHub Projects**: tablero Kanban con label por grupo, responsable único por tarea y vistas filtradas.

#### 💡 Ideas de proyecto (brainstorming — a desarrollar)

Lluvia de ideas propuesta en clase como punto de partida para elegir el proyecto de cada grupo. Son ideas abiertas, no compromisos definitivos:

- Gestión de gimnasio (rutinas personalizadas, seguimiento por alumno)
- Sistema de seguimiento de encomiendas
- Sistema de inventario / stock para una papelera
- Gestión de ventas digitales (fotografía de eventos deportivos)
- Sistema de pedidos de cafetería
- Sistema de notas para una institución secundaria
- Sistema de turnos (peluquería, consultorio médico, actividades deportivas)
- Mantenimiento de senderos de un parque nacional
- BackOffice / gestión de stock
- Venta de entradas
- E-commerce de accesorios para mascotas

#### 🎯 Candidatas propias (Grupo 5)

De esa lluvia de ideas, las que quedaron como candidatas concretas para el proyecto del equipo:

1. **BackOffice — Gestión de stock**
2. **Sistema de venta de entradas** (estilo passline)
3. **Gestión de turnos** en peluquería / consultorio médico particular
4. **Sistema de gestión para e-commerce de accesorios de mascotas**

Info útil de la clase para arrancar el desarrollo, aplicable a estas cuatro:

- **La idea de "turnos" fue avalada explícitamente en clase**: se marcó como un clásico pero todavía muy necesario, porque hay mucha gente que no tiene sistema de turnos — y se dio de ejemplo justamente una peluquería. Es un buen indicio de que el problema es real y acotado.
- **Punto de partida metodológico para cualquiera de las cuatro** (mismo camino que se usó en clase con el sistema de ventas de ejemplo):
  1. Identificar la **entrada / activador** del sistema: qué evento dispara todo (un pedido de stock que ingresa, una compra de entrada, un turno solicitado, una venta en el e-commerce).
  2. Definir la **salida esperada**: qué se considera resuelto (stock actualizado, entrada emitida, turno confirmado, pedido despachado).
  3. Recién ahí desglosar los **elementos internos** (los pasos/subsistemas que conectan la entrada con la salida) y armar el **happy path**.
  4. Cerrar con el **alcance/límite**: dejar explícito qué queda afuera (cobros, logística, reposición de stock, etc., según corresponda a cada idea) para evitar diferencias de expectativas con el cliente.
- **Antes de elegir una definitiva**, confirmar que haya un **cliente real y accesible** que pueda dedicarle tiempo al equipo — el requisito no negociable del TP, ya sea para la peluquería/consultorio o para el negocio de stock, entradas o e-commerce de mascotas.
- **Mantenerla acotada**: mismo criterio que se remarcó con "gestión de gimnasio" — elegir una sola de estas cuatro y no ir sumándole funcionalidades de las otras tres a medida que avanza el diseño.
- **Ojo con que "turnos" quede demasiado chico**: en la clase 2, al revisar en vivo la idea de otro grupo para una peluquería/estética, se marcó que un negocio que es puramente de turnos ("turnario y listo") puede quedarse corto de contenido para el TP, porque no suma control de stock ni maneja presupuestos — es un servicio sin producto de por medio. Si se elige esta candidata, conviene explorar si hay algo más para modelar (por ejemplo, gestión de insumos del local) antes de darla por buena.

#### Diferencia de expectativas

Uno de los ejes centrales de la clase: cuando alguien pide algo, tiene en la cabeza un resultado esperado que **no siempre coincide** con lo que la otra persona entiende o entrega. Esa brecha es la fuente más común de conflictos entre cliente y proveedor.

- Se ilustró con ejemplos cotidianos (una tarea doméstica mal especificada, un pedido en un local de comida rápida que no coincide con la publicidad, reclamos de clientes por el resultado de un trabajo) y con una escena de película donde un jefe corrige a un empleado sin explicitar nunca el estándar que esperaba, generando desgaste innecesario.
- **Conclusión útil para el TP:** no asumir que el cliente sabe explicar lo que necesita ni que uno entiende automáticamente lo que pide. Hay que preguntar, confirmar y dejar explícito el alcance para minimizar diferencias de expectativas.

#### Tipos de contratación: Locación de servicio vs. Locación de obra

Dos formas de encuadrar la relación con un cliente, con implicancias distintas para el diseño del TP:

| | Locación de **servicio** | Locación de **obra** |
|---|---|---|
| Qué se vende | Horas / tiempo de trabajo | Un producto o resultado terminado |
| Ejemplo | Una consultora que factura desarrolladores por hora | Comprometerse a entregar un sistema funcionando |
| Riesgo típico | El cliente paga aunque el alcance crezca | El proveedor absorbe el costo si el alcance crece sin renegociar (*scope creep*) |

Se representó con un ejemplo dialogado (roleplay) donde un cliente va agregando pedidos sobre la marcha (una rutina personalizada, después falta esto, después falta el botoncito, después un reporte estadístico) y el proveedor termina entregando mucho más de lo pactado originalmente sin cobrar de más — ejemplo directo de scope creep en locación de obra.

- **Conclusión útil para el TP:** en locación de obra, el proveedor es quien más necesita preguntar y dejar todo por escrito antes de arrancar, porque cualquier cosa no explicitada corre por su cuenta. En locación de servicio el riesgo de sobrecosto lo asume más el cliente, así que es este quien debería preguntar más para no pagar de más.

#### Alcance (límite) de un sistema

Se trabajó en vivo el diseño de un sistema de ventas de ejemplo, partiendo de un diagrama con los elementos: *recibir pedido → seleccionar forma de pago → cobrar (tarjeta) → preparar pedido → enviar mercadería*, con la pregunta "¿hay stock?" como bifurcación.

- **Elementos**: cada bloque o subsistema que compone el sistema (recibir pedido, cobrar, preparar pedido, etc.).
- **Relaciones**: las flechas/interacciones entre esos elementos.
- **Objetivo**: en el ejemplo, entregar la mercadería pedida por el cliente.
- **Happy path**: el camino donde todo sale bien y se cumple el objetivo sin interrupciones. El camino no feliz (no hay stock, falla el cobro, etc.) también hay que contemplarlo, pero se distingue del camino ideal.
- **Límite / alcance**: definir explícitamente qué **no** hace el sistema. En el ejemplo se discutió si estaban dentro o fuera del alcance la logística de envío, la reposición de stock, la gestión del circuito de devoluciones y el pago de sueldos del personal — se concluyó que, salvo la logística en sí, varias de esas dudas dependen del criterio de cada equipo y conviene dejarlas explícitas para evitar ambigüedad.

> **Idea clave repetida en clase:** si el límite de lo que uno se compromete a hacer no queda claro, se generan diferencias de expectativas → conflictos → pérdida de tiempo, dinero o clientes. Definir el alcance es una de las partes más importantes de la primera etapa del TP.

#### Objetivos de corto, mediano y largo plazo

Se planteó un ejercicio (ejemplo cotidiano: sacar la basura) para mostrar cómo toda tarea puntual está enmarcada dentro de objetivos de distinto horizonte temporal, y que conviene pensarlos **de atrás para adelante** (ingeniería inversa): primero se define el objetivo de largo plazo, después el de mediano plazo que lo sostiene, y recién ahí se entiende por qué la acción de corto plazo importa.

- Ejemplo armado en clase: sacar la basura a horario (**corto**) → evitar multas y gastos superfluos (**mediano**) → ahorrar para un objetivo mayor, como comprar un auto (**largo**).
- **Conclusión útil para el TP:** las mismas preguntas hay que hacérselas al cliente. Si dice "quiero vender más", conviene preguntar en qué plazo y con qué objetivo mayor se relaciona esa necesidad — eso ayuda a entender el contexto y tomar mejores decisiones sobre cómo priorizar cada tarea puntual.

### Material de la clase

Repaso en base a **Unidad 1** — ver detalle y descarga en [Material de referencia](#material-de-referencia).

</details>

<details>
<summary><a id="clase-2"></a><font color="#1A7F37"><strong>Clase 2 — 31/8 · SMART, toma de decisiones y cronograma del TP</strong></font></summary>

### Temas vistos

- Repaso de la teoría de proyectos (ciclo de vida de producto, atributos de un sistema) vista la clase anterior
- Objetivos SMART: qué significa cada letra y cómo aplicarlo a un objetivo de proyecto
- Toma de decisiones dentro de un proceso: cómo se apoya en datos e información
- Fechas oficiales confirmadas del cronograma del TP
- Aclaración sobre qué implica la entrega del "Prototipo inicial"
- Trabajo en salas por grupo, con revisión en vivo de un objetivo SMART de cada equipo

#### Objetivos SMART

Repaso en profundidad del acrónimo que ya había aparecido en el material de "Proyectos, Procesos, Productos, Personas": todo objetivo de proyecto tiene que ser **S**pecific (específico), **M**easurable (medible), **A**chievable (alcanzable), **R**elevant (relevante) y **T**ime-bound (con tiempo definido).

- **Specific / Measurable:** se trabajó armando objetivos en clase a partir de frases vagas. Ejemplo: "mejorar tiempos de producción" (ligado a la idea de venta de fotos de eventos deportivos) no dice nada por sí solo — hay que precisar de qué proceso puntual se habla (por ejemplo, el tiempo que tarda un cliente en seleccionar sus fotos, no todo el circuito de venta) y con qué número se lo mide (ej.: "mejorar los tiempos de selección de imágenes en un 30%, en 6 meses, con una aplicación web").
- **Achievable:** a diferencia de una tarea repetida muchas veces (donde ya hay una marca personal de referencia), un proyecto es algo nuevo y no hay forma de estar 100% seguro de que algo es alcanzable antes de hacerlo. Lo que se puede hacer es estimar en base al tiempo real disponible — por ejemplo, la carga horaria de la materia (unas pocas horas por semana) marca un techo realista de dedicación, no ocho horas por día.
- **Relevant:** un objetivo tiene que estar conectado a algo que le importe a quien lo pide. Se usó el ejemplo de "mejorar la condición física" — solo cobra sentido si se conecta con un motivo concreto (una competencia, poder hacer determinada actividad), no como fin en sí mismo.
- **Time-bound:** tiene que tener una fecha límite. Se usó como ejemplo el propio TP: sin una fecha de entrega, "aprobar la materia" no sería time-bound.
- **Conclusión útil para el TP:** cuanto más ambiguo queda un objetivo, más lugar hay para que cada uno lo entienda distinto — y esa ambigüedad es la que después genera conflictos de expectativas con el cliente (mismo tema que ya había aparecido en la clase 1).

#### Toma de decisiones y datos

- Se retomó la relación entre dato e información (ya vista en la Teoría General de los Sistemas): una decisión solo puede tomarse bien si el sistema cuenta con los datos necesarios; si falta algo, la decisión termina siendo intuición y no una decisión informada.
- Ejemplo de clase: para decidir "qué ropa ponerse" hace falta información concreta (clima, agenda del día, código de vestimenta si corresponde) — y esa información tiene que estar completa y detallada. Un sistema no puede apoyarse en un "etcétera": si un dato no está identificado explícitamente, el sistema no lo va a tener disponible para decidir.
- Aplicado a un sistema de pedidos: una decisión típica es si mandar o no un recordatorio por email a un cliente, en función del estado en que quedó su pedido (por ejemplo, si la selección de imágenes quedó en borrador). Ese tipo de reglas de decisión conviene dejarlas escritas, no solo pensadas.
- **Conclusión útil para el TP:** al relevar el proceso del cliente, conviene identificar los puntos donde el sistema tiene que decidir algo, y para cada uno preguntar qué información hace falta para decidir bien — sin dejar nada bajo un "etcétera".

#### Fechas oficiales del cronograma del TP

Se confirmaron las fechas reales de entrega para esta cursada (ya actualizadas en la sección [Etapas y entrega del TP](#funcionamiento-etapas) del índice). También se aclaró cómo funciona la penalización: si un grupo entrega tarde, no solo se resiente la nota de esa entrega puntual — el atraso baja el techo máximo de nota que ese grupo puede alcanzar en las entregas siguientes, aunque después presenten todo perfecto.

#### Aclaración sobre el "Prototipo inicial"

Surgió la duda de si la primera entrega implicaba programar (por ejemplo, en JavaScript). Se aclaró que no: el "prototipo inicial" se refiere a mostrarle al cliente la parte visual del sistema, del mismo modo que se hace en desarrollo web antes de programar. Se puede resolver con Figma, con HTML directo (sin lógica de programación), o incluso con herramientas de generación de interfaces por IA — lo que importa es tener pantallas para mostrar, no código funcionando.

- **Conclusión útil para el TP:** no hace falta saber programar para esta primera entrega. Alcanza con maquetar las pantallas que reflejen el proceso que se va a resolver.

#### Feedback general sobre el armado de los objetivos

Al revisar en vivo los objetivos que armó cada grupo, se remarcaron dos criterios que aplican a cualquier proyecto (incluido el de este equipo):

- **Evitar títulos demasiado abarcativos.** Un nombre de proyecto muy general (por ejemplo, algo tipo "centralizar información de socios") deja lugar a interpretaciones distintas — conviene ser específico desde el título para evitar zonas grises.
- **No perder tiempo diseñando pantallas estándar.** Todo sistema va a tener registro, login y asignación de permisos por rol — son pantallas que no aportan valor diferencial al proyecto, así que no hace falta detenerse en su diseño.

### Material de la clase

Profundización sobre **Unidad 1**, sin material nuevo — ver [Material de referencia](#material-de-referencia).

</details>

<details>
<summary><a id="clase-3"></a><font color="#1A7F37"><strong>Clase 3 — 7/9 · Ciclo de vida del producto, MVP y gestión de stakeholders</strong></font></summary>

### Temas vistos

- Repaso rápido de proyectos: objetivo, alcance, restricciones
- Ciclo de vida del producto aplicado paso a paso, con foco en la etapa de Introducción
- Diferencia entre prototipo y MVP (producto mínimo viable)
- Fidelidad de prototipos: baja fidelidad (wireframes) vs. alta fidelidad
- Planeamiento estratégico: gestión de riesgos y gestión de stakeholders
- Marco Cynefin aplicado para elegir entre metodología en cascada o iterativa/incremental
- Ambigüedad del lenguaje entre cliente y proveedor (mismo tema que diferencia de expectativas)
- Priorización de iteraciones según riesgo y complejidad

#### Ciclo de vida del producto, en profundidad

Se retomó el ciclo de vida del producto (Introducción → Crecimiento → Madurez → Declive) y se abrió la etapa de **Introducción** en sus sub-etapas: Ideación → Validación → Planeamiento → Construcción → Lanzamiento. La etapa de Introducción termina justo cuando se lanza el **MVP**; de ahí en adelante el producto entra en Crecimiento (más funcionalidades, corrección de errores, ya se piensa en la segunda versión).

- **Ideación y Validación** se resuelven con **Design Thinking** (Empatizar → Definir → Idear → Prototipar → Evaluar), que termina en un **prototipo validado**.
- **Planeamiento** se resuelve con técnicas de planeamiento estratégico (se vieron solo de forma introductoria): análisis de mercado, prueba de concepto, gestión de riesgos, selección del MVP y gestión de stakeholders.
- **Construcción** se resuelve con el ciclo de vida del desarrollo de software (análisis → diseño → codificación → pruebas → implementación), en cascada o iterativo según el caso.

⭐ **El prototipo validado que resulta de Design Thinking hay que incorporarlo al documento del TP.**

#### Prototipo vs. MVP

- **Prototipo**: versión reducida y mínima que solo busca mostrar el valor central de la solución, para validarla con el cliente antes de invertir en construirla en serio. Puede ser de **baja fidelidad** (wireframes, cuadraditos sin texto ni color, rápido de hacer) o de **alta fidelidad** (pantallas con colores, textos y navegación simulada).
- **MVP (Minimum Viable Product)**: versión mínima pero real del producto, lista para salir al mercado. Para pasar de un prototipo validado a un MVP hace falta sumarle piezas que el prototipo no necesitaba (ejemplo dado en clase: login, segundo factor de autenticación, algún reporte) — son requisitos para que el producto pueda sostenerse en producción, no para demostrar la idea.
- **Conclusión útil para el TP:** el "Prototipo inicial" que pide la guía del TP se queda en la etapa de prototipo — no hace falta llegar a nivel MVP para esa entrega.

#### Gestión de riesgos

- Se trabajó con una matriz de **probabilidad de ocurrencia** vs. **impacto** para ubicar los riesgos de un proyecto (ejemplo extremo usado en clase: la caída de un meteorito sobre la base de datos — probabilidad bajísima, pero impacto muy alto si no hay backup).
- El impacto de un riesgo depende del **FODA** propio de cada proyecto: si la base de datos ya está descentralizada, ese mismo riesgo pesa menos que si está centralizada.
- Aplicado a decisiones técnicas: la tolerancia a estar offline (por ejemplo, 10 minutos) determina qué mitigación conviene — desde un backup simple hasta un esquema de redundancia con failover automático, que cuesta más pero da mayor disponibilidad.

#### Marco Cynefin aplicado: cómo elegir la metodología

Se retomó el Marco Cynefin (Simple / Complicado / Complejo / Caótico / Desorden) para decidir entre desarrollo en **cascada** o **iterativo e incremental**:

- **Simple o Complicado** (ya se hizo muchas veces, hay expertos, se conocen los riesgos — ejemplo: construir una casa) → conviene **cascada**: plan secuencial, más eficiente en costos porque cada especialista entra en su etapa sin necesidad de supervisión extra.
- **Complejo** (no hay experiencia previa, se interactúa con componentes desconocidos — ejemplo: una app de fitness que usa acelerómetro y cámara sin haber trabajado antes con esos sensores) → conviene **iterativo e incremental**: ir paso a paso (conectar cámara → primera iteración, conectar acelerómetro → segunda iteración, etc.), aprendiendo en cada entrega.
- **Conclusión útil para el TP:** conviene evaluar con qué parte del proyecto el equipo tiene menos experiencia, y a esa tratarla como "compleja" (resolverla de a poco, en iteraciones chicas) en vez de plantearla toda de una.

#### Gestión de stakeholders

- **Stakeholders** = interesados en el proyecto. Además del propio equipo, hay que identificar al menos: **cliente** (quien decide y paga, o autoriza la compra), **sponsor** (quien pone la plata, puede no ser la misma persona que el cliente) y **usuario** (quien va a usar el sistema, puede ser interno o externo — ejemplo dado: en una app de tipo Uber/Cabify, el conductor es un usuario interno del lado operativo y el pasajero es un usuario externo).
- Se usa una matriz de **interés vs. influencia** para ubicar a cada stakeholder y decidir cómo gestionarlo.
- **Resistencia al cambio:** en general, un usuario que ya tiene una forma de hacer las cosas (limpiar, estudiar, usar una pantalla) no tiene interés espontáneo en que se la cambien, aunque tenga mucha influencia sobre si el proyecto se adopta o no — salvo que lo actual esté funcionando muy mal.

#### Ambigüedad del lenguaje (ejemplo del "amigo")

Se retomó la diferencia de expectativas (vista en la Clase 1) con un ejemplo del propio grupo: la palabra "amigo" significa cosas distintas para cada persona. Si esa ambigüedad aparece en una conversación con el cliente, cada uno interpreta un compromiso distinto — un cliente puede esperar que el sistema haga diez cosas mientras el equipo cotizó pensando en dos, y ese desajuste sale caro recién cuando ya se cerró el trato.

- **Conclusión útil para el TP:** las palabras clave de la conversación con el cliente conviene chequearlas explícitamente, no darlas por entendidas.

#### Mapa de causa raíz (los "por qué")

Herramienta para no quedarse en el síntoma que pide el cliente. Ejemplo usado en clase: si alguien dice "me duele el zapato, comprame otro zapato" sin indagar más, comprar otro zapato del mismo tipo no resuelve nada — el problema real puede ser otro (por ejemplo, un pie con una forma particular que necesita un zapato a medida). Preguntar "por qué" varias veces seguidas ayuda a llegar a la causa real, aunque haya que hacerlo con cuidado para que no se sienta como un interrogatorio.

⭐ **El mapa de causa raíz es la herramienta puntual que hay que incluir en el documento del TP**, dentro de la etapa "Definir" de Design Thinking.

### Material de la clase

Contenido de **Unidad 2** (ciclo de vida del producto, pensamiento de diseño, Marco Cynefin):

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Unidad_2_(parte_1)-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%202/02%20-%20MetSis_I_U2_1.pdf)
[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Unidad_2_(parte_2)-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%202/02%20-%20MetSis_I_U2_2.pdf)

Con un breve repaso de **Unidad 1** (objetivo, alcance y restricciones de un proyecto):

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Proyectos%2C_Procesos%2C_Productos%2C_Personas-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%201/01%20-%20Proyectos%2C%20Procesos%2C%20Productos%2C%20Personas.pptx.pdf)

</details>

---

## <a id="material-de-referencia"></a><font color="#8250DF">📎 Material de referencia</font>


### Generales

[![Ver PDF](https://img.shields.io/badge/📄_Guía_TP_grupal-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/00%20-%20Guria%20TP%20grupal.pdf)
[![Ver PDF](https://img.shields.io/badge/📄_Planificación_de_la_materia-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/Planificaci%C3%B3n%20Metodolog%C3%ADa%20de%20Sistemas%20I.pdf)

La guía detalla el objetivo, la metodología y las etapas del TP grupal (ver resumen en [Etapas y entrega del TP](#funcionamiento-etapas)).

### UNIDAD 1

Base teórica usada en las clases 1 y 2.

**Teoría General de los Sistemas** — concepto de sistema (conjunto de elementos interrelacionados que trabajan para un objetivo; ejemplos citados: un ecosistema, una organización, un tren de carga, el cuerpo humano), atributos (elementos, relaciones, objetivo, límite), clasificaciones (abiertos/cerrados/aislados, naturales/artificiales, concretos/abstractos, estáticos/dinámicos, simples/complejos), cualidades (entropía, homeostasis, sinergia, retroalimentación positiva/negativa, equifinalidad, permeabilidad, adaptabilidad, emergencia), dato vs. información, y sistema de información (captura → procesamiento → almacenamiento → distribución).

⭐ El material remarca los **requisitos de la información eficiente** — exactitud, relevancia, oportunidad, integridad, claridad, consistencia, accesibilidad y confiabilidad — con un ejemplo por requisito (ej.: relevancia = un examen de sangre sirve para el diagnóstico puntual que se pide, no para cualquier otro).

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Teor%C3%ADa_General_de_los_Sistemas-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%201/02%20-%20Teor%C3%ADa%20General%20de%20los%20Sistemas.pptx.pdf)

**Proyectos, Procesos, Productos, Personas** (las 4 P del desarrollo de software) — proyectos (objetivo SMART, alcance, restricciones, recursos; ciclo de vida: iniciación → planificación → ejecución → monitoreo y control → cierre), procesos (gestión de proyectos como Scrum/PMBOK vs. técnicos como Agile/Waterfall), productos (funcionalidad, calidad, mantenibilidad; ciclo de vida: concepción → desarrollo → implementación → mantenimiento → retirada) y personas (roles: desarrolladores, analistas, testers, gestores de proyecto; factores clave: competencia, colaboración, cultura organizacional).

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Proyectos%2C_Procesos%2C_Productos%2C_Personas-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%201/01%20-%20Proyectos%2C%20Procesos%2C%20Productos%2C%20Personas.pptx.pdf)

### UNIDAD 2

Desarrollada parcialmente en la Clase 3 (ciclo de vida del producto, pensamiento de diseño, Marco Cynefin). Cubre además: **enfoques de gestión de proyectos** (Predictivo, Ágil e Híbrido) y la mentalidad ágil (co-creación de valor, aceptar la incertidumbre); **ciclo de vida del desarrollo de software** en cascada vs. iterativo e incremental (análisis → diseño → codificación → pruebas → implementación); **requerimientos funcionales** (comportamiento esperado del sistema) vs. **no funcionales** (performance, seguridad, tecnología, legales, documentación); **UML: casos de uso** (título, actor, escenario); y **documentación en agilidad** (épicas → features → historias de usuario, con criterio "Como \[usuario], quiero \[algo], para \[objetivo]" y sus criterios de aceptación) — estos últimos puntos, aún no vistos en clase.

⭐ Directamente relacionado con las entregas de **Análisis** y **Diseño** del TP — ver notas en [Etapas y entrega del TP](#funcionamiento-etapas).

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Unidad_2_(parte_1)-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%202/02%20-%20MetSis_I_U2_1.pdf)
[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Unidad_2_(parte_2)-0A66C2?style=for-the-badge)](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/LautaroSantiago/metodologia-de-sistemas-1/master/Material/UNIDAD%202/02%20-%20MetSis_I_U2_2.pdf)

### UNIDAD 3

Todavía sin material cargado.

---

## <font color="#8250DF">🗂️ Estructura del repositorio</font>

```
Metodología de Sistemas I
├── Material
│   ├── 00 - Guria TP grupal.pdf
│   ├── Planificación Metodología de Sistemas I.pdf
│   ├── UNIDAD 1
│   │   ├── 01 - Proyectos, Procesos, Productos, Personas.pptx.pdf
│   │   └── 02 - Teoría General de los Sistemas.pptx.pdf
│   ├── UNIDAD 2
│   │   ├── 02 - MetSis_I_U2_1.pdf
│   │   └── 02 - MetSis_I_U2_2.pdf
│   └── UNIDAD 3
└── Readme.md
```
