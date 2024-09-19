<div align = "center">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
  <img style="height: 200px" src=https://seeklogo.com/images/U/universidad-peruana-de-ciencias-aplicadas-upc-logo-B98C3A365C-seeklogo.com.png>
  <h2 >Carrera: de Ingeniería de Software</h2>
  <h2 >Ciclo: 2024-02</h2>
  <br>
  <h2 >Curso: Desarrollo de Aplicaciones Open Source </h2>
  <h2 >Sección: WS51</h2>
  <br>
  <h2 >Informe del TB1</h2>
  <h2 >Startup: SmartFinance</h2>
  <h2 >Producto: Finzar </h2>
  <br>
  <h2 >Integrantes:</h2>
  <ul style="list-style: none; padding: 0;">
      <li><h3>Juan Diego Astonitas Díaz</h3></li>
      <li><h3>Sebastián Omar Real Calderón</h3></li>
      <li><h3>Sebastian Pacheco Astiguetta</h3></li>
      <li><h3>Gianluca Santino Pasquale Barrenechea</h3></li>
      <li><h3>Josue Gonzalo Paiva Quispe</h3></li>
  </ul>
  <br>
  <h4>Septiembre del 2024</h4>
</div>

## Registro de Versiones del Informe

| Versión | Fecha      | Autor                 | Descripción de modificación |
|---------|------------|-----------------------|-----------------------------|
| TB1     | 08/09/2024 | Todos los integrantes | Desarrollo de la TB1        |

## Project Report Collaboration Insights
Se han realizado todas las tareas asignadas para la entrega de la TB1, las cuales se encuentran registradas en el repositorio de Github de la organización del equipo bajo el 
enlace [https://github.com/SmartFinance-OpenSource.](https://github.com/SmartFinance-OpenSource) Para elaborar el informe, cada miembro ha redactado y creado gráficos en formato Markdown según los puntos asignados, realizando commits para registrar el avance en el repositorio. 

## Contenido

- [Student Outcome](#student-outcome)

- [Capítulo I: Introducción](#cap1)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#cap2)
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
        - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)



- [Capítulo III: Requirements Specification](#cap3)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)


- [Capítulo IV: Product Design](#cap4)
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
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
        - [4.7.2. Class Dictionary](#472-class-dictionary)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)


- [Capítulo V: Product Implementation, Validation & Deployment](#cap5)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
            - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
            - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

<table>
<tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Comunica oralmente con
efectividad a diferentes rangos
de audiencia.</td>
    <td>
	Juan Astonitas<br>TB1<br>
	A lo largo del desarrollo del proyecto Bliss, he participado activamente en la toma de decisiones estratégicas y en la definición de la dirección del equipo, promoviendo la comunicación abierta y la responsabilidad compartida para garantizar un liderazgo efectivo y colectivo.<br>
	Sebastian Pacheco<br>TB1<br>
	En el desarrollo del proyecto, he participado en la realización de actividades asignadas y promoviendo la participación de otros en las actividades de compañeros, permitiendo que haya un círculo de confianza y se logre afinar el producto gracias a la recepción del punto de vista del resto.<br>
    Josue Paiva <br>TB1 <br>
    En el entregable 1 he mantenido una comunicación constante con mis compañeros, pues se buscó un aporte constante por parte de todos los integrantes, en general tuvimos buena comunicación y buena aportación a partes iguales.<br>
    Gianluca Pasquale<br>TB1<br>
	He contribuido activamente en el liderazgo compartido, facilitando la toma de decisiones y promoviendo la responsabilidad colectiva.<br>
    Sebastián Real <br>TB1 <br>
    En el desarrollo de la primera etapa del proyecto, hubo una comunicación constante entre los integrantes del equipo, lo que llevo a que la realización de las actividades designadas fuera lo más fluida posible, y logrando eliminar cualquier posibilidad de malentendidos o fallas por falta de comunicación.
    </td>
    <td> TB1<br>En el desarrollo de nuestro proyecto, cada uno ha participado en sus actividades asignadas, también dando su retroalimentación con experiencia como ingenieros. Todos han aportado de manera activa, siempre comunicando cualquier cambio que desarrollen, manteniendo una comunicación entre todos y de esa manera afinando la confianza mutua. Esto ha fortalecido el valor del trabajo en equipo, el cual es de vital importancia para proyectos colaborativos en donde todos son importantes y logran cumplir las responsabilidades propuestas eficientemente.</td>
  </tr>
  <tr>
    <td>Comunica por escrito con
efectividad a diferentes rangos
de audiencia</td>
    <td>
	Juan Astonitas<br>TB1<br>
	Durante el proyecto, he contribuido a la creación de un entorno inclusivo y colaborativo, fomentando la participación de todos los miembros del equipo. He trabajado en la definición de metas claras, la planificación de tareas detalladas, y el seguimiento del cumplimiento de los objetivos, asegurando que cada miembro se sienta valorado y comprometido con los resultados.<br>
	Sebastian Pacheco<br>TB1<br>
	Para promover la participación de otros en un trabajo colaborativo, he desarrollado las actividades asignadas y he buscado la experiencia de mis compañeros para poder mejorar el producto, así como dando ideas propias hacia las actividades de otros y asistiendo en ello.<br>
    Josue Paiva <br>TB1 <br>
    Durante las semanas de plazo he completado las tareas delegadas, asi como las que surgían inesperadamente siempre que pude, las mismas se pueden ver reflejadas en mis commits, ademas de aportar con mis compañeros siempre que se necesito.
    <br>Gianluca Pasquale<br>TB1<br>
	He fomentado un entorno inclusivo, definiendo metas claras, planificando tareas, y asegurando el cumplimiento de los objetivos del proyecto.<br>
    Sebastián Real <br>TB1<br>
    Durante las semanas de trabajo, he completado las tareas que se me encomendaron, y busqué oportunidades para aportar en el desarrollo del producto con ideas o al cumplir tareas específicas. Me comuniqué con el resto de mi grupo, y entre todos documentamos nuestros avances para garantizar un seguimiento efectivo del progreso del proyecto.
    </td>
    <td> TB1<br>En el desarrollo de nuestro proyecto, todos han participado sin falta y asistido en actividades en donde otros tenían complicaciones. Se han establecido responsabilidades y planificado entregas en donde cada uno formó parte, logrando un progreso efectivo y cumpliendo los objetivos dados. El hecho de que exista una participación activa de todos los miembros fomenta valores de trabajo en equipo, el cual es punto clave para el progreso y cumplimiento de los objetivos propuestos.  </td>
  </tr>

</table>


## Capítulo I: Introducción <a id="cap1"></a>


### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup

Somos SmartFinance, una startup creada por estudiantes de la carrera de Ingeniería de Software
de la Universidad Peruana de Ciencias Aplicadas del Perú.
Hemos desarrollado una aplicación web llamada Finzar,
diseñada para optimizar la gestión de las finanzas personales de los usuarios.

Finzar es una aplicación web diseñada para transformar la gestión de las finanzas personales
en una experiencia sencilla y efectiva. Con una interfaz intuitiva, permite a los usuarios
controlar sus ingresos y gastos, establecer metas de ahorro, gestionar deudas y recibir reportes
detallados sobre sus hábitos financieros. Finzar también ofrece recordatorios y calculadoras
financieras para facilitar la toma de decisiones informadas, convirtiéndose en un aliado esencial
para quienes buscan mejorar su bienestar económico.

**Misión:** Nuestra misión es proporcionar a las personas una solución fácil de usar para tomar el
control de sus finanzas personales.

**Visión:** En SmartFinance nos visualizamos como un referente
en la creación de soluciones financieras accesibles y prácticas para los peruanos.

#### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th colspan="2"> Juan Astonitas </th>
  </tr>
  <tr>
    <td> <img src="assets/teampics/JuanAstonitas.png" width=300px > </td>
    <td>Mi nombre es Juan Diego Astonitas Diaz, mi código de estudiante es u202110237 ,tengo 20 años, actualmente curso el 5to ciclo de la carrera de Ingeniería de Software, en la UPC en la sede San Miguel. Mis principales cualidades son el liderazgo y el dominio de Python. Haré todo lo que esté a mi alcance para respaldar al equipo en la finalización oportuna y efectiva de las tareas asignadas. </td>
  </tr>
  <tr>
    <th colspan="2"> Gianluca Santino Pasquale Barrenechea </th>
  </tr>
  <tr>
    <td> <img src="assets/teampics/GianlucaPasquale.jpg" style="width: 300px"> </td>
    <td> Me llamo Gianluca Santino Pasquale Barrenechea, con código de alumno u202112078, tengo 20 años y soy estudiante de la carrera de Ingenieria de Software. Como miembro de equipo, me centraré en el desarrollo del frontend y backend de nuestra Startup, utilizare mis habilidades en C++, C#, Python, Java y HTML para lograr esto. Mi objetivo está en tener un código limpio y eficiente. </td>
  </tr>
<tr>
    <th colspan="2"> Sebastian Pacheco Astiguetta </th>
  </tr>
  <tr>
    <td> <img src="assets/teampics/SebastianPacheco.jpg" style="width:300px"> </td>
    <td> Soy Sebastian Pacheco, tengo 21 años y soy alumno de Ingeniería de Software en la UPC. Me considero una persona trabajadora y activa, priorizando las responsabilidades ante todo, pero también destaco en trabajo en equipo, permitiendo a todos que participen. Tengo conocimiento de C++ y Python, los cuales pongo en práctica mediante proyectos personales. </td>
  </tr>
<tr>
    <th colspan="2"> Sebastián Omar Real Calderón </th>
  </tr>
  <tr>
    <td>
        <img src="assets/teampics/SebastianReal.jpg" style="width:300px">
    </td>
    <td> Soy Sebastián Real Calderón, tengo 19 años y soy estudiante de la carrera de Ingeniería de Software. Tengo conocimientos sobre lenguajes de programación como C++, C# y Java. Principalmente me dedico al desarrollo de proyectos que me permitan desarrollar mis habilidades de programación, tales como videojuegos o programas sencillos, ya que apunto a volverme desarrollador. </td>
  </tr>
<tr>
    <th colspan="2"> Intengrante 5 </th>
  </tr>
  <tr>
    <td>Foto Intengrante 5 </td>
    <td> desc </td>
  </tr>
</table>


### 1.2. Solution Profile
#### 1.2.1 Antecedentes y problemática


###### What

- ¿Cuál es el problema?

El problema es que los jóvenes adultos peruanos, especialmente estudiantes universitarios
y jóvenes profesionales, enfrentan dificultades significativas para gestionar sus
finanzas personales debido a ingresos limitados y falta de experiencia. Esto conlleva
a problemas como el sobreendeudamiento y la incapacidad para ahorrar de manera efectiva.
Finzar busca resolver estos problemas proporcionando herramientas prácticas y accesibles
para mejorar la estabilidad económica y fomentar buenos hábitos financieros desde una edad
temprana.

- ¿Cuál es la relación con la persona en cuestión?

La relación con la persona en cuestión es directa, ya que Finzar está diseñada
específicamente para ayudar a jóvenes adultos peruanos a gestionar sus
finanzas personales. La aplicación les proporciona las herramientas necesarias
para controlar sus ingresos y gastos, planificar ahorros y evitar problemas financieros,
mejorando así su estabilidad económica y hábitos financieros.

###### When

- ¿Cuándo sucede el problema?


El problema sucede durante una etapa crucial de la vida de los jóvenes adultos,
entre los 18 y 30 años, cuando están estableciendo sus carreras y asumiendo
nuevas responsabilidades financieras.

- ¿Cuándo utiliza el cliente el producto?

El cliente utiliza Finzar de manera continua para gestionar sus finanzas personales,
especialmente cuando realiza actividades financieras diarias como registrar ingresos y gastos,
planificar ahorros y controlar deudas. También recurren a la aplicación en momentos clave, como
al preparar un presupuesto mensual, al recibir recordatorios de pagos, o al analizar sus hábitos
financieros para tomar decisiones económicas informadas.

###### Where

- ¿Dónde está el cliente cuando usa el producto?

El cliente usa Finzar principalmente en su entorno diario, como en casa,
en la universidad o en el trabajo, donde gestiona sus finanzas personales y
revisa su situación económica. La aplicación web está diseñada para ser accesible
desde cualquier lugar con conexión a internet, permitiendo a los usuarios integrar
la gestión financiera en su rutina diaria, ya sea al registrar gastos, planificar
presupuestos o analizar reportes financieros.

- ¿Dónde surge el problema?

El problema surge en el entorno cotidiano de los jóvenes adultos, como en el hogar,
la universidad o el lugar de trabajo, donde enfrentan dificultades para manejar sus
finanzas personales de manera efectiva.

###### Who

- ¿Quienes se ven involucrados en el problema?

En el problema están involucrados jóvenes adultos peruanos ,
incluyendo estudiantes universitarios y jóvenes profesionales que están
empezando sus carreras.


###### Why

- ¿Cuáles son las causas del problema?

Las causas del problema incluyen la falta de educación financiera adecuada y
herramientas accesibles para jóvenes adultos que están comenzando a manejar sus finanzas.
La combinación de ingresos iniciales limitados, gastos imprevistos y la falta de experiencia
en la planificación financiera contribuye al sobreendeudamiento y la incapacidad para ahorrar.


###### How

- ¿En qué condiciones los clientes usan nuestro producto?

Los clientes usan Finzar en condiciones de acceso regular a internet
desde sus dispositivos personales, como computadoras portátiles, tablets o smartphones.
La aplicación está diseñada para ser utilizada de manera intuitiva y accesible
en cualquier momento del día.

###### How much

En un contexto donde el 32,3% de la población peruana estuvo en riesgo de caer en condición de pobreza en 2022,
según el Instituto Nacional de Estadística e Informática (2023), Finzar ofrece una solución accesible y asequible
para jóvenes adultos que buscan mejorar su estabilidad financiera. La aplicación está diseñada para ayudar a este
segmento vulnerable a gestionar mejor sus recursos y evitar dificultades económicas, ofreciendo una versión gratuita
con funcionalidades esenciales y una suscripción premium a bajo costo, adaptada a las necesidades económicas de
quienes están en riesgo financiero.


#### 1.2.2 Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
Nuestro servicio fue diseñado para ayudar a los jóvenes adultos peruanos a gestionar sus finanzas personales de manera efectiva. Hemos observado que los jovenes no manejan sus finanzas de forma adecuada, lo que está causando problemas como el sobreendeudamiento, la falta de ahorro y dificultades para alcanzar metas económicas a largo plazo. ¿Cómo podríamos abordar estos problemas para que los jóvenes adultos puedan mejorar su estabilidad financiera y lograr un mejor control de sus recursos económicos?

##### 1.2.2.2. Lean UX Assumptions
###### **Supuestos del Negocio:**
1. **Creo que mis clientes tienen la necesidad de:** Gestionar mejor sus finanzas personales para lograr estabilidad económica.
2. **Estas necesidades pueden resolverse con:** Una aplicación intuitiva que permita organizar ingresos, gastos, ahorros e inversiones.
3. **Mis clientes iniciales son (o serán):** Jóvenes adultos peruanos, entre 18 y 30 años, interesados en mejorar su salud financiera.
4. **El principal valor que un cliente quiere obtener de mi servicio es:** Control total sobre sus finanzas.  
   **También pueden obtener estos beneficios adicionales:** Ahorro de tiempo, reducción de deudas y planificación de inversiones.
5. **Adquiriré la mayoría de mis clientes a través de:** Marketing digital en redes sociales y colaboraciones con influencers.
6. **Ganaré dinero mediante:** Suscripciones mensuales
7. **Mi principal competencia en el mercado será:** Otras apps de finanzas personales y servicios bancarios tradicionales.  
   **Superaremos a la competencia debido a:** Una experiencia de usuario adaptada al contexto local peruano.
8. **El mayor riesgo de mi producto es:** Falta de adopción por parte de los usuarios.  
   **Lo resolveremos mediante:** Mejora continua del producto basada en el feedback de los usuarios.
9. **Otras suposiciones que, si se demuestran falsas, harán que nuestro negocio fracase:** Los jóvenes peruanos no están dispuestos a pagar por servicios financieros adicionales o no confían en las apps para gestionar sus finanzas.
###### **Supuestos del Cliente:**
1. **¿Quién es el cliente?** Jóvenes adultos peruanos, entre 18 y 30 años.
2. **¿Dónde encaja nuestro producto en su vida?** Como una herramienta esencial para gestionar sus finanzas diariamente.
3. **¿Qué problemas soluciona nuestro producto?** Evita el sobreendeudamiento, facilita el ahorro y mejora la planificación financiera.
4. **¿Cuándo y cómo se utiliza nuestro producto?** Diariamente para seguimiento de gastos e ingresos, y mensualmente para ajustes financieros.
5. **¿Qué características son importantes?** Presupuestos personalizados, alertas de gasto, análisis financiero y una interfaz fácil de usar.
6. **¿Cómo debería verse y comportarse nuestro producto?** Con una interfaz moderna, limpia y fácil de navegar, enfocada en la simplicidad y eficiencia.
##### 1.2.2.3. Lean UX Hypothesis Statements
###### **Hipótesis 1:**
**Creemos que** incorporar una función de alertas personalizadas para gastos excesivos ayudará a los jóvenes adultos peruanos a evitar sobreendeudamiento y a mantener un control más riguroso de sus gastos.  
**Sabremos que esto es cierto cuando veamos** una reducción en la cantidad de gastos excesivos reportados por los usuarios, así como un aumento en el número de usuarios que configuran y utilizan las alertas. Además, esperamos recibir feedback positivo sobre la utilidad y eficacia de esta función en las reseñas de la aplicación.
###### **Hipótesis 2:**
**Creemos que** ofrecer recomendaciones personalizadas basadas en los hábitos de gasto y objetivos financieros de los usuarios mejorará su capacidad para ahorrar y planificar a largo plazo.  
**Sabremos que esto es cierto cuando veamos** un aumento en el monto promedio de ahorro mensual de los usuarios, un incremento en la cantidad de metas financieras alcanzadas y comentarios positivos sobre la relevancia de las recomendaciones recibidas en la aplicación.
###### **Hipótesis 3:**
**Creemos que** simplificar el proceso de creación de presupuestos mediante una interfaz más intuitiva y fácil de usar aumentará la adopción de esta función entre nuestros usuarios jóvenes adultos peruanos.  
**Sabremos que esto es cierto cuando veamos** un incremento en la tasa de usuarios que crean y ajustan presupuestos dentro de la aplicación, junto con una mejora en las calificaciones de usabilidad y facilidad de uso en las reseñas de la aplicación.
##### 1.2.2.4. Lean UX Canvas
### 1.3. Segmentos objetivo

**Segmento objetivo #1: Jóvenes Adultos Peruanos**

Este grupo está compuesto por jóvenes adultos de entre 18 y 30 años, 
que incluyen tanto estudiantes universitarios como jóvenes 
profesionales al inicio de sus carreras. Estos individuos 
enfrentan desafíos significativos en la gestión de sus finanzas 
personales, tales como el sobreendeudamiento y la falta de ahorro. 
La realidad económica de este segmento se caracteriza por ingresos 
iniciales limitados y una alta exposición a gastos imprevistos, 
lo que puede dificultar la creación de un colchón financiero estable.

Características clave de este segmento:

- Enfrentan desafíos en la gestión de sus finanzas debido a ingresos iniciales bajos y gastos imprevistos.
- Buscan herramientas prácticas y accesibles para mejorar su estabilidad económica y evitar el sobreendeudamiento.
- Desean desarrollar buenos hábitos financieros desde una edad temprana para asegurar un futuro económico sólido.
- Valoran soluciones que sean fáciles de usar y que se adapten a su estilo de vida dinámico

**Segmento objetivo #2: Expertos en Finanzas**

Este grupo está compuesto por profesionales de las finanzas con varios años de experiencia, como consultores financieros, asesores de inversiones y planificadores financieros. Estos individuos tienen un profundo conocimiento en la gestión de finanzas avanzadas y buscan herramientas que no solo optimicen su propia gestión financiera, sino que también puedan recomendar a sus clientes. Aunque manejan herramientas complejas en su día a día, valoran la simplicidad y la eficiencia para gestionar sus finanzas personales de manera rápida y efectiva.

Características clave de este segmento:
- Conocen profundamente las finanzas, pero buscan herramientas que les ahorren tiempo en tareas rutinarias como la gestión de ingresos, gastos, deudas y ahorros personales.
- Valoran el análisis financiero avanzado y reportes detallados que les permitan un seguimiento preciso tanto para ellos como para sus clientes.
- Desean soluciones que sean accesibles y prácticas para recomendar a sus clientes, facilitando la educación financiera.
- Buscan automatización y simplicidad, dado que su tiempo es limitado y prefieren que ciertas tareas financieras se manejen de manera automática.
- Prefieren herramientas que integren tanto finanzas personales como profesionales, para gestionar su dinero y el de sus clientes sin complicaciones adicionales.

## Capítulo II: Requirements Elicitation & Analysis <a id="cap2"></a>

### 2.1. Competidores

Considerando los ideales de nuestra empresa y la tecnología que desarrolla, alineados 
con nuestra misión y visión, es importante reconocer la existencia de otras aplicaciones 
y herramientas similares en el mercado. 
A continuación, mencionamos algunas de ellas y cómo se diferencian de nuestra propuesta.

- **Monefy:**

Monefy es la aplicación líder en el sector de finanzas tanto en web como móvil, se trata de una herramienta muy completa que le permite al usuario llevar un registro diario de sus gastos, establecer metas, etc. Todo acompañado de una excelente interfaz y una gran variedad de personalización.

<div style="text-align: center;">
  <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple126/v4/6a/d9/fe/6ad9fe61-1093-9e6d-3255-31c4ad760334/AppIcon-1x_U007emarketing-0-7-0-85-220.png/246x0w.webp" alt="Fintonic" width="300"/>
</div>

- **BlueCoins:** 

BlueCoins es una alternativa mas simple y limpia visualmente que aplicaciones mas predominantes en el sector como Monefy por ejemplo, ayuda a la lectura de gastos con gráficos vistosos que se pueden importar en gran variedad de formatos, se diferencia de sus competidores con su sistema de pago, pues es de pago unico a diferencia de sus rivales que cuentan con sistema de suscripción.

<div style="text-align: center;">
  <img src="https://play-lh.googleusercontent.com/-aqnLAv6P5doG6C7mKFYDjeuANbbMhPwYpgGzPk7irE4-3Q5jUCu1KkbGmTNl5ijvsM=w240-h480-rw" alt="BlueCoins" width="300"/>
</div>

- **Wallet by BudgetBakers:**

Wallet es una aplicación global que permite a los usuarios 
planificar sus presupuestos y gestionar sus finanzas personales 
con un enfoque en la personalización y sincronización con cuentas 
bancarias. Ofrece reportes detallados y herramientas avanzadas 
para ayudar a los usuarios a tomar decisiones financieras informadas, 
todo dentro de una plataforma flexible y adaptable.

<div style="text-align: center;">
  <img src="https://lh3.googleusercontent.com/LBIyqZbsxXWWQWjsWD5moPJhQQ5L0OKUFNNEbNfUAyJR8vBhPTNll4m2Z2-Lu6reuU4" alt="Wallet" width="300"/>
</div>

#### 2.1.1. Análisis competitivo
<table border="1" style="text-align: center;">
	<tbody>
		<tr>
			<td colspan="6">Análisis de competidores</td>
		</tr>
		<tr>
			<td colspan="2"></td>
			<td>SmartFinance</td>
			<td>Wallet</td>
			<td>Monefy</td>
			<td>Bluecoins</td>
		</tr>
		<tr>
			<td rowspan="2">Perfil</td>
			<td>Resumen</td>
			<td>Una aplicacion que busca apoyar al usuario en la gestion de sus finanzas, el usuario podra establecer presupuestos personalizados, recibir alertas, etc.</td>
			<td>Se trata de una aplicación de planificación financiera, donde el usuario puede establecer sus objetivos, sus presupuestos y llevar control de los gastos que realizo durante el dia</td>
			<td>Es la aplicación líder en finanzas, Monefy ofrece una interfaz simple pero llena de poderosas herramientas orientadas al control de los gastos diarios y de los objetivos del usuario.</td>
			<td>Es una aplicación sencilla que le permite al usuario llevar seguimiento de sus gastos e ingresos, la informacion recolectada puede ser exportada en diferentes formatos.</td>
		</tr>
		<tr>
			<td>Ventaja competitiva</td>
			<td>Buscamos integrar una gran cantidad de herramientas bajo una misma aplicación, manteniendo una interfaz limpia para facilitar la experiencia al usuario.</td>
			<td>Otra aplicación top en el sector de finanzas personales, orientada sobre todo al ahorro de dinero.</td>
			<td>Líder en el sector de finanzas personales y con una excelente reputacion debido a las multiples herramientas que ofrece
      </td>
			<td>Interfaz amigable y funcionamiento rápido y sencillo, muy amigable con nuevos usuarios. </td>
		</tr>
		<tr>
			<td rowspan="2">Perfil de Marketing</td>
			<td>Mercado objetivo</td>
			<td>Jovenes peruanos, entre los 18 y 30 años.</td>
			<td>Adultos que cuentan con multiples gastos diarios.</td>
			<td>Adultos que ya se encuentran en su vida laboral y buscan ahorrar dinero cada mes.</td>
			<td>Cualquier joven o adulto que desee ordenar sus ingresos mensuales de una manera rápida.</td>
		</tr>
		<tr>
			<td>Estrategias de marketing</td>
			<td>Marketing digital en redes sociales y colaboraciones con influencers.</td>
			<td>Alianza con Google Ads, tanto en Youtube como Chrome.</td>
			<td>Marketing online, tanto en artículos online como video reseñas por parte de influencers.</td>
			<td>Promociones realizadas por influencers en Youtube.</td>
		</tr>
		<tr>
			<td rowspan="3">Perfil de Producto</td>
			<td>Productos y Servicios</td>
			<td>Aplicación con herramientas que permiten registrar ingresos y gastos, planificar ahorros, recibir recordatorios, etc.</td>
			<td>Aplicación móvil y web que cuenta con presupuestos, registro diario de gastos y graficos para seguir nuestro progreso</td>
			<td>Aplicación móvil que invita al usuario a ser transparente con sus gastos diarios y lo alienta a empezar a ahorrar dinero.</td>
			<td>Aplicación móvil facil de usar que permite llevar un seguimiento de los gastos diarios con gran variedad de gráficas y métodos de exportación.</td>
		</tr>
		<tr>
			<td>Precios y Costos</td>
			<td>Modelo de suscripción mensual para acceder a los servicios de coaching y planes alimentarios personalizados.</td>
			<td>Modelo gratuito con suscripción anual.</td>
			<td>Modelo gratuito con suscripción anual.</td>
			<td>Inicio gratuito con la posibilidad de mejorar la cuenta a una cuenta premium permanente.</td>
		</tr>
		<tr>
			<td>Canales de distribución</td>
			<td>Disponible en línea a través de la aplicación web.</td>
			<td>Descargable en Google Play y App Store y la plataforma web.</td>
			<td>Descargable en Google Play y App Store.</td>
			<td>Descargable en Google Play y App Store.</td>
		</tr>
		<tr>
			<td rowspan="4">Análisis SWOT</td>
			<td>Fortalezas</td>
			<td>
                <ul>
                    <li>Orientado a jóvenes peruanos</li>
                    <li>Multiples herramientas incluidas</li>
                    <li>Herramientas gratuitas y otras de pago</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Gran cantidad de usuarios</li>
                    <li>Buena variedad de herramientas</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Orientado al ahorro de dinero</li>
                    <li>Líder en el sector finanzas con gran cantidad de reseñas positivas</li>
                    <li>Herramientas poderosas e interfaz vistosa</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Mejora asequible y de pago único</li>
                    <li>Rápida de usar y facilidad para exportar reportes</li>
                </ul>
            </td>
		</tr>
		<tr>
			<td>Debilidades</td>
			<td>
                <ul>
                    <li>Nuevo competidor</li>
                    <li>Sector con competidores fuertes ya establecidos</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Suscripción anual con un precio no muy asequible</li>
                    <li>Requiere de mucha atención por parte del usuario</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Version gratuita muy limitada</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Es la aplicación con menos base de usuarios</li>
                    <li>Poca variedad de herramientas</li>
                </ul>
            </td>
		</tr>
		<tr>
			<td>Oportunidades</td>
			<td>
                <ul>
                    <li>Sin competidores a nivel nacional</li>
                    <li>Puede resultar muy útil para el sector elegido debido a sus posibilidades economicas</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Aplicación en crecimiento</li>
                    <li>Soporte para múltiples monedas</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Poderosas herramientas en constante actualización</li>
                    <li>Membresía asequible</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Pago único y asequible</li>
                    <li>Excelente interfaz</li>
                </ul>
            </td>
		</tr>
		<tr>
			<td>Amenazas</td>
			<td>
                <ul>
                    <li>Competencia ya establecidos</li>
                    <li>Sector muy competitivo</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Poca cantidad de usuarios premium</li>
                    <li>Membresía anual muy alta</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Soporte tecnico en ingles</li>
                    <li>Precio inconsistente debido a las diferentes promociones</li>
                </ul>
            </td>
			<td>
                <ul>
                    <li>Se ve opacado por la competencia</li>
                    <li>Escala mas sencilla comparado con sus competidores</li>
                </ul>
            </td>
		</tr>
	</tbody>
</table>
#### 2.1.2. Estrategias y tácticas frente a competidores.
### 2.2. Entrevistas.
#### 2.2.1. Diseño de entrevistas

##### Segmento 1:

###### Preguntas de Información General:

1. ¿Cuál es tu nombre?
2. ¿Cuántos años tienes?
3. ¿En qué distrito vives?
4. ¿A qué te dedicas actualmente? (Estudiante, profesional, etc.)

###### Preguntas sobre Hábitos Financieros:

5. ¿Cómo manejas actualmente tus ingresos y gastos?
6. ¿Cuál es el mayor desafío que enfrentas al gestionar tus finanzas personales?
7. ¿Sueles establecer un presupuesto mensual? Si es así, ¿qué tan a menudo lo sigues?
8. ¿Tienes algún sistema o herramienta que te ayude a planificar tus ahorros?
9. ¿Has solicitado algún tipo de crédito o préstamo? 
10. ¿Qué tan fácil o difícil te resulta hacer un seguimiento de tus deudas?
11. ¿Qué características valorarías más en una aplicación de finanzas personales?

###### Preguntas sobre Tecnología y Comportamiento:

12. ¿Qué tipo de dispositivos sueles usar para gestionar tus finanzas?
13. ¿Qué aplicaciones o plataformas digitales utilizas frecuentemente?
14. ¿Cómo te sientes respecto a la privacidad y seguridad de tus datos financieros al usar aplicaciones? ¿Te preocupa que tus datos puedan ser comprometidos?
15. Si pudieras cambiar algo en la forma en que gestionas tus finanzas, ¿qué sería?
16. ¿Qué tan dispuesto estarías a suscribirte por una aplicación que mejore significativamente tu gestión financiera?
17. ¿Qué te haría dejar de usar una aplicación de finanzas personales?

#### 2.2.2. Registro de entrevistas
##### Entrevista #1
Nombre y apellido: Elvia Rodriguez
Edad: 23
Distrito: Comas
![int1](https://github.com/JosuePaiva02/files/blob/main/Entrevista%201%20Finzar%20-%20YouTube%20-%20Google%20Chrome%208_09_2024%2016_09_50.png?raw=true)
Inicio de la entrevista: 0:26s
[URL de la entrevista](https://www.youtube.com/watch?v=zLULHrg971A
)


##### Entrevista #2
Nombre y apellido: Bruno Martinez
Edad: 19
Distrito: Comas
![int1](https://github.com/JosuePaiva02/files/blob/main/Entrevista%201%20Finzar%20-%20YouTube%20-%20Google%20Chrome%208_09_2024%2016_10_10.png?raw=true)
Inicio de la entrevista: 0:34s
[URL de la entrevista](https://www.youtube.com/watch?v=H7TcCMm1-CU
)


##### Entrevista #3
Nombre y apellido: Flavio Gallardo
Edad: 20
Distrito: Breña
![int3](https://github.com/JosuePaiva02/files/blob/main/Entrevista%201%20Finzar%20-%20YouTube%20-%20Google%20Chrome%208_09_2024%2016_23_23.png?raw=true)
Inicio de la entrevista: 0.20s
[URL de la entrevista](https://drive.google.com/file/d/1bQi7SGnlGwXWfvCi3nJE4HDy3oBC6-vp/view
)


#### 2.2.3. Análisis de entrevistas
##### Entrevista 1: Elvia Ridriguez
Análisis de la entrevista:
Elvia nos cuenta como gestiona sus ingresos como practicante, cuenta con una deuda de una tarjeta de crédito hace algunos años y por esta misma experiencia le resulta complicado hacer seguimiento de sus finanzas, le gustaría que una aplicación de finanzas sea ágil y no requiera poco tiempo de uso para hacer registro de gastos diarios, se encuentra muy dispuesta a hacer uso de una aplicación para controlar sus finanzas pero la desmotivaría si esta requiere de mucho uso diario.

##### Entrevista 2: Bruno Martinez
Análisis de la entrevista: Bruno nos comenta como gestiona sus finanzas semanales con excel, el cual sigue al pie de la letra, nunca se ha visto expuesto a deudas, ademas nos cuenta que valoraria mucho el seguimiento de su presupuesto con una app y que le notifique cuando se esta llegando al límite, le gustaría una aplicación eficiente, pero duda si la suscripción llegue a estar en su prespuesto, ademas se alejaría de la app si la suscripción es muy cara o si no es tan eficiente como su modelo de organización anterior

##### Entrevista 3: Flavio Gallardo
Análisis de la entrevista: Flavio tiene un caso mas simple al tratarse de un estudiante universitario, no ha solicitado deudas y sus finanzas se ven sujetas a su mesada mensual, a veces usa hojas de cálculo para ordenar sus finanzas, usa regularmente aplicaciones como la banca de BCP y Yape para pagos, le preocupa la seguridad de sus datos personales y le gustaría ser mas disciplinado con la regulación de su presupuesto, consideraría pagar una suscripción por una aplicación que le ofrezca algo superior a aplicaciónes gratuitas y la dejaría si considera que no es muy eficiente o si recibe numerosas notificaciones
### 2.3. Needfinding
#### 2.3.1. User Personas
###### Segmento Objetivo 1
![User personas](https://github.com/user-attachments/assets/bb847986-d273-43e9-94d1-28dc325337c9)
###### Segmento Objetivo 2
![User Persona 2 FINZAR](https://github.com/user-attachments/assets/a3cf00b8-8ded-4e8c-90cb-f60e8f640869)

#### 2.3.2. User Task Matrix
######  Jóvenes  Adultos Peruanos

Introducción:
El siguiente User Task Matrix detalla las tareas que los jóvenes adultos peruanos suelen realizar en la gestión de sus finanzas personales. Este segmento incluye estudiantes universitarios y jóvenes profesionales que enfrentan desafíos significativos en la administración de su dinero debido a ingresos limitados y falta de experiencia. Las tareas están clasificadas según su frecuencia e importancia para este grupo, proporcionando una visión clara de las áreas en las que se concentran y las que requieren más atención.

| **Tareas (Tasks)**                                   | **Frecuencia** | **Importancia** |
|------------------------------------------------------|:---------------------------------:|:----------------------:|                                                      
| **Registrar ingresos y gastos**                   | Alta           | Alta            | Alta           | Alta            |
| **Crear y ajustar un presupuesto mensual**        | Media          | Alta            | Alta           | Alta            |
| **Planificar y seguir metas de ahorro**           | Media          | Alta            | Alta           | Alta            |
| **Controlar y pagar deudas**                      | Baja           | Media           | Media          | Alta            |
| **Revisar y analizar reportes financieros**       | Media          | Media           | Alta           | Alta            |
| **Buscar información financiera y educación**     | Alta           | Alta            | Media          | Media           |
| **Evaluar y seleccionar herramientas financieras**| Media          | Media           | Media          | Alta            |
| **Consultar asesoría financiera**                 | Baja           | Baja            | Media          | Media           |

Explicación:

- **Registrar ingresos y gastos**: Es crucial y frecuente, ya que permite a los jóvenes adultos tener un control básico de sus finanzas.
- **Crear y ajustar un presupuesto mensual**: Importante para planificar gastos y evitar el sobreendeudamiento, realizado con frecuencia media.
- **Planificar y seguir metas de ahorro**: Ayuda a establecer objetivos financieros y es vital para la estabilidad económica, con frecuencia media.
- **Controlar y pagar deudas**: Aunque menos frecuente, es esencial para evitar problemas financieros graves.
- **Revisar y analizar reportes financieros**: Proporciona una visión clara de la situación financiera, con frecuencia e importancia medias.
- **Buscar información financiera y educación**: Es de alta frecuencia e importancia, dado que muchos jóvenes necesitan aprender y mejorar sus habilidades financieras.
- **Evaluar y seleccionar herramientas financieras**: Importante para adaptar soluciones a las necesidades personales, con frecuencia media.
- **Consultar asesoría financiera**: Menos frecuente e importante, pero útil para quienes buscan orientación profesional específica.


###### Expertos en finanzas

Introducción:
El siguiente User Task Matrix detalla las tareas realizadas por expertos en finanzas en la gestión de sus finanzas personales y profesionales. Este segmento incluye consultores financieros, asesores de inversiones y planificadores financieros. Las tareas están clasificadas por frecuencia e importancia para entender sus prioridades y áreas de enfoque.


| **Tareas (Tasks)**                                   | **Frecuencia** | **Importancia** |
|------------------------------------------------------|:--------------:|:---------------:|
| **Registrar ingresos y gastos**                     | Media          | Alta            |
| **Crear y ajustar un presupuesto mensual**          | Baja           | Alta            |
| **Planificar y seguir metas de ahorro**             | Baja           | Media           |
| **Controlar y pagar deudas**                        | Baja           | Media           |
| **Revisar y analizar reportes financieros**          | Alta           | Alta            |
| **Buscar información financiera y educación**       | Media          | Media           |
| **Evaluar y seleccionar herramientas financieras**   | Media          | Alta            |
| **Consultar asesoría financiera**                    | Baja           | Baja            |

**Explicación:**

- **Registrar ingresos y gastos**: Frecuente y de alta importancia para mantener el control financiero personal.
- **Crear y ajustar un presupuesto mensual**: Menos frecuente pero crucial para la planificación de gastos.
- **Planificar y seguir metas de ahorro**: Menos frecuente, importancia media para mantener estrategias de ahorro.
- **Controlar y pagar deudas**: Menos frecuente e importante, los expertos suelen gestionar bien sus deudas.
- **Revisar y analizar reportes financieros**: Alta frecuencia e importancia para evaluar el desempeño financiero.
- **Buscar información financiera y educación**: Frecuencia e importancia medias, para actualizar conocimientos.
- **Evaluar y seleccionar herramientas financieras**: Frecuencia e importancia medias para adaptar herramientas a sus necesidades.
- **Consultar asesoría financiera**: Menos frecuente e importante, ya que generalmente tienen el conocimiento necesario.



#### 2.3.3. User Journey Mapping
![User Jorney Mapping](https://github.com/user-attachments/assets/5c8dcf3b-a8f5-40c2-94c3-3768e58c8e34)
#### 2.3.4. Empathy Mapping
![Empathy map](https://github.com/user-attachments/assets/d5217f32-d4f5-4097-ab3c-5ec9b07e43a0)
#### 2.3.5. As-is Scenario Mapping
###### Segmento Objetivo #1
![As-is Scenario Mapping UserPersona01 FINZAR](https://github.com/user-attachments/assets/6c3afd26-1760-4f87-b9a5-d6e9bd5f1089)

###### Segmento Objetivo #2
![As-is Scenario Mapping UserPersona02 FINZAR](https://github.com/user-attachments/assets/f61c8b64-d343-4c9a-a37b-d3470e8c2712)

### 2.4. Ubiquitous Language

#### **Términos Generales**

1. **User (Usuario):**
   - Jóvenes adultos peruanos entre 18 y 30 años, incluyendo estudiantes universitarios y jóvenes profesionales, que utilizan Finzar para gestionar sus finanzas personales.

2. **User Profile (Perfil de Usuario):**
   - Información personal y preferencias financieras del usuario, que Finzar utiliza para personalizar la experiencia y ofrecer recomendaciones adecuadas.

3. **Intuitive Interface (Interfaz Intuitiva):**
   - Diseño de la aplicación Finzar que facilita la navegación y uso, permitiendo a los usuarios manejar sus finanzas de manera sencilla.

4. **Service Cost (Costo de Servicio):**
   - Comisiones o tarifas aplicadas a los usuarios por servicios premium ofrecidos por Finzar, como reportes avanzados o asistencia personalizada.

---

#### **Perfiles de Usuario**

1. **Financial Goal (Meta Financiera):**
   - Objetivo que el usuario establece en Finzar para ahorrar o reducir deudas, como la compra de un bien o la creación de un fondo de emergencia.

4. **Balance (Saldo):**
   - Cantidad de dinero con la que trabaja el usuario, declarada por el mismo o ligada a su cuenta bancaria.

2. **Income (Ingreso):**
   - Cantidad de dinero que un usuario recibe de diversas fuentes, como salario, becas, o trabajos independientes, y que se registra en Finzar para su gestión.

3. **Expense (Gasto):**
   - Dinero que el usuario destina a cubrir sus necesidades y deseos, como pagos de servicios, compras personales o entretenimiento.


---

#### **Proceso de Gestión Financiera**

1. **Budget (Presupuesto):**
   - Plan financiero que el usuario crea en Finzar para asignar sus ingresos a diferentes categorías de gastos y ahorro, asegurando un equilibrio entre ambos.

2. **Saving Plan (Plan de Ahorro):**
   - Estrategia desarrollada por el usuario dentro de Finzar para apartar una parte de sus ingresos con el fin de alcanzar sus metas financieras.

3. **Financial Report (Reporte Financiero):**
   - Informe detallado generado por Finzar que muestra los hábitos financieros del usuario, incluyendo ingresos, gastos, ahorros y deudas.

4. **Financial Reminder (Recordatorio Financiero):**
   - Notificación que Finzar envía al usuario para alertarle sobre pagos próximos, plazos de deuda, o revisiones presupuestarias necesarias.

5. **Debt Management (Gestión de Deudas):**
   - Herramienta en Finzar que ayuda a los usuarios a controlar y pagar sus deudas de manera efectiva.

## Capítulo III: Requirements Specification <a id="cap3"></a>

### 3.1. To-Be Scenario Mapping
###### Segmento Objetivo #1
![To-be Scenario Mapping UserPersona01 FINZAR](https://github.com/user-attachments/assets/96796f9f-2c6b-418b-bcc0-3d8aa8447dee)

###### Segmento Objetivo #2
![To-be Scenario Mapping UserPersona02 FINZAR](https://github.com/user-attachments/assets/7391cff1-d51d-4957-8939-ec33d1442a2c)

### 3.2. User Stories
| **Epic / Story ID** | **Título**                                    | **Descripción**                                                                                                                              | **Criterios de Aceptación**                                                                                                                                                                                                                                                    | **Relacionado con (Epic ID)** |
|---------------------|-----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| US-01               | Registro de Usuario                           | Como visitante, quiero registrarme en la aplicación para empezar a gestionar mis finanzas personales.                                        | **Given** el visitante está en la página de registro, **when** completa los campos obligatorios y hace clic en "Registrarse", **then** el sistema debe crear una cuenta.                                                                                                       | EP-01                         |
| US-02               | Inicio de Sesión                              | Como usuario, quiero iniciar sesión en la aplicación para acceder a mi cuenta y gestionar mis finanzas.                                      | **Given** el usuario está registrado, **when** ingresa sus credenciales correctas, **then** debe poder acceder a su cuenta.                                                                                                                                                    | EP-01                         |
| US-03               | Recuperación de Contraseña                    | Como usuario, quiero recuperar mi contraseña en caso de olvidarla para poder acceder nuevamente a mi cuenta.                                 | **Given** el usuario ha olvidado su contraseña, **when** solicita la recuperación, **then** debe recibir un enlace para restablecerla por correo electrónico.                                                                                                                  | EP-01                         |
| US-04               | Creación de Billeteras                        | Como usuario, quiero disponer de dos billeteras por defecto creados durante la creación de mi cuenta para poder registrar mis transacciones. | **Given** el usuario creó su cuenta, **when** accede a la sección de billeteras, **then** debería ver una billetera general y una billetera de emergencia por defecto.                                                                                                         | EP-01                         |
| US-05               | Creación de Billeteras                        | Como usuario, quiero crear billeteras adicionales para organizar mis transacciones de acuerdo a mis necesidades.                             | **Given** el usuario está en la sección de billeteras, **when** selecciona la opción de crear una nueva billetera, **then** debe poder ingresar un nombre y descripción para la nueva billetera.                                                                               | EP-02                         |
| US-06               | Visualizar el Estado de una Billetera         | Como usuario, quiero ver el estado actual de una billetera para conocer mi saldo y transacciones recientes.                                  | **Given** el usuario está en la sección de billeteras, **when** selecciona una billetera, **then** debe ver el saldo actual y las transacciones más recientes de la billetera.                                                                                                 | EP-02                         |
| US-07               | Ingreso de Transacciones                      | Como usuario, quiero registrar un ingreso o gasto en una billetera seleccionada para llevar un control de mis finanzas.                      | **Given** el usuario está en la sección de una billetera, **when** selecciona la opción de registrar una transacción, **then** debe poder ingresar los detalles de la transacción, como monto, categoría y nota.                                                               | EP-02                         |
| US-08               | Categorizar Transacciones                     | Como usuario, quiero categorizar mis transacciones para organizar y analizar mis gastos e ingresos.                                          | **Given** el usuario registra una transacción, **when** selecciona una categoría para la transacción, **then** la transacción se clasifica automáticamente en la categoría seleccionada.                                                                                       | EP-02                         |
| US-09               | Crear Transacciones Recurrentes               | Como usuario, quiero crear transacciones recurrentes para automatizar el registro de gastos e ingresos periódicos.                           | **Given** el usuario está en la sección de una billetera, **when** selecciona la opción de registrar una transacción **and** marca la opción de transacción recurrente configurando la frecuencia, **then** la transacción se registra automáticamente según la configuración. | EP-02                         | 
| US-10               | Ver Futuras Transacciones                     | Como usuario, quiero ver las transacciones futuras programadas para anticipar mis gastos e ingresos.                                         | **Given** el usuario está en la sección de una billetera, **when** accede a la lista de transacciones futuras, **then** debe ver las transacciones programadas con sus detalles y fechas.                                                                                      | EP-02                         |
| US-11               | Filtrar Transacciones por Nota                | Como usuario, quiero filtrar mis transacciones por nota para encontrar rápidamente transacciones específicas.                                | **Given** el usuario está en la sección de una billetera, **when** ingresa una nota en el campo de búsqueda, **then** el sistema debe mostrar solo las transacciones que contienen la nota ingresada.                                                                          | EP-02                         |
| US-12               | Realizar Transacciones a otra Billetera       | Como usuario, quiero transferir dinero de una billetera a otra para mover fondos entre mis cuentas.                                          | **Given** el usuario está en la sección de una billetera, **when** selecciona la opción de transferir dinero, **then** debe poder ingresar el monto **and** seleccionar la billetera de destino para completar la transferencia.                                               | EP-02                         |
| US-13               | Crear Plan de Presupuesto                     | Como usuario, quiero crear un plan de presupuesto para establecer límites de gastos y controlar mis finanzas de manera efectiva.             | **Given** el usuario está en la sección de presupuestos, **when** selecciona la opción de crear un nuevo plan, **then** debe poder ingresar un nombre, monto y fechas de inicio y fin para el plan de presupuesto.                                                             | EP-03                         |
| US-14               | Editar Plan de Presupuesto                    | Como usuario, quiero editar un plan de presupuesto existente para ajustar los límites de gastos y adaptarlos a mis necesidades actuales.     | **Given** el usuario está en la sección de presupuestos, **when** selecciona un plan de presupuesto existente, **then** debe poder modificar el nombre, monto y fechas del plan de presupuesto.                                                                                | EP-03                         |
| US-15               | Ver Presupuesto Restante                      | Como usuario, quiero ver el presupuesto restante de un plan para controlar mis gastos y evitar exceder los límites establecidos.             | **Given** el usuario está en la sección de presupuestos, **when** selecciona un plan de presupuesto, **then** debe ver el monto restante del presupuesto y una barra de progreso que indica el porcentaje gastado.                                                             | EP-03                         |
| US-16               | Alerta de Límite de Presupuesto               | Como usuario, quiero recibir una alerta cuando esté cerca de exceder el límite de un plan de presupuesto para evitar gastos innecesarios.    | **Given** el usuario está en la sección de presupuestos, **when** el monto gastado se acerca al límite del plan, **then** debe recibir una notificación de alerta que le advierte sobre el exceso de gastos.                                                                   | EP-03                         |
| US-17               | Crear Plan de Ahorro                          | Como usuario, quiero crear un plan de ahorro para establecer metas financieras y ahorrar dinero de manera sistemática.                       | **Given** el usuario está en la sección de ahorros, **when** selecciona la opción de crear un nuevo plan, **then** debe poder ingresar un nombre, monto y fechas de inicio y fin para el plan de ahorro.                                                                       | EP-03                         |
| US-18               | Editar Plan de Ahorro                         | Como usuario, quiero editar un plan de ahorro existente para ajustar las metas financieras y adaptarlas a mis necesidades actuales.          | **Given** el usuario está en la sección de ahorros, **when** selecciona un plan de ahorro existente, **then** debe poder modificar el nombre, monto y fechas del plan de ahorro.                                                                                               | EP-03                         |
| US-19               | Ver Progreso del Ahorro                       | Como usuario, quiero ver el progreso de un plan de ahorro para seguir mis metas financieras y motivarme a ahorrar.                           | **Given** el usuario está en la sección de ahorros, **when** selecciona un plan de ahorro, **then** debe ver el monto ahorrado, el monto restante y una barra de progreso que indica el porcentaje alcanzado de la meta.                                                       | EP-03                         |
| US-20               | Navegación por el Landing Page                | Como visitante, quiero navegar por la landing page del software para obtener la información que deseo del producto.                          | **Given** el visitante está en la landing page, **when** navega por las secciones y contenido, **then** debe encontrar información clara y relevante sobre las funcionalidades y beneficios del software.                                                                      | EP-04                         |
| US-21               | Ver los Miembros del Equipo Desarrollador     | Como visitante, quiero ver la información del equipo de desarrollo para conocer a las personas detrás del software.                          | **Given** el visitante está en la landing page,, **when** navega por los perfiles de los miembros, **then** debería ver fotos, nombres y roles de cada miembro del equipo.                                                                                                     | EP-04                         |
| US-22               | Cambiar el Idioma de la Landing Page          | Como visitante, quiero cambiar el idioma de la landing page para poder entender mejor la información presentada.                             | **Given** el visitante está en la landing page, **when** selecciona un idioma diferente en el menú de idiomas, **then** la página debe cambiar al idioma seleccionado.                                                                                                         | EP-04                         |
| TS-23               | Configurar Entorno de Desarrollo              | Como desarrollador, quiero configurar mi entorno de desarrollo local para poder trabajar en el proyecto.                                     | **Given** el desarrollador tiene acceso al repositorio del proyecto, **when** sigue las instrucciones de configuración, **then** debería poder ejecutar la aplicación localmente.                                                                                              | EP-05                         |
| TS-24               | Solucionar Errores Reportados                 | Como desarrollador, quiero corregir los errores del software notificados por el equipo de QA para mejorar la calidad del producto.           | **Given** el desarrollador recibe un reporte de error, **when** identifica y soluciona el problema, **then** debe confirmar la corrección con el equipo de QA.                                                                                                                 | EP-05                         |
| TS-25               | Implementar Notificaciones como Funcionalidad | Como desarrollador, quiero implementar el poder recibir notificaciones para mantener al usuario informado sobre sus reportes.                | **Given** el desarrollador tiene acceso al código fuente, **when** implementa la funcionalidad de notificaciones, **then** el sistema envía notificaciones al usuario quien recibe las alertas en tiempo real.                                                                 | EP-05                         |
| TS-26               | Registrar Usuarios por una API                | Como desarrollador, quiero implementar una API que permita registrar nuevos usuarios al sistema.                                             | **Given** el endpoint (/api/v1/auth/sign-up) esté disponible, **when** se envía una solicitud POST con los datos del usuario ingresados al endpoint, **then** se recibe una señal de confirmación (201) **and** el sistema registra al usuario.                                | EP-05                         |
| TS-27               | Autenticación de Usuarios                     | Como desarrollador, quiero implementar una API que permita autenticar a los usuarios en el sistema.                                          | **Given** el endpoint (/api/v1/auth/log-in) esté disponible, **when** se envía una solicitud POST con las credenciales del usuario al endpoint, **then** se recibe una señal de confirmación (200) **and** el sistema permite el acceso al usuario.                            | EP-05                         |
| TS-28               | Mantenimiento del Software                    | Como desarrollador, quiero mantener actualizado y en buen estado el software para asegurar su correcto funcionamiento y seguridad.           | **Given** la plataforma tiene un mantenimiento pendiente o nuevas funcionalidades, **when** realiza el mantenimiento correspondiente mediante las actualizaciones, **then** el sistema se mantiene seguro y actualizado.                                                       | EP-05                         |

### **Epic 01: Creación y Gestión de Cuenta**
| **Story ID** | **Título**                 |
|--------------|----------------------------|
| US-01        | Registro de Usuario        |
| US-02        | Inicio de Sesión           |
| US-03        | Recuperación de Contraseña |

### **Epic 02: Billetera del Usuario y Registro de Transacciones**
| **Story ID** | **Título**                                       |
|--------------|--------------------------------------------------|
| US-04        | Crear Billeteras                                 |
| US-05        | Visualizar el Estado Financiero de una Billetera |
| US-06        | Ingreso de Transacciones                         |
| US-07        | Categorizar Transacciones                        |
| US-08        | Crear Transacciones Recurrentes                  |
| US-09        | Ver Futuras Transacciones                        |
| US-10        | Filtrar Transacciones por Nota                   |
| US-11        | Realizar Transacciones a otra Billetera          |

### **Epic 03: Monitoreo de Presupuestos y Ahorros**
| **Story ID** | **Título**                      |
|--------------|---------------------------------|
| US-13        | Crear Plan de Presupuesto       |
| US-14        | Editar Plan de Presupuesto      |
| US-15        | Ver Presupuesto Restante        |
| US-16        | Alerta de Límite de Presupuesto |
| US-17        | Crear Plan de Ahorro            |
| US-18        | Editar Plan de Ahorro           |
| US-19        | Ver Progreso del Ahorro         |

### **Epic 04: Visualización de la Interfaz del Usuario**
| **Story ID** | **Título**                           |
|--------------|--------------------------------------|
| US-20        | Navegación por el Landing Page       |
| US-21        | Ver los Miembros del Equipo          |
| US-22        | Cambiar el Idioma de la Landing Page |

### **Epic 05: Desarrollo de Funcionalidades de la Aplicación**
| **Story ID** | **Título**                                     |
|--------------|------------------------------------------------|
| TS-23        | Configurar Entorno de Desarrollo               |  
| TS-24        | Solucionar Errores Reportados                  |
| TS-25        | Implementar Notificaciones como Funcionalidad  |
| TS-26        | Registrar Usuarios por una API                 |
| TS-27        | Autenticación de Usuarios                      |
| TS-28        | Mantenimiento del Software                     |

### 3.3. Impact Mapping
![Impact mapping](https://github.com/user-attachments/assets/976952a8-dc3b-4fa3-97de-983bd5c11eb7)
### 3.4. Product Backlog
| **#Orden** | **User Story Id** | **Título**                                    | **Descripción**                                                                                                                              | **Story Points** |
|------------|-------------------|-----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| 1          | US-01             | Registro de Usuario                           | Como visitante, quiero registrarme en la aplicación para empezar a gestionar mis finanzas personales.                                        | 2                |
| 2          | US-02             | Inicio de Sesión                              | Como usuario, quiero iniciar sesión en la aplicación para acceder a mi cuenta y gestionar mis finanzas.                                      | 3                |
| 3          | US-03             | Recuperación de Contraseña                    | Como usuario, quiero recuperar mi contraseña en caso de olvidarla para poder acceder nuevamente a mi cuenta.                                 | 3                |
| 4          | US-04             | Creación de Billeteras                        | Como usuario, quiero disponer de dos billeteras por defecto creados durante la creación de mi cuenta para poder registrar mis transacciones. | 3                |
| 5          | US-05             | Creación de Billeteras                        | Como usuario, quiero crear billeteras adicionales para organizar mis transacciones de acuerdo a mis necesidades.                             | 3                |
| 6          | US-06             | Visualizar el Estado de una Billetera         | Como usuario, quiero ver el estado actual de una billetera para conocer mi saldo y transacciones recientes.                                  | 3                |
| 7          | US-07             | Ingreso de Transacciones                      | Como usuario, quiero registrar un ingreso o gasto en una billetera seleccionada para llevar un control de mis finanzas.                      | 5                |
| 8          | US-08             | Categorizar Transacciones                     | Como usuario, quiero categorizar mis transacciones para organizar y analizar mis gastos e ingresos.                                          | 5                |
| 9          | US-09             | Crear Transacciones Recurrentes               | Como usuario, quiero crear transacciones recurrentes para automatizar el registro de gastos e ingresos periódicos.                           | 5                |
| 10         | US-10             | Ver Futuras Transacciones                     | Como usuario, quiero ver las transacciones futuras programadas para anticipar mis gastos e ingresos.                                         | 3                |
| 11         | US-11             | Filtrar Transacciones por Nota                | Como usuario, quiero filtrar mis transacciones por nota para encontrar rápidamente transacciones específicas.                                | 3                |
| 12         | US-12             | Realizar Transacciones a otra Billetera       | Como usuario, quiero transferir dinero de una billetera a otra para mover fondos entre mis cuentas.                                          | 5                |
| 13         | US-13             | Crear Plan de Presupuesto                     | Como usuario, quiero crear un plan de presupuesto para establecer límites de gastos y controlar mis finanzas de manera efectiva.             | 5                |
| 14         | US-14             | Editar Plan de Presupuesto                    | Como usuario, quiero editar un plan de presupuesto existente para ajustar los límites de gastos y adaptarlos a mis necesidades actuales.     | 3                |
| 15         | US-15             | Ver Presupuesto Restante                      | Como usuario, quiero ver el presupuesto restante de un plan para controlar mis gastos y evitar exceder los límites establecidos.             | 2                |
| 16         | US-16             | Alerta de Límite de Presupuesto               | Como usuario, quiero recibir una alerta cuando esté cerca de exceder el límite de un plan de presupuesto para evitar gastos innecesarios.    | 5                |
| 17         | US-17             | Crear Plan de Ahorro                          | Como usuario, quiero crear un plan de ahorro para establecer metas financieras y ahorrar dinero de manera sistemática.                       | 5                |
| 18         | US-18             | Editar Plan de Ahorro                         | Como usuario, quiero editar un plan de ahorro existente para ajustar las metas financieras y adaptarlas a mis necesidades actuales.          | 3                |
| 19         | US-19             | Ver Progreso del Ahorro                       | Como usuario, quiero ver el progreso de un plan de ahorro para seguir mis metas financieras y motivarme a ahorrar.                           | 2                |
| 20         | US-20             | Navegación por el Landing Page                | Como visitante, quiero navegar por la landing page del software para obtener la información que deseo del producto.                          | 3                |
| 21         | US-21             | Ver los Miembros del Equipo                   | Como visitante, quiero ver la información del equipo de desarrollo para conocer a las personas detrás del software.                          | 2                |
| 22         | US-22             | Cambiar el Idioma de la Landing Page          | Como visitante, quiero cambiar el idioma de la landing page para poder entender mejor la información presentada.                             | 3                |
| 23         | TS-23             | Configurar Entorno de Desarrollo              | Como desarrollador, quiero configurar mi entorno de desarrollo local para poder trabajar en el proyecto.                                     | 5                |
| 24         | TS-24             | Solucionar Errores Reportados                 | Como desarrollador, quiero corregir los errores del software notificados por el equipo de QA para mejorar la calidad del producto.           | 5                |
| 25         | TS-25             | Implementar Notificaciones como Funcionalidad | Como desarrollador, quiero implementar el poder recibir notificaciones para mantener al usuario informado sobre sus reportes.                | 3                |
| 26         | TS-26             | Registrar Usuarios por una API                | Como desarrollador, quiero implementar una API que permita registrar nuevos usuarios al sistema.                                             | 3                |
| 27         | TS-27             | Autenticación de Usuarios                     | Como desarrollador, quiero implementar una API que permita autenticar a los usuarios en el sistema.                                          | 3                |
| 28         | TS-28             | Mantenimiento del Software                    | Como desarrollador, quiero mantener actualizado y en buen estado el software para asegurar su correcto funcionamiento y seguridad.           | 5                |


![Product backlog](https://github.com/user-attachments/assets/3b947560-bc6a-44d0-835c-85a9b7a382fc)

## Capítulo IV: Product Design <a id="cap4"></a>

### 4.1. Style Guidelines
A continuación presentaremos los Style Guidelines de nuestro proyecto, con el fin de definir los parametros de presentacion de nuestra aplicación.
![Logo](https://github.com/JosuePaiva02/files/blob/main/nlogo.png?raw=true)

#### 4.1.1. General Style Guidelines
#### Logo
Con el siguiente logo buscamos proyectar una imagen moderna, con un logo minimalista azul y blanco, para fortalecer esta idea
![Logo2](https://github.com/JosuePaiva02/files/blob/main/logos.png?raw=true)

#### Tipografía
Estas son nuestras fuentes elegidas para nuestro producto:

![FontPic!](https://github.com/JosuePaiva02/files/blob/main/typo.png?raw=true)

#### Colores
Como ya establecimos, el color azul es importante para el tipo de aplicación que deseamos crear, sin embargo el azul estándar es muy brillante y molesto en ocasiones, por ello optamos por una alternativa mas oscura acompañado de blanco que le dara un aspecto amigable, limpio y moderno a nuestra interfaz
![Color](https://github.com/JosuePaiva02/files/blob/main/colores.png?raw=true)
#### 4.1.2. Web Style Guidelines
Empezaremos trabajando SmartFinance como una aplicación web, por ello es importante elegir el tipo de diseño correcto para facilitar la experiencia de usuario, por ello elegimos el diseño web adaptable o responsive web en ingles, este diseño permite al usuario tener una experiencia adaptada a la pantalla de su dispositivo, por lo que el usuario podra acceder a nuestra aplicación comodamente tanto en su celular como su PC o Laptop.
### 4.2. Information Architecture
A continuación presentaremos la arquitectura de la aplicación, ordenando primordialmente en tablas el contenido de la misma.
#### 4.2.1. Organization Systems
**Menú de Inicio**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Sección</th>
            <th style="text-align:center">Contenido</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Home</td>
            <td style="text-align: left">En inicio presentamos SmartFinance mencionando nuestra funcion y misión.</td>
        </tr>
        <tr>
            <td>About</td>
            <td style="text-align: left">En About, profundizamos en las herramientas incorporadas en la aplicación, explicando su funcionamiento y propósito.</td>
        </tr>
        <tr>
            <td>Premium</td>
            <td style="text-align: left">En Upgrade el usuario puede conocer las características premium de nuestra aplicación y las diferencias clave con la versión estándar.</td>
        </tr>
        <tr>
            <td>Contacto</td>
            <td style="text-align: left">En esta página incluiremos nuestras redes sociales, asi como un correo de soporte técnico y otro correo de negocios.</td>
        </tr>
        <tr>
            <td>Log In</td>
            <td style="text-align: left">Aqui el usuario podrá iniciar sesión en su cuenta, de no tenerla le ofreceremos la posibilidad de crear una gratuitamente.</td>
        </tr>
    </body>
</table>

##### About
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Sección</th>
            <th style="text-align:center">Contenido</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Sobre Finanzr</td>
            <td style="text-align: left">Explicación sobre la aplicaición, detallando sus features y la funcionalidad de las mismas.</td>
        </tr>
        <tr>
            <td>Sobre SmartFinance</td>
            <td style="text-align: left">Presentamos nuestra startup y nuestro equipo</td>
        </tr>
    </body>
</table>

##### Premium
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Sección</th>
            <th style="text-align:center">Contenido</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Premium</td>
            <td style="text-align: left">Presentación de las suscripciones, sus diferencias, contenido y precios.</td>
        </tr>
        <tr>
            <td>Ventajas de ser Premium</td>
            <td style="text-align: left">Highlight de las principales diferencias de mejorar la cuenta y las diferencias clave con la cuenta estándar</td>
        </tr>
    </body>
</table>

##### Contacto
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Sección</th>
            <th style="text-align:center">Contenido</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Contactanos</td>
            <td style="text-align: left">Información de contacto, siendo un correo de contacto con soporte técnico para clientes, como un correo de contacto para ofertas de negocio</td>
        </tr>
    </body>
</table>

##### log In
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Sección</th>
            <th style="text-align:center">Contenido</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Inicia sesion</td>
            <td style="text-align: left">Pagina de inicio de sesión indicando el correo de la cuenta y la contraseña correspondiente, tambien una opción en la parte inferior para crear una cuenta gratuitamente</td>
        </tr>
    </body>
</table>
<br><br>
<br><br>

#### 4.2.2. Labeling Systems
Los sistemas de etiquetado seran los mismos que presentamos en organization systems, el usuario hara clic en el encabezado que desea navegar y se le redirigira a la sección correspondiente
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Sección</th>
            <th style="text-align:center">Contenido</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Home</td>
            <td style="text-align: left">El usuario iniciara su navegación aqui por default y podra regresar en cualquier momento si decidio cambiar de sección.</td>
        </tr>
        <tr>
            <td>About</td>
            <td style="text-align: left">Informacion sobre nuestra startup y producto.</td>
        </tr>
        <tr>
            <td>Premium</td>
            <td style="text-align: left">Sección que presenta las opciones de suscripción premium y sus mejoras respectivas con respecto a la cuenta estándar.</td>
        </tr>
        <tr>
            <td>Contacto</td>
            <td style="text-align: left">Información de contacto, tanto de soporte como de negocios.</td>
        </tr>
        <tr>
            <td>Log In</td>
            <td style="text-align: left">Inicio de sesión para usuarios registrados, o registro de no estarlo.</td>
        </tr>
    </body>
</table>

#### 4.2.3. SEO Tags and Meta Tags
Para mejorar la visibilidad de la aplicación contamos con SEO tags:

Title: Finzar-Gestiona tus finanzas

Meta Description: Finzar te permitira gestionar tus finanzas personales de manera rapida y eficiente, registra tus gastos, ponte límites y cumple tus objetivos.

Meta Keyowords: finanzas personales. registro de gastos, ahorro, objetivos financieros

Meta Author: SmartFinance
#### 4.2.4. Searching Systems
Para facilitar la navegación cuando se accede a una pestaña que no cuente con la barra de navegación o en caso el usuario la haya desactivado, el usuario cuenta con un botón de búsqueda rápida que ofrece la posibilidad de regresar a home, about,premium y log in. 

#### 4.2.5. Navigation Systems
Para navegar por la aplicación el usuario cuenta con una barra de navegación con todas las secciones clave de nuestro producto: home, about us, premium y log in.
### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
![landing-page-wireframe](assets/LandingPageDesign/finzarLandingPageWireframe.png)
#### 4.3.2. Landing Page Mock-up
![landing-page-mockup](assets/LandingPageDesign/finzarLandingPageMockUp.png)
### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.4. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
La arquitectura de software orientada al dominio proporciona una imagen de lo que se quiere en la estructura de software de nuestro producto. Tal imagen refleja lo que nosotros, Finzar, planteamos para SmartFinance: identificar las funcionalidades de la solución y cómo se van a estructurar adaptándose a los elementos a usar.
#### 4.6.1. Software Architecture Context Diagram
Los elementos presentes son:

* Visitor (Visitante): Visualiza el landing page.
* Client (Cliente): Accede a la aplicación web.
* Administrator (Administrador): Accede a la aplicación web y supervisa su funcionamiento.
* SmartFinance: Software que los usuarios utilizarán.
* Stripe: Software de pago que SmartFinance utilizará.
<br>

![SmartFinance-SystemContext](assets/dsl/structurizr-SystemContext-001.png)
#### 4.6.2. Software Architecture Container Diagrams
Los elementos presentes son:

* Landing Page: Página que presenta el producto.
* Web App: Frontend donde los usuarios interactúan con la aplicación.
* API: Conexión entre el frontend y backend.
* Bounded Contexts: Las funcionalidades que el sistema proporciona a los usuarios.
* Bases de datos: Almacenará datos como cuentas de usuario, reportes, transacciones, ajustes, etc.
<br>

![SmartFinance-Container](assets/dsl/structurizr-Container-001.png)
#### 4.6.3. Software Architecture Components Diagrams
**Account Management**
Los elementos presentes son:
* Controllers: Controlan un conjunto de funcionalidades.
* Managers: Realizan una secuencia para llevar a cabo una acción.
* Repositories: Permiten el acceso a una base de datos o un servicio externo.
![AccountManagement-Component](assets/dsl/structurizr-Component-001.png)

**Transaction Management**
Los elementos presentes son:
* Controller: Controla un conjunto de funcionalidades.
* Managers: Realizan una secuencia para llevar a cabo una acción.
* Repository: Permite el acceso a una base de datos.
![TransactionManagement-Component](assets/dsl/structurizr-Component-002.png)

**Finance Monitoring**
Los elementos presentes son:
* Controller: Controla un conjunto de funcionalidades.
* Configurator: Permite que el usuario realize una configuración de una funcionalidad.
* Exporter: Permite la exportación de un archivo almacenado en la base de datos.
* Observer: Supervisa una funcionalidad, ejecutando una acción si cumple una condición.
* Notifier: Al ser ejecutado, notifica al usuario.
* Repository: Permite el acceso a una base de datos o un servicio externo.
![FinanceMonitoring-Component](assets/dsl/structurizr-Component-003.png)

**Application Personalizer**
Los elementos presentes son:
* Controller: Controla un conjunto de funcionalidades.
* Engine: Mini sistema que retorna resultados después de procesarse.
* Visualizer: Interfaz de una funcionalidad que el usuario puede visualizar
* Personalizer: Funciona como un controller, pero se enfoca en cambiar elementos de la interfaz.
* Repository: Permite el acceso a una base de datos o un servicio externo.
![ApplicationPersonalization-Component](assets/dsl/structurizr-Component-004.png)

### 4.7. Software Object-Oriented Design
El diseño orientado a objetos del software será esencial para nuestro proyecto. Estructuramos nuestro software de acuerdo a nuestras reglas de negocio para poder crear componentes que puedan ser entendibles para su desarrollo en un sistema real, y sean fáciles de modificar para nosotros.
#### 4.7.1. Class Diagrams
![ClassDiagram](assets/software-architecture/finzarClassDiagram.png)
#### 4.7.2. Class Dictionary
<table><tbody>
    <tr>
        <th>Clase</th>
        <th>Nombre de atributo</th>
        <th>Descripción</th>
        <th>Tipo de dato</th>
    </tr>
    <tr>
        <th rowspan="6">Person</th>
        <th>firstName</th>
        <th>Primer nombre del cliente.</th>
        <th>String</th>
    </tr>
    <tr>
        <th>lastName</th>
        <th>Apellido del usuario.</th>
        <th>String</th>
    </tr>
    <tr>
        <th>DNI</th>
        <th>DNI del usuario.</th>
        <th>Int</th>
    </tr>
    <tr>
        <th>address</th>
        <th>Dirección del usuario.</th>
        <th>String</th>
    </tr>
    <tr>
        <th>city</th>
        <th>Ciudad de residencia del usuario.</th>
        <th>String</th>
    </tr>
    <tr>
        <th>birthDate</th>
        <th>Fecha de nacimiento del usuario.</th>
        <th>Date</th>
    </tr>
    <tr>
        <th rowspan="6">Account</th>
        <th>username</th>
        <th>Apodo del usuario</th>
        <th>String</th>
    </tr>
    <tr>
        <th>email</th>
        <th>Correo electrónico del usuario</th>
        <th>String</th>
    </tr>
    <tr>
        <th>password</th>
        <th>Contraseña del usuario</th>
        <th>String</th>
    </tr>
    <tr>
        <th>person</th>
        <th>Persona asociada a la cuenta</th>
        <th>Person</th>
    </tr>
    <tr>
        <th>preference</th>
        <th>Preferencias de la cuenta</th>
        <th>AccountPreferences</th>
    </tr>
    <tr>
        <th>history</th>
        <th>Historial de transacciones de la cuenta</th>
        <th>History</th>
    </tr>
    <tr>
        <th rowspan="2">AccountPreferences</th>
        <th>theme</th>
        <th>Tema de la interfaz</th>
        <th>String</th>
    </tr>
    <tr>
        <th>elementDisplay</th>
        <th>Ajuste de visualización de elementos</th>
        <th>String</th>
    </tr>
    <tr>
        <th>History</th>
        <th>transactions</th>
        <th>Lista de transacciones realizadas por la cuenta</th>
        <th>Transaction[]</th>
    </tr>
    <tr>
        <th rowspan="4">Transaction</th>
        <th>transactionDate</th>
        <th>Fecha de la transacción</th>
        <th>Date</th>
    </tr>
    <tr>
        <th>amount</th>
        <th>Monto de la transacción</th>
        <th>Double</th>
    </tr>
    <tr>
        <th>type</th>
        <th>Tipo de transacción</th>
        <th>String</th>
    </tr>
    <tr>
        <th>category</th>
        <th>Categoría de la transacción</th>
        <th>Category</th>
    </tr>
    <tr>
        <th>Category</th>   
        <th>categoryName</th>
        <th>Nombre de la categoría</th>
        <th>String</th>
    </tr>
    <tr>
        <th rowspan="2">Report</th>
        <th>format</th>
        <th>Formato del reporte</th>
        <th>String</th>
    </tr>
    <tr>
        <th>dateGenerated</th>
        <th>Fecha de generación</th>
        <th>Date</th>
    </tr>
    <tr>
        <th>Recommendation</th>
        <th>keywords</th>
        <th>Palabras claves para la generación.</th>
        <th>String[]</th>
    </tr>
    <tr>
        <th rowspan="3">Repository</th>
        <th>totalIncome</th>
        <th>Ingreso total del usuario.</th>
        <th>Double</th>
    </tr>
    <tr>
        <th>totalExpense</th>
        <th>Gasto total del usuario.</th>
        <th>Double</th>
    </tr>
    <tr>
        <th>currentMoney</th>
        <th>Dinero actual del usuario.</th>
        <th>Double</th>
    </tr>
    <tr>
        <th rowspan="2">Budget</th>
        <th>limitAmount</th>
        <th>Monto límite establecido por el usuario.</th>
        <th>Double</th>
    </tr>
    <tr>
        <th>dateStart</th>
        <th>Fecha de establecimiento del límite.</th>
        <th>Date</th>
    </tr>
    <tr>
        <th>Notification</th>
        <th>message</th>
        <th>Mensaje generado para la notificación.</th>
        <th>String</th>
    </tr>
</tbody></table>

### 4.8. Database Design
El diseño de la base de datos será fundamental para nuestro proyecto, ya que proporcionará la estructura subyacente para almacenar y gestionar los datos de manera eficiente y segura. Esto nos permitirá organizar los datos de manera lógica y coherente, facilitando su recuperación y manipulación en respuesta a las solicitudes de los usuarios.
![Database](assets/software-architecture/finzarDB.jpg)
#### 4.8.1. Database Diagram


## Capítulo V: Product Implementation, Validation & Deployment <a id="cap5"></a>

### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration

* ### Project Management
    * ### Trello
    Plataforma de gestión de proyectos que permite seguir el proceso de las tareas a desarrollar.

    [[Link de la herramienta]](https://trello.com/)

    Imagen de evidencia de uso:

    ![trello-evidence](/assets/environment-images/trello.jpg)

* ### Requirement Management
    * ### UXPressia

    Herramienta en linea que ayuda en el proceso de mapeo. En este proyecto ha sido utilizado para el Impact Mapping.

    [[Link de la herramienta]](https://uxpressia.com/)

    Imagen de evidencia de uso:

    ![uxpressia-evidence](/assets/environment-images/uxpressia.jpg)

    * ### Structurizr

    Herramienta que facilita la creación de modelos C4 para representar de forma gráfica la estructura del producto.

    [[Link de la herramienta]](https://www.structurizr.com/)

    Imagen de evidencia de uso:

    ![structurizr-evidence](/assets/environment-images/structurizr.jpg)

* ### Product UX/UI Design
    * ### Figma

    Plataforma colaborativa de diseño que facilita la creación de wireframes y mockups para la landing page.

    [[Link de la herramienta]](https://www.figma.com/)

    ![figma-evidence](/assets/environment-images/figma.jpg)

* ### Software Development
    * ### HTML
    Lenguaje de etiquetado utilizado para crear la estructura de páginas web.

    Imagen de evidencia de uso:

    ![html-evidence](/assets/environment-images/html-evidence.jpg)

    * ### CSS
    Lenguaje de diseño gráfico usado para dar formato y estilo a la página web escrita en HTML

    Imagen de evidencia de uso:

    ![css-evidence](/assets/environment-images/css-evidence.jpg)

    * ### JavaScript
    Lenguaje de programación orientado a objetos. Utilizado para definir el comportamiento de la página web e implementar funcionalidades.

    Imagen de evidencia de uso:

    ![javascript-evidence](/assets/environment-images/javascript-evidence.jpg)

* ### Software Testing
    * ### Gherkin Language
    Lenguaje específico de dominio (DSL) diseñado para ser comprensible para los desarrolladores y utilizado definir tests de aceptación.

    [[Más información]](https://cucumber.io/docs/gherkin/reference/)

    Imagen de evidencia de uso:

    ![gherkin-evidence](/assets/environment-images/gherkin-evidence.jpg)

* ### Software Documentation
    * ### Github
    Plataforma utilizada para alojar multiples versiones del código fuente de un proyecto. Muy popular en el trabajo colaborativo entre programadores.

    [[Link de la página]](https://github.com/)

    Imagen de evidencia de uso:

    ![github-evidence](/assets/environment-images/github.jpg)

* ### Software Deployment
    * ### Github Pages
    Servicio de Github que permite la realización de despliegues simples desde un repositorio.

#### 5.1.2. Source Code Management

Landing Page Repository: [Landing Page Repository](https://github.com/SmartFinance-OpenSource/Landing-Page/tree/develop)

* Gitflow Implementation
Implementamos el flujo de trabajo Gitflow a través de ramas(branches) para separar el desarrollo en paralelo de diversas secciones del proyecto.

![gitflow](/assets/environment-images/gitflow.jpg)

### **Main branch**
La rama principal de desarrollo del proyecto es la Main branch. En esta rama reside el código que actualmente se encuentra en producción.

#### Notación: main

### **Develop branch**
La rama "Develop" albergará las más recientes actualizaciones y cambios agregados que serán incluidos en la próxima versión del proyecto. Esta rama sirve como un espacio para la prueba continua de los cambios antes de ser fusionados con la rama principal "Main" para su posterior despliegue.

#### Notación: develop

### **Release branch**
La rama de lanzamiento (Release branch) facilitará la preparación de una nueva versión del producto. Esta rama permitirá la corrección de errores y permitirá que la rama Develop reciba más actualizaciones.

#### Notación: release

### **Conventional Commits**
"Conventional Commits" es una convención para estructurar los mensajes de confirmación (commits) en un formato estándar y semántico. Este formato ayuda a comunicar claramente los cambios realizados en el código y facilita la generación de registros de cambios automáticos. Los "Conventional Commits" suelen seguir un formato que incluye un encabezado, un cuerpo opcional y un pie de página opcional, y se utilizan para describir de manera sucinta y clara los cambios realizados en el código, lo que facilita su seguimiento y comprensión por parte de los desarrolladores y otros miembros del equipo.
<br>
La estructura de un commit debe seguir las siguientes pautas:
~~~
git commit -m “<type>[optional scope]: <title>“ -m “<description”
~~~
**Tipos De Conventional Commits**
~~~
1. feat: Used to describe a new feature or functionality added to the code.
2. fix: Indicates a bug fix or solution to a problem.
3. docs: Employed for changes or improvements in code documentation.
4. style: Describes changes related to the code's formatting, such as whitespace, indentation, etc., that do not affect its functionality.
5. refactor: Used for modifications to the code that do not fix bugs or add new features, but rather improve its structure or readability.
6. test: Indicates the addition or modification of unit tests or functional tests.
7. chore: Used for changes in the build process or maintenance tasks that are not directly related to the code itself.
8. perf: Describes performance improvements in the code.
~~~

#### 5.1.3. Source Code Style Guide & Conventions

- ### HTML 
    - #### Use Lowercase Element Names:
        Es recomendable utilizar minúsculas o lowercase para los nombres de los elementos HTML.
        ~~~ 
      <body>
            <p>This is a paragraph</p>
      <body>
       ~~~
    - #### Close All HTML Elements:
        Es recomendable cerrar todos los elementos HTML correctamente.
        ~~~ 
      <body>
            <p>This is a paragraph</p>
            <p>This is another paragraph</p>
      <body>
       ~~~
    - #### Use Lowercase Attribute Names:
        Es recomendable utilizar minúsculas para los nombres de los atributos HTML.
      ~~~ 
      <a href="https://www.w3schools.com/html/">Visit our HTMLtutorial</a>
       ~~~
    - #### Always Specify alt, width, and height for Images:
      Es recomendable seguir estas convenciones en caso de que la imagen no se pueda mostrar, lo que ayuda a mejorar la accesibilidad del contenido.
      ~~~ 
      <img src="html5.gif" alt="HTML5" 
      style="width:128px;height:128px">
      ~~~ 
    - #### Spaces and Equal Signs:
      Se recomienda no utilizar espacios en blanco entre las entidades para mejorar la legibilidad.
      ~~~ 
      <link rel="stylesheet" href="styles.css">
      ~~~ 
- ### CSS
    - #### ID and Class Naming
      Es recomendable utilizar nombres de clases e id's significativos que expresen claramente el propósito del elemento.
      ~~~ 
      #gallery {}
      #login {}
      .video {}
       ~~~
    - #### ID and Class Name Style
      Se recomienda utilizar nombres cortos para nombrar ids o clases, pero lo suficientemente descriptivos para entender su propósito.
      ~~~ 
      #nav {}
      .author {}
      ~~~
    - #### Shorthand Properties
      Se recomienda utilizar propiedades CSS de forma abreviada siempre que sea posible para hacer el código más eficiente y comprensible.
       ~~~ 
       border-top: 0;
       font: 100%/1.6 palatino, georgia, serif;
       padding: 0 1em 2em;
       ~~~ 
    - #### 0 and Units
      Es recomendable evitar especificar la unidad después del valor 0 en propiedades que lo permitan, ya que esto ayuda a reducir el tamaño del código y mejora su legibilidad.
       ~~~ 
       margin: 0;
       padding: 0;
       ~~~
     - #### Declaration Order
       Se recomienda ordenar las declaraciones en orden alfabético para facilitar el mantenimiento y la recordación del código.
       ~~~ 
        background: fuchsia;
        border: 1px solid;
        border-radius: 4px;
        color: black;
        text-align: center;
        text-indent: 2em;
       ~~~  
- ### JAVASCRIPT
     - #### Use expanded syntax
       Cada línea de JavaScript debería estar en una nueva línea, con la llave de apertura en la misma línea de su declaración y la llave de cierre en una nueva línea al final.
       ~~~ 
       function myFunc() {
        console.log('Hello!');
       };
       ~~~
     - #### Variable naming
       Para el nombre de las variables, se recomienda utilizar lowerCamelCase. 
       ~~~ 
       let playerScore = 0;
       let speed = distance / time;
       ~~~  
     - #### Declaring variables
       Para la declaración de variables, es recomendable utilizar las palabras reservadas let y const en lugar de var.
       ~~~ 
       const myName = 'Chris';
       console.log(myName);
       let myAge = '40';
       myAge++;
       console.log('Happy birthday!');
       ~~~ 
     - #### Function naming
       Para el nombre de las funciones, se recomienda utilizar lowerCamelCase.
       ~~~ 
       function sayHello() {
       alert('Hello!');
       };
       ~~~ 
- ### LENGUAJE GHERKIN
    - #### Descriptive and concise titles for scenarios
      Utilizar títulos descriptivos y concisos para los escenarios.
      ~~~ 
      Feature: Login
        Scenario: Successful login
          Given a user is on the login page     
          When they enter valid credentials     
          Then they should be logged in successfully      
      ~~~
    - #### Follow the Given-When-Then structure consistently.
      Seguir la estructura de Given-When-Then de manera consistente.
      ~~~ 
      Scenario: Adding items to the shopping cart
        Given the user is on the shopping page
        When they add an item to the cart
        Then the item should appear in the cart 
      ~~~
    - #### Focus on business-readable language
      Centrarse en un lenguaje legible para el negocio, evitando detalles técnicos de implementación.
      ~~~ 
      Scenario: Changing user settingst
        Given the user is logged in
        When they navigate to the settings page
        Then they should be able to update their profile
      ~~~
    - ####  Utilize Scenario Outline for scenarios with multiple similar cases.
      Utilizar Scenario Outline para escenarios con múltiples casos similares.
      ~~~ 
      Scenario Outline: Searching for products
        Given the user is on the search page
        When they search for "<product>"
        Then they should see search results for "<product>"
      
      Examples:
        | product  |
        | Laptop   |
        | Smartphone |
      ~~~
    - #### Add comments to provide additional context
      Agregar comentarios para proporcionar contexto adicional o explicaciones cuando sea necesario.
      ~~~ 
      # This scenario checks the functionality of the logout feature
      Scenario: User logout
        Given the user is logged in
        When they click on the logout button
        Then they should be redirected to the login page      
      ~~~

#### 5.1.4. Software Deployment Configuration

### Creación de la Landing Page

1. Creación de repositorio de la Landing Page.

![landing-page-repository](/assets/deployment-images/landing-page-repository.jpg)

2. Habilitar Github Pages para el despliegue.

![github-pages-repository](/assets/deployment-images/github-pages.jpg)

### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1

<table>
  <tr>
    <td colspan="1"><strong>Sprint #</strong></td>
    <td colspan="1">1</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Sprint Planning Background</strong></td>
  </tr>
  <tr>
    <td colspan="1"><strong>Date</strong></td>
    <td colspan="1">2024-09-02</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Time</strong></td>
    <td colspan="1">1:00 PM</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Location</strong></td>
    <td colspan="1">Virtual - Google Meet</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Prepared by</strong></td>
    <td colspan="1">Juan Astonitas</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Attendees (to planning meeting)</strong></td>
    <td colspan="1">Juan Astonitas, Sebastián Real, Gianluca Pasquale, Josue Paiva, Sebastián Pacheco</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Sprint n – 1 Review Summary</strong></td>
    <td colspan="1">Se realizó la landing page, implementada con css y html, con base en los mockups y wireframes del diseño realizado en figma y siguiendo los style guidelines.</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Sprint n – 1 Retrospective Summary</strong></td>
    <td colspan="1">Mejorar la organización y el trabajo en grupo.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Sprint Goal & User Stories</strong></td>
  </tr>
  <tr>
    <td colspan="1"><strong>Sprint 1 Goal</strong></td>
    <td colspan="1">Implementar la landing page y prepararla para presentar el producto adecuadamente a los visitantes. Esto ayudará a captar su atención e informarlos sobre las funcionalidades de nuestra aplicación.</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Sprint 1 Velocity</strong></td>
    <td colspan="1"> 25 Story Points.</td>
  </tr>
  <tr>
    <td colspan="1"><strong>Sum of Story Points</strong></td>
    <td colspan="1"> 18 Story Points atendidos. </td>
  </tr>
</table>

##### 5.2.1.2. Sprint Backlog 1

Para el primer sprint, desarrollamos la estructura y las funcionalidades básicas de la landing page, así como el diseño visual y la barra de navegación.

<table>
  <tr>
    <td colspan="1"><strong>Sprint #</strong></td>
    <td colspan="7"><strong>Sprint 1</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>User Story</strong></td>
    <td colspan="6"><strong>Work-Item/task</strong></td>
  </tr>
  <tr>
    <td colspan="1"><strong>Id</strong></td>
    <td colspan="1"><strong>Title</strong></td>
    <td colspan="1"><strong>Id</strong></td>
    <td colspan="1"><strong>Title</strong></td>
    <td colspan="1"><strong>Description</strong></td>
    <td colspan="1"><strong>Estimation(Hrs)</strong></td>
    <td colspan="1"><strong>Assigned To</strong></td>
    <td colspan="1"><strong>Status</strong></td>
  </tr>
  <tr>
    <td colspan="1">US01</td>
    <td colspan="1">Registro de Usuario</td>
    <td colspan="1">T01</td>
    <td colspan="1">Crear un sistema de registro de usuarios.</td>
    <td colspan="1">La página web debe tener una opción para que los usuarios creen una cuenta.</td>
    <td colspan="1">0.5</td>
    <td colspan="1">Juan Astonitas</td>
    <td colspan="1">Done</td>
  </tr>
  <tr>
    <td colspan="1">US02</td>
    <td colspan="1">Inicio de Sesión</td>
    <td colspan="1">T02</td>
    <td colspan="1">Crear un sistema de inicio de sesión para usuarios registrados.</td>
    <td colspan="1">La página web debe permitir a los usuarios registrados el ingresar sus datos para acceder a sus cuentas.</td>
    <td colspan="1">0.5</td>
    <td colspan="1">Juan Astonitas</td>
    <td colspan="1">Done</td>
  </tr>
</table>

##### 5.2.1.3. Development Evidence for Sprint Review

| Repository          | Branch  | Commit ID                                | Commit Message                           | Commit Message Body                                                                                                                                 | Commited on (Date) |
|---------------------|---------|------------------------------------------|------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|
| SmartFinance-OpenSource/Landing-Page | develop | 464433d | feat: add landing page images |  | 08/09/2024  |
| SmartFinance-OpenSource/Landing-Page | develop  | 8bd63b6 | feat: added first version landing page |  | 08/09/2024 |

##### 5.2.1.4. Testing Suite Evidence for Sprint Review

Se omite esta sección, dado que aún no se tiene el conocimiento necesario para realizar pruebas automatizadas. Esto se llevara a cabo en futuros sprints.

##### 5.2.1.5. Execution Evidence for Sprint Review

En esta entrega, nuestro equipo ha desplegado con éxito la landing page.

![landing-page-1](/assets/landing-page-screenshots/1.jpg)
![landing-page-2](/assets/landing-page-screenshots/2.jpg)
![landing-page-3](/assets/landing-page-screenshots/3.jpg)

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

Se omite esta sección ya que aún no contamos con Web Application, la cual se desarrollará en Sprints futuros.

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

Se omite esta sección ya que actualmente no contamos con una Front End App, ya que esta se implementará en Sprints futuros.

##### 5.2.1.8. Team Collaboration Insights during Sprint

A continuación, se muestra la página de insights proporcionada por Github.

![github-insights](/assets/githubpics/insights_cap1.jpg)

## Conclusiones

- A lo largo del desarrollo de Finzar, se ha identificado y comprendido a fondo a su segmento objetivo: jóvenes adultos peruanos, incluyendo estudiantes universitarios y jóvenes profesionales. Esta comprensión ha permitido adaptar la herramienta para abordar problemas específicos como el sobreendeudamiento y la falta de ahorro, ofreciendo soluciones prácticas y accesibles que mejoran la estabilidad económica y promueven buenos hábitos financieros desde edades tempranas.

- En la evaluación de competidores, Finzar ha demostrado tener ventajas significativas al enfocarse en las necesidades locales y específicas del mercado peruano. A diferencia de otras aplicaciones financieras, Finzar no solo gestiona ingresos y gastos, sino que también prioriza la educación financiera y la personalización del servicio, lo cual la posiciona como una herramienta diferenciada y valiosa en un mercado competitivo.

- A lo largo del proceso, se ha resaltado la importancia de adaptar Finzar a las condiciones y contextos peruanos, lo que incluye desde la integración con bancos locales hasta la alineación con los hábitos y retos financieros específicos de los jóvenes peruanos. Esta adaptación no solo mejora la usabilidad de la aplicación, sino que también la hace más relevante y efectiva para su audiencia objetivo.

- El diseño y la ejecución de entrevistas han sido fundamentales para validar las necesidades y preferencias del segmento objetivo de Finzar. Esta metodología de acercarse a los usuarios reales ha permitido recopilar información valiosa que asegura que la herramienta esté alineada con las expectativas del mercado, fortaleciendo su propuesta de valor y guiando futuras mejoras en el desarrollo del producto.

## Bibliografía

- INEI [Instituto Nacional de Estadística e Informática]. (2023, 11 mayo). *Pobreza monetaria afectó al 27,5% de la población del país en el año 2022*. Recuperado 23 de agosto de 2024, de [https://m.inei.gob.pe/prensa/noticias/pobreza-monetaria-afecto-al-275-de-la-poblacion-del-pais-en-el-ano-2022-14391/](https://m.inei.gob.pe/prensa/noticias/pobreza-monetaria-afecto-al-275-de-la-poblacion-del-pais-en-el-ano-2022-14391/)

## Anexos
