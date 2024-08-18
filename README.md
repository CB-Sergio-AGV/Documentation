
<p style="text-align: center;">
  UNIVERSIDAD PERUANA<br>
  DE CIENCIAS APLICADAS
</p>

<p style="text-align: center;">
  <img src="https://hackmd.io/_uploads/ryJoz7YcR.png" alt="Logo" />
</p>


  **SI729 Desarrollo de Aplicaciones Open Source** 
    **Sección: WS53**
    **Carrera: Ingeniería de Software**
    **Ciclo: 5-6**
    **Profesor:**
    **Juan Antonio Flores Moroco**
    **"Informe de Trabajo Final"**
    **Tema: SphereHub**
    **Producto: BookSphere**
    **Agosto 2024**

**Integrantes:**


- Gómez Vallejos Sergio André - U20221D401
- Salon Puerta Merly - U20201B772
- Romero Qwistgaard, Russell Stephen - U20211043
- Nanfuñay Liza, Pedro Jesús - U202215462
- Fabian Puente, Ronaldo Macedonio - U20201B193


<p style="text-align: center;">
  <strong>Registro de versiones de informe:</strong><br>
</p>


| Entregables  | Fecha | Autor | Descripción de modificación |
|-----------|-----------|-----------|-----------|
| TB1| Fila 1, Columna 2 | Fila 1, Columna 3 | Fila 1, Columna 4 |
| TP | Fila 2, Columna 2 | Fila 2, Columna 3 | Fila 2, Columna 4 |
| TB2 | Fila 3, Columna 2 | Fila 3, Columna 3 | Fila 3, Columna 4 |
| TF | Fila 4, Columna 2 | Fila 4, Columna 3 | Fila 4, Columna 4 |


**Project Report Collaboration Insights**

| URL del Repositorio |
|----------------------|
| https://github.com/orgs/BookSphere-Hub/repositories |




<p style="text-align: center; font-weight: bold;">
  Tabla de contenido
  
</p>

1. [CAPÍTULO I: Introducción](#CAPÍTULO-I-Introducción)<br>
      1.1. [Startup Profile](#Startup-Profile)<br>
      1.1.1. [Descripción de la Startup](#Descripción-de-la-Startup)<br>
      1.1.2. [Perfiles de integrantes del equipo](#Perfiles-de-integrantes-del-equipo)<br>
   1.2. [Solution Profile](#Solution-Profile)<br>
      1.2.1. [Antecedentes y problemática](#Antecedentes-y-problemática)<br>
      1.2.2. [Lean UX Process](#Lean-UX-Process)<br>
             1.2.2.1 [Lean UX Problem Statements](#Lean-UX-Problem-Statements)<br>
             1.2.2.2 [Lean UX Assumptions](#Lean-US-Assumptions)<br>
             1.2.2.3 [Lean UX Hypothesis Statements](#Lean-UX-Hypothesis-Statements)<br>
             1.2.2.4 [Lean UX Canvas](#Lean-UX-Canvas) <br>
1.3. [Segmentos objetivo](#Segmentos-objetivo) <br>
2. [CAPÍTULO II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis) <br>
   2.1. [Competidores](#Competidores) <br>
      2.1.1. [Análisis competitivo](#Análisis-competitivo) <br>
      2.1.2. [Estrategias y tácticas frente a competidores](#Estrategias-y-tácticas-frente-a-competidores) <br>
   2.2. [Entrevistas](#Entrevistas) <br>
      2.2.1. [Diseño de entrevistas](#Diseño-de-entrevistas) <br>
      2.2.2. [Registro de entrevistas](#Registro-de-entrevistas)<br> 
      2.2.3. [Análisis de entrevistas](#Análisis-de-entrevistas)<br> 
   2.3. [Needfinding](#Needfinding) <br>
      2.3.1. [User Personas](#User-Personas) <br>
      2.3.2. [User Task Matrix](#User-Task-Matrix) <br>
      2.3.3. [User Journey Mapping](#User-Journey-Mapping) <br>
      2.3.4. [Empathy Mapping](#Empathy-Mapping) <br>
      2.3.5. [As-is Scenario Mapping](#As-is-Scenario-Mapping) <br>
   2.4. [Ubiquitous Language](#Ubiquitous-Language) <br>
3. [CAPÍTULO III: Requirements Specification](#Capítulo-III-Requirements-Specification) <br>
   3.1. [To-Be Scenario Mapping](#To-Be-Scenario-Mapping) <br>
   3.2. [User Stories](#User-Stories) <br>
   3.3. [Impact Mapping](#Impact-Mapping) <br>
   3.4. [Product Backlog](#Product-Backlog) <br>
4. [CAPÍTULO IV: Product Design](#Capítulo-IV-Product-Design) <br>
   4.1. [Style Guidelines](#Style-Guidelines) 
      4.1.1. [General Style Guidelines](#General-Style-Guidelines) <br>
      4.1.2. [Web Style Guidelines](#Web-Style-Guidelines) <br>
   4.2. [Information Architecture](#Information-Architecture) <br>
      4.2.1. [Organization Systems](#Organization-Systems) <br>
      4.2.2. [Labeling Systems](#Labeling-Systems) <br>
      4.2.3. [SEO Tags and Meta Tags](#SEO-Tags-and-Meta-Tags) <br>
      4.2.4. [Searching Systems](#Searching-Systems) <br>
      4.2.5. [Navigation Systems](#Navigation-Systems) <br>
   4.3. [Landing Page UI Design](#Landing-Page-UI-Design) <br>
      4.3.1. [Landing Page Wireframe](#Landing-Page-Wireframe) <br>
      4.3.2. [Landing Page Mock-up](#Landing-Page-Mock-up) <br>
   4.4. [Web Applications UX/UI Design](#Web-Applications-UX-UI-Design) <br>
      4.4.1. [Web Applications Wireframes](#Web-Applications-Wireframes) <br>
      4.4.2. [Web Applications Wireflow Diagrams](#Web-Applications-Wireflow-Diagrams) <br>
      4.4.3. [Web Applications Mock-ups](#Web-Applications-Mock-ups) <br>
      4.4.4. [Web Applications User Flow Diagrams](#Web-Applications-User-Flow-Diagrams) <br>
   4.5. [Web Applications Prototyping](#Web-Applications-Prototyping) <br>
   4.6. [Domain-Driven Software Architecture](#Domain-Driven-Software-Architecture) <br>
      4.6.1. [Software Architecture Context Diagram](#Software-Architecture-Context-Diagram) <br>
      4.6.2. [Software Architecture Container Diagrams](#Software-Architecture-Container-Diagrams) <br>
      4.6.3. [Software Architecture Components Diagrams](#Software-Architecture-Components-Diagrams) <br>
   4.7. [Software Object-Oriented Design](#Software-Object-Oriented-Design) <br>
      4.7.1. [Class Diagrams](#Class-Diagrams) <br>
      4.7.2. [Class Dictionary](#Class-Dictionary) <br>
   4.8. [Database Design](#Database-Design) <br>
      4.8.1. [Database Diagram](#Database-Diagram) <br>
5. [CAPÍTULO V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation--Validation--Deployment) <br>
   5.1. [Software Configuration Management](#Software-Configuration-Management) <br>
      5.1.1. [Software Development Environment Configuration](#Software-Development-Environment-Configuration) <br>
      5.1.2. [Source Code Management](#Source-Code-Management) <br>
      5.1.3. [Source Code Style Guide & Conventions](#Source-Code-Style-Guide--Conventions) <br>
      5.1.4. [Software Deployment Configuration](#Software-Deployment-Configuration) <br>
   5.2. [Landing Page, Services & Applications Implementation](#Landing-Page--Services--Applications-Implementation) <br>
      5.2.1. [Sprint 1](#Sprint-1) <br>
         5.2.1.1. [Sprint Planning 1](#Sprint-Planning-1) <br>
         5.2.1.2. [Sprint Backlog 1](#Sprint-Backlog-1) <br>
         5.2.1.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review) <br>
         5.2.1.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review) <br>
         5.2.1.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review) <br>
         5.2.1.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review) <br>
         5.2.1.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review) <br>
         5.2.1.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint) <br>
      5.2.2. [Sprint 2](#Sprint-2) <br>
         5.2.2.1. [Sprint Planning 2](#Sprint-Planning-2) <br>
         5.2.2.2. [Sprint Backlog 2](#Sprint-Backlog-2) <br>
         5.2.2.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-2)<br> 
         5.2.2.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-2) <br>
         5.2.2.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-2) <br>
         5.2.2.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-2) <br>
         5.2.2.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-2) <br>
         5.2.2.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-2) <br>
      5.2.3. [Sprint 3](#Sprint-3) <br>
         5.2.3.1. [Sprint Planning 3](#Sprint-Planning-3) <br>
         5.2.3.2. [Sprint Backlog 3](#Sprint-Backlog-3) <br>
         5.2.3.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-3) <br>
         5.2.3.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-3) <br>
         5.2.3.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-3) <br>
         5.2.3.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-3) <br>
         5.2.3.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-3) <br>
         5.2.3.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-3) <br>
      5.2.4. [Sprint 4](#Sprint-4) <br>
         5.2.4.1. [Sprint Planning 4](#Sprint-Planning-4) <br>
         5.2.4.2. [Sprint Backlog 4](#Sprint-Backlog-4) <br>
         5.2.4.3. [Development Evidence for Sprint Review](#Development-Evidence-for-Sprint-Review-4) <br>
         5.2.4.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-Evidence-for-Sprint-Review-4) <br>
         5.2.4.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review-4) <br>
         5.2.4.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint-Review-4) <br>
         5.2.4.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint-Review-4) <br>
         5.2.4.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint-4) <br>
   5.3. [Validation & Testing](#Validation--Testing) <br>
      5.3.1. [Testing Plan](#Testing-Plan) <br>
      5.3.2. [Quality Assurance](#Quality-Assurance) <br>
      5.3.3. [User Acceptance Testing (UAT)](#User-Acceptance-Testing-UAT) <br>
   5.4. [Product Deployment](#Product-Deployment) <br>
      5.4.1. [Deployment Plan](#Deployment-Plan) <br>
      5.4.2. [Deployment Process](#Deployment-Process) <br>
      5.4.3. [Post-Deployment Review](#Post-Deployment-Review) <br>
6. [CAPÍTULO VI: Appendix](#Capítulo-VI-Appendix) <br>
   6.1. [References](#References) <br>
   6.2. [Glossary](#Glossary) <br>
   6.3. [Acronyms](#Acronyms) <br>
   6.4. [Bibliography](#Bibliography)<br>




# CAPÍTULO I: Introducción
## Startup Profile
### Descripción de la Startup
Nombre del Proyecto: BookSphere

#### Descripción General:
<div style="text-align: justify">
SphereHub es nuestra empresa innovadora que une la pasión por la lectura y la tecnología con el objetivo de transformar la manera en que las personas acceden a los libros y materiales educativos. Al igual que Steam revolucionó la distribución de videojuegos, BookSphere nuestro producto, busca convertirse en la plataforma de referencia para el acceso y la exploración de libros, audiolibros, y recursos de estudio en formato digital.
<div/>

Nuestra plataforma principal, BookSphere, permite a los usuarios explorar una vasta colección de libros y audiolibros, acceder a reseñas, y visualizar información detallada antes de decidir qué leer. BookSphere no solo es un lugar para descubrir nuevos títulos, sino también para sumergirse en el contenido de una manera interactiva y personalizada.

#### Colaboraciones Estratégicas:
En BookSphere, estamos comprometidos a establecer sólidas alianzas con editoriales, autores independientes, e instituciones educativas. Trabajamos en estrecha colaboración con ellos para garantizar que nuestros usuarios tengan acceso a una biblioteca digital en constante expansión, donde se destacan tanto las obras clásicas como las contemporáneas. Invitamos a los autores y las editoriales a cargar versiones digitales de sus libros y otros materiales educativos, enriqueciendo nuestra plataforma y ampliando las opciones disponibles para los lectores.

#### Innovación y Tecnología:
Nuestra plataforma utiliza tecnologías avanzadas para ofrecer una experiencia inmersiva a los usuarios. Desde la capacidad de visualizar adelantos y reseñas en formato interactivo hasta la personalización del contenido basado en los intereses del usuario, BookSphere busca redefinir la forma en que las personas interactúan con los libros y el conocimiento. Queremos que cada usuario se sienta como un explorador en un vasto universo literario, con acceso inmediato a los recursos que necesita para aprender, crecer y disfrutar.

#### Comunidad y Funciones Sociales:
BookSphere no es solo una plataforma para leer y aprender; es también un espacio social donde los usuarios pueden conectarse con otros lectores, compartir opiniones, y descubrir nuevas perspectivas. La plataforma incluye funciones de red social que permiten a los usuarios dejar comentarios y reseñas, participar en discusiones sobre libros, y seguir a otros miembros de la comunidad con intereses similares. Esta característica fomenta la creación de una comunidad vibrante y comprometida, donde los lectores pueden intercambiar ideas y recomendaciones, creando un ambiente enriquecedor y colaborativo.

#### Visión:
Visualizamos un mundo donde la tecnología y la lectura se fusionan para crear experiencias enriquecedoras y accesibles para todos. Nuestro objetivo es que BookSphere sea sinónimo de innovación en el mundo de la literatura y la educación, un lugar donde los usuarios puedan descubrir y disfrutar de libros y materiales educativos de manera más intuitiva y conectada. Aspiramos a crear una sociedad donde el conocimiento esté al alcance de todos, y donde el acceso a los recursos educativos sea tan sencillo y emocionante como explorar una biblioteca infinita.

#### Misión:
Nos esforzamos por proporcionar una plataforma que conecte a los lectores y estudiantes con una vasta colección de recursos educativos a través de una experiencia digital avanzada. Estamos decididos a utilizar la tecnología para generar un impacto positivo en el acceso al conocimiento y la educación. BookSphere será símbolo de pasión por la lectura, innovación en la distribución de libros, y compromiso con el aprendizaje continuo, mientras fomentamos una comunidad activa y participativa en torno a la literatura y el conocimiento.

### Perfiles de integrantes del equipo
| Integrante | Descripción |
| ---- | --- |
| ![Sergio](https://hackmd.io/_uploads/SkU_5d9cR.png) | Sergio André Gómez Vallejos – Ingeniería de Software – u20221d401 <br> Soy una persona resiliente que, sin importar cuántas veces caiga, siempre encuentra la manera de levantarse. Tengo habilidades sociales sólidas y una amplia experiencia en la resolución de problemas de código. Suelo ser el miembro más activo de mi equipo de trabajo. Me apasionan los lenguajes de programación y la tecnología, y constantemente me esfuerzo por alcanzar mis objetivos y contribuir al desarrollo del startup. |
| ![fotoperfilMerly](https://hackmd.io/_uploads/H1jAVj9cA.jpg) | Merly Salon Puerta – Ingeniería de Software – U20201b772 <br>A lo largo de mi vida he adquirido diversos valores éticos los cuales son la base en todas las áreas de mi vida. Estoy comprometida a aportar de diversas formas para el desarrollo del proyecto con mucho optimismo y entusiasmo. Participaré activamente en las actividades grupales para culminar el proyecto de manera satisfactoria. |
| ![FotoPerfil4](https://hackmd.io/_uploads/rJGKndc5A.jpg) | Pedro Jesús Nanfuñay Liza - Ingeniería de Software - U202215462<br>Me considero una persona responsable y perseverante, siempre dispuesto a participar y colaborar con mi equipo. Cuento con conocimientos en varios lenguajes de programación y una fuerte pasión por investigar y conocer el desarrollo de las nuevas tecnologías. Mi objetivo es culminar este proyecto de manera satisfacoria.|
| ![Captura de pantalla 2024-08-15 121605](https://hackmd.io/_uploads/ByWzO2icC.png)| Russell Stephen Romero Qwistgaard - Ingeniería de Software - U202211043 <br>  |
|![Ronaldo](https://hackmd.io/_uploads/BJXwMC1sR.jpg)|Ronaldo Macedonio Fabian Puente - Ingeniería de Software - U20201b193<br>Me comprometo a desarrollar el trabajo en equipo hasta completar los objetivos planteados.|



## Solution Profile
### Antecedentes y problemática
#### Antecedentes
WHO?
SphereHub es una empresa que está posicionada para revolucionar la manera en que las personas acceden a los libros y materiales educativos en formato digital. Está dirigida tanto a lectores apasionados como a estudiantes, autores independientes, editoriales y a instituciones educativas.

WHAT?
BookSphere busca convertirse en la plataforma de referencia para la exploración y acceso a libros, audiolibros, y recursos educativos digitales. A través de su innovadora plataforma, los usuarios pueden explorar una amplia variedad de contenidos literarios y educativos, acceder a reseñas detalladas, y sumergirse en una experiencia de lectura personalizada e interactiva.

WHERE?
La plataforma de BookSphere opera principalmente en el entorno digital, lo que le permite llegar a usuarios globalmente. Aunque se enfoca en mercados donde el acceso a recursos educativos y libros digitales está creciendo, su visión es convertirse en una plataforma globalmente reconocida y utilizada.

WHEN?
La necesidad de una plataforma como BookSphere surge en un contexto donde la digitalización de contenidos ha transformado muchas industrias, incluyendo la literaria y educativa. Con el aumento del uso de dispositivos digitales para el consumo de medios y la creciente demanda de acceso flexible a recursos educativos, el momento actual es ideal para la implementación de una solución como BookSphere.

WHY?:
La misión de BookSphere es democratizar el acceso al conocimiento y la educación, haciendo que sea tan sencillo y emocionante como explorar una biblioteca infinita. En un mundo donde la educación es clave para el desarrollo personal y profesional, BookSphere busca eliminar las barreras al acceso a los libros y materiales educativos, brindando a los usuarios una experiencia inmersiva y personalizada.

HOW?
BookSphere utiliza tecnología avanzada para ofrecer una plataforma que no solo permite la descarga y lectura de libros, sino que también incluye funciones interactivas como adelantos de contenido, personalización de recomendaciones, y un espacio social donde los usuarios pueden compartir opiniones y participar en discusiones sobre literatura y educación.

HOW MUCH?
El costo de implementación y desarrollo de la plataforma es significativo debido a la necesidad de integrar tecnología avanzada y establecer alianzas estratégicas con autores, editoriales, y otras entidades. Sin embargo, los beneficios potenciales en términos de expansión del acceso al conocimiento y la creación de una comunidad lectora activa justifican esta inversión.

#### Problemática
**WHO?**
Los principales afectados por la falta de una plataforma como BookSphere son los lectores y estudiantes que buscan acceso a una amplia gama de recursos literarios y educativos, pero enfrentan barreras debido a la disponibilidad limitada, los altos costos de los libros físicos, o la falta de interactividad en las plataformas actuales.

**WHAT?**
La problemática radica en la falta de una plataforma digital centralizada y accesible que combine una extensa biblioteca de recursos educativos y literarios con tecnologías interactivas que mejoren la experiencia del usuario. A pesar de la digitalización, muchas plataformas existentes carecen de un enfoque integral que ofrezca una experiencia personalizada y socialmente conectada.

**WHERE?**
La necesidad se siente a nivel global, pero es más acentuada en regiones donde el acceso a libros y recursos educativos es limitado, ya sea por restricciones económicas, geográficas o tecnológicas.

**WHEN?**
El problema es especialmente relevante en la era actual, donde el aprendizaje continuo y el acceso a la información son cruciales para el éxito personal y profesional. Sin una plataforma como BookSphere, el acceso al conocimiento se mantiene fragmentado y desigual.

**WHY?**
La falta de acceso adecuado a recursos educativos y literarios limita las oportunidades de aprendizaje y crecimiento personal. Además, la ausencia de una plataforma que combine funcionalidad, accesibilidad y una experiencia de usuario envolvente perpetúa la desconexión entre el contenido educativo disponible y los usuarios que más lo necesitan.

**HOW?**
Actualmente, la mayoría de las plataformas digitales están fragmentadas en términos de funcionalidad y acceso, con muchas enfocadas únicamente en la venta de libros sin considerar la experiencia integral del usuario o la creación de comunidades de lectores. Esto crea una brecha en la cual los usuarios no pueden disfrutar plenamente de los beneficios de la digitalización.

**HOW MUCH?**
La falta de acceso a una plataforma como BookSphere puede resultar en un costo significativo para los usuarios en términos de oportunidades educativas perdidas, el tiempo invertido en buscar recursos dispersos, y la falta de una comunidad de apoyo para compartir y discutir conocimientos.

### Lean UX Process
#### Lean UX Problem Statements
Russel
#### Lean UX Assumptions
Russel
#### Lean UX Hypothesis Statements
Russel
#### Lean UX Canvas
Russel
### Segmentos objetivo
#### 1. Lectores Ávidos Particulares o Estudiantes:

Este segmento objetivo abarca a lectores apasionados y estudiantes que buscan acceder a una amplia variedad de libros y audiolibros, ya sea por interés personal o para cumplir con sus obligaciones académicas. Estos usuarios valoran la accesibilidad, la diversidad de títulos, y la posibilidad de personalizar su experiencia de lectura. Además, están interesados en interactuar con otros lectores a través de reseñas y comunidades en línea que enriquecen su experiencia literaria.


#### 2. Instituciones Educativas:
El segundo segmento objetivo incluye a instituciones educativas, editoriales y autores independientes que desean distribuir sus obras o recursos educativos de manera más eficiente y llegar a un público más amplio. Estos actores valoran una plataforma que les permita gestionar sus contenidos de forma digital y mantener un control sobre su distribución, con la posibilidad de obtener ingresos a través de suscripciones o ventas directas. Además, les interesa participar en una comunidad donde puedan interactuar con lectores, recibir feedback, y promover sus obras.


####  Variable geográfica:

País: Perú
Ciudad: Zonas urbanas y suburbanas
    
Variable demográfica:

Género: Femenino / Masculino
Ocupación: Estudiantes, lectores, instituciones educativas, editores, autores independientes
Estado civil: Todos los estados
Edad y etapa del ciclo de vida: Ciudadanos mayores de 15 años

#### Variable psicográfica:

Nivel Socioeconómico (NSE): Todos los niveles socioeconomicos
Características de personalidad: Curiosidad, deseo de aprendizaje continuo, aprecio por la lectura, compromiso con la educación y el desarrollo personal
    
# Capítulo II: Requirements Elicitation & Analysis
## Competidores
BookSphere enfrenta competencia de plataformas como Google Play Books, Audible y Scribd. Google Play Books proporciona una amplia gama de libros electrónicos y audiolibros, pero carece de una componente social. Audible, especializado en audiolibros, ofrece una gran biblioteca y buena integración con dispositivos Amazon, aunque no cuenta con funciones comunitarias. Scribd ofrece acceso ilimitado a diversos contenidos digitales bajo suscripción, pero su interacción social es limitada. A diferencia de estos competidores, BookSphere destaca por integrar una comunidad literaria activa, permitiendo a los usuarios compartir reseñas y participar en discusiones, lo que enriquece la experiencia del usuario.
## Análisis Competitivo
<table>
   <tr>
      <td align="center" colspan="6">Competitive Analysis Landscaspe</td>
   </tr>
   <tr>
      <td colspan="2">¿Porqué llevar a cabo este análisis?</td><td colspan="4">¿Cómo podemos proporcionar un buen servicio entre los restaurantes y los consumidores de manera que la comunicación entre ambos sea efectiva y agradable?</td>
   </tr>
   <tr align="center">
      <td colspan="2"><td>SphereHub<br><img src="https://hackmd.io/_uploads/S15TtAi90.jpg" alt="Google Play Books" style="max-width: 80px;"/></td><td>Google Play Books<br><img src="https://hackmd.io/_uploads/SkbrwAo5A.jpg" alt="Google Play Books" style="max-width: 80px;"/></td><td>Audible<br><img src="https://hackmd.io/_uploads/S191dAo5C.png" alt="Audible" style="max-width: 80px;"/></td><td>Scribd<br><img src="https://hackmd.io/_uploads/SJ4_u0i9R.png" alt="Audible" style="max-width: 90px;"/></td>
   </tr>




   <tr>
      <td rowspan="2">Perfil</td><td>Overview</td><td> SphereHub es una empresa emergente que, a través de BookSphere, busca revolucionar el acceso a libros y recursos educativos digitales. Integrando una experiencia inmersiva y social, BookSphere se posiciona como una plataforma integral para estudiantes y lectores que desean descubrir, interactuar y compartir conocimientos.	 </td><td>Google Play Books ofrece un extenso catálogo de libros digitales y audiolibros, con opciones de compra y alquiler directamente en la plataforma de Google.</td><td> Audible, una subsidiaria de Amazon, se especializa en audiolibros y contenido de audio, ofreciendo una vasta colección de títulos y suscripciones.</td><td> Scribd es un servicio de suscripción que ofrece acceso a una vasta biblioteca digital de libros, audiolibros, documentos y más. Su modelo de suscripción todo en uno lo convierte en una opción popular para consumidores de contenido digital. </td>
   </tr>
   <tr>
      <td>Ventaja competitiva. ¿Qué valor ofrece a los clientes?</td><td> BookSphere se diferencia por combinar el acceso a libros con una comunidad interactiva, similar a la experiencia de Steam, donde los usuarios pueden dejar reseñas, comentarios y participar en foros relacionados con la literatura.</td><td> Google Play Books ofrece una integración nativa con Android, y su modelo permite a los usuarios comprar títulos específicos sin necesidad de suscripción.</td><td> Audible cuenta con una extensa selección de audiolibros exclusivos y la integración con dispositivos Amazon, como Alexa, lo que mejora la experiencia del usuario.	 </td><td> Scribd ofrece un acceso ilimitado a su biblioteca por una suscripción mensual, cubriendo una amplia gama de géneros y formatos.	 </td>
   </tr>
   <tr>
      <td rowspan="2">Perfil de Marketing</td><td>Mercado Objetivo</td><td>  Nos enfocamos en lectores apasionados y estudiantes que buscan una plataforma digital intuitiva para acceder a libros, audiolibros y recursos educativos. Además, nuestro objetivo es colaborar con editoriales, autores independientes e instituciones educativas que desean distribuir sus obras de manera innovadora y llegar a un público más amplio. </td><td> Usuarios de dispositivos Android que buscan conveniencia en la adquisición de contenido digital.
 </td><td> Consumidores que prefieren la experiencia auditiva para leer, incluyendo profesionales y entusiastas de la literatura.	 </td><td> Lectores generales que consumen una variedad de contenido digital, desde libros hasta revistas y documentos.	 </td>
   </tr>
   <tr>
      <td>Estrategias de Marketing</td><td> SphereHub planea enfocarse en campañas digitales dirigidas a instituciones educativas y crear alianzas estratégicas con editoriales y universidades. Además, promoverá la plataforma en redes sociales y a través de influencers literarios.	 </td><td> Google Play Books se apoya en la preinstalación en dispositivos Android y en su visibilidad dentro del ecosistema Google para llegar a un público amplio.
 </td><td> Audible invierte en campañas de marketing masivas, especialmente a través de Amazon y dispositivos Alexa, destacando su oferta de prueba gratuita y su contenido exclusivo.	 </td><td> Scribd apuesta por publicidad online y alianzas con creadores de contenido. También se enfoca en la retención mediante recomendaciones personalizadas y una experiencia sin interrupciones.	 </td>
   </tr>
   <tr>
      <td rowspan="3">Perfil de Producto</td><td>Productos & Servicios</td><td> Acceso a una amplia variedad de libros, audiolibros, y recursos educativos, junto con funcionalidades sociales para mejorar la interacción y el descubrimiento de contenido.	 </td><td> Libros digitales, audiolibros, revistas.
 </td><td> Audiolibros, podcasts, contenido exclusivo.	 </td><td> Libros, audiolibros, documentos, artículos, revistas.	 </td>
   </tr>
   <tr>
      <td>Precios & Costos</td><td> Ofreceremos un modelo flexible similar al de Steam, pero centrado en libros y audiolibros, con opciones de compra individual y suscripciones que permiten a los usuarios acceder a una vasta colección de contenido digital. </td><td> Compra individual de títulos.
 </td><td> Suscripción mensual para un crédito mensual, con opciones de compra adicional.	 </td><td> Suscripción mensual con acceso ilimitado.	 </td>
   </tr>
   <tr>
      <td>Canales de distribución (Web y/o Móvil)</td><td> Disponible en la web y como app móvil, con sincronización de progreso en múltiples dispositivos.	 </td><td> Web, iOS, Android. </td><td> Web, iOS, Android, dispositivos Alexa.	 </td><td> Web, iOS, Android, Kindle.	
 </td>
   </tr>

   <tr>
      <td rowspan="5">Análisis SWOT</td><td>Fortalezas</td><td> Comunidad interactiva, integración de funcionalidades sociales, enfoque en estudiantes y lectores serios.	 </td><td> Gran alcance y facilidad de acceso a través de dispositivos Android y Google.
 </td><td> Gran selección de contenido exclusivo y alto enfoque en la experiencia auditiva.	 </td><td> Acceso ilimitado a una biblioteca extensa por una tarifa plana.	 </td>
   </tr>
   <tr>
      <td>Debilidades</td><td> Dependencia inicial de alianzas estratégicas para construir una biblioteca robusta.	 </td><td> Competencia con otras plataformas de Google en el mismo ecosistema. </td><td> Alto costo si el usuario desea más de un libro al mes.	 </td><td> Puede saturarse el contenido debido a la amplitud de la biblioteca.	 </td>
   </tr>
   <tr>
      <td>Oportunidades</td><td> Crecimiento en el sector educativo, expansión a mercados internacionales, adopción de tecnologías emergentes.	 </td><td> Expansión en mercados donde Android es dominante. </td><td> Creciente popularidad de los audiolibros y podcasts.	 </td><td> Expansión a otros mercados verticales, como educación.	 </td>
   </tr>
   <tr>
      <td>Amenazas</td><td> Competencia fuerte en el mercado de libros digitales, barreras tecnológicas para la expansión en comunidades sin acceso a internet de alta calidad.	 </td><td> Competencia dentro del propio ecosistema de Google y otras apps con modelos más atractivos. </td><td> Nuevos jugadores en el mercado de audiolibros o cambios en las preferencias de consumo.	 </td><td> Competencia con plataformas de distribución más grandes, como Amazon.	 </td>
   </tr>

</table> 

<br/>


## Estrategias y tácticas frente a competidores
BookSphere VS Audible, Scribd, Google Play Books

### Estrategias:

Diferenciación: BookSphere se diferencia al ofrecer una plataforma interactiva que combina el acceso a libros, audiolibros y recursos educativos con características sociales, como la posibilidad de compartir reseñas, comentarios, y participar en comunidades de lectores. Esta integración de contenido y red social crea una experiencia de usuario única que no se encuentra en los competidores tradicionales.

Enfoque en el usuario: BookSphere se enfoca en entender las preferencias y comportamientos de sus usuarios, personalizando la experiencia de navegación y recomendación de libros y recursos. A través de algoritmos avanzados, la plataforma adaptará su contenido para ofrecer recomendaciones relevantes, manteniendo a los usuarios comprometidos y leales a la plataforma.

Alianzas estratégicas: BookSphere buscará establecer colaboraciones con editoriales, autores independientes y entidades educativas para expandir su catálogo digital. Además, creará alianzas con influencers y comunidades de lectores online para promover la plataforma y atraer a nuevos usuarios, generando un efecto de red que fortalezca su posición en el mercado.

### Tácticas:

Mejora tecnológica constante: BookSphere implementará mejoras continuas en su plataforma utilizando tecnologías avanzadas, como inteligencia artificial para recomendaciones personalizadas, análisis de comportamiento del usuario, y características de gamificación para fomentar la interacción dentro de la comunidad. También se actualizarán las opciones de lectura y escucha, como modos offline y sincronización entre dispositivos.

Análisis de la competencia: BookSphere realizará un análisis constante de los movimientos y estrategias de competidores como Audible, Scribd, y Google Play Books. Este análisis permitirá ajustar las tácticas de marketing y producto, asegurando que BookSphere se mantenga a la vanguardia en términos de innovación y satisfacción del usuario.

Integración de la comunidad: BookSphere se centrará en fortalecer su componente de red social, incentivando la participación de los usuarios a través de desafíos de lectura, clubes de lectura virtuales, y eventos en línea. La plataforma también ofrecerá incentivos, como acceso anticipado a nuevos títulos o descuentos en membresías, para usuarios activos y comprometidos en la comunidad.
## Entrevistas
### Diseño de entrevistas
## 1. Segmento Objetivo: Lectores Ávidos Particulares o Estudiantes
Nuestra plataforma, BookSphere, ha desarrollado una serie de preguntas orientadas a comprender las necesidades, experiencias y expectativas de los lectores particulares y estudiantes en relación con el acceso a libros y materiales educativos en formato digital. Sabemos que, para este segmento, la disponibilidad, el precio y la experiencia de usuario son factores clave para elegir una plataforma de lectura. Nuestro objetivo es identificar cómo BookSphere puede satisfacer estas necesidades ofreciendo una biblioteca digital completa, accesible y con funcionalidades avanzadas. Además, buscamos explorar qué características interactivas podrían enriquecer la experiencia del usuario y fomentar un entorno de aprendizaje dinámico. Con estas entrevistas, buscamos no solo validar nuestras hipótesis, sino también adaptar nuestra oferta para garantizar que los lectores encuentren en BookSphere un recurso valioso y conveniente.
## Preguntas Principales:
1. ¿Con qué frecuencia lees libros o audiolibros en formato digital?
2. ¿Qué características buscas en una plataforma de libros digitales?
3. ¿Cómo sueles descubrir nuevos libros para leer?
4. ¿Qué tipo de contenidos prefieres: libros, audiolibros, o ambos?
5. ¿Qué valoras más al seleccionar un libro para leer (reseñas, recomendaciones, adelantos, etc.)?
6. ¿Cómo te gustaría que una plataforma te ayudara a organizar y gestionar tu lectura?
7. ¿Utilizas alguna plataforma actual para discutir libros con otros lectores? ¿Qué te gusta o disgusta de esa experiencia?
8. ¿Qué tan importante es para ti la personalización de las recomendaciones de libros?
9. ¿Cómo te sentirías si pudieras interactuar directamente con autores a través de una plataforma?
10. ¿Qué mejorarías en las plataformas de libros digitales que ya usas?

## 2. Segmento Objetivo: Instituciones Educativas
BookSphere se enfoca en facilitar la distribución y acceso a materiales educativos y libros de todo tipo a través de una plataforma digital. En este segmento, las entrevistas estarán dirigidas a comprender las expectativas y necesidades de instituciones educativas, editoriales y autores independientes que desean llegar a un público más amplio mediante la digitalización y distribución de sus contenidos. Preguntaremos sobre los desafíos actuales que enfrentan en la distribución de sus libros, la facilidad para integrarse a plataformas digitales, y qué funcionalidades consideran importantes para maximizar la exposición y las ventas. Además, indagaremos sobre la disposición para colaborar con una plataforma como BookSphere, que busca ofrecer una solución centralizada y eficiente para la distribución de contenidos digitales. Con estas entrevistas, pretendemos ajustar nuestra estrategia para convertirnos en un aliado clave para las instituciones y autores.
## Preguntas principales: 

1. ¿Cuáles son tus principales desafíos al distribuir libros o materiales educativos en formato digital?
2. ¿Qué factores consideras al elegir una plataforma para publicar tus obras?
3. ¿Cómo valoras la visibilidad y el alcance que te ofrece una plataforma de libros digitales?
4. ¿Qué tipo de herramientas o funcionalidades te gustaría que una plataforma te ofreciera para promocionar tus libros o materiales?
5. ¿Qué importancia tiene para ti el feedback de los lectores en la plataforma?
6. ¿Cómo manejas actualmente la relación con tus lectores? ¿Cómo crees que una plataforma digital podría mejorar esa relación?
7. ¿Qué tan relevante es la seguridad y protección de los derechos de autor en una plataforma digital?
8. ¿Qué esperas en términos de análisis de datos o reportes sobre el rendimiento de tus libros en la plataforma?
9. ¿Cómo te gustaría que una plataforma te apoyara en la creación de una comunidad alrededor de tu obra?
10. ¿Qué papel juega la interacción con otras editoriales, autores o instituciones en tu estrategia de publicación?
## Registro de entrevistas
### Segmento: Estudiantes

### Análisis de entrevistas
    
#### Entrevista 1
| **Información del entrevistado** | 
|--------------------------|
| **Timing de entrevista:**   ... - ... |
| **Nombre:**  Saico Gonzales José Fernando |
| **Edad:**  19 años |
| **Procedencia:**  Lima, Carabayllo |
| ![Entrevista1](https://hackmd.io/_uploads/HkebyaCqC.png)|
| **Resumen:** José Gonzales, estudiante que utiliza libros y audiolibros digitales al menos dos o tres veces por semana, valora una amplia variedad de títulos y una interfaz intuitiva en las plataformas. Prefiere combinar libros para estudios y audiolibros para actividades multitarea. Descubre nuevos libros a través de recomendaciones y reseñas, y busca funciones como listas de lectura personalizadas y recordatorios de lectura en las plataformas. Aprecia la personalización de recomendaciones y le gustaría interactuar con autores. Sin embargo, encuentra que la interacción en plataformas actuales a veces es limitada y desea mejoras en la interactividad y organización de las plataformas.  . |

## Needfinding
### User Personas
#### Segmento 1: Lectores Ávidos Particulares o Estudiantes
![User Persona - S1](https://hackmd.io/_uploads/BkPhy3C5C.png)

### User Task Matrix
Ronaldo 
    
    

| User Task                                       | Lectores Ávidos Particulares o Estudiantes (Frecuencia) | Lectores Ávidos Particulares o Estudiantes (Importancia) | Instituciones Educativas (Frecuencia) | Instituciones Educativas (Importancia) |
|--------------------------------------------|--------------------------------------------------------|---------------------------------------------------------|---------------------------------------|----------------------------------------|
| Explorar Colección de Libros               | Always                                                | High                                                    | Sometimes                             | Medium                                 |
| Buscar y Filtrar Libros                    | Always                                                | High                                                    | Never                                 | Low                                    |
| Leer Reseñas y Calificaciones              | Sometimes                                             | Medium                                                  | Always                                | High                                   |
| Leer Muestras de Libros                    | Always                                                | High                                                    | Never                                 | Low                                    |
| Comprar o Descargar Libros                 | Always                                                | High                                                    | Never                                 | Low                                    |
| Dejar Comentarios y Reseñas                | Always                                                | High                                                    | Never                                 | Low                                    |
| Participar en Discusiones sobre Libros     | Always                                                | High                                                    | Never                                 | Low                                    |
| Seguir a Otros Usuarios                    | Sometimes                                             | Medium                                                  | Sometimes                             | Medium                                 |
| Cargar Libros Digitales                    | Never                                                 | Low                                                     | Always                                | High                                   |
| Actualizar Información del Libro           | Never                                                 | Low                                                     | Always                                | High                                   |
| Gestionar Perfil y Obras Publicadas        | Sometimes                                             | Low                                                     | Always                                | High                                   |
| Acceder a Estadísticas de Lectura          | Sometimes                                             | Low                                                     | Always                                | High                                   |
| Colaborar en Proyectos Educativos          | Never                                                 | Low                                                     | Always                                | High                                   |
| Gestionar Derechos y Licencias             | Never                                                 | Low                                                     | Always                                | High                                   |
| Verificación y Aprobación de Contenidos    | Never                                                 | Low                                                     | Always                                | High                                   |



    

### User Journey Mapping
Sergio :,v (se necesita los user personas)
### Empathy Mapping
#### Segmento 1: Lectores Ávidos Particulares o Estudiantes
![Empathy Map - S1](https://hackmd.io/_uploads/SypMg3R50.png)

### As-is Scenario Mapping
Ronaldo
## Ubiquitous Language
**1. Avid Reader (Lector Ávido)**
Un individuo apasionado por la lectura que busca constantemente nuevos libros y contenido literario. Suelen estar muy comprometidos con comunidades y discusiones relacionadas con libros.
    
**2. Digital Library (Biblioteca Digital)**
Una colección de libros, audiolibros y otros materiales educativos disponibles en formato digital y accesibles a través de una plataforma en línea.
    
**3. Interactive Content (Contenido Interactivo)**
Contenido digital que permite a los usuarios interactuar de diversas maneras, como mediante vistas previas interactivas, elementos multimedia o características personalizadas.
    
**4. Personalized Recommendations (Recomendaciones Personalizadas)**
Sugerencias de libros o materiales educativos adaptadas a los intereses, historial de lectura o metas de aprendizaje de un individuo, a menudo generadas mediante algoritmos o preferencias del usuario.
    
**5. Content Management (Gestión de Contenidos)**
El proceso de organizar, actualizar y mantener el contenido digital en una plataforma, incluyendo la carga de nuevos materiales y la gestión de los existentes.
    
**6. User Engagement (Participación del Usuario)**
 El nivel de interacción e involucramiento que un usuario tiene con la plataforma, incluyendo actividades como la lectura, reseñas y participación en discusiones comunitarias.
    
**7. Author Interaction (Interacción con el Autor)**
La capacidad para que los usuarios se relacionen directamente con los autores a través de funciones como sesiones de preguntas y respuestas, chats en vivo o blogs de autores.
    
**8. Feedback Loop (Ciclo de Retroalimentación)**
El proceso mediante el cual se recopila la retroalimentación de los usuarios y se utiliza para mejorar la plataforma o el contenido, incluyendo reseñas y calificaciones.
    
**9. Educational Resources (Recursos Educativos)**
Materiales diseñados para apoyar el aprendizaje y la educación, como libros de texto, guías de estudio y contenido instructivo.
    
**10. Content Visibility (Visibilidad del Contenido)**
El grado en que el contenido digital es accesible y descubrible para los usuarios, influenciado por factores como la funcionalidad de búsqueda y las herramientas de promoción.
    
**11. Publisher Partnership**
Asociación con Acuerdos colaborativos entre la plataforma y las editoriales para distribuir y promover libros y materiales educativos.
    
**12. Digital Rights Management (DRM) (Gestión de Derechos Digitales)**
Tecnología y políticas utilizadas para proteger el contenido digital contra la distribución no autorizada y la piratería, asegurando que los autores y editores mantengan el control sobre su trabajo.
    
**13. Community Features (Funciones Comunitarias)**
Herramientas y funcionalidades que facilitan la interacción y el compromiso de los usuarios dentro de la plataforma, como foros de discusión, reseñas de usuarios y opciones de compartir en redes sociales.
    
**14. Platform Usability (Usabilidad de la Plataforma)**
 La facilidad con la que los usuarios pueden navegar y utilizar la plataforma, incluyendo aspectos como el diseño intuitivo, la accesibilidad y el soporte al usuario.
    
**15. Content Updates (Actualizaciones de Contenido)**
El proceso de modificar o agregar nuevas versiones de materiales digitales, incluyendo revisiones, nuevas ediciones o correcciones de contenido existente.
# Capítulo III: Requirements Specification
## To-Be Scenario Mapping
texto
## User Stories
texto
## Impact Mapping
texto
## Product Backlog
texto
# Capítulo IV: Product Design
## Style Guidelines
### General Style Guidelines
texto
### Web Style Guidelines
texto
## Information Architecture
### Organization Systems
texto
### Labeling Systems
texto
### SEO Tags and Meta Tags
texto
### Searching Systems
texto
### Navigation Systems
texto
## Landing Page UI Design
### Landing Page Wireframe
texto
### Landing Page Mock-up
texto
## Web Applications UX/UI Design
### Web Applications Wireframes
texto
### Web Applications Wireflow Diagrams
texto
### Web Applications Mock-ups
texto
### Web Applications User Flow Diagrams
texto
## Web Applications Prototyping
texto
## Domain-Driven Software Architecture
### Software Architecture Context Diagram
texto
### Software Architecture Container Diagrams
texto
### Software Architecture Components Diagrams
texto
## Software Object-Oriented Design
### Class Diagrams
texto
### Class Dictionary
texto
## Database Design
### Database Diagram
texto
# Capítulo V: Product Implementation, Validation & Deployment
## Software Configuration Management
### Software Development Environment Configuration
texto
### Source Code Management
texto
### Source Code Style Guide & Conventions
texto
### Software Deployment Configuration
texto
## Landing Page, Services & Applications Implementation
### Sprint 1
#### Sprint Planning 1
texto
#### Sprint Backlog 1
texto
#### Development Evidence for Sprint Review
texto
#### Testing Suite Evidence for Sprint Review
texto
#### Execution Evidence for Sprint Review
texto
#### Services Documentation Evidence for Sprint Review
texto
#### Software Deployment Evidence for Sprint Review
texto
#### Team Collaboration Insights during Sprint
texto
### Sprint 2
#### Sprint Planning 2
texto
#### Sprint Backlog 2
texto
#### Development Evidence for Sprint Review
texto
#### Testing Suite Evidence for Sprint Review
texto
#### Execution Evidence for Sprint Review
texto
#### Services Documentation Evidence for Sprint Review
texto
#### Software Deployment Evidence for Sprint Review
texto
#### Team Collaboration Insights during Sprint
texto
### Sprint 3
#### Sprint Planning 3
texto
#### Sprint Backlog 3
texto
#### Development Evidence for Sprint Review
texto
#### Testing Suite Evidence for Sprint Revie
texto
#### Execution Evidence for Sprint Review
texto
#### Services Documentation Evidence for Sprint Review
texto
#### Software Deployment Evidence for Sprint Review
texto
#### Team Collaboration Insights during Sprint
texto
### Sprint 4
#### Sprint Planning 4
texto
#### Sprint Backlog 4
texto
#### Development Evidence for Sprint Review
texto
#### Testing Suite Evidence for Sprint Review
texto
#### Execution Evidence for Sprint Review
texto
#### Services Documentation Evidence for Sprint Review
texto
#### Software Deployment Evidence for Sprint Review
texto
#### Team Collaboration Insights during Sprint
texto
## Validation Interviews
### Diseño de Entrevistas
texto
### Registro de Entrevistas
texto
### Evaluaciones según heurísticas
texto
## Video About-the-Product
texto
# Conclusiones
## Conclusiones y recomendaciones
texto
## Video About-the-Team
texto

# Bibliografía
texto
# Anexos
texto
