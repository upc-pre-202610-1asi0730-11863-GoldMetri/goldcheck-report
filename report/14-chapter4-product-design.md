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
