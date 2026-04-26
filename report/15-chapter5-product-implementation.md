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

#### 5.2.1.2. Aspect Leaders and Collaborators

#### 5.2.1.3. Sprint Backlog 1

#### 5.2.1.4. Development Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product