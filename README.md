
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
|TB1| 20/04/2025 |Antonio Salazar Jhan Clinton|  Capítulo I: Introducción, Capítulo II: Requirement Elicitation & Analysis, Capítulo III: Requirements Specification, Capítulo IV: Solution Software Design |
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
        - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
        - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
        - [4.1.3.3. Software Architecture Components Level Diagrams](#4133-software-architecture-components-level-diagrams)
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
establecen objetivos, planifican tareas y cumplen objetivos.<br><br>

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
| Jhan Clinton Antonio Salazar |   Soy Jhan Clinton, estudiante de Ingeniería de Software con gran pasión por el desarrollo tecnológico. En mi formación académica me enfoco en fortalecer mis habilidades en programación, diseño de sistemas y trabajo en equipo. Como estudiante, destaco por mi capacidad para aprender rápidamente, resolver problemas técnicos y colaborar activamente en proyectos grupales. Mi objetivo es seguir creciendo profesionalmente, aplicando mis conocimientos teóricos en desafíos prácticos y contribuyendo con soluciones innovadoras. ¡Siempre listo para asumir nuevos retos en el mundo del desarrollo de software!                                                                                                                                                                                     |  ![Image](https://github.com/user-attachments/assets/cb661b96-b6e6-4908-a148-9a34ec718192)  |
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
    <td>Arturo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Adrianzén Flores</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Huancayo</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Mejorar el rendimiento de sus cultivos y aprender nuevas tecnologías que faciliten su trabajo.</td>
  </tr>
  <tr>
    <td>Frustración</td>
    <td>No saber con precisión cuánto fertilizante o agua aplicar y enfrentar el alto costo de los insumos.</td>
  </tr>
  <tr>
    <td>Tecnologías</td>
    <td>Zoom, Windows</td>
  </tr>
  <tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>Diego Criollo</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="Resources/Chapter%2002/Interview%20Evidence/Evidencia-Arturo-Adrianzen.png" alt="Entrevista a Arturo Adrianzen"></div></td>
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
    <td style="text-align: justify;">
Arturo Adrianzen, joven agricultor e hijo de campesinos de la sierra peruana, realiza el riego y la fertilización de sus cultivos guiándose por la observación diaria y la experiencia familiar, sin herramientas técnicas ni un calendario fijo. Señala que le cuesta saber con exactitud cuánto fertilizante o agua aplicar, lo que a veces le ha generado pérdidas. No monitorea el suelo de forma regular y el alto costo de los insumos lo obliga a usarlos con cuidado. Considera que una herramienta que indique en tiempo real las necesidades del cultivo sería muy útil, especialmente para ahorrar agua y evitar errores. Reconoce que el cambio climático ha afectado su producción y ha tenido que adaptarse. Usa su celular con frecuencia para informarse y estaría dispuesto a usar tecnología agrícola, siempre que sea sencilla, funcione sin internet constante y venga acompañada de capacitación.
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
    <td><div align="center"><img src="/Resources/Chapter%2002/Interview%20Evidence/Evidencia-Nicolle.png" alt=""></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216263_upc_edu_pe/EWhORUFcKbJFvkIqTgSUbgEBzBrjdJ2ZaSesRmqd4Jl3FQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=bdwGMr" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>:: min - :: min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">
    Nicolle Gonzales, gerente de operaciones agrícolas de 25 años, lidera una finca de 45 hectáreas de arándanos en Ica. Si bien cuenta con sensores de humedad y riego tecnificado, aún depende de decisiones manuales para aplicar agua y fertilizantes, lo que genera imprecisiones y riesgos de salinidad o deficiencias nutricionales. La gestión actual combina registros en Excel, monitoreos manuales y análisis trimestrales de nutrientes, lo que limita la capacidad de respuesta y eficiencia. Nicolle valora la trazabilidad y requiere una solución que registre acciones automáticamente, funcione con poca conectividad y facilite la toma de decisiones en tiempo real. Considera que la precisión es clave para lograr ahorro, sostenibilidad y calidad de exportación. Está interesada en adoptar una plataforma modular, fácil de usar, que integre sensores, clima y recomendaciones prácticas para el campo.

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
    <td><div align="center"><img src="/Resources/Chapter%2002/Interview%20Evidence/Evidencia-Italo.png" alt=""></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216263_upc_edu_pe/EatICUR_XWFOjxJ8MkYTkXEB_Ok6EZhBUpPCymh9A8D_tg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=XuyiaI" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>:: min - :: min </td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td style="text-align: justify;">
    Ítalo Hurtado, encargado de operaciones agrícolas de 25 años, trabaja en una finca de 60 hectáreas de palta Hass y uva Red Globe en Chincha, Ica. Aunque cuentan con sensores de humedad y estaciones meteorológicas, la toma de decisiones sigue siendo manual, lo que genera márgenes de error en el riego y fertilización. El control del suelo es diario, pero el monitoreo de nutrientes es trimestral, limitando la rapidez de reacción ante cambios. El costo de fertilizantes es alto y su mal manejo ha generado problemas de calidad en campañas anteriores. Ítalo destaca la importancia de la trazabilidad para exportar y considera urgente automatizar decisiones para mejorar eficiencia. Valora especialmente soluciones que ofrezcan automatización basada en datos en tiempo real, sean modulares y adaptables al crecimiento de la operación.
    </td>
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
    <td>Leonel </td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Alfaro Cumba</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td> 25 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Chincha Ica</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Microsoft Stream</td>
  </tr>
  <tr>
    <td>Motivación</td>
    <td>Implementar soluciones tecnológicas accesibles para optimizar el manejo de cultivos, reducir costos operativos y mejorar la calidad de la producción mediante el uso de herramientas digitales.</tr>
  <tr>
    <td>Frustración</td>
    <td>Dificultad para acceder a sistemas de monitoreo agrícola asequibles y fáciles de usar. La falta de datos en tiempo real lo obliga a depender de métodos tradicionales, lo que genera ineficiencias en riego y fertilización.</tr>
  <tr>
    <td>Tecnologías</td>
    <td>Android, Laptop con Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google</td>
  </tr>
  <tr>
    <td>Entrevistador</td>
    <td>![Image](https://github.com/user-attachments/assets/2b115383-7f54-4418-95c7-4d5b1ec4533f)/td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center"><img src="/Resources/Chapter%2002/Interview%20Evidence/Evidencia-Italo.png" alt=""></div></td>
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

**Segmento de Productores Rurales Tradicionales**

**Perfil Demográfico**

* Edades: Promedio de 23 años.
* Ubicación Geográfica: Principalmente zonas rurales de Perú como Huancayo (Junín), La Molina (Lima) y Santo Tomás (Cusco).
* Actividad Principal: Agricultura de pequeña escala, principalmente cultivos de papa, cebada y arándanos.
* Tamaño de parcelas: Entre 3 a 5 hectáreas aproximadamente.

**Experiencia y Conocimientos en Agricultura**

* Todos los entrevistados tienen experiencia práctica basada en la observación diaria y el conocimiento familiar tradicional.
* Algunos, como Diego Cano, han tenido contacto con tecnologías básicas de agricultura de precisión (riego por goteo, fertirriego y sensores de humedad), aunque su uso aún no es integrado o automatizado.
* Existe un interés generalizado en modernizar sus prácticas agrícolas, pero requieren herramientas simples y accesibles.

**Herramientas y Tecnologías Utilizadas**

El uso de tecnología es limitado o parcial:

- Todos usan smartphones para comunicación y búsqueda de información agrícola básica.
- Algunos utilizan computadoras de escritorio para análisis de datos cuando hay disponibilidad.
- El acceso a internet es intermitente o limitado en zonas rurales.
- No cuentan con plataformas integradas para la toma de decisiones agrícolas en tiempo real.

**Intereses y Necesidades en Soluciones Agrícolas**

- **Optimización de recursos**: Buscan soluciones que les ayuden a aplicar agua y fertilizantes solo cuando es necesario, para ahorrar insumos costosos.
- **Automatización de decisiones**: Consideran útil una plataforma que indique en tiempo real las necesidades de riego y fertilización del cultivo.
- **Accesibilidad**: Necesitan herramientas que funcionen offline o con baja conectividad y que sean fáciles de usar, incluso en zonas remotas.
- **Adaptabilidad cultural**: Se valora que la solución incluya un lenguaje sencillo o, en algunos casos como en Cusco, compatibilidad cultural como lenguaje quechua.
- **Capacitación**: Todos los entrevistados señalan que la capacitación es clave para adoptar nuevas tecnologías de forma efectiva.

**Preferencias y Comportamientos**
- Los productores rurales tradicionales tienen un enfoque empírico y práctico.
- Valoran las soluciones que mejoren la productividad y reduzcan costos operativos.
- Prefieren herramientas que sean sencillas, visuales, y que no dependan completamente de internet.
- Se muestran abiertos a la adopción tecnológica si se demuestra un beneficio económico claro y rápido.
- Valoran altamente la experiencia compartida con otros agricultores para validar nuevas herramientas.

**Estadísticas y Porcentajes**
- El 100% de los entrevistados mostró interés en una herramienta que indique en tiempo real las necesidades de su cultivo.
- El 100% manifestó que la falta de precisión en el riego y fertilización les ha generado pérdidas económicas.
- El 100% utiliza celular para tareas básicas de comunicación agrícola, pero no plataformas especializadas.
- El 100% considera importante que la tecnología funcione offline o en lugares con señal deficiente.
- El 100% cree que el cambio climático ha afectado su producción y reconocen la necesidad de adaptarse con nuevas herramientas.
- El 100% valoraría soluciones que, además de ser efectivas, incluyan capacitación práctica para su uso.


Con base en estas entrevistas, se puede concluir que los productores rurales tradicionales entrevistados tienen una fuerte disposición a adoptar soluciones tecnológicas que les permitan optimizar el uso de recursos como agua y fertilizantes, mejorar su productividad y adaptarse al cambio climático. Sin embargo, las herramientas deben ser accesibles, intuitivas, funcionar en condiciones de baja conectividad, y venir acompañadas de procesos de capacitación prácticos. Existe una clara oportunidad para NutriControl de posicionarse como una solución transformadora en este segmento si se atienden estas necesidades fundamentales.

**Segmento de Productores Tecnificados de Cultivos de Alto Valor**

**Perfil Demográfico**

Edades: Promedio de 25 años.
Ubicación Geográfica: Regiones agrícolas de alta producción como Ica (La Tinguiña y Chincha).
Actividad Principal: Producción de cultivos de exportación como arándano, palta Hass y uva Red Globe.
Tamaño de operación: Predios entre 45 a 60 hectáreas, orientados a mercado internacional.

**Experiencia y Conocimientos en Agricultura**

* Todos los entrevistados tienen experiencia directa en agricultura tecnificada.

* Manejan cultivos de alta rentabilidad, aplicando técnicas como fertirriego, uso de sensores de humedad, estaciones meteorológicas y software de trazabilidad.

* Aunque utilizan tecnología, muchos procesos todavía dependen de la interpretación manual de datos, lo que genera brechas de eficiencia.

**Herramientas y Tecnologías Utilizadas**

- Uso extendido de sensores de humedad y estaciones meteorológicas.
- Sistemas básicos de control de riego y fertirriego gestionados desde consolas.
- Hojas de Excel y plataformas digitales simples para registro y trazabilidad de insumos.
- Acceso a laptops y smartphones; en algunos casos con conectividad limitada en campo.

**Intereses y Necesidades en Soluciones Agrícolas**

- **Automatización inteligente**: Buscan soluciones que permitan tomar decisiones autónomas basadas en datos en tiempo real (riego y fertilización automática sin intervención manual).
- **Optimización de recursos**: Desean reducir el desperdicio de agua y fertilizantes, mejorando su rentabilidad sin sacrificar calidad.
- **Trazabilidad automática**: Valoran enormemente que cada acción de riego o fertilización quede registrada automáticamente para cumplir estándares de exportación.
- **Interfaz integrada y modular**: Quieren plataformas que integren clima, suelo y gestión de cultivos, adaptables al crecimiento de sus operaciones.

**Preferencias y Comportamientos**

- Son usuarios que priorizan precisión, rentabilidad y cumplimiento de estándares de calidad de exportación.
- Prefieren tecnologías confiables, predictivas y fáciles de integrar con sistemas actuales.
- Demandan soluciones que no requieran alta intervención técnica para su operación diaria.
- Están dispuestos a invertir en tecnología siempre que el retorno en ahorro de recursos y mejora de calidad sea tangible y rápido.
- Valoran las plataformas escalables que crecen según la necesidad de la finca.

**Estadísticas y Porcentajes**

- El 100% de los entrevistados valora altamente la automatización de riego y fertilización basada en datos reales.
- El 100% ha experimentado pérdidas o problemas de calidad por falta de control preciso de fertilizantes o agua.
- El 100% gestiona actualmente reportes de riego y fertilización de manera manual o semimanual.
- El 100% considera crítica la trazabilidad de insumos para poder exportar sus productos.
- El 100% prefiere una solución modular que se adapte al crecimiento de su operación.
- El 100% considera la baja conectividad en campo como un reto a superar mediante herramientas que funcionen offline o en modo híbrido.


Con base en estas entrevistas, se puede concluir que los productores tecnificados de cultivos de alto valor tienen una alta disposición a adoptar tecnologías que automaticen decisiones críticas como riego y fertilización, mejoren la trazabilidad y optimicen el uso de recursos. Su prioridad es asegurar la calidad de exportación mientras reducen costos operativos. NutriControl tiene una gran oportunidad de posicionarse en este segmento si ofrece soluciones inteligentes, modulares, fáciles de integrar y capaces de operar bajo condiciones de conectividad limitada.


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

***To-Be Scenario Map:*** **Productores rurales tradicionales (pequeños y medianos agricultores)**

![Recurso creado en Miro](Resources/Chapter%2003/To-Be/ToBe1.PNG)

***To-Be Scenario Map:*** **Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación)**

![Recurso creado en Miro](Resources/Chapter%2003/To-Be/ToBe2.PNG)

<div style="page-break-after: always;"></div>

### 3.2. *User Stories:*

***Epics***

<table>
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Historias de usuario relacionadas</th>
  </tr>
  <tr>
    <td>EP-01</td>
    <td>Presentación de NutriControl</td>
    <td>Como usuario potencial, cuando ingrese a la Landing Page de NutriControl, quiero poder ver una presentación clara de la solución, incluyendo su funcionamiento, características y opciones de planes, para poder decidir si la plataforma satisface mis necesidades y si quiero registrarme.
    </td>
    <td>US-01, US-02, US-03</td>
  </tr>
  <tr>
    <td>EP-02</td>
    <td>Gestión de Usuarios</td>
    <td>Como usuario, cuando ingrese a la plataforma NutriControl, quiero poder registrarme, iniciar sesión y gestionar mi información personal, de modo que pueda acceder a todos los beneficios de la solución y mantener mis datos actualizados en todo momento.
    </td>
    <td>US-04, US-05, US-06, US-22, US-23</td>
  </tr>
  <tr>
    <td>EP-03</td>
    <td>Gestión de Campos Agrícolas</td>
    <td>Como productor agrícola, cuando ingrese a NutriControl, quiero poder gestionar mis campos agrícolas, lo que incluye agregar, editar y eliminar campos, para poder automatizarlos y tener un control eficiente de los recursos y las tareas en mis cultivos.
    </td>
    <td>US-07, US-08, US-09</td>
  </tr>
  <tr>
    <td>EP-04</td>
    <td>Gestión de Cultivos</td>
    <td>Como productor agrícola, cuando acceda a la plataforma, quiero poder gestionar mis cultivos dentro de los campos agrícolas, permitiéndome agregar, editar y eliminar cultivos según mis necesidades, para optimizar el manejo de mis recursos agrícolas.
    </td>
    <td>US-10, US-11, US-12</td>
  </tr>
  <tr>
    <td>EP-05</td>
    <td>Gestión de Dispositivos IOT y Automatización</td>
    <td>Como productor agrícola, cuando acceda a mis campos agrícolas en NutriControl, quiero poder conectar y gestionar dispositivos IOT que automatizan tareas como el riego y la fertilización, y recibir alertas sobre su estado, de modo que pueda optimizar el monitoreo y control de mis cultivos.
    </td>
    <td>US-13, US-14, US-16, US-18</td>
  </tr>
  <tr>
    <td>EP-06</td>
    <td>Inteligencia Agrícola y Optimización</td>
    <td>Como agricultor, cuando necesite mejorar el rendimiento de mis cultivos, quiero recibir recomendaciones, alertas y análisis predictivos basados en datos inteligentes, para tomar decisiones más informadas sobre el riego, la fertilización y otros aspectos agrícolas, optimizando el uso de recursos y mejorando la producción.
    </td>
    <td>US-15, US-17, US-19, US-20, US-21</td>
  </tr>
</table>



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
    Escenario 1: Visualizar la descripción general de NutriControl
    <br><br>
    Dado que el usuario potencial ingresa a la Landing Page,
    Cuando acceda a la sección principal,
    Entonces podrá visualizar información sobre el funcionamiento de NutriControl
    Y entenderá su propuesta de valor.
    <br><br>
    Escenario 2: Navegación fluida a la sección de información
    <br><br>
    Dado que el usuario está en la Landing Page,
    Cuando haga clic en el botón "¿Qué es NutriControl?",
    Entonces deberá ser dirigido de forma fluida a la sección informativa
    Y podrá regresar fácilmente al inicio.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-02</td>
    <td>Características de NutriControl</td>
    <td>Como usuario potencial, cuando navegue dentro de las secciones de la Landing Page de NutriControl, quiero poder visualizar características específicas de lo que NutriControl ofrece y ver si se adecuan a mis necesidades.</td>
    <td>
    Escenario 1: Visualizar las características principales
    <br><br>
    Dado que el usuario potencial navega por la Landing Page,
    Cuando llegue a la sección de características,
    Entonces podrá visualizar una lista de funcionalidades destacadas de NutriControl
    Y entender para qué sirve cada una.
    <br><br>
    Escenario 2: Información expandida de características
    <br><br>
    Dado que el usuario esté interesado en una funcionalidad específica,
    Cuando haga clic en "Más información" de una característica,
    Entonces se desplegará una descripción detallada
    Y podrá cerrar esa información para seguir navegando.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-03</td>
    <td>Sección de planes o membresías</td>
    <td>Como usuario potencia, cuando navegue dentro de las secciones de la Landing Page de NutriControl, quiero poder visualizar una sección de planes en los cuales ver los beneficios adicionales que tendría fuera de un plan 
     Freemium. 
    </td>
    <td>
    Escenario 1: Visualizar todos los tipos de planes
    <br><br>
    Dado que el usuario potencial está navegando por la Landing Page,
    Cuando acceda a la sección de planes,
    Entonces podrá visualizar todos los tipos de planes disponibles
    Y comparar sus beneficios.
    <br><br>
    Escenario 2: Diferenciación clara entre planes
    <br><br>
    Dado que el usuario potencial observa los planes,
    Cuando revise las características,
    Entonces podrá identificar las diferencias entre el plan Freemium y los planes Premium
    Y entender qué beneficios adicionales ofrece cada uno.
    </td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-04</td>
    <td>Registro de Usuario</td>
    <td>Como usuario, cuando ingrese a la App Web o descargue el App Móvil, quiero poder registrarme con un correo electrónico y contraseña para poder usar NutriControl.</td>
    <td>
    Escenario 1: Registro exitoso
    <br><br>
    Dado que un usuario nuevo quiere registrarse,
    Cuando ingrese un correo electrónico válido y una contraseña segura,
    Entonces podrá completar el registro
    Y recibirá una confirmación de creación de cuenta.
    <br><br>
    Escenario 2: Error en el registro por datos inválidos
    <br><br>
    Dado que un usuario quiere registrarse,
    Cuando ingrese un correo inválido o una contraseña débil,
    Entonces el sistema mostrará un mensaje de error
    Y le pedirá corregir los datos antes de continuar.
    <br><br>
    Escenario 3: Confirmación visual del registro
    <br><br>
    Dado que el usuario haya terminado el registro,
    Cuando se envíe el formulario correctamente,
    Entonces verá una pantalla de "Registro exitoso"
    Y se le ofrecerá iniciar sesión de inmediato.
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-05</td>
    <td>Inicio de Sesión</td>
    <td>Como usuario, cuando ingrese a la App Web o descargue el App Móvil, quiero poder iniciar sesión con mis credenciales ya creadas en el registro de NutriControl.</td>
    <td>
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-06</td>
    <td>Recuperación de Contraseña</td>
    <td>Como usuario, cuando ingrese a la App Web o descargue el App Móvil, quiero poder recuperar o cambiar mi contraseña en caso la haya olvidado.</td>
    <td>
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-07</td>
    <td>Adición de Campos Agrícolas</td>
    <td>Como productor agrícola, cuando ingrese al inicio de NutriControl, quiero poder agregar los Campos Agrícolas que deseo automatizar.</td>
    <td>
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-08</td>
    <td>Edición de Campos Agrícolas</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Campos Agrícolas, quiero poder editar la información de los Campos que poseo.</td>
    <td>
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-09</td>
    <td>Eliminación de Campos Agrícolas</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Campos Agrícolas, quiero poder eliminar cualquier Campo Agrícola que posea.</td>
    <td>
    </td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-10</td>
    <td>Registro de Cultivos</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Campos Agrícolas, quiero poder agregar cultivos dentro de mis campos.</td>
    <td>
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-11</td>
    <td>Edición de Cultivos</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Cultivos de los Campos, quiero poder editar la información de mis Cultivos.</td>
    <td>
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-12</td>
    <td>Eliminación de Cultivos</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Campos de los Campos, quiero poder eliminar ciertos cultivos dentor de mis Campos Agrícolas.</td>
    <td>
    </td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-13</td>
    <td>Conectar y Adicionar Dispositivos IOT a mis Cultivos</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Campos Agrícolas, quiero registrar y adicionar a mis Campos los dispositivos IOT que están presentes en mis cultivos.</td>
    <td>
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-14</td>
    <td>Desconectar Dispositivos IOT a mis Cultivos</td>
    <td>Como productor agrícola, cuando ingrese a ver mis Campos Agrícolas, quiero desactivar los dispositivos IOT que están presentes en mis cultivos.</td>
    <td>
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-15</td>
    <td>Alertas del pH del Suelo</td>
    <td>Como agricultor rural, cuando no entiendo los niveles de pH del suelo, quiero recibir una alerta con una recomendación sencilla para saber qué hacer.</td>
    <td>
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-16</td>
    <td>Alertas y Configuración del Riego Automático</td>
    <td>Como agricultor rural, cuando necesito usar el riego automático, quiero recibir una alerta cuando el riego esté completado o necesite activar el riego en cierta determinada zona de mis cultivos.</td>
    <td>
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-17</td>
    <td>Recomendaciones y Toma de decisón de los Cultivos</td>
    <td>Como agricultor rural, cuando necesito recomendaciones sobre la toma de decisiones, quiero recibir consejos sobre que hacer respecto al estado de cada cultivo.</td>
    <td>
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-18</td>
    <td>Gestión del Riego y Fertilización</td>
    <td>Como agricultor rural, cuando necesito gestionar el riego automático y fertilización, quiero poder entrar a manejar el estado de mis dispositivos de riego y fertilización para poder configurarlos según mis necesidades y recomendaciones.</td>
    <td>
    </td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-19</td>
    <td>Ahorro de Recursos</td>
    <td>Como agricultor tecnificado, cuando necesito reducir o minimizar recursos, quiero poder recibir recomendaciones de uso de los recursos como el agua o fertilizanes en mis cultivos.</td>
    <td>
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-20</td>
    <td>Análisis Predictivo de Cultivos</td>
    <td>Como agricultor tecnificado, cuando conocer información de ayuda a futuro sobre mis cultivos, quiero poder revisar en base al registro de mis cultivos y técnicas empleadas, datos predictivos sobre que hacer en diferentes ocasiones.</td>
    <td>
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-21</td>
    <td>Recomendaciones de Cultivos</td>
    <td>Como agricultor tecnificado, cuando necesito recibir recomendaciones sobre mis cultivos o técnicas, quiero poder visualizar información sobre recomendaciones para cada tipo de cultivo o terreno de campo agrícola.</td>
    <td>
    </td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-22</td>
    <td>Planes de Suscripción</td>
    <td>Como usuario, cuando necesito adquirir más beneficios o elegir un plan de suscripción de acuerdo a mis necesidades, quiero poder visualizar detalles sobre planes premium o freemium sobre NutriControl y elegir la mejor opción para mis necesidades.</td>
    <td>
    </td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-23</td>
    <td>Configuración de Cuenta</td>
    <td>Como usuario, cuando necesito cambiar información personal de mi cuenta o visualizar, quiero poder tener una sección de Perfil dentro de NutriControl para ver toda tipo de esa información.</td>
    <td>
    </td>
    <td>EP-02</td>
  </tr>
</table>



<div align="justify">



***Technical User Stories***



</div>

### 3.3. *Impact Mapping*

<div align="justify">
El impact map es una herramienta estratégica que permite identificar de manera precisa las características de una aplicación que pueden ser utilizadas o mejoradas para cumplir con un objetivo empresarial específico. Al partir del objetivo clave, se desglosan los comportamientos necesarios de los usuarios, se definen las acciones que deben realizar en la aplicación, se identifican las características necesarias para habilitar esas acciones, se evalúa el impacto potencial de cada característica en el logro del objetivo, y finalmente se crea un plan de acción detallado que guía el desarrollo y mejora continua de la aplicación, alineando así las acciones de los usuarios con los objetivos estratégicos de la empresa.

</div>

<br>

**Productores rurales tradicionales (pequeños y medianos agricultores) y Productores tecnificados de cultivos de alto valor (orientados al mercado de exportación):**

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

En esta sección introduciremos y explicaremos el proceso realizado para las decisiones de nivel estratégico aplicando Domain-Driven Design. 

### 4.1.1. *EventStorming*

<div align = "justify">
Esta es la técnica colaborativa utilizada para modelar sistemas complejos y entender el dominio del problema, donde explicamos y evidenciamos el proceso con el fin de plantear una primera aproximación al modelado general e identificando el mayor nivel de detalle posible. Este fue desarrollado en las siguientes fases:

1. **Unstructured Exploration:** 

<br>
En esta fase, el equipo exploró libremente el dominio del problema, compartiendo conocimientos y capturando ideas sin una estructura formal. El objetivo fue generar una visión amplia y completa del sistema, sentando las bases para las siguientes fases del modelado.

  ![Unstructured Exploration](Resources/Chapter%2002/EventStorming/Unstructured-Exploration.png)

2. **Timelines:**  
<br>
En esta fase, el equipo organizó los eventos identificados en un flujo cronológico, visualizando su secuencia y las interacciones entre ellos. Esto ayudó a identificar dependencias y puntos críticos, facilitando la comprensión del sistema y la planificación de las siguientes etapas del modelado.
 
 ![Timelines](Resources/Chapter%2002/EventStorming/timelines.png)

3. **Pain Points:**   
<br>
En esta fase, el equipo identificó los problemas o desafíos clave dentro del dominio del sistema. Se enfocaron en los puntos críticos donde los usuarios o procesos pueden enfrentar dificultades o ineficiencias.
 
 ![Pain Points](Resources/Chapter%2002/EventStorming/Pain-points.png)

4. **Pivotal Points:**  
<br>
En esta fase, el equipo identificó los eventos clave que tienen un impacto significativo en el sistema y que podrían cambiar el curso de las decisiones o procesos. 

![Pivotal points](Resources/Chapter%2002/EventStorming/pivotal-points.png)

5. **Commands:**   
<br>
En esta fase, el equipo identificó las acciones  que deben ser ejecutados dentro del sistema para que los eventos ocurran o los procesos se inicien. Estos comandos son decisiones o instrucciones claras que desencadenan eventos específicos y ayudan a guiar el flujo de trabajo en el sistema.

![Commands](Resources/Chapter%2002/EventStorming/Commands.png)


</div>


#### 4.1.1.1. *Candidate Context Discovery*

<div align = "justify">

En esta sección, el equipo, a partir del dominio modelado con EventStorming, explicó y evidenció el proceso realizado durante la sesión de Candidate Context Discovery, cuyo objetivo fue identificar los bounded contexts.La sesión duró 1 hora con 50 minutos, y se utilizó la herramienta miro, complementando la explicación con capturas de los cambios progresivos en EventStorming.

6. **Policies:**   
<br>
En esta fase, el equipo identificó las reglas o políticas que rigen el comportamiento del sistema. Estas políticas son restricciones, normativas o criterios que deben ser seguidos para tomar decisiones dentro del proceso.

![Commands](Resources/Chapter%2002/EventStorming/policies.png)

7. **Read Models:**   
<br>
En esta fase , el equipo se centró en identificar los modelos de lectura que permiten consultar y visualizar la información almacenada en el sistema. 

![Commands](Resources/Chapter%2002/EventStorming/Read-models.png)

8. **External Systems:**   
<br>
En esta fase, el equipo identificó y analizó los sistemas externos con los que el sistema principal interactúa. Estos pueden incluir aplicaciones, bases de datos, servicios de terceros o plataformas externas que proporcionan o reciben información del sistema. 

![Commands](Resources/Chapter%2002/EventStorming/external-systems.png)

9. **Aggregates:**    
<br>
En esta fase, el equipo definió las entidades principales que agrupan y gestionan los datos relacionados como una unidad. Los Aggregates aseguran la consistencia de los datos y aplican las reglas de negocio dentro de sus límites.

![Commands](Resources/Chapter%2002/EventStorming/Aggregates.png)

10. **Bounded Contexts:**
<br>
En esta fase, el equipo identificó los límites dentro de los cuales un modelo específico es aplicable y coherente. Cada Bounded Context define un área del sistema con su propio conjunto de reglas, terminología y lógica de negocio.

![Commands](Resources/Chapter%2002/EventStorming/Bounded-Contexts.png)

**Enlace a los diagramas en Miro:** [https://miro.com/app/board/uXjVI-UYdMU=/?share_link_id=788988253384](https://miro.com/app/board/uXjVI-UYdMU=/?share_link_id=788988253384)


</div>



#### 4.1.1.2. *Domain Message Flows Modeling*

<div align = "justify">
Utilizamos el Domain Message Flows Modeling para mapear cómo los mensajes fluyen entre los componentes del sistema y los bounded contexts. Este enfoque nos permite identificar interacciones clave, optimizar la comunicación entre contextos y asegurar que el diseño esté alineado con los objetivos del negocio, mejorando la eficiencia y escalabilidad del sistema. <br></br>


1. **Registro e instalación de sensores**  
   </br>
   ![Escenario1](Resources/Chapter%2004/Domain-Message-Flows-Modeling/Escenario1.png)

2. **Activación del riego automatizado**  
   </br>
   ![Escenario2](Resources/Chapter%2004/Domain-Message-Flows-Modeling/Escenario2.png)

3. **Recepción de alerta por condiciones críticas**  
   </br>
   ![Escenario3](Resources/Chapter%2004/Domain-Message-Flows-Modeling/Escenario3.png)

4. **Visualización de reportes y análisis**  
   </br>
   ![Escenario4](Resources/Chapter%2004/Domain-Message-Flows-Modeling/Escenario4.png)



</div>


#### 4.1.1.3. *Bounded Context Canvases*

<div align = "justify">
En esta sección se describen los bounded contexts de AgroSense utilizando un proceso iterativo basado en el Bounded Context Canvas. Se documento el diseño de cada contexto, incluyendo su definición general y reglas de negocio principales.

##### Proceso de Diseño Iterativo

 - Context Overview Definition: Se definieron los límites de cada bounded context basándose en las áreas funcionales clave de AgroSense, garantizando que cada contexto conservara su enfoque y coherencia con su propósito.Los bounded context definidos fueron:  
 *Plans & Membership Management*, *User Registration & Authentication**, *User Profile Management**, *Automated Irrigation Control*, *Field Registration & Management**, **Sensors and Systems Setup* y *Crop Monitoring & Field Data Management*.

 - Business Rules Distillation & Ubiquitous Language Capture: En cada bounded context se registraron las reglas de negocio y el lenguaje común utilizado por los usuarios. En Automated Irrigation Control se adoptaron términos como “irrigation cycle scheduling” y “automatic sensor activation”; en Crop Monitoring & Farm Data Management se estandarizó el uso de conceptos como “harvest record” y “field data analysis”; y en Sensors and Systems Setup se definieron términos como “sensor calibration” y “device registration”.

 - Capability Analysis: Se evaluaron las capacidades requeridas en cada bounded context, resaltando cómo cada uno aporta al funcionamiento global de la plataforma. Automated Irrigation Control permite programar y ejecutar ciclos de riego de manera automática basados en datos de sensores; Crop Monitoring & Farm Data Management facilita la recopilación, análisis y visualización de información crítica sobre los cultivos; Sensors and Systems Setup habilita la instalación, calibración y gestión de sensores y sistemas de monitoreo; y Field Registration & Management ofrece las herramientas para registrar, organizar y administrar los campos agrícolas dentro de la aplicación.

 - Capability Layering (si aplica): No se implementó una segmentación adicional por capas en cada contexto, ya que la estructura actual de los contextos es lo suficientemente clara y coherente como para no requerir una división adicional.

 - Dependencies Capture: Se identificaron dependencias clave entre los distintos bounded contexts. Automated Irrigation Control depende de Sensors and Systems Setup para recibir los datos en tiempo real que permiten activar los sistemas de riego, mientras que Crop Monitoring & Farm Data Management utiliza la información almacenada en Field Registration & Management para organizar los datos por campo o parcela.

 - Design Critique : Se llevaron a cabo revisiones internas exhaustivas del diseño para garantizar que cada contexto tuviera la autonomía necesaria y que sus interdependencias estuvieran claramente justificadas. Durante estas evaluaciones, se analizó cuidadosamente si las decisiones de diseño promovían la flexibilidad operativa, la escalabilidad y la facilidad de mantenimiento a largo plazo, con el objetivo de asegurar una solución sostenible y adaptable a futuras necesidades.

Se identificaron varias relaciones clave entre los distintos bounded contexts. La relación entre Field Registration & Management y Crop Monitoring & Farm Data Management sigue el patrón Customer/Supplier, donde Field Registration & Management actúa como proveedor al registrar cultivos y campos agrícolas, y Crop Monitoring & Farm Data Management consume esta información para asociar datos de monitoreo y análisis a campos específicos. Por otro lado, Sensors and Systems Setup se comporta como un Conformist respecto a Automated Irrigation Control, proporcionando datos críticos que deben ser utilizados tal como se generan para activar el riego automático. Además, Sensors and Systems Setup y Crop Monitoring & Farm Data Management comparten un Shared Kernel, ya que ambos necesitan sincronizar datos de sensores (como temperatura, humedad y luminosidad) para sus respectivos procesos de activación de riego y monitoreo de cultivos. Finalmente, la interacción entre Automated Irrigation Control y Field Registration & Management se maneja mediante un Anti-Corruption Layer, lo que permite traducir los datos de cultivos o zonas registradas en instrucciones claras para los sistemas de riego, sin que las complejidades del modelo de registro de campo interfieran en la lógica de automatización del riego.

</div>




### 4.1.2. *Context Mapping*

<div align = "justify">
Para AgroSense, utilizamos un enfoque iterativo para diseñar y visualizar los bounded contexts, con base en las funcionalidades propuestas para resolver los problemas del segmento objetivo. El proceso incluyó:

1. **Identificación de Capacidades Clave:**  
   Se mapearon las capacidades necesarias para que AgroSense proporcione valor a los agricultores y técnicos agrícolas. Estas capacidades incluyen monitoreo y gestión de cultivos, generación de reportes y análisis de datos de sensores.

2. **Revisión de Dependencias y Problemas Actuales:**  
   Basándonos en los retos identificados en el As-Is, como la falta de integración y duplicación de esfuerzos, evaluamos cómo diseñar contexts que minimicen dependencias entre módulos y optimicen el uso compartido de datos.

3. **Generación de Diseños Candidatos:**  
   Se propusieron alternativas de bounded contexts, cada una evaluada con preguntas clave para maximizar la eficiencia, escalabilidad y alineación con los objetivos del proyecto.

---

**Preguntas Consideradas en el Proceso**

Se exploraron los siguientes escenarios para guiar la configuración óptima:

- **¿Qué pasaría si movemos la funcionalidad de análisis de sensores a otro bounded context?**  
   Evaluamos la posibilidad de separar "Análisis de Cultivos" en su propio context, liberando al módulo principal de "Gestión de Cultivos" de procesos computacionales intensos.

- **¿Qué pasaría si partimos el bounded context de monitoreo de cultivos en múltiples bounded contexts?**  
   Propuesta para dividir en "Gestión de Sensores" y "Visualización de Datos de Cultivos", permitiendo enfoques más especializados.

- **¿Qué pasaría si creamos un shared service para datos de sensores?**  
   Analizamos centralizar la recolección y procesamiento de datos de sensores en un "Servicio Compartido de Sensores", reduciendo duplicación entre contexts.

- **¿Qué pasaría si creamos un Anti-Corruption Layer para integraciones externas?**  
   Propusimos una capa que aísle AgroSense de sistemas externos, como plataformas de análisis climático o APIs de terceros.

---

**Discusión de Alternativas de Context Mapping**

1. **Alternativa 1: Contextos Mínimos Monolíticos**
   - **Ventajas:** Diseño inicial simple.
   - **Desventajas:** Falta de modularidad, dificultad para escalar funcionalidades específicas.

2. **Alternativa 2: Contextos Especializados con Shared Kernel**
   - **Ventajas:** Permite centralizar capacidades compartidas (p. ej., autenticación, datos de sensores).
   - **Desventajas:** Aumenta la complejidad inicial de configuración.

3. **Alternativa 3: Customer/Supplier con Anti-Corruption Layer**
   - **Ventajas:** Ideal para manejar dependencias externas y mantener integridad interna.
   - **Desventajas:** Requiere mayor esfuerzo en la implementación de la capa de integración.

4. **Alternativa 4: División por Sub-capacidades**
   - **Ventajas:** Reduce la complejidad de contexts individuales.
   - **Desventajas:** Podría fragmentar demasiado el sistema, complicando el mantenimiento.

---

## **Diseño Final Seleccionado**

El equipo optó por un enfoque híbrido que combina las alternativas 2 y 3:

- **Contextos Especializados:**  
   - **Monitoreo y Gestión de Cultivos:** Gestión de datos provenientes de sensores.  
   - **Análisis de Datos de Sensores:** Proceso de recolección de datos obtenidos de los sensores.  
   - **Generación de Reportes:** Consolidación de datos en informes descargables.

- **Shared Kernel:**  
   - Autenticación y gestión básica de usuarios.  
   - Datos históricos y almacenamiento centralizado de datos de sensores.  

- **Anti-Corruption Layer:**  
   - Manejo de interacciones con APIs externas (clima, fertilizantes, etc.).

---

## **Visualización Final**

Los bounded contexts diseñados muestran relaciones claras:  
- **Relación Customer/Supplier** entre "Monitoreo y Gestión de Cultivos" y "Análisis de Datos de Sensores".  
- Uso de un **Shared Kernel** para servicios compartidos como autenticación.  
- Integración externa a través de un **Anti-Corruption Layer**, asegurando robustez frente a cambios en servicios externos.
</div>

### 4.1.3. *Software Architecture*

A continuación, se visualizarán los diagramas C4.

#### 4.1.3.1. *Software Architecture Context Level Diagrams*

![Artefacto hecho en Structurizr](Resources/Chapter%2004/software-architecture/Software%20Architecture%20Context%20Diagram.png)

#### 4.1.3.2. *Software Architecture Container Level Diagrams*

![Artefacto hecho en Structurizr](Resources/Chapter%2004/software-architecture/Software%20Architecture%20Container%20Diagrams.png)

#### 4.1.3.3. *Software Architecture Components Level Diagrams*

![Artefacto hecho en Structurizr](Resources/Chapter%2004/software-architecture/Software%20Architecture%20Components%20Diagrams.png)

## 4.2. *Tactical-Level Domain-Driven Design*

En este capítulo explicamos y presentamos nuestra propuesta para la perspectiva táctica del diseño de la solución de software.

### 4.2.1. *Bounded Context: <Bounded Sensors and Systems Setup>Sensors and Systems Setup*
Sensors and Systems Setup gestiona todo lo relacionado con el registro, instalación y configuración de sensores y dispositivos agrícolas en el sistema AgroSense.  
Incluye desde el registro inicial de sensores hasta su asignación a zonas específicas, así como su calibración y activación para la operación en campo.  
Este contexto es crítico, ya que asegura que los dispositivos estén correctamente configurados para recopilar datos de calidad, permitiendo que el resto de las operaciones del sistema funcionen de manera eficiente.

#### 4.2.1.1. *Domain Layer*
Esta capa define las entidades y objetos de valor fundamentales relacionados con la instalación y organización de sensores agrícolas. Aquí se representa la lógica central del negocio, encargada de modelar cómo se administran los dispositivos y las áreas de cultivo.
- **Sensor**: La entidad principal que representa los dispositivos responsables de recopilar datos como temperatura, humedad o niveles de luz dentro del campo. Cada sensor tiene atributos como tipo, estado operativo y ubicación.
- **Sensor Configuration**: Esta entidad gestiona los parámetros específicos de cada sensor, como la calibración y la frecuencia de medición. Asegura que el sensor esté configurado adecuadamente para su entorno.
- **Sensor Zone**: Un objeto de valor que agrupa múltiples sensores dentro de la misma área geográfica, permitiendo la gestión colectiva de dispositivos en una zona específica del campo.
- **Automated Irrigation System**: Esta entidad gestiona la conexión entre los sensores y los sistemas de riego. Recibe datos de los sensores y los utiliza para tomar decisiones automáticas sobre cuándo activar el riego, basándose en las condiciones del suelo.


#### 4.2.1.2. *Interface Layer*
Esta capa expone los puntos de acceso que permiten a los usuarios o sistemas externos interactuar con la gestión de sensores y zonas, ofreciendo las funcionalidades necesarias para su administración.

- **Sensor Management**: Interfaz que permite la instalación y configuración de los sensores dentro del sistema. Desde aquí, los usuarios pueden agregar nuevos sensores, configurar sus tipos y parámetros, y ver el estado de los dispositivos en tiempo real.
- **Sensor Data Visualization**: Proporciona una interfaz para visualizar los datos recopilados por los sensores, como temperatura, humedad y otros parámetros ambientales. Los usuarios pueden consultar lecturas de sensores individuales y realizar diagnósticos.


#### 4.2.1.3. *Application Layer*
Coordina los procesos de negocio relacionados con la gestión de sensores, actuando como intermediaria entre las reglas del dominio y las interfaces de usuario o externas.

- **Install Sensor**: Coordina el proceso de agregar nuevos sensores al sistema, asegurando que los dispositivos estén configurados correctamente de acuerdo con las necesidades del campo.
- **Update Sensor Configuration**: Se encarga de modificar los parámetros de los sensores existentes, como la frecuencia de medición o la configuración de calibración.
- **Manage Sensor Zones**: Coordina la asignación de sensores a zonas geográficas específicas dentro del campo, facilitando la gestión colectiva de los dispositivos.


#### 4.2.1.4. *Infrastructure Layer*
Esta capa implementa los mecanismos técnicos para la persistencia de sensores y la interacción con sistemas externos, como bases de datos o redes de dispositivos.

- **Sensor Repository**: Implementa el almacenamiento y recuperación de datos de los sensores. Este componente asegura que los sensores sean accesibles y se puedan configurar eficientemente.
- **Sensor Communication Service**: Facilita la comunicación entre los sensores y el sistema central. Es responsable de transmitir los datos de los sensores al sistema para su procesamiento.
- **Configuration Service**: Se encarga de la implementación de configuraciones predeterminadas o personalizadas de los sensores, como la calibración o la frecuencia de actualización, asegurando que se mantengan según lo especificado.



#### 4.2.1.5. *Bounded Context Software Architecture Component Level Diagrams*

Sensors and System Setup Component Diagram:

![Sensor component diagram](Resources/Chapter%2004/Component-Diagrams/SensorsComponent.png)


#### 4.2.1.6. *Bounded Context Software Architecture Code Level Diagrams*

##### 4.2.1.6.1. *Bounded Context Domain Layer Class Diagrams*

Sensors and System Setup Domain Layer diagram:

![Sensor layer diagram](Resources/Chapter%2004/DomainLayer/db1layer.png)

##### 4.2.1.6.2. *Bounded Context Database Design Diagram*

Sensors and System Setup database diagram:

![Sensor databse diagram](Resources/Chapter%2004/DatabaseDesign/db1DatabaseDesign.png)


### 4.2.2. *Bounded Context: <Bounded Plans and Memembership Management>Plans & Membership Management*
Plans & Membership Management se encarga de gestionar los diferentes planes de suscripción que ofrece AgroSense y su relación con los usuarios registrados.  
Este contexto asegura que los usuarios puedan acceder a diferentes niveles de servicio, dependiendo de sus necesidades agrícolas y del tamaño de sus operaciones, manejando además la activación, renovación o cancelación de sus membresías.

#### 4.2.2.1. *Domain Layer*
En esta capa se encuentran las entidades y objetos de valor esenciales que definen el manejo de planes y membresías dentro del sistema.

- **Membership**: Representa la suscripción activa de un usuario, incluyendo su plan actual, fecha de inicio, vencimiento y estado (activo, suspendido, cancelado).
- **Plan**: Define los diferentes tipos de planes disponibles (por ejemplo, Basic, Premium), especificando características como límite de sensores, acceso a reportes, o funcionalidades avanzadas.
- **SubscriptionHistory**: Objeto de valor que mantiene un registro de los cambios de suscripción del usuario a lo largo del tiempo.
- **PaymentInfo**: Objeto de valor que almacena detalles relacionados con la forma de pago y el estado de las transacciones asociadas al plan.

#### 4.2.2.2. *Interface Layer*
Define las interfaces de comunicación que utilizan otros módulos o clientes para interactuar con los servicios de planes y membresías.

- **PlanSummary**: Estructura de datos que expone información sobre los planes disponibles, incluyendo nombre, descripción, costo y características principales.
- **MembershipStatus**: Estructura que representa el estado actual de la suscripción de un usuario, incluyendo plan activo, fechas relevantes y estado de pago.
- **SubscriptionRecord**: Estructura que lista los cambios de plan de un usuario a lo largo del tiempo.

#### 4.2.2.3. *Application Layer*
Esta capa coordina las acciones necesarias para que los usuarios puedan gestionar sus planes de forma correcta, asegurando la correcta interacción entre la lógica de dominio e infraestructura.

- **PlanService**: Servicio de aplicación que permite listar los planes disponibles y consultar sus detalles.
- **MembershipService**: Servicio responsable de manejar la suscripción de un usuario: activación, actualización, renovación y cancelación de membresías.
- **SubscriptionHistoryService**: Servicio que consulta el historial de cambios de suscripción de cada usuario.

#### 4.2.2.4. *Infrastructure Layer
Esta capa se ocupa de la persistencia y de la integración con servicios externos relacionados a pagos y membresías.

- **PlanRepository**: Repositorio encargado de almacenar, recuperar y actualizar los planes de suscripción disponibles.
- **MembershipRepository**: Repositorio que gestiona la persistencia de las membresías activas de los usuarios.
- **PaymentGatewayClient**: Cliente que interactúa con sistemas de pago externos para procesar compras, renovaciones o cancelaciones de membresías.
- **SubscriptionHistoryRepository**: Repositorio encargado de almacenar el historial de cambios de planes de los usuarios.

#### 4.2.2.5. *Bounded Context Software Architecture Component Level Diagrams*

Plans and Memebership Component Diagram:

![Plans component diagram](Resources/Chapter%2004/Component-Diagrams/PlansComponent.png)


#### 4.2.2.6. *Bounded Context Software Architecture Code Level Diagrams*
##### 4.2.2.6.1. *Bounded Context Domain Layer Class Diagrams*

Plans and Memebership Domain Layer diagram:

![Plans layer diagram](Resources/Chapter%2004/DomainLayer/db2layer.png)

##### 4.2.2.6.2. *Bounded Context Database Design Diagram*

Plans and Memebership database diagram:

![Plans databse diagram](Resources/Chapter%2004/DatabaseDesign/db2DatabaseDesign.png)

### 4.2.3. *Bounded Context: <Bounded User Profile Management>User Profile Management*
El contexto de User Management integra todo lo relacionado al registro de nuevos usuarios, autenticación en el sistema y gestión de los perfiles personales.  
Su correcta implementación garantiza que los usuarios tengan acceso seguro y personalizado a las funcionalidades del sistema.

#### 4.2.3.1. *Domain Layer*
En esta capa se modelan las entidades y objetos de valor que permiten representar a los usuarios y sus atributos esenciales dentro del sistema.

- **User**: Entidad principal que almacena información del usuario, como nombre, correo electrónico, número de teléfono, rol asignado y preferencias.
- **Credentials**: Objeto de valor que contiene la información necesaria para la autenticación del usuario (correo electrónico, contraseña encriptada, estado de la cuenta).
- **UserPreferences**: Objeto de valor que administra configuraciones personalizadas del usuario, como preferencias de notificación o idioma.

#### 4.2.3.2. *Interface Layer*

Define las estructuras que permiten exponer y capturar la información necesaria para registrar usuarios, autenticarlos y gestionar sus perfiles.

- **RegistrationForm**: Estructura de datos utilizada para capturar la información de un nuevo usuario al momento del registro.
- **LoginRequest**: Estructura que recibe las credenciales de un usuario que intenta iniciar sesión.
- **ProfileDetails**: Estructura que expone la información personal de un usuario registrado, permitiendo su visualización o edición.
- **UpdateProfileRequest**: Estructura que recoge los nuevos datos cuando un usuario desea actualizar su información de perfil o preferencias.

#### 4.2.3.3. *Application Layer*

Aquí se orquestan los procesos que permiten a los usuarios registrarse, autenticarse y mantener actualizado su perfil, sin involucrar directamente la lógica de negocio ni la infraestructura.

- **UserRegistrationService**: Servicio que gestiona el proceso de creación de nuevas cuentas, validando la información y generando credenciales seguras.
- **AuthenticationService**: Servicio encargado de autenticar a los usuarios durante el login, validando sus credenciales y generando tokens de acceso seguros.
- **ProfileManagementService**: Servicio que permite a los usuarios consultar y actualizar los datos de su perfil personal.

#### 4.2.3.4. *Infrastructure Layer*

Se ocupa de la persistencia de la información de usuarios y credenciales, además de manejar la interacción con servicios de autenticación o notificaciones externas.

- **UserRepository**: Repositorio encargado de almacenar, recuperar y actualizar la información de los usuarios registrados.
- **CredentialsRepository**: Repositorio responsable de la gestión de credenciales seguras asociadas a cada usuario.
- **AuthenticationProvider**: Cliente o adaptador para servicios externos de autenticación o manejo de tokens seguros.

#### 4.2.3.5. *Bounded Context Software Architecture Component Level Diagrams*

User Profile Component Diagram:

![User Profile component diagram](Resources/Chapter%2004/Component-Diagrams/UserComponent.png)

#### 4.2.3.6. *Bounded Context Software Architecture Code Level Diagrams*
##### 4.2.3.6.1. *Bounded Context Domain Layer Class Diagrams*
User Profile Domain Layer diagram:

![User layer diagram](Resources/Chapter%2004/DomainLayer/db3layer.png)



##### 4.2.3.6.2. *Bounded Context Database Design Diagram*
User Profile database diagram:

![User databse diagram](Resources/Chapter%2004/DatabaseDesign/db3DatabaseDesign.png)

### 4.2.4. *Bounded Context: <Bounded Automated Irrigation Control>Automated Irrigation Control*

Este contexto se encarga de la gestión y automatización del sistema de riego dentro de AgroSense.  
La correcta integración de esta capa asegura que los cultivos reciban la cantidad adecuada de agua en el momento oportuno, mejorando la eficiencia agrícola y reduciendo el desperdicio de recursos.

#### 4.2.4.1. *Domain Layer*

En esta capa se modelan las entidades y objetos que representan la lógica de negocio para la gestión del riego automatizado, interactuando con sensores y dispositivos de riego.

- **IrrigationZone**: Entidad que representa una zona específica en el campo que puede ser regada por un sistema de riego. Contiene atributos como el área de la zona, el tipo de cultivo y los parámetros de riego necesarios.
- **IrrigationSystem**: Entidad que gestiona el sistema de riego completo, desde las válvulas hasta los sensores de humedad, controlando la distribución del agua en diferentes zonas del campo.
- **WateringSchedule**: Objeto de valor que define el horario y la cantidad de agua que se debe aplicar en una zona de riego, en función de los datos de humedad y el tipo de cultivo.
- **SoilMoistureSensor**: Objeto de valor que representa los sensores de humedad instalados en el campo, proporcionando datos en tiempo real para activar o desactivar el riego en las zonas correspondientes.

#### 4.2.4.2. *Interface Layer*

Esta capa proporciona las interfaces necesarias para la configuración y monitoreo del sistema de riego automatizado, permitiendo la interacción con los usuarios y la captura de datos para el control del riego.

- **IrrigationConfiguration**: Estructura de datos que permite a los usuarios definir y configurar las zonas de riego, así como los horarios y parámetros de cada una.
- **IrrigationStatus**: Estructura que muestra el estado actual de los sistemas de riego, incluyendo la cantidad de agua distribuida, el estado de los sensores y las zonas activas.
- **WateringRequest**: Estructura que recoge una solicitud para activar o desactivar el riego en una zona específica, ajustada a las condiciones de humedad y las preferencias del usuario.

#### 4.2.4.3. *Application Layer*

Esta capa se encarga de gestionar el flujo de control del sistema de riego, activando y desactivando el riego según las condiciones y la configuración del usuario, sin involucrar la lógica de negocio ni la infraestructura de fondo.

- **IrrigationControlService**: Servicio que orquesta el proceso de activación y desactivación del sistema de riego, ajustándose a los parámetros configurados por el usuario y los datos de humedad de los sensores.
- **WateringScheduleService**: Servicio que gestiona las actualizaciones y consultas sobre los horarios y cantidades de agua en función de las zonas y el clima.
- **SensorMonitoringService**: Servicio que monitorea los datos de los sensores de humedad y envía notificaciones o acciones al sistema de riego para optimizar el uso de agua.

#### 4.2.4.4 *Infrastructure Layer*

En esta capa se encuentran los componentes encargados de la persistencia de los datos de riego y la integración con sistemas externos, como los sensores de humedad y las válvulas de riego.

- **IrrigationRepository**: Repositorio encargado de almacenar y recuperar las configuraciones de riego y las zonas de irrigación.
- **SensorDataRepository**: Repositorio que almacena los datos de los sensores de humedad y otros datos ambientales relacionados con el sistema de riego.
- **IrrigationDeviceController**: Componente que se encarga de la interacción con los dispositivos de riego (válvulas, bombas, sensores), activando o desactivando las operaciones basadas en los datos recibidos del sistema.

#### 4.2.4.5. *Bounded Context Software Architecture Component Level Diagrams*

Automated Irrigation Control Component Diagram:

![Irrigation component diagram](Resources/Chapter%2004/Component-Diagrams/IrrigationComponent.png)

#### 4.2.4.6. *Bounded Context Software Architecture Code Level Diagrams*
##### 4.2.4.6.1. *Bounded Context Domain Layer Class Diagrams*
Automated Irrigation Control Domain Layer diagram:

![Irrigation layer diagram](Resources/Chapter%2004/DomainLayer/db4Layer.png)



##### 4.2.4.6.2. *Bounded Context Database Design Diagram*
Automated Irrigation Control database diagram:

![Irrigation databse diagram](Resources/Chapter%2004/DatabaseDesign/db4DatabaseDesign.png)


### 4.2.5. *Bounded Context: <Bounded Field Registration and Management>Field Registration & Management*

Este contexto se encarga de gestionar el registro, seguimiento y administración de los campos agrícolas dentro de AgroSense.  
Permite a los usuarios registrar y configurar las propiedades de sus campos, tales como la ubicación, el tipo de cultivo y las características del suelo.  
Una gestión adecuada de la información del campo facilita la toma de decisiones en la optimización de recursos y mejora la productividad agrícola.


#### 4.2.5.1. *Domain Layer*

En esta capa se encuentran las entidades y objetos de valor relacionados con el registro y administración de campos agrícolas, incluyendo la configuración de los cultivos y las características del terreno.

- **Field**: Entidad que representa un campo agrícola dentro del sistema. Contiene información sobre su ubicación, tamaño, tipo de cultivo y otras características asociadas, como el tipo de suelo y la disponibilidad de riego.
- **SoilType**: Objeto de valor que representa el tipo de suelo de un campo. Incluye propiedades como la textura, el pH y la capacidad de retención de agua.
- **Crop**: Entidad que define el tipo de cultivo que se está cultivando en un campo. Incluye información sobre las necesidades de agua, el tiempo de cosecha, y los requisitos nutricionales.
- **FieldConfiguration**: Objeto de valor que guarda la configuración personalizada para un campo, como las preferencias de riego, los métodos de fertilización y las prácticas agrícolas aplicadas.

#### 4.2.5.2 *Interface Layer*

Esta capa permite la interacción entre el sistema y el usuario para registrar y gestionar los campos agrícolas, proporcionando la interfaz necesaria para la entrada y visualización de datos.

- **FieldRegistrationForm**: Estructura que permite a los usuarios registrar un nuevo campo, incluyendo detalles como la ubicación, el tamaño, y el tipo de cultivo.
- **FieldManagementDashboard**: Interfaz que presenta un panel de control para gestionar los campos registrados, mostrando información clave como el estado del cultivo, los registros de riego y las recomendaciones de fertilización.
- **CropSelectionForm**: Estructura que permite a los usuarios seleccionar el tipo de cultivo para un campo registrado, teniendo en cuenta factores como la temporada, el clima y los requerimientos del suelo.


#### 4.2.5.3 *Application Layer*

En esta capa se gestionan los procesos que orquestan las operaciones sobre los campos agrícolas, coordinando las actividades entre las entidades y la infraestructura.

- **FieldRegistrationService**: Servicio encargado de gestionar el proceso de registro de un nuevo campo, asegurándose de que toda la información necesaria sea ingresada y almacenada correctamente.
- **FieldManagementService**: Servicio que coordina las operaciones para administrar los campos, incluyendo la actualización de la información de cultivo, el seguimiento de las condiciones del campo y las recomendaciones de acciones agrícolas.
- **CropManagementService**: Servicio que orquesta el registro y gestión de los cultivos dentro de un campo, actualizando sus características y necesidades según la etapa de crecimiento y las condiciones ambientales.

#### 4.2.5.4 *Infrastructure Layer*

Esta capa se encarga de los detalles técnicos relacionados con la persistencia de los datos de los campos y cultivos, así como la integración con sistemas externos para la gestión de recursos.

- **FieldRepository**: Repositorio encargado de almacenar y recuperar la información de los campos registrados, incluidos los detalles sobre la ubicación, el tipo de cultivo y el estado de los cultivos.
- **CropRepository**: Repositorio que gestiona el almacenamiento y recuperación de la información sobre los cultivos, sus características y el seguimiento de su evolución.
- **SoilDataRepository**: Repositorio que almacena los datos relacionados con las propiedades del suelo, como el tipo de suelo y la capacidad de retención de agua.

#### 4.2.5.5. *Bounded Context Software Architecture Component Level Diagrams*

Field Registartion and Management Component Diagram:

![Field component diagram](Resources/Chapter%2004/Component-Diagrams/FieldComponent.png)


#### 4.2.5.6. *Bounded Context Software Architecture Code Level Diagrams*

##### 4.2.5.6.1. *Bounded Context Domain Layer Class Diagrams*
Field Registartion and Management Domain Layer diagram:

![Field layer diagram](Resources/Chapter%2004/DomainLayer/db5layer.png)



##### 4.2.5.6.2. *Bounded Context Database Design Diagram*
Field Registration and Management database diagram:

![Field databse diagram](Resources/Chapter%2004/DatabaseDesign/db5DatabaseDesign.png)


### 4.2.6. *Bounded Context: <Bounded Crop Monitoring and Field Data Managementl>Crop Monitoring & Field Data Management*
Este contexto está encargado de la recopilación, monitoreo y análisis de los datos relacionados con los cultivos y las condiciones del terreno.  
Permite a los usuarios obtener información detallada sobre la salud y el progreso de los cultivos, lo que facilita la toma de decisiones para mejorar el rendimiento y optimizar el uso de recursos.  

#### 4.2.6.1 *Domain Layer*

En esta capa se encuentran las entidades y objetos de valor que representan los datos recogidos de los cultivos y el campo, así como la lógica que se utiliza para analizarlos y extraer información relevante.

- **CropMonitoringData**: Entidad que almacena los datos recogidos de los sensores relacionados con el cultivo, como humedad del suelo, temperatura, niveles de fertilización y otros indicadores importantes para el seguimiento de los cultivos.
- **FieldData**: Entidad que agrupa la información sobre el estado general del campo, incluyendo datos sobre el clima, el tipo de cultivo, la actividad de riego, y otros parámetros que afectan el rendimiento de la agricultura.
- **ClimateData**: Objeto de valor que contiene los datos climáticos recolectados para un campo, como la temperatura, la humedad, la radiación solar y las precipitaciones, los cuales son importantes para realizar predicciones sobre las condiciones de crecimiento de los cultivos.
- **GrowthStage**: Objeto de valor que representa las diferentes etapas de crecimiento de un cultivo, desde la siembra hasta la cosecha. Incluye indicadores que permiten determinar cuándo un cultivo está listo para ser cosechado o si requiere intervenciones específicas.


#### 4.2.6.2. *Interface Layer*

Esta capa presenta las interfaces que permiten a los usuarios consultar y analizar los datos relacionados con sus cultivos, facilitando la visualización de la información y la toma de decisiones.

- **CropMonitoringDashboard**: Interfaz que presenta un panel de control donde los usuarios pueden ver el estado en tiempo real de sus cultivos, incluyendo los datos más relevantes, como la humedad del suelo, el clima y los niveles de fertilización.
- **FieldDataReport**: Interfaz que permite generar reportes detallados sobre el estado del campo, incluyendo información histórica sobre el clima, las condiciones del suelo y el progreso de los cultivos.
- **GrowthStageOverview**: Interfaz que proporciona una visión general del progreso de los cultivos según su etapa de crecimiento, con recomendaciones sobre las acciones a seguir en cada fase.

#### 4.2.6.3 *Application Layer*

La capa de aplicación coordina las operaciones necesarias para acceder y procesar los datos del cultivo y el campo, proporcionando la lógica para la visualización y análisis de la información.

- **CropMonitoringService**: Servicio que gestiona el proceso de recolección y análisis de los datos de los cultivos, asegurando que los sensores se comuniquen correctamente con el sistema y que la información se presente de manera clara a los usuarios.
- **FieldDataAnalysisService**: Servicio encargado de procesar y analizar los datos recopilados sobre el terreno y los cultivos, generando predicciones y recomendaciones sobre el mejor uso de los recursos agrícolas.
- **GrowthStageAnalysisService**: Servicio que se encarga de analizar el progreso de los cultivos en función de su etapa de crecimiento, sugiriendo acciones específicas como el riego o la fertilización necesarias en cada fase.


#### 4.2.6.4 *Infrastructure Layer*

Esta capa incluye los componentes que gestionan la persistencia y el acceso a los datos recopilados sobre los cultivos y las condiciones del campo, así como la integración con sistemas externos de monitoreo.

- **CropMonitoringRepository**: Repositorio encargado de almacenar y recuperar los datos de monitoreo de los cultivos, como la humedad, temperatura, y otros parámetros clave.
- **FieldDataRepository**: Repositorio que almacena los datos relacionados con el campo, incluidos los datos climáticos y la actividad de los cultivos.
- **ClimateDataRepository**: Repositorio que gestiona el almacenamiento y recuperación de los datos climáticos de un campo, que se usan para analizar las condiciones externas que afectan a los cultivos.


#### 4.2.6.5. *Bounded Context Software Architecture Component Level Diagrams*

Crop Monitoring & Field Data Management Component Diagram:

![Crop component diagram](Resources/Chapter%2004/Component-Diagrams/CropComponent.png)


#### 4.2.6.6. *Bounded Context Software Architecture Code Level Diagrams*
##### 4.2.6.6.1. *Bounded Context Domain Layer Class Diagrams*
Crop Monitoring & Field Data Management Domain Layer diagram:

![Crops layer diagram](Resources/Chapter%2004/DomainLayer/db6Layer.png)

##### 4.2.6.6.2. *Bounded Context Database Design Diagram*

Crop Monitoring & Field Data Management database diagram:

![Crops databse diagram](Resources/Chapter%2004/DatabaseDesign/db6DatabaseDesign.png)


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

+ Repositorio GitHub de la Organización: [Ver Organización](https://github.com/Desarrollo-de-Soluciones-IoT-2510-2942)<br><br>
+ Repositorio GitHub del Informe: [Ver Repositorio](https://github.com/Desarrollo-de-Soluciones-IoT-2510-2942/Informe)<br><br>
+ Repositorio GitHub del Backend: [Ver Repositorio](https://github.com/Desarrollo-de-Soluciones-IoT-2510-2942/BackEnd)<br><br>
+ Repositorio GitHub de la Aplicación Web: [Ver Repositorio](https://github.com/Desarrollo-de-Soluciones-IoT-2510-2942/FrontEnd)<br><br>
+ Repositorio GitHub de la Aplicación Móvil: [Ver Repositorio](https://github.com/Desarrollo-de-Soluciones-IoT-2510-2942/MobileApp)<br><br>
+ Repositorio GitHub de la Landing Page: [Ver Repositorio](https://github.com/Desarrollo-de-Soluciones-IoT-2510-2942/LandingPage)<br><br>

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
