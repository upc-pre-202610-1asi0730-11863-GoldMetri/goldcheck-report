# CAPÍTULO IV: PRODUCT DESIGN

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.2. Web Applications Mock-ups

### 4.4.3. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

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

## 4.7. Software Object-Oriented Design
A continuación se presentaran los diagramas de clases de los respectivos bounded context.
### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams