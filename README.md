<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br><img src="https://www.upc.edu.pe/static/img/logo_upc_red.png"></img><br>
    <br>
    <strong>Ingeniería de Software - 2025-01</strong><br>
    <br>
    <strong>1ASI0572 - Desarrollo de Soluciones IoT - 2942</strong><br>  
    <br>
    <strong>Profesor: Marco Antonio León Baca</strong><br>
    <br> <strong>INFORME DE TB1</strong> 
</p>
<p align="center">
    <strong>Startup: AgroSense</strong><br>
    <strong>Producto: NutriControl</strong>
</p>

<h3 align="center" >Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Miembro</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Criollo De La Cruz, Diego Anderson</td>
            <td>U202219639</td>
        </tr>
        <tr>
            <td>Antonio Salazar, Jhan Clinton</td>
            <td>U20201B312</td>
        </tr>
        <tr>
            <td>Espinoza Saenz, Christian Renato</td>
            <td>U202213208</td>
        </tr>
        <tr>
            <td>Morales Calderón, Hernan Emilio</td>
            <td>U202216263</td>
        </tr>
        <tr>
            <td>Valle Zuta, Abel Andrés</td>
            <td>U202210297</td>
        </tr>
    </table>
</div>
<br>
<p align="center">
    <strong>ABRIL 2025 </strong>
</p>
<br>

---

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

<div align="center">

| Versión |   Fecha    | Autor | Descripción de modificación | 
|:-------:|:----------:|:-----:|:----------------------------| 
|TB1| 20/04/2025 |Criollo De La Cruz, Diego Anderson| Capítulo I: Introducción, Capítulo II: Requirement Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Solution Software Design |
|TB1| //2025 || |
|TB1| 20/04/2025 |Espinoza Saenz, Christian Renato| Capítulo I: Introducción, Capítulo II: Requirement Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Solution Software Design |
|TB1| 20/04/2025 |Morales Calderón, Hernan Emilio| Capítulo I: Introducción, Capítulo II: Requirement Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Solution Software Design |
|TB1| 20/04/2025 |Valle Zuta, Abel Andrés| Capítulo I: Introducción, Capítulo II: Requirement Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Solution Software Design |

</div>

---

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights

<div align="justify">



</div>

<div style="page-break-after: always;"></div>

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome)
### [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-&-analysis)
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

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
        - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
        - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
        - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
        - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
        - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
        - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
        - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: <Bounded Context Name>](#421-bounded-context-1)
        - [4.2.1.1. Domain Layer](#4211-domain-layer)
        - [4.2.1.2. Interface Layer](#4212-interface-layer)
        - [4.2.1.3. Application Layer](#4213-application-layer)
        - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
        - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
            - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

### [Conclusiones](#conclusiones)
### [Bibliografía](#bibliografía)
### [Anexos](#anexos)
---
<div style="page-break-after: always;"></div>

# Student Outcome

**ABET – EAC – Student Outcome 5**

<div align="justify">
    Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.<br>

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.
</div>    

<div align="justify">
</div>    

<div align="justify">
<table>
  <tr>
    <th>Criterio Específico</th>
    <th>Acciones Realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Trabaja en equipo para proporcionar liderazgo en forma conjunta.</td>
    <td>
      <strong>TB1:</strong><br><br>
      Criollo de la Cruz, Diego Anderson<br>
      En el desarrollo del TB1, asumí un rol activo dentro del equipo encargándome principalmente de la elaboración de la documentación técnica y la corrección de errores en el desarrollo general del proyecto. Estas tareas me permitieron no solo aportar a la     
      organización y claridad del trabajo en grupo, sino también apoyar a mis compañeros identificando y solucionando problemas técnicos de manera colaborativa. Considero que, a través de estas acciones, contribuí al liderazgo conjunto del equipo, asegurando que 
      avanzáramos de forma coordinada hacia los objetivos planteados.
      <br><br>
      Espinoza Saenz, Christian Renato<br>
      Durante la implementación del software como propuesta de solución para la problemática encontrada, asumí la responsabilidad de coordinar las sesiones de trabajo y distribuir tareas equitativamente. Esto incluyó planificar reuniones, moderar discusiones y asegurar que cada integrante tuviera claridad sobre sus objetivos. Esta experiencia no solo fortaleció el liderazgo compartido, sino que también promovió un ambiente de trabajo inclusivo y eficiente.
      <br><br>
      Morales Calderón, Hernan Emilio<br>
      Durante este TB1, desempeñé un rol de liderazgo rotativo, donde alterné responsabilidades con mis compañeros para garantizar una toma de decisiones equitativa. Mi enfoque se centró en la gestión del tiempo y la priorización de tareas críticas, lo que permitió al equipo completar con éxito el primer alcance del proyecto dentro del plazo establecido, fomentando la confianza mutua y la colaboración.
      <br><br>
      Valle Zuta, Abel Andrés<br>
      En la primera entrega del presente proyecto, lideré la organización de un cronograma semanal que permitió al equipo balancear sus responsabilidades. También proporcioné retroalimentación sobre avances individuales, promoviendo una dinámica de aprendizaje grupal y asegurando que el liderazgo se ejerciera de manera conjunta, enfocándonos siempre en cumplir los objetivos establecidos.
    </td>
    <td>
      <strong>TB1:</strong><br><br>
      La experiencia acumulada durante el desarrollo del TB1 refleja un compromiso sólido con el liderazgo compartido y el trabajo en equipo. A través de roles diversos como la documentación técnica, la coordinación de tareas, la moderación de discusiones, y la gestión del tiempo, se promovió un ambiente de colaboración inclusivo y eficiente. Estas acciones no solo garantizaron el cumplimiento de los objetivos del proyecto dentro de los plazos establecidos, sino que también fortalecieron la comunicación, la confianza mutua y el aprovechamiento de las fortalezas individuales de los integrantes. En conjunto, estas contribuciones destacaron la importancia de un liderazgo rotativo y equitativo para alcanzar resultados exitosos.
    </td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
    <td>
      <strong>TB1:</strong><br><br>
      Criollo de la Cruz, Diego Anderson<br>
      Durante el desarrollo del TB1, me encargué de redactar la documentación del proyecto, asegurándome de que la información técnica estuviera presentada de forma clara, ordenada y objetiva. Me enfoqué en que los resultados y decisiones del equipo pudieran ser 
      comprendidos tanto por personas con formación técnica como por aquellas de otras áreas. Esta experiencia me permitió mejorar mi capacidad de comunicar ideas por escrito de manera efectiva, adaptando el lenguaje según el público y manteniendo siempre un enfoque 
      profesional y comprensible para todos los niveles jerárquicos involucrados.
      <br><br>
      Espinoza Saenz, Christian Renato<br>
      Durante este primer avance, elaboré un informe técnico que resumía los avances y resultados del proyecto. Este documento estaba estructurado para ser comprensible tanto para los miembros técnicos del equipo como para la dirección general. Me enfoqué en utilizar un lenguaje preciso y acompañar la explicación con gráficos y tablas que facilitaran la comprensión, asegurando que el mensaje fuera claro para todos los destinatarios.
      <br><br>
      Morales Calderón, Hernan Emilio<br>
      Como parte de esta primera entrega, preparé una presentación escrita para los stakeholders del proyecto, detallando las metodologías empleadas, los resultados obtenidos y las recomendaciones futuras. Adapté el contenido según las necesidades del público, utilizando un lenguaje accesible para personas sin conocimientos técnicos y terminología especializada para quienes requerían un mayor nivel de detalle técnico.
      <br><br>
      Valle Zuta, Abel Andrés<br>
      Durante la primera entrega del presente proyecto, lideré la elaboración del reporte del proyecto que contiene los puntos clave del proyecto, la arquitectura que este tendrá y el alcance que planeamos para el software. Utilicé diagramas y esquemas para complementar el texto, garantizando que tanto aspectos técnicos como estratégicos fueran entendidos por audiencias con diferentes especialidades y roles jerárquicos.
    </td>
    <td>
      <strong>TB1:</strong><br><br>
      En este primer avance del proyecto, logramos trabajar en diferentes entornos colaborativos e inclusivos, elaborando diversos documentos técnicos y presentaciones adaptadas a diferentes audiencias con el fin de cumplir las metas establecidas. Nos aseguramos de que la información estuviera estructurada de manera clara, utilizando gráficos, tablas y esquemas para facilitar la comprensión de los aspectos técnicos y estratégicos. Esta experiencia no solo fortaleció nuestra capacidad para redactar contenidos accesibles tanto para especialistas como para personas de otras áreas, sino que también consolidó la habilidad para transmitir ideas complejas de manera profesional y efectiva, asegurando que todos los niveles jerárquicos involucrados comprendieran el alcance, las metodologías y los resultados del proyecto.
    </td>
  </tr>
</table>


</div>

<div style="page-break-after: always;"></div>


# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
<div align="justify">
    AgroSense es una startup enfocada en transformar radicalmente el sector agroindustrial mediante el diseño e implementación de soluciones tecnológicas inteligentes. Con un enfoque innovador en la agricultura de precisión, la automatización de procesos y el aprovechamiento del Internet de las Cosas (IoT), desarrollamos herramientas avanzadas que permiten monitorear, analizar y actuar sobre variables críticas del entorno agrícola, como el clima, la humedad del suelo, el estado de los cultivos y otros factores determinantes, todo ello con el fin de maximizar la eficiencia productiva, reducir el uso innecesario de insumos y promover una toma de decisiones basada en datos reales y en tiempo real. En AgroSense creemos en una agricultura conectada, sostenible y centrada en el bienestar del productor, por lo que buscamos democratizar el acceso a la tecnología agro-inteligente, permitiendo que productores de todos los tamaños gestionen sus cultivos desde cualquier lugar y en cualquier momento. Nuestra visión del futuro agrícola es clara: un ecosistema donde cada hectárea cultivada represente una oportunidad para producir más con menos impacto ambiental, donde cada decisión esté respaldada por datos y donde la tecnología sea una aliada estratégica frente a los desafíos del cambio climático y la seguridad alimentaria global.
    <br><br>
    
  <div align="center">

  <div align="center">

  ![AgroSense](Resources/Chapter%2001/Startup%20Logo/AgroSense-Logo.png)

  </div>

  </div>

</div>
<div align="justify">
    <ul>
        <li>
            <b>Misión:</b>
        </li> 
Impulsar la transformación profunda del sector agroindustrial a través de soluciones tecnológicas innovadoras, accesibles y sostenibles que permitan a los agricultores monitorear, analizar y actuar con precisión sobre sus cultivos. 
	    <br><br>
	<li>
            <b>Visión:</b>
        </li>
Ser líderes globales en innovación agroindustrial, reconocidos por transformar la manera en que se cultiva la tierra mediante tecnologías que integran inteligencia, automatización y sostenibilidad. Aspiramos a construir un ecosistema agrícola más eficiente, transparente y conectado.
    </ul>
<br>
</div>

<div style="page-break-after: always;"></div>

### 1.1.2. Perfiles de integrantes del equipo

### Los integrantes que conforman parte de nuestro startup son:
<div align="justify">

| Integrante                | Perfil                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Foto                                                |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|
| Criollo De La Cruz, Diego Anderson (U202219639) | Mi nombre es Diego Anderson Criollo de La Cruz, soy estudiante de 7mo ciclo de la carrera de Ingeniería de Software. Me gusta mucho emplear soluciones creativas y que busquen eficiencia para poder abordar de esta forma cualquier desafío de la mejor manera. Como miembro del grupo, pretendo aportar con todos mis conocimientos en el desarrollo web tanto como en el front-end y back-end, además de siempre colaborar con mis ideas y soluciones ante cualquier dificultad que se presente en el desarrollo. Espero poder aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del desarrollo del proyecto.                                                                                             | ![Diego Criollo](Resources/Chapter%2001/Team%20Members/Criollo-Diego.jpg)             |
|  |                                                                                                                                                                                       | ![]()               |
| Morales Calderón, Hernan Emilio (U202216263) | Soy Hernan Morales, tengo 20 años y actualmente estoy cursando el 7mo ciclo de Ingeniería de Software. Me considero una persona sumamente responsable y organizada, especialmente en trabajos universitarios. Mi objetivo es culminar exitosamente el curso y nuestro proyecto junto a mi equipo, asegurando que cada detalle se ejecute con precisión. Tengo conocimientos sólidos en lenguajes como C++, C#, y JavaScript, así como en frameworks como Angular y Vue, lo que me permite desarrollar interfaces dinámicas y adaptarme rápidamente a diferentes entornos de desarrollo. Además, manejo SQL para la gestión y optimización de bases de datos. Estoy convencido de que, con buena planificación y comunicación, entregaremos un proyecto de alta calidad que supere las expectativas. | ![Hernan Morales](Resources/Chapter%2001/Team%20Members/Morales-Hernan.png)             |
| Valle Zuta, Abel Andrés (U202210297) | Soy Abel Andrés Valle Zuta, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), tengo 20 años y actualmente estoy cursando el 7mo ciclo en la sede de Monterrico. Sé programar y editar videos. Además, sé resolver problemas, trabajar en equipo y lograr unir más al grupo. Mis hobbies son jugar básquet, fútbol, tenis, videojuegos, escuchar música, salir a pasear con mis amigos, ver películas, nadar, hacer ejercicio, pasear a mis mascotas y pasar tiempo con mi familia. Finalmente, siempre estoy dispuesto a trabajar y terminar a tiempo los deberes, esforzándome para aprender y comprender lo máximo posible y finalizar con éxito todos mis objetivos.                                                                     | ![Abel Valle](Resources/Chapter%2001/Team%20Members/Valle-Abel.jpg)               |
| Espinoza Saenz, Christian Renato (U202213208) | Mi nombre es Christian Espinoza, soy un estudiante de 20 años que cursa el 7mo ciclo de la carrera Ingeniería de Software. Poseo ideas únicas e innovadoras para que el trabajo logre sobresalir. Tengo experiencia en la creación de distintos tipos de diagramas, editar diferentes tipos de multimedia como videos, y un conocimiento general en programación de C++, HTML, CSS y SQL. Además, se me facilita desarrollar interfaces intuitivas en el frontend, lo cual será beneficioso para el proyecto.                                                                    | ![Christian Espinoza](Resources/Chapter%2001/Team%20Members/Christian-Espinoza.jpg)               |

</div>

<div style="page-break-after: always;"></div>

## 1.2. Solution Profile

**Product Name:** NutriControl

<div align="justify">

**Producto Descriptivo:**  NutriControl es una solución tecnológica integral desarrollada por AgroSense para optimizar el proceso de fertilización agrícola. Diseñada especialmente para pequeños y medianos productores en Sudamérica, esta plataforma combina sensores inteligentes con automatización de riego por goteo, permitiendo medir en tiempo real variables críticas del suelo como el pH, la humedad y los niveles de nutrientes. A partir de estos datos, NutriControl toma decisiones autónomas para activar el sistema de riego solo cuando el cultivo lo necesita, garantizando una aplicación precisa de agua y fertilizantes. La plataforma incluye una interfaz web y una aplicación móvil que ofrecen monitoreo en tiempo real, alertas personalizadas, reportes detallados y recomendaciones adaptadas a las condiciones de cada terreno. De esta forma, NutriControl mejora la eficiencia del uso de insumos, aumenta el rendimiento de los cultivos y contribuye a una agricultura más sostenible y resiliente frente al cambio climático y la escasez hídrica.

**Monetización:**  NutriControl adoptará un modelo de monetización accesible y escalable, pensado especialmente para pequeños y medianos agricultores. La plataforma ofrecerá un modelo *freemium*, donde los usuarios podrán acceder gratuitamente a funciones básicas de monitoreo, alertas y visualización de datos desde la aplicación móvil o web. Para quienes deseen funcionalidades adicionales como reportes históricos, análisis predictivos y recomendaciones personalizadas, se ofrecerán planes de suscripción mensual de bajo costo, con tarifas ajustadas al tamaño del terreno o número de sensores instalados.

</div>


![Solution Profile](Resources/Chapter%2001/Solution%20Profile/Reference.jpg)

### 1.2.1. Antecedentes y problemática

<div align="justify">
En el contexto agrícola de Sudamérica, y particularmente en Perú, los productores enfrentan una combinación de desafíos estructurales y emergentes que afectan profundamente la eficiencia y sostenibilidad del sector. Uno de los problemas más urgentes es la escasez de agua: según el Centro Nacional de Planeamiento Estratégico (Ceplan), se estima que para el año 2030 más del 58% de la población peruana vivirá en zonas con estrés hídrico, mientras regiones como Piura ya se encuentran en estado de emergencia por déficit hídrico. Esta crisis compromete gravemente la capacidad de riego de los cultivos y exige una gestión más eficiente del agua. A ello se suma el incremento sostenido en los precios de los fertilizantes, cuya importación anual en Perú supera el millón de toneladas y ha alcanzado un valor de más de 800 millones de dólares, impulsado por factores como la pandemia, los conflictos geopolíticos y las limitaciones en la cadena de suministro global. Este aumento ha afectado especialmente a pequeños y medianos productores, reduciendo sus márgenes de ganancia y dificultando el acceso a insumos esenciales. Por otro lado, la agricultura peruana aún presenta una marcada brecha tecnológica: mientras los grandes productores comienzan a incorporar tecnologías de precisión, la mayoría de agricultores no cuenta con herramientas que les permitan monitorear en tiempo real variables clave como la humedad, el pH del suelo o la disponibilidad de nutrientes, lo que limita su capacidad para tomar decisiones informadas frente a condiciones climáticas cada vez más impredecibles.
<br><br>
En respuesta a estos desafíos, AgroSense presenta NutriControl, una solución tecnológica integral que automatiza el proceso de fertilización mediante sensores inteligentes capaces de medir en tiempo real variables críticas del suelo como el pH, la humedad y los niveles de nutrientes. A partir de estos datos, el sistema activa de forma autónoma el riego por goteo solo cuando el cultivo lo necesita, garantizando una aplicación precisa y oportuna de agua y fertilizantes. Esta tecnología no solo reduce el uso innecesario de insumos y agua, sino que también mejora significativamente el rendimiento de los cultivos. <br><br>
Además, con el fin de comunicar con mayor claridad el valor y alcance de nuestra solución, proponemos su descripción detallada utilizando el modelo 5W y 2H:
<br><br>
</div>


<div align="justify">

***What***

* Los agricultores gestionan el riego y fertilización de forma empírica o mediante calendarios fijos.
* Esto genera uso excesivo de agua y fertilizantes, aumentando costos y reduciendo eficiencia.
* La falta de monitoreo en tiempo real impide decisiones oportunas y precisas sobre el manejo del cultivo.



***Who***

* A pequeños y medianos agricultores rurales, que gestionan sus cultivos con experiencia empírica y enfrentan limitaciones económicas, técnicas y climáticas para mejorar su productividad.
* A agricultores de cultivos de alto valor orientados a la exportación, que requieren precisión en el manejo de insumos para mantener la calidad y rentabilidad de sus productos.

***Where***
* Esta problemática se manifiesta en todo el territorio sudamericano, con especial gravedad en regiones agrícolas de Perú como Piura, Lambayeque o Ica, donde la disponibilidad de agua es crítica y los efectos del cambio climático agravan la variabilidad en las condiciones del suelo y el clima.


***When***
* El problema se presenta de forma continua durante toda la campaña agrícola, pero es especialmente crítico en fases de desarrollo del cultivo donde la falta de agua o nutrientes impacta directamente en el rendimiento. Además, se intensifica en épocas de sequía o cuando los precios de los fertilizantes aumentan bruscamente.

***Why***

* Porque los productores no cuentan con herramientas accesibles para monitorear condiciones del suelo.
* Porque la toma de decisiones no está basada en datos, sino en experiencia o tradición.
* Porque la tecnología agrointeligente aún no está democratizada en la mayoría de regiones rurales.


***How***

* Con NutriControl, los agricultores pueden automatizar el riego y fertilización mediante sensores que monitorean en tiempo real las condiciones del suelo.
* El sistema toma decisiones autónomas para activar el riego por goteo solo cuando es necesario, optimizando el uso de recursos.
* La plataforma web y la app móvil permiten al agricultor supervisar el proceso, recibir alertas y acceder a recomendaciones específicas para su terreno.


***How Much***

* Un agricultor puede perder hasta 30% del rendimiento por fertilización mal ejecutada.
* Con NutriControl, se estima una reducción de hasta 40% en el uso de fertilizantes y agua, además de un incremento en la productividad de hasta un 25%, traduciéndose en un impacto económico directo y positivo para el agricultor.

<br>
</div>

### 1.2.2. *Lean UX Process*

#### 1.2.2.1. *Lean UX Problem Statements*

<div align="justify">

***Problem Statement:***

**1. Domain:**
* El dominio corresponde al sector agropecuario, específicamente a la agricultura de precisión aplicada a cultivos de pequeña y mediana escala en regiones afectadas por problemas climáticos, hídricos y económicos. Se centra en el uso de tecnologías digitales, sensores IoT, automatización y analítica de datos para optimizar recursos y mejorar la rentabilidad agrícola.


**2. Customer Segments:**
* Pequeños y medianos agricultores rurales:
  * Carecen de acceso a tecnologías de monitoreo o automatización.
  * Toman decisiones basadas en experiencia empírica, no en datos.
  * Tienen recursos económicos limitados y márgenes de ganancia estrechos.
  * Viven en zonas rurales con estrés hídrico y condiciones climáticas adversas.

* Agricultores de cultivos de alto valor orientados a la exportación
  * Necesitan precisión en la dosificación de nutrientes y riego para cumplir estándares de calidad.
  * Pueden tener una mayor disposición a invertir si hay retorno claro.
  * Su producción se ve muy afectada por errores en fertilización o riego.

**3. Pain Points:**
* **Desconocimiento del estado real del suelo y sus necesidades:** La mayoría de agricultores carece de herramientas para medir variables clave como humedad, pH o nutrientes, lo que lleva a aplicar insumos sin criterios técnicos.

* **Ineficiencia en el uso del agua:** El riego suele aplicarse manualmente en horarios fijos, sin tomar en cuenta si el suelo lo necesita, lo que conlleva un uso excesivo o inadecuado del recurso hídrico.
  
* **Dependencia de insumos costosos (fertilizantes):** El aumento en el precio de fertilizantes y su aplicación ineficiente elevan los costos de producción sin garantizar un aumento proporcional en el rendimiento.

* **Falta de herramientas tecnológicas accesibles:** Las soluciones existentes son caras, diseñadas para grandes productores, o requieren conocimientos técnicos complejos, dejando fuera a la mayoría de agricultores rurales.

* **Riesgo productivo ante el cambio climático:** Fenómenos como sequías, heladas o lluvias intensas afectan de forma impredecible. Sin información en tiempo real, el agricultor no puede anticiparse ni actuar estratégicamente.

* **Carga operativa y toma de decisiones bajo presión:** El agricultor debe vigilar manualmente sus campos y tomar decisiones clave diariamente, sin apoyo tecnológico, generando estrés y errores frecuentes.

**4. Gap:**
<br><br>Existe una brecha crítica en el acceso a soluciones agrointeligentes que sean:

* **Accesibles económicamente para agricultores pequeños y medianos:** El mercado está saturado de soluciones costosas, importadas o de difícil mantenimiento, fuera del alcance de este segmento clave.
  
* **Fáciles de instalar y usar, sin necesidad de expertos:** Muchas tecnologías requieren formación técnica o soporte externo constante, lo cual no es viable para zonas rurales alejadas.
  
* **Diseñadas para zonas con conectividad limitada:** Pocas soluciones están adaptadas a funcionar offline o con sincronización diferida, lo cual es esencial para el entorno rural.
  
* **Enfocadas en el ahorro de recursos y el empoderamiento del agricultor:** La mayoría de herramientas tecnológicas actuales no se comunican bien con el usuario final ni priorizan el ahorro inmediato como incentivo.

**5. Vision / Strategy:**  
<br>La visión de AgroSense con NutriControl es democratizar el acceso a la agricultura de precisión, haciendo que la tecnología sea una aliada directa del agricultor, no un lujo inalcanzable. Para eso, se propone:

* Desarrollar una solución modular, escalable y de bajo costo, con sensores precisos que recolecten datos del suelo y el clima local.
* Ofrecer un sistema que automatice el riego y fertilización, reduciendo la carga operativa del agricultor y optimizando el uso de recursos clave.
* Diseñar una interfaz intuitiva y visual, que pueda ser utilizada incluso por agricultores con poca experiencia tecnológica.
* Integrar alertas y recomendaciones accionables, que ayuden a tomar decisiones informadas sin depender de asesores externos.
* Fomentar una comunidad de usuarios conectados, que compartan aprendizajes y validen el valor de la tecnología desde la experiencia en campo. 
</div>

#### 1.2.2.2. *Lean UX Assumptions*

***Business Assumptions:***

<div align="justify">

1. Los agricultores están dispuestos a adoptar tecnología si esta representa una mejora directa en su rentabilidad y productividad.

2. La creciente presión por hacer un uso eficiente del agua generará demanda por soluciones tecnológicas de monitoreo y control hídrico.


3. La dependencia del Perú de fertilizantes importados continuará impulsando la búsqueda de alternativas que reduzcan su consumo.


4. Existen programas de financiamiento o subsidios agrícolas que podrían facilitar la adquisición de tecnologías como NutriControl.


5. Las políticas públicas estarán cada vez más orientadas hacia la sostenibilidad y podrían favorecer el uso de herramientas de agricultura de precisión.


6. El mercado sudamericano tiene una base agrícola diversa que requiere soluciones flexibles y adaptables a diferentes tipos de cultivos.


7. La brecha tecnológica entre grandes y pequeños productores crea una oportunidad para democratizar el acceso a innovación.


8. El boca a boca y las demostraciones en campo serán canales clave para generar confianza y promover la adopción de la solución.


</div>

***Business Outcomes:***

<div align="justify">

- Aumento sostenido de ventas y adopción de NutriControl en regiones agrícolas con alto estrés hídrico como Piura, Arequipa, Ica y Lambayeque.


- Disminución del uso de fertilizantes entre un 20% y 40% mediante dosificación inteligente y personalizada.


- Optimización del uso del agua de riego hasta en un 50%, especialmente en zonas con escasa disponibilidad hídrica.


- Ampliación del mercado objetivo hacia otros países andinos y de la región con contextos similares (Ecuador, Bolivia, Colombia).

- Creación de alianzas con cooperativas agrarias, ONGs rurales o entidades públicas para facilitar la implementación.

- Mayor visibilidad de AgroSense como referente de innovación agrícola en ferias, congresos y publicaciones especializadas.

- Generación de datos valiosos del comportamiento del suelo y cultivos para futuros desarrollos y mejoras de producto.


</div>

***Users Assumptions:***

<div align="justify">

1. **¿Quién es el usuario?**

    * Pequeños y medianos agricultores, principalmente de zonas rurales de Perú y otros países de Sudamérica, con acceso limitado a tecnología avanzada.
    * Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación).

2. **¿Qué problemas tiene nuestro producto? ¿Resolver?**

    * Escasez de agua, alto costo de fertilizantes, baja eficiencia en el riego y fertilización, falta de información en tiempo real para la toma de decisiones.

3. **¿Qué características son importantes?**

    * Monitoreo en tiempo real, sensores de humedad, pH y nutrientes, automatización del riego y fertilización, interfaz intuitiva, acceso remoto desde cualquier dispositivo.

4. **¿Dónde encaja nuestro producto en su trabajo o vida?**

    * En la gestión diaria de cultivos, durante las jornadas de trabajo en el campo, permitiendo controlar el riego y la nutrición del suelo sin supervisión constante.
   
5. **¿Cuándo y cómo es usado nuestro producto?**

    * Durante toda la temporada de cultivo; se utiliza a través de una aplicación móvil o sistema web que se conecta con sensores instalados en el terreno, funcionando de manera continua y autónoma.

6. **¿Cómo debe verse nuestro producto y cómo comportarse?**

    * Debe tener una interfaz simple y visualmente clara, accesible desde dispositivos móviles con conexión limitada. 
    * El sistema debe comportarse de forma predictiva y automatizada, con alertas y recomendaciones personalizadas para el agricultor.

</div>

***User outcomes:***

<div align="justify">

- Mayor control sobre el uso de recursos hídricos y nutricionales en sus cultivos, con datos visibles y comprensibles.

- Ahorro de costos operativos anuales, especialmente en agua, fertilizantes y mano de obra para monitoreo manual.

- Incremento de la productividad por hectárea gracias a decisiones más precisas y personalizadas.

- Reducción del estrés operativo al contar con un sistema automatizado que indica cuándo y cuánto aplicar.

- Disminución del riesgo de pérdida de cultivos por condiciones climáticas extremas gracias a alertas predictivas.

- Adopción de una cultura de toma de decisiones basada en datos, fomentando una agricultura más profesionalizada.

- Percepción de modernización tecnológica, mejorando su competitividad frente a productores más grandes.

- Mayor resiliencia frente a los efectos del cambio climático y los mercados volátiles.


</div>

***Feature Assumptions***

<div align="justify">

- Los sensores podrán operar con eficiencia en suelos variados (arcillosos, arenosos, húmedos) y condiciones climáticas extremas (lluvias intensas, calor extremo).

- El sistema de riego automatizado responderá en tiempo real a las condiciones del suelo sin necesidad de intervención humana constante.

- La interfaz será intuitiva, multilingüe y compatible con dispositivos de baja gama (celulares de gama media/baja con conexión intermitente).

- Se podrá acceder a la plataforma desde zonas rurales con conectividad limitada, incluyendo modo offline para ciertas funciones.

- Las alertas y reportes estarán personalizadas por cultivo, tipo de suelo, y perfil del agricultor.

- El sistema tendrá capacidad de expansión modular para integrar nuevas variables (temperatura, salinidad, plagas).

- La solución podrá ser instalada y mantenida fácilmente con capacitación básica, sin necesidad de técnicos especializados constantes.

- El producto será escalable, desde parcelas pequeñas hasta medianas fincas, con opciones de configuración según el tamaño del terreno.


</div>

#### 1.2.2.3. *Lean UX Hypothesis Statements*

<div align="justify">

* **Creemos que** los pequeños y medianos agricultores adoptarán NutriControl si perciben una mejora directa en el uso eficiente del agua y fertilizantes. **Sabremos que esto es cierto cuando** al menos el 70% de los usuarios en piloto reporten una reducción comprobada del consumo de recursos en los primeros 3 meses de uso.

* **Creemos que** una interfaz intuitiva y visual facilitará que agricultores sin experiencia tecnológica puedan usar el sistema sin asistencia externa. **Sabremos que esto es cierto cuando** el 80% de los usuarios puedan completar las tareas principales (ver datos, programar riego, recibir alertas) sin soporte técnico durante las pruebas de usabilidad.


* **Creemos que** la automatización del riego y fertilización reducirá el estrés operativo y mejorará la productividad del agricultor. **Sabremos que esto es cierto cuando** el 60% de los usuarios reporten un incremento en el rendimiento del cultivo y menor carga de trabajo diaria luego de 2 ciclos agrícolas.

* **Creemos que** la solución podrá escalarse fácilmente a distintos tipos de cultivos y terrenos sin rediseños complejos. **Sabremos que esto es cierto cuando** al menos 3 tipos distintos de cultivos (por ejemplo, vid, maíz y arándanos) implementen el sistema sin requerir modificaciones técnicas significativas.


* **Creemos que** un proceso de instalación simple y guiado aumentará la tasa de adopción inicial sin requerir visitas técnicas. **Sabremos que esto es cierto cuando** más del 70% de los usuarios instalen y activen el sistema sin intervención presencial del equipo de soporte.

* **Creemos que** incluir lenguaje local, soporte en español y ejemplos con cultivos reales aumentará la confianza en el uso de la plataforma. **Sabremos que esto es cierto cuando** el índice de satisfacción del onboarding supere el 80% en zonas rurales tras las primeras pruebas piloto.

</div>

#### 1.2.2.4. *Lean UX Canvas*

![image](https://github.com/user-attachments/assets/d95293d3-eed7-4c60-b3d7-4fb6a112f627)

## 1.3. Segmentos objetivo

<div align="justify">

En esta sección, identificamos los segmentos de clientes específicos a los que se dirige NutriControl, basándonos en sus características productivas, comportamientos agrícolas y necesidades comunes frente a los desafíos del sector agropecuario.
<br>

**Productores rurales tradicionales (pequeños y medianos agricultores)**

**Descripción:**  
Agricultores que trabajan en zonas rurales, generalmente con acceso limitado a tecnologías agrícolas modernas y que gestionan sus cultivos con base en experiencia empírica. Representan la mayoría de productores en regiones como la sierra y costa peruana, donde existe una alta vulnerabilidad ante el cambio climático y la escasez hídrica.

**Características:**  
- Bajos niveles de tecnificación.  
- Recursos económicos limitados.  
- Alta dependencia de factores climáticos.  
- Cultivos de subsistencia o producción local.

**Necesidades:**  
- Acceder a herramientas asequibles para monitorear el suelo y el riego.  
- Optimizar el uso de agua y fertilizantes sin conocimientos técnicos complejos.  
- Recibir alertas y recomendaciones simples para mejorar la toma de decisiones.  
- Acceder a programas de financiamiento o subsidios que faciliten la adopción tecnológica.

<br>

**Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación)**

**Descripción:**  
Agricultores o empresas agroindustriales que cultivan productos como arándanos, uvas, palta o espárragos, destinados a mercados nacionales e internacionales. Estos productores buscan optimizar sus procesos para garantizar calidad, trazabilidad y sostenibilidad en sus cultivos.

**Características:**  
- Mayor nivel de inversión y disposición tecnológica.  
- Necesidad de control preciso de variables agrícolas.  
- Alta exigencia en calidad y cumplimiento de estándares de exportación.  
- Operan en áreas donde incluso pequeñas variaciones pueden afectar la rentabilidad.

**Necesidades:**  
- Monitoreo avanzado en tiempo real de humedad, pH y nutrientes del suelo.  
- Automatización del riego y fertilización para mejorar la eficiencia operativa.  
- Análisis predictivo y reportes históricos para planificación estratégica.  
- Recomendaciones personalizadas para cada tipo de cultivo y terreno.

</div>



<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

<div align="justify">

Después de realizar una investigación de mercado, hemos identificado tres plataformas que ofrecen características similares a las de nuestra solución NutriControl. Estas son:
</div>

**Competidores:**

<div align="justify">

* ***NetBeat (Netafim):***
NetBeat es una plataforma desarrollada por Netafim, líder global en soluciones de riego por goteo y agricultura de precisión. Es el primer sistema digital de gestión de riego que integra monitoreo, análisis y automatización en tiempo real. Permite a los agricultores controlar el riego y la fertilización desde un solo panel inteligente, tomando decisiones basadas en datos obtenidos de sensores de suelo, clima y cultivos. Aunque es una solución potente y muy consolidada, su implementación puede resultar costosa, especialmente para pequeños y medianos productores rurales.

</div>

  ![Imagen extraída de NetBeat([URL]())](Resources/Chapter%2002/Competitors/Netafim.png)

<br>
<div align="justify">

* ***Agrosmart:***
Agrosmart es una plataforma brasileña de agricultura digital diseñada para ayudar a los productores a tomar decisiones más informadas mediante el uso de datos climáticos, sensores de campo y análisis predictivo. Ofrece monitoreo remoto del suelo, clima y cultivos, además de generar alertas, reportes y recomendaciones personalizadas. Agrosmart ha logrado posicionarse fuertemente en América Latina gracias a su enfoque local y accesibilidad. Sin embargo, su oferta está más orientada al monitoreo y no a la automatización directa del riego y fertilización como lo hace NutriControl.

</div>

  ![Imagen extraída de AgroSmart([URL]())](Resources/Chapter%2002/Competitors/AgroSmart.png)
<br><br>
<div align="justify">

* ***Taranis:***
Taranis es una plataforma global de inteligencia agrícola que utiliza imágenes aéreas de alta resolución, sensores y algoritmos de inteligencia artificial para detectar problemas en los cultivos, como plagas, enfermedades y deficiencias nutricionales. Está orientada principalmente a grandes explotaciones agrícolas, ofreciendo reportes detallados y alertas tempranas sobre la salud del cultivo. Aunque es muy avanzada tecnológicamente, su enfoque se centra en el diagnóstico visual a gran escala más que en la automatización de procesos como el riego o la fertilización.

</div>

  ![Imagen extraída de Taranis([URL]())](Resources/Chapter%2002/Competitors/Taranis.png)

<br>


### 2.1.1. Análisis competitivo

<table>
    <thead>
        <tr>
            <th colspan="6">Competitive Analysis Landscape</th>
        </tr>
        <tr>
            <th colspan="6">Este análisis se realizó con la finalidad de poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de estos.</th>
        </tr>
        <tr>
            <th colspan="2">Nombre</th>
            <th>NutriControl</th>
            <th>NeatBeat (Netafim)</th>
            <th>AgroSmart</th>
            <th>Taranis</th>
        </tr>
        <tr>
            <th colspan="2">Logo</th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/NutriControl.jpeg" alt="Logo NutriControl"></th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/Netafim.png" alt="Logo NeatBeat"></th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/AgroSmart.png" alt="Logo AgroSmart"></th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/Taranis.png" alt="Logo Taranis"></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2" align="justify">Perfil</td>
            <td align="justify">Overview</td>
            <td align="justify">Solución tecnológica integral que combina sensores inteligentes con automatización de riego por goteo y análisis en tiempo real.</td>
            <td align="justify">Plataforma de gestión de riego digital que integra monitoreo, análisis y automatización en tiempo real.</td>
            <td align="justify">Plataforma de agricultura digital enfocada en el monitoreo y análisis predictivo.</td>
            <td align="justify">Plataforma de inteligencia agrícola basada en imágenes aéreas y algoritmos de IA para detectar problemas en los cultivos.</td>
        </tr>
        <tr>
            <td align="justify">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
            <td align="justify">Enfoque en pequeños y medianos productores rurales, con una solución accesible y fácilmente escalable que permite decisiones basadas en datos en tiempo real.</td>
            <td align="justify">Automatización completa de riego y fertilización, con tecnología líder en precisión agrícola.</td>
            <td align="justify">Enfoque local, accesibilidad económica y recomendaciones personalizadas para pequeños y medianos productores.</td>
            <td align="justify">Tecnología avanzada en detección visual de problemas en cultivos a gran escala.</td>
        </tr>
        <tr>
            <td rowspan="5" align="justify">Perfil de Marketing</td>
            <td align="justify">Mercado Objetivo</td>
            <td align="justify">Dirigido a pequeños y medianos productores rurales, con opción de escalabilidad futura hacia productores tecnificados.</td>
            <td align="justify">Productores tecnificados de cultivos de alto valor y grandes explotaciones agrícolas.</td>
            <td align="justify">Pequeños y medianos productores rurales en América Latina.</td>
            <td align="justify">Grandes explotaciones agrícolas a nivel global.</td>
        </tr>
        <tr>
            <td align="justify">Estrategias de Marketing</td>
            <td align="justify">Promoción directa en ferias locales, demostraciones de campo, alianzas con cooperativas y presencia en canales digitales.</td>
            <td align="justify">Marca consolidada, enfoque en tecnología de precisión y beneficios a largo plazo.</td>
            <td align="justify">Enfoque local, alianzas estratégicas con cooperativas y gobiernos.</td>
            <td align="justify">Promoción tecnológica avanzada en eventos globales de agricultura.</td>
        </tr>
        <tr>
            <td align="justify">Productos & servicios</td>
            <td align="justify">Riego automatizado, monitoreo en tiempo real, alertas personalizadas, reportes detallados y recomendaciones adaptadas a cada terreno.</td>
            <td align="justify">Riego automatizado, monitoreo y análisis en tiempo real.</td>
            <td align="justify">Monitoreo remoto del suelo, clima y cultivos, con alertas y reportes personalizados.</td>
            <td align="justify">Diagnóstico avanzado de cultivos mediante IA y reportes visuales detallados.</td>
        </tr>
        <tr>
            <td align="justify">Precios & Costos</td>
            <td align="justify">Modelo freemium con funciones básicas gratuitas; planes de suscripción mensual de bajo costo, ajustados al tamaño del terreno o número de sensores instalados.</td>
            <td align="justify">Costo promedio por hectárea entre $2,500 y $6,000, dependiendo del tipo de cultivo y suelo.</td>
            <td align="justify">Precio inicial de $950 por año.</td>
            <td align="justify">Costo por acre varía entre $5 y $20 por temporada, dependiendo del tipo de cultivo y frecuencia de monitoreo.</td>
        </tr>
        <tr>
            <td align="justify">Canales de distribución (Web y/o móvil)</td>
            <td align="justify">Aplicación web accesible desde dispositivos móviles y de escritorio, diseñado para ser intuitivo y fácil de usar por productores con bajos niveles de tecnificación.</td>
            <td align="justify">Aplicación web y móvil, con enfoque principal en la versión web.</td>
            <td align="justify">Aplicación web y móvil con facilidad de uso.</td>
            <td align="justify">Principalmente a través de plataformas web y socios tecnológicos.</td>
        </tr>
        <tr>
            <td rowspan="4" align="justify">Análisis SWOT</td>
            <td align="justify">Fortalezas</td>
            <td align="justify">Accesible, escalable y enfocado en pequeños productores rurales, con una solución integral que combina monitoreo y automatización.</td>
            <td align="justify">Tecnología avanzada, líder en automatización del riego y fertilización.</td>
            <td align="justify">Adaptabilidad al mercado local, accesible para pequeños productores, con recomendaciones personalizadas.</td>
            <td align="justify">Algoritmos de IA y precisión en diagnóstico visual de problemas en cultivos a gran escala.</td>
        </tr>
        <tr>
            <td align="justify">Debilidades</td>
            <td align="justify">Dependencia de la conectividad en zonas rurales.</td>
            <td align="justify">Alto costo, poco accesible para pequeños agricultores.</td>
            <td align="justify">Limitado al monitoreo, sin automatización directa de procesos como riego y fertilización.</td>
            <td align="justify">Enfocado en grandes explotaciones, poco accesible a pequeños productores; alto costo por acre.</td>
        </tr>
        <tr>
            <td align="justify">Oportunidades</td>
            <td align="justify">Adopción creciente de tecnología en pequeños y medianos productores; alianzas con programas de financiamiento o subsidios.</td>
            <td align="justify">Expansión en mercados emergentes con necesidad de soluciones de riego eficientes.</td>
            <td align="justify">Crecimiento en mercados rurales en América Latina; posibilidad de ampliar servicios hacia automatización.</td>
            <td align="justify">Desarrollo de nuevas funcionalidades de automatización; expansión a nuevos mercados agrícolas.</td>
        </tr>
        <tr>
            <td align="justify">Amenazas</td>
            <td align="justify">Entrada de nuevos competidores con mayores recursos; resistencia al cambio por parte de productores tradicionales.</td>
            <td align="justify">Competencia de soluciones más accesibles y adaptadas a pequeños productores.</td>
            <td align="justify">Competidores con capacidades avanzadas de automatización que podrían captar su mercado objetivo.</td>
            <td align="justify">Demanda alta de inversión inicial en equipos avanzados; posibles restricciones regulatorias.</td>
        </tr>
    </tbody>
</table>


### 2.1.2. Estrategias y tácticas frente a competidores

<div align="justify">
Según Michael Porter, la estrategia competitiva define cómo una empresa se posiciona frente a sus competidores. Existen tres enfoques clave: liderazgo en costos, que busca ofrecer precios más bajos; diferenciación, centrada en brindar productos o servicios únicos; y enfoque, que consiste en atender segmentos específicos del mercado. Para implementar con éxito cualquiera de estas estrategias, es esencial comprender a fondo el mercado y la competencia, con el fin de construir una ventaja sostenible a largo plazo. En este contexto, y considerando el análisis SWOT de NutriControl, se proponen diversas estrategias competitivas alineadas a estas directrices.
</div>

<br>
<div align="justify">

**Estrategias Competitivas para** ***NutriControl:***

1. **Liderazgo en Costos:**

**Estrategia:**  
NutriControl puede ofrecer una solución tecnológica eficiente y accesible, orientada especialmente a pequeños y medianos productores, utilizando herramientas de bajo costo y estructuras operativas ágiles.

**Tácticas:**
* Desarrollar una plataforma ligera compatible con dispositivos de baja gama y conexión limitada.  
* Ofrecer modelos de suscripción flexibles con precios diferenciados según el tamaño del productor.  
* Establecer convenios con instituciones públicas y ONGs para subsidios o cofinanciamiento del servicio.

2. **Diferenciación a través de la Innovación:**

**Estrategia:**  
NutriControl puede diferenciarse ofreciendo funciones especializadas en nutrición vegetal y modelos predictivos personalizados que respondan a las condiciones locales y necesidades específicas de cultivos regionales.

**Tácticas:**
* Integrar análisis del suelo, clima y recomendaciones nutricionales en tiempo real.  
* Invertir en el desarrollo de modelos predictivos con inteligencia artificial entrenados en datos locales.  
* Crear una interfaz intuitiva con alertas prácticas y consejos fácilmente aplicables por los agricultores.

3. **Enfoque en segmentos específicos del mercado:**

**Estrategia:**  
NutriControl puede especializarse en atender sectores agrícolas con escasa penetración tecnológica, como cooperativas rurales, cultivos de exportación de pequeña escala y regiones con menor acceso a servicios de asesoramiento agronómico.

**Tácticas:**
* Diseñar soluciones específicas para cultivos como café, cacao, maíz y hortalizas en regiones tropicales.  
* Ofrecer soporte técnico personalizado y recursos formativos en el idioma y contexto local.  
* Establecer alianzas con asociaciones de productores para adaptar y distribuir la solución a gran escala.

**Tácticas Específicas para** ***NutriControl:***

1. **Monitoreo Competitivo Continuo:**

**Táctica:**  
Analizar de manera constante las estrategias y características de plataformas como NetBeat, Agrosmart y Taranis para identificar ventajas diferenciales y vacíos de mercado.

**Acciones:**
* Realizar benchmarking de funcionalidades, modelos de precios y tecnologías utilizadas por los competidores.  
* Evaluar las debilidades en su adaptabilidad a productores pequeños o a contextos locales complejos.

2. **Estrategias de Precios y Paquetes Competitivos:**

**Táctica:**  
Diseñar paquetes de servicios adaptados a diferentes perfiles de usuario, con una estructura de precios transparente y accesible.

**Acciones:**
* Ofrecer un modelo freemium o versiones básicas con posibilidad de expansión mediante módulos adicionales.  
* Crear planes de precios por grupo, región o tipo de cultivo, facilitando el acceso colectivo.

3. **Inversión en Marketing Diferenciado:**

**Táctica:**  
Posicionar a NutriControl como una solución local, accesible y centrada en el productor, enfocándose en mostrar beneficios concretos y medibles.

**Acciones:**
* Publicar estudios de caso, testimonios y datos de impacto en productividad agrícola.  
* Utilizar canales de comunicación directa como redes sociales, ferias del agro y alianzas con radios comunitarias.

4. **Alianzas Estratégicas y Colaboraciones:**

**Táctica:**  
Aprovechar colaboraciones con entidades del ecosistema agrícola para ampliar el alcance, la credibilidad y la distribución de la solución.

**Acciones:**
* Establecer convenios con gobiernos, universidades agrícolas y centros de extensión rural.  
* Integrar NutriControl en programas de asistencia técnica, formación agronómica y financiamiento agrícola.

</div>


## 2.2. Entrevistas

<div align="justify">

Para acceder al video de las entrevistas, haga click en la ([URL]())

### 2.2.1. Diseño de entrevistas

Se han diseñado entrevistas cualitativas dirigidas a personas representativas de nuestros segmentos objetivo. Las preguntas fueron adaptadas a cada segmento, considerando sus contextos, niveles de tecnificación y necesidades específicas. Esta diferenciación nos permite obtener información más precisa, relevante y alineada a las realidades particulares de cada perfil de usuario.


**Segmento 1: Productores Rurales Tradicionales** 

**Preguntas de introducción:**

1. ¿Cuál es su nombre y cuántos años tiene?
2. ¿En qué zona o distrito vive?
3. ¿Cómo calificaría su situación económica? (Alta, media, media-baja o baja)
4. ¿Cuántos años lleva trabajando en agricultura?
5. ¿Qué cultivos tiene y en cuántas hectáreas?
6. ¿Alguna vez ha usado tecnología o herramientas digitales para su trabajo en el campo?

**Preguntas principales:**

1. ¿Cómo realiza actualmente el riego y la fertilización de sus cultivos? ¿Sigue algún calendario o lo hace según la observación diaria?
2. ¿Qué dificultades enfrenta al momento de decidir cuánto fertilizante o agua aplicar a sus plantas?
3. ¿Con qué frecuencia monitorea el estado del suelo (humedad, pH, nutrientes)? ¿Utiliza algún método o herramienta para hacerlo?
4. ¿Ha tenido pérdidas en sus cultivos por aplicar demasiada o muy poca agua/fertilizante?
5. ¿Qué tan costoso representa para usted adquirir fertilizantes o insumos? ¿Ha notado que su precio ha cambiado en los últimos años?
6. ¿Qué haría diferente si pudiera saber en tiempo real lo que su cultivo necesita?
7. ¿Qué importancia tiene para usted el ahorro de agua en su actividad agrícola?
8. ¿Cómo le afecta el cambio climático en su producción agrícola? ¿Ha cambiado algo en la forma en que trabaja?
9. ¿Con qué frecuencia accede a internet o usa un celular durante su jornada en el campo?
10. ¿Estaría dispuesto a utilizar una herramienta que le diga exactamente cuándo y cuánto fertilizante o agua aplicar?
11. ¿Qué condiciones debería tener una herramienta tecnológica para que usted la use sin complicaciones?
12. ¿Qué beneficios espera de una solución que automatice parte del riego o fertilización?
13. ¿Desea agregar algo más que considere importante sobre su trabajo o sobre el uso de nuevas herramientas?


**Segmento 2: Productores Tecnificados de Cultivos de Alto Valor** 

**Preguntas de introducción:**

1. ¿Cuál es su nombre, edad y cargo dentro de la empresa o predio agrícola?
2. ¿Hace cuántos años están operando con este cultivo?
3. ¿Qué cultivos producen principalmente y cuántas hectáreas manejan actualmente?
4. ¿En qué región o zona se ubica su operación agrícola?
5. ¿Actualmente cuentan con algún sistema de agricultura de precisión o monitoreo digital?
6. ¿Qué herramientas o tecnologías utilizan para gestionar riego, fertilización o trazabilidad?


**Preguntas principales:**

1. ¿Cómo determinan actualmente la cantidad de agua y fertilizantes que necesita el cultivo?
2. ¿Con qué frecuencia monitorean variables como humedad del suelo, pH o niveles de nutrientes?
3. ¿Tienen sensores instalados actualmente? Si no, ¿por qué aún no los implementan?
4. ¿Qué tan automatizado está su sistema de riego/fertilización? ¿Hay procesos manuales?
5. ¿Qué impacto económico tiene el uso de fertilizantes en su operación? ¿Buscan optimizarlo?
6. ¿Han tenido problemas por sobreuso o deficiencia de fertilizantes o agua en campañas pasadas?
7. ¿Qué tan importante es para su empresa la trazabilidad de los insumos y el historial del cultivo?
8. ¿Cómo gestionan actualmente la toma de decisiones en base a los datos del terreno o clima?
9. ¿Qué tipo de reportes o métricas son más útiles en su gestión diaria o estratégica?
10. ¿Qué valoraría más de una solución como NutriControl: automatización, precisión o ahorro?
11. ¿Qué características o integraciones consideran imprescindibles en una plataforma tecnológica agrícola?
12. ¿Estarían dispuestos a adoptar una solución modular que se adapte al tipo de cultivo, terreno o tamaño de operación?
13. ¿Desea agregar algo más que considere importante sobre su trabajo o sobre el uso de nuevas herramientas?


</div>

### 2.2.2. Registro de entrevistas

<div align="justify">

Para el registro de entrevistas se realizará una entrevista por segmento, dando un total de 6 entrevistas. Además, el formato de las entrevistas es mp4, cada entrevista es independiente debido a las diferentes preguntas y respuestas dadas por los entrevistados de cada segmento.

**Segmento 1: Productores Rurales Tradicionales**

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"> <div align="center">Entrevista #1<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td></td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td></td>
  </tr>
  <tr>
    <td>Edad</td>
    <td> años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td></td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td></td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td></td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td></td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td></td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td></td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="" alt="Entrevista "></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>00:00 min - : min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;"></td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #2<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Diego</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Cano Acero</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>23 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Mejorar la calidad del cultivo, optimizar el uso del agua y garantizar la producción de arándanos de alta calidad.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>Enfrenta dificultades al aplicar teorías agrícolas que no siempre se ajustan a las condiciones reales del campo. El cambio climático ha afectado la calidad del cultivo por el exceso de calor y la pérdida de nutrientes. Además, la mala conectividad limita el uso de herramientas digitales en tiempo real y la falta de información compartida con otros agricultores dificulta la prevención de plagas.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td> celular, laptop , sensores de ph y Riego por goteo</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Christian Espinoza</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="Resources/Chapter%2002/Interview%20Evidence/Evidencia-DiegoCano.png" alt="Diego Cano"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213208_upc_edu_pe/EfG8rT-fPO9Elb-usHmyvRMBYBDAB3Cro2b3cIwB-DOVMw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=x2cQT8" title="Title">Ver Entrevista</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>11:04 min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">
    Diego Cano, joven agricultor de 23 años, trabaja desde hace tres años en el cultivo de arándanos en unas 3 hectáreas que le fueron asignadas. Aunque no es propietario, está familiarizado con prácticas avanzadas en agricultura como el riego por goteo, fertirriego, uso de sensores y análisis de suelo. Resalta el impacto del cambio climático en su zona, con temperaturas elevadas y menor disponibilidad de agua. Usa tecnología en campo, pero limitada al uso por computadora, ya que la señal móvil es deficiente. Expresa interés en herramientas digitales que le proporcionen retroalimentación en tiempo real sobre el estado del cultivo, dosificación precisa de fertilizantes y alertas preventivas frente a plagas observadas por agricultores cercanos. Recalca la importancia de herramientas confiables, fáciles de usar y compartidas entre el personal.</td>
  </tr>
</tbody>
</table>


<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #3<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Magno Jesus</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Puma Ayasta</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>28 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Santo Tomás, Chumbivilcas, Cusco</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Mejorar la eficiencia de su trabajo agrícola, ahorrar recursos y aumentar la productividad de sus cultivos para garantizar una mejor calidad de vida.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>Dificultades por la falta de acceso a herramientas precisas, los altos costos de insumos y el impacto del cambio climático, lo que complica su labor diaria.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Brave</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Abel Andrés Valle Zuta</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="Resources/Chapter%2002/Interview%20Evidence/entrevista_andres_magno.PNG" alt="Magno Puma"></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>: min - :: min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">
    Magno Puma, agricultor de 28 años de Santo Tomás, Cusco, con una economía media-baja, ha trabajado en agricultura toda su vida, dedicándose principalmente al cultivo de papa y cebada en tres hectáreas. Su riego y fertilización se basan en observación tradicional y conocimiento empírico, enfrentando desafíos como la falta de precisión al aplicar insumos y el impacto del cambio climático en la producción. Aunque no utiliza herramientas tecnológicas avanzadas, está interesado en soluciones que le permitan ahorrar agua y fertilizantes, mejorar la salud de sus cultivos y aumentar su rendimiento. Considera esencial que estas herramientas sean simples, accesibles sin internet y adaptadas a su contexto, como incluir lenguaje quechua. Además, enfatiza la importancia de la capacitación para aprovechar al máximo cualquier innovación.</td>
  </tr>
</tbody>
</table>


**Segmento 2: Productores Tecnificados de Cultivos de Alto Valor**

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #1<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Nicolle</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Gonzales</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>25 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Tinguiña, Ica, Perú</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Meets</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Mejorar la gestión de su cultivo de arándanos con tecnología que le permita tomar decisiones más precisas, reducir el desperdicio de agua y fertilizantes, y lograr un mayor control sobre la producción.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>No contar con una solución que le indique con claridad cuándo y cuánto fertilizar o regar, tener que depender de la observación visual, y no poder automatizar tareas clave.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop y Computadora Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Hernan Morales</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="" alt=""></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>:: min - :: min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">
</td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #2<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Italo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Hurtado</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>25 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Chincha Alta, Ica, Perú</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Meets</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Optimizar los procesos de riego y fertilización para ahorrar insumos y mejorar la calidad del cultivo, apostando por tecnologías que faciliten la gestión sin necesidad de supervisión constante.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>Falta de herramientas accesibles que ayuden a tomar decisiones precisas y en tiempo real. La variación climática lo obliga a improvisar y eso impacta en el rendimiento.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Laptop, Computadora Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Googlee Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Hernan Morales</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="" alt=""></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>:: min - :: min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;"></td>
  </tr>
</tbody>
</table>

<table>
<colgroup>
</colgroup>
<thead>
  <tr>
    <th colspan="2"><div align="center">Entrevista #3<br></div></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td></td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td></td>
  </tr>
  <tr>
    <td>Edad</td>
    <td> años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td></td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td></td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td></tr>
  <tr>
    <td>Frustración</td>
    <td></tr>
  <tr>
    <td>Tecnologías</td>
    <td></td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td></td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td></td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="" alt="Entrevista "></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>:: min  - :: min  </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;"></td>
  </tr>
</tbody>
</table>

</div>

### 2.2.3. Análisis de entrevistas

<div align="justify">



</div>

## 2.3. *Needfinding*

<div align="justify">

Con el fin de desarrollar un producto que satisfaga las necesidades de un cliente en particular, AgroSense identificará los User persona, User Task Matrix, User Journey Maps y Empathy Mapping.

</div>


### 2.3.1. *User Personas*

<div align="justify">

Presentaremos los User Persona por cada segmento objetivo, en los cuales nos basamos en los usuarios ideales de cada segmento. A continuación, los presentamos:

<div style="page-break-after: always;"></div>

***User Persona 1 - Segmento de :*** **Productores rurales tradicionales (pequeños y medianos agricultores)**

</div>

![Artefacto creado en UXPressia](Resources/Chapter%2002/User%20Personas/RobinsonRojas.png)

<div style="page-break-after: always;"></div>

***User Persona 2 - Segmento de :*** **Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación)**

![Artefacto creado en UXPressia](Resources/Chapter%2002/User%20Personas/Mariana%20Díaz.png)

<div style="page-break-after: always;"></div>


### 2.3.2. *User Task Matrix*

User Task Matrix: 

Con el fin de elaborar un Task Matrix adecuado para el proyecto, se han considerado los dos segmentos objetivo, producto del análisis de entrevistas, es decir, productores rurales tradicionales y productores tecnificados de cultivos de alto valor.

<b>Robinson Rojas (Productor rural tradicional)</b><br>

<div align="center">

| **USER TASK**                               | **Frecuencia** | **Importancia** |
|---------------------------------------------|----------------|-----------------|
| Monitorear la humedad y nutrientes del suelo	 |     Media      |      Alta      |
| Recibir alertas sobre cuándo regar	 |     Alta      |      Alta      |
| Ajustar el sistema de riego manualmente	 |     Baja      |      Media      |
| Consultar reportes básicos de su terreno	 |     Media      |      Media      |
| Recibir recomendaciones simples	 |     Alta      |      Alta      |
| Configurar sensores iniciales	 |     Baja      |      Media      |
| Contactar soporte técnico	 |     Baja      |      Baja      |
| Aprender a usar la aplicación móvil	 |     Media      |      Alta      |


</div><br><br>

<b>Mariana Díaz (Productora tecnificada de cultivos de alto valor)</b><br>

<div align="center">

| **USER TASK**                               | **Frecuencia** | **Importancia** |
|---------------------------------------------|----------------|-----------------|
| Monitorear en tiempo real las variables del suelo	 |     Alta      |      Alta      |
| Automatizar el sistema de riego y fertilización	 |     Alta      |      Alta      |
| Consultar reportes históricos detallados	 |     Media      |      Alta      |
| Analizar predicciones basadas en datos	 |     Media      |      Alta      |
| Personalizar las alertas y notificaciones	 |     Baja      |      Media      |
| Configurar y calibrar sensores avanzados	 |     Baja      |      Alta      |
| Integrar NutriControl con otros sistemas de gestión agrícola	 |     Baja      |      Alta      |
| Realizar capacitaciones a su equipo sobre la herramienta	 |     Baja      |      Media      |

</div>


### 2.3.3. *User Journey Mapping*

***User Journey Mapping:*** **Productores rurales tradicionales (pequeños y medianos agricultores)**

![Artefacto creado en UXPressia](Resources/Chapter%2002/Journey%20Map/Robinson%20Rojas.png)

<div style="page-break-after: always;"></div>

***User Journey Mapping:*** **Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación)**

