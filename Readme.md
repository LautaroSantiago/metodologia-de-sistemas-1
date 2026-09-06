# <font color="#1F6FEB">Metodología de Sistemas I</font>

Apuntes de cursada, material de clase y seguimiento del Trabajo Práctico grupal de la materia **Metodología de Sistemas I** (Tecnicatura Universitaria en Programación, UTN Facultad Regional Avellaneda). El objetivo del repositorio es centralizar lo visto en cada clase, dejar registro de las decisiones tomadas para el TP y servir de referencia rápida antes de cada entrega.

**Cursada:** 2do. cuatrimestre 2026

---

## <font color="#8250DF">🧭 Índice</font>

- [<font color="#8250DF"><strong>Funcionamiento de la materia</strong></font>](#funcionamiento)
  - [<font color="#1A7F37">Modalidad</font>](#funcionamiento-modalidad)
  - [<font color="#1A7F37">Herramientas</font>](#funcionamiento-herramientas)
  - [<font color="#1A7F37">Etapas y entrega del TP</font>](#funcionamiento-etapas)
- [<font color="#8250DF"><strong>Clase 1 — 24/8 · Presentación de la materia y primeros conceptos</strong></font>](#clase-1)

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

- **Figma** — pizarrón virtual compartido para dinámicas de grupo, brainstorming y diagramas en clase.
- **GitHub Projects** — planificación y seguimiento de tareas del TP (tablero tipo Kanban):
  - Columnas: *To Do* → *In Progress* → *Resol* (a revisión) → *Done*. Si una tarea entregada no está a la altura, vuelve a *In Progress* con comentarios.
  - Cada tarea (issue) lleva un **label con el número de grupo**, imprescindible para que después funcionen los filtros por grupo.
  - Cada tarea tiene **un único responsable asignado** (ni todos, ni nadie).
  - Se arman **vistas filtradas por grupo** para que cada equipo gestione solo lo suyo.
- **Google Docs** — documentación del TP centralizada en un documento de solo lectura, donde se va agregando todo lo producido durante la cursada.

### <a id="funcionamiento-etapas"></a><font color="#1A7F37">Etapas y entrega del TP</font>

<details>
<summary><font color="#1A7F37">Prototipo inicial</font></summary>

**Se entrega:** conjunto de pantallas (HTML/JS) con datos estáticos que reflejen la información a procesar, resultado de aplicar Design Thinking sobre el proceso elegido.
**Fecha confirmada:** 31/08.

</details>

<details>
<summary><font color="#1A7F37">Análisis</font></summary>

**Se entrega:** listado de requerimientos funcionales y no funcionales, vinculado a las interfaces de usuario diseñadas en el prototipo.
**Fecha:** 4/5 según la plantilla de cátedra — a confirmar para esta cursada.

</details>

<details>
<summary><font color="#1A7F37">Diseño</font></summary>

**Se entrega:** detalle de casos de uso, modelo de clases y modelo de datos.
**Fecha:** 18/5 según la plantilla de cátedra — a confirmar para esta cursada.

</details>

<details>
<summary><font color="#1A7F37">Desarrollo</font></summary>

**Se entrega:** detalle de las formas de trabajo grupal y su documentación (buenas prácticas de desarrollo).
**Fecha:** 1/6 según la plantilla de cátedra — a confirmar para esta cursada.

</details>

<details>
<summary><font color="#1A7F37">Pruebas</font></summary>

**Se entrega:** diseño de pruebas unitarias, funcionales, de regresión y de performance.
**Fecha:** 1/6 según la plantilla de cátedra — a confirmar para esta cursada.

</details>

<details>
<summary><font color="#1A7F37">Implementación</font></summary>

**Se entrega:** configuración de ambientes (usuarios, recursos, seguridad y variables).
**Fecha:** 22/6 según la plantilla de cátedra — a confirmar para esta cursada.

</details>

**Corrección:** las entregas se revisan en el tablero de GitHub Projects. Una tarea pasa de *In Progress* a *Resol* cuando el grupo la da por terminada; si queda bien resuelta pasa a *Done*, y si no, vuelve a *In Progress* con comentarios para corregir.

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

**Teoría General de los Sistemas** — base teórica usada en clase para analizar el ejemplo del sistema de ventas: concepto de sistema, atributos (elementos, relaciones, objetivo, límite), clasificaciones, cualidades (entropía, homeostasis, sinergia, retroalimentación, equifinalidad), dato vs. información, y sistema de información (captura → procesamiento → almacenamiento → distribución).

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Teor%C3%ADa_General_de_los_Sistemas-0A66C2?style=for-the-badge)](./Material/2-TeoríaGeneraldelosSistemas.pdf)

**Proyectos, Procesos, Productos, Personas** (las 4 P del desarrollo de software) — no se llegó a desarrollar en profundidad en esta clase, queda como referencia: proyectos (objetivo SMART, ciclo de vida), procesos (Scrum, PMBOK, Agile, Waterfall), productos (ciclo de vida) y personas (roles, competencia, colaboración).

[![Ver PDF](https://img.shields.io/badge/📄_Ver_PDF-Proyectos%2C_Procesos%2C_Productos%2C_Personas-0A66C2?style=for-the-badge)](./Material/1-ProyectosProcesosProductosPersonas.pdf)

</details>

---

## <font color="#8250DF">🗂️ Estructura del repositorio</font>

```
Metodología de Sistemas I
├── Material
│   ├── 1-ProyectosProcesosProductosPersonas.pdf
│   └── 2-TeoríaGeneraldelosSistemas.pdf
└── Readme.md
```
