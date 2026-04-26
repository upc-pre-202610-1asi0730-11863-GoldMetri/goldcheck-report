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

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design


### 4.4.1. Web Applications Wireframes
<img src="../assets/img/chapter-iv/Log in.png" width="300"/>
<img src="../assets/img/chapter-iv/Sign up.png" width="300"/>
<img src="../assets/img/chapter-iv/Profile Screen.png" width="300"/>
<img src="../assets/img/chapter-iv/Payment Method.png" width="300"/>
<img src="../assets/img/chapter-iv/REGISTER.png" width="300"/>
<img src="../assets/img/chapter-iv/Frame 1321317457.png" width="300"/>
<img src="../assets/img/chapter-iv/Overlay+OverlayBlur.png" width="300"/>
<img src="../assets/img/chapter-iv/Dashboard Joyería - Modal Validación.png" width="300"/>
<img src="../assets/img/chapter-iv/Profile Screen.png" width="300"/>
<img src="../assets/img/chapter-iv/Overlay+OverlayBlur-1.png" width="300"/>
<img src="../assets/img/chapter-iv/Dashboard Minería - Principal.png" width="300"/>
<img src="../assets/img/chapter-iv/Overlay+OverlayBlur-2.png" width="300"/>
<img src="../assets/img/chapter-iv/Overlay+OverlayBlur-3.png" width="300"/>
<img src="../assets/img/chapter-iv/Dashboard Minería - Detalle Lote.png" width="300"/>
<img src="../assets/img/chapter-iv/Dashboard Usuario Final.png" width="300"/>
<img src="../assets/img/chapter-iv/Overlay+OverlayBlur-4.png" width="300"/>
<img src="../assets/img/chapter-iv/Dashboard Minería - Alerta Activa.png" width="300"/>
<img src="../assets/img/chapter-iv/Overlay+OverlayBlur-5.png" width="300"/>

### 4.4.2. Web Applications Wireflow Diagrams
<img src="../assets/img/chapter-iv/wireflow/1 (1).jpeg" width="300"/>
<img src="../assets/img/chapter-iv/wireflow/1 (2).jpeg" width="300"/>
<img src="../assets/img/chapter-iv/wireflow/1 (3).jpeg" width="300"/>
<img src="../assets/img/chapter-iv/wireflow/1 (4).jpeg" width="300"/>

### 4.4.2. Web Applications Mock-ups
<img src="../assets/img/chapter-iv/Mockup/Log in.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Sign up.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Profile Screen.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Payment Method.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/SUSCRIPTIONS.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Joyería - Principal.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Joyería - Modal Validación.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Joyería - Modal Validación-1.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Joyería - Éxito de QR.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Minería - Principal.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Minería - Nuevo Lote Modal.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Minería - Nuevo Lote (Paso 2).png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Minería - Detalle Lote.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Minería - Alerta Activa.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Minería - Modal Incidente.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Dashboard Usuario Final.png" width="300"/>
<img src="../assets/img/chapter-iv/Mockup/Usuario Final - Vincular Joya.png" width="300"/>

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