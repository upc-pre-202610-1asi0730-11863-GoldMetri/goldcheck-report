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


**URL del Landing Page Desplegado:** [https://vocal-sunburst-4c90ad.netlify.app/](`[URL]`)



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

*(Ve a la pestaña "Insights" > "Contributors" de tu repositorio de GitHub y toma una captura donde se vean los commits de todos los miembros del equipo)*
![Team Collaboration Sprint 1](../assets/sprints/sprint1-collaboration.png)

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

El Sprint 2 está dedicado al desarrollo y despliegue de la primera versión del Frontend Web Application de GoldMetrics, integrada con una fake API que simula los endpoints de los bounded contexts principales.

| Campo | Detalle |
| :--- | :--- |
| Sprint # | Sprint 2 |
| Date | 2026-05-07 |
| Time | 8:00 pm |
| Location | Reunión virtual por Discord |
| Prepared By | Tuesta Girón, Kiara Lucia |
| Attendees | Armestar Felipa, Adrian / García Paredes, Victor / Navarro Aldoradin, Carolina / Philco Mota, Katty / Tuesta Girón, Kiara |
| Sprint 1 Review Summary | Se logró desplegar la primera versión del Landing Page de GoldMetrics con las secciones principales dirigidas a los tres segmentos objetivo. Se completó la documentación de los capítulos I al V incluyendo artefactos de UX/UI, diagramas de arquitectura C4, diagramas de clases y base de datos. Se recibieron observaciones del docente sobre la estructura orientada a objetos, los Hypothesis Statements y las Technical Stories. |
| Sprint 1 Retrospective Summary | El equipo identificó la necesidad de mejorar la coordinación en los tiempos de revisión de Pull Requests y establecer checkpoints más frecuentes. Se acordó realizar seguimiento diario por Discord para mayor visibilidad del avance individual. Se priorizó también resolver los problemas de formato del informe en PDF antes de la entrega del TB1. |
| Sprint 2 Goal | Our focus is on deploying a functional first version of the GoldMetrics Frontend Web Application integrated with a fake API. We believe it delivers a navigable and interactive experience to the three target segments (mining companies, jewelry stores, and final consumers), allowing them to explore traceability, verification and monitoring features. This will be confirmed when users can access and navigate the main views of the web application from a public URL without errors. |
| Sprint 2 Velocity | 30 Story Points |
| Sum of Story Points | 28 |

#### 5.2.2.2. Aspect Leaders and Collaborators

Para este Sprint 2 enfocado en el desarrollo del Frontend Web Application y la integración con MockAPI, la distribución de liderazgo (L) y colaboración (C) es la siguiente:

| Team Member (Last Name, First Name) | GitHub Username | Frontend Web App (Vue) | MockAPI / Fake API | Corrección Diagramas (Clases & BD) | Corrección Wireframes & User Flows | Sprint Documentation |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| Armestar Felipa, Adrian Andres | Adrian5102 | C | C | C | C | C |
| García Paredes, Victor Manuel | vicmacode | C | L | C | C | C |
| Navarro Aldoradin, Carolina Celeste | genixmvp | L | C | C | C | L |
| Philco Mota, Katty Yolanda | kattyph | L | C | L | C | C |
| Tuesta Girón, Kiara Lucia | kitu05g | C | C | L | L | C |

L = Leader  |  C = Collaborator

#### 5.2.2.3. Sprint Backlog 2

El objetivo principal de este Sprint es contar con una Web Application desplegada que permita a los tres segmentos objetivo explorar las funcionalidades principales de GoldMetrics integradas con datos de prueba.

| Sprint # | | | | | | | |
| :---: | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Sprint 2** | **User Story** | | **Work-Item / Task** | | | | |
| **ID** | **Título** | **ID** | **Título** | **Descripción** | **Estimación (h)** | **Asignado a** | **Status** |
| US01 | Visualizar dashboard de trazabilidad | T01 | Implementar vista Dashboard | Desarrollar la vista principal del dashboard con KPIs de activos, alertas y mapa en tiempo real usando Vue y PrimeVue | 5 | Philco, Katty | Done |
| US01 | Visualizar dashboard de trazabilidad | T02 | Conectar dashboard con MockAPI | Integrar los endpoints de MockAPI para cargar datos de activos y alertas en el dashboard | 3 | García, Victor | Done |
| US02 | Monitorear traslado de mineral | T03 | Implementar vista de trazabilidad | Desarrollar la vista de trazabilidad con timeline de recorrido del mineral y estado de la carga | 5 | Philco, Katty | Done |
| US03 | Verificar autenticidad de mineral | T04 | Implementar vista de verificación QR | Desarrollar la vista de búsqueda por ID de lote con resultado de autenticidad para el segmento joyería | 4 | Tuesta, Kiara | Done |
| US04 | Consultar origen ético de producto | T05 | Implementar vista de producto para consumidor | Desarrollar la vista de detalle de producto con certificado de origen y timeline para consumidor final | 4 | Tuesta, Kiara | Done |
| US05 | Gestionar suscripción | T06 | Implementar vistas de suscripción | Desarrollar las vistas de selección de plan, método de pago y confirmación de suscripción | 4 | Navarro, Carolina | Done |
| US06 | Consultar historial de pagos | T07 | Implementar vista de historial de pagos | Desarrollar la vista de historial con tabla filtrable y opción de descarga de factura | 3 | Navarro, Carolina | Done |
| TS01 | Endpoints fake API | T08 | Configurar recursos en MockAPI | Crear y configurar los recursos de trazabilidad, activos y suscripciones en MockAPI con datos de prueba | 3 | García, Victor | Done |
| US07 | Actualizar perfil de usuario | T09 | Implementar vista de perfil | Desarrollar la vista de perfil de usuario con formulario de edición de datos | 2 | Navarro, Carolina | Done |
| - | Correcciones AV1 | T10 | Corregir diagramas de clases y BD | Actualizar diagramas de clases (4.7.1) y base de datos (4.8.1) según observaciones del docente | 3 | Philco, Katty / Tuesta, Kiara | Done |
| - | Despliegue Frontend | T11 | Desplegar Frontend Web Application | Configurar y ejecutar el despliegue de la aplicación Vue en Netlify | 2 | Navarro, Carolina | Done |

#### 5.2.2.4. Development Evidence for Sprint Review

Durante el Sprint 2 el equipo se enfocó en el desarrollo del Frontend Web Application utilizando Vue Framework con PrimeVue como biblioteca de componentes UI, siguiendo el Design System definido en el Capítulo IV. Se implementó la integración con MockAPI para simular los endpoints del RESTful API. Cada integrante trabajó en su rama correspondiente y realizó Pull Requests a `develop` al completar cada vista.

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| goldcheck-webapp | develop | 5dce6217bcbaf98cc0cb6a2402798c5910a8243e | feat: upload frontend app | Initial upload of the frontend application structure with Vue and PrimeVue setup | 2026-05-14 |
| goldcheck-webapp | develop | f7d3a2c357b3de18dd45a5a00840d3f674b4c58e | update src with bounded contexts | Restructures source folders following bounded contexts: traceability, subscriptions, IAM and asset management | 2026-05-14 |
| goldcheck-webapp | develop | f7d3a2c357b3de18dd45a5a00840d3f674b4c58e | modified colors and add subscriptions views | Updates color palette to match GoldMetrics brand guidelines and adds subscription plan selection and confirmation views | 2026-05-14 |
| goldcheck-webapp | develop | cce9917f21383b2f108b9bffccc9a8331a80cc49 | modify entities | Updates entity models to align with domain-driven design definitions and bounded context structure | 2026-05-14 |
| goldcheck-mockapi | main | cce9917f21383b2f108b9bffccc9a8331a80cc49 | upload mockapi goldcheck | Uploads MockAPI configuration with resources for traceability, assets, subscriptions and payment history endpoints | 2026-05-13 |

#### 5.2.2.5. Execution Evidence for Sprint Review

En el Sprint 2 se logró desarrollar y desplegar la primera versión funcional del Frontend Web Application de GoldMetrics. La aplicación cuenta con vistas diferenciadas para cada segmento objetivo: el dashboard de trazabilidad y monitoreo de flota para empresas mineras, el panel de verificación de autenticidad y origen para joyerías, y la vista de consulta de origen ético del producto para consumidores finales. Todas las vistas son responsivas y están integradas con la capa mock configurada en MockAPI.

A continuación se presentan las principales vistas implementadas durante este Sprint:

[Screenshot Frontend - Dashboard principal]

[Screenshot Frontend - Vista de trazabilidad]

[Screenshot Frontend - Vista de verificación QR]

[Screenshot Frontend - Vista de producto consumidor final]

[Screenshot Frontend - Vista de suscripción]

[Screenshot Frontend - Historial de pagos]

URL del Frontend Web Application desplegado: 

URL del video de navegación (Microsoft Stream): 

---

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

El Sprint 2 tuvo como alcance exclusivo la construcción del Frontend Web Application de GoldMetrics. Todos los datos son servidos mediante una capa mock con MockAPI a partir de recursos configurados con datos de prueba, sin conexión a endpoints reales de backend. Por esta razón, no se generó documentación OpenAPI ni se desplegaron Web Services durante esta iteración.

La especificación completa de los endpoints RESTful que el frontend consumirá en producción se encuentra documentada en las Technical Stories del Product Backlog del Capítulo III. Su implementación está planificada para el Sprint 3 dentro del repositorio goldcheck-backend, cubriendo los siguientes bounded contexts: Identity & Access Management con autenticación JWT, Subscriptions & Billing con gestión de planes y facturación, Asset & Maintenance Management con registro y monitoreo de maquinaria, Traceability con seguimiento del recorrido del mineral desde extracción hasta comercialización, y Consumer Experience con verificación pública de autenticidad mediante código QR.

---

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizó el despliegue exitoso del Frontend Web Application de GoldMetrics. A continuación se describen los pasos realizados:


URL del Frontend Web Application desplegado: 
URL del Landing Page: 

#### 5.2.2.8. Team Collaboration Insights during Sprint

Durante este Sprint la colaboración se gestionó íntegramente a través de GitHub. Se utilizaron Pull Requests para integrar el trabajo de las ramas de feature a `develop` y posteriormente a `main`. La coordinación diaria se realizó por Discord.

[Screenshot Team Collaboration Sprint 2]

