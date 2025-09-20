# COURSE PROJECT

---

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>2025-02</strong><br>
    <strong>Desarrollo de Soluciones IOT</strong><br>
    <strong>Docente: Marco Antonio Leon Baca</strong><br>
    <br>TB1</br>
</p>

<p align="center">
    <strong>Startup: ecoTech</strong><br>
    <strong>Producto: MUEVETE!</strong>
</p>

### Team Members:

<div style="align=center;display: flex; justify-content: center; align-items: center;">

| **Member**                          | **Code**    |
|-------------------------------------|-------------|
| Onofre Ruiz, Carlos Jesus      	    | u202115590  |
| Travezaño Patiño, Eduard Gedeon      	| u20211a789  |
| Onofre Ruiz, Carlos Jesus      	    | u202115590  |
| Hidalgo Lopez, Mathias Adriano      	    | u202213222  |

</div>

<p align="center">
    <strong>Septiembre 2025</strong>
</p>

---

# Registro de Versiones del Informe

 __TB1__

Para el desarrollo de la entrega **TB1**, se optó por dividir el trabajo de la siguiente forma:

| **Versión**  | **Fecha**  | **Autor**                         | **Descripción**                                                                                                   |
|--------------|------------|-----------------------------------|-------------------------------------------------------------------------------------------------------------------|
|**#01 - TB1**| 09/09/25   |      |  |
|**#01 - TB1**| 09/09/25   |      |  |
|**#01 - TB1**| 10/09/25   |      |  |
|**#01 - TB1**| 08/09/25   |      |  |
|**#01 - TB1**| 10/09/25   |      |  |

# Contenido

