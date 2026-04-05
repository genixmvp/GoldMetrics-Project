# Informe del Trabajo Final
<center>(Como meto una foto del logo de la upc aqui?)</center>
<center>Universidad Peruana de Ciencias Aplicadas</center>
<center>Ingenieria de Software</center>
<center>2026-01</center>
<center>Aplicaciones Web</center>
<center>12053</center>
<center>Nombre del profesor</center>
<center>Informe de Trabajo Final</center>
<center>Start Up: GoldMetrics</center>
<center>Producto: </center>
<center>Armestar Felipa, Adrian Andres - u202410084</center>
<center>García Paredes, Victor Manuel -</center>
<center>Navarro Aldoradin, Carolina Celeste - u20241b962</center>
<center>Philco Mota, Katty Yolanda -</center>
<center>Tuesta Girón, Kiara Lucia -</center>

<center>Abril, 2026</center>

---

# Registro de Versiones del Informe
()
# Project Report Collaboration Insights
()
# Tabla de Contenido
- **Capitulo I: Introduccion**
    - 1.1. Startup Profile
        - 1.1.1. Descripción de la Startup
        - 1.1.2. Perfiles de integrantes del equipo
    - 1.2. Solution Profile
        - 1.2.1 Antecedentes y problematica
        - 1.2.2 Lean UX Process
            - 1.2.2.1. Lean UX Problem Statements
            - 1.2.2.2. Lean UX Assumptions
            - 1.2.2.3. Lean UX Hypothesis Statements
            - 1.2.2.4. Lean UX Canvas
    - 1.3. Segmentos objetivo
- **Capitulo II: Requirements Elicitation & Analysis**
    - 2.1. Competidores
        - 2.1.1. Analisis competitivo
        - 2.1.2. Estrategias y tácticas frente a competidores
    - 2.2. Entrevistas
        - 2.2.1. Diseño de entrevistas
        - 2.2.2. Registro de entrevistas
        - 2.2.3. Análisis de entrevistas
    - 2.3. Needfinding
        - 2.3.1. User Personas
        - 2.3.2. User Task Matrix
        - 2.3.3. User Journey Mapping
        - 2.3.4. Empathy Mapping
    - 2.4. Big Picture EventStorming
    - 2.5. Ubiquitous Language
- **Capitulo III: Requirements Specification**
    - 3.1. User Stories
    - 3.2. Impact Mapping
    - 3.3. Product Backlog
- **Capitulo IV: Product Design**
    - 4.1. Style Guidelines
        - 4.1.1. General Style Guidelines
        - 4.1.2. Web Style Guidelines
    - 4.2. Information Architecture
        - 4.2.1. Organization Systems
        - 4.2.2. Labeling Systems
        - 4.2.3. SEO Tags and Meta Tags
        - 4.2.4. Searching Systems
        - 4.2.5. Navigation Systems
    - 4.3. Landing Page UI Design
        - 4.3.1. Landing Page Wireframe
        - 4.3.2. Landing Page Mock-up
    - 4.4. Web Applications UX/UI Design
        - 4.4.1. Web Applications Wireframes
        - 4.4.2. Web Applications Wireflow Diagrams
        - 4.4.2. Web Applications Mock-ups
        - 4.4.3. Web Applications User Flow Diagrams
    - 4.5. Web Applications Prototyping
    - 4.6. Domain-Driven Software Architecture
        - 4.6.1. Design-Level EventStorming
        - 4.6.2. Software Architecture Context Diagram
        - 4.6.3. Software Architecture Container Diagrams
        - 4.6.4. Software Architecture Components Diagrams
    - 4.7. Software Object-Oriented Design
        - 4.7.1. Class Diagrams
    - 4.8. Database Design
        - 4.8.1. Database Diagrams
- **Capitulo V: Product Implementation, Validation & Deployment**
    - 5.1. Software Configuration Management
        - 5.1.1. Software Development Environment Configuration
        - 5.1.2. Source Code Management
        - 5.1.3. Source Code Style Guide & Conventions
        - 5.1.4. Software Deployment Configuration
    - 5.2. Landing Page, Services & Applications Implementation
        - 5.2.1. Sprint 1
            - 5.2.1.1. Sprint Planning 1
            - 5.2.1.2. Aspect Leaders and Collaborators
            - 5.2.1.3. Sprint Backlog 1
            - 5.2.1.4. Development Evidence for Sprint Review
            - 5.2.1.5. Execution Evidence for Sprint Review
            - 5.2.1.6. Services Documentation Evidence for Sprint Review
            - 5.2.1.7. Software Deployment Evidence for Sprint Review
            - 5.2.1.8. Team Collaboration Insights during Sprint
