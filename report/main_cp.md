<!-- Cover -->
<div align="center">
 <img src="../assets/img/logoUPC.png">
</div>

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

***Ingeniería de Software***

**Curso:** 1ASI0730 | Aplicaciones Web
**NRC:** 12053
**Ciclo:** 5  
**Docente:** Efraín Ricardo Bautista Ubillús  

## **"Informe de trabajo: AV1"**

#### *Startup:* GoldMetrics

#### *Producto:* GoldCheck


***Relación de integrantes:***

| INTEGRANTES | CÓDIGO |
| :---: | :---: |
| Armestar Felipa, Adrian Andres | U202410084 |
| García Paredes, Victor Manuel | U202012001 |
| Navarro Aldoradin, Carolina Celeste  | U20241B962 |
| Philco Mota, Katty Yolanda | U202416107 |
| Tuesta Girón, Kiara Lucia | U20251i477 |

<!-- Cover -->
<div align="center">
 <strong>Abril, 2026</strong>

</div>


<div style="page-break-after: always"></div>

## REGISTRO DE VERSIONES DEL INFORME

| Versión | Fecha | Autor | Descripción de modificación |
| :---: | :---: | :---: | :---: |


<div style="page-break-after: always"></div>

## PROJECT REPORT COLLABORATION INSIGHTS

<div style="page-break-after: always"></div>


## CONTENIDO

[REGISTRO DE VERSIONES DEL INFORME](#registro-de-versiones-del-informe)

[PROJECT REPORT COLLABORATION INSIGHTS](#project-report-collaboration-insights)

[STUDENT OUTCOME](#student-outcome)

[CAPÍTULO I: INTRODUCCIÓN](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción del Startup](#111-descripción-del-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)

- [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

---

[CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS](#capítulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)

- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)

- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)

- [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)

---

[CAPÍTULO III: REQUIREMENTS SPECIFICATION](#capítulo-iii-requirements-specification)

- [3.1. User Stories](#31-user-stories)
- [3.2. Impact Mapping](#32-impact-mapping)
- [3.3. Product Backlog](#33-product-backlog)

---

[CAPÍTULO IV: PRODUCT DESIGN](#capítulo-iv-product-design)

- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)

- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)

- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)

- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
  - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)

- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)

- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
  - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
  - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
  - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)

- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)

- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagrams](#481-database-diagrams)

---

[CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT](#capítulo-v-product-implementation-validation--deployment)

- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)

- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
    - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

- [5.3. Validation Interviews](#53-validation-interviews)
  - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
  - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)

- [5.4. Video About-the-Product](#54-video-about-the-product)

- [Anexos](#55-anexos)

# STUDENT OUTCOME

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta. | Navarro Aldoradin Carolina Celeste<br>AV1<br>Lideró el diseño de la Landing Page (Wireframe y Mock-up), guiando las decisiones visuales del equipo para estos componentes.<br><br>Philco Mota Katty Yolanda <br>AV1<br>Lideró la sección de Needfinding (User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping), orientando al equipo en la comprensión del problema y las necesidades de los usuarios.<br><br>Armestar Felipa, Adrián Andres<br>AV1<br>Lideró la elaboración de la arquitectura de software orientada al dominio (Domain-Driven Software Architecture: Design-Level EventStorming, diagramas de Contexto, Contenedores y Componentes) y el Software Object-Oriented Design, guiando las decisiones técnicas del equipo.<br><br>García Paredes Victor Manuel<br>AV1<br>Lideró la elaboración de los Requirements Specification (User Stories, Impact Mapping y Product Backlog) coordinando la definición de requisitos y el diseño de datos del proyecto.<br><br>Tuesta Girón, Kiara Lucia<br>AV1<br>Lideró el diseño UX/UI de las Web Applications (Wireframes, Wireflow Diagrams, Mock-ups y User Flow Diagrams), guiando las decisiones visuales del equipo para estos componentes. | El equipo demostró liderazgo distribuido durante el AV1, asignando responsables claros para cada área del proyecto. Cada integrante asumió su rol de liderazgo, facilitando la toma de decisiones y el avance estructurado del trabajo. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | Tuesta Girón, Kiara Lucia<br>AV1<br>Colaboró en el diseño, registro y análisis de entrevistas junto al equipo, y cumplió con la entrega de los artefactos de diseño UI/UX dentro del plazo establecido para el Sprint 1.<br><br>Philco Mota, Katty Yolanda<br>AV1<br>Participó activamente en las sesiones de entrevistas y en la elaboración de los artefactos de Needfinding, contribuyendo a la construcción de una visión compartida de los usuarios.<br><br>Navarro Aldoradin, Carolina Celeste<br>AV1<br>Colaboró en la configuración del entorno de desarrollo y en el Source Code Management, cumpliendo con la entrega de los diagramas de arquitectura planificados para el Sprint 1.<br><br>García Paredes, Victor Manuel<br>AV1<br>Participó en la planificación del Sprint 1 y en la construcción del Product Backlog, estableciendo metas claras mediante User Stories priorizadas y cumpliendo con los entregables asignados.<br><br>Armestar Felipa, Adrián Andres<br>AV1<br>Colaboró en la definición del problema y la propuesta de solución junto al equipo, estableciendo objetivos iniciales y cumpliendo con la redacción del Capítulo I dentro del plazo establecido. | Durante el AV1, el equipo trabajó de manera colaborativa e inclusiva, participando activamente en las actividades de investigación y planificación. Se establecieron objetivos claros, se distribuyeron las tareas según las fortalezas de cada integrante y se cumplieron los entregables dentro del plazo definido. |

# CAPÍTULO I: INTRODUCCIÓN {#capitulo-i-introduccion}

## 1.1. Startup Profile

### 1.1.1. Descripción del Startup

Nuestra start up "Goldmetrics" está enfocada en el sector minero ya que se busca monitorear, analizar y validar el recorrido de los minerales desde su extracción hasta el producto final. Logramos esto al desarrollar una plataforma de trazabilidad de minerales implementando tecnología IoT, soluciones Web e Inteligencia Artificial.

La solución permite a las empresas mineras mejorar la eficiencia y la logística al reducir pérdidas y mejorar la gestión de las operaciones al usar datos en tiempo real. De la misma manera, brinda a las joyerías las herramientas necesarias para validar el origen de los minerales para que estos puedan vender productos de calidad.

Goldmetrics le garantiza al usuario la autenticidad del producto al permitir la transparencia de la información de estos, lo cual promueve una compra consciente y sobre todo ética.

Misión: Desarrollar tecnologías que permitan rastrear, analizar y certificar el recorrido de los minerales, garantizando la autenticidad de los productos y promoviendo la responsabilidad social.

Visión: Gold Metrics busca posicionarse como la plataforma líder en trazabilidad minera de América Latina conectando tanto a empresas como a consumidores con información confiable y verificable.

### 1.1.2. Perfiles de integrantes del equipo

| Integrantes | Descripción |
| :--- | :--- |
|![Adrian](../assets/img/chapter-i/Armestar.png) | **Nombres y Apellidos:** Adrian Andres Armestar Felipa <br> **Código:** U202410084 <br> **Carrera:** Ingenieria de Software <br> Soy una persona confiable, adaptable y responsable en cuanto a las entregas de los trabajos. Me especializo en el lenguaje C++ pero también tengo conocimientos acerca de base de datos y JavaScript. Poseo una mentalidad de mejora continua, donde busco aprender y mejorar mis habilidades. Del mismo modo, busco trabajar de manera constante y con una adecuada gestión del tiempo. |
|![Victor](../assets/img/chapter-i/Garcia.png)  |**Nombres y Apellidos:** García Paredes, Victor Manuel  <br> **Código:** U202012001 <br> **Carrera:** Ingenieria de Software Estudiante de la carrera de ingeniería de software con sólidos conocimientos en desarrollo de aplicaciones, estructuras de datos y programación orientada a objetos. Tengo experiencia en el uso de C++, así como en la gestión de proyectos mediante herramientas como Git y GitHub para el control de versiones. También tengo un conocimiento basico sobre Python, MSSQL y MongoDB. Me caracterizo por ser una persona responsable, con iniciativa para el aprendizaje autónomo, y con habilidades para el trabajo en equipo y la comunicación efectiva de ideas.|
|![Carolina](../assets/img/chapter-i/Navarro.png) | **Nombres y Apellidos:** Carolina Celeste Navarro Aldoradin <br> **Código:** U20241b962 <br> **Carrera:** Ingenieria de Software <br> Soy una persona resiliente, analítica y creativa. Tengo conocimientos en el lenguaje C++, Python, Javascript, SQL y Vercel, así como conocimientos en telemetría y IoT industrial. Poseo habilidades de gestión del tiempo y gestión de proyectos y estoy enfocada en la resolución de problemas y optimización de procesos.
|![Katty](../assets/img/chapter-i/Philco.png)  | **Nombres y Apellidos:** Katty Yolanda Philco Mota <br> **Código:** U202416107<br> **Carrera:** Ingeniería de Software<br> Soy una persona organizada, responsable y comprometida con mi crecimiento académico. Cuento con conocimientos en programación, especialmente en C++, así como en estructuras de datos, algoritmos y desarrollo de soluciones tecnológicas orientadas a proyectos reales. Me destaco por mi capacidad de análisis, resiliencia frente a los desafíos y disposición para el trabajo en equipo. Me interesa el desarrollo de proyectos innovadores que generen impacto, manteniendo siempre una actitud de aprendizaje constante y mejora continua.|
|![Kiara](../assets/img/chapter-i/Tuesta.png)|**Nombres y Apellidos:** Kiara Lucia Tuesta Girón <br> **Código:** U20251I2025 <br> **Carrera:** Ingenieria de Software Tengo 20 años y me interesa el desarrollo de aplicaciones. He trabajado con lenguajes como C++ y C#, y también tengo experiencia usando SQL para bases de datos. En trabajos en equipo me gusta participar activamente, aportar ideas y ayudar a que el grupo avance.|

## 1.1. Solution Profile

Somos GoldMetrics, una startup integrado por estudiantes de la carrera de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas. Nuestra startup se centra en la industria minera, con el objetivo de monitorear, examinar y certificar el camino de los minerales desde su extracción hasta el producto final. Esto se logra mediante el desarrollo de una plataforma que permite la trazabilidad de minerales, utilizando tecnología IoT, soluciones web e inteligencia artificial.

**Misión:** Desarrollar tecnologías de vanguardia que permitan rastrear, examinar y validar el trayecto de los minerales, asegurando la autenticidad de los productos y promoviendo activamente la responsabilidad social en la industria.

**Visión:** Consolidarnos como la empresa líder en trazabilidad minera en América Latina, conectando a toda la cadena de valor: desde la mina hasta el consumidor; con información confiable, inmutable y verificable.

### 1.2.1. Antecedentes y problemática

#### What?

El problema se centra en la falta de trazabilidad confiable de minerales en el Perú, lo cual impide reconocer el origen, autenticidad y recorrido de materiales como oro u otros metales.

Según la directora ejecutiva de la Sociedad Nacional de Minería, Angela Grossheim, rastrear el origen de minerales, especialmente el oro, es difícil debido al mercado informal mezclándose con el mercado formal (DesdeAdentro, 2025). Esto indica que en el sector hay incertidumbre sobre si los minerales provienen de fuentes legales, del mismo modo en el que se pueden manipular los datos de los productos lo cual incrementa el riesgo de pérdidas y/o fraude.

#### Who?

Alrededor de esta problemática se pueden identificar varios involucrados, principalmente a las empresas mineras, pues estas presentan dificultades para mantener un control claro de sus operaciones logísticas. Lo cual termina en ineficiencia operativa, fallas en las maquinarias y sobre todo pérdidas económicas y de material.

Por su lado, otros actores involucrados serían las joyerías y los consumidores finales, puesto que estos buscan adquirir productos auténticos y que estos posean un origen ético. Sin embargo, al no contar con datos confiables se genera una desconfianza en el mercado alrededor del verdadero valor de ciertos productos.

#### Where?

Este problema se presenta alrededor del sector minero, como en las zonas de extracción, las etapas de transporte, el almacenamiento, procesamiento y comercialización de los minerales.

#### When?

La problemática sucede en momentos como el transporte, procesamiento y transferencia de los minerales.

#### Why?

Este problema surge por la poca implementación de tecnologías para el monitoreo y control de los minerales, siendo que varias empresas siguen usando registros manuales cuyos datos pueden ser fácilmente manipulados.

#### How?

El problema ocurre debido a la falta de seguimiento de los minerales, por lo que nuestros usuarios utilizarán la solución cuando necesiten asegurar el control y validación de los minerales.

#### How much?

Esta problemática tiene impactos en varios sectores, especialmente el económico. Según el fiscal coordinado de las Fiscalías Especializadas en Materia Ambiental, Frank Almanza, afirmó que las pérdidas económicas por minería ilegal equivale al 2,5% del PBI (Canchari, 2025). Gracias a esto, podemos deducir que la falta de trazabilidad afecta no solo a los ingresos de las empresas, sino que afecta a la economía nacional, resaltando lo importante que es el buscar una solución a dicha problemática.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Nuestra solución busca mejorar la trazabilidad de los minerales mediante el uso de una plataforma que use tecnología IoT, Web e IA.

Hemos observado que las empresas, sobre todo relacionadas a la minería, sufren ineficiencias operativas al tener dificultades para monitorear en tiempo real el traslado de los minerales.

**¿Cómo puede nuestro producto apoyar en el rastreo de minerales para reducir pérdidas?**

Nuestra solución busca verificar la autenticidad de los minerales que son usados en productos.

Hemos observado que las tiendas no cuentan con mecanismos para validar el origen de los minerales lo cual afecta la credibilidad de los distribuidores.

**¿Cómo puede nuestro producto garantizar la autenticidad de los minerales para reforzar la confianza entre los clientes?**

Nuestra solución busca ofrecer acceso transparente a la información relacionada al origen de los productos minerales que terminan en objetos que se compran en el día a día.

Hemos observado que el consumidor no tiene una forma de verificar si el producto proviene de fuentes responsables.

**¿Cómo puede nuestro producto fomentar la venta de productos hechos en base a minerales con origen ético?**

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**
- Creemos que nuestros usuarios necesitan tener una herramienta con la que puedan validar el recorrido de los minerales.
- Estas necesidades se pueden satisfacer con una solucion web que brinde informacion detallada sobre los minerales tratados.
- Nuestros clientes iniciales seran las empresas, joyerias y los usuarios finales.
- El valor mas importante que un cliente quiere de nuestros servicios es la trazabilidad de los minerales, incluyendo informacion desde su origen.
- El cliente tambien va a obtener reduccion de perdidas y apoyo en las decisiones logísticas.
- Vamos a obtener la mayoria de los clientes mediante alianzas con empresas relacionadas al sector minero al igual que marketing B2B y demostraciones del sistema en eventos del sector.
- Vamos a obtener ingresos mediante suscripciones mensuales las cuales dependan de un numero de productos analizados preestablecido.
- Nuestra competencia en el mercado seran soluciones que monitoreen los minerales de manera incompleta con software caro y poco flexible.
- Vamos a tener ventaja frente a nuestra competencia debido a la integración de tecnologías IoT, IA y WEB en el enfoque de la trazabilidad del mineral.
- El mayor riesgo del servicio es la adaptación del sistema en productos ya existentes y errores manuales al momento de registrar datos.
- Lo resolveremos realizando interfaces simple y sesiones de entrenamiento simulando casos reales.

**User Assumptions:**
- ¿Quien es el usuario?
Los usuarios son empresas mineras que necesiten gestionar los bienes obtenidos. Tambien estan, las joyerías que requieran validar dichos insumos. Finalmente son los usuarios finales que esten interesados en conocer el origen de los productos y evitar ser estafados en el proceso.
- ¿Que problemas tiene nuestro producto que resolver?
Nuestro producto tiene que resolver las dificultades en el monitoreo de los minerales, al igual que necesita verificar tanto la autenticidad como el origen etico de estos.
- ¿Que caracteristicas son importantes?
Se incluye el registro y monitoreo en tiempo real del traslado de los minerales, en estos registros estará información como el peso del mineral, la cantidad de este, las condiciones del envió y la verificación de la carga y de la descarga. Del mismo modo es necesaria la generacion de reportes especificando quien superviso, quien manipulo, cuando y donde.
- ¿Donde encaja nuestro producto en su trabajo o vida?
El producto encaja en la gestión operativa y en la logística de las empresas mineras para que estas puedan tener un mejor control sobre los minerales obtenidos. También encaja tanto en tiendas como en consumidores pues estos pueden validar y verificar información sobre los productos.
- ¿Cuando y como es nuestro producto usado?
Se utiliza durante todo el proceso del ámbito minero, llendo desde la extracción, incluyendo el traslado, el deposito o el procesamiento hasta la venta final. El producto puede ser usado mediante una plataforma web en cualquier momento siendo limitado por el rol del usuario.
- ¿Como debe verse nuestro producto y como debe comportarse?
Debe ser intuitiva mediante el uso de dashboards, de esta manera brindara una navegación sencilla a los usuarios mientras brinda información confiable y lo suficientemente rápida como para estar a tiempo real.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Creemos** que una plataforma que permita monitorear en tiempo real los minerales ayudara a reducir las perdidas de minerales.
**Sabremos que** hemos tenido éxito
**Cuando** en los reportes de las empresas mineras disminuya la cantidad de perdidas.

**Creemos** que una plataforma que pueda certificar la autenticidad de los minerales ayudara a mejorar la confianza entre tiendas y consumidores.
**Sabremos que** hemos tenido éxito
**Cuando** los productos con certificación sean más vendidos respecto a los productos regulares.

**Creemos que** una plataforma que permita al usuario observar información de los productos en venta logrará fomentar decisiones de compra responsables.
**Sabremos que** hemos tenido éxito
**Cuando** calculemos el tiempo de visualización de información como una estadística.

#### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas Goldmetrics](../assets/img/chapter-i/LeanUXCanvas.png)

## 1.3. Segmentos Objetivo

### Segmento 1: Empresas mineras

#### Descripción general:

Se refiere a las empresas que se dedican a la extracción de los minerales que terminan siendo procesados en productos pero que tienen problemas en la trazabilidad de sus operaciones.

#### Perfil Operativo:
Incluye a ingenieros y supervisores de entre 30 a 60 años que trabajan en las zonas mineras del Perú.

#### Datos del sector:
Según Canchari (2025), los problemas de trazabilidad y control en el sector minero genera mas de 22 mil millones de soles como perdidas al año.

#### Necesidad:
Este segmento necesita herramientas tecnológicas que permita el monitoreo en tiempo real para optimizar la logística en el ámbito minero.

### Segmento 2: Joyerías 

#### Descripción general:
Se refiere a empresas que venden productos cuyo material principal son los minerales pero que tienen dificultades al momento de garantizar el origen de dichos productos.

#### Perfil Operativo:
Incluye a dueños y gerentes de dichas tiendas cuya edad varia entre 26 a 60 años ubicados en zonas comerciales del Perú.

#### Datos del sector:
Según el presidente de la Sociedad Nacional de Mineria, Petroleo y Energia, Victor Gobitz, la minería ilegal implementa más del millón de onzas de oro al mercado (Cruz, 2024). Esta alarmante cantidad significa que existe una alta probabilidad de que las joyerías vendan productos con una trazabilidad inexistente.

#### Necesidad:
Este segmento necesita herramientas tecnológicas que permitan validar el origen del mineral para ofrecer una certificación confiable a los clientes.

### Segmento 3: Consumidores finales

#### Descripción general:
Se refiere a personas que compran productos como joyas.

#### Perfil Operativo:
Incluye adultos jóvenes de entre 18 a 25 años con un interés en el consumo responsable.

#### Datos del sector:
Según el Anuario Minero 2024 del Minem, el Perú produjo 100 mil toneladas de oro, pero exporto 200 mil (Nuñez, 2025). Esto indica que alrededor de 100 mil toneladas de oro ilegales pueden ser exportadas mediante canales formales los cuales terminan siendo compradas por los consumidores.

#### Necesidad:
Este segmento necesita herramientas que les permita acceder a la información del producto de manera sencilla para poder reconocer su origen y autenticidad.

# CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table border="1">
<!-- Encabezado Superior -->
<tr>
<th colspan="5"><b>Competitive Analysis Landscape</b></th>
<th colspan="4"></th>
</tr>
<tr>
<td width="20%">¿Por qué llevar a cabo este análisis?</td>
<td colspan="5">Identificar brechas en el mercado de trazabilidad minera y posicionar a GoldMetrics frente a soluciones telemáticas y plataformas OEM.</td>
</tr>

<!-- Encabezado de Columnas -->

<tr>
<td colspan="2"> <b>Competidores</b> </td>
<td>
    <img src="../assets/img/goldmetrics_logo.png" alt="Logo de Geotab" width="200">
    <b>GoldMetrics</b>
</td>
<td><img src="https://static.esmartcity.es/media/2020/02/logotipo-geotab.png" alt="Logo de Geotab" width="100"><br>

  <b>Competidor 1: Geotab (Minería)</b>
</td>
<td>
<img src= "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlTyO3BqONQBYmuLyd2iHow_VHAiaYqmuGGw&s" alt= "Logo de MineStar" width=""><br>

<img src= "https://upload.wikimedia.org/wikipedia/commons/6/62/Modular_Mining_Systems_logo.svg" alt= "Logo de Modular Mining" width=""><br>

<b>Competidor 2: Caterpillar MineStar / Modular (Komatsu)</b></td>
<td>

<img src= "https://assets.weforum.org/organization/image/aUNcA6Ix6AURcKk26xlf-Uqf09QeNS3cdfx1TIpWMuo.jpg" alt= "Logo de Circulor" width=""><br>

<img src= "https://static1.squarespace.com/static/615d3194538126232ff12aec/t/61f9e2edf81ca15cc6aaa567/1697418174626/TraceMark_vert_pos_RGB.png?format=1500w" alt= "Logo de Tracemark" width="">
<img src= "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRAzb4D0LBSoRUPefrRH0hX0NUO6zvrLbQXg&s" alt= "Logo de Minehub" width="">
<br>
<b>Competidor 3: Circulor / Tracemark / MineHub</b></td>
</tr>

<!-- Sección Perfil -->

<tr>
<td rowspan="2" style="vertical-align: middle; transform: rotate(-90deg);"><b>Perfil</b></td>
<td>Overview</td>
<td>Plataforma de inteligencia de datos especializada en optimización de activos mineros.</td>
<td>Líder mundial en telemática y gestión de flotas con hardware robusto.</td>
<td>Sistemas de gestión de flota (FMS) integrados directamente en la maquinaria.</td>
<td>Plataformas enfocadas en cumplimiento ESG y trazabilidad de cadena de suministro (Blockchain).</td>
</tr>
<tr>
<td>Ventaja competitiva</td>
<td>Agilidad en integración de datos y visualización personalizada de KPIs operativos.</td>
<td>Ecosistema masivo de datos y compatibilidad multimarca mediante hardware plug-and-play.</td>
<td>Control total del hardware de la máquina y automatización profunda del ciclo de carga.</td>
<td>Especialización en normativas de sostenibilidad y "pasaporte digital" de minerales.</td>
</tr>

<!-- Sección Marketing -->

<tr>
<td rowspan="2" style="vertical-align: middle; transform: rotate(-90deg);"><b>Perfil de Marketing</b></td>
<td>Mercado objetivo</td>
<td>Minas medianas y grandes que buscan optimizar costos operativos.</td>
<td>Empresas de logística minera y flotas de transporte terrestre.</td>
<td>Grandes corporaciones mineras con flotas monomarca o de alto tonelaje.</td>
<td>Empresas mineras enfocadas en exportación a Europa/EE.UU. y cumplimiento ético.</td>
</tr>
<tr>
<td>Estrategias de marketing</td>
<td>Venta consultiva enfocada en eficiencia y retorno de inversión (ROI).</td>
<td>Alianzas con revendedores globales y marketplace de aplicaciones.</td>
<td>Venta directa integrada en la compra de activos (maquinaria pesada).</td>
<td>Marketing de reputación, transparencia y cumplimiento de estándares globales (LME).</td>
</tr>
<tr>
<td rowspan="3" style="vertical-align: middle; transform: rotate(-90deg);"><b>Perfil de Producto</b></td>
<td>Productos & Servicios</td>
<td>Dashboards analíticos, monitoreo en tiempo real y reportes automáticos.</td>
<td>Dispositivos GO9, software MyGeotab y análisis de comportamiento de conducción.</td>
<td>Sistemas de guiado GPS, gestión de fatiga y autonomía de camiones.</td>
<td>Software de seguimiento de activos mediante tecnología de registro distribuido.</td>
</tr>
<tr>
<td>Precios & Costos</td>
<td>SaaS (Suscripción mensual) escalable por número de activos.</td>
<td>Costo de hardware inicial + suscripción mensual por dispositivo.</td>
<td>Capex elevado (Licenciamiento perpetuo o incluido en el activo) + soporte.</td>
<td>Suscripciones corporativas premium basadas en volumen de material trazado.</td>
</tr>
<tr>
<td>Canales de distribución (Web y/o Móvil)</td>
<td>Web App y notificaciones móviles integradas.</td>
<td>Plataforma Web, Apps móviles y APIs para integración externa.</td>
<td>Sistemas embebidos en cabina y centros de control locales (on-premise).</td>
<td>Plataformas Cloud (Web) con acceso para múltiples actores de la cadena.</td>
</tr>
<tr>
<td rowspan="4" style="vertical-align: middle; transform: rotate(-90deg);"><b>Análisis SWOT</b></td>
<td>Fortalezas</td>
<td>Flexibilidad y enfoque en el usuario final.</td>
<td>Escalabilidad y robustez del hardware probado.</td>
<td>Integración técnica inigualable con el motor y sistemas del equipo.</td>
<td>Posicionamiento único en el nicho de "Minería Verde".</td>
</tr>
<tr>
<td>Debilidades</td>
<td>Menor reconocimiento de marca frente a gigantes.</td>
<td>Instalación de hardware físico requerida en cada unidad.</td>
<td>Sistemas cerrados y muy costosos para flotas mixtas.</td>
<td>Complejidad en la implementación con proveedores externos.</td>
</tr>
<tr>
<td>Oportunidades</td>
<td>Expansión a minería artesanal o pequeña escala desatendida.</td>
<td>Integración con vehículos eléctricos mineros.</td>
<td>Dominio del mercado de camiones autónomos.</td>
<td>Nuevas regulaciones ambientales estrictas a nivel mundial.</td>
</tr>
<tr>
<td>Amenazas</td>
<td>Consolidación de competidores grandes adquiriendo startups.</td>
<td>Commoditización de los servicios básicos de GPS.</td>
<td>Resistencia de las minas a cambiar sistemas ya instalados de fábrica.</td>
<td>Cambios rápidos en los protocolos tecnológicos de trazabilidad.</td>
</tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
- **Estrategia Defensiva: Neutralizar las Fortalezas de los Competidores**
Enfoque: Si no puedes vencer su hardware, integra su data.
  - ***Táctica de "Capa Superior" (vs. OEMs/Geotab)***: No intentes competir fabricando hardware más robusto que Caterpillar o Geotab. Posiciona a GoldMetrics como la plataforma agnóstica que consolida los datos de ambas fuentes en un solo dashboard.
  - ***Táctica de Alianzas Técnicas***: Desarrollar APIs abiertas y conectores pre-configurados para que el cliente sienta que GoldMetrics "desbloquea" el valor de la maquinaria que ya compró, en lugar de ser un sistema que compite con el fabricante.

2. **Estrategia Ofensiva: Explotar las Debilidades de la Competencia**
Enfoque: Agilidad vs. Burocracia y Flexibilidad vs. Rigidez.
   - ***Táctica de Flotas Mixtas (vs. OEMs)***: Los OEMs suelen fallar cuando una mina tiene camiones Komatsu y palas Caterpillar. Ataca este punto crítico ofreciendo una visión 360° que los fabricantes no pueden (o no quieren) dar por proteger su ecosistema cerrado.
   - ***Táctica de "Cero Fricción" (vs. Geotab)***: Mientras Geotab requiere tiempos de instalación física y configuración de hardware, implementa un modelo de ingesta de datos vía API (Cloud-to-Cloud) para que el cliente vea resultados en días, no meses.
   - ***Táctica de Precios SaaS (vs. Alto Capex de OEMs)***: Elimina la barrera del "pago inicial millonario". Implementa una estructura de costos operativos (OpEx) que permita a minas medianas acceder a tecnología de punta sin comprometer su flujo de caja.

3. **Estrategia de Oportunidad: Liderar en Trazabilidad y ESG**
Enfoque: Simplificar lo complejo.

   - ***Táctica "ESG-Light":*** Las plataformas como Circulor son extremadamente complejas. Crea un módulo de Reportabilidad Automática de Carbono que tome los datos de consumo de combustible ya existentes en GoldMetrics y los transforme en reportes de cumplimiento para inversionistas con un solo clic.
   - ***Táctica de Nicho (Minería de Media Escala):*** Mientras los grandes se pelean por las "Tier 1" (BHP, Rio Tinto), enfócate en capturar el mercado de minería mediana que está siendo presionada por regulaciones ambientales pero no tiene el presupuesto para soluciones a medida de millones de dólares.

4. **Estrategia de Mitigación de Amenazas: Construcción de Foso (Moat)**
Enfoque: Blindar la relación con el cliente.
  - ***Táctica de Éxito del Cliente (High-Touch):*** Los gigantes ofrecen soporte mediante tickets y call centers. GoldMetrics debe ofrecer Consultoría de Optimización incluida en la suscripción, donde un experto analice los KPIs junto al jefe de mina mensualmente para asegurar el ROI.
  - ***Táctica de Modularidad:*** Para evitar que un competidor grande te desplace por precio, permite que el cliente compre solo el módulo que necesita (ej. solo "Gestión de Neumáticos" o solo "Consumo de Diésel"). Una vez dentro de su ecosistema, la expansión es mucho más natural.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

  **Primer Segmento:** A continuación, se presentan las preguntas dirigidas al segmento de empresas mineras, conformado por profesionales y organizaciones responsables de la extracción, transporte y gestión de minerales. Este segmento se encarga de la obtención y movilización de los recursos, enfrentando desafíos relacionados con el control y la trazabilidad.

  - **Preguntas principales:**
1.	¿Cómo registran actualmente el traslado de minerales?
2.	¿Existen problemas de pérdida o falta de control?
3.	¿Cuál es tu principal objetivo en la gestión de materiales o minerales?
4.	¿Qué herramientas usan para monitoreo?
5.	¿Qué tan común es la falta de trazabilidad?
6.	¿Qué impacto tiene en costos o producción?
7.	¿Crees útil un sistema que rastree minerales desde la extracción?
8.	¿Qué información sería clave para ustedes?
9.	¿Qué tan frecuente es la ocurrencia de fallas durante la obtención de minerales?
10.	¿Cómo identifican actualmente los errores o fallas en la extracción de minerales?

- **Preguntas complementarias**
1.	¿Cuál es tu edad?
2.	¿En qué distrito o zona vives?
3.	¿Cuál es tu estado civil?
4.	¿Qué dispositivos utilizas con mayor frecuencia en tu trabajo?
5.	¿Utilizas aplicaciones o sistemas digitales en tus labores diarias? ¿Cuáles?
6.	¿Qué rol desempeñas dentro del sector minero?
7.	¿Qué es lo que más te frustra del proceso actual de control o traslado de minerales?

 **Segundo Segmento:** A continuación, se presentan las preguntas dirigidas al segmento de joyerías, integrado por personas que trabajan en la fabricación y comercialización de productos elaborados con minerales. Estas empresas pueden operar tanto con materiales provenientes de proveedores como con insumos proporcionados directamente por los clientes.

  - **Preguntas principales:**
1.	¿Cómo verificas la autenticidad de las joyas que vendes?
2.	¿Has tenido problemas con proveedores o materiales falsos?
3.	¿Qué tan importante es para tus clientes saber el origen de una joya?
4.	¿Llevas algún registro del origen de tus productos?
5.	¿Tus clientes te piden certificación o pruebas de autenticidad?
6.	¿Cómo generas confianza al vender?
7.	¿Qué problemas has tenido con la trazabilidad o calidad del material?
8.	¿Has perdido ventas por falta de confianza del cliente?
9.	¿Qué haces cuando un cliente trae su propio material (oro u otros minerales)?
10.	¿Cómo manejas o comunicas la autenticidad cuando el material es proporcionado por el cliente?

- **Preguntas complementarias**
1.	¿Cuál es tu edad?
2.	¿En qué distrito o zona vives?
3.	¿Cuál es tu estado civil?
4.	¿Qué rol desempeñas dentro de la joyería?
5.	¿Usas sistemas digitales para gestionar ventas o inventario?
6.	¿Qué es lo más difícil al trabajar con materiales proporcionados por proveedores o clientes?

**Tercer Segmento:** A continuación, se presentan las preguntas dirigidas al segmento de usuarios consumidor, es decir, personas que adquieren productos fabricados con minerales, como joyas. Este segmento se caracteriza por su creciente interés en la autenticidad, la transparencia y el origen ético de los productos que consume.

  - **Preguntas principales:**
1.	¿Con qué frecuencia compras joyas?
2.	¿Qué factores consideras al comprar (precio, marca, material, etc.)?
3.	¿Te preocupa si una joya es auténtica?
4.	¿Cómo sabes si una joya es real?
5.	¿Te importa el origen del producto (si es ético o no)?
6.	¿Pagarías más por una joya certificada como ética?
7.	¿Qué tanta confianza tienes en la información que brindan las marcas sobre sus productos?
8.	¿Te gustaría poder verificar por ti mismo el origen de un producto mediante una app o código QR?
9.	¿Qué tipo de información te gustaría conocer antes de comprar una joya o producto mineral?
10.	 ¿Dejarías de comprar una marca si supieras que sus productos provienen de explotación laboral o prácticas poco éticas?

- **Preguntas complementarias**
1.	¿Cuál es tu edad?
2.	¿En qué distrito o zona vives?
3.	¿Cuál es tu estado civil?
4.	¿Qué dispositivos utilizas con mayor frecuencia (celular, laptop, etc.)?
5.	¿Qué opinas de productos con certificaciones como “cruelty-free” o “eco-friendly”?
6.	¿Qué buscas principalmente al comprar una joya o producto (ej. calidad, estatus, significado, inversión)?

<div style="page-break-after: always"></div>

### 2.2.2. Registro de entrevistas
| Segmento: Empresas Mineras | Entrevista #1 |
| --- | --- |
| Nombres y Apellidos | Maximiliano Lopez Melgarejo|
| Edad | 22 años |
| Distrito | Callao |
| Ocupación | Especialista en mecatrónica de camiones mineros |
| Timming inicio |00:00:00 - 00:11:29 |
| Duración | 11 minutos y 38 segundos|
| URL |https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ |
| Screenshot | ![Screenshot Maximiliano](../assets/img/chapter-ii/interview-Maximiliano.png) |
| Resumen | El entrevistado es Maximiliano Lopez Melgarejo, un joven de 22 años residente en el Callao, especializado en mecatrónica de camiones mineros. Su trabajo se enfoca en el mantenimiento de equipos pesados utilizando tecnologías como sensores, cámaras y módulos electrónicos que permiten monitorear en tiempo real el rendimiento, condiciones del vehículo y carga transportada. En el proceso de traslado de minerales, destaca la importancia del control de carga, ya que exceder los límites establecidos puede generar riesgos operativos, pérdidas económicas e incluso accidentes. Además, menciona que uno de los principales problemas es la pérdida de material durante el trasbordo entre camiones, lo que afecta la eficiencia del proceso. Respecto a la trazabilidad, señala que existe una ruptura en la cadena una vez que el mineral es vendido a terceros, perdiéndose el seguimiento hasta el consumidor final. También enfatiza que cualquier sistema de monitoreo debe garantizar la confidencialidad de los datos, ya que la información sobre extracción y producción es altamente sensible para las empresas. Finalmente, indica que las fallas se gestionan mediante sistemas de monitoreo y mantenimiento preventivo, aunque las paradas por reparación representan un alto costo operativo. En este contexto, resalta la necesidad de equilibrar la continuidad de la producción con la seguridad y el buen estado de los equipos. |

<div style="page-break-after: always"></div>

| Segmento: Empresas Mineras | Entrevista #2 |
| --- | --- |
| Nombres y Apellidos | Lynn Marin |
| Edad |30 años|
| Distrito |  San Miguel |
| Ocupación | Ingeniera mecatrónica |
| Timming inicio | 00:11:29 - 00:29:02 |
| Duración | 17 minutos y 37 segundos|
| URL | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ |
| Screenshot | ![Screenshot Lynn](../assets/img/chapter-ii/interview-Lynn.png) |
| Resumen | La entrevistada es una ingeniera mecatrónica de 30 años que trabaja en un laboratorio de electrónica en Ferreyros, enfocada en la confiabilidad del armado y mantenimiento de motores para minería. Su labor está altamente vinculada al uso de tecnologías avanzadas, como sensores, actuadores y sistemas digitales para el monitoreo y análisis de datos en tiempo real.En cuanto a la gestión y monitoreo, utiliza herramientas como el software Tracking para rastrear componentes, así como plataformas como Smarty y Daris, que permiten recolectar información técnica y controlar equipos de forma remota. Su principal objetivo es maximizar la vida útil de los motores, asegurar su confiabilidad y reducir los tiempos de entrega, todo bajo un enfoque orientado a resultados económicos medibles. Respecto a la trazabilidad, destaca que es un elemento clave en procesos complejos, permitiendo conocer el estado, ubicación e historial de los componentes en todo momento. Sin embargo, señala que las empresas mineras son cautelosas al compartir esta información por motivos de confidencialidad y competencia. Además, enfatiza la importancia de analizar datos históricos y en tiempo real para implementar mantenimiento predictivo y evitar fallas recurrentes. En conclusión, identifica como principal frustración la dependencia de registros manuales, los cuales generan pérdida de tiempo y menor eficiencia operativa. En este sentido, promueve la automatización mediante sensores y sistemas integrados que permitan capturar datos de manera automática, optimizando los procesos y mejorando la toma de decisiones. |

<div style="page-break-after: always"></div>

| Segmento: Empresas Mineras | Entrevista #3 |
| --- | --- |
| Nombres y Apellidos | Max Alonso Yapo Figueroa|
| Edad | 31 años |
| Distrito | Arequipa (Cercado)|
| Ocupación | Ingeniero metalurgista |
| Timming inicio |00.29:02 - 00:35:29 |
| Duración | 6 minutos y 27 segundos|
| URL |https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ |
| Screenshot | ![Screenshot Max](../assets/img/chapter-ii/interview-Max.jpg)|
| Resumen | El entrevistado es un profesional de 31 años, residente en Arequipa, que se desempeña como jefe de metalurgia y operaciones. En su trabajo utiliza principalmente el celular y la laptop, además de herramientas especializadas como Molycop. Actualmente, el registro del traslado de minerales se realiza mediante plantillas de Excel, complementadas con personal encargado del seguimiento desde la mina hasta la planta. Sin embargo, este proceso presenta limitaciones, ya que el control es en gran parte empírico, lo que genera errores en el pesaje de los volquetes y en las balanzas. Estos errores, aunque inicialmente pequeños, se acumulan con el tiempo y generan cuellos de botella operativos, afectando la precisión de los datos. Si bien existe un monitoreo constante mediante personal distribuido en la ruta, la trazabilidad no siempre es completamente precisa. Respecto a las fallas, suelen ser de nivel leve a moderado y están relacionadas con factores operativos. Además, el registro de incidentes se realiza de forma manual (en papel), utilizando dispositivos digitales solo para comunicación, lo que limita la eficiencia del proceso. Finalmente, el entrevistado considera que la implementación de un sistema digital de rastreo desde la extracción sería altamente beneficiosa, destaca la importancia de contar con información precisa sobre la ubicación del mineral y el tonelaje exacto, ya que los errores en estos datos afectan directamente el control del concentrado y la toma de decisiones en la planta.|

<div style="page-break-after: always"></div>

| Segmento: Joyerías | Entrevista #1 |
| --- | --- |
| Nombres y Apellidos | Yesiliany Canchica Muñoz |
| Edad | 21 años |
| Distrito | Surquillo |
| Ocupación | Secretaria de Joyería |
| Timming inicio |00:35:29 - 00:40:20 |
| Duración | 4 minutos y 50 segundos|
| URL | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ|
| Screenshot | ![Screenshot Yesiliany](../assets/img/chapter-ii/interview-Yesiliany.png)|
| Resumen | La entrevistada es una joven de 21 años que reside en Surquillo, ella trabaja como secretaria en una joyería desempeñando funciones operativas dentro del negocio. La gestión de inventarios se realiza de manera manual, ellos no realizan digitalización para los procesos internos del negocio. Respecto al control de calidad, la empresa utiliza tanto métodos tradicionales como tecnológicos para verificar la autenticidad del oro, como la prueba del ácido nítrico y máquinas de medición de quilataje. Sin embargo, uno de los principales desafíos identificados es el trabajo con materiales proporcionados por los clientes, puesto que si el oro no posee la calidad adecuada, el proceso de refinamiento implica una merma significativa pudiendo perderse hasta 1.5 gramos por cada 5 gramos iniciales. Respecto a la trazabilidad, la joyería mantiene relaciones de confianza con proveedores desde hace más de 10 años lo que garantiza la autenticidad del material adquirido. Por otro lado, los clientes valoran altamente el origen de las joyas y suelen exigir certificaciones especialmente en piezas con piedras preciosas. Finalmente, ella menciona que la confianza del cliente se construye a través de la transparencia, informando sobre la calidad real de las piezas y sus posibles riesgos. En síntesis, se observa un entorno de trabajo tradicional, enfocado en la experiencia y la calidad con oportunidades de mejora en la incorporación de herramientas digitales para la gestión. |

<div style="page-break-after: always"></div>

| Segmento: Joyerías | Entrevista #2 |
| --- | --- |
| Nombres y Apellidos | Ginny Céspedes Mundaca |
| Edad | 54 años |
| Distrito | Tarapoto, San Martin |
| Ocupación | Dueña de Joyería|
| Timming inicio | 00:40:20 - 00:48:54 |
| Duración | 08 minutos y 34 segundos|
| URL |https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ |
| Screenshot | ![Screenshot Ginny](../assets/img/chapter-ii/interview-Ginny.png)|
| Resumen |La entrevistada es la propietaria de una joyería en Tarapoto con aproximadamente 26 años de experiencia en el rubro. Trabaja junto a su esposo, quien es el orfebre del negocio, y basa gran parte de la verificación de autenticidad en su conocimiento técnico y experiencia. No utilizan sistemas digitales ni llevan un registro formal del origen de los materiales, lo que evidencia un manejo tradicional del negocio. En cuanto a la autenticidad y calidad, confían plenamente en la experiencia del orfebre para identificar materiales genuinos, lo que les ha permitido evitar problemas con proveedores. Sin embargo, reconocen que muchos consumidores sí son engañados en el mercado informal, lo que refuerza la importancia del conocimiento técnico en el sector. Respecto a la trazabilidad, los clientes no suelen exigir certificaciones ni información sobre el origen de las joyas, ya que la confianza se basa principalmente en la trayectoria del negocio y la garantía de calidad (oro de 18 quilates). No obstante, la entrevistada considera que implementar herramientas como códigos QR o sellos de certificación sería una oportunidad para diferenciarse y generar mayor confianza. Finalmente, uno de los principales desafíos es la informalidad del mercado, ya que adquirir oro con documentación legal eleva considerablemente los costos, reduciendo la competitividad y los márgenes de ganancia. Esto obliga al negocio a recurrir a proveedores informales, lo que limita la trazabilidad completa del material a pesar de mantener estándares de calidad en el producto final. |

<div style="page-break-after: always"></div>

| Segmento: Joyerías | Entrevista #3 |
| --- | --- |
| Nombres y Apellidos | Vicky Ríos Macedo |
| Edad | 42 años |
| Distrito | Tarapoto, San Martin |
| Ocupación | Dueña de Joyería |
| Timming inicio |00:48:54 - 01:03:25 |
| Duración | 14 minutos y 32 segundos |
| URL | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ|
| Screenshot |![Screenshot Vicky](../assets/img/chapter-ii/interview-Vicky.png) |
| Resumen |La entrevistada es Vicky, una emprendedora del rubro de joyería de acero en Tarapoto. Su negocio se basa en la reventa de productos, y utiliza herramientas digitales básicas como videollamadas para coordinar con proveedores y medios de pago electrónicos. No cuenta con sistemas formales de gestión ni registros detallados del origen de los productos, lo que evidencia un manejo operativo simple. En cuanto a la autenticidad y calidad, la validación se realiza a través del uso personal. Tanto ella como su hija prueban los productos para asegurar que no pierdan brillo, no se oxiden y no causen alergias. La confianza hacia los clientes se construye mediante esta experiencia directa y ofreciendo garantías de cambio o devolución, más que a través de certificaciones formales. Respecto a la trazabilidad, existe un conocimiento limitado sobre el origen de los productos, ya que solo identifica que provienen de China y se distribuyen desde Lima. Los clientes, por su parte, no suelen exigir información sobre procedencia o certificaciones, priorizando más bien la estética, el precio accesible y la durabilidad del producto. Finalmente, la entrevistada muestra interés en la implementación de herramientas tecnológicas como códigos de trazabilidad, considerándolas una oportunidad para diferenciar su negocio. Esto refleja una apertura hacia la innovación, aunque actualmente el sector en el que opera no exige altos niveles de transparencia en comparación con otros rubros. |

<div style="page-break-after: always"></div>

| Segmento: Usuario consumidor | Entrevista #1 |
| --- | --- |
| Nombres y Apellidos | Carla Gallardo Morales |
| Edad | 19 años |
| Distrito | La Molina |
| Ocupación | Estudiante universitaria |
| Timming inicio |01:03:25 - 01:08:09 |
| Duración | 4 minutos y 44 segundos |
| URL | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ|
| Screenshot | ![Screenshot Carla](../assets/img/chapter-ii/interview-Carla.png) |
| Resumen | Carla Gallardo es una joven de 19 años que reside en La Molina, soltera y estudiante universitaria. Ella usa principalmente el celular y la computadora para sus actividades académicas, lo que evidencia un perfil digital activo. Su frecuencia de compra de joyas es baja, adquiriendo principalmente accesorios de acero y comprando oro o plata  cada tres años aproximadamente. Al comprar una joya, sus principales criterios son la autenticidad del material, el diseño, la marca y el precio, muestra una alta preocupación por la autenticidad, aunque reconoce tener poco conocimiento técnico, lo que genera desconfianza hacia mecanismos tradicionales como los sellos de quilataje, ya que pueden ser falsificados. Asimismo, ella también valora el origen ético de los productos, tiene una postura positiva hacia certificaciones como “cruelty-free” y afirma que estaría dispuesta a pagar más por una joya que garantice tanto autenticidad como condiciones laborales justas. Además, señala que dejaría de consumir una marca si descubre prácticas de explotación laboral. Antes de realizar una compra le gustaría tener información clara sobre la autenticidad del material, el precio y la procedencia del producto. Finalmente, considera que herramientas tecnológicas como la verificación mediante QR o aplicaciones serían una solución efectiva para aumentar la confianza del consumidor. |

<div style="page-break-after: always"></div>


| Segmento: Usuario consumidor | Entrevista #2 |
| --- | --- |
| Nombres y Apellidos | Mauricio Moquillaza |
| Edad | 19 años |
| Distrito | Jesús María |
| Ocupación | Estudiante|
| Timming inicio | 01:08:09 - 01:19:44|
| Duración |11 minutos y 35 segundos |
| URL |https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ |
| Screenshot | ![Screenshot Mauricio](../assets/img/chapter-ii/interview-Mauricio.png)|
| Resumen | El entrevistado es Mauricio Moquillaza, un joven de 19 años, residente en Jesús María, Lima, soltero. Utiliza con frecuencia el celular y la laptop, mostrando un perfil digital activo. Su frecuencia de compra de joyas es baja, aproximadamente una vez al año, priorizando productos duraderos y de larga vida útil. Al momento de comprar, se enfoca principalmente en la apariencia visual, la durabilidad y que el precio sea acorde al producto, restando importancia a la marca. Sin embargo, muestra una alta preocupación por la autenticidad, debido a la existencia de falsificaciones. Aunque posee conocimientos básicos de verificación (como pruebas caseras), su nivel de confianza en las marcas es bajo ya que considera que muchas utilizan el marketing como estrategia más que como garantía real. En cuanto al aspecto ético, considera importante el origen de las joyas, especialmente para evitar contribuir a la minería ilegal o explotación laboral. Afirma que estaría dispuesto a pagar un poco más por productos certificados y que dejaría de comprar una marca si se comprobara que incurre en prácticas poco éticas. Finalmente, destaca el valor de herramientas tecnológicas como aplicaciones o códigos QR para verificar la autenticidad y trazabilidad del producto. Le gustaría acceder a información clara sobre la pureza del material y su procedencia, lo que refleja una necesidad de mayor transparencia y confianza en el mercado de joyería. |

<div style="page-break-after: always"></div>

| Segmento: Usuario consumidor | Entrevista #3 |
| --- | --- |
| Nombres y Apellidos | Oliver Galindo |
| Edad | 20 años |
| Distrito | Comas |
| Ocupación | Estudiante |
| Timming inicio |01:19:44 - 01:29:28 |
| Duración | 09 minutos y 43 segundos|
| URL |https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQALz-3qssjESZ1UptetozBUAfBFYqCG-yNQA-sl2rIA2CY?e=YGfOIJ |
| Screenshot | ![Screenshot Oliver](../assets/img/chapter-ii/interview-Oliver.png)|
| Resumen |El entrevistado es Oliver Galindo, un joven de 20 años, residente en Comas, soltero. Utiliza principalmente el celular y la computadora, lo que refleja un perfil digital activo. Su frecuencia de compra de joyas es baja y está orientada principalmente a la adquisición de obsequios solo ocasiones especiales. Al comprar, prioriza la calidad y la durabilidad del producto, seguido de la relación calidad-precio. Aunque inicialmente el diseño puede ser más relevante que la autenticidad técnica, menciona que sí muestra interés en verificar la veracidad del producto consultando al vendedor o revisando sellos de autenticidad, especialmente en materiales como oro o perlas. Respecto al origen ético, considera importante consumir productos legales y responsables, aunque reconoce que es difícil acceder a esta información. Por ello, opta por comprar en lugares formales para reducir riesgos. Además, estaría dispuesto a pagar más por productos con certificación ética y afirma que dejaría de comprar marcas vinculadas a la explotación laboral. Finalmente, percibe un bajo nivel de confianza en las marcas, ya que considera que muchas veces la información es solo marketing. En este contexto, valora positivamente el uso de herramientas tecnológicas como códigos QR o aplicaciones que permitan verificar la autenticidad y procedencia del producto, evidenciando una necesidad de mayor transparencia en el mercado. |

<div style="page-break-after: always"></div>

### 2.2.3. Análisis de entrevistas
Analisis por segmento y gráficas y porcentajes:

**Análisis Primer Segmento Empresas Mineras:** En primer lugar, existe una desconexión entre la data técnica y el impacto financiero. Según Lynn Marín, los sistemas actuales permiten recolectar información detallada sobre fallas y mantenimiento, pero no logran traducir estos datos en indicadores económicos claros. Esto evidencia la necesidad de soluciones que conviertan automáticamente la información técnica en pérdidas o ganancias en tiempo real, facilitando la toma de decisiones.

En segundo lugar, en el área de operaciones se identifica un problema crítico en la precisión del pesaje. La principal frustración no radica en la falta de tecnología digital, sino en errores físicos en el tonelaje de los volquetes, los cuales afectan directamente el cálculo del concentrado.

En tercer lugar, se evidencia una resistencia a los procesos manuales, especialmente en el uso de checklists en papel. Los operarios consideran estas tareas como una pérdida de tiempo, lo que genera una clara oportunidad para implementar sistemas automatizados mediante sensores que optimicen la captura de datos.

En cuarto lugar, se identifica una ruptura en la trazabilidad de la cadena de suministro. Una vez que el mineral es vendido a terceros, se pierde el seguimiento del mismo, dificultando la validación de su origen especialmente en industrias como la joyería. Esta desconexión limita la transparencia y el control a lo largo del ciclo de vida del mineral.

En conjunto, el segmento minero evidencia una dualidad operativa: mientras el 67% (2 de 3) presenta un alto nivel de digitalización enfocado en mantenimiento predictivo y monitoreo en tiempo real, el 33% (1 de 3) aún depende de procesos manuales para el control productivo. A pesar de esta diferencia, el 100% considera excelente contar con un sistema que rastree el mineral o los componentes desde su origen. Sin embargo, existe una resistencia total a compartir información con la competencia o distribuidores externos por temor a perder competitividad o exponer debilidades operativas. Esto revela que la oportunidad no está solo en digitalizar, sino en automatizar y asegurar la información, conectando datos técnicos con impacto económico en toda la cadena de valor.

![Chart 1](../assets/img/chapter-ii/chart-1.png)


**Análisis Segundo Segmento Joyerías:** En conjunto, el segmento joyería presenta una diversidad de perfiles que reflejan distintas realidades del sector: la empresaria tradicional (Ginny), la emprendedora emergente (Vicky) y la secretaria (Yesiliany). A pesar de sus diferencias, el 100% coincide en operar con esquemas tradicionales sin uso de sistemas digitales formales para la gestión de inventarios lo que evidencia un bajo nivel de digitalización en el rubro. En cuanto a la verificación de autenticidad, el 67% se basa en conocimiento técnico especializado (orfebres y la prueba de ácido nítrico), mientras que el 33% usa métodos empíricos como el uso personal del producto. 

Respecto a la trazabilidad, el 100% presenta ausencia o limitaciones en el registro formal del origen de los materiales. Esta situación está directamente relacionada con factores estructurales del mercado, como la informalidad y el alto costo del oro legal. Por ejemplo, adquirir oro con factura puede costar hasta 550 soles por gramo, mientras que el precio competitivo del mercado ronda los 460 soles, lo que obliga a recurrir a proveedores informales para mantener la rentabilidad.
![Chart 2](../assets/img/chapter-ii/chart-2.jpg)

En el aspecto operativo, se identifican ineficiencias en el manejo del material, como pérdidas de hasta 30% en procesos de purificación al trabajar con oro de clientes. Desde la perspectiva del cliente, el 67% de entrevistadas indica que no existe una demanda activa por certificaciones, especialmente en productos de menor valor como el acero, donde se prioriza la estética. Sin embargo, en joyas de mayor valor la importancia de su autenticidad alcanza niveles altos, especialmente en piezas con piedras preciosas. Finalmente, el 100% de los entrevistados muestra apertura hacia la implementación de tecnologías que permitan mostrar al cliente el origen del producto (como códigos QR) considerándolas una oportunidad para diferenciarse y fortalecer la confianza del cliente.
![Chart 3](../assets/img/chapter-ii/chart-3.png)


**Análisis Tercer Segmento Consumidor Final :** En conjunto, los consumidores entrevistados presentan un comportamiento de compra poco frecuente, orientado principalmente a ocasiones específicas. El 100% prioriza factores como la calidad, durabilidad y precio, mientras que la marca tiene una relevancia baja en la decisión de compra.

Respecto a la confianza y autenticidad, el 100% de los entrevistados manifiesta preocupación por la veracidad del producto, aunque reconoce tener un bajo conocimiento técnico para verificarlo. Como consecuencia, recurren a métodos como consultar al vendedor o usar pruebas básicas, lo que incrementa la incertidumbre durante la compra.

En cuanto a la confianza en las marcas, el 67% presenta un nivel de confianza bajo o moderado, percibiendo que muchas empresas utilizan el marketing sin garantizar realmente la autenticidad o el origen del producto.

Por otro lado, el 100% de los entrevistados valora el origen ético de los productos y estaría dispuesto a pagar un costo adicional (moderado) por garantizar autenticidad y condiciones laborales justas. Asimismo, el 100% muestra interés en herramientas tecnológicas como códigos QR o aplicaciones, que permitan verificar la procedencia, pureza y legalidad del producto antes de la compra.

![Chart 4](../assets/img/chapter-ii/chart-4.png)


## 2.3. Needfinding
Para llevar a cabo el proceso de needfinding en GoldCheck, se realizaron entrevistas en profundidad con usuarios pertenecientes a los segmentos objetivo, incluyendo consumidores finales, joyeros y profesionales del sector minero. Estas conversaciones se centraron en comprender sus hábitos, objetivos y principales frustraciones relacionadas con la autenticidad, trazabilidad y confianza en la comercialización de joyas y minerales.

Gracias a esta exploración, se identificaron áreas críticas de mejora, como la falta de transparencia en el origen de los materiales, la baja confianza en los productos adquiridos y la limitada adopción de herramientas digitales en los procesos del sector minero. Asimismo, se evidenció la existencia de brechas tanto tecnológicas como informativas que afectan la toma de decisiones de los usuarios. Durante las entrevistas, surgieron patrones y necesidades recurrentes, como la importancia de contar con un sistema confiable que permita verificar la autenticidad, procedencia y valor real de los productos. De esta manera, se logra identificar una oportunidad clara para desarrollar una solución como GoldCheck, que facilite el acceso a información validada y mejore la confianza en la cadena de valor.

### 2.3.1. User Personas


**Segmento Objetivo: Empresas mineras:**
![User-Persona-i](../assets/img/chapter-ii/UserPersona-1.png)

<div style="page-break-after: always"></div>

**Segmento Objetivo: Joyerías:**
![User-Persona-ii](../assets/img/chapter-ii/UserPersona-2.png)

<div style="page-break-after: always"></div>

**Segmento Objetivo: Consumidor final:**
![User-Persona-iii](../assets/img/chapter-ii/UserPersona-3.png)

### 2.3.2. User Task Matrix
<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; text-align: center;">
  
  <!-- Main header -->
  <tr style="background-color:#f2f2f2;">
    <th rowspan="2">Task</th>
    <th colspan="2">Leonardo Gonzales (Mining Engineer)</th>
    <th colspan="2">Elena Rosas (Jewelry Business Owner)</th>
    <th colspan="2">Pilar Chavez (Final Consumer)</th>
  </tr>

  <!-- Sub header -->
  <tr style="background-color:#f2f2f2;">
    <th>Frequency</th>
    <th>Importance</th>
    <th>Frequency</th>
    <th>Importance</th>
    <th>Frequency</th>
    <th>Importance</th>
  </tr>

  <!-- Rows -->
  <tr>
    <td>Verify material authenticity</td>
    <td>Medium</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
  </tr>

  <tr>
    <td>Evaluate material quality/purity</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>Medium</td>
    <td>High</td>
  </tr>

  <tr>
    <td>Record material data (origin, quantity)</td>
    <td>High</td>
    <td>High</td>
    <td>Medium</td>
    <td>High</td>
    <td>Low</td>
    <td>Medium</td>
  </tr>

  <tr>
    <td>Monitor material transportation</td>
    <td>High</td>
    <td>High</td>
    <td>Low</td>
    <td>Medium</td>
    <td>Low</td>
    <td>Low</td>
  </tr>

  <tr>
    <td>Search for information before purchasing</td>
    <td>Low</td>
    <td>Medium</td>
    <td>Medium</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
  </tr>

  <tr>
    <td>Trust suppliers / sellers</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
  </tr>

  <tr>
    <td>Manage inventory or stock</td>
    <td>Medium</td>
    <td>Medium</td>
    <td>High</td>
    <td>High</td>
    <td>Low</td>
    <td>Low</td>
  </tr>

  <tr>
    <td>Detect errors or failures</td>
    <td>High</td>
    <td>High</td>
    <td>Medium</td>
    <td>High</td>
    <td>Low</td>
    <td>Medium</td>
  </tr>

  <tr>
    <td>Communicate information</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>Medium</td>
    <td>Medium</td>
  </tr>

  <tr>
    <td>Evaluate price vs quality</td>
    <td>Medium</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
  </tr>

  <tr>
    <td>Verify ethical origin</td>
    <td>Medium</td>
    <td>High</td>
    <td>Medium</td>
    <td>High</td>
    <td>High</td>
    <td>High</td>
  </tr>

</table>

<div style="page-break-after: always"></div>

### 2.3.3. User Journey Mapping

**Segmento Objetivo Empresas mineras:**
![User-JourneyMap-i](../assets/img/chapter-ii/JourneyMap-1.png)

<div style="page-break-after: always"></div>

**Segmento Objetivo Joyerías:**
![User-JourneyMap-ii](../assets/img/chapter-ii/JourneyMap-2.png)

<div style="page-break-after: always"></div>

**Segmento Objetivo Consumidor final:**
![User-JourneyMap-iii](../assets/img/chapter-ii/JourneyMap-3.png)

### 2.3.4. Empathy Mapping
**Segmento Objetivo Empresas mineras:**
![EmpathyMap-i](../assets/img/chapter-ii/EmpathyMap-1.png)

<div style="page-break-after: always"></div>

**Segmento Objetivo Joyerías:**
![EmpathyMap-ii](../assets/img/chapter-ii/EmpathyMap-2.png)

<div style="page-break-after: always"></div>

**Segmento Objetivo Consumidor final:**
![EmpathyMap-iii](../assets/img/chapter-ii/EmpathyMap-3.png)

## 2.4. Big Picture EventStorming
En la sesión de Big Picture Event Storming, el equipo exploró de forma visual el panorama general del dominio de telemetría en minería y trazabilidad de la cadena de valor para joyería de GoldMetrics. Se identificaron los eventos significativos del ciclo de vida de un activo monitoreado, desde el registro de la maquinaria hasta la respuesta ante incidentes críticos, integrando los sistemas externos que interactúan con la plataforma y exponiendo los problemas, dudas y oportunidades de mejora detectados durante la sesión. Esta primera aproximación permitió alinear el entendimiento del equipo y sentar las bases para el diseño detallado de la solución.

**Primera fase: Eventos**
![Big picture eevent storming](../assets/img/event-storming-events.png)

**Mapa general:**
https://canva.link/yc2kttn17z9hf75

## 2.5. Ubiquitous Language
- **Machinery (Maquinaria)**: Cualquier unidad de equipo físico en la mina, como camiones de acarreo, palas o excavadoras, que genera datos y requiere monitoreo.

- **Haul Truck (Camión de acarreo)**: Vehículo pesado diseñado específicamente para transportar grandes volúmenes de material desde el punto de carga hasta el de descarga.

- **Fleet (Flota)**: Conjunto total de activos móviles que operan dentro de una unidad minera.

- **OEM - Original Equipment Manufacturer (Fabricante de Equipo Original)**: Empresas que fabrican la maquinaria (ej. Caterpillar, Komatsu). Sus sistemas de datos suelen ser cerrados o propietarios.

- **Haulage (Acarreo)**: El proceso de transportar material extraído desde el tajo (pit) hacia su destino (chancadora o botadero).

- **Cycle Time (Tiempo de ciclo)**: Tiempo total que tarda un activo en completar una secuencia completa: carga, transporte de ida, descarga y retorno vacío.

- **Loading Point (Punto de carga):** Ubicación específica en la mina donde el material es depositado en el camión por una pala o cargador.

- **Dumping Point / Dump (Punto de descarga / Botadero):** Destino final del material, ya sea para procesamiento (mineral) o almacenamiento (estéril).

- **Payload (Carga útil):** El peso real del material transportado por un activo en un solo ciclo, excluyendo el peso del vehículo.

- **Idle Time (Tiempo en ralentí):** Periodo en el que el motor del activo está encendido pero el vehículo no está realizando trabajo productivo ni desplazándose.

- **Downtime (Tiempo de inactividad):** Tiempo durante el cual un activo no está disponible para operar, ya sea por fallas mecánicas o mantenimiento programado.

- **Availability (Disponibilidad)**: Porcentaje de tiempo que un activo está en condiciones mecánicas para operar, independientemente de si se está usando o no.

- **Utilization (Utilización):** Proporción del tiempo de disponibilidad en el que el activo realmente está realizando tareas operativas.

- **Production (Producción):** Cantidad total de material (usualmente medido en toneladas) movido durante un periodo determinado.

- **Ore (Mineral):** Roca que contiene sustancias económicamente valiosas (oro, cobre, etc.) y que se envía a la planta de procesamiento.

- **Waste / Overburden (Estéril / Lastre):** Material que debe ser removido para acceder al mineral pero que no tiene valor económico. Se envía a los botaderos.

- **Grade (Ley):** La concentración de metal valioso contenido en el mineral extraído.

- **Telemetry (Telemetría):** Medición y transmisión inalámbrica de datos desde los sensores del activo (motor, GPS, peso) hacia la plataforma.

- **Fuel Consumption (Consumo de combustible):** Cantidad de combustible diesel utilizado por un activo, analizado generalmente por hora o por tonelada movida.

- **Engine Hours (Horas motor):** Tiempo acumulado de funcionamiento del motor de un activo, utilizado como base para los planes de mantenimiento.

- **Event (Evento):** Una ocurrencia específica detectada por los sensores que tiene relevancia operativa (ej. exceso de velocidad, fatiga del operador).

- **ESG - Environmental, Social, and Governance (Criterios ambientales, sociales y de gobernanza):** Marco de evaluación de la sostenibilidad y el impacto ético de la operación minera.

- **Traceability (Trazabilidad):** Capacidad de seguir el historial, la ubicación y la procedencia de un lote de mineral desde la mina hasta su destino final.

- **Engine Ignition (Encendido del motor):** Estado que indica que el motor principal del activo está operativo y consumiendo combustible

- **Communication loss (Pérdida de comunicación):** Falla en el flujo de datos entre los sensores del activo y la plataforma de monitoreo.

- **Exhaust Temperature (Temperatura de escape):** Indicador térmico de los gases de salida del motor, clave para prevenir daños mecánicos catastróficos.

- **Dossification Rail (Riel de dosificación):** Sistema encargado de la distribución precisa de combustible o aditivos en el motor.

- **Oil Pan (Cárter de aceite):** Depósito metálico que contiene el aceite lubricante del motor.

- **GNSS (Sistema Global de Navegación por Satélite):** Tecnología (como el GPS) utilizada para rastrear la ubicación y velocidad del activo en tiempo real.

- **Oil Filter pressure difference (Diferencial de presión del filtro de aceite):** Medida que indica el nivel de obstrucción del filtro; una diferencia alta sugiere la necesidad de cambio inmediato.

- **Fatigue event (Evento de fatiga):** Alerta generada cual el sistema detecta signos de cansancio o falta de atención en el operador.

- **Operator (Operador):** Persona responsable de la conducción y operación directa de una Machinery (Maquinaria) durante un turno. Es el principal generador de eventos como Speed excess o Fatigue events.

- **Supervisor (Supervisor):** Usuario con privilegios de gestión encargado de monitorear el desempeño de la flota, validar reportes y reaccionar ante alertas críticas o Accidents.

- **User (Usuario):** Término genérico para cualquier persona con credenciales de acceso al sistema, cuyo historial de Login y Registration es auditado por la plataforma.

- **Component (Componente):** Parte o sistema específico de un activo (ej. motor, transmisión, bomba hidráulica) que puede ser monitoreado o reemplazado de forma independiente.

- **Component Discharged (Componente dado de baja):** Estado que indica que una pieza ha sido retirada de un activo para su reemplazo o desecho.

- **Refinery (Refinería):** Instalación industrial donde el mineral procesado se purifica para obtener metal precioso (oro/plata) con grado de inversión o joyería.

- **Jeweler (Joyero):** El artesano o empresa final que transforma el metal precioso en piezas de joyería. En GoldMetrics, el joyero es un stakeholder interesado en la procedencia ética del material.

- **Ethical Gold (Oro Ético)**: Oro extraído bajo estándares que garantizan el respeto a los derechos humanos y el cumplimiento de normativas ambientales (ESG), un factor clave en la trazabilidad de la plataforma.

- **Bullion (Lingote / Metal en bruto):** Forma física del metal precioso (usualmente con 99.9% de pureza) antes de ser trabajado por un joyero.

- **Conflict-Free Certification (Certificación Libre de Conflicto):** Validación documental que asegura que el oro no proviene de zonas de guerra o financia actividades ilícitas, vinculada directamente al reporte de Traceability.

- **Dossification Rail Pressure (Presión del Riel de Dosificación):** Presión del sistema de inyección; niveles altos o bajos pueden indicar fallas inminentes.

- **Oil Filter Pressure Difference (Diferencial de Presión del Filtro de Aceite):** Diferencia entre la presión de entrada y salida del filtro, indicando qué tan obstruido está.

- **Durability (Durabilidad):** Capacidad de un Machinery o Component de mantener su función operativa bajo las condiciones extremas de la mina sin fallar.

- **PCR - Planned Component Replacement (Reemplazo Planificado de Componentes:)** Es el tiempo mínimo u óptimo de operación (medido en horas motor) que un componente debe durar antes de ser retirado de servicio para evitar fallas.

- **Preventive Maintenance (Mantenimiento Preventivo):** Tareas de servicio programadas basadas en el tiempo de operación para asegurar la longevidad del equipo.

# Capítulo III: Requirements Specification

</div>

---

### 3.1. User Stories

En esta sección se detallan los requisitos del producto digital GoldMetrics a través de 9 Epics y 45 User Stories (40 funcionales y 5 técnicas). Para cada historia se han definido dos escenarios de aceptación (un flujo principal y un flujo alternativo/excepción).


| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|:---------------:|:------:|:------------|:------------------------|:-------------------------:|
| **EP01** | **Landing Page y Captación** | Funcionalidades del sitio web estático para presentar el modelo de negocio e informar a los segmentos. | — | — |
| US01 | Visualización de Hero Section | Como visitante, deseo visualizar la propuesta de valor principal, para entender rápidamente qué ofrece GoldMetrics. | **Scenario 1:** Carga inicial <br> **Given** el visitante ingresa al dominio <br> **When** la página carga <br> **Then** el sistema muestra el mensaje principal y los llamados a la acción.<br><br>**Scenario 2:** Interacción con llamado a la acción <br> **Given** el visitante visualiza la sección principal <br> **When** acciona el botón de registro <br> **Then** el sistema redirige al formulario de creación de cuenta B2B. | EP01 |
| US02 | Visualización de Planes | Como visitante, deseo ver los planes de suscripción, para evaluar el costo-beneficio del servicio. | **Scenario 1:** Consulta de planes <br> **Given** el visitante navega por el sitio <br> **When** accede a la sección de precios <br> **Then** el sistema detalla las características de los planes B2B.<br><br>**Scenario 2:** Cambio de facturación <br> **Given** el visitante visualiza los planes <br> **When** cambia el selector a facturación anual <br> **Then** el sistema recalcula y muestra los precios con descuento aplicado. | EP01 |
| US03 | Formulario de Contacto B2B | Como visitante de empresa, deseo enviar mis datos de contacto, para solicitar una demostración del sistema. | **Scenario 1:** Envío exitoso <br> **Given** el visitante llena todos los campos obligatorios <br> **When** envía el formulario <br> **Then** el sistema registra el prospecto y envía un correo de confirmación.<br><br>**Scenario 2:** Campos incompletos <br> **Given** el visitante omite el correo corporativo <br> **When** intenta enviar el formulario <br> **Then** el sistema retiene el envío y muestra una alerta de validación. | EP01 |
| US04 | Visualización de Casos de Éxito | Como visitante, deseo leer testimonios de joyerías y mineras, para confiar en la efectividad de la plataforma. | **Scenario 1:** Lectura de testimonios <br> **Given** el visitante está en el home <br> **When** se desplaza a la sección de casos de éxito <br> **Then** el sistema muestra las reseñas principales.<br><br>**Scenario 2:** Navegación por testimonios <br> **Given** el visitante visualiza las reseñas <br> **When** acciona los controles de navegación <br> **Then** el sistema rota la vista mostrando testimonios adicionales. | EP01 |
| US05 | Redirección a Web App | Como visitante registrado, deseo acceder al portal de la aplicación, para iniciar sesión en mi cuenta. | **Scenario 1:** Acceso a login <br> **Given** el visitante se encuentra en el landing page <br> **When** selecciona la opción de ingresar <br> **Then** el sistema lo redirige a la vista de autenticación.<br><br>**Scenario 2:** Sesión ya activa <br> **Given** el visitante tiene una sesión guardada en el navegador <br> **When** selecciona la opción de ingresar <br> **Then** el sistema lo redirige directamente a su dashboard. | EP01 |
| **EP02** | **Autenticación y Perfiles** | Gestión de acceso, roles y configuración de cuentas para los diferentes actores B2B. | — | — |
| US06 | Registro de Empresa Minera | Como administrador minero, deseo registrar mi empresa, para obtener acceso al sistema de trazabilidad. | **Scenario 1:** Registro exitoso <br> **Given** el usuario ingresa datos corporativos válidos <br> **When** confirma el registro <br> **Then** el sistema crea la cuenta en estado pendiente.<br><br>**Scenario 2:** Documento duplicado <br> **Given** el usuario ingresa un RUC previamente registrado <br> **When** confirma el registro <br> **Then** el sistema rechaza la solicitud indicando la duplicidad. | EP02 |
| US07 | Registro de Joyería | Como dueño de joyería, deseo registrar mi negocio, para poder certificar mis joyas. | **Scenario 1:** Registro exitoso <br> **Given** el usuario ingresa datos comerciales válidos <br> **When** confirma el registro <br> **Then** el sistema crea la cuenta con rol "Joyería".<br><br>**Scenario 2:** Formato de correo inválido <br> **Given** el usuario ingresa un correo sin formato estándar <br> **When** intenta avanzar <br> **Then** el sistema deshabilita la acción y solicita corrección. | EP02 |
| US08 | Inicio de Sesión | Como usuario registrado, deseo autenticarme, para acceder a mi panel de control. | **Scenario 1:** Login correcto <br> **Given** el usuario tiene credenciales válidas <br> **When** ingresa su correo y contraseña <br> **Then** el sistema valida y redirige al dashboard.<br><br>**Scenario 2:** Credenciales incorrectas <br> **Given** el usuario ingresa una contraseña errónea <br> **When** intenta iniciar sesión <br> **Then** el sistema deniega el acceso y alerta sobre el error. | EP02 |
| US09 | Recuperación de Contraseña | Como usuario registrado, deseo recuperar mi contraseña, para recuperar el acceso si la olvido. | **Scenario 1:** Envío de token <br> **Given** el usuario ingresa su correo registrado <br> **When** solicita el restablecimiento <br> **Then** el sistema envía un enlace de recuperación.<br><br>**Scenario 2:** Correo no registrado <br> **Given** el usuario ingresa un correo inexistente en la base de datos <br> **When** solicita el restablecimiento <br> **Then** el sistema no envía correo pero muestra un mensaje genérico por seguridad. | EP02 |
| US10 | Gestión de Perfil Corporativo | Como administrador de empresa, deseo actualizar la información de mi negocio, para mantener los datos de contacto al día. | **Scenario 1:** Actualización de datos <br> **Given** el administrador está autenticado <br> **When** modifica la dirección comercial <br> **Then** el sistema guarda los cambios y actualiza el perfil.<br><br>**Scenario 2:** Intento de eliminar dato obligatorio <br> **Given** el administrador está autenticado <br> **When** intenta dejar el campo de teléfono vacío <br> **Then** el sistema bloquea el guardado. | EP02 |
| **EP03** | **Gestión de Extracción (Mineras)** | Funcionalidades operativas para registrar el origen geográfico, lotes y pesajes iniciales del mineral. | — | — |
| US11 | Registro de Yacimiento | Como ingeniero de mina, deseo registrar la ubicación de un yacimiento, para establecer el punto de origen del mineral. | **Scenario 1:** Creación de yacimiento <br> **Given** el ingeniero ingresa coordenadas GPS <br> **When** guarda el registro <br> **Then** el sistema asigna un identificador único al yacimiento.<br><br>**Scenario 2:** Coordenadas inválidas <br> **Given** el ingeniero ingresa valores fuera del rango geográfico (-90 a 90) <br> **When** intenta guardar <br> **Then** el sistema marca el error y exige valores reales. | EP03 |
| US12 | Registro de Volquetes | Como supervisor logístico, deseo registrar los vehículos de carga, para asociarlos a los traslados de mineral. | **Scenario 1:** Alta de vehículo <br> **Given** el supervisor ingresa placa y capacidad <br> **When** confirma el alta <br> **Then** el sistema añade el volquete al catálogo.<br><br>**Scenario 2:** Placa duplicada <br> **Given** el supervisor ingresa una placa existente <br> **When** confirma el alta <br> **Then** el sistema alerta sobre la colisión de datos. | EP03 |
| US13 | Creación de Lote (Batch) | Como supervisor de extracción, deseo generar un código de lote, para identificar un conjunto de mineral extraído. | **Scenario 1:** Generación de ID <br> **Given** el supervisor selecciona el yacimiento <br> **When** solicita crear un lote <br> **Then** el sistema genera un código alfanumérico único.<br><br>**Scenario 2:** Falta de permisos <br> **Given** un usuario con rol "Consultor" <br> **When** intenta crear un lote <br> **Then** el sistema deniega la acción por falta de privilegios. | EP03 |
| US14 | Registro de Pesaje Inicial | Como operador de balanza, deseo registrar el peso del volquete cargado, para establecer el tonelaje inicial del lote. | **Scenario 1:** Pesaje guardado <br> **Given** el operador vincula un volquete a un lote <br> **When** ingresa el peso bruto <br> **Then** el sistema asocia el peso inicial al lote.<br><br>**Scenario 2:** Exceso de capacidad <br> **Given** el operador vincula un volquete <br> **When** ingresa un peso que excede la capacidad técnica del vehículo <br> **Then** el sistema emite una alerta preventiva. | EP03 |
| US15 | Asignación de Responsables | Como supervisor de mina, deseo asignar un conductor a un lote, para mantener un registro de custodia. | **Scenario 1:** Asignación de custodia <br> **Given** un lote creado <br> **When** el supervisor vincula a un conductor disponible <br> **Then** el sistema registra la custodia.<br><br>**Scenario 2:** Conductor ocupado <br> **Given** un lote creado <br> **When** intenta asignar a un conductor con un viaje activo <br> **Then** el sistema rechaza la asignación. | EP03 |
| US16 | Tipificación de Mineral | Como ingeniero metalurgista, deseo clasificar el tipo de mineral del lote, para mantener el control de calidad. | **Scenario 1:** Asignación de tipo <br> **Given** un lote en estado inicial <br> **When** el ingeniero selecciona oro <br> **Then** el sistema actualiza los metadatos del lote.<br><br>**Scenario 2:** Modificación tardía <br> **Given** un lote que ya inició su ruta de transporte <br> **When** intenta cambiar el tipo de mineral <br> **Then** el sistema bloquea la edición. | EP03 |
| **EP04** | **Trazabilidad y Transporte** | Monitoreo del desplazamiento del mineral desde la mina hasta la planta procesadora o punto de venta. | — | — |
| US17 | Inicio de Ruta | Como conductor, deseo marcar el inicio del traslado, para activar el monitoreo del lote. | **Scenario 1:** Ruta iniciada <br> **Given** el conductor tiene un lote asignado <br> **When** confirma la salida <br> **Then** el sistema cambia el estado a "En Tránsito".<br><br>**Scenario 2:** Inicio sin pesaje <br> **Given** un lote asignado que carece de registro de peso <br> **When** el conductor intenta iniciar ruta <br> **Then** el sistema impide la salida hasta completar los datos. | EP04 |
| US18 | Registro de Checkpoints | Como supervisor logístico, deseo que el sistema registre puntos de control, para verificar que el camión sigue la ruta. | **Scenario 1:** Paso por checkpoint <br> **Given** un lote "En Tránsito" <br> **When** las coordenadas del vehículo coinciden con un control <br> **Then** el sistema guarda el registro.<br><br>**Scenario 2:** Desconexión temporal <br> **Given** un vehículo pierde señal en ruta <br> **When** recupera la conexión <br> **Then** el sistema sincroniza los checkpoints locales almacenados. | EP04 |
| US19 | Alerta de Retraso o Desvío | Como ingeniero de operaciones, deseo recibir alertas automáticas, para tomar acción si un volquete se detiene irregularmente. | **Scenario 1:** Retraso detectado <br> **Given** un vehículo "En Tránsito" <br> **When** supera el tiempo límite entre controles <br> **Then** el sistema genera una alerta visual.<br><br>**Scenario 2:** Desvío de ruta <br> **Given** un vehículo "En Tránsito" <br> **When** sus coordenadas salen del polígono geográfico permitido <br> **Then** el sistema envía una notificación crítica. | EP04 |
| US20 | Confirmación de Llegada | Como operador de planta, deseo marcar la recepción del vehículo, para finalizar la etapa de transporte. | **Scenario 1:** Llegada confirmada <br> **Given** el operador ingresa el código del lote <br> **When** confirma la recepción <br> **Then** el estado cambia a "En Planta".<br><br>**Scenario 2:** Falsa ubicación <br> **Given** el operador intenta confirmar recepción <br> **When** el GPS del vehículo no está dentro de la geocerca de la planta <br> **Then** el sistema bloquea la confirmación. | EP04 |
| US21 | Pesaje Final (Recepción) | Como operador de balanza en planta, deseo registrar el peso de llegada, para calcular discrepancias. | **Scenario 1:** Pesaje de destino <br> **Given** un lote "En Planta" <br> **When** se ingresa el peso final <br> **Then** el sistema registra el dato para su cálculo.<br><br>**Scenario 2:** Peso excedente <br> **Given** un lote "En Planta" <br> **When** el peso ingresado es mayor al peso inicial de mina <br> **Then** el sistema marca un posible error de calibración. | EP04 |
| US22 | Cálculo Automático de Merma | Como ingeniero metalurgista, deseo que el sistema calcule la pérdida de material, para identificar ineficiencias o robos. | **Scenario 1:** Diferencia normal <br> **Given** un lote con pesos inicial y final registrados <br> **When** se procesa la información <br> **Then** el sistema muestra la diferencia porcentual.<br><br>**Scenario 2:** Merma crítica <br> **Given** un lote procesado <br> **When** la merma supera el 5% <br> **Then** el sistema marca el lote en estado "Bajo Investigación". | EP04 |
| **EP05** | **Certificación (Joyerías)** | Procesos para que las joyerías validen el oro adquirido y emitan certificados para el consumidor. | — | — |
| US23 | Verificación de Lote Comprado | Como dueño de joyería, deseo ingresar el código del proveedor, para asegurar que el oro proviene de una mina legal. | **Scenario 1:** Lote validado <br> **Given** el dueño ingresa un código GoldMetrics <br> **When** ejecuta la búsqueda <br> **Then** el sistema muestra la ruta de origen.<br><br>**Scenario 2:** Código inexistente <br> **Given** el dueño ingresa un código falso o erróneo <br> **When** ejecuta la búsqueda <br> **Then** el sistema indica que el lote no es válido. | EP05 |
| US24 | Registro de Prueba de Pureza | Como orfebre, deseo registrar el resultado de mis pruebas físicas, para consolidar la calidad del material. | **Scenario 1:** Registro de pureza <br> **Given** un lote de oro en inventario <br> **When** el orfebre ingresa los quilates verificados <br> **Then** el sistema actualiza la pureza.<br><br>**Scenario 2:** Discrepancia de proveedor <br> **Given** un lote declarado por el proveedor como 24k <br> **When** el orfebre registra 18k <br> **Then** el sistema genera una alerta de discrepancia comercial. | EP05 |
| US25 | Subdivisión de Lote | Como orfebre, deseo dividir un lote de oro en varias piezas individuales, para asignar trazabilidad a cada joya creada. | **Scenario 1:** División exitosa <br> **Given** un lote de 100g <br> **When** se crean piezas hijas de 20g <br> **Then** el sistema genera sub-códigos vinculados.<br><br>**Scenario 2:** Exceso de masa <br> **Given** un lote de 100g <br> **When** se intenta crear piezas que sumen 120g <br> **Then** el sistema bloquea la creación por inconsistencia física. | EP05 |
| US26 | Generación de Código QR | Como dueño de joyería, deseo generar un código QR por joya, para adjuntarlo a la etiqueta del producto. | **Scenario 1:** QR generado <br> **Given** una joya registrada <br> **When** se solicita el QR <br> **Then** el sistema emite una imagen escaneable.<br><br>**Scenario 2:** Sin validación <br> **Given** una joya cuyo lote no tiene pureza confirmada <br> **When** se intenta generar QR <br> **Then** el sistema lo impide hasta que el orfebre valide la pureza. | EP05 |
| US27 | Exportación de Certificado PDF | Como secretaria de joyería, deseo exportar el certificado de autenticidad en PDF, para imprimirlo y entregarlo al cliente. | **Scenario 1:** Descarga exitosa <br> **Given** una joya con trazabilidad completa <br> **When** se solicita exportación <br> **Then** el sistema genera el archivo PDF.<br><br>**Scenario 2:** Datos incompletos <br> **Given** una joya sin fotografía o descripción asignada <br> **When** se solicita exportación <br> **Then** el sistema pide completar los campos antes de generar el PDF. | EP05 |
| US28 | Marcado de Joya Vendida | Como secretaria de joyería, deseo marcar una joya como "Vendida", para retirar el stock del sistema activo. | **Scenario 1:** Cambio de estado <br> **Given** una joya en "Venta" <br> **When** se confirma transacción <br> **Then** el sistema la pasa a "Vendida".<br><br>**Scenario 2:** Doble venta <br> **Given** una joya ya catalogada como "Vendida" <br> **When** se intenta cambiar su estado nuevamente a vendida <br> **Then** el sistema deshabilita el botón de acción. | EP05 |
| **EP06** | **Oro Reciclado (Material del Cliente)** | Casos específicos donde la joyería trabaja con material proporcionado por el consumidor final. | — | — |
| US29 | Ingreso de Material de Cliente | Como dueño de joyería, deseo registrar el oro traído por un cliente, para mantenerlo separado del oro de proveedores. | **Scenario 1:** Alta manual <br> **Given** un registro iniciado <br> **When** se clasifica como "Oro de Cliente" y se ingresa peso <br> **Then** el sistema crea el lote sin historial minero.<br><br>**Scenario 2:** Alta sin masa <br> **Given** un registro iniciado <br> **When** no se declara un peso inicial <br> **Then** el sistema bloquea la creación del lote. | EP06 |
| US30 | Registro de Merma por Refinamiento | Como orfebre, deseo registrar la pérdida de peso tras purificar el oro del cliente, para justificar la reducción de gramos. | **Scenario 1:** Cálculo de pérdida <br> **Given** un lote "Oro de Cliente" <br> **When** se ingresa el peso post-refinamiento <br> **Then** el sistema calcula la merma exacta.<br><br>**Scenario 2:** Peso ilógico <br> **Given** un lote a refinar <br> **When** se ingresa un peso resultante mayor al inicial <br> **Then** el sistema rechaza el valor por inconsistencia matemática. | EP06 |
| US31 | Emisión de Reporte de Refinamiento | Como dueña de joyería, deseo generar un reporte detallado del refinamiento, para explicarle al cliente de forma transparente por qué su oro disminuyó en peso. | **Scenario 1:** Reporte emitido <br> **Given** un lote cliente ya refinado <br> **When** se pide reporte <br> **Then** el sistema detalla peso bruto, merma y peso neto.<br><br>**Scenario 2:** Refinamiento cancelado <br> **Given** un lote cuyo proceso fue anulado <br> **When** se intenta generar reporte <br> **Then** el sistema indica que no hay datos de refinamiento. | EP06 |
| US32 | Asignación de QR a Oro Reciclado | Como orfebre, deseo emitir un QR que indique "Oro Reciclado", para diferenciarlo del oro de mina directa. | **Scenario 1:** QR Reciclado <br> **Given** una joya derivada de lote cliente <br> **When** se genera el QR <br> **Then** la interfaz pública resalta su condición de material reciclado.<br><br>**Scenario 2:** Intento de ocultamiento <br> **Given** la configuración de una joya reciclada <br> **When** se intenta cambiar su origen manualmente a "Mina" <br> **Then** el sistema bloquea la alteración del origen raíz. | EP06 |
| **EP07** | **Transparencia para el Consumidor** | Interfaces públicas y funcionalidades dirigidas a la validación de joyas por parte del usuario final. | — | — |
| US33 | Escaneo de QR | Como consumidor final, deseo escanear el QR con mi celular, para verificar la autenticidad de la joya antes de comprarla. | **Scenario 1:** Escaneo válido <br> **Given** el consumidor usa su cámara <br> **When** lee el QR <br> **Then** el sistema abre la vista pública de la joya.<br><br>**Scenario 2:** Joya reportada <br> **Given** un QR escaneado <br> **When** el registro interno marca la joya como "Robada" <br> **Then** el sistema oculta los datos y muestra una advertencia de seguridad. | EP07 |
| US34 | Visualización de Hoja de Vida | Como consumidor final, deseo ver la mina de origen, tipo de mineral y pureza, para asegurarme de que no proviene de minería ilegal. | **Scenario 1:** Carga completa <br> **Given** la URL de la joya <br> **When** carga exitosamente <br> **Then** el sistema despliega el mapa, fechas y metadatos.<br><br>**Scenario 2:** Conexión intermitente <br> **Given** el consumidor tiene baja señal <br> **When** accede a la URL <br> **Then** el sistema muestra esqueletos de carga priorizando los datos de texto sobre el mapa. | EP07 |
| US35 | Validación del Vendedor | Como consumidor final, deseo ver el nombre y credenciales de la joyería, para confirmar que estoy comprando en un comercio autorizado. | **Scenario 1:** Vendedor verificado <br> **Given** la vista de trazabilidad <br> **When** el usuario baja a la sección comercial <br> **Then** se muestra la insignia de socio autorizado.<br><br>**Scenario 2:** Membresía expirada <br> **Given** la misma vista <br> **When** la joyería tiene deuda o suspensión en GoldMetrics <br> **Then** la insignia de autorización no se despliega. | EP07 |
| US36 | Reporte de Irregularidad | Como consumidor final, deseo reportar un código QR sospechoso, para alertar sobre posibles falsificaciones. | **Scenario 1:** Reporte enviado <br> **Given** la vista de trazabilidad <br> **When** el usuario emite un reporte argumentado <br> **Then** el sistema lo encola para revisión administrativa.<br><br>**Scenario 2:** Prevención de Spam <br> **Given** un dispositivo emitiendo alertas <br> **When** supera 3 reportes en 5 minutos <br> **Then** el sistema limita temporalmente la capacidad de enviar reportes (Rate Limit). | EP07 |
| US37 | Compartir Trazabilidad | Como consumidor final, deseo compartir el enlace de trazabilidad de mi joya, para demostrar su autenticidad a terceros. | **Scenario 1:** Copiar enlace <br> **Given** la vista de trazabilidad <br> **When** el usuario acciona el botón "Copiar" <br> **Then** el sistema guarda la URL en el portapapeles.<br><br>**Scenario 2:** Compartir en red social <br> **Given** la misma vista <br> **When** selecciona el ícono de WhatsApp <br> **Then** el sistema abre la aplicación con un texto predefinido y el link. | EP07 |
| **EP08** | **Analítica y Dashboards** | Herramientas de visualización de datos y métricas para la toma de decisiones empresariales. | — | — |
| US38 | Dashboard Minero - Merma Global | Como administrador minero, deseo visualizar un gráfico de mermas mensuales, para identificar si existen problemas sistémicos de robo o ineficiencia. | **Scenario 1:** Renderizado de gráfico <br> **Given** el usuario ingresa a métricas <br> **When** filtra por un mes con datos <br> **Then** el sistema dibuja un gráfico de barras comparativo.<br><br>**Scenario 2:** Estado vacío <br> **Given** el usuario ingresa a métricas <br> **When** filtra por un mes sin operaciones <br> **Then** el sistema muestra una ilustración amigable indicando que no hay datos. | EP08 |
| US39 | Dashboard Joyería - Volumen Validado | Como dueño de joyería, deseo ver la cantidad total de oro validado en el mes, para llevar control de mis compras a proveedores formales. | **Scenario 1:** Cómputo total <br> **Given** el dashboard de joyería <br> **When** carga inicialmente <br> **Then** el sistema suma y muestra el total de gramos ingresados legalmente.<br><br>**Scenario 2:** Filtro por proveedor <br> **Given** el mismo dashboard <br> **When** se selecciona un proveedor específico en el filtro <br> **Then** el sistema recalcula la métrica para reflejar solo compras a esa entidad. | EP08 |
| US40 | Exportación de Data Histórica | Como ingeniero de operaciones, deseo descargar en Excel el historial de lotes, para realizar análisis estadísticos externos. | **Scenario 1:** Descarga síncrona <br> **Given** una tabla filtrada con 500 lotes <br> **When** se solicita exportación <br> **Then** el sistema entrega un archivo CSV de descarga inmediata.<br><br>**Scenario 2:** Exportación masiva <br> **Given** una tabla con más de 10,000 registros <br> **When** se solicita exportación <br> **Then** el sistema notifica que el archivo pesado se procesará en segundo plano y será enviado por correo. | EP08 |
| **EP09** | **GoldMetrics API (Technical Stories)** | Endpoints técnicos para la integración del backend (ASP.NET Core) con Frontend y hardware IoT. | — | — |
| TS01 | Endpoint de Creación de Lotes | Como Developer, deseo un endpoint POST para registrar nuevos lotes, para permitir la comunicación asíncrona desde sistemas externos. | **Scenario 1:** Solicitud correcta <br> **Given** un payload JSON válido con Token <br> **When** se llama a POST `/api/v1/batches` <br> **Then** el servidor retorna HTTP 201 Created.<br><br>**Scenario 2:** Solicitud no autorizada <br> **Given** un payload válido pero sin Token en el header <br> **When** se llama al endpoint <br> **Then** el servidor bloquea el acceso con HTTP 401 Unauthorized. | EP09 |
| TS02 | Endpoint de Recepción IoT (GPS) | Como Developer, deseo un endpoint POST para recibir coordenadas GPS de los camiones, para actualizar el monitoreo de ruta. | **Scenario 1:** Coordenada guardada <br> **Given** un dispositivo IoT enviando su lat/lng <br> **When** se llama a POST `/api/v1/tracking/location` <br> **Then** el servidor almacena el punto y retorna HTTP 200 OK.<br><br>**Scenario 2:** Formato inválido <br> **Given** un payload con strings en lugar de numéricos para lat/lng <br> **When** se llama al endpoint <br> **Then** el servidor rechaza la petición con HTTP 400 Bad Request. | EP09 |
| TS03 | Endpoint de Consulta de Trazabilidad | Como Developer, deseo un endpoint GET público para obtener la hoja de vida de un QR, para que la web app consulte los datos del consumidor. | **Scenario 1:** Consulta exitosa <br> **Given** un ID de joya existente <br> **When** se llama a GET `/api/v1/traceability/{id}` <br> **Then** el servidor retorna HTTP 200 OK y el JSON con el árbol del lote.<br><br>**Scenario 2:** Recurso inexistente <br> **Given** un ID que no figura en la base de datos <br> **When** se llama al endpoint <br> **Then** el servidor retorna HTTP 404 Not Found. | EP09 |
| TS04 | Endpoint de Recepción IoT (Balanza) | Como Developer, deseo un endpoint POST para automatizar la recepción de pesos desde balanzas digitales, para reducir errores de ingreso manual. | **Scenario 1:** Peso acoplado <br> **Given** una balanza enviando un dato en kg/toneladas <br> **When** se llama a POST `/api/v1/iot/weight` <br> **Then** el servidor vincula el peso al ID y retorna HTTP 200 OK.<br><br>**Scenario 2:** Lote inactivo <br> **Given** la petición a un ID de lote ya cerrado o procesado <br> **When** se llama al endpoint <br> **Then** el servidor rechaza la escritura con HTTP 409 Conflict. | EP09 |
| TS05 | Endpoint de Reporte de Mermas | Como Developer, deseo un endpoint GET protegido para consultar agregados de mermas, para alimentar los gráficos del dashboard analítico. | **Scenario 1:** Agrupación válida <br> **Given** parámetros `startDate` y `endDate` válidos <br> **When** se llama a GET `/api/v1/analytics/shrinkage` <br> **Then** el servidor retorna HTTP 200 OK con la data agrupada.<br><br>**Scenario 2:** Fechas invertidas <br> **Given** un parámetro `startDate` mayor al `endDate` <br> **When** se llama al endpoint <br> **Then** el servidor indica el error lógico con HTTP 400 Bad Request. | EP09 |

## 3.2. Impact Mapping

En esta sección se presenta el Impact Mapping elaborado para el modelo de negocio digital de **GoldMetrics**. Este artefacto nos permite alinear visualmente nuestros objetivos estratégicos de negocio con las necesidades de nuestros User Personas y los entregables de software, asegurando que cada funcionalidad construida (User Story) tenga un propósito claro y medible.

![Impact Map](../assets/img/chapter-iii/impact-map.png)

El Impact Mapping elaborado para GoldMetrics ilustra de manera estratégica cómo las funcionalidades de nuestra plataforma tecnológica contribuyen directamente a alcanzar nuestros objetivos comerciales. Para esta fase del proyecto, hemos definido dos objetivos SMART (Business Goals) enfocados tanto en la adopción empresarial (B2B) como en la penetración en el usuario final (B2C).

**Alineación del Business Goal 1 (Adopción B2B):**
Nuestro primer objetivo busca alcanzar la suscripción de 50 empresas formales en el plazo de 12 meses. Para lograr esta meta, hemos identificado a dos actores clave que nos ayudarán a lograrlo: las **Empresas Mineras** y las **Joyerías**.
* En el caso de las mineras, el impacto que necesitamos generar es que digitalicen su control operativo, dejando atrás los formatos manuales en papel para reducir sus mermas. Como negocio digital, provocaremos este impacto construyendo un *Módulo de Gestión de Extracción y Monitoreo IoT* (Deliverable), el cual se materializa en historias de usuario enfocadas en la creación de lotes, registro de pesajes automatizados y monitoreo de rutas de transporte (US13, US14, US18).
* Por el lado de las joyerías, el impacto esperado es que adopten GoldMetrics como su estándar para emitir garantías digitales frente a sus clientes. Para facilitar este comportamiento, implementaremos un *Módulo de Certificación y Generación de QR* (Deliverable), soportado por funcionalidades que permiten validar lotes de proveedores, subdividir material y generar certificados PDF o códigos escaneables (US23, US26, US27).

**Alineación del Business Goal 2 (Alcance B2C):**
El segundo objetivo tiene como meta alcanzar los 5,000 escaneos de trazabilidad en los primeros 6 meses. El actor fundamental aquí es el **Consumidor Final**.
* Para lograr esta meta de escaneos, el impacto o cambio de comportamiento requerido es que el cliente adquiera el hábito de verificar activamente la pureza y el origen ético de la joya antes de su compra. El entregable que proporcionaremos para gatillar este comportamiento es la *Interfaz Web Móvil Pública de Trazabilidad*. Esto se traduce en un conjunto de User Stories diseñadas para brindar transparencia, permitiéndoles escanear el QR, visualizar la informació del mineral desde su extracción, y compartir la autenticidad del producto con terceros (US33, US34, US37).

En conclusión, este mapa evidencia que ninguna funcionalidad de GoldMetrics ha sido ideada al azar; cada User Story propuesta es el eslabón final de una cadena diseñada específicamente para generar valor a nuestros clientes y cumplir las metas financieras y operativas de nuestra startup.

## 3.3. Product Backlog

En esta sección se presenta el Product Backlog del proyecto GoldMetrics, el cual consolida y prioriza todas las historias de usuario y tareas técnicas necesarias para construir la solución. 

El orden de los elementos ha sido estrictamente determinado por el **valor para el negocio**, asegurando que los entregables con mayor impacto (como la captación de clientes y la funcionalidad *core* de trazabilidad) se desarrollen primero. Por este motivo, las historias de usuario relacionadas con el sitio web (Landing Page) encabezan el backlog para ser abordadas desde el primer sprint, mientras que las funcionalidades de soporte (como la autenticación y perfiles) han sido priorizadas posteriormente.

| # Orden | User Story ID | Título | Descripción | Story Points |
|:-------:|:-------------:|:------:|:------------|:------------:|
| 1 | US01 | Visualización de Hero Section | Como visitante, deseo visualizar la propuesta de valor principal, para entender rápidamente qué ofrece GoldMetrics. | 2 |
| 2 | US02 | Visualización de Planes | Como visitante, deseo ver los planes de suscripción, para evaluar el costo-beneficio del servicio. | 3 |
| 3 | US03 | Formulario de Contacto B2B | Como visitante de empresa, deseo enviar mis datos de contacto, para solicitar una demostración del sistema. | 3 |
| 4 | US04 | Visualización de Casos de Éxito | Como visitante, deseo leer testimonios de joyerías y mineras, para confiar en la efectividad de la plataforma. | 2 |
| 5 | US05 | Redirección a Web App | Como visitante registrado, deseo acceder al portal de la aplicación, para iniciar sesión en mi cuenta. | 1 |
| 6 | US13 | Creación de Lote (Batch) | Como supervisor de extracción, deseo generar un código de lote, para identificar un conjunto de mineral extraído. | 3 |
| 7 | TS01 | Endpoint de Creación de Lotes | Como Developer, deseo un endpoint POST para registrar nuevos lotes, para permitir la comunicación asíncrona desde sistemas externos. | 3 |
| 8 | US14 | Registro de Pesaje Inicial | Como operador de balanza, deseo registrar el peso del volquete cargado, para establecer el tonelaje inicial del lote. | 5 |
| 9 | TS04 | Endpoint de Recepción IoT (Balanza) | Como Developer, deseo un endpoint POST para automatizar la recepción de pesos desde balanzas digitales, para reducir errores de ingreso manual. | 5 |
| 10 | US23 | Verificación de Lote Comprado | Como dueño de joyería, deseo ingresar el código del proveedor, para asegurar que el oro proviene de una mina legal. | 5 |
| 11 | US26 | Generación de Código QR | Como dueño de joyería, deseo generar un código QR por joya, para adjuntarlo a la etiqueta del producto. | 3 |
| 12 | US33 | Escaneo de QR | Como consumidor final, deseo escanear el QR con mi celular, para verificar la autenticidad de la joya antes de comprarla. | 3 |
| 13 | US34 | Visualización de Hoja de Vida | Como consumidor final, deseo ver la mina de origen, tipo de mineral y pureza, para asegurarme de que no proviene de minería ilegal. | 5 |
| 14 | TS03 | Endpoint de Consulta de Trazabilidad | Como Developer, deseo un endpoint GET público para obtener la hoja de vida de un QR, para que la web app consulte los datos del consumidor. | 5 |
| 15 | US06 | Registro de Empresa Minera | Como administrador minero, deseo registrar mi empresa, para obtener acceso al sistema de trazabilidad. | 5 |
| 16 | US07 | Registro de Joyería | Como dueño de joyería, deseo registrar mi negocio, para poder certificar mis joyas. | 5 |
| 17 | US08 | Inicio de Sesión | Como usuario registrado, deseo autenticarme, para acceder a mi panel de control. | 3 |
| 18 | US11 | Registro de Yacimiento | Como ingeniero de mina, deseo registrar la ubicación de un yacimiento, para establecer el punto de origen del mineral. | 2 |
| 19 | US12 | Registro de Volquetes | Como supervisor logístico, deseo registrar los vehículos de carga, para asociarlos a los traslados de mineral. | 3 |
| 20 | US15 | Asignación de Responsables | Como supervisor de mina, deseo asignar un conductor a un lote, para mantener un registro de custodia. | 2 |
| 21 | US16 | Tipificación de Mineral | Como ingeniero metalurgista, deseo clasificar el tipo de mineral del lote, para mantener el control de calidad. | 2 |
| 22 | US17 | Inicio de Ruta | Como conductor, deseo marcar el inicio del traslado, para activar el monitoreo del lote. | 3 |
| 23 | US18 | Registro de Checkpoints | Como supervisor logístico, deseo que el sistema registre puntos de control, para verificar que el camión sigue la ruta. | 5 |
| 24 | TS02 | Endpoint de Recepción IoT (GPS) | Como Developer, deseo un endpoint POST para recibir coordenadas GPS de los camiones, para actualizar el monitoreo de ruta. | 5 |
| 25 | US19 | Alerta de Retraso o Desvío | Como ingeniero de operaciones, deseo recibir alertas automáticas, para tomar acción si un volquete se detiene irregularmente. | 8 |
| 26 | US20 | Confirmación de Llegada | Como operador de planta, deseo marcar la recepción del vehículo, para finalizar la etapa de transporte. | 3 |
| 27 | US21 | Pesaje Final (Recepción) | Como operador de balanza en planta, deseo registrar el peso de llegada, para calcular discrepancias. | 3 |
| 28 | US22 | Cálculo Automático de Merma | Como ingeniero metalurgista, deseo que el sistema calcule la pérdida de material, para identificar ineficiencias o robos. | 5 |
| 29 | US24 | Registro de Prueba de Pureza | Como orfebre, deseo registrar el resultado de mis pruebas físicas, para consolidar la calidad del material. | 3 |
| 30 | US25 | Subdivisión de Lote | Como orfebre, deseo dividir un lote de oro en varias piezas individuales, para asignar trazabilidad a cada joya creada. | 8 |
| 31 | US27 | Exportación de Certificado PDF | Como secretaria de joyería, deseo exportar el certificado de autenticidad en PDF, para imprimirlo y entregarlo al cliente. | 5 |
| 32 | US28 | Marcado de Joya Vendida | Como secretaria de joyería, deseo marcar una joya como "Vendida", para retirar el stock del sistema activo. | 2 |
| 33 | US35 | Validación del Vendedor | Como consumidor final, deseo ver el nombre y credenciales de la joyería, para confirmar que estoy comprando en un comercio autorizado. | 2 |
| 34 | US37 | Compartir Trazabilidad | Como consumidor final, deseo compartir el enlace de trazabilidad de mi joya, para demostrar su autenticidad a terceros. | 2 |
| 35 | US29 | Ingreso de Material de Cliente | Como dueño de joyería, deseo registrar el oro traído por un cliente, para mantenerlo separado del oro de proveedores. | 3 |
| 36 | US30 | Registro de Merma por Refinamiento | Como orfebre, deseo registrar la pérdida de peso tras purificar el oro del cliente, para justificar la reducción de gramos. | 3 |
| 37 | US31 | Emisión de Reporte de Refinamiento | Como dueña de joyería, deseo generar un reporte detallado del refinamiento, para explicarle al cliente de forma transparente por qué su oro disminuyó en peso. | 5 |
| 38 | US32 | Asignación de QR a Oro Reciclado | Como orfebre, deseo emitir un QR que indique "Oro Reciclado", para diferenciarlo del oro de mina directa. | 3 |
| 39 | US36 | Reporte de Irregularidad | Como consumidor final, deseo reportar un código QR sospechoso, para alertar sobre posibles falsificaciones. | 3 |
| 40 | US09 | Recuperación de Contraseña | Como usuario registrado, deseo recuperar mi contraseña, para recuperar el acceso si la olvido. | 3 |
| 41 | US10 | Gestión de Perfil Corporativo | Como administrador de empresa, deseo actualizar la información de mi negocio, para mantener los datos de contacto al día. | 3 |
| 42 | US38 | Dashboard Minero - Merma Global | Como administrador minero, deseo visualizar un gráfico de mermas mensuales, para identificar si existen problemas sistémicos de robo o ineficiencia. | 5 |
| 43 | US39 | Dashboard Joyería - Volumen Validado | Como dueño de joyería, deseo ver la cantidad total de oro validado en el mes, para llevar control de mis compras a proveedores formales. | 5 |
| 44 | TS05 | Endpoint de Reporte de Mermas | Como Developer, deseo un endpoint GET protegido para consultar agregados de mermas, para alimentar los gráficos del dashboard analítico. | 5 |
| 45 | US40 | Exportación de Data Histórica | Como ingeniero de operaciones, deseo descargar en Excel el historial de lotes, para realizar análisis estadísticos externos. | 8 |

---

# CAPÍTULO IV: PRODUCT DESIGN

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines
El diseño de la plataforma GoldMetrics se desarrolla en base a los principios obtenidos durante el proceso de Lean UX, considerando las necesidades de los idstintos segmentos de usuarios: empresas minera, joyerías y consumidores finales.
En ese sentido, se establecen los siguientes lineamientos generales:
- La interfaz del sistema debe ser clara, intuitiva y orientada a la eficiencia, permitiendo a los usuarios acceder rápidamente a información crítica.
- Se empleará un lenaguaje formal pero comprensible, evitando, evitando tecnicismos innecesarios, con el objetivo de facilitar la interacción d eusuarios con distintos niveles de experiencia tecnológica.
- El sistema prioriza la visualización de información en tiempo real, respondiendo a la problemática identificada de falta de control y monitorio en la trazabilidad de minerales.
- Se garantiza la consistencia visual y funcional en todos los módulos del sistema, asegurando una experiencia homogénea.
- Se promoverá la transparencia de la información, permitiendo a los usuarios validar el origen y recorrido de los minerales.
- El diseño estará enfocado en reducir la carga cognitiva, mostrando únicamente información relevante según el rol del usuario.

### 4.1.2. Web Style Guidelines
Los lineamientos visuales de GoldMetrics están orientados a facilitar la interpretación de datos complejos en entornos operativos, asegurando usabilidad y accesibilidad.
- Paleta de colores:
  - **Gris oscuro (#3A3E40):** representa estabilidad, tecnología y entornos industriales. Se utiliza como color principal en barras de navegación y encabezados.  

  - **Dorado claro (#E1D094):** evoca el valor del mineral (oro) y aporta identidad visual. Puede usarse en elementos destacados.  

  - **Dorado medio (#B4944E):** refuerza la identidad minera del sistema, ideal para botones principales o indicadores importantes.  

  - **Dorado oscuro (#9E8354):** utilizado para variaciones de estado o elementos secundarios dentro de la misma gama cromática.  

  - **Blanco grisáceo (#F2F2F2):** empleado como fondo principal para mantener claridad visual y legibilidad.  

  - **Verde (#28A745):** indica estados correctos o funcionamiento adecuado del sistema.  

  - **Rojo (#DC3545):** representa fallas, errores o alertas críticas.  

  - **Amarillo (#FFC107):** indica advertencias o estados intermedios, como mantenimiento próximo.
- Tipografía:
  - Se utilizarán fuentes sans-serif (Como Arial o Roboto por su alta legibilidad).

| Arial | Roboto |
|---|---|
| <img src="../assets/img/chapter-iv/Arial.jpg" width="300"/> | <img src="../assets/img/chapter-iv/Roboto.png" width="300"/> |


- Componentes de interfaz:
  - Dashboards con gráficos (líneas, barras, indicadores) para representar información operativa.
  - Tarjetas (cards) para mostrar métricas clave como estado de maquinaria y ubicación.
  - Botones con acciones claras y visibles.
- Diseño responsive:
  - El sistema será adaptable a diferentes dispositivos, permitiendo su uso tanto en campo como en oficina.
- Accesibilidad:
  - Uso adecuado de contraste de colores.
  - Indicadores visuales que faciliten la interpretación rápida de la información.

## 4.2. Information Architecture
La arquitectura de la información de GoldMetrics ha sido definida con el objetivo de optimizar el acceso, organización y comprensión de la información, en función de las necesidades identificadas en el proceso de Lean UX.

### 4.2.1. Organization Systems
El sistema organiza la información mediante diferentes enfoques complementarios:
- Organización jerárquica:
  - Un dashboard principal como punto de entrada.
  - Módulos específicos: Trazabilidad, Mantenimiento y Reportes.
- Organización por roles:
  - Empresas mineras: gestión operativa y monitoreo
- Consumidores: consulta de información del producto
Este enfoque responde directamente a la segmentación de usuarios definida en el proyecto.
- Organización por procesos:
  - Extracción --> Transporte --> Procesamiento --> Comercialización
  Permite representar el cilo de vida del mineral.
- Organización por daots:
  - Flota de maquinaria
  - Ubicación
  - Estado operativo
  - Historial de eventos

Facilitando el análisis y la toma de decisiones
### 4.2.2. Labeling Systems
El sistema utiliza etiquetas claras, consistentes y orientadas al usuario:
- Dashboard
- Trazabilidad
- Mantenimiento
- Reportes
- Certificados
- Historial
- Ubicación en tiempo real

Estas etiquetas han sido definidas para facilitar la comprensión y navegación, evitando terminología técnica innecesaria

### 4.2.3. SEO Tags and Meta Tags
Para mejorar la visibilidad y estructuración del sistema web, se implementan las siguientes prácticas:

- `<title>`: Goldmetrics - Plataforma de trazabilidad minera  
- `<meta name="description">`: Plataforma que permite monitorear, analizar y validar minerales en tiempo real mediante IoT e inteligencia artificial.  
- `<meta name="keywords">`: trazabilidad minera, monitoreo de minerales, IoT minería, minería Perú  

**Adicionalmente:**

- Uso adecuado de encabezados:
  - `<h1>`
  - `<h2>`
  - `<h3>`

- URLs estructuradas:
  - `/dashboard`
  - `/trazabilidad`
  - `/mantenimiento`
  - `/reportes`

### 4.2.4. Searching Systems
El sistema incorpora mecanismos de búsqueda que permiten acceder rápidamente a información específica:

- **Búsqueda por:**
  - ID del mineral  
  - Código QR  
  - Unidad de maquinaria  
  - Ubicación  

- **Filtros avanzados:**
  - Fecha  
  - Estado (activo, en mantenimiento, falla)  
  - Tipo de mineral  

- **Resultados en tiempo real**, facilitando la toma de decisiones operativas.

### 4.2.5. Navigation Systems
La navegación del sistema está diseñada para ser clara, eficiente y orientada a las necesidades del usuario:

- **Menú principal:**
  - Dashboard  
  - Trazabilidad  
  - Mantenimiento  
  - Reportes  

- **Navegación por flujo:**
  - Seguimiento del mineral a lo largo de su ciclo de vida.  

- **Navegación contextual:**
  - Acceso a información detallada desde dashboards y gráficos.  

- **Elementos de apoyo:**
  - Breadcrumbs (ej: Dashboard > Mantenimiento > Unidad)  
  - Botones de acceso rápido  

Asimismo, el sistema permite visualizar información relacionada al mantenimiento de maquinaria, incluyendo detección de fallas, análisis de patrones y generación de reportes, lo cual refuerza la funcionalidad operativa del sistema.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe
**Landing Wireframe 1**

![Landing Wireframe 1](../assets/img/landing-wireframe-1.png)

**Landing Wireframe 2**

![Landing Wireframe 2](../assets/img/landing-wireframe-2.png)

**Landing Wireframe 3**

![Landing Wireframe 3](../assets/img/landing-wireframe-3.png)

**Landing Wireframe 4**

![Landing Wireframe 4](../assets/img/landing-wireframe-4.png)

**Landing Wireframe 5**

![Landing Wireframe 5](../assets/img/landing-wireframe-5.png)

**Landing Wireframe 6**

![Landing Wireframe 6](../assets/img/landing-wireframe-6.png)

**Link de figma**: https://www.figma.com/design/QbycMaaRmv7o2nCa9J8dPs/Wireframes-y-Mockups-GoldMetrics?node-id=0-1&t=cne9ZmeVzc0o0Y0J-1

### 4.3.2. Landing Page Mock-up
**Landing Mockup 1**

![Landing Mockup 1](../assets/img/landing-mockup-1.png)

**Landing Mockup 2**

![Landing Mockup 2](../assets/img/landing-mockup-2.png)

**Landing Mockup 3**

![Landing Mockup 3](../assets/img/landing-mockup-3.png)

**Landing Mockup 4**

![Landing Mockup 4](../assets/img/landing-mockup-4.png)

**Landing Mockup 5**

![Landing Mockup 5](../assets/img/landing-mockup-5.png)

**Landing Mockup 6**

![Landing Mockup 6](../assets/img/landing-mockup-6.png)

**Link de figma:**
https://www.figma.com/design/QbycMaaRmv7o2nCa9J8dPs/Wireframes-y-Mockups-GoldMetrics?node-id=0-1&t=cne9ZmeVzc0o0Y0J-1

## 4.4. Web Applications UX/UI Design


### 4.4.1. Web Applications Wireframes
![Log in](../assets/img/chapter-iv/Log%20in.png)  
![Sign up](../assets/img/chapter-iv/Sign%20up.png)  
![Profile Screen](../assets/img/chapter-iv/Profile%20Screen.png)  
![Payment Method](../assets/img/chapter-iv/Payment%20Method.png)  
![REGISTER](../assets/img/chapter-iv/REGISTER.png)  
![Frame](../assets/img/chapter-iv/Frame%201321317457.png)  
![Overlay](../assets/img/chapter-iv/Overlay+OverlayBlur.png)  
![Modal Validación](../assets/img/chapter-iv/Dashboard%20Joyería%20-%20Modal%20Validación.png)  
![Profile Screen](../assets/img/chapter-iv/Profile%20Screen.png)  
![Overlay](../assets/img/chapter-iv/Overlay+OverlayBlur-1.png)  
![Dashboard Minería](../assets/img/chapter-iv/Dashboard%20Minería%20-%20Principal.png)  
![Overlay](../assets/img/chapter-iv/Overlay+OverlayBlur-2.png)  
![Overlay](../assets/img/chapter-iv/Overlay+OverlayBlur-3.png)  
![Detalle Lote](../assets/img/chapter-iv/Dashboard%20Minería%20-%20Detalle%20Lote.png)  
![Dashboard Usuario](../assets/img/chapter-iv/Dashboard%20Usuario%20Final.png)  
![Overlay](../assets/img/chapter-iv/Overlay+OverlayBlur-4.png)  
![Alerta Activa](../assets/img/chapter-iv/Dashboard%20Minería%20-%20Alerta%20Activa.png)  
![Overlay](../assets/img/chapter-iv/Overlay+OverlayBlur-5.png)  
---
### 4.4.2. Web Applications Wireflow Diagrams

![Wireflow 1](../assets/img/chapter-iv/wireflow/1%20(1).jpeg)  
![Wireflow 2](../assets/img/chapter-iv/wireflow/1%20(2).jpeg)  
![Wireflow 3](../assets/img/chapter-iv/wireflow/1%20(3).jpeg)  
![Wireflow 4](../assets/img/chapter-iv/wireflow/1%20(4).jpeg)  

---

### 4.4.2. Web Applications Mock-ups
![Log in](../assets/img/chapter-iv/Mockup/Log%20in.png)  
![Sign up](../assets/img/chapter-iv/Mockup/Sign%20up.png)  
![Profile](../assets/img/chapter-iv/Mockup/Profile%20Screen.png)  
![Payment](../assets/img/chapter-iv/Mockup/Payment%20Method.png)  
![Subscriptions](../assets/img/chapter-iv/Mockup/SUSCRIPTIONS.png)  
![Dashboard Joyería](../assets/img/chapter-iv/Mockup/Dashboard%20Joyería%20-%20Principal.png)  
![Modal Validación](../assets/img/chapter-iv/Mockup/Dashboard%20Joyería%20-%20Modal%20Validación.png)  
![Modal Validación 2](../assets/img/chapter-iv/Mockup/Dashboard%20Joyería%20-%20Modal%20Validación-1.png)  
![QR Éxito](../assets/img/chapter-iv/Mockup/Dashboard%20Joyería%20-%20Éxito%20de%20QR.png)  
![Dashboard Minería](../assets/img/chapter-iv/Mockup/Dashboard%20Minería%20-%20Principal.png)  
![Nuevo Lote](../assets/img/chapter-iv/Mockup/Dashboard%20Minería%20-%20Nuevo%20Lote%20Modal.png)  
![Nuevo Lote Paso 2](../assets/img/chapter-iv/Mockup/Dashboard%20Minería%20-%20Nuevo%20Lote%20(Paso%202).png)  
![Detalle Lote](../assets/img/chapter-iv/Mockup/Dashboard%20Minería%20-%20Detalle%20Lote.png)  
![Alerta](../assets/img/chapter-iv/Mockup/Dashboard%20Minería%20-%20Alerta%20Activa.png)  
![Incidente](../assets/img/chapter-iv/Mockup/Dashboard%20Minería%20-%20Modal%20Incidente.png)  
![Usuario Final](../assets/img/chapter-iv/Mockup/Dashboard%20Usuario%20Final.png)  
![Vincular Joya](../assets/img/chapter-iv/Mockup/Usuario%20Final%20-%20Vincular%20Joya.png)  


### 4.4.3. Web Applications User Flow Diagrams
### Happy Path 1 – Joyería: Validación de lote y registro de joya

**Flujo principal:**

1. Joyero ingresa al sistema  
2. Accede a “Validar Lote”  
3. Ingresa ID del lote  

4. El sistema muestra:
   - Peso registrado  
   - Origen   

5. El joyero realiza el pesaje físico del material  

**Decisión:**
- ¿El peso coincide (dentro de tolerancia)?  
  - No → Cancelar
  - Sí → Continuar  

6. Confirmar recepción  
7. El sistema registra el evento en blockchain  

8. El joyero registra nueva joya:
   - Nombre
   - Descripción  

9. Publicar certificado digital  
10. Generar código QR de la joya

![Happy Joyería](../assets/img/chapter-iv/userflows/happy%20joyeria.jpeg)
---


### Happy Path 2 – Minería: Registro de nuevo lote

**Flujo principal:**

1. Operador Minero inicia sesión  
2. Accede a “Registrar Lote”  

3. Ingresa:
   - Origen / yacimiento  
   - Carro de transporte  

4. Hace clic en “Capturar pesaje”  
5. El sistema registra el peso del lote  

**Decisión:**
- ¿Pesaje válido?  
  - No → Retroceder
  - Sí → Continuar  

6. Confirmar registro del lote  
7. El sistema genera ID del lote  
8. Se asocia el lote al camión  

9. El sistema muestra:
   - Ubicación del camión en tiempo real  

10. Estado del lote: “En Origen” 

![Happy Minería](../assets/img/chapter-iv/userflows/happy%20mineria.jpeg)

---

### Happy Path 3 – Usuario final: Vincular joya

**Flujo principal:**

1. Usuario accede a la plataforma  
2. Hace clic en “Vincular joya”  
3. Ingresa ID de la joya  

**Decisión:**
- ¿ID válido?  
  - No → Mostrar error y permitir reintento  
  - Sí → Continuar  

4. Hace clic en “Validar y vincular”  
5. El sistema verifica la autenticidad  

6. El sistema:
   - Vincula la joya al usuario  
   - La guarda en su perfil  

7. El usuario visualiza:
   - Certificado digital  
   - Trazabilidad de la joya

![Happy Usuario](../assets/img/chapter-iv/userflows/happy%20usuario.jpeg)

---

### Unhappy Path – Desvío de ruta del camión

**Flujo principal:**

1. El sistema monitorea la ubicación del camión  
2. Detecta una desviación de ruta  

**Decisión:**
- ¿La ruta coincide con la planificada?  
  - Sí → Continúa flujo normal  
  - No → Generar alerta  

3. El usuario (Administrador/Supervisor) accede a “Ver detalles”  

4. El sistema muestra:
   - Ubicación actual del camión  
   - Número de lote  
   - Conductor  
   - Teléfono  
   - Mapa de ruta  

**Decisión:**
- ¿Es una desviación real?  
  - No → Marcar como “Falsa alarma”  
  - Sí → Continuar  

5. Opciones disponibles:
   - Llamar al conductor  
   - Congelar lote  
   - Notificar a seguridad  

6. Estado del lote: “Anomalía” 

![Unhappy](../assets/img/chapter-iv/userflows/unhappy.jpeg)

## 4.5. Web Applications Prototyping

Prototipo de la aplicación web GoldMetric en Figma:
https://www.figma.com/design/7O7yxNUaLKdHpT7T4GyrSh/WIRFRAME-4?node-id=0-1&t=9KcYAtK3HDnZEl7w-1

## 4.6. Domain-Driven Software Architecture

GoldMetrics utiliza el enfoque de Domain-Driven Design (DDD) con el fin de facilitar la colaboración entre developers y expertos en el sector. Para esto, el sistema utiliza una organización entre 11 Bounded Context independientes de manera que logramos separar claramente las responsabilidades. Con esto también resaltamos las funcionalidades clave para hacer del proyecto altamente escalable de manera que se pueda incrementar la eficiencia de  procesos como el mantenimiento o la escalación. 

A continuación se muestran y describen los Bounded Context que forman la solución:

| Bounded Context | Descripción |
| :--- | :--- |
| **Fleet Operations** | Inicio del ciclo de transporte. |
| **Material Operations** | Clasificación y descarga de materiales. |
| **Jewelry Inventory & Certification** | Guardado en inventario de joyería y certificación de materiales. |
| **Consumer Traceability** | Trazabilidad y soporte para el consumidor. |
| **Monitoring & Telemetry** | Monitoreo y gestion de anomalias. |
| **Analytics** | Análisis de ruta, impulsa la trazabilidad. |
| **Incident Management** | Gestion de incidentes. |
| **Reporting & Notifications** | Reportes de accidentes y notificaciones. |
| **Asset & Maintenance Management** | Gestion de mantenimiento de operativo minero. |
| **Identity & Access Management** | Autenticación e inicio de sesión. |
| **Subscriptions & Billing** | Gestión de planes, acceso escalonado a funcionalidades y facturación. |

### 4.6.1. Design-Level EventStorming
Utilizando la técnica de Event Storming a nivel de diseño, hemos logrado identificar los eventos de dominio y los comandos quienes cargan con la lógica de negocio en cada Bounded Context.

A continuación, se muestra la matriz de interdependencias entre los módulos:
| Origen (Evento) | Destino (Comando) | Descripción |
| :--- | :--- | :--- |
| **Fleet Operations:** Charging point reached | **Material Operations:** Dowload material | Descarga del material al llegar al punto de interes. |
| **Material Operations:** Material downloaded | **Jewelry Inventory & Certification:** Register Material in Inventory | Descarga del material al llegar a la joyeria. |
| **Jewelry Inventory & Certification:** Certificate Saved | **Consumer Traceability:** View certificate | Permite al usuario ver el certificado emitido por la joyería. |
| **Consumer Traceability:** Traceability data requested | **Analytics:** View route progress | Permite al usuario ver el progreso de ruta que tuvo el material. |
| **Incident Management:** Smoke alert commited | **Monitoring & Telemetry:** Monitor exhaust temperature | Emite una alerta de gas que sugiera revisar alguna fuga de gas. |
| **Monitoring & Telemetry:** Telemetry data proccessed | **Incident Management:** Commit accident | Guarda la información del accidente recibido gracias a la telemetría. |
| **Incident Management:** Accident commited | **Reporting & Notifications:** Request accident data | Pide la información del accidente para generar un reporte sobre este. |

**EventStorming**

![EventStorming](../assets/img/chapter-iv/event-storming-goldmetrics.jpg)

Para visualizar el Event Storming de mejor manera recomendamos ingresar al siguiente link:
[Visualizar EventStorming en Miro](https://miro.com/app/board/uXjVJeWDqwE=/?share_link_id=757586972674)

### 4.6.2. Software Architecture Context Diagram
El diagrama de contexto establece los límites de la plataforma GoldCheck y su interacción con los diferentes perfiles de usuario y sistemas externos críticos para el negocio.

![Diagrama de contexto](../assets/img/chapter-iv/context-diagram.png)

### 4.6.3. Software Architecture Container Diagrams
En el segundo nivel de abstracción, se ha diseñado una arquitectura altamente desacoplada orientada a la escalabilidad y la resiliencia operativa tanto en frontend como en backend.

**Frontend:**

![Diagrama de contenedores frontend](../assets/img/chapter-iv/container-diagram-frontend.png)

**Backend:**

![Diagrama de contenedores backend](../assets/img/chapter-iv/container-diagram-backend.png)

### 4.6.4. Software Architecture Components Diagrams

**Identity & Access Management**

![Diagrama de contexto 1](../assets/img/chapter-iv/context-diagram-1.png)
**Fleet Operations**

![Diagrama de contexto 2](../assets/img/chapter-iv/context-diagram-2.png)

**Assist & Maintenance Management**
![Diagrama de contexto 3](../assets/img/chapter-iv/context-diagram-3.png)

**Material Operations**
![Diagrama de contexto 4](../assets/img/chapter-iv/context-diagram-4.png)

**Jewelry Inventory & Certification**
![Diagrama de contexto 5](../assets/img/chapter-iv/context-diagram-5.png)

**Consumer Traceability**
![Diagrama de contexto 6](../assets/img/chapter-iv/context-diagram-6.png)

**Analytics**
![Diagrama de contexto 7](../assets/img/chapter-iv/context-diagram-7.png)

**Monitoring & Telemetry**
![Diagrama de contexto 8](../assets/img/chapter-iv/context-diagram-8.png)

**Incident Management**
![Diagrama de contexto 9](../assets/img/chapter-iv/context-diagram-9.png)

**Reporting & Notificacions**
![Diagrama de contexto 10](../assets/img/chapter-iv/context-diagram-10.png)

**Subscripcions & Billing**
![Diagrama de contexto 11](../assets/img/chapter-iv/context-diagram-11.png)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams
A continuación se presentaran los diagramas de clases de los respectivos bounded context.

**Identity & Access Management**

![Diagrama de clase 1](../assets/img/chapter-iv/class-diagram-identity.png)

**Fleet Operations**

![Diagrama de clase 2](../assets/img/chapter-iv/class-diagram-fleet.png)

**Assist & Maintenance Management**

![Diagrama de clase 3](../assets/img/chapter-iv/class-diagram-asset.png)

**Material Operations**

![Diagrama de clase 4](../assets/img/chapter-iv/class-diagram-material.png)

**Jewelry Inventory & Certification**

![Diagrama de clase 5](../assets/img/chapter-iv/class-diagram-jewelry.png)

**Consumer Traceability**

![Diagrama de clase 6](../assets/img/chapter-iv/class-diagram-consumer.png)

**Analytics**

![Diagrama de clase 7](../assets/img/chapter-iv/class-diagram-analytics.png)

**Monitoring & Telemetry**

![Diagrama de clase 8](../assets/img/chapter-iv/class-diagram-monitoring.png)

**Incident Management**

![Diagrama de clase 9](../assets/img/chapter-iv/class-diagram-incident.png)

**Reporting & Notificacions**

![Diagrama de clase 10](../assets/img/chapter-iv/class-diagram-reporting.png)

**Subscripcions & Billing**

![Diagrama de clase 11](../assets/img/chapter-iv/class-diagram-subscriptions.png)

## 4.8. Database Design

### 4.8.1. Database Diagrams
**Identity & Access Management**

![Diagrama de clase 1](../assets/img/chapter-iv/identity-db.png)

**Fleet Operations**

![Diagrama de clase 2](../assets/img/chapter-iv/fleet.png)

**Assist & Maintenance Management**

![Diagrama de clase 3](../assets/img/chapter-iv/assist.png)

**Material Operations**

![Diagrama de clase 4](../assets/img/chapter-iv/material.png)

**Jewelry Inventory & Certification**

![Diagrama de clase 5](../assets/img/chapter-iv/jewelry.png)

**Consumer Traceability**

![Diagrama de clase 6](../assets/img/chapter-iv/consumer.png)

**Analytics**

![Diagrama de clase 7](../assets/img/chapter-iv/analytics.png)

**Monitoring & Telemetry**

![Diagrama de clase 8](../assets/img/chapter-iv/monitoring.png)

**Incident Management**

![Diagrama de clase 9](../assets/img/chapter-iv/incident.png)

**Reporting & Notificacions**

![Diagrama de clase 10](../assets/img/chapter-iv/reporting.png)

**Subscripcions & Billing**

![Diagrama de clase 11](../assets/img/chapter-iv/subscriptions.png)

# CAPÍTULO V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

**-Project Management:**
1. Herramienta: Trello
Propósito: Gestión de tareas, planificación de sprints y seguimiento del progreso del equipo mediante tableros Kanban. 

**-Requirements Management:**
1. Herramienta: UXPressia
Propósito: Creación de artefactos de needfinding como User Personas, User Journey Maps y Empathy Maps para comprender las necesidades del usuario.
2. Herramienta: Miro
Propósito: Desarrollo de Event Storming (Big Picture y Process Level) para el modelado de procesos y definición del alcance del sistema.
3. Herramienta: Gherkin
Propósito: Definición de criterios de aceptación y escenarios de prueba en formato Given–When–Then.

**-Product UX/UI Design:**
1. Herramienta: Figma
Propósito: Diseño de wireframes y mockups de la interfaz del sistema, incluyendo la landing page.

**-Software Development:**
1. Herramienta: Visual Studio Code
Propósito: Entorno de desarrollo utilizado para la programación del sistema.
2. Herramienta: GitHub
Propósito: Control de versiones y trabajo colaborativo mediante repositorios, commits y ramas. Cada miembro del equipo clonará el repositorio para desarrollar de manera distribuida sus features.
3. Tecnología Frontend: Vue.js  
Lenguaje: JavaScript  
Propósito: Desarrollo de interfaces web interactivas y responsivas del sistema, permitiendo una experiencia de usuario dinámica mediante componentes reutilizables.
4. Tecnología Backend:
Lenguaje: C#  
Propósito: Desarrollo de la lógica del servidor, implementación de servicios RESTful, manejo de peticiones HTTP y comunicación con la base de datos.
5. Base de Datos: Microsoft SQL Server  
Propósito: Almacenamiento, gestión y consulta eficiente de la información del sistema, garantizando integridad y consistencia de los datos.
6. Herramienta: WebStorm  
Propósito: Entorno de desarrollo especializado para aplicaciones JavaScript y TypeScript, utilizado como soporte para el desarrollo frontend junto con Vue.js.

**-Software Deployment:**
1. Herramienta: GitHub Pages
Propósito: Despliegue de la solución de cada producto digital de OpalTrace desde nuestro repositorio de Github.

**-Software Documentation:**
1. Herramienta: Markdown
Propósito: Documentación técnica del proyecto (README y documentación del código).
2. Herramienta: Structurizr
Propósito: Elaboración de diagramas de arquitectura del sistema utilizando el modelo C4 (contexto, contenedores, componentes y código).

![Software Configuration](../assets/img/chapter-v/software.png)

### 5.1.2. Source Code Management
Para el control de versiones y la organización ordenada del código de nuestro proyecto GoldCheck, el equipo utiliza GitHub como plataforma principal. GitHub nos permite almacenar código fuente de la Landing Page, Front-End, Back-End llevar un registro histórico de cambios, colaborar de manera estructurada y garantizar trazabilidad durante todo el ciclo de desarrollo. Por ende, creamos la organización Minex-Organization, que incluye los siguientes repositorios:
| Solución  | Nombre del repositorio  |  Enlace  |
|---|---|---|
| report | goldcheck-report  | https://github.com/upc-pre-202610-1asi0730-11863-GoldMetri/goldcheck-report.git |
| website  | goldcheck-website  |  https://github.com/upc-pre-202610-1asi0730-11863-GoldMetri/goldcheck-website.git |
| webapp  |  goldcheck-webapp  | https://github.com/upc-pre-202610-1asi0730-11863-GoldMetri/goldcheck-webapp.git |
| platform  | goldcheck-platform   | https://github.com/upc-pre-202610-1asi0730-11863-GoldMetri/goldcheck-platform.git   |

NNuestro equipo de trabajo ha adoptado el flujo GitFlow, basado en el artículo “A successful Git branching model” de Vincent Driessen. La organización del repositorio se estructura en dos ramas principales y permanentes: master, que contiene las versiones estables listas para entrega, y develop, que funciona como la rama de integración continua del desarrollo. A partir de la rama develop, se crean ramas de tipo feature siguiendo la nomenclatura feature/chapter-#-description, por ejemplo: feature/chapter-ii-interviews. Estas ramas permiten que cada miembro del equipo desarrolle funcionalidades o secciones específicas de manera aislada. En casos donde un integrante desarrolla un capítulo completo, se utiliza una convención como feature/chapter-#-content. Una vez finalizado el trabajo, estas ramas se integran nuevamente en develop, asegurando una consolidación ordenada de los avances.

Cuando el producto se aproxima a una fecha de entrega, se genera una rama release a partir de develop. En esta etapa se realizan ajustes menores, como corrección de errores o mejoras finales. Posteriormente, la rama release se fusiona tanto en master como en develop, garantizando que los cambios aplicados se mantengan en futuras iteraciones del proyecto. En cuanto a la gestión de versiones, se utiliza Semantic Versioning mediante ramas con el formato release/vX.Y.Z. Asimismo, las correcciones críticas se gestionan a través de ramas hotfix, con la nomenclatura hotfix/vX.Y.Z, permitiendo resolver errores urgentes directamente sobre la versión en producción.

Adicionalmente, el equipo aplica la convención Conventional Commits, la cual estandariza los mensajes de confirmación para mejorar la trazabilidad y comprensión de los cambios. Cada commit sigue una estructura clara, por ejemplo:

git commit -m "docs(chapter-#): add ..."

Este enfoque facilita la generación automática de historiales de cambios y permite mantener un registro organizado y semántico del desarrollo.

En síntesis, cada nueva funcionalidad se desarrolla en una rama feature, las versiones listas para entrega se gestionan mediante release branches, y las correcciones urgentes a través de hotfix branches. Todo ello, junto con el uso de Conventional Commits, asegura un flujo de trabajo estructurado, colaborativo y alineado con buenas prácticas para el desarrollo del proyecto GoldCheck.

**Repositorio report**
![report-screenshoot](../assets/img/chapter-v/report.png)


**Repositorio  website**
![landing-screenshoot](../assets/img/chapter-v/website.png)


**Repositorio webapp**
![frontend-screenshoot](../assets/img/chapter-v/webapp.png)


**Repositorio platform**
![backend-screenshoot](../assets/img/chapter-v/platform.png)


### 5.1.3. Source Code Style Guide & Conventions
Como norma general, todo el código desarrollado en GoldCheck deberá estar completamente redactado en inglés, incluyendo nombres de variables, funciones, clases, archivos y comentarios, esto garantiza consistencia, mantenibilidad y alineación con estándares internacionales. Asimismo, el equipo adopta convenciones basadas en guías reconocidas como Google Style Guide, Microsoft C# Guidelines y Gherkin Best Practices, adaptadas al contexto del dominio minero y de trazabilidad definido en el Ubiquitous Language del proyecto.

1. Principios Generales
- Uso obligatorio del idioma inglés en todo el código.
- Nombres descriptivos alineados al dominio (ubiquitous language), por ejemplo: haulTruck, payload, traceabilityData, oreBatch
- Evitar ambigüedad: los nombres deben reflejar claramente su propósito.
- Priorizar automatización sobre procesos manuales (alineado a insights del proyecto).
2. HTML
- Uso de etiquetas y atributos en minúsculas
`<section id="traceability-report"></section>`
- Cerrar correctamente todos los elementos
`<p>Gold traceability data</p>`
- Uso de comillas dobles para atributos
`<button class="primary-button"></button>`
- Incluir atributos de accesibilidad (alt, width, height)
`<img src="ore.png" alt="gold-ore" width="64" height="64" />`
- Sangría de 2 espacios
3. CSS
- Uso de kebab-case para clases e IDs
`.traceability-card {}`
`.mineral-data {}`
- Uso opcional de BEM para componentes complejos
`.traceability-card__status--active {}`
- Omitir unidades en valores cero
`margin: 0;`
- Ordenar propiedades (alfabético o por bloques)
- Separar bloques con líneas en blanco para legibilidad
4. JavaScript
- Uso de camelCase para variables y funciones
`function calculatePayload() {}`
- Declaración de variables con const y let
`const payloadWeight = 120;`
`let cycleTime = 0;`
- Uso de ES6+ (arrow functions, destructuring, etc.)
- Manejo de errores
`try {`
`  processTelemetryData();`
`} catch (error) {`
`  console.error(error);`
`}`
- Evitar funciones largas (máx. 20–30 líneas)
5. C# (.NET / Backend)
- PascalCase para clases y métodos
`public class TraceabilityService {`
`    public void CalculateProduction() { }`
`}`
- camelCase para variables y parámetros
`int payloadWeight;`
- UPPER_SNAKE_CASE para constantes
`const int MAX_PAYLOAD = 400;`
- Sangría de 4 espacios (sin tabs)
- Principios clave: Single Responsibility, código modular Y comentarios claros y concisos
6. Gherkin (BDD)

Se utilizará Gherkin para definir escenarios de negocio relacionados a trazabilidad minera y validación de oro.

- Estructura obligatoria: Given – When – Then
- Lenguaje entendible para negocio (no técnico)
`Feature: Gold Traceability Verification`
`Scenario: Verify origin of gold`
`Given a user scans a QR code`
`When the system retrieves traceability data`
`Then the user should see the origin mine and certification`
- Uso de Scenario Outline cuando aplique
- Escenarios claros, cortos y orientados a valor

7. Uso del Ubiquitous Language
Todos los términos del dominio deben respetar el lenguaje definido en el sistema para asegurar consistencia entre negocio y tecnología, para que tanto desarrolladores como stakeholders hablen el mismo idioma dentro del sistema..

Ejemplos aplicados:

`HaulTruck`
`Payload`
`Traceability`
`Ore`
`Refinery`
`Jeweler`
`EthicalGold`
`Telemetry`

Ejemplo en código:

`const haulTruckPayload = calculatePayload(haulTruckData);`

### 5.1.4. Software Deployment Configuration
- Creación de la Website (Landing Page):
1. Se crea un repositorio (goldcheck-website) desde GoldMetri-organization
![deployment1-screenshoot](../assets/img/chapter-v/deployment-1.png)

2. Agregar a los miembros del equipo
![deployment2-screenshoot](../assets/img/chapter-v/deployment-2.png)

3. Habilitar GitHub Pages en branch master y ruta "/(root)"
![deployment3-screenshoot](../assets/img/chapter-v/deployment-3.png)


- Creación de WebApp
1. Creación del repositorio (goldcheck-webapp) dentro de la organización GoldMetri-organization
![deployment4-screenshoot](../assets/img/chapter-v/deployment-4.png)

2. Agregar a los miembros del equipo
![deployment5-screenshoot](../assets/img/chapter-v/deployment-2.png)

- Creación de Platform
1. Creación del repositorio (goldcheck-platform) dentro de la organización GoldMetri-organization
![deployment4-screenshoot](../assets/img/chapter-v/deployment-6.png)

2. Agregar a los miembros del equipo
![deployment5-screenshoot](../assets/img/chapter-v/deployment-2.png)

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

El Sprint 1 está dedicado exclusivamente a establecer la presencia digital de la startup mediante el diseño, desarrollo y despliegue de la primera versión del Landing Page de GoldCheck.

| Campo | Detalle |
|:------|:--------|
| **Sprint #** | Sprint 1 |
| **Date** | `2026-04-15` |
| **Time** | `6:00 pm` |
| **Location** | Reunión virtual por Discord |
| **Prepared By** | `[Nombre del Team Leader del grupo]` |
| **Attendees** | Armestar Felipa, Adrian / García Paredes, Victor / Navarro Aldoradin, Carolina / Philco Mota, Katty / Tuesta Girón, Kiara |
| **Sprint 0 Review Summary** | Se definieron los perfiles de la startup, la problemática del sector minero y los segmentos objetivos (Empresas mineras, joyerías y consumidores finales). Se establecieron los repositorios y la organización en GitHub. |
| **Sprint 0 Retrospective Summary** | El equipo coincide en la necesidad de mejorar la comunicación asíncrona y respetar los tiempos de revisión de Pull Requests. |
| **Sprint 1 Goal** | **Our focus is on** delivering the first functional version of the Goldmetrics Landing Page. **We believe it delivers** a clear presentation of our value proposition regarding mineral traceability **to** our target segments (miners, jewelers, consumers). **This will be confirmed when** visitors can access the live website and understand the problem we solve and the features we offer. |
| **Sprint 1 Velocity** | 20 Story Points |
| **Sum of Story Points** | `16` |


#### 5.2.1.2. Aspect Leaders and Collaborators

Para este primer Sprint enfocado en el Landing Page y la configuración inicial de los proyectos, la distribución de liderazgo (L) y colaboración (C) es la siguiente:

| Team Member (Last Name, First Name) | GitHub Username | UI/UX Design (Figma) | Landing Page Layout (HTML/CSS) | Landing Page Interactivity (JS) | DevOps & Deployment |
|:-----------------------------------:|:---------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| Armestar Felipa, Adrian Andres | `Adrian5102` | C | L | C | C |
| García Paredes, Victor Manuel | `vicmacode` | C | L | L | C |
| Navarro Aldoradin, Carolina Celeste | `genixmvp` | L | L | L | C |
| Philco Mota, Katty Yolanda | `kattyph` | C | C | C | L |
| Tuesta Girón, Kiara Lucia | `kitu05g` | L | C | L | C |

> **L** = Leader &nbsp;|&nbsp; **C** = Collaborator


#### 5.2.1.3. Sprint Backlog 1

El objetivo principal de este Sprint es contar con un sitio web estático desplegado que presente a Goldmetrics y sus beneficios.

| Sprint # | | | | | | | |
|:--------:|---|---|---|---|---|---|---|
| **Sprint 1** | **User Story** | | **Work-Item / Task** | | | | |
| | **ID** | **Título** | **ID** | **Título** | **Descripción** | **Estimación (h)** | **Asignado a** | **Estado** |
| | US01 | Visualizar propuesta de valor | T01 | Diseñar UI en Figma | Elaborar los mockups de la sección Hero y features del LP. | 4 | Navarro, Carolina | Done |
| | US01 | Visualizar propuesta de valor | T02 | Maquetar HTML/CSS base | Convertir el diseño de Figma a código HTML5 y CSS3 semántico. | 5 | Armestar, Adrian | Done |
| | US02 | Visualizar los segmentos | T03 | Programar vistas interactivas | Agregar dinamismo a las tarjetas de segmentos con JavaScript. | 3 | Tuesta, Kiara | Done |
| | US03 | Contactar al equipo | T04 | Maquetar Footer y Contacto | Implementar la sección de contacto y redes sociales. | 3 | García, Victor | Done |
| | *Task* | Configurar Repositorios | T05 | Setup GitHub y Despliegue | Inicializar los repos en GitHub y conectar Vercel al Landing Page. | 2 | Philco, Katty | Done |


#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo se enfocó en establecer la base técnica de BrandRadar mediante el uso de estándares web modernos: HTML5 para la estructura y CSS3 para el diseño visual. Se priorizó una arquitectura de estilos modular, donde cada componente de la Landing Page cuenta con su propia hoja de estilos, facilitando el trabajo paralelo y evitando conflictos en el código.

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|:----------:|:------:|:---------:|:--------------:|:-------------------:|:-------------------:|
| `goldmetrics/website` | `main` | `14ca4e3` | `feat: add hero section` | `Implemented responsive hero section with main CTA` | `2026-04-25` |
| `goldmetrics/website` | `develop` | ` a1b2c3d` | `feat: add user segments cards` | `Created cards for miners, jewelers and consumers` | `2026-04-25` |
| `goldmetrics/website` | `main` | `9f8e7d6` | `style: update color palette` | `Applied Goldmetrics brand colors to the layout` | `2026-04-25` |

---

#### 5.2.1.5. Execution Evidence for Sprint Review

En este primer Sprint se ha logrado el diseño y codificación del Landing Page estático, el cual incluye las secciones de "Hero", "Beneficios/Características" y "Público Objetivo" (empresas mineras, joyerías y consumidores). La interfaz es 100% responsiva (adaptable a dispositivos móviles y escritorio).

![Landing Page Desktop 1](../assets/img/home-page.png)
![Landing Page Desktop 2](../assets/img/home-page.png)
![Landing Page Desktop 3](../assets/img/about-us.png)
![Landing Page Desktop 4](../assets/img/hows-work.png)
![Landing Page Desktop 5](../assets/img/faqs-page.png)
![Landing Page Desktop 6](../assets/img/contact-page.png)
![Landing Page Desktop 7](../assets/img/footer.png)


**URL del Landing Page Desplegado:** [lucky-rolypoly-aaac25.netlify.app](`[URL]`)



#### 5.2.1.6. Services Documentation Evidence for Sprint Review

> *Para el Sprint 1, enfocado estrictamente en la implementación y despliegue del Landing Page, esta sección no aplica. La documentación de los Web Services mediante OpenAPI / Swagger se implementará en los sprints posteriores.*



#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 1 se realizó el despliegue exitoso del Landing Page utilizando la plataforma Netifly.
1. Se creó una cuenta en la plataforma utilizando el correo del equipo.
2. Se vinculó la cuenta con la organización de GitHub de Goldmetrics.
3. Se importó el repositorio `goldmetrics-website`.
4. Se configuró el autodespliegue asociado a la rama `main`.


![Deployment Evidence 1](../assets/img/despliegue.png)


#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante este sprint, la colaboración se gestionó íntegramente a través de GitHub. Se utilizaron Pull Requests (PRs) para integrar el trabajo de la rama `develop` a `main`.

![Team Collaboration Sprint 1](../assets/img/chapter-v/collaboration.png)

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product


## Anexos
Vídeo Exposición: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202416107_upc_edu_pe/IQDMT9TjIRw1RLKM_7j2hos-AfLlqFAwuKrcE9YKUDOwdWI?e=055arn&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