## Tabla de contenidos
- [COURSE PROJECT](#course-project)
    - [Team Members:](#team-members)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [Studen Outcome](#studen-outcome)
- [**Capítulo I: Introducción.**](#capítulo-i-introducción)
  - [**1.1. Startup Profile.**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup.**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo.**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile.**](#12-solution-profile)
    - [**1.2.1. Antecedentes y problemática.**](#121-antecedentes-y-problemática)
    - [**1.2.2. Lean UX Process.**](#122-lean-ux-process)
      - [**1.2.2.1. Lean UX Problem Statements.**](#1221-lean-ux-problem-statements)
      - [**1.2.2.2. Lean UX Assumptions.**](#1222-lean-ux-assumptions)
      - [**1.2.2.3. Lean UX Hypothesis Statements.**](#1223-lean-ux-hypothesis-statements)
      - [**1.2.2.4. Lean UX Canvas.**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo.**](#13-segmentos-objetivo)

- [**Capítulo II: Requirements Elicitation & Analysis.**](#capítulo-ii-requirements-elicitation--analysis)
  - [**2.1. Competidores.**](#21-competidores)
    - [**2.1.1. Análisis competitivo.**](#211-análisis-competitivo)
    - [**2.1.2. Estrategias y tácticas frente a competidores.**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas.**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas.**](#221-diseño-de-entrevistas)
    - [**2.2.2. Registro de entrevistas.**](#222-registro-de-entrevistas)
    - [**2.2.3. Análisis de entrevistas.**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding.**](#23-needfinding)
    - [**2.3.1. User Personas.**](#231-user-personas)
    - [**2.3.2. User Task Matrix.**](#232-user-task-matrix)
    - [**2.3.3. User Journey Mapping.**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping.**](#234-empathy-mapping)
  - [**2.4. Big Picture EventStorming.**](#24-big-picture-eventstorming)
  - [**2.5. Ubiquitous Language.**](#25-ubiquitous-language)

- [**Capítulo III: Requirements Specification.**](#capítulo-iii-requirements-specification)
  - [**3.1. User Stories.**](#31-user-stories)
  - [**3.2. Impact Mapping.**](#32-impact-mapping)
  - [**3.3. Product Backlog.**](#33-product-backlog)

- [**Capítulo IV: Solution Software Design.**](#capítulo-iv-solution-software-design)
  - [**4.1. Strategic-Level Domain-Driven Design.**](#41-strategic-level-domain-driven-design)
    - [**4.1.1. Design-Level EventStorming.**](#411-design-level-eventstorming)
      - [**4.1.1.1. Candidate Context Discovery.**](#4111-candidate-context-discovery)
      - [**4.1.1.2. Domain Message Flows Modeling.**](#4112-domain-message-flows-modeling)
      - [**4.1.1.3. Bounded Context Canvases.**](#4113-bounded-context-canvases)
    - [**4.1.2. Context Mapping.**](#412-context-mapping)
    - [**4.1.3. Software Architecture.**](#413-software-architecture)
      - [**4.1.3.1. Software Architecture System Landscape Diagram.**](#4131-software-architecture-system-landscape-diagram)
      - [**4.1.3.2. Software Architecture Context Level Diagrams.**](#4132-software-architecture-context-level-diagrams)
      - [**4.1.3.3. Software Architecture Container Level Diagrams.**](#4133-software-architecture-container-level-diagrams)
      - [**4.1.3.4. Software Architecture Deployment Diagrams.**](#4134-software-architecture-deployment-diagrams)
  - [**4.2. Tactical-Level Domain-Driven Design.**](#42-tactical-level-domain-driven-design)
    - [**4.2.X. Bounded Context: <Bounded Context Name>.**](#42x-bounded-context-bounded-context-name)
      - [**4.2.X.1. Domain Layer.**](#42x1-domain-layer)
      - [**4.2.X.2. Interface Layer.**](#42x2-interface-layer)
      - [**4.2.X.3. Application Layer.**](#42x3-application-layer)
      - [**4.2.X.4. Infrastructure Layer.**](#42x4-infrastructure-layer)
      - [**4.2.X.5. Bounded Context Software Architecture Component Level Diagrams.**](#42x5-bounded-context-software-architecture-component-level-diagrams)
      - [**4.2.X.6. Bounded Context Software Architecture Code Level Diagrams.**](#42x6-bounded-context-software-architecture-code-level-diagrams)
        - [**4.2.X.6.1. Bounded Context Domain Layer Class Diagrams.**](#42x61-bounded-context-domain-layer-class-diagrams)
        - [**4.2.X.6.2. Bounded Context Database Design Diagram.**](#42x62-bounded-context-database-design-diagram)

- [**Capítulo V: Solution UI/UX Design.**](#capítulo-v-solution-uiux-design)
  - [**5.1. Style Guidelines.**](#51-style-guidelines)
    - [**5.1.1. General Style Guidelines.**](#511-general-style-guidelines)
    - [**5.1.2. Web, Mobile and IoT Style Guidelines.**](#512-web-mobile-and-iot-style-guidelines)
  - [**5.2. Information Architecture.**](#52-information-architecture)
    - [**5.2.1. Organization Systems.**](#521-organization-systems)
    - [**5.2.2. Labeling Systems.**](#522-labeling-systems)
    - [**5.2.3. SEO Tags and Meta Tags.**](#523-seo-tags-and-meta-tags)
    - [**5.2.4. Searching Systems.**](#524-searching-systems)
    - [**5.2.5. Navigation Systems.**](#525-navigation-systems)
  - [**5.3. Landing Page UI Design.**](#53-landing-page-ui-design)
    - [**5.3.1. Landing Page Wireframe.**](#531-landing-page-wireframe)
    - [**5.3.2. Landing Page Mock-up.**](#532-landing-page-mock-up)
  - [**5.4. Applications UX/UI Design.**](#54-applications-uxui-design)
    - [**5.4.1. Applications Wireframes.**](#541-applications-wireframes)
    - [**5.4.2. Applications Wireflow Diagrams.**](#542-applications-wireflow-diagrams)
    - [**5.4.3. Applications Mock-ups.**](#543-applications-mock-ups)
    - [**5.4.4. Applications User Flow Diagrams.**](#544-applications-user-flow-diagrams)
  - [**5.5. Applications Prototyping.**](#55-applications-prototyping)

- [**Capítulo VI: Product Implementation, Validation & Deployment.**](#capítulo-vi-product-implementation-validation--deployment)
  - [**6.1. Software Configuration Management.**](#61-software-configuration-management)
    - [**6.1.1. Software Development Environment Configuration.**](#611-software-development-environment-configuration)
    - [**6.1.2. Source Code Management.**](#612-source-code-management)
    - [**6.1.3. Source Code Style Guide & Conventions.**](#613-source-code-style-guide--conventions)
    - [**6.1.4. Software Deployment Configuration.**](#614-software-deployment-configuration)
  - [**6.2. Landing Page, Services & Applications Implementation.**](#62-landing-page-services--applications-implementation)
    - [**6.2.X. Sprint n.**](#62x-sprint-n)
      - [**6.2.X.1. Sprint Planning n.**](#62x1-sprint-planning-n)
      - [**6.2.X.2. Aspect Leaders and Collaborators.**](#62x2-aspect-leaders-and-collaborators)
      - [**6.2.X.3. Sprint Backlog n.**](#62x3-sprint-backlog-n)
      - [**6.2.X.4. Development Evidence for Sprint Review.**](#62x4-development-evidence-for-sprint-review)
      - [**6.2.X.5. Testing Suite Evidence for Sprint Review.**](#62x5-testing-suite-evidence-for-sprint-review)
      - [**6.2.X.6. Execution Evidence for Sprint Review.**](#62x6-execution-evidence-for-sprint-review)
      - [**6.2.X.7. Services Documentation Evidence for Sprint Review.**](#62x7-services-documentation-evidence-for-sprint-review)
      - [**6.2.X.8. Software Deployment Evidence for Sprint Review.**](#62x8-software-deployment-evidence-for-sprint-review)
      - [**6.2.X.9. Team Collaboration Insights during Sprint.**](#62x9-team-collaboration-insights-during-sprint)
  - [**6.3. Validation Interviews.**](#63-validation-interviews)
    - [**6.3.1. Diseño de Entrevistas.**](#631-diseño-de-entrevistas)
    - [**6.3.2. Registro de Entrevistas.**](#632-registro-de-entrevistas)
    - [**6.3.3. Evaluaciones según heurísticas.**](#633-evaluaciones-según-heurísticas)
  - [**6.4. Video About-the-Product.**](#64-video-about-the-product)

- [**Conclusiones y Recomendaciones.**](#conclusiones-y-recomendaciones)
- [**Video About-the-Team.**](#video-about-the-team)
- [**Bibliografía.**](#bibliografía)
- [**Anexos.**](#anexos)

---

# [Studen Outcome](#studen-outcome)
| Criterio específico | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                    |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta |  |  |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.. |   |  |

---

# [**Capítulo I: Introducción.**](#capítulo-i-introducción)

## [**1.1 Startup Profile.**](#11-startup-profile)

En esta sección, exploraremos la identidad de nuestra startup, presentando una descripción detallada de la empresa y los perfiles de quienes conformamos el equipo.

### [**1.1.1 Descripción del startup.**](#111-descripción-del-startup)

GoUni es una startup que nace como una iniciativa frente a dos realidades urbanas en pleno auge: la urgente demanda de opciones de movilidad sostenible y la creciente popularidad de los vehículos ecológicos. Nuestra propuesta se materializa en una aplicación que sirve como puente, conectando a personas que necesitan un medio de transporte —como bicicletas, scooters, skateboards o motos eléctricas— con quienes ya poseen estos vehículos y están dispuestos a compartirlos.

Lo que realmente nos distingue en el ecosistema de aplicaciones de movilidad es nuestro doble propósito. No solo defendemos y facilitamos una forma de transporte más limpia y amigable con el planeta, sino que también abrimos una puerta a oportunidades de ingreso para la comunidad universitaria. Los estudiantes pueden generar ganancias de forma flexible, ya sea alquilando o vendiendo sus vehículos. Además, hemos integrado en nuestra plataforma funcionalidades clave para garantizar que cada interacción sea segura, ágil y, sobre todo, una experiencia positiva.

**Misión:** Ser el conector digital que facilita el acceso a una movilidad urbana sostenible. A través de nuestra plataforma, buscamos reducir activamente la huella de carbono en la ciudad, al tiempo que empoderamos a los estudiantes universitarios con nuevas oportunidades económicas.

**Visión:** Aspiramos a consolidarnos como la aplicación de referencia en el ámbito de la movilidad urbana sostenible. Queremos ser reconocidos por democratizar el acceso a vehículos ecológicos y por inspirar un estilo de vida más saludable y en armonía con nuestro entorno.

### [**1.1.2 Perfiles de los integrantes del equipo.**](#112-perfiles-de-los-integrantes-del-equipo)

<table>
  <tr>
    <th>Miembros del equipo</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td><img src="assets/images/profiles/Anampa_Angel.jpg" alt="" width="100" height="100"></td>
    <td>Mi nombre es Angel Anampa y tengo 19 años. Actualmente estoy cursando la carrera de Ingeniería de Software en la UPC. Elegí dicha carrera porque soy una persona que le interesa mucho los temas que tienen que ver con tecnología , me gustan los videojuegos. Me considero una persona atenta, responsable , optimista que sabe solucionar los problemas. Como integrante del equipo me comprometo a apoyar al grupo en este trabajo.</td>
  </tr>
  
   <tr>
    <td><img src="assets/images/profiles/Ayquipa_Abraham.jpeg" width="150" height="130"></td>
    <td>Soy estudiante de la carrera de ingeniería de software, actualmente cursando el 8to ciclo de carrera. Aunque soy fullstack developer, tengo más inclinación por el desarrollo frontend. Mi stack arranca con Next.js(Framework de React) + Typescript para el front y Node.js + Express.js + MongoDB para el back. Como todo buen programador, me considero un eterno estudiante, por lo que me encuentro en este momento estudiando Docker y Redis..</td>
  </tr>

  <tr>
    <td><img src="/assets/images/profiles/Onofre_Carlos.jpeg" width="100" height="100"></td>
    <td>Estudiante de ingeniería de software, tengo varios interes como backend developer, aun asi desempeño roles como desarrollo frontend y diseño UX/UI. Participo activamente en ramas estudiantiles y a la par apoyando a la facultad de Ingenieria. Me encuentro realizando m tesis basado en machine learning siendo un reto para mi que superaré.</td>
    </tr>

  <tr>
    <td><img src="./assets/images/profiles/Landeo_Favio.png" width="140" height="100"></td>
    <td>Tengo 22 años y actualmente estoy cursando el décimo ciclo de la carrera de Ingeniería de Software. Estoy disponible para ayudar siempre a mis compañeros y además tiendo a generar buenas relaciones sociales con diferentes tipos de personas gracias a mi tolerancia y capacidad de trabajo en equipo. En mis tiempos libres me gusta escuchar música, jugar videojuegos y editar videos.</td>
  </tr>

</table>

---

## [**1.2. Solution Profile.**](#12-solution-profile)

Esta sección se divide en dos áreas fundamentales:

Contexto y Desafío: Aquí profundizamos en el problema que nuestro proyecto se propone resolver. Detallamos el panorama actual, los elementos cruciales que nuestra solución debe atender, y definimos los objetivos y limitaciones del proyecto.

Proceso Lean UX: En esta parte, aplicamos el marco de trabajo Lean UX para explicar cómo abordaremos la solución del problema desde la perspectiva del modelo de negocio.

### [**1.2.1. Antecedentes y Problemática.**](#121-antecedentes-y-problemática)

### Antecedentes:
En los últimos diez años, el pulso de nuestras ciudades ha cambiado. La forma en que nos movemos está en plena transformación, impulsada por una mayor conciencia ambiental y los avances tecnológicos. Alternativas de transporte ecológicas, como las bicicletas y los scooters eléctricos, han ganado un terreno impresionante, lo que evidencia un deseo colectivo por soluciones de movilidad más inteligentes y responsables.

Para los habitantes de Lima Metropolitana, el transporte urbano no es solo un inconveniente, es uno de los problemas más críticos de su día a día. Se le describe como un sistema informal, ineficiente y de baja calidad, marcado por la inseguridad, altas tasas de accidentes y una contaminación ambiental y sonora alarmante, tal como lo han señalado el MTC (2013) y la OMS.

Frente a esta realidad, la búsqueda de alternativas de movilidad más ágiles, sostenibles y al alcance de todos se ha convertido en una prioridad. Vehículos como bicicletas, scooters, skateboards y motos eléctricas emergen como soluciones prácticas que no solo contribuyen a limpiar el aire que respiramos, sino que también promueven un estilo de vida más activo y saludable.

Paralelamente, existe un desafío económico que afecta directamente a los jóvenes. Según datos de la USIL, la tasa de deserción en la educación superior universitaria aumentó significativamente del 19.3% en 2019 al 23.2% en 2021. Esta cifra sugiere que muchos estudiantes necesitan un respaldo financiero adicional para poder costear y continuar con su formación profesional.

Es en la intersección de estos dos mundos donde encontramos nuestra oportunidad. A la par que crece la demanda de movilidad ecológica, también lo hace la necesidad de ingresos flexibles entre los estudiantes universitarios. En un contexto de costos de vida crecientes y altas exigencias académicas, los jóvenes buscan maneras de ganar dinero que se ajusten a sus horarios, y la economía digital ofrece el espacio perfecto para ello.

Nuestro proyecto busca ser un agente de cambio. Queremos transformar la movilidad en Lima y, al mismo tiempo, empoderar a los universitarios, ofreciéndoles una herramienta digital para generar ingresos de manera autónoma. Al conectar a estudiantes con potenciales usuarios, creamos un ecosistema donde la sostenibilidad y el espíritu emprendedor van de la mano. Nuestra meta es clara: reducir la huella de carbono y fortalecer el bienestar económico de los jóvenes, un viaje a la vez.

### Problemática (5Ws y 2Hs)
**¿Qué? (What):** El núcleo del problema es la ausencia de una plataforma digital que integre la movilidad sostenible con una oportunidad económica real y flexible para los estudiantes. Por un lado, la ciudad de Lima lidia con serios problemas de congestión y contaminación; por otro, los universitarios luchan por encontrar fuentes de ingreso compatibles con su vida académica.

**¿Cuándo? (When):** Esta problemática no es nueva, pero se ha intensificado notablemente en la última década debido al crecimiento urbano desmedido y a la creciente urgencia de adoptar hábitos más sostenibles. La presión económica sobre los estudiantes se ha agudizado con el aumento del costo de vida.

**¿Dónde? (Where):** El epicentro de este desafío es Lima, una metrópoli que sufre de alta congestión vehicular y niveles preocupantes de contaminación. Sin embargo, la necesidad de ingresos flexibles es una realidad que afecta a estudiantes universitarios en todo el país.

**¿Quién? (Who):** Los protagonistas de esta historia son, por un lado, los universitarios que poseen vehículos menores (bicicletas, scooters, etc.) y buscan una forma de monetizarlos. Por otro lado, están los usuarios de la aplicación, un grupo diverso que incluye trabajadores, turistas y residentes de Lima que desean moverse por la ciudad de una manera más económica, eficiente y ecológica.

**¿Por qué? (Why):** La causa fundamental del problema es la falta de una solución unificada. Esta carencia frena el potencial de los universitarios para mejorar su autonomía financiera y, a su vez, limita la capacidad de la ciudad para transitar hacia un modelo de movilidad más limpio y ordenado.

**¿Cómo? (How):** Los usuarios interactuarán con nuestro producto a través de una aplicación web y móvil, diseñada para ser intuitiva y accesible desde cualquier dispositivo con conexión a internet. El descubrimiento de nuestra plataforma se dará de forma orgánica a través de redes sociales, alianzas con universidades, campañas de marketing digital y el boca a boca en comunidades enfocadas en la sostenibilidad. La preferencia será siempre una experiencia de usuario fluida, rápida y que motive la participación.

**¿Cuánto? (How much):** El impacto de este problema es profundo y multifacético. A nivel ambiental, contribuye a que Lima sea una de las ciudades con peor calidad de aire en la región. A nivel social, la congestión vehicular roba a los ciudadanos un promedio de tres horas diarias, afectando su productividad y bienestar. A nivel económico, la falta de ingresos flexibles aumenta el estrés financiero de los estudiantes, un grupo que representa una parte vital de la juventud limeña, mientras que la dependencia del ineficiente transporte público consume una porción considerable de sus ya limitados presupuestos.

### [**1.2.2. Lean UX Process.**](#122-lean-ux-process)

#### [**1.2.2.1. Lean UX Problem Statements.**](#1221-lean-ux-problem-statements)


Nuestro objetivo es crear una plataforma digital que funcione como un punto de encuentro para universitarios con vehículos menores en desuso y personas que buscan activamente alternativas de movilidad más asequibles y respetuosas con el medio ambiente. Hemos identificado que una gran cantidad de estudiantes posee bicicletas, scooters o patinetas sin darles uso, mientras que, simultáneamente, existe un grupo de personas que necesita opciones de transporte económicas y sostenibles. Esta situación refleja una preocupación real por los costos de movilidad, el impacto ecológico y la promoción de un estilo de vida saludable. Por lo tanto, nos preguntamos: 

¿Cómo podemos diseñar una experiencia digital que facilite el intercambio de estos vehículos de forma eficiente, promoviendo así un ecosistema de transporte económico, sostenible y beneficioso para la salud?

### Aspectos

#### Domain:
Movilidad y transporte compartido para estudiantes universitarios.

#### Customer Segments:

- ##### Estudiantes Universitarios
Estudiantes que necesitan desplazarse a sus universidades y buscan una alternativa al transporte público o a los vehículos particulares. Estos estudiantes enfrentan desafíos como el estrés, la inseguridad y el costo elevado del transporte.

- ##### Propietarios de Vehículos Privados
Estudiantes que poseen vehículos y desean compartir sus viajes con otros para reducir gastos en combustible y maximizar el uso de sus vehículos.

#### Pain Points:

- ##### Estudiantes

###### Estrés y Fatiga:
La congestión en el transporte público y las largas esperas causan estrés y fatiga, afectando negativamente su experiencia de desplazamiento.

###### Inseguridad:
La inseguridad durante el viaje, especialmente en autobuses abarrotados, es una preocupación constante.

###### Costo Elevado: 

Los gastos en transporte son una carga financiera significativa para los estudiantes.

- ##### Propietarios de Vehículos Privados

###### Oportunidades de Rellenar Asientos: 
Hay una falta de mecanismos eficientes para asegurar que todos los asientos disponibles en un viaje compartido sean utilizados, reduciendo el potencial de ingresos por compartir el viaje.
#### Gap:
Existe una brecha en el mercado de transporte compartido específico para estudiantes universitarios. Aunque hay aplicaciones de viajes compartidos, no están adaptadas a las necesidades y horarios específicos de los estudiantes, lo que dificulta la formación de compañeros de viaje compatibles y la optimización del uso del vehículo.

#### Vision/Strategy:
Crear una plataforma de carpooling diseñada específicamente para estudiantes universitarios que permita una conexión efectiva entre compañeros de viaje con horarios y rutas compatibles. La plataforma debe abordar el estrés y la inseguridad relacionados con el transporte, al mismo tiempo que ofrece una solución económica y eficiente para los estudiantes que desean compartir sus viajes y reducir costos.

#### [**1.2.2.2. Lean UX Assumptions.**](#1222-lean-ux-assumptions)

* **Suposiciones de Negocio:**
    * **Necesidad del Cliente:** Partimos de la premisa de que nuestros usuarios anhelan una solución que entrelace la movilidad sostenible con una fuente de ingresos adaptable a sus vidas.
    * **Solución Propuesta:** Nuestra aplicación web será el puente que conecte a estudiantes con vehículos menores y a personas interesadas en alquilarlos o comprarlos, creando un mercado beneficioso para ambos.
    * **Propuesta de Valor:** Para los universitarios, ofrecemos una vía para monetizar sus activos sin sacrificar sus estudios. Para los usuarios, brindamos acceso fácil a un transporte ecológico que mejora su movilidad.
    * **Adquisición de Clientes:** Planeamos llegar a nuestro público a través de campañas en redes sociales, colaboraciones estratégicas con universidades y presencia en eventos de sostenibilidad.
    * **Modelo de Ingresos:** Nuestra sostenibilidad financiera se basará en modelos de suscripción para los estudiantes que publican sus vehículos y en una comisión por cada transacción exitosa.
    * **Competencia:** Aunque existen otras plataformas de movilidad, nuestro factor diferenciador será la combinación única de sostenibilidad, flexibilidad económica para estudiantes y una interfaz diseñada para ser excepcionalmente simple y práctica.
    * **Riesgos Clave:** Los principales desafíos son construir una masa crítica de usuarios activos y garantizar que la experiencia en la plataforma supere sus expectativas.

* **Suposiciones sobre el Usuario:**
    * **¿Quién es?** Identificamos dos perfiles claros: **universitarios** con vehículos subutilizados y un deseo de generar ingresos, y **usuarios finales** (trabajadores, turistas, etc.) que buscan opciones de transporte ecológicas y económicas en Lima.
    * **¿Cómo encajamos en su vida?** Para los estudiantes, somos una herramienta de empoderamiento financiero. Para los usuarios, somos un facilitador de una movilidad más inteligente y consciente.
    * **¿Qué problema resolvemos?** A los estudiantes les solucionamos la necesidad de ingresos flexibles. A los usuarios les ofrecemos una alternativa a la congestión y la contaminación.
    * **¿Cuándo y cómo nos usarán?** Los estudiantes usarán la app para gestionar sus vehículos disponibles. Los usuarios la consultarán cuando necesiten moverse por la ciudad de forma rápida y sostenible.
    * **¿Qué funciones valorarán?** Creemos que características como un sistema de valoraciones, búsqueda avanzada, historial de transacciones, un foro de ayuda y un mapa interactivo serán cruciales para una experiencia de usuario exitosa. La gamificación añadirá un elemento de compromiso y diversión.

* **Suposiciones sobre las Funcionalidades:**
    * Asumimos que un sistema de calificaciones y reseñas generará confianza en la comunidad.
    * Una función de búsqueda con filtros avanzados permitirá a los usuarios encontrar exactamente lo que necesitan de manera rápida.
    * Un panel de usuario con un historial de transacciones ofrecerá transparencia y control.
    * Un canal de soporte directo, como un foro o contacto por WhatsApp, resolverá dudas eficientemente.
    * Un mapa interactivo para localizar vehículos será una herramienta fundamental.
    * Elementos de gamificación, como logros y recompensas, incentivarán el uso recurrente de la aplicación.

* **Resultados de Negocio Esperados:**
    * Aspiramos a una plataforma estable y fluida que garantice una experiencia de usuario sin interrupciones.
    * Nuestro objetivo es alcanzar un 70% de satisfacción entre los usuarios en el primer trimestre post-lanzamiento.
    * Buscamos lograr una reducción medible del 40% en la contaminación generada por los viajes de nuestros usuarios, contribuyendo así a la lucha contra el cambio climático.

* **Nuestros Usuarios:**
    El corazón de nuestra plataforma son los **estudiantes universitarios**, quienes a través del alquiler o venta de sus vehículos menores se convierten en pequeños emprendedores. Del otro lado se encuentran los **usuarios finales**, personas que buscan una forma más inteligente y sostenible de moverse por la ciudad y encuentran en nuestra comunidad la solución perfecta.

* **Beneficios para el Usuario:**
    * **Para los Universitarios:** La oportunidad de generar ingresos de forma flexible y la satisfacción de contribuir a una causa ecológica.
    * **Para los Usuarios Finales:** La capacidad de reducir su huella de carbono y el acceso simplificado a medios de transporte prácticos cuando más los necesitan.


#### [**1.2.2.3. Lean UX Hypothesis Statements.**](#1223-lean-ux-hypothesis-statements)

* **Hipótesis 01:** Creemos que al facilitar que los universitarios alquilen o vendan sus vehículos, fomentaremos una cultura de economía compartida que reducirá la necesidad de vehículos privados y, por ende, beneficiará al medio ambiente. Sabremos que es cierto cuando veamos un aumento en los ingresos de los estudiantes y un crecimiento orgánico de la comunidad a través de recomendaciones.
* **Hipótesis 02:** Creemos que al ofrecer una gama diversa de opciones de transporte sostenible, inspiraremos un estilo de vida más eco-consciente. El éxito será evidente cuando observemos que las autoridades locales de Lima invierten más en infraestructura para la micromovilidad, como ciclovías y carriles para scooters.
* **Hipótesis 03:** Creemos que ampliar nuestra oferta de vehículos atraerá a un público más amplio. Mediremos el éxito a través de un crecimiento significativo en nuestra base de usuarios después de cada nueva incorporación.
* **Hipótesis 04:** Creemos que un enfoque riguroso en la seguridad y el mantenimiento de los vehículos fortalecerá la confianza del usuario. Lo confirmaremos al ver un aumento en la tasa de retención de usuarios y al recibir comentarios positivos sobre la fiabilidad del servicio.
* **Hipótesis 05:** Creemos que al optimizar continuamente la experiencia de usuario, haremos que la aplicación sea más accesible y agradable para todos. Sabremos que hemos tenido éxito cuando las métricas muestren un mayor tiempo de uso en la app y las encuestas reflejen una alta satisfacción general.

#### [**1.2.2.4. Lean UX Canvas.**](#1224-lean-ux-canvas)

| **Lean UX Canvas**                                                                                                                                                               | **Fecha:** 20/08/2025                                                                                               | **Iteración:** 1 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|------------------|
| **1. Business Problem:**                                                                                                                                                         | **5. Solutions:**                                                                                                  | **2. Business Outcomes:** |
| - La falta de un sistema eficiente y confiable que conecte a los estudiantes universitarios que necesitan compartir transporte hacia la universidad.                              | - **Plataforma de Carpooling:** Sistema que permita a los estudiantes ofrecer y encontrar viajes compartidos hacia la universidad.                        | - Aumento en el número de usuarios activos y viajes compartidos realizados. |
| - Aunque existen alternativas de transporte público y privado, los estudiantes enfrentan problemas como el tráfico, el costo elevado, la inseguridad y la pérdida de tiempo.      | - **Verificación de Usuarios:** Proceso de verificación para garantizar la seguridad y confianza entre los usuarios.                                       | - Reducción de costos de transporte para los estudiantes. |
| - Además, la falta de una solución que optimice el uso de vehículos privados entre estudiantes afecta la movilidad y la sostenibilidad.                                           | - **Sistema de Recompensas:** Incentivos para conductores y pasajeros frecuentes.                                                                         | - Mejora en la eficiencia y sostenibilidad del transporte universitario. |
|                                                                                                                                                                                  | - **Funcionalidad de Chat:** Herramienta de comunicación directa entre conductores y pasajeros para coordinar detalles del viaje.                        | - Reconocimiento y adopción de la plataforma como la opción preferida para el carpooling entre estudiantes universitarios. |
|                                                                                                                                                                                  | - **Integración de Rutas:** Sincronización con aplicaciones de mapas para optimizar las rutas y tiempos de viaje.                                         | |
|                                                                                                                                                                                  | - **Notificaciones en Tiempo Real:** Alertas sobre cambios en la ruta o disponibilidad de viajes.                                                        | |

| **3. Users:**                                                                                                                                                                   | **6. Hypotheses:**                                                                                                                                       | **4. User Outcomes & Benefits:** |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| - Los usuarios principales serán estudiantes universitarios que buscan una alternativa de transporte más económica, segura y conveniente para llegar a sus campus.              | - Creemos que al simplificar el proceso de registro y la verificación de usuarios en nuestra plataforma, aumentaremos la tasa de conversión de nuevos estudiantes. | - **Estudiantes:** Ahorro de tiempo y dinero, reducción del estrés del transporte público, y mayor seguridad al viajar con compañeros de estudio. |
| - También incluye a los conductores que desean compartir sus vehículos para reducir costos y contribuir a una movilidad más sostenible.                                          | - Creemos que al implementar una función de mensajería entre conductores y pasajeros, mejoraremos la coordinación y la confianza en nuestra plataforma.   | - **Conductores:** Reducción de costos operativos y mayor sostenibilidad en sus desplazamientos. |
| - Las universidades podrían ser clientes interesados en promover el uso de la plataforma entre sus estudiantes.                                                                 | - Creemos que al ofrecer una sección destacada para los “Viajes Más Populares de la Semana,” aumentaremos la participación de los estudiantes en la plataforma. | - **Universidades:** Promoción de una solución eficiente, segura, y ecológica para sus estudiantes, mejorando la calidad de vida en el campus. |
|                                                                                                                                                                                 | - Creemos que al proporcionar métricas claras sobre la eficiencia de los viajes, motivaremos a más estudiantes a utilizar nuestro servicio regularmente.  | |
|                                                                                                                                                                                 | - Creemos que al incorporar un sistema de recompensas para conductores y pasajeros frecuentes, aumentaremos la retención de usuarios.                    | |

| **7. What's the most important thing we need to learn first?**                                                                                                                  | **8. What's the least amount of work we need to do to learn the next most important thing?**                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| - Conocer las necesidades y comportamientos de los estudiantes en relación con sus hábitos de transporte y carpooling.                                                         | - Crear un prototipo funcional que permita a los estudiantes registrarse, verificar su identidad y buscar u ofrecer viajes compartidos.                    |
| - Evaluar la seguridad y confiabilidad del sistema de verificación de usuarios.                                                                                                 | - Realizar pruebas con un grupo pequeño de usuarios para validar la usabilidad y efectividad del sistema de verificación y mensajería.                    |
| - Investigar las preferencias de diseño y funcionalidad de los usuarios potenciales.                                                                                            | - Desarrollar un plan de marketing inicial para generar interés en una universidad piloto.                                                                 |
| - Identificar barreras de adopción y estrategias para superarlas.                                                                                                               | - Establecer soporte básico al usuario para resolver consultas y problemas de manera rápida y efectiva.                                                   |
| - Comprender las mejores prácticas de carpooling y estudiar a la competencia.                                                                                                  |                                                                                                                                                           |

---

## [**1.3. Segmentos objetivo.**](#13-segmentos-objetivo)

Por medio de nuestro enfoque de obtener una solución efectiva a las problemáticas de nuestros futuros usuarios, identificamos los siguientes segmentos para GoUni:

### **Segmento objetivo #1: Estudiantes Universitarios que necesiten movilizarse.**

**Aspectos demográficos:**

- **Sexo:** Masculino y femenino
- **Edades:** Adultos entre 18 - 30 años
- **Nivel socioeconómico:** Clases B, C, D (media-baja, baja)

**Aspectos geográficos:**

- **Nacionalidad:** Peruana
- **Zona geográfica en la que vive:** Urbana
- **Departamento:** Lima Metropolitana

**Aspectos psicográficos:**

- Abiertos a herramientas que les ayuden a simplificar y facilitar su viaje.
- Son hábiles dentro del uso de dispositivos inteligentes.

---

### **Segmento objetivo #2: Estudiantes Universitarios propietarios de un vehículo privado.**

**Aspectos demográficos:**

- **Sexo:** Masculino y femenino
- **Edades:** Adultos entre 18 - 30 años
- **Nivel socioeconómico:** Clases A, B, C (alta, media-alta y media)

**Aspectos geográficos:**

- **Nacionalidad:** Peruana
- **Zona geográfica en la que vive:** Urbana
- **Departamento:** Lima Metropolitana

**Aspectos psicográficos:**

- Son hábiles dentro del uso de dispositivos inteligentes.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### BlaBlaCar

Es una plataforma global de ride-sharing que conecta conductores y pasajeros para 
compartir viajes de media y larga distancia. Los usuarios pueden dividir los costos del viaje, 
lo que hace que el transporte sea más económico y sostenible. BlaBlaCar fomenta la colaboración y 
la optimización de recursos al reducir la cantidad de vehículos en la carretera.

### Urbvan

Es una plataforma de transporte privado en van que opera en rutas predefinidas, generalmente en áreas
metropolitanas. Se enfoca en ofrecer una alternativa más eficiente y cómoda al transporte público, 
brindando un servicio seguro y puntual a través de vehículos compartidos, pero con un enfoque de 
calidad y confort para los usuarios.

### Yango

Es una aplicación internacional de ride-hailing que ofrece transporte bajo demanda con tarifas 
competitivas y un enfoque en la facilidad de uso. Opera en diversas ciudades del mundo, brindando a 
los usuarios una experiencia de transporte rápida, segura y accesible, con la opción de reservar y 
pagar viajes directamente a través de la aplicación.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se esta llevando a cabo para connotar las diferencias con las empresas competidoras y tomar sus amenazas
    como nuevas oportunidades en nuestro producto para poder innovar.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        GoUni
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/logo/gounilogo.jfif" alt="StartUp" width="100px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    BlaBlaCar
    <div style="text-align: center; margin-top: 20px;">
                <img src="assets/images/competitorsLogo/blablacar.png" alt="blablacar" width="100px">
        </div
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      Urbvan
      <div style="text-align: center; margin-top: 40px;">
                <img src="assets/images/competitorsLogo/urbvan.png" alt="urbvan" width="200px">
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Yango
      <div style="text-align: center; margin-top: 20px;">
                <img src="assets/images/competitorsLogo/yango.png" alt="yango" width="610px">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Plataforma de ride-sharing entre estudiantes universitarios en Perú, centrada en la 
    colaboración, sostenibilidad y reducción de costos de transporte.</td>
    <td colspan="1" valign="top">Plataforma global de ride-sharing para viajes interurbanos, 
    donde conductores y pasajeros comparten viajes y gastos.</td>
    <td colspan="1" valign="top">Plataforma de transporte privado en van con rutas predefinidas, 
    enfocada en eficiencia y comodidad.</td>
    <td colspan="1" valign="top">Aplicación internacional de ride-hailing que se enfoca en 
    ofrecer tarifas competitivas y una experiencia sencilla de uso.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Focalización en estudiantes universitarios, fomentando una comunidad cerrada y 
    segura con intereses comunes; enfoque en sostenibilidad.</td>
    <td colspan="1" valign="top">Operación a nivel global con una amplia base de usuarios; 
    experiencia consolidada en viajes largos.</td>
    <td colspan="1" valign="top">Ofrece transporte cómodo y seguro en rutas fijas; 
    ideal para desplazamientos largos dentro de la ciudad.</td>
    <td colspan="1" valign="top">Tarifas competitivas y experiencia de usuario sencilla, 
    rápida expansión en diversas ciudades.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Estudiantes universitarios en Perú que buscan compartir viajes seguros, 
    económicos y sostenibles con sus compañeros.</td>
    <td colspan="1" valign="top">Viajeros interurbanos que buscan reducir costos y socializar en viajes largos.</td>
    <td colspan="1" valign="top">Profesionales y estudiantes que requieren transporte cómodo y 
    eficiente en rutas fijas dentro de la ciudad.</td>
    <td colspan="1" valign="top">Usuarios urbanos que buscan transporte asequible y 
    rápido en varias ciudades de América Latina.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Enfoque en el marketing digital y redes sociales en entornos estudiantiles; 
    colaboraciones con universidades para promociones.</td>
    <td colspan="1" valign="top">Campañas de marketing enfocadas en la experiencia compartida, 
    la comunidad y la reducción de costos de viaje.	</td>
    <td colspan="1" valign="top">Enfoque en la eficiencia, seguridad y confort en el transporte urbano; 
    promociones y descuentos para usurios frecuentes.</td>
    <td colspan="1" valign="top">Enfoque en tarifas competitivas, promociones frecuentes y facilidad de uso; 
    expansión rápida y adquisición de nuevos usuarios.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Plataforma de ride-sharing exclusiva para estudiantes 
    universitarios, con opciones para compartir viajes cortos y largos dentro de la ciudad.</td>
    <td colspan="1" valign="top">Ride-sharing interurbano, conectando conductores 
    y pasajeros en viajes de larga distancia.</td>
    <td colspan="1" valign="top">Servicios de transporte en vans con rutas fijas; 
    asientos reservados y viajes cómodos.</td>
    <td colspan="1" valign="top">Ride-hailing en tiempo real con diferentes tipos de vehículos; 
precios competitivos y una plataforma fácil de usar.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">Precios asequibles con base en compartir costos de 
    viaje; enfoque en la economía colaborativa.</td>
    <td colspan="1" valign="top">Compartir costos de viaje entre conductores y pasajeros; 
    enfoque en la reducción de costos de viaje.</td>
    <td colspan="1" valign="top">Tarifas fijas según las rutas y horarios predefinidos; enfoque en la comodidad.</td>
    <td colspan="1" valign="top">Tarifas accesibles con promociones frecuentes; 
    modelo basado en precios competitivos y flexibles.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Aplicación móvil enfocada en estudiantes universitarios, 
    con soporte web para registros y gestión de viajes.</td>
    <td colspan="1" valign="top">Aplicación móvil y web con acceso a reservas 
    de viajes compartidos en toda la región.</td>
    <td colspan="1" valign="top">Aplicación móvil y reservas web para la gestión de rutas y viajes en vans.</td>
    <td colspan="1" valign="top">Aplicación móvil fácil de usar disponible en múltiples ciudades de América Latina.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Enfoque en la comunidad estudiantil; servicio exclusivo y seguro; sostenibilidad.</td>
    <td colspan="1" valign="top">Amplia red global de usuarios; enfoque en viajes largos; reputación consolidada.</td>
    <td colspan="1" valign="top">Comodidad y eficiencia en rutas predefinidas; seguridad y confort en transporte urbano.</td>
    <td colspan="1" valign="top">Tarifas competitivas y fácil de usar; expansión rápida en diversas ciudades.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Mercado limitado a estudiantes universitarios; competencia con transporte público económico.</td>
    <td colspan="1" valign="top">Dependencia de viajes largos; limitado a rutas interurbanas.</td>
    <td colspan="1" valign="top">Restricción de rutas fijas y horarios; costos más altos comparados con el transporte público tradicional.</td>
    <td colspan="1" valign="top">Competencia feroz en mercados urbanos; problemas con la regulación local.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Expansión a otras universidades y ciudades; colaboraciones con instituciones educativas.</td>
    <td colspan="1" valign="top">Expansión a mercados nuevos y emergentes; desarrollo de más servicios complementarios.</td>
    <td colspan="1" valign="top">Expansión a más rutas y ciudades; enfoque en ofrecer servicios corporativos.</td>
    <td colspan="1" valign="top">Crecimiento acelerado en más ciudades; enfoque en la mejora continua del servicio y tarifas.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia de aplicaciones de ride-hailing y transporte público; regulación gubernamental.</td>
    <td colspan="1" valign="top">Aparición de competidores más locales en áreas específicas; cambios en la regulación.</td>
    <td colspan="1" valign="top">Competencia con aplicaciones de ride-hailing y transporte público tradicional.</td>
    <td colspan="1" valign="top">Regulación gubernamental y competencia feroz en el mercado urbano de transporte.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

- **Diferenciación de la plataforma:**  
  GoUni se diferencia por ser una plataforma exclusiva para estudiantes universitarios. El enfoque en la comunidad académica y la seguridad brinda un entorno más cerrado y confiable en comparación con otras plataformas abiertas al público general. Además, su misión de promover la sostenibilidad y la economía colaborativa refuerza su atractivo para jóvenes conscientes del medio ambiente.

---

- **Comunidad activa:**  
  Con GoUni queremos fomentar una comunidad de estudiantes comprometidos, creando un entorno en el que los usuarios se sientan seguros viajando con personas de su misma universidad. La cercanía entre los miembros de la comunidad facilita la interacción y genera confianza entre los usuarios.

---

- **Marketing dirigido:**  
  El marketing en GoUni se enfocará en captar a estudiantes universitarios mediante colaboraciones con universidades, eventos estudiantiles y promociones a través de redes sociales específicas para jóvenes. Esta comunicación apela a la sostenibilidad, la seguridad y la economía colaborativa, factores importantes para la comunidad estudiantil.

---

- **Monetización creativa:**  
  La monetización de GoUni se basará en la compartición de costos entre estudiantes, pero puede explorar modelos adicionales como suscripciones premium que ofrezcan beneficios exclusivos, como rutas garantizadas o mayor seguridad. También podría implementar alianzas con marcas enfocadas en estudiantes, generando ingresos adicionales a través de publicidad contextual o colaboraciones.


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se han definido todas las preguntas que se plantearán en el momento de realizar las entrevistas a los diferentes segmentos objetivos.

#### **Preguntas Generales**

1. ¿Cuál es tu nombre?
2. ¿Qué edad tienes?
3. ¿Dónde vives actualmente?
4. ¿A qué te dedicas?

---

#### **Preguntas Segmento 1: Estudiantes universitarios**

1. ¿Con qué frecuencia utilizas transporte para llegar a la universidad?
2. ¿Cuáles son las mayores dificultades que enfrentas al desplazarte a la universidad?
3. ¿Cuánto tiempo sueles tardar en llegar a la universidad desde tu casa?
4. ¿Estarías dispuesto/a a compartir tu trayecto con otros estudiantes? ¿Por qué?
5. ¿Qué factores te harían sentir más cómodo/a utilizando un servicio de ride-sharing para estudiantes?
6. ¿Cómo crees que un servicio de transporte compartido podría mejorar tu experiencia diaria?

---

#### **Preguntas Segmento 2: Estudiantes universitarios propietarios de vehículos privados**

1. ¿Con qué frecuencia conduces hacia tu universidad o trabajo?
2. ¿Te gustaría compartir tu vehículo con otros estudiantes en tus trayectos?
3. ¿Cuáles son tus mayores preocupaciones al compartir tu vehículo con otras personas?
4. ¿Qué aspectos te motivarían a ofrecer tu vehículo en un servicio de ride-sharing?
5. ¿Qué tipo de incentivos te harían más propenso/a a unirte a una plataforma de ride-sharing para estudiantes?
6. ¿Cómo manejas los costos de mantenimiento y gasolina? ¿Crees que compartir tu vehículo podría ayudar a reducir esos costos?
7. ¿Cuáles son tus expectativas en cuanto a seguridad y comodidad al ofrecer tu vehículo para transportar a otros?

### 2.2.2 Registro de entrevistas

#### **Segmento 1: Estudiantes Universitarios**

**Entrevista 1:**

- **Nombres:** Melina
- **Apellidos:** Rojas Sosa
- **Edad:** 19
- **Lugar de residencia:** Ate, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/EvidenciaEntrevista.png">

**Enlace de la entrevista:** [https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475%5Fupc%5Fedu%5Fpe%2FDocuments%2FTEAM%20SOFTWARE%20PROCESS%2FENTREVISTAS%2FAngel%20Anampa%20%2D%201er%20segmento%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Efe2fdd23%2Dbae9%2D4e48%2D9efb%2D4e7d035773e3
](https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475%5Fupc%5Fedu%5Fpe%2FDocuments%2FTEAM%20SOFTWARE%20PROCESS%2FENTREVISTAS%2FAngel%20Anampa%20%2D%201er%20segmento%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Efe2fdd23%2Dbae9%2D4e48%2D9efb%2D4e7d035773e3)
**Resumen de la entrevista:**  
Melina es una estudiante universitaria que enfrenta dificultades diarias para llegar a sus clases debido a la congestión vehicular en Lima. Ella expresa que estaría encantada si existiera un servicio de carpooling que le permitiera llegar más rápido a la universidad. Además, destaca los beneficios adicionales que este tipo de servicio podría ofrecer, como la oportunidad de hacer networking con otros estudiantes de su misma universidad.

---

**Entrevista 2:**

- **Nombres:** Sebastian
- **Apellidos:** Mendez
- **Edad:** 22
- **Lugar de residencia:** Ate, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/MendezEvidencia.png">

**Enlace de la entrevista:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202115590_upc_edu_pe/EX3HYcv8l09EmHBq5wEKB8IBuyRvbgm4H99tEktUwkfYmg?e=TgFCEg&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

**Resumen de la entrevista:**  
Sebastian vive en Ate y estudia en la UPC Monterrico le toma 1hora 30min para llegar a su universidad, normalmente tiene dificultades movilizarse debido al trafico. Nos cuenta que le parece una idea interesante nuestra propuesta y le gustaria probarla si le ayuda a ahorrar costo y evitar demorarse como normalmente lo hace al tomar las microbuses.

---

**Entrevista 3:**

- **Nombres:** Aaron Alejandro
- **Apellidos:** Cruz Ticona
- **Edad:** 21
- **Lugar de residencia:** Santiago de Surco, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/entrevista02.png">

**Enlace de la entrevista:** https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475_upc_edu_pe%2FDocuments%2FTEAM%20SOFTWARE%20PROCESS%2FENTREVISTAS%2FABRAHAM%20AYQUIPA%20-%201ER%20SEGMENTO%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E11770188-ced7-423a-a07b-8c3a4a95c2a1

**Resumen de la entrevista:**  
Aaron nos indicó que tiene 21 años, vive actualmente en Surco. Estudia en la UPC sede monterrico pero una vez por la semana tiene que movilizarse a un diferente campus lo que le genera molestia pues el trayecto es demasiado largo e indica que una propuesta de solucón a su problema como la nuestra le vendría bastante bien.


---

**Entrevista 4:**

- **Nombres:** Milagros
- **Apellidos:** Tongo Alejandro
- **Edad:** 21
- **Lugar de residencia:** Santa Anita, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/1entrevista4.png">

**Enlace de la entrevista:** https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475%5Fupc%5Fedu%5Fpe%2FDocuments%2FTEAM%20SOFTWARE%20PROCESS%2FENTREVISTAS%2FFavio%20Landeo%201er%20segmento%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E3c8ed694%2De927%2D48c7%2D8870%2D64d549537ade

**Resumen de la entrevista:**  
Milagros tiene 21 años, vive actualmente en el distrito de Santa Anita, estudia en la UPC sede Monterrico y se moviliza seguido porque tiene cursos casi todos los días de la semana. Indica que está a favor del ride-sharing para su seguridad y comodidad.


---

#### **Segmento 2: Estudiantes universitarios propietarios de vehículos privados**

**Entrevista 1:**

- **Nombres:** Jose
- **Apellidos:** Zarate Castro
- **Edad:** 22
- **Lugar de residencia:** San Juan Lurigancho, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/ZarateEvidencia.png">

**Enlace de la entrevista:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202115590_upc_edu_pe/EX3HYcv8l09EmHBq5wEKB8IBuyRvbgm4H99tEktUwkfYmg?e=cYNkaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

**Resumen de la entrevista:**  
Jose es un estudiante que es propietario de un vehiculo, nos comenta que le parece buena la idea la aplicacion ya que podria ayudarle a solventar gastos de gasolina o peaje pero que se encuentre en su ruta de viaje para que le salga rentable. Lo que busca en la aplicacion es tener seguridad como ver calificacion de usuarios para conocer con que tipo de pasajeros va lidiar.

---

**Entrevista 2:**

- **Nombres:** Natanael David
- **Apellidos:** Soto salis
- **Edad:** 24
- **Lugar de residencia:** Santiago de Surco, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/entrevista01.png">

**Enlace de la entrevista:** https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475_upc_edu_pe%2FDocuments%2FTEAM%20SOFTWARE%20PROCESS%2FENTREVISTAS%2FABRAHAM%20AYQUIPA%20-%202DO%20SEGMENTO%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E9336584c-0401-42f5-9db3-d3d03ee17a42

**Resumen de la entrevista:**  
Natanael nos indicó que vive en santiago de surco y tiene 24 años, cuenta con un vehiculo con el que está dispuesto a usarlo para llevar a su universidad(UPC) a otros estudiantes con el fin de contar con un ingreso extra pero bajo la condición de que la aplicación analice los perfiles de los estudiantes que requieren el servicio por seguridad.

---

**Entrevista 3:**

- **Nombres:** Ariana
- **Apellidos:** Martinez
- **Edad:** 24
- **Lugar de residencia:** Santiago de Surco, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/">

**Enlace de la entrevista:** 

**Resumen de la entrevista:**  

---

**Entrevista 4:**

- **Nombres:** Paul
- **Apellidos:** Vega Sayritupac
- **Edad:** 23
- **Lugar de residencia:** San Juan de Lurigancho, Lima

**Evidencia de la entrevista:**  
<img src="assets/images/interviews/2entrevista4.png">

**Enlace de la entrevista:** https://upcedupe-my.sharepoint.com/personal/u202218475_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202218475%5Fupc%5Fedu%5Fpe%2FDocuments%2FTEAM%20SOFTWARE%20PROCESS%2FENTREVISTAS%2FFavio%20Landeo%202do%20segmento%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ecd8872a6%2D2846%2D4f13%2Db413%2D88d52afa5d48

**Resumen de la entrevista:**  
Paul nos comenta que él estudia y trabaja por lo que se moviliza toda su semana laboral con su vehículo particular, utiliza GNV y estaría dispuesto a obtener un ingreso extra haciendo ride-sharing con otros estudiantes que viven entre su ruta desde su casa hasta la universidad.

---

### 2.2.3 Análisis de entrevistas.
<TABLE BORDER>
	<TR>
		<TD COLSPAN = 2 align=center>

*Características*</TD>

<TD align=center>

*Segmento1*
<br>
*Estudiantes universitarios*
</TD>

<TD align=center>

*Segmento2*
<br>
*Estudiantes universitarios propietarios de vehiculos privados*
</TD>

   </TR>
	<TR>
		<TD ROWSPAN = 4>

*Objetivas*
</TD>
<TD>Tráfico</TD>
<TD>Costos</TD>
<TD>Seguridad</TD>
</TR>
<TR>
<TD>Problemas con el tráfico diario</TD>
<TD>Potencial de ahorro en transporte </TD>
<TD>Preocupación por la seguridad en transporte público</TD>
</TR>
<TR>
<TD>Menos relevante, pero buscan reducir tiempo y costo</TD>
<TD>Reducir costos de transporte es clave </TD>
<TD>Seguridad personal y verificación de identidad son cruciales</TD>
</TR>
<TR>
<TD >Mejoraría tiempos de viaje y eficiencia</TD>
<TD>N/A</TD>
<TD>Reducir tiempos también es valorado</TD>
</TR>

   <TR>
		<TD ROWSPAN = 4>

*Subjetivas*
</TD>
<TD>Conexiones sociales</TD>
<TD>Comodidad</TD>
<TD>Reglas claras</TD>
<TR>
<TD>Oportunidad de hacer networking con otros estudiantes</TD>
<TD>Preferirían más comodidad que en transporte público</TD>
<TD>N/A</TD>
</TR>
<TR>
<TD>Hacer nuevas amistades mientras reducen costos</TD>
<TD>Preocupación por la comodidad de los pasajeros</TD>
<TD>Necesidad de reglas claras y sistemas de calificación</TD>
</TR>
<TR>

</TR>
</TABLE>

## 2.3. Needfinding

### 2.3.1. User Personas

#### *Estudiantes universitarios:*

<img src="assets/images/user-persona/user-persona-1.png" width="800px">

#### *Estudiantes Universitarios propietarios de vehículos privados:*

<img src="assets/images/user-persona/user-persona-2.png" width="800px">

---

### 2.3.2. User Task Matrix

A continuación se pueden apreciar los User Task Matrix de los segmentos objetivos.

#### *Segmento Objetivo: Estudiantes Universitarios*

| **Task**                                 | **Frequency** | **Importance** |
|------------------------------------------|---------------|-----------------|
| Buscar compañeros disponibles en la app  | High          | High            |
| Coordinar el punto de encuentro           | Medium        | Medium          |
| Realizar pagos a través de la app         | Medium        | High            |
| Verificar la seguridad del conductor/compañeros | High      | High            |
| Calificar al conductor y el viaje         | Low           | Medium          |
| Planificar viajes recurrentes             | Medium        | High            |
| Ser partícipe de promociones o descuentos | Low           | Medium          |

---

#### *Segmento Objetivo: Estudiantes universitarios propietarios de vehículos privados*

| **Task**                                 | **Frequency** | **Importance** |
|------------------------------------------|---------------|-----------------|
| Publicar la disponibilidad del vehículo  | High          | High            |
| Aceptar solicitudes de pasajero           | High          | High            |
| Coordinar horarios y puntos de recogida   | Medium        | Medium          |
| Recibir pago de los pasajeros             | High          | High            |
| Revisar la seguridad y confiabilidad del pasajero | Medium  | High            |
| Calificar a los pasajeros                 | Low           | Medium          |
| Optimizar rutas para ahorrar tiempo y combustible | Medium | High            |


### 2.3.3. User Journey Mapping

A continuación se pueden apreciar los User Journey Mapping de los segmentos objetivos.

#### *Estudiantes Universitarios*

<img src="assets/images/user-journey-mapping/journey-map-1.png" width="900px">

#### *Estudiantes universitarios propietarios de vehículos privados*

<img src="assets/images/user-journey-mapping/journey-map-2.png" width="900px">

---

### 2.3.4. Empathy Mapping

A continuación se pueden apreciar los Empathy Mapping de los segmentos objetivos.

#### *Estudiantes Universitarios*

<img src="assets/images/empathy-mapping/empathy-mapping-1.png" width="900px">

#### *Estudiantes universitarios propietarios de vehículos privados*

<img src="assets/images/empathy-mapping/empathy-mapping-2.png" width="900px">

---

### 2.3.5. As-is Scenario Mapping

A continuación se pueden apreciar los As-Is Scenario de los segmentos objetivos.

#### *Estudiantes Universitarios*

<img src="assets/images/as-is-scenario-mapping/as-is-scenario-1.png" width="900px">

#### *Estudiantes universitarios propietarios de vehículos privados*

<img src="assets/images/as-is-scenario-mapping/as-is-scenario-2.png" width="900px">

**Enlace de Miro:** [As-Is Scenario Mapping Board](https://miro.com/app/board/uXjVKlGuWKk=/?share_link_id=612949293517)

---

## 2.4. Ubiquitous Language

- **Usuario**: Estudiante universitario registrado en la plataforma, ya sea como conductor o pasajero.
- **Conductor**: Estudiante universitario que posee un vehículo y está dispuesto a compartir su viaje hacia la universidad con otros estudiantes a cambio de una compensación económica.
- **Pasajero**: Estudiante universitario que utiliza la plataforma para buscar conductores con rutas compatibles y compartir un viaje hacia su universidad a cambio de una tarifa.
- **Viaje Compartido**: Desplazamiento en un vehículo particular en el que participan un conductor y uno o más pasajeros que comparten una ruta similar hacia la universidad.
- **Ruta**: Trayectoria específica que sigue un conductor desde su punto de origen hasta la universidad, la cual es compartida con los pasajeros a través de la plataforma.
- **Carpooling**: El acto de compartir un viaje entre varias personas para optimizar el uso de un vehículo particular, reducir costos y disminuir la congestión vehicular.
- **Reserva de Viaje**: Proceso mediante el cual un pasajero asegura un asiento en el vehículo de un conductor para un viaje específico, siguiendo una ruta y horario predeterminado.
- **Tarifa**: Costo que un pasajero paga al conductor por compartir el viaje. Esta tarifa cubre una parte de los gastos del conductor, como el combustible.
- **Perfil del Usuario**: Información detallada que cada usuario (conductor o pasajero) proporciona a la plataforma, incluyendo su nombre, universidad, calificaciones previas, y preferencias de viaje.
- **Calificación**: Sistema de puntuación que los pasajeros y conductores otorgan mutuamente después de cada viaje, basado en aspectos como puntualidad, seguridad y comportamiento durante el trayecto.
- **Notificación**: Comunicación enviada a los usuarios a través de la plataforma, informándoles sobre el estado de su reserva, cambios en la ruta, o recordatorios de viaje.
- **Punto de Encuentro**: Lugar acordado donde el conductor y los pasajeros se reúnen para iniciar el viaje compartido.
- **Destino**: La universidad u otro lugar predeterminado donde el viaje compartido finaliza.

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección se resume la información recopilada. Se presentan dos tablas que detallan la situación a mejorar de cada segmento objetivo, analizando los pasos que se realizarán y cómo se sienten los usuarios en cada etapa.

### *Segmento: Estudiantes Universitarios que necesiten movilizarse*

![ScenarioMapO1.jpg](assets/images/toBeScenarioMapping/ScenarioMapO1.jpg)

---

### *Segmento: Estudiantes Universitarios propietarios de vehículo privado*

![ScenarioMapO2.jpg](assets/images/toBeScenarioMapping/ScenarioMapO2.jpg)


## 3.2. User Stories

### Épicas del Proyecto
<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 21%" />
<col style="width: 39%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>
<tr class="odd" style="background-color:hsl(73, 75.00%, 95.30%);">
<td colspan="5" style="padding: 15px; border: 2px solid;">
<strong>Epic 1: Funcionalidades Básicas de Carpooling</strong><br>
<strong>Como</strong> estudiante universitario<br>
<strong>Quiero</strong> acceder a funcionalidades básicas de carpooling<br>
<strong>Para</strong> compartir viajes, generar ingresos y evaluar la seguridad de los trayectos
</td>
</tr>
<tr class="even">
<td>E1-US01</td>
<td>Compartir viajes con compañeros de universidad</td>
<td>
<p><strong>Como</strong> estudiante universitario sin vehículo,</p>
<p><strong>Quiero</strong> compartir viajes con compañeros que se dirijan a la universidad</p>
<p><strong>Para</strong> reducir costos y llegar de manera más eficiente</p>
</td>
<td>
<p>Escenario 1: Búsqueda de viajes disponibles</p>
<p><strong>Dado</strong> que el usuario necesita transporte hacia la universidad,</p>
<p><strong>Cuando</strong> accede a la plataforma</p>
<p><strong>Entonces</strong> podrá buscar y ver una lista de conductores disponibles que se dirijan a su universidad en un horario compatible</p>
<p>Escenario 2: Reserva de un viaje</p>
<p><strong>Dado</strong> que el usuario ha encontrado un viaje disponible,</p>
<p><strong>Cuando</strong> selecciona al conductor y realiza la reserva,</p>
<p><strong>Entonces</strong> podrá confirmar su lugar en el vehículo y recibir detalles sobre el viaje</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E1-US02</td>
<td>Generar ingresos compartiendo mi vehículo</td>
<td>
<p><strong>Como</strong> estudiante universitario con vehículo propio,</p>
<p><strong>Quiero</strong> ofrecer lugares en mi auto a otros estudiantes que van hacia la unviersidad</p>
<p><strong>Para</strong> reducir mis gastos de transporte y generar ingresos adicionales</p>
</td>
<td>
<p>Escenario 1: Publicación de disponibilidad de asientos</p>
<p><strong>Dado</strong> que el usuario tiene un vehículo con lugares disponibles,</p>
<p><strong>Cuando</strong> accede a la plataforma</p>
<p><strong>Entonces</strong> podrá publicar su ruta y disponibilidad de asientos para que otros estudiantes puedan reservar</p>
<p>Escenario 2: Gestión de reservas</p>
<p><strong>Dado</strong> que el usuario ha publicado su disponibilidad,</p>
<p><strong>Cuando</strong> los pasajeros reservan lugares en su vehículo,</p>
<p><strong>Entonces</strong> podrá ver y gestionar todas las reservas en su aplicación, confirmando los pasajeros y horarios</p>
</td>
<td>1</td>
</tr>

<tr class="even">
<td>E1-US03</td>
<td>Evaluar la seguridad del viaje</td>
<td>
<p><strong>Como</strong> estudiante,</p>
<p><strong>Quiero</strong> evaluar a los conductores y recibir calificaciones de otros usuarios</p>
<p><strong>Para</strong> asegurarme de que el viaje sea seguro y confiable</p>
</td>
<td>
<p>Escenario 1: Ver calificaciones de conductores</p>
<p><strong>Dado</strong> que el usuario está reservando un viaje,</p>
<p><strong>Cuando</strong> selecciona un conductor,</p>
<p><strong>Entonces</strong> podrá ver la calificación y los comentarios de otros pasajeros sobre la experiencia previa a ese conductor</p>
<p>Escenario 2: Dejar una calificación</p>
<p><strong>Dado</strong> que el usuario ha completado un viaje,</p>
<p><strong>Cuando</strong> finalice el trayecto,</p>
<p><strong>Entonces</strong> podrá dejar una calificación y comentarios sobre la experiencia con el conductor</p>
</td>
<td>1</td>
</tr>

<tr class="even" style="background-color:hsl(73, 75.00%, 95.30%);">
<td colspan="5" style="padding: 15px; border: 2px solid;">
<strong>Epic 2: Seguridad y Notificaciones</strong><br>
<strong>Como</strong> usuario de la plataforma<br>
<strong>Quiero</strong> contar con sistemas de seguridad y notificaciones<br>
<strong>Para</strong> tener viajes seguros con notificaciones en tiempo real y pagos protegidos
</td>
</tr>
<tr class="odd">
<td>E2-US01</td>
<td>Recibir notificaciones en tiempo real</td>
<td>
<p><strong>Como</strong> estudiante pasajero,</p>
<p><strong>Quiero</strong> recibir notificaciones en tiempo real sobre mi viaje </p>
<p><strong>Para</strong> estar al tanto de cualquier cambio en la ruta o el horario</p>
</td>
<td>
<p>Escenario 1: Actualización de la hora de llegada</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> haya un cambio en la ruta o el horario,</p>
<p><strong>Entonces</strong> el usuario recibirá una notificación en tiempo real indicando el neuvo tiempo estimado de llegada</p>
<p>Escenario 2: Notificación de recogida</p>
<p><strong>Dado</strong> que el conductor está llegando a recoger a un pasajero,</p>
<p><strong>Cuando</strong> esté cerca al punto de encuentro,</p>
<p><strong>Entonces</strong> el usuario recibirá una notificación informándole que el conductor está próximo</p>
</td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US02</td>
<td>Verificación de identidades</td>
<td>
<p><strong>Como</strong> usuario de la plataforma,</p>
<p><strong>Quiero</strong> que tanto los conductores como los pasajeros verifiquen sus identidades </p>
<p><strong>Para</strong> asegurarme de que mi viaje será con persona confiables</p>
</td>
<td>
<p>Escenario 1: Verificación de conductores</p>
<p><strong>Dado</strong> que el usuario va realizar un viaje,</p>
<p><strong>Cuando</strong> seleccione un conductor,</p>
<p><strong>Entonces</strong> podrá ver si el conductor ha verificado su identidad y sus documentos</p>
<p>Escenario 2: Verificación de pasajeros</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> los pasajeros confirmen su reserva,</p>
<p><strong>Entonces</strong> el conductor podrá ver si los pasajeros han verificado su identidad a través de la plataforma</p>
</td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US03</td>
<td>Realizar pagos de manera segura</td>
<td>
<p><strong>Como</strong> pasajero,</p>
<p><strong>Quiero</strong> realizar el pago del viaje a través de la paltaforma de forma segura </p>
<p><strong>Para</strong> no tener que manejar efectivo durante el trayecto</p>
</td>
<td>
<p>Escenario 1: Pago en línea</p>
<p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
<p><strong>Cuando</strong> confirme su reserva,</p>
<p><strong>Entonces</strong> podrá realizar el apgo del viaje a través de la plataforma utilizando métodos de pago seguros como tarjeta de crédito, débito o bileteras digitales</p>
<p>Escenario 2: Confirmación de pago</p>
<p><strong>Dado</strong> que el usuario ha realizado el pago,</p>
<p><strong>Cuando</strong> se complete la transacción,</p>
<p><strong>Entonces</strong> recibirá una confirmación del pago en su correo electrónico o dentro de la aplicación</p>
</td>
<td>2</td>
</tr>

<tr class="odd" style="background-color:hsl(73, 75.00%, 95.30%);">
<td colspan="5" style="padding: 15px; border: 2px solid;">
<strong>Epic 3: Gestión de Usuarios y Viajes</strong><br>
<strong>Como</strong> usuario<br>
<strong>Quiero</strong> gestionar mi cuenta y mis viajes<br>
<strong>Para</strong> registrarme, buscar viajes, hacer reservas y comunicarme con otros usuarios
</td>
</tr>
 <tr class="even">
        <td>E3-US01</td>
        <td>Registro de usuario</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder crear mi usuario</p>
            <p><strong>Para</strong> acceder al servicio de carpooling</p>
        </td>
        <td>
            <p>Escenario 1: Registro del usuario</p>
            <p><strong>Dado</strong> que el usuario quiere unirse a la plataforma,</p>
            <p><strong>Cuando</strong> complete el formulario de registro,</p>
            <p><strong>Entonces</strong> recibirá un correo electrónico de confirmación después del registro.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US02</td>
        <td>Búsqueda de Viaje Disponibles</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> buscar viajes disponibles</p>
            <p><strong>Para</strong> poder planificar mis desplazamientos</p>
        </td>
        <td>
            <p>Escenario 1: Filtrado de viajes</p>
            <p><strong>Dado</strong> que el usuario necesita un viaje,</p>
            <p><strong>Cuando</strong> ingrese sus criterios de búsqueda,</p>
            <p><strong>Entonces</strong> podrá ver una lista de viajes disponibles con información detallada.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US03</td>
        <td>Reserva de Viaje</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder reservar un asiento en el viaje disponible</p>
            <p><strong>Para</strong> garantizar mi lugar.</p>
        </td>
        <td>
            <p>Escenario 1: Confirmación de reserva</p>
            <p><strong>Dado</strong> que el usuario ha seleccionado un viaje,</p>
            <p><strong>Cuando</strong> acceda a la página de detalles del viaje,</p>
            <p><strong>Entonces</strong> podrá encontrar la opción para reservar un asiento y confirmar la reserva.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US04</td>
        <td>Comunicación con el Conductor</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder comunicarme con el conductor de mi viaje</p>
            <p><strong>Para</strong> coordinar detalles y obtener información adicional.</p>
        </td>
        <td>
            <p>Escenario 1: Mensajería dentro de la plataforma</p>
            <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
            <p><strong>Cuando</strong> quiera comunicarse con el conductor,</p>
            <p><strong>Entonces</strong> podrá hacerlo a través de la plataforma UniRider.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US05</td>
        <td>Cancelación de Reserva</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder cancelar una reserva de viaje</p>
            <p><strong>Para</strong> los casos de que surjan imprevistos</p>
        </td>
        <td>
            <p>Escenario 1: Cancelación de reserva</p>
            <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
            <p><strong>Cuando</strong> acceda a la página de detalles de su reserva,</p>
            <p><strong>Entonces</strong> podrá encontrar la opción para cancelar su reserva y confirmar la cancelación.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US06</td>
        <td>Calificación y Comentario del Conductor</td>
        <td>
            <p><strong>Como</strong> Usuario,</p>
            <p><strong>Quiero</strong> poder calificar y dejar comentarios sobre la experiencia de viaje con el conductor</p>
            <p><strong>Para</strong> ayudar a otros usuarios en su elección</p>
        </td>
        <td>
            <p>Escenario 1: Calificación del conductor</p>
            <p><strong>Dado</strong> que el usuario ha completado un viaje,</p>
            <p><strong>Cuando</strong> quiera dejar una opinión,</p>
            <p><strong>Entonces</strong> podrá calificar al conductor con una puntuación y un comentario opcional.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="even">
        <td>E3-US07</td>
        <td>Publicación de disponibilidad de asientos</td>
        <td>
            <p><strong>Como</strong> Usuario con vehículo,</p>
            <p><strong>Quiero</strong> publicar la disponibilidad de asientos</p>
            <p><strong>Para</strong> que otros estudiantes puedan reservar</p>
        </td>
        <td>
            <p>Escenario 1: Publicación de disponibilidad</p>
            <p><strong>Dado</strong> que el usuario tiene un vehículo con lugares disponibles,</p>
            <p><strong>Cuando</strong> acceda a la plataforma,</p>
            <p><strong>Entonces</strong> podrá publicar su ruta y disponibilidad de asientos para que otros estudiantes puedan reservar.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E3-US08</td>
        <td>Gestión de reservas</td>
        <td>
            <p><strong>Como</strong> Usuario con vehículo,</p>
            <p><strong>Quiero</strong> gestionar las reservas de los pasajeros</p>
            <p><strong>Para</strong> confirmar los pasajeros y horarios</p>
        </td>
        <td>
            <p>Escenario 1: Gestión de reservas</p>
            <p><strong>Dado</strong> que el usuario ha publicado su disponibilidad,</p>
            <p><strong>Cuando</strong> los pasajeros reservan lugares en su vehículo,</p>
            <p><strong>Entonces</strong> podrá ver y gestionar todas las reservas en su aplicación, confirmando los pasajeros y horarios.</p>
        </td>
        <td>3</td>
    </tr>

<tr class="odd" style="background-color:hsl(73, 75.00%, 95.30%);">
<td colspan="5" style="padding: 15px; border: 2px solid ;">
<strong>Epic 4: Planes de Servicio y Suscripciones</strong><br>
<strong>Como</strong> usuario de la plataforma<br>
<strong>Quiero</strong> acceder a diferentes planes de servicio<br>
<strong>Para</strong> elegir la suscripción que mejor se adapte a mis necesidades y presupuesto
</td>
</tr>
<tr class="even">
        <td>E4-US01</td>
        <td>Visualizar planes de servicio</td>
        <td>
            <p><strong>Como</strong> usuario que visita la plataforma del restaurante,</p>
            <p><strong>Quiero</strong> visualizar los planes de servicio disponibles</p>
            <p><strong>Para</strong> evaluar las opciones y elegir el que mejor se adapte a mis necesidades</p>
        </td>
        <td>
            <p>Escenario 1: Visualización inicial de los planes de servicio</p>
            <p><strong>Dado</strong> que el usuario ha accedido a la plataforma,</p>
            <p><strong>Cuando</strong> el usuario navega a la sección de planes de servicio,</p>
            <p><strong>Entonces</strong> se muestran todos los planes disponibles en una lista, incluyendo el nombre del plan, precio y beneficios principales.</p>
        </td>
        <td>
            <p>Escenario 2: Ver detalles de un plan específico</p>
            <p><strong>Dado</strong> que el usuario está visualizando los planes de servicio,</p>
            <p><strong>Cuando</strong> el usuario selecciona un plan específico de la lista,</p>
            <p><strong>Entonces</strong> se muestra con los detalles completos del plan, incluyendo una descripción más detallada de los beneficios y cualquier condición asociada.</p>
        </td>
        <td>3</td>
    </tr>

  <tr class="odd">
        <td>E4-US02</td>
        <td>Seleccionar un plan de servicio</td>
        <td>
            <p><strong>Como</strong>usuario registrado en la plataforma,</p>
            <p><strong>Quiero</strong> seleccionar un plan de servicio</p>
            <p><strong>Para</strong> adquirir los beneficios específicos que ofrece el plan</p>
        </td>
        <td>
            <p>Escenario 1: Selección de un plan desde la lista</p>
            <p><strong>Dado</strong> que el usuario ha visualizado los planes de servicio disponibles,</p>
            <p><strong>Cuando</strong> el usuario selecciona un plan de la lista,</p>
            <p><strong>Entonces</strong> se redirige al usuario a una página de confirmación, mostrando un resumen del plan seleccionado.</p>
        </td>
        <td>
            <p>Escenario 2: Confirmación de selección del plan</p>
            <p><strong>Dado</strong> que el usuario ha seleccionado un plan,</p>
            <p><strong>Cuando</strong> el usuario revisa el resumen del plan en la página de confirmación,,</p>
            <p><strong>Entonces</strong> tiene la opción de confirmar la selección o regresar a la lista de planes para elegir otro.</p>
        </td>
        <td>3</td>
    </tr>
    
<tr class="even">
        <td>E4-US03</td>
        <td>Realizar el pago del plan seleccionado</td>
        <td>
            <p><strong>Como</strong> usuario que ha seleccionado un plan,</p>
            <p><strong>Quiero</strong> realizar el pago del plan seleccionado</p>
            <p><strong>Para</strong> activar los beneficios del plan y comenzar a utilizarlos</p>
        </td>
        <td>
            <p>Escenario 1: Ingreso de detalles de pago</p>
            <p><strong>Dado</strong>  que el usuario ha confirmado la selección de un plan y ha sido redirigido a la página de pago,
            <p><strong>Cuando</strong> el usuario introduce los detalles de pago (tarjeta de crédito, PayPal, etc.),</p>
            <p><strong>Entonces</strong> el sistema verifica la validez de los detalles ingresados y muestra un resumen de la transacción.</p>
        </td>
        <td>
            <p>Escenario 2: Confirmación del pago</p>
            <p><strong>Dado</strong> que el usuario ha ingresado detalles de pago válidos,</p>
            <p><strong>Cuando</strong> el usuario confirma la transacción,</p>
            <p><strong>Entonces</strong> el sistema procesa el pago y muestra una confirmación en pantalla, indicando que el plan ha sido activado con éxito.</p>
        </td>
        <td>
            <p>Escenario 3: Notificación de pago exitoso</p>
            <p><strong>Dado</strong> que el pago ha sido procesado con éxito,</p>
            <p><strong>Cuando</strong> la transacción se completa,</p>
            <p><strong>Entonces</strong> el usuario recibe una notificación de confirmación por correo electrónico, detallando el plan adquirido y los beneficios activados.</p>
        </td>
        <td>5</td>
    </tr>

<tr class="odd">
        <td>E4-US04</td>
        <td>Cancelar suscripción o plan</td>
        <td>
            <p><strong>Como</strong>usuario que ha adquirido un plan,</p>
            <p><strong>Quiero</strong> cancelar mi suscripción o plan</p>
            <p><strong>Para</strong> dejar de recibir los beneficios y evitar cargos futuros</p>
        </td>
        <td>
            <p>Escenario 1: Acceso a la opción de cancelación</p>
            <p><strong>Dado</strong> que el usuario tiene un plan activo en su cuenta,</p>
            <p><strong>Cuando</strong> el usuario accede a la sección de “Mis planes” o “Mi cuenta”,</p>
            <p><strong>Entonces</strong> se le muestra la opción de cancelar su suscripción o plan actual.</p>
        </td>
        <td>
            <p>Escenario 2: Coonfirmación de la cancelación</p>
            <p><strong>Dado</strong> que el usuario ha solicitado cancelar su plan,</p>
            <p><strong>Cuando</strong> el usuario hace clic en “Cancelar plan” y se le solicita confirmar la acción,</p>
            <p><strong>Entonces</strong> el sistema muestra un mensaje de confirmación que explica las consecuencias de la cancelación.</p>
        </td>
        <td>3</td>
    </tr>

<tr class="odd" style="background-color:hsl(73, 75.00%, 95.30%);">
<td colspan="5" style="padding: 15px; border: 2px solid ;">
<strong>Epic 5: Landing Page</strong><br>
<strong>Como</strong> cliente<br>
<strong>Quiero</strong> visualizar una página informativa<br>
<strong>Para</strong> conocer más acerca de la aplicación web y poder ingresar a ella
</td>
</tr>
<tr class="even">
<td>E5-US01</td>
<td>Barra de navegación en la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> una barra de navegación en la landing page,</p>
<p><strong>Para</strong> tener acceso directo a la aplicación.</p>
</td>
<td>
<p>Escenario 1: El cliente o conducto se encuentra en el navbar de navegación</p>
<p><strong>Dado</strong> que el usuario se encuentra en la landing page,</p>
<p><strong>Cuando</strong> se encuentre en la sección del navbar,</p>
<p><strong>Entonces</strong> visualiza enlaces de las secciones, botón de idiomas y el botón para redirigir a la aplicación.</p>
</td>
<td>1</td>
</tr>

<tr class="odd">
<td>E5-US02</td>
<td>Dirigirse a la aplicación mediante la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> dirigirme a la aplicación mediante el botón “Open App”,</p>
<p><strong>Para</strong> poder usarla.</p>
</td>
<td>
<p>Escenario 1: Enlace directo a la aplicación a través de un botón</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> este se dirige al navbar,</p>
<p><strong>Cuando</strong> presione el botón “Open app”,</p>
<p><strong>Entonces</strong> es dirigido a la aplicación donde se podrá loguear.</p>
</td>
<td>2</td>
</tr>

<tr class="even">
<td>E5-US03</td>
<td>Sección hero del landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> observar la sección hero de la landing,</p>
<p><strong>Para</strong> poder tener información de lo que es y ofrece la aplicación.</p>
</td>
<td>
<p>Escenario 1: El cliente o conductor se encuentra en la sección de hero</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Cuando</strong> se encuentra en la sección hero,</p>
<p><strong>Entonces</strong> observa una presentación de la aplicación.</p>
<p>Escenario 2: El cliente o conductor accede a la aplicación por el botón de Sign Up</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> presiona el botón “Sign up”,</p>
<p><strong>Entonces</strong> es redirigido al formulario de registro de cuentas.</p>
</td>
<td>3</td>
</tr>

<tr class="odd">
<td>E5-US04</td>
<td>Versión en español de la landing page</td>
<td>
<p><strong>Como</strong> cliente o conductor,</p>
<p><strong>Quiero</strong> tener al alcance una versión en español del landing page,</p>
<p><strong>Para</strong> tener accesibilidad en cuanto a opciones de idioma.</p>
</td>
<td>
<p>Escenario 1: El cliente entra a la landing page</p>
<p><strong>Dado</strong> que el usuario se encuentra en el landing page,</p>
<p><strong>Cuando</strong> sea su primera vez,</p>
<p><strong>Entonces</strong> el idioma predeterminado de la landing page será inglés.</p>
<p>Escenario 2: El cliente quiere cambiar de idioma</p>
<p><strong>Dado</strong> que el usuario se encuentra en la landing page,</p>
<p><strong>Y</strong> desea cambiar de idioma a español,</p>
<p><strong>Cuando</strong> presiona el botón para cambiar de inglés a español,</p>
<p><strong>Entonces</strong> la landing page se muestra en el idioma de preferencia seleccionado.</p>
</td>
<td>4</td>
</tr>

<tr class="even">
<td>E5-US05</td>
<td>Sección about the product y about the team</td>
<td>
<p><strong>Como</strong> cliente o staff,</p>
<p><strong>Quiero</strong> ver la sección del about the product y about the team,</p>
<p><strong>Para</strong> conocer las características de la aplicación y del grupo de desarrolladores.</p>
</td>
<td>
<p>Escenario 1: Enlace directo a la sección about the product y the team</p>
<p><strong>Dado</strong> que el cliente o conductor se encuentra en la landing page,</p>
<p><strong>Y</strong> este se dirige al navbar,</p>
<p><strong>Entonces</strong> puede acceder directamente a la sección correspondiente.</p>
</td>
<td>5</td>
</tr>

<tr class="odd">
  <td>E1-US01</td>
  <td>Agendar notificaciones de recordatorio de viajes</td>
  <td>
    <p><strong>Como</strong> pasajero,</p>
    <p><strong>Quiero</strong> recibir notificaciones de recordatorio antes del inicio de mi viaje</p>
    <p><strong>Para</strong> asegurarme de estar listo a tiempo</p>
  </td>
  <td>
    <p>Escenario 1: Recordatorio antes del viaje</p>
    <p><strong>Dado</strong> que el usuario ha reservado un viaje,</p>
    <p><strong>Cuando</strong> queden 30 minutos para que comience el viaje,</p>
    <p><strong>Entonces</strong> recibirá una notificación recordándole el inicio próximo del viaje</p>
    <p>Escenario 2: Ubicación del conductor</p>
    <p><strong>Dado</strong> que el usuario ha recibido la notificación de recordatorio,</p>
    <p><strong>Cuando</strong> abra la aplicación,</p>
    <p><strong>Entonces</strong> podrá ver la ubicación y el tiempo estimado de llegada del conductor</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US02</td>
  <td>Filtrar viajes por tipos de vehículos</td>
  <td>
    <p><strong>Como</strong> pasajero,</p>
    <p><strong>Quiero</strong> poder filtrar los viajes según el tipo de vehículo</p>
    <p><strong>Para</strong> seleccionar el que más se ajuste a mis necesidades</p>
  </td>
  <td>
    <p>Escenario 1: Aplicar filtros</p>
    <p><strong>Dado</strong> que el usuario está buscando un viaje,</p>
    <p><strong>Cuando</strong> acceda a los filtros,</p>
    <p><strong>Entonces</strong> podrá seleccionar el tipo de vehículo, como sedan, SUV, o camioneta</p>
    <p>Escenario 2: Búsqueda de vehículos filtrados</p>
    <p><strong>Dado</strong> que el usuario ha aplicado el filtro,</p>
    <p><strong>Cuando</strong> seleccione "Buscar",</p>
    <p><strong>Entonces</strong> verá solo los viajes disponibles con el tipo de vehículo seleccionado</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US03</td>
  <td>Establecer destinos secundarios</td>
  <td>
    <p><strong>Como</strong> conductor,</p>
    <p><strong>Quiero</strong> poder establecer destinos secundarios durante mi ruta</p>
    <p><strong>Para</strong> recoger a más estudiantes en puntos intermedios</p>
  </td>
  <td>
    <p>Escenario 1: Añadir destinos secundarios</p>
    <p><strong>Dado</strong> que el usuario ha publicado un viaje,</p>
    <p><strong>Cuando</strong> esté configurando su ruta,</p>
    <p><strong>Entonces</strong> podrá agregar puntos de parada adicionales en el trayecto</p>
    <p>Escenario 2: Verificación de paradas</p>
    <p><strong>Dado</strong> que el conductor ha agregado un destino secundario,</p>
    <p><strong>Cuando</strong> un pasajero busque viajes,</p>
    <p><strong>Entonces</strong> podrá ver si hay paradas adicionales en la ruta del conductor</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US04</td>
  <td>Opciones de seguridad adicionales para conductores</td>
  <td>
    <p><strong>Como</strong> conductor,</p>
    <p><strong>Quiero</strong> poder acceder a opciones adicionales de seguridad, como compartir mi ubicación en tiempo real</p>
    <p><strong>Para</strong> garantizar un viaje seguro</p>
  </td>
  <td>
    <p>Escenario 1: Activar seguimiento de ubicación</p>
    <p><strong>Dado</strong> que el conductor ha iniciado un viaje,</p>
    <p><strong>Cuando</strong> comience el recorrido,</p>
    <p><strong>Entonces</strong> podrá activar la opción de compartir su ubicación en tiempo real con un contacto de confianza</p>
    <p>Escenario 2: Desactivar el seguimiento</p>
    <p><strong>Dado</strong> que el conductor ha compartido su ubicación,</p>
    <p><strong>Cuando</strong> termine el viaje,</p>
    <p><strong>Entonces</strong> podrá desactivar el seguimiento de la ubicación</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US05</td>
  <td>Identificación de usuarios frecuentes</td>
  <td>
    <p><strong>Como</strong> pasajero frecuente,</p>
    <p><strong>Quiero</strong> poder marcar ciertos conductores como favoritos</p>
    <p><strong>Para</strong> facilitar la reserva de futuros viajes con ellos</p>
  </td>
  <td>
    <p>Escenario 1: Marcar un conductor como favorito</p>
    <p><strong>Dado</strong> que el pasajero ha completado varios viajes con un conductor,</p>
    <p><strong>Cuando</strong> acceda a su perfil,</p>
    <p><strong>Entonces</strong> podrá marcarlo como "Favorito" para futuros viajes</p>
    <p>Escenario 2: Recibir notificaciones de conductores favoritos</p>
    <p><strong>Dado</strong> que el pasajero ha marcado a un conductor como favorito,</p>
    <p><strong>Cuando</strong> busque viajes,</p>
    <p><strong>Entonces</strong> recibirá notificaciones cuando ese conductor tenga disponibilidad</p>
  </td>
  <td>1</td>
</tr>

<tr class="odd">
  <td>E1-US06</td>
  <td>Programar viajes recurrentes</td>
  <td>
    <p><strong>Como</strong> usuario,</p>
    <p><strong>Quiero</strong> poder programar viajes recurrentes</p>
    <p><strong>Para</strong> no tener que hacer reservas diarias cada vez que necesite transporte</p>
  </td>
  <td>
    <p>Escenario 1: Programar viaje recurrente</p>
    <p><strong>Dado</strong> que el usuario necesita transporte diario,</p>
    <p><strong>Cuando</strong> acceda a la opción de "Viajes recurrentes",</p>
    <p><strong>Entonces</strong> podrá establecer un horario y ruta fijos para repetir el viaje automáticamente</p>
    <p>Escenario 2: Confirmación de viajes recurrentes</p>
    <p><strong>Dado</strong> que el usuario ha programado un viaje recurrente,</p>
    <p><strong>Cuando</strong> se aproxime la fecha del viaje,</p>
    <p><strong>Entonces</strong> recibirá una confirmación automática del viaje y detalles del conductor</p>
  </td>
  <td>1</td>
</tr>

</tbody>
</table>
<hr>

## 3.3. Impact Mapping.


## 3.4. Product Backlog.
<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 28%" />
<col style="width: 14%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th>#Orden</th>
<th>User Story ID</th>
<th>Titulo</th>
<th>Descripcion</th>
<th>Prioridad</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td>US01</td>
<td>Compartir viajes con compañeros de universidad</td>
<td><p><strong>Como</strong> estudiante universitario sin vehículo,</p>
<p><strong>quiero</strong> compartir viajes con compañeros que se dirijan a la universidad</p>
<p><strong>para</strong> reducir costos y llegar de manera más eficiente</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>2</td>
<td>US02</td>
<td>Generar ingresos compartiendo mi vehículo</td>
<td><p><strong>Como</strong> estudiante universitario con vehículo propio,</p>
<p><strong>quiero</strong> ofrecer lugares en mi auto a otros estudiantes que van hacia la universidad</p>
<p><strong>para</strong> reducir mis gastos de transporte y generar ingresos adicionales</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>3</td>
<td>US03</td>
<td>Evaluar la seguridad del viaje</td>
<td><p><strong>Como</strong> estudiante,</p>
<p><strong>quiero</strong> evaluar a los conductores y recibir calificaciones de otros usuarios</p>
<p><strong>para</strong> asegurarme de que el viaje sea seguro y confiable</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>4</td>
<td>US04</td>
<td>Recibir notificaciones en tiempo real</td>
<td><p><strong>Como</strong> estudiante pasajero,</p>
<p><strong>quiero</strong> recibir notificaciones en tiempo real sobre mi viaje</p>
<p><strong>para</strong> estar al tanto de cualquier cambio en la ruta o el horario</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>5</td>
<td>US05</td>
<td>Verificación de identidades</td>
<td><p><strong>Como</strong> usuario de la plataforma,</p>
<p><strong>quiero</strong> que tanto los conductores como los pasajeros verifiquen sus identidades</p>
<p><strong>para</strong> asegurarme de que mi viaje será con personas confiables</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>6</td>
<td>US06</td>
<td>Realizar pagos de manera segura</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> realizar el pago del viaje a través de la plataforma de forma segura</p>
<p><strong>para</strong> no tener que manejar efectivo durante el trayecto</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>7</td>
<td>US07</td>
<td>Registro de usuario</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder crear mi usuario</p>
<p><strong>para</strong> acceder al servicio de carpooling</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="even">
<td>8</td>
<td>US08</td>
<td>Búsqueda de viajes disponibles</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> buscar viajes disponibles</p>
<p><strong>para</strong> poder planificar mis desplazamientos</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>9</td>
<td>US09</td>
<td>Reserva de viaje</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder reservar un asiento en el viaje disponible</p>
<p><strong>para</strong> garantizar mi lugar</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>10</td>
<td>US10</td>
<td>Comunicación con el conductor</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder comunicarme con el conductor de mi viaje</p>
<p><strong>para</strong> coordinar detalles y obtener información adicional</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>11</td>
<td>US11</td>
<td>Cancelación de reserva</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder cancelar una reserva de viaje</p>
<p><strong>para</strong> los casos de que surjan imprevistos</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="even">
<td>12</td>
<td>US12</td>
<td>Calificación y comentario del conductor</td>
<td><p><strong>Como</strong> Usuario,</p>
<p><strong>quiero</strong> poder calificar y dejar comentarios sobre la experiencia de viaje con el conductor</p>
<p><strong>para</strong> ayudar a otros usuarios en su elección</p></td>
<td>Alta</td>
<td>3</td>
</tr>
<tr class="odd">
<td>13</td>
<td>US13</td>
<td>Publicación de disponibilidad de asientos</td>
<td><p><strong>Como</strong> Usuario con vehículo,</p>
<p><strong>quiero</strong> publicar la disponibilidad de asientos</p>
<p><strong>para</strong> que otros estudiantes puedan reservar</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>14</td>
<td>US14</td>
<td>Gestión de reservas</td>
<td><p><strong>Como</strong> Usuario con vehículo,</p>
<p><strong>quiero</strong> gestionar las reservas de los pasajeros</p>
<p><strong>para</strong> confirmar los pasajeros y horarios</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>15</td>
<td>US15</td>
<td>Visualizar planes de servicio</td>
<td><p><strong>Como</strong> usuario que visita la plataforma del restaurante,</p>
<p><strong>quiero</strong> visualizar los planes de servicio disponibles</p>
<p><strong>para</strong> evaluar las opciones y elegir el que mejor se adapte a mis necesidades</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>16</td>
<td>US16</td>
<td>Seleccionar un plan de servicio</td>
<td><p><strong>Como</strong> usuario registrado en la plataforma,</p>
<p><strong>quiero</strong> seleccionar un plan de servicio</p>
<p><strong>para</strong> adquirir los beneficios específicos que ofrece el plan</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>17</td>
<td>US17</td>
<td>Realizar el pago del plan seleccionado</td>
<td><p><strong>Como</strong> usuario que ha seleccionado un plan,</p>
<p><strong>quiero</strong> realizar el pago del plan seleccionado</p>
<p><strong>para</strong> activar los beneficios del plan y comenzar a utilizarlos</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>18</td>
<td>US18</td>
<td>Cancelar suscripción o plan</td>
<td><p><strong>Como</strong> usuario que ha adquirido un plan,</p>
<p><strong>quiero</strong> cancelar mi suscripción o plan</p>
<p><strong>para</strong> dejar de recibir los beneficios y evitar cargos futuros</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>19</td>
<td>US19</td>
<td>Barra de navegación en la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> una barra de navegación en la landing page,</p>
<p><strong>para</strong> tener acceso directo a la aplicación</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="even">
<td>20</td>
<td>US20</td>
<td>Dirigirse a la aplicación mediante la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> dirigirme a la aplicación mediante el botón “Open App”,</p>
<p><strong>para</strong> poder usarla</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>21</td>
<td>US21</td>
<td>Sección hero del landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> observar la sección hero de la landing,</p>
<p><strong>para</strong> poder tener información de lo que es y ofrece la aplicación</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>22</td>
<td>US22</td>
<td>Versión en español de la landing page</td>
<td><p><strong>Como</strong> cliente o conductor,</p>
<p><strong>quiero</strong> tener al alcance una versión en español del landing page,</p>
<p><strong>para</strong> tener accesibilidad en cuanto a opciones de idioma</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="odd">
<td>23</td>
<td>US23</td>
<td>Sección about the product y about the team</td>
<td><p><strong>Como</strong> cliente o staff,</p>
<p><strong>quiero</strong> ver la sección del about the product y about the team,</p>
<p><strong>para</strong> conocer las características de la aplicación y del grupo de desarrolladores</p></td>
<td>Media</td>
<td>5</td>
</tr>
<tr class="even">
<td>24</td>
<td>US24</td>
<td>Agendar notificaciones de recordatorio de viajes</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> recibir notificaciones de recordatorio antes del inicio de mi viaje,</p>
<p><strong>para</strong> asegurarme de estar listo a tiempo</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>25</td>
<td>US25</td>
<td>Filtrar viajes por tipos de vehículos</td>
<td><p><strong>Como</strong> pasajero,</p>
<p><strong>quiero</strong> poder filtrar los viajes según el tipo de vehículo,</p>
<p><strong>para</strong> seleccionar el que más se ajuste a mis necesidades</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>26</td>
<td>US26</td>
<td>Establecer destinos secundarios</td>
<td><p><strong>Como</strong> conductor,</p>
<p><strong>quiero</strong> poder establecer destinos secundarios durante mi ruta,</p>
<p><strong>para</strong> recoger a más estudiantes en puntos intermedios</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="odd">
<td>27</td>
<td>US27</td>
<td>Opciones de seguridad adicionales para conductores</td>
<td><p><strong>Como</strong> conductor,</p>
<p><strong>quiero</strong> poder acceder a opciones adicionales de seguridad, como compartir mi ubicación en tiempo real,</p>
<p><strong>para</strong> garantizar un viaje seguro</p></td>
<td>Alta</td>
<td>5</td>
</tr>
<tr class="even">
<td>28</td>
<td>US28</td>
<td>Identificación de usuarios frecuentes</td>
<td><p><strong>Como</strong> pasajero frecuente,</p>
<p><strong>quiero</strong> poder marcar ciertos conductores como favoritos,</p>
<p><strong>para</strong> facilitar la reserva de futuros viajes con ellos</p></td>
<td>Media</td>
<td>3</td>
</tr>
<tr class="odd">
<td>29</td>
<td>US29</td>
<td>Programar viajes recurrentes</td>
<td><p><strong>Como</strong> usuario,</p>
<p><strong>quiero</strong> poder programar viajes recurrentes,</p>
<p><strong>para</strong> no tener que hacer reservas diarias cada vez que necesite transporte</p></td>
<td>Alta</td>
<td>8</td>
</tr>
</tbody>
</table>

---

# [**Capítulo IV: Product Design.**](#capítulo-iv-product-design)

En este capítulo describimos las directrices de diseño y estilo para el producto, asegurando una experiencia visual coherente y atractiva para el usuario.

## [**4.1. Style Guidelines.**](#style-guidelines)
En esta sección se describen las pautas generales de estilo que guían la apariencia visual del producto, incluyendo el uso de colores, tipografía y espaciado.

### [**4.1.1. General Style Guidelines.**](#general-style-guidelines)
Las directrices generales aseguran una estética que refuerza la marca y proporciona claridad visual para los usuarios.

#### Historia de la marca
La marca busca transmitir modernidad y profesionalismo, reflejando estos valores en cada elemento visual del diseño.

#### Misión
Proporcionar a los usuarios una experiencia fluida y atractiva, con interfaces claras y consistentes.

#### Visión
Ser reconocidos como una marca que combina funcionalidad y estilo en el diseño de productos digitales.

#### Brand Name
El nombre de la marca es un elemento clave de nuestra identidad, representando los valores fundamentales de la empresa.

#### Colores
La paleta de colores está diseñada para proporcionar un equilibrio visual. Utilizamos una combinación de tonos brillantes y neutros para transmitir profesionalismo y modernidad.

![Paleta de Colores](assets/images/styleGuidelines/colors.png)

#### Tipografía
Usamos la tipografía **Roboto** en diferentes pesos para establecer jerarquía visual y garantizar una legibilidad óptima. El color de la letra principal es `#404040`.

![Guía de Tipografía](assets/images/styleGuidelines/guidelines.png)

#### Espaciado
El espaciado entre elementos visuales asegura una estructura clara y organizada, ayudando a los usuarios a navegar por el contenido de forma fluida.

- **Tamaño de letra**: Las fuentes varían desde 12px hasta 98px según la jerarquía del texto.
- **Interlineado**: Mantenemos un interlineado proporcional para mejorar la legibilidad.

### [**4.1.2. Web Style Guidelines.**](#web-style-guidelines)

Las pautas de estilo para la web están diseñadas para asegurar que el diseño sea funcional y atractivo tanto en dispositivos móviles como en pantallas grandes. Incluir consistencia en colores, tipografías y espaciado es clave para mantener la identidad visual en todas las plataformas.

## [**4.2. Information Architecture.**](#information-architecture)

En esta sección, se describe cómo se organizará el contenido en la plataforma **GoUni**, tanto en la web como en las aplicaciones móviles. Se busca que la estructura sea intuitiva para los estudiantes universitarios, permitiendo una navegación fluida y el acceso rápido a las principales funcionalidades de la plataforma.

<hr>

### [**4.2.1. Organization Systems.**](#organization-systems)

El Sistema de Organización de **GoUni** está diseñado para facilitar la interacción entre el usuario y la plataforma, asegurando que los estudiantes puedan encontrar y utilizar los servicios clave, como la búsqueda de viajes o la oferta de plazas en vehículos.

- **Jerarquía Visual**: La página principal destacará las acciones más importantes para el usuario, como “Buscar viaje” y “Publicar viaje”, con énfasis en botones de llamada a la acción que lleven a estas secciones.
- **Organización Secuencial**: Se aplicará a procesos clave como el registro de usuario, reserva de un viaje y configuración de perfil. Estos procesos se guiarán paso a paso, asegurando que los usuarios completen cada tarea sin problemas.
- **Organización Matricial**: Los filtros de búsqueda permitirán a los usuarios seleccionar viajes según el tipo de vehículo, horario y calificaciones del conductor, haciendo que sea más fácil encontrar un viaje que se ajuste a sus necesidades.
- **Esquemas de Categorización**: La categorización de la información podrá hacerse por orden alfabético (al buscar conductores por nombre), cronológico (al organizar las reservas según la fecha), o por audiencia (al segmentar entre conductores y pasajeros).

<br>

### [**4.2.2. Labeling Systems.**](#labeling-systems)

En **GoUni**, las etiquetas se diseñarán para ser claras, directas y comprensibles para los estudiantes, priorizando una navegación simple y una experiencia de usuario intuitiva.

### Etiquetas:
- **Inicio**: Al hacer clic en el logo de GoUni, los usuarios serán redirigidos a la página principal.
- **Buscar Viaje**: Opción en el menú principal que permite a los estudiantes buscar viajes disponibles en su universidad.
- **Publicar Viaje**: Los usuarios con vehículo propio podrán acceder a esta opción para publicar su ruta y disponibilidad de asientos.
- **Reservas Actuales**: Sección donde los usuarios pueden ver y gestionar sus reservas actuales.
- **Perfil**: Permite a los usuarios gestionar sus datos personales, verificar su identidad y ver su historial de viajes.

Una vez que los usuarios se registren y accedan a su cuenta, aparecerán nuevas etiquetas como:
- **Mis Viajes**: Un lugar donde los usuarios pueden revisar sus reservas activas y pasadas.
- **Calificar Conductores**: Opción que aparece tras la finalización de un viaje, permitiendo dejar comentarios y puntuaciones.

<br>

### [**4.2.3. SEO Tags and Meta Tags.**](#seo-tags-and-meta-tags)

Los SEO Tags y Meta Tags son esenciales para mejorar la visibilidad de **GoUni** en los motores de búsqueda.

### Para la Landing Page:
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GoUni - Carpooling para Estudiantes Universitarios</title>
<meta name="description" content="GoUni es la plataforma de carpooling exclusiva para estudiantes universitarios, enfocada en la seguridad, sostenibilidad y economía colaborativa.">
<meta name="keywords" content="carpooling universitario, compartir autos estudiantes, movilidad sostenible, transporte colaborativo">
<meta name="author" content="GoUni Team">
```
### Para la Aplicación Web:
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GoUni - Comparte tu auto con otros estudiantes universitarios</title>
<meta name="description" content="Con GoUni, puedes compartir tu auto con otros estudiantes universitarios y reducir tus gastos de transporte mientras ayudas al medio ambiente.">
<meta name="keywords" content="carpooling estudiantes, compartir auto universidad, transporte sostenible, viaje colaborativo">
<meta name="author" content="GoUni Team">
```

<br>

### [**4.2.4. Searching Systems.**](#searching-systems)

El sistema de búsqueda en GoUni facilitará a los usuarios encontrar viajes disponibles de forma rápida y efectiva. La funcionalidad de búsqueda incluirá:

Búsqueda por Universidad: Los estudiantes podrán buscar viajes que conecten con su universidad específica.
Filtros de Búsqueda: Los usuarios podrán filtrar los resultados por tipo de vehículo, horario de salida, calificación del conductor y disponibilidad de plazas.
Organización de Resultados: Los resultados se podrán ordenar de manera alfabética, por hora de salida o por la proximidad del conductor al punto de recogida.

![Searching.png](assets/images/styleGuidelines/search.png)

<br>

### [**4.2.5. Navigation Systems.**](#navigation-systems)

El sistema de navegación de GoUni estará diseñado para que los usuarios puedan encontrar la información y realizar las acciones deseadas con el mínimo esfuerzo.

Navegación Principal: El menú superior incluirá accesos rápidos a las funciones clave: "Buscar Viaje", "Publicar Viaje", "Reservas Actuales" y "Perfil".
Navegación Móvil: En la versión móvil, el menú será desplegable para ahorrar espacio y mostrar solo las opciones más importantes de manera compacta. Los usuarios podrán regresar a la página de inicio pulsando el logo de GoUni.
Navegación Secundaria: En secciones como el perfil, habrá opciones adicionales para gestionar la cuenta, verificar la identidad o ajustar preferencias de notificaciones.

![Navigation.png](assets/images/styleGuidelines/navigation.png)

<br>

---

## [**4.3. Landing Page UI Design**](#landing-page-ui-design)

<hr>
<td align="center">
En esta sección, presentamos el diseño de la interfaz de usuario
de la landing page para GoUni. El diseño se ha desarrollado teniendo
en cuenta la experiencia del usuario y la accesibilidad tanto en
versiones de escritorio como móviles. El objetivo principal es
proporcionar una navegación clara y atractiva. </td>

### [**4.3.1. Landing Page Wireframe.**](#landing-page-wireframe)

<td align="center">
A continuación, mostramos los wireframes de la landing page, 
los cuales representan la estructura básica y el layout sin 
elementos gráficos detallados. Estos sirven como una guía inicial
para el diseño visual, asegurando que todos los elementos
necesarios estén presentes y correctamente organizados.
</td>

Enlace a los wireframes de la Landing Page en Figma:

[Landing Page Wireframes Link](https://www.figma.com/design/8HLFLOPVBAOUkQcOi54BjZ/GoUni-TSP?node-id=0-1&p=f&t=03GYsMHZup0zyO9S-0)

#### Wireframe de la Landing Page en Figma:

#### Versión Desktop:

##### Wireframe de la página principal:

Wireframe de la sección Header:

![Header_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Header_Wireframes_Desktop.png)

Wireframe de la sección Hero:

![HeroSection_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/HeroSection_Wireframes_Desktop.png)

Wireframe de la sección How It Works:

![HowItWorks_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/HowItWorks_Wireframes_Desktop.png)

Wireframe de la sección Benefits of GoUni:

![BenefitsofGoUni_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/BenefitsofGoUni_Wireframes_Desktop.png)

Wireframe de la sección Security:

![Security_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Security_Wireframes_Desktop.png)

Wireframe de la sección Plans:

![Plans_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Plans_Wireframes_Desktop.png)

Wireframe de la sección Our Apps and Portals:

![OurAppsandPortals_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/OurAppsandPortals_Wireframes_Desktop.png)

Wireframe de la sección Contact Us:

![ContactUs_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/ContactUs_Wireframes_Desktop.png)

Wireframe de la sección Footer:

![Footer_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/home/Footer_Wireframes_Desktop.png)

##### Wireframe de la sección Sobre Nosotros:

Wireframe de la sección Header:

![headerAboutUs_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/headerAboutUs_Wireframes_Desktop.png)

Wireframe de la sección Who We Are:

![whoWeAre_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/whoWeAre_Wireframes_Desktop.png)

Wireframe de la sección Our Sponsor:

![ourSponsors_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/ourSponsors_Wireframes_Desktop.png)

Wireframe de la sección whyGoUni?:

![whyGoUni?_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/whyGoUni_Wireframes_Desktop.png)

Wireframe de la sección Our Team:

![ourTeam_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/ourTeam_Wireframes_Desktop.png)

Wireframe de la sección Footer:

![footerAboutUs_Wireframes_Desktop.png](assets/images/landingPage/wireframes/desktop/aboutUs/footerAboutUs_Wireframes_Desktop.png)

##### Versión Mobile:

##### Wireframe de la página principal:

Wireframe de la sección Header:

![homeHome_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/homeHome_Wireframe_Mobiles.png)

Wireframe de la sección How It Works:

![howItWorks_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/howItWorks_Wireframe_Mobiles.png)

Wireframe de la sección Benefits of GoUni:

![benefitsOfGoUni_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/benefitsOfGoUni_Wireframe_Mobiles.png)

Wireframe de la sección Security:

![security_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/security_Wireframe_Mobiles.png)

Wireframe de la sección Plans:

![plans_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/plans_Wireframe_Mobiles.png)

Wireframe de la sección Our Apps and Portals:

![ourAppsAndPortals_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/ourAppsAndPortals_Wireframe_Mobiles.png)

Wireframe de la sección Contact Us:

![contactUs_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/contactUs_Wireframe_Mobiles.png)

Wireframe de la sección Footer:

![footerHome_Wireframe_Mobiles.png](assets/images/landingPage/wireframes/mobiles/home/footerHome_Wireframe_Mobiles.png)

##### Wireframe de la sección Sobre Nosotros:

Wireframe de la sección Header:

![headerAboutUs_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/headerAboutUs_Wireframes_Mobiles.png)

Wireframe de la sección Why GoUni?:

![whyGoUni_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/whyGoUni_Wireframes_Mobiles.png)

Wireframe de la sección Our Sponsors:

![ourSponsors_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/ourSponsors_Wireframes_Mobiles.png)

Wireframe de la sección Our Team:

![ourTeam_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/ourTeam_Wireframes_Mobiles.png)

Wireframe de la sección Footer:

![footerAboutUs_Wireframes_Mobiles.png](assets/images/landingPage/wireframes/mobiles/aboutUs/footerAboutUs_Wireframes_Mobiles.png)



### [**4.3.2. Landing Page Mock-up.**](#landing-page-mock-up)

<td align="center">
Esta sección presenta los mockups de la landing page,
que ilustran el diseño final con detalles gráficos, tipografía,
y color. Los mockups son fundamentales para visualizar cómo se
verá la página final y para realizar ajustes antes del desarrollo.
</td>

Enlace a la mockup de la Landing Page en Figma:

#### Mockups de la Landing Page en Figma:

##### Versión Desktop:

#### Mockups de la página principal

Mockup de la sección Header:

![homeHome_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/homeHome_Mockup_Desktop.png)

Mockup de la sección Hero:

![heroHowItWorks_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/heroHowItWorks_Mockup_Desktop.png)

Mockup de la sección How It Works:

![howItWorks_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/howItWorks_Mockup_Desktop.png)

Mockup de la sección Benefits of GoUni:

![benefitsOfGoUni_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/benefitsOfGoUni_Mockup_Desktop.png)

Mockup de la sección Security:

![security_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/security_Mockup_Desktop.png)

Mockup de la sección Plans:

![plans_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/plans_Mockup_Desktop.png)

Mockup de la sección Our Apps and Portals:

![ourAppsAndPortals_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/ourAppsAndPortals_Mockup_Desktop.png)

Mockup de la sección Contact Us:

![contactUs_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/contactUs_Mockup_Desktop.png)

Mockup de la sección Footer:

![footerHome_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/home/footerHome_Mockup_Desktop.png)

#### Mockups de la sesion Sobre Nosotros:

Mockup de la sección Header:

![headerAboutUs_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/headerAboutUs_Mockup_Desktop.png)

Mockup de la sección Who We Are:

![whoWeAre_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/whoWeAre_Mockup_Desktop.png)

Mockup de la sección Why GoUni?:

![whyGoUni_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/whyGoUni_Mockup_Desktop.png)

Mockup de la sección Our Sponsors:

![ourSponsors_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/ourSponsors_Mockup_Desktop.png)

Mockup de la sección Footer:

![footerAboutUs_Mockup_Desktop.png](assets/images/landingPage/mockups/desktop/aboutUs/footerAboutUs_Mockup_Desktop.png)

##### Versión Mobile:

#### Mockups de la página principal

Mockup de la sección Header:

![homeHome_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/homeHome_Mockup_Mobile.png)

Mockup de la sección How It Works:

![howItWorks_Mockuo_Mobile.png](assets/images/landingPage/mockups/mobile/home/howItWorks_Mockup_Mobile.png)

Mockup de la sección Benefits of GoUni:

![benefitsOfGoUni_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/benefitsOfGoUni_Mockup_Mobile.png)

Mockup de la sección Security:

![security_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/security_Mockup_Mobile.png)

Mockup de la sección Plans:

![plans_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/plans_Mockup_Mobile.png)

Mockup de la sección Our Apps and Portals:

![ourAppsAndPortals_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/ourAppsAndPortals_Mockup_Mobile.png)

Mockup de la sección Contact Us:

![contactUs_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/contactUs_Mockup_Mobile.png)

Mockup de la sección Footer:
![footerHome_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/home/footerHome_Mockup_Mobile.png)


##### Mockups de la sesion Sobre Nosotros:

Mockup de la sección Header:

![headerAboutUs_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/headerAboutUs_Mockup_Mobile.png)

Mockup de la sección Why GoUni?:

![whyGoUni_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/whyGoUni_Mockup_Mobile.png)

Mockup de la sección Our Sponsors:

![ourSponsors_Mockup_Mobile.png](assets/images/landingPage/mockups/mobile/aboutUs/ourSponsors_Mockup_Mobile.png)


Mockup de la sección Footer:

![footerAboutUs_Mockup_Mobiles.png](assets/images/landingPage/mockups/mobile/aboutUs/footerAboutUs_Mockup_Mobiles.png)


## [**4.4. Web Applications UX/UI Design.**](#web-applications-uxui-design)

En esta sección, presentamos el diseño de la interfaz de usuario de las aplicaciones web de GoUni, que incluyen el inicio de sesión, la creación de cuenta, la búsqueda de viajes, la reserva de asientos y la calificación de conductores. El diseño se ha desarrollado teniendo en cuenta la experiencia del usuario y la accesibilidad en diferentes dispositivos.

### [**4.4.1. Web Applications Wireframes.**](#web-applications-wireframes)

Enlace a los wireframes de las aplicaciones web en Figma:

[Link Web Applications Wireframes](https://www.figma.com/design/sDl1xClQAtYSkXhEGEgjb7/Landing-Page-GoUni---TSP?node-id=0-1&p=f&t=zJdMUNIpjRHzxDl7-0)

#### Wireframes de las Aplicaciones Web en Figma:

Wireframe de la página de inicio de sesión:

![Iniciar de sesion.png](assets/images/webApplicationsWireframe/Iniciar%20de%20sesion.png)

Wireframe de la página de creación de cuenta:

![creacionDeCuenta.png](assets/images/webApplicationsWireframe/creacionDeCuenta.png)

Wireframe de la página de creación de cuenta elija una opcion:

![elijaOpcionEC.png](assets/images/webApplicationsWireframe/elijaOpcionEC.png)

Wireframe de la página de creación de cuenta conductor:

![confirmacionConductor.png](assets/images/webApplicationsWireframe/confirmacionConductor.png)

Wireframe de la página de creación de cuenta estudiante:

![creacionEstudiante.png](assets/images/webApplicationsWireframe/creacionEstudiante.png)

Wireframe de la página de inicio:

![inicio.png](assets/images/webApplicationsWireframe/inicio.png)

Wireframe de la página de servicios:

![servicio.png](assets/images/webApplicationsWireframe/servicio.png)

Wireframe de la página de planes de suscripcion:

![planesSubs.png](assets/images/webApplicationsWireframe/planesSubs.png)

Wireframe de la página de pagos:

![pagos.png](assets/images/webApplicationsWireframe/pagos.png)

Wireframe de maps:

![maps.png](assets/images/webApplicationsWireframe/maps.png)

Wireframe de la página de reservas:

![reserva.png](assets/images/webApplicationsWireframe/reserva.png)

Wireframe de la página de reserva descripcion:

![reservaDescripcion.png](assets/images/webApplicationsWireframe/reservaDescripcion.png)

Wireframe de la página de confirmacion:

![confirmacion.png](assets/images/webApplicationsWireframe/confirmacion.png)

Wireframe de la página de tus reservas:

![tuReserva.png](assets/images/webApplicationsWireframe/tuReserva.png)

Wireframe de la página de chat:

![chat.png](assets/images/webApplicationsWireframe/chat.png)

Wireframe de la página de calificacion:

![puntaje.png](assets/images/webApplicationsWireframe/puntaje.png)



### [**4.4.2. Web Applications Wireflow Diagrams.**](#web-applications-wireflow-diagrams)

Los Wireflow Diagrams son diagramas que representan la secuencia de pasos que un usuario sigue al interactuar con la aplicación web. Estos diagramas muestran cómo los usuarios navegan por la plataforma, desde el inicio de sesión hasta la reserva de un viaje.

#### Wireflow Diagrams de las Aplicaciones Web en LucidChart Iniciar Sesion:

![iniciarSesion.png](assets/images/userFlowDiagramsMockup/iniciarSesion.png)

Wireflow Diagrams de las Aplicaciones Web en LucidChart Plan:

![plan.png](assets/images/userFlowDiagramsMockup/plan.png)

Wireflow Diagrams de las Aplicaciones Web en LucidChart Reservar Viaje:

![reservarViaje.png](assets/images/userFlowDiagramsMockup/reservarViaje.png)


### [**4.4.3. Web Applications Mock-ups.**](#web-applications-mock-ups)

En esta sección, presentamos los mockups de la aplicación web de GoUni, que ilustran el diseño final con detalles gráficos, tipografía y color. Los mockups son fundamentales para visualizar cómo se verá la aplicación final y para realizar ajustes antes del desarrollo.

Enlace a la mockup de la App Web en Figma:
[Link Web Applications Mockups](https://www.figma.com/design/sDl1xClQAtYSkXhEGEgjb7/Landing-Page-GoUni---TSP?node-id=0-1&p=f&t=zJdMUNIpjRHzxDl7-0)


Inicio de sesión:

![iniciarSesion_WebApplications.png](assets/images/webApplication/mockups/iniciarSesion_WebApplications.png)

Creación de cuenta:

![crearCuenta_WebApplication.png](assets/images/webApplication/mockups/crearCuenta_WebApplication.png)

Elegir entre ser conductor o pasajero:

![opcionEorC_WebApplications.png](assets/images/webApplication/mockups/opcionEorC_WebApplications.png)

Registro de estudiante:

![registroEstudiante_WebApplications.png](assets/images/webApplication/mockups/registroEstudiante_WebApplications.png)

Registro de conductor:

![registroConductor_WebApplications.png](assets/images/webApplication/mockups/registroConductor_WebApplications.png)

Inicio de la Web Applications:

![inicio_WebApplications.png](assets/images/webApplication/mockups/inicio_WebApplications.png)

Servicios de la Web Applications:

![servicio_WebApplications.png](assets/images/webApplication/mockups/servicio_WebApplications.png)


Planes de la Web Applications:
![planes_WebApplications.png](assets/images/webApplication/mockups/planes_WebApplications.png)

Pagos del plan de la Web Applications:

![pagos_WebApplications.png](assets/images/webApplication/mockups/pagos_WebApplications.png)

Mapa de la Web Applications:

![mapa_WebApplications.png](assets/images/webApplication/mockups/mapa_WebApplications.png)

Reservas de la Web Applications:

![reserva_WebApplications.png](assets/images/webApplication/mockups/reserva_WebApplications.png)

Reserva descripción de la Web Applications:

![reservaDescripcion_WebApplications.png](assets/images/webApplication/mockups/reservaDescripcion_WebApplications.png)

Confirmación de reserva de la Web Applications:

![confirmacionReserva_WebApplications.png](assets/images/webApplication/mockups/confirmacionReserva_WebApplications.png)

Tus reservas de la Web Applications:

![tusReservas_WebApplications.png](assets/images/webApplication/mockups/tusReservas_WebApplications.png)

Chat de la Web Applications:

![chat_WebApplications.png](assets/images/webApplication/mockups/chat_WebApplications.png)

Calificación de la Web Applications:

![puntaje_WebApplications.png](assets/images/webApplication/mockups/puntaje_WebApplications.png)


### [**4.4.4. Web Applications User Flow Diagrams.**](#web-applications-user-flow-diagrams)

Los User Flow Diagrams son diagramas que representan la secuencia de pasos que un usuario sigue al interactuar con la aplicación web. Estos diagramas muestran cómo los usuarios navegan por la plataforma, desde el inicio de sesión hasta la reserva de un viaje.

Inicio de sesión y creación de cuenta:

![iniciarSesion.png](assets/images/webApplication/userFlowDiagrams/iniciarSesion.png)

Plan de pago:

![plan.png](assets/images/webApplication/userFlowDiagrams/plan.png)

Realizar reserva:

![reservarViaje.png](assets/images/webApplication/userFlowDiagrams/reservarViaje.png)


## [**4.5. Web Applications Prototyping.**](#web-applications-prototyping)

<hr>
En esta sección, presentamos los prototipos interactivos de las aplicaciones web de GoUni. Los prototipos permiten a los usuarios navegar por las diferentes pantallas y funcionalidades, simulando la experiencia de uso de la aplicación antes de su desarrollo.

![WebApplicationsPrototyping.png](assets/images/webApplication/WebApplicationProtoyping/WebApplicationsPrototyping.png)

Además, se adjunta el enlace al video completo de la presentación del prototipo:

[Link Video Applications Prototyping](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218664_upc_edu_pe/EWGbMcHowddPkLKM-izeDnkBu8xRzmdoXugfgBBKk-ylHA?e=t1N4fR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Link Web Applications Prototyping:

[Link Web Applications Prototyping](https://www.figma.com/proto/EwjGSJ6rrm0CnMdTbftA6k/Web-Application-Wireframe---Mock-Up?page-id=0%3A1&node-id=15-495&starting-point-node-id=15%3A482)



## [**4.6. Domain-Driven Software Architecture**](#domain-driven-software-architecture)

### [**4.6.1. Software Architecture Context Diagram.**](#software-architecture-context-diagram)

![Diagrama de clase](assets/images/databaseDesign/diagramcontext.png)

### [**4.6.2. Software Architecture Container Diagrams.**](#software-architecture-container-diagrams)

![Diagrama de clase](assets/images/databaseDesign/diagramcontainer.png)

### [**4.6.3. Software Architecture Components Diagrams.**](#software-architecture-components-diagrams)

![Diagrama de clase](assets/images/databaseDesign/diagramcomponent.png)

## [**4.7. Software Object-Oriented Design.**](#software-object-oriented-design)

### [**4.7.1. Class Diagrams.**](#class-diagrams)

![Diagrama de clase](assets/images/databaseDesign/Diagrama_clase.png)

### [**4.7.2. Class Dictionary.**](#class-dictionary)

---

### **Usuario**
La clase Usuario representa a un usuario dentro de la plataforma, ya sea un conductor o pasajero.

#### **Atributos:**

| Atributo       | Descripción                                                              |
| -------------- | ------------------------------------------------------------------------ |
| `nombre: String`      | Almacena el nombre del usuario.                                            |
| `email: String`       | Almacena la dirección de correo electrónico del usuario.                   |
| `contraseña: String`  | Almacena la contraseña del usuario.                                        |
| `rol: Rol`            | Define el rol del usuario en la plataforma (conductor o pasajero).         |
| `verificado: Boolean` | Indica si el usuario ha verificado su identidad.                           |

#### **Métodos:**

| Método                   | Descripción                                                                        |
| ------------------------ | ---------------------------------------------------------------------------------- |
| `registrarse(): void`    | Método para registrar a un nuevo usuario en la plataforma.                        |
| `iniciarSesion(): void`  | Método para que el usuario inicie sesión en la plataforma.                        |
| `verificarIdentidad(): void` | Verifica la identidad del usuario a través de documentos o información adicional. |

---

### **Evaluación**
La clase Evaluación permite a los usuarios calificar y dejar comentarios sobre sus experiencias de viaje.

#### **Atributos:**

| Atributo       | Descripción                                              |
| -------------- | -------------------------------------------------------- |
| `calificación: int` | Almacena la calificación numérica del viaje (por ejemplo, de 1 a 5). |
| `comentario: String` | Almacena los comentarios opcionales sobre el viaje. |
| `evaluador: Usuario` | Almacena la información del usuario que realiza la evaluación. |
| `viaje: Viaje`       | Almacena la información del viaje evaluado.         |

#### **Métodos:**

| Método                 | Descripción                                              |
| ---------------------- | -------------------------------------------------------- |
| `calificar(): void`    | Permite al usuario dejar una calificación sobre el viaje.|
| `dejarComentario(): void` | Permite al usuario dejar un comentario opcional sobre el viaje.|

---

### **Pasajero**
La clase Pasajero es una extensión de Usuario y representa a los usuarios que buscan y reservan viajes.

#### **Métodos:**

| Método                   | Descripción                                                   |
| ------------------------ | ------------------------------------------------------------- |
| `buscarViaje(): void`    | Permite al pasajero buscar viajes disponibles en la plataforma.|
| `reservarViaje(): void`  | Permite al pasajero reservar un asiento en un vehículo disponible.|

---

### **Vehículo**
La clase Vehículo representa a los vehículos registrados por los conductores para ofrecer sus viajes.

#### **Atributos:**

| Atributo       | Descripción                                              |
| -------------- | -------------------------------------------------------- |
| `tipo: String`        | Almacena el tipo de vehículo (sedán, SUV, camioneta, etc.). |
| `matrícula: String`   | Almacena la matrícula del vehículo.                       |
| `capacidad: int`      | Almacena la capacidad de pasajeros del vehículo.           |

#### **Métodos:**

| Método                           | Descripción                                               |
| -------------------------------- | --------------------------------------------------------- |
| `registrarVehiculo(): void`      | Permite al conductor registrar su vehículo en la plataforma. |
| `actualizarDetallesVehiculo(): void` | Permite actualizar la información del vehículo.             |

---

### **Viaje**
La clase Viaje representa un viaje específico que un conductor ofrece a los pasajeros.

#### **Atributos:**

| Atributo       | Descripción                                              |
| -------------- | -------------------------------------------------------- |
| `origen: String`    | Almacena el lugar de origen del viaje.                       |
| `destino: String`   | Almacena el destino del viaje.                                |
| `horario: Date`     | Almacena la hora de salida del viaje.                         |
| `conductor: Conductor` | Almacena la información del conductor que ofrece el viaje. |
| `estado: String`    | Almacena el estado del viaje (disponible, completado, cancelado).|

#### **Métodos:**

| Método                       | Descripción                                               |
| ---------------------------- | --------------------------------------------------------- |
| `publicarViaje(): void`      | Permite al conductor publicar un viaje en la plataforma. |
| `reservarAsiento(): void`    | Permite reservar un asiento en el vehículo para un pasajero. |
| `actualizarEstado(): void`   | Actualiza el estado del viaje (por ejemplo, lleno, en curso).|

---

### **Reserva**
La clase Reserva representa la acción de un pasajero que reserva un asiento en un viaje.

#### **Atributos:**

| Atributo           | Descripción                                              |
| ------------------ | -------------------------------------------------------- |
| `pasajero: Pasajero` | Almacena la información del pasajero que realizó la reserva.|
| `viaje: Viaje`       | Almacena la información del viaje reservado.             |
| `asientoReservado: String` | Almacena el asiento reservado en el vehículo.         |
| `estado: String`    | Almacena el estado de la reserva (confirmada, cancelada). |

#### **Métodos:**

| Método                         | Descripción                                                   |
| ------------------------------ | ------------------------------------------------------------- |
| `confirmarReserva(): void`     | Confirma la reserva realizada por el pasajero.                |
| `cancelarReserva(): void`      | Permite cancelar una reserva antes del inicio del viaje.      |

---

### **Pago**
La clase Pago representa la transacción realizada por un pasajero al reservar un viaje.

#### **Atributos:**

| Atributo           | Descripción                                              |
| ------------------ | -------------------------------------------------------- |
| `monto: float`       | Almacena el monto del pago por el viaje.                 |
| `metodoDePago: String` | Almacena el método de pago utilizado (tarjeta, billetera digital, etc.). |
| `estado: String`    | Almacena el estado del pago (completado, pendiente).     |

#### **Métodos:**

| Método                         | Descripción                                                   |
| ------------------------------ | ------------------------------------------------------------- |
| `realizarPago(): void`         | Realiza el pago del viaje reservado.                         |
| `confirmarPago(): void`        | Confirma que el pago ha sido realizado con éxito.            |

---

### **Notificación**
La clase Notificación gestiona el envío de mensajes a los usuarios en relación con sus viajes y reservas.

#### **Atributos:**

| Atributo           | Descripción                                              |
| ------------------ | -------------------------------------------------------- |
| `mensaje: String`   | Almacena el contenido de la notificación.                 |
| `tipo: String`      | Almacena el tipo de notificación (recordatorio, cambio de ruta, etc.).|
| `tiempo: Date`      | Almacena la fecha y hora de envío de la notificación.     |

#### **Métodos:**

| Método                       | Descripción                                                   |
| ---------------------------- | ------------------------------------------------------------- |
| `enviarNotificacion(): void` | Envía la notificación al usuario correspondiente.            |

---

## [**4.8. Database Design.**](#database-design)

![Diagrama de clase](assets/images/databaseDesign/Diagrama_clase.png)

### [**4.8.1. Database Diagram.**](#database-diagram)

A continuación se detalla el modelo físico realizado para esta entrega, donde se consideró los requerimientos necesarios para el negocio.

![Diagrama de la Base de Datos](assets/images/databaseDesign/databasediagram.png)

---

# [**Conclusiones.**](#conclusiones)

## [**Conclusiones y Recomendaciones.**](#conclusiones-y-recomendaciones)

#### 1. GoUni responde a las necesidades de movilidad estudiantil
La startup aborda la problemática de transporte en zonas urbanas como Lima, donde el transporte público es ineficiente y el uso de vehículos privados es costoso, proporcionando una plataforma de carpooling accesible y económica.

#### 2. Contribución a la sostenibilidad
GoUni fomenta el uso compartido de vehículos, lo que ayuda a reducir la congestión vehicular, disminuye las emisiones de CO2 y promueve un uso más eficiente de los recursos entre los estudiantes universitarios.

#### 3. Enfoque colaborativo y seguro
La plataforma no solo facilita el ahorro económico a través de viajes compartidos, sino que también implementa medidas de seguridad como la verificación de identidad y las calificaciones de usuarios para garantizar un entorno confiable.

#### 4. Impacto social y económico
GoUni no solo mejora la movilidad diaria de los estudiantes, sino que también permite a aquellos con vehículo propio generar ingresos adicionales, ofreciendo una solución que beneficia tanto a pasajeros como a conductores.

#### 5. Innovación y tecnología como pilares
La plataforma utiliza tecnología móvil avanzada y un enfoque innovador para crear una experiencia de movilidad eficiente y socialmente responsable, adaptada a las necesidades de los estudiantes en un contexto de creciente demanda por soluciones digitales.


---

# [**Bibliografia.**](#bibliografia)

1. NEI. (2021). *Encuesta Nacional de Hogares: Módulo de Victimización*. Lima, Perú: INEI.
2. Traverso, J. L. (2020). *Impacto del crimen en la calidad de vida de los habitantes de Lima Metropolitana*. *Revista Peruana de Criminología*, 3(1), 45-58.
3. Municipalidad Metropolitana de Lima. (2023). *Informe anual sobre el estado del transporte público en Lima*. Lima, Perú: Autor.
4. Flores Martos, C. Y., & Gonzales Otiniano, J. E. (2018). Efecto de la implementación del aplicativo Carpooling, bajo la norma ISO 9126, en la economía de estudiantes universitarios de Cajamarca.
5. Amaro Meza, R. D. (2019). Aplicación carpooling para el transporte de personas que trabajan en el Centro Empresarial de San Isidro.
6. Flores Martos, C. Y., & Gonzales Otiniano, J. E. (2018). Efecto de la implementación del aplicativo Carpooling, bajo la norma ISO 9126, en la economía de estudiantes universitarios de Cajamarca.
7. Valdez Fabian, I. K. (2023). Gestión de comunicación del proyecto de responsabilidad social Facilito de Osinergmin en Lima Metropolitana.
8. Jáuregui Mena, G. M. ¿La culpa es solo del conductor?: Un análisis de la responsabilidad de las plataformas digitales frente al consumidor de taxi por aplicativo en el Perú.
9. Hofer, S., & Schwentner, H. (2021). *Domain Storytelling: A Collaborative, Visual, and Agile Way to Build Domain-Driven Software*. Addison-Wesley Professional.
10. Vural, H., & Koyuncu, M. (2021). Does domain-driven design lead to finding the optimal modularity of a microservice?. *IEEE Access*, 9, 32721-32733.
11. Tramullas Ortiz, C. (2023). *Diseño y aplicación de autómatas programables basados en open source*.
12. Casado, P. E. F. (2020). *Domine JavaScript* (4ª Edición). Ra-Ma Editorial.
13. Casado, P. E. F. (2023). *Creación de componentes en JavaScript Curso practico*. Ra-Ma Editorial.
14. Fernández, P. (2023). *Construcción y diseño de páginas web con HTML, CSS y JavaScript*. Ediciones de la U.
15. García-Holgado, A., & García-Peñalvo, F. J. (2014). *Patrón arquitectónico para la definición de ecosistemas de eLearning basados en desarrollos open source*.
16. Molina Araque, F. A., & Espitia Pineda, A. A. (2016). *Propuesta de diseño e implementación de una aplicación móvil (App) como plataforma para compartir el uso del carro particular (carpooling) entre empleados de las sucursales en Bogotá de la empresa Claro Colombia sa, para teléfonos inteligentes cuyo sistema operativo sea Android 5.1*.
17. Villena Romero, C. L. (2023). *Estudio de prefactibilidad para la instalación de una empresa de transporte compartido (carpooling) en una universidad privada de la ciudad de Lima*.
18. Miranda de La Espriella, D., & Ramón García, N. (2016). *Fuímonos-Carpooling estudio y análisis para el desarrollo de la estrategia de mercadeo: plataforma web y móvil monografía de investigación*.
19. Díaz Domínguez, G. M. (2015). *Carpooling GT, aplicación para compartir vehículo* (Doctoral dissertation, Universidad de San Carlos de Guatemala).
20. Melo Domínguez, A. I. (2018). *Mejoramiento del problema de la congestión vehicular para la comunidad universitaria UDEC hacia una solución TI para carpooling*.
21. Mendizábal, E. L. (2015). *Los nuevos sistemas de utilización compartida de vehículos de transporte ("carpooling" y "car sharing"): entre la economía colaborativa y la competencia desleal*. *Revista de derecho mercantil*, (296), 283-334.
22. Cárdenas Peralta, N. F., Navarrete Cruzate, E. A., Jiménez Valdivia, K. M., & Arias Chilet, P. M. *CampusRoad*.
23. Murillo Paredes, A. (2021). *Diseño de software aplicando el patrón Domain-Driven Design*.


# [**Anexos**](#anexos)

| Descripción                           | Link                                                                                                                                                                                                                                                                     |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Repositorio General de StudentConnect | [https://github.com/upc-pre-202502-14103-sw65-tsp](https://github.com/upc-pre-202502-14103-sw65-tsp)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Repositorio Reporte                   | [https://github.com/upc-pre-202502-14103-sw65-tsp/GoUni_documentation_report](https://github.com/upc-pre-202502-14103-sw65-tsp/GoUni_documentation_report)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Repositorio Landingpage               | [https://github.com/upc-pre-202502-14103-sw65-tsp/GoUni_LandingPage](https://github.com/upc-pre-202502-14103-sw65-tsp/GoUni_LandingPage)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Exposición TB1                        | []() 
| Link landing page                     | [https://carpool-smoky.vercel.app/home](https://carpool-smoky.vercel.app/home)                                                                                                                                                                                                                                                                                       
| Link de Entrevisas                    | []() |