- **Conclusiones**
- **Bibliografia** 
- **Anexos**
# Student Outcome
()

# Capitulo I: Introduccion
## 1.1. Startup Profile 
### 1.1.1 Descripcion de la Startup
Nuestra start up "Goldmetrics" esta enfocada en el sector minero ya que se busca monitorear, analizar y validar el recorrido de los minerales desde su extracción hasta el producto final. Logramos esto al desarrollar una plataforma de trazabilidad de minerales implementando tecnología IoT, soluciones Web e Inteligencia Artificial.

La solucion permite a las empresas mineras mejorar la eficiencia y la logistica al reducir perdidas y mejorar la gestion de las operaciones al usar datos en tiempo real. De la misma manera, brinda a las joyerias las herramientas necesarias para validar el origen de los minerales para que estos puedan vender productos de calidad.

Goldmetrics le garantiza al usuario la autenticidad del producto al permitir la transparencia de la informacion de estos, lo cual promueve una compra consciente y sobre todo etica.

Mision: Desarrollar tecnologias que permitan rastrear, analizar y certificar el recorrido de los minerales, garantizando la autenticidad de los productos y promoviendo la responsabilidad social.

Vision: Goldmetrics busca posicionarse como la plataforma lider en trazabilidad minera de América Latina conectando tanto a empresas como a consumidores con información confiable y verificable.
### 1.1.2. Perfiles de integrantes del equipo
()
## 1.2 Solution Profile
### 1.2.1 Antecedentes y problematica
#### What?
El problema se centra en la falta de trazabilidad confiable de minerales en el Perú, lo cual impide reconocer el origen, autenticidad y recorrido de materiales como oro u otros metales.

Según la directora ejecutiva de la Sociedad Nacional de Mineria, Angela Grossheim, rastrear el origen de minerales, especialmente el oro, es difícil debido al mercado informal mezclándose con el mercado formal (DesdeAdentro, 2025). Esto indica que en el sector hay incertidumbre sobre si los minerales provienen de fuentes legales, del mismo modo en el que se pueden manipular los datos de los productos lo cual incrementa el riesgo de perdidas y/o fraude.

#### Who?
Alrededor de esta problemática se pueden identificar varios involucrados, principalmente a las empresas mineras, pues estas presentan dificultades para mantener un control claro de sus operaciones logísticas. Lo cual termina en ineficiencia operativa, fallas en las maquinarias y sobre todo perdidas económicas y de material.

Por su lado, otros actores involucrados serian las joyerías y los consumidores finales, puestos que estos buscan adquirir productos auténticos y que estos posean un origen ético. Sin embargo, al no contar con datos confiables se genera una desconfianza en el mercado alrededor del verdadero valor de ciertos productos. 

#### Where?
Este problema se presenta alrededor del sector minero, como en las zonas de extracción, las etapas de transporte, el almacenamiento, procesamiento y comercialización de los minerales.

#### When?
La problemática sucede en momentos como el transporte, procesamiento y transferencia de los minerales.

#### Why?
Este problema surge por la poca implementación de tecnologías para el monitoreo y control de los minerales, siendo que varias empresas siguen usando registros manuales cuyos datos pueden ser fácilmente manipulados.

### How?
El problema ocurre debido a la falta de seguimiento de los minerales, por lo que nuestros usuarios utilizaran la solución cuando necesiten asegurar el control y validación de los minerales.