![Artefacto creado en UXPressia](Resources/Chapter%2002/Journey%20Map/Mariana%20Diaz.png)

<div style="page-break-after: always;"></div>

### 2.3.4. *Empathy Mapping*

***Empathy Mapping:*** **Productores rurales tradicionales (pequeños y medianos agricultores)**

![Artefacto creado en UXPressia](Resources/Chapter%2002/Empathy%20Map/Robinson%20Rojas.png)

<div style="page-break-after: always;"></div>

***Empathy Mapping:*** **Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación)**

![Artefacto creado en UXPressia](Resources/Chapter%2002/Empathy%20Map/Mariana%20Díaz.png)

<div style="page-break-after: always;"></div>


### 2.3.5. *As-is Scenario Mapping*

<div align="justify">

El As-Is Scenario Mapping es una herramienta para identificar los pensamientos que tienen los usuarios sin la aplicación.

</div>

***As-Is Scenario Map:*** **Productores rurales tradicionales (pequeños y medianos agricultores)**

![Recurso creado en Miro](Resources/Chapter%2002/As-Is/AsIs_Segmento1.png)

***As-Is Scenario Map:*** **Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación)**

![Recurso creado en Miro](Resources/Chapter%2002/As-Is/AsIs_Segmento2.png)

<div style="page-break-after: always;"></div>

## 2.4. *Ubiquitous Language*

Los términos utilizados en el dominio del negocio son los siguientes:

| **Término**              | **Definición**                                                                 |
|-----------------------|--------------------------------------------------------------------------------|
| **Crop**              | Conjunto de plantas cultivadas en una zona específica, monitoreadas mediante sensores. |
| **Cultivation Zone**  | Área geográfica delimitada donde se desarrollan y controlan los cultivos.      |
| **Environmental Variable** | Factor del entorno como temperatura, humedad, o radiación que impacta el crecimiento del cultivo. |
| **Precision Agriculture** | Estrategia que emplea datos y tecnología para optimizar el uso de recursos en la producción agrícola. |
| **Irrigation System** | Conjunto de tecnologías que permiten administrar de forma eficiente el riego de los cultivos en función de datos ambientales. |
| **Real-time Monitoring** | Observación continua de datos del campo para permitir decisiones inmediatas. |
| **Decision Support**  | Herramientas analíticas que ayudan al productor a tomar decisiones informadas basadas en datos. |
| **Soil Moisture**     | Cantidad de agua presente en el suelo, factor clave para determinar las necesidades de riego. |
| **Data-driven Agriculture** | Modelo agrícola donde las decisiones se basan completamente en análisis de datos recolectados. |
| **Field Activity Log**| Registro cronológico de todas las acciones y eventos relacionados con un cultivo específico. |


<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

### 3.1. *To-Be Scenario Mapping*

El *To-Be Scenario Mapping* es una herramienta para identificar cómo se sentirán los usuarios con los nuevos cambios que deberían haber solucionado los problemas planteados en los *As-Is scenario maps.*

![Recurso creado en Miro](Resources/cap2/ToBeSM.png)

### 3.2. *User Stories:*

***Epics***




***User Stories***

<table>
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionado con (Epic ID)</th>
  </tr>
  <tr>
    <td>US-01</td>
    <td>Información de NutriControl</td>
    <td>Como usuario potencial, cuando ingrese a la Landing Page de NutriControl, quiero poder visualizar información del funcionamiento de la solución y su propuesta de valor.</td>
    <td>
    </td>
    <td>-</td>
  </tr>
  <tr>
    <td>US-02</td>
    <td>Características de NutriControl</td>
    <td>Como usuario potencial, cuando navegue dentro de las secciones de la Landing Page de NutriControl, quiero poder visualizar características específicas de lo que NutriControl ofrece y ver si se adecuan a mis necesidades.</td>
    <td>
    </td>
    <td>-</td>
  </tr>
  <tr>
    <td>US-03</td>
    <td>Sección de planes o membresías</td>
    <td>Como usuario potencia, cuando navegue dentro de las secciones de la Landing Page de NutriControl, quiero poder visualizar una sección de planes en los cuales ver los beneficios adicionales que tendría fuera de un plan 
     Freemium. 
    </td>
    <td>
    </td>
    <td>-</td>
  </tr>
  <tr>
    <td>US-04</td>
    <td>Registro de Usuario</td>
    <td>Como usuario, cuando ingrese a la App Web o descargue el App Móvil, quiero poder registrarme con un correo electrónico y contraseña para poder usar NutriControl.</td>
    <td>
    </td>
    <td>-</td>
  </tr>
  <tr>
    <td>US-05</td>
    <td>Inicio de Sesión</td>
    <td>Como usuario, cuando ingrese a la App Web o descargue el App Móvil, quiero poder iniciar sesión con mis credenciales ya creadas en el registro de NutriControl.</td>
    <td>
    </td>
    <td>-</td>
  </tr>
  <tr>
    <td>US-06</td>
    <td>Recuperación de Contraseña</td>
    <td>Como usuario, cuando ingrese a la App Web o descargue el App Móvil, quiero poder recuperar o cambiar mi contraseña en caso la haya olvidado.</td>
    <td>
    </td>
    <td>-</td>
  </tr>
</table>



<div align="justify">



***Technical User Stories***



</div>

### 3.3. *Impact Mapping*

El impact map es una herramienta estratégica que permite identificar de manera precisa las características de una aplicación que pueden ser utilizadas o mejoradas para cumplir con un objetivo empresarial específico. Al partir del objetivo clave, se desglosan los comportamientos necesarios de los usuarios, se definen las acciones que deben realizar en la aplicación, se identifican las características necesarias para habilitar esas acciones, se evalúa el impacto potencial de cada característica en el logro del objetivo, y finalmente se crea un plan de acción detallado que guía el desarrollo y mejora continua de la aplicación, alineando así las acciones de los usuarios con los objetivos estratégicos de la empresa.

![Artefacto creado en UXPressia](Resources/Chapter%2002/Impact%20Map/ImpactMap.png)

<div style="page-break-after: always;"></div>

### 3.4. *Product Backlog*

Utilizaremos la escala de Fibonacci (1/2/3/5/8/13/21) para realizar este valorización de User Stories por Story Points.

**User Story Base:**

Seleccionamos esta User Story como base de referencia para la valorización de las demás User Stories.

| **# Orden** | **User Story ID** | **Título**                                                      | **Descripción**                                                                                                                                                               | **Story Points (1 / 2 / 3 / 5 / 8 / 13 /…)** |
|:-----------:|:-----------------:|:---------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|----------------------------------------------|
|           |               |  | **Como** , **quiero**  **para** . |                                             |


**Product Backlog:**

<div align = "justify">



</div>

# Capítulo IV: *Solution Software Design*

## 4.1. *Strategic-Level Domain-Driven Design*



### 4.1.1. *EventStorming*

Esta es la técnica colaborativa utilizada para modelar sistemas complejos y entender el dominio del problema, donde explicamos y evidenciamos el proceso con el fin de plantear una primera aproximación al modelado general e identificando el mayor nivel de detalle posible. Este fue desarrollado en las siguientes fases:

1. Unstructured Exploration:  
En esta fase, el equipo exploró libremente el dominio del problema, compartiendo conocimientos y capturando ideas sin una estructura formal. El objetivo fue generar una visión amplia y completa del sistema, sentando las bases para las siguientes fases del modelado.
  ![Unstructured Exploration](Resources/Chapter%2002/EventStorming/Unstructured-Exploration.png)

2. Timelines:  
En esta fase, el equipo organizó los eventos identificados en un flujo cronológico, visualizando su secuencia y las interacciones entre ellos. Esto ayudó a identificar dependencias y puntos críticos, facilitando la comprensión del sistema y la planificación de las siguientes etapas del modelado.
 ![Timelines](Resources/Chapter%2002/EventStorming/timelines.png)

3. Pain Points:   
En esta fase, el equipo identificó los problemas o desafíos clave dentro del dominio del sistema. Se enfocaron en los puntos críticos donde los usuarios o procesos pueden enfrentar dificultades o ineficiencias.
 ![Pain Points](Resources/Chapter%2002/EventStorming/Pain-points.png)

4. Pivotal Points:  
En esta fase, el equipo identificó los eventos clave que tienen un impacto significativo en el sistema y que podrían cambiar el curso de las decisiones o procesos. 
![Pivotal points](Resources/Chapter%2002/EventStorming/pivotal-points.png)

5. Commands:   
En esta fase, el equipo identificó las acciones  que deben ser ejecutados dentro del sistema para que los eventos ocurran o los procesos se inicien. Estos comandos son decisiones o instrucciones claras que desencadenan eventos específicos y ayudan a guiar el flujo de trabajo en el sistema.
![Commands](Resources/Chapter%2002/EventStorming/Commands.png)



#### 4.1.1.1. *Candidate Context Discovery*

En esta sección, el equipo, a partir del dominio modelado con EventStorming, explicó y evidenció el proceso realizado durante la sesión de Candidate Context Discovery, cuyo objetivo fue identificar los bounded contexts.La sesión duró 1 hora con 50 minutos, y se utilizó la herramienta miro, complementando la explicación con capturas de los cambios progresivos en EventStorming.

6. Policies:   
En esta fase, el equipo identificó las reglas o políticas que rigen el comportamiento del sistema. Estas políticas son restricciones, normativas o criterios que deben ser seguidos para tomar decisiones dentro del proceso.
![Commands](Resources/Chapter%2002/EventStorming/policies.png)

7. Read Models:   
En esta fase , el equipo se centró en identificar los modelos de lectura que permiten consultar y visualizar la información almacenada en el sistema. 
![Commands](Resources/Chapter%2002/EventStorming/Read-models.png)

8. External Systems:   
En esta fase, el equipo identificó y analizó los sistemas externos con los que el sistema principal interactúa. Estos pueden incluir aplicaciones, bases de datos, servicios de terceros o plataformas externas que proporcionan o reciben información del sistema. 
![Commands](Resources/Chapter%2002/EventStorming/external-systems.png)

9. Aggregates:    
En esta fase, el equipo definió las entidades principales que agrupan y gestionan los datos relacionados como una unidad. Los Aggregates aseguran la consistencia de los datos y aplican las reglas de negocio dentro de sus límites.
![Commands](Resources/Chapter%2002/EventStorming/Aggregates.png)

10. Bounded Contexts:
En esta fase, el equipo identificó los límites dentro de los cuales un modelo específico es aplicable y coherente. Cada Bounded Context define un área del sistema con su propio conjunto de reglas, terminología y lógica de negocio.
![Commands](Resources/Chapter%2002/EventStorming/Bounded-Contexts.png)

Para una mejor visualización este es enlace a los diagramas en miro : 
[https://miro.com/app/board/uXjVI-UYdMU=/?share_link_id=788988253384](https://miro.com/app/board/uXjVI-UYdMU=/?share_link_id=788988253384)


#### 4.1.1.2. *Domain Message Flows Modeling*



#### 4.1.1.3. *Bounded Context Canvases*



### 4.1.2. *Context Mapping*



### 4.1.3. *Software Architecture*



#### 4.1.3.1. *Software Architecture System Landscape Diagram*



#### 4.1.3.2. *Software Architecture Context Level Diagrams*



#### 4.1.3.3. *Software Architecture Container Level Diagrams*



#### 4.1.3.4. *Software Architecture Deployment Diagrams*



## 4.2. *Tactical-Level Domain-Driven Design*



### 4.2.1. *Bounded Context: <Bounded Context Name>*



#### 4.2.1.1. *Domain Layer*



#### 4.2.1.2. *Interface Layer*



#### 4.2.1.3. *Application Layer*



#### 4.2.1.4. *Infrastructure Layer*



#### 4.2.1.5. *Bounded Context Software Architecture Component Level Diagrams*



#### 4.2.1.6. *Bounded Context Software Architecture Code Level Diagrams*



##### 4.2.1.6.1. *Bounded Context Domain Layer Class Diagrams*



##### 4.2.1.6.2. *Bounded Context Database Design Diagram*




# Conclusiones

<br>

<div align = "justify">



</div>

<br>

# Bibliografía

<br>

+ <br>  <br><br>

+ <br>  <br><br>

+ <br>  <br><br>

+ <br>  <br><br>

<br>

# Anexos

+ Repositorio GitHub de la Organización: [Ver Organización]()<br><br>
+ Repositorio GitHub del Informe: [Ver Repositorio]()<br><br>
+ Repositorio GitHub del Backend: [Ver Repositorio]()<br><br>
+ Repositorio GitHub de la Aplicación Móvil: [Ver Repositorio]()<br><br>
+ Enlace de la Landing Page: [Ver Landing Page]()<br><br>
+ Enlace del Backend deployado: [Ver Backend]()<br><br>

## Needfinding Interviews

  <div align="center">
    <img src="">
 </div>


Enlace: [Needfinding]()


## Video Exposición del TB1

  <div align="center">
    <img src="">
 </div>


Enlace: [TB1]()