### How much?
Esta problemática tiene impactos en varios sectores, especialmente el económico. Según el fiscal coordinado de las Fiscalias Especializadas en Materia Ambiental, Frank Almanza, afirmo que las perdidas económicas por minería ilegal equivale al 2,5% del PBI (Canchari, 2025). Gracias a esto, podemos deducir que la falta de trazabilidad afecta no solo a los ingresos de las empresas, sino que afecta a la economía nacional, resaltando lo importante que es el buscar una solución a dicha problematica.
### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
()
#### 1.2.2.2 Lean UX Assumptions
()
#### 1.2.2.3 Lean UX Hypothesis Statements
()
#### 1.2.2.4 Lean UX Canvas
()
## 1.3 Segmentos Objetivo
()
# Capitulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
### 2.1.1 Analisis competitivo
()
### 2.1.2 Estrategias y tacticas frente a competidores
()
## 2.2 Entrevistas
### 2.2.1 Diseño de entrevistas
()
### 2.2.2 Registro de entrevistas
(son 3 por segmento)
### 2.2.3 Analisis de entrevistas
()
## 2.3 Needfinding
### 2.3.1 User Personas
()
### 2.3.2 User Task Matrix
()
### 2.3.3 User Journey Mapping
()
### 2.3.4 Empathy Mapping
()
## 2.4 Big Picture EventStorming
()
## 2.5 Ubiquitous Language
()
# Capitulo III: Requirements Specification
## 3.1 User Stories
()
## 3.2 Impact Mapping
()
## 3.3 Product Backlog
()
# Capitulo IV: Product Design
## 4.1 Style Guidelines
### 4.1.1 General Style Guidelines
()
### 4.1.2 Web Style Guidelines
()
## 4.2 Information Architecture
()
### 4.2.1 Organization Systems
()
### 4.2.2 Labeling Systems
()
### 4.2.3 SEO Tags and Meta Tags
()
### 4.2.4 Searching Systems
()
### 4.2.5 Navigation Systems
()
## 4.3 Landing Page UI Design
### 4.3.1 Landing Page Wireframe
()
### 4.3.2 Landing Page Mock-up
()
## 4.4 Web Applications UX/UI Design
### 4.4.1 Web Applications Wireframes
()
### 4.4.2 Web Applications Wireflow Diagrams
()
### 4.4.2 Web Applications Mock-ups
()
### 4.4.3 Web Applications User Flow Diagrams
()
## 4.5 Web Applications Prototyping
()
## 4.6 Domain-Driven Software Architecture
()
### 4.6.1 Design-Level EventStorming
()
### 4.6.2 Software Architecture Context Diagram
()
### 4.6.3 Software Architecture Container Diagrams
()
### 4.6.4 Software Architecture Components Diagrams
()
## 4.7 Software Object-Oriented Design
()
### 4.7.1 Class Diagrams
()
## 4.8 Database Design 
### 4.8.1 Database Diagrams
()
# Capitulo V: Product Implementation, Validation & Deployment 
## 5.1 Software Configuration Management
### 5.1.1 Software Development Environment Configuration
()
### 5.1.2 Source Code Management
()
### 5.1.3 Source Code Style Guide & Conventions
()
### 5.1.4 Software Deployment Configuration
()
## 5.2 Landing Page, Services & Applications Implementation
### 5.2.1 Sprint 1
#### 5.2.1.1 Sprint Planning 1
()
#### 5.2.1.2 Aspect Leaders and Collaborators
()
#### 5.2.1.3 Sprint Backlog 1
()
#### 5.2.1.4 Development Evidence for Sprint Review
()
#### 5.2.1.5 Execution Evidence for Sprint Review
()
#### 5.2.1.6 Services Documentation Evidence for Sprint Review
()
#### 5.2.1.7 Software Deployment Evidence for Sprint Review
()
#### 5.2.1.8 Team Collaboration Insights during Sprint
()
# Conclusiones
()
# Bibliografia
Canchari, D. (13 de julio, 2025). Minería ilegal genera pérdidas al Estado que equivalen al 2,5% del PBI. La Republica. https://larepublica.pe/economia/2025/07/13/mineria-ilegal-genera-perdidas-al-estado-que-equivalen-al-25-del-pbi-hnews-284664

DesdeAdentro. (1 de septiembre, 2025). SNMPE: Presupuesto y trazabilidad son claves para luchar contra la minería ilegal. Revista de la Sociedad Nacional de Mineria, Petroleo y Energia. https://www.desdeadentro.pe/2025/09/snmpe-presupuesto-y-trazabilidad-son-claves-para-luchar-contra-la-mineria-ilegal/
# Anexos
()