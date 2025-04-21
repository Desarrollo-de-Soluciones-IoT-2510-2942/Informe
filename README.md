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
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
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
|TB1| //2025 |Criollo De La Cruz, Diego Anderson| |
|TB1| //2025 || |
|TB1| //2025 || |
|TB1| //2025 |Morales Calderón, Hernan Emilio| |
|TB1| //2025 |Valle Zuta, Abel Andrés| |

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

<div align="justify">



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
            <th>NutriControl</th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/Netafim.png" alt="Logo NeatBeat"></th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/AgroSmart.png" alt="Logo AgroSmart"></th>
            <th><img src="Resources/Chapter%2002/Competitors%20Table/Taranis.png" alt="Logo Taranis"></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2" align="justify">Perfil</td>
            <td align="justify">Overview</td>
            <td align="justify">Es una plataforma en línea que facilita el alquiler de una amplia gama de espacios para eventos, desde salones de eventos hasta casas y alojamientos temporales. Con una interfaz fácil de usar, conecta a arrendadores con arrendatarios, ofreciendo una solución conveniente y eficiente para satisfacer las necesidades de ambos.</td>
            <td align="justify">Plataforma en línea que revoluciona el alquiler de alojamientos a corto plazo, conectando anfitriones y huéspedes en todo el mundo. Ofrece una amplia variedad de opciones de alojamiento, desde habitaciones individuales hasta casas completas.</td>
            <td align="justify">Plataforma en línea que permite a los usuarios buscar y reservar alojamientos vacacionales directamente a través de arrendadores. Ofrece una variedad de opciones de alojamiento, como casas, apartamentos, cabañas y villas, en diferentes destinos, adaptándose a las necesidades y preferencias de los viajeros.</td>
            <td align="justify">Booking.com es una plataforma líder para reservar alojamiento y actividades turísticas en todo el mundo. Ofrece una amplia variedad de opciones, desde hoteles hasta apartamentos, y facilita la búsqueda y reserva según las preferencias y presupuesto de los usuarios.</td>
        </tr>
        <tr>
            <td align="justify">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
            <td align="justify">Proporciona una solución completa para la planificación de eventos, ofreciendo una amplia gama de espacios para eventos y una plataforma intuitiva para gestionar reservas y espacios. Con características como registro gratuito de espacios, búsqueda avanzada y servicio al cliente dedicado, ArrendaFácil simplifica el proceso de planificación de eventos para arrendatarios y arrendadores.</td>
            <td align="justify">Ofrece una amplia variedad de alojamientos en todo el mundo, desde habitaciones individuales hasta casas completas, junto con experiencias locales únicas organizadas por anfitriones. Esto permite a los viajeros personalizar su experiencia y sumergirse en la cultura local.	</td>
            <td align="justify">Se especializa en alquileres vacacionales directamente a través de arrendadores, brindando a los viajeros la oportunidad de disfrutar de una experiencia más auténtica y personalizada. Con una amplia selección de alojamientos vacacionales, Vrbo ofrece opciones para todos los gustos y presupuestos.</td>
            <td align="justify">Destaca por su amplia oferta de alojamiento y servicios, que incluyen hoteles, vuelos, alquiler de coches y actividades turísticas. La plataforma fácil de usar permite a los usuarios encontrar y reservar alojamiento de manera rápida y sencilla, ofreciendo una solución integral para los viajeros.</td>
        </tr>
        <tr>
            <td rowspan="5" align="justify">Perfil de Marketing</td>
            <td align="justify">Mercado Objetivo</td>
            <td align="justify">Dirigido a arrendatarios adultos de 18 años en adelante que buscan espacios para eventos sociales, corporativos o especiales, como bodas, conferencias, fiestas de empresa, entre otros. Además, atrae a empresas y organizaciones que buscan espacios para eventos corporativos y reuniones profesionales dirigidas a un público adulto.</td>
            <td align="justify">Se centra en viajeros adultos de 18 años en adelante, ofreciendo una amplia variedad de alojamientos en todo el mundo, desde habitaciones individuales hasta casas completas, para adaptarse a diferentes necesidades y preferencias de viaje. Además, apunta a grupos de amigos, parejas y familias adultas que buscan opciones de alojamiento que se ajusten a sus requerimientos y presupuestos durante sus vacaciones o escapadas.</td>
            <td align="justify">Está dirigido a familias y grupos de amigos adultos de 18 años en adelante que buscan alquilar casas, villas o cabañas para vacaciones o escapadas grupales. Además, atrae a parejas y grupos de amigos adultos que buscan alquilar alojamientos vacacionales para eventos especiales, como bodas, reuniones familiares o celebraciones de cumpleaños.</td>
            <td align="justify">Orientado a viajeros adultos de 18 años en adelante, busca ofrecer una amplia gama de opciones de alojamiento para adaptarse a diversas necesidades y preferencias durante sus viajes. También se dirige a personas que viajan por negocios, parejas en escapadas románticas, grupos de amigos en vacaciones y familias en busca de opciones de alojamiento cómodas y convenientes.</td>
        </tr>
        <tr>
            <td align="justify">Estrategias de Marketing</td>
            <td align="justify">ArrendaFácil destaca con marketing de contenidos, participación en eventos de la industria y alianzas con proveedores de servicios de eventos para ofrecer soluciones completas a arrendatarios.</td>
            <td align="justify">Airbnb emplea campañas publicitarias en redes sociales y colaboraciones con influencers para promocionar destinos y experiencias únicas. También utiliza programas de referidos para aumentar su base de usuarios.</td>
            <td align="justify">Vrbo se centra en contenido educativo en su sitio web, colaboraciones con agencias de viajes y ofertas exclusivas para atraer a familias y grupos de amigos a reservar a través de su plataforma.</td>
            <td align="justify">Booking.com utiliza estrategias de SEO y SEM, junto con programas de fidelización, para atraer tráfico y fomentar la lealtad del cliente a través de una experiencia personalizada.</td>
        </tr>
        <tr>
            <td align="justify">Productos & servicios</td>
            <td align="justify">Aplicación web que conecta a arrendadores de diversos espacios, como salones de eventos, jardines y locales comerciales, con arrendatarios que buscan alquilar estos espacios para celebrar eventos sociales, corporativos o especiales. Proporciona una variedad de herramientas y servicios para facilitar la búsqueda, reserva y gestión de espacios para eventos.</td>
            <td align="justify">Plataforma en línea donde los usuarios pueden alquilar una variedad de alojamientos a corto plazo, desde habitaciones individuales hasta casas completas, en todo el mundo. Además de alojamiento, Airbnb también proporciona experiencias locales únicas organizadas por anfitriones, como recorridos gastronómicos, clases de cocina y excursiones.	</td>
            <td align="justify">Plataforma para alquilar alojamientos vacacionales directamente a través de los arrendadores. Los usuarios pueden encontrar y reservar una amplia gama de propiedades, que van desde casas y apartamentos hasta cabañas y villas, para sus vacaciones o escapadas en todo el mundo.</td>
            <td align="justify">Plataforma en línea que permite a los usuarios reservar una variedad de alojamientos, incluyendo hoteles, hostales, apartamentos y otros tipos de hospedaje en todo el mundo. Además de alojamiento, Booking.com ofrece la posibilidad de reservar vuelos, alquilar coches y reservar actividades turísticas para completar la experiencia de viaje del usuario.</td>
        </tr>
        <tr>
            <td align="justify">Precios & Costos</td>
            <td align="justify">Los precios de ArrendaFácil varían dependiendo del lugar, el tamaño de la propiedad, servicios, y el tiempo de uso.</td>
            <td align="justify">El costo promedio puede variar significativamente dependiendo de varios factores, como la ubicación, el tipo de alojamiento, la época del año y la demanda local.</td>
            <td align="justify">Los precios en VRBO pueden variar significativamente dependiendo de la ubicación, el tamaño de la propiedad, las comodidades ofrecidas y la temporada del año.</td>
            <td align="justify">Los precios pueden variar significativamente según la ubicación, la temporada, la demanda y el tipo de alojamiento.</td>
        </tr>
        <tr>
            <td align="justify">Canales de distribución (Web y/o móvil)</td>
            <td align="justify">Redes sociales y aplicación web donde los usuarios pueden poner en renta su espacio o alquilar un espacio para eventos.</td>
            <td align="justify">Sitio web de Airbnb, aplicación móvil de Airbnb, socios afiliados y asociaciones, redes sociales y marketing digital.</td>
            <td align="justify">Principalmente su sitio web y su aplicación móvil, así como acuerdos de distribución con otros sitios web de viajes o agencias de viajes en línea.</td>
            <td align="justify">Sitio web de Booking.com, aplicación móvil de Booking, agencias de viajes en línea, alianzas con compañías de viajes, afiliados y asociados.</td>
        </tr>
        <tr>
            <td rowspan="4" align="justify">Análisis SWOT</td>
            <td align="justify">Fortalezas</td>
            <td align="justify">Solución completa para la planificación de eventos.</td>
            <td align="justify">Gran comunidad de anfitriones y usuarios.</td>
            <td align="justify">Variedad de alojamientos en todo el mundo.</td>
            <td align="justify">Interfaz fácil de usar y experiencia intuitiva del usuario.</td>
        </tr>
        <tr>
            <td align="justify">Debilidades</td>
            <td align="justify">Dependencia de la disponibilidad de espacios para eventos.</td>
            <td align="justify">Dependencia de la reputación y opiniones de los usuarios.</td>
            <td align="justify">Posible saturación del mercado de alquiler vacacional.</td>
            <td align="justify">Competencia intensa con otras plataformas de alquiler de alojamiento.</td>
        </tr>
        <tr>
            <td align="justify">Oportunidades</td>
            <td align="justify">Expansión mediante aplicaciones integradas para mejorar la comunicación entre sus usuarios.</td>
            <td align="justify">Desarrollo de nuevas características y servicios para mejorar la experiencia del usuario.</td>
            <td align="justify">Alianzas estratégicas con proveedores de servicios de eventos.</td>
            <td align="justify">Aprovechamiento de la tendencia creciente del turismo y los viajes.</td>
        </tr>
        <tr>
            <td align="justify">Amenazas</td>
            <td align="justify">Cambios en la regulación de alquileres vacacionales y eventos.</td>
            <td align="justify">Posible disminución de la demanda de viajes debido a crisis económicas o sanitarias.</td>
            <td align="justify">Innovaciones tecnológicas que podrían ser adoptadas por competidores.</td>
            <td align="justify">Posible pérdida de confianza del usuario debido a problemas de seguridad o calidad del servicio.</td>
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

**Segmento 1:**

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
    <td><div align="center"><img src=""></div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td><p><a target="_blank"  href="" title="Title">Microsoft Stream</a></p></td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>: min - : min </td>
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
    <td><div align="center"><img src="" alt=""></div></td>
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
    <td style="text-align: justify;"></td>
  </tr>
</tbody>
</table>


**Segmento 2:**

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

User Persona 1 - Segmento de : 

</div>

![Artefacto creado en UXPressia](Resources/cap2/.png)

<div style="page-break-after: always;"></div>

Gráfico sobre la sistema operativo mas usado:
![Creado en Excel](Resources/cap2/.png)

Gráfico sobre dispositivo móvil mas usado:
![Creado en Excel](Resources/cap2/.png)

Gráfico sobre browser mas usado:
![Creado en Excel](Resources/cap2/.png)

<div style="page-break-after: always;"></div>

User Persona 2 - Segmento de : 

![Artefacto creado en UXPressia](Resources/cap2/.png)

<div style="page-break-after: always;"></div>

Gráfico sobre la sistema operativo mas usado:
![Creado en Excel](Resources/cap2/.png)

Gráfico sobre dispositivo móvil mas usado:
![Creado en Excel](Resources/cap2/.png)

Gráfico sobre browser mas usado:
![Creado en Excel](Resources/cap2/.png)

### 2.3.2. *User Task Matrix*

User Task Matrix: 

Con el fin de elaborar un Task Matrix adecuado para el proyecto, se han considerado los dos segmentos objetivo, producto del análisis de entrevistas, es decir,  y .



<b>Usuario </b><br>

<div align="center">

| **USER TASK**                               | **Frecuencia** | **Importancia** |
|---------------------------------------------|----------------|-----------------|
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |
|  |           |            |

</div><br><br>

<b>Usuario </b><br>

<div align="center">



</div>


### 2.3.3. *User Journey Mapping*

User Journey Mapping: 

![Artefacto creado en UXPressia](Resources/cap2/.png)

User Journey Mapping: 

![Artefacto creado en UXPressia](Resources/cap2/.png)

<div style="page-break-after: always;"></div>

### 2.3.4. *Empathy Mapping*

Empathy Mapping: 

![Artefacto creado en UXPressia](Resources/cap2/.png)

<div style="page-break-after: always;"></div>

Empathy Mapping: 

![Artefacto creado en UXPressia](Resources/cap2/.png)

### 2.3.5. *As-is Scenario Mapping*

<div align="justify">

El As-Is Scenario Mapping es una herramienta para identificar los pensamientos que tienen los usuarios sin la aplicación.

</div>

***As-Is Scenario Map:*** **-**

![Recurso creado en Miro](Resources/cap2/.png)

***As-Is Scenario Map:*** **-**

![Recurso creado en Miro](Resources/cap2/.png)

<div style="page-break-after: always;"></div>

## 2.4. *Ubiquitous Language*



![Ubiquitous Language](Resources/cap2/ubiquitous-language.png)


<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

### 3.1. *To-Be Scenario Mapping*

El *To-Be Scenario Mapping* es una herramienta para identificar cómo se sentirán los usuarios con los nuevos cambios que deberían haber solucionado los problemas planteados en los *As-Is scenario maps.*

![Recurso creado en Miro](Resources/cap2/ToBeSM.png)

### 3.2. *User Stories:*

***Epics***




**User Stories**

<div align="justify">



**Technical User Stories**



</div>

### 3.3. *Impact Mapping*

El impact map es una herramienta estratégica que permite identificar de manera precisa las características de una aplicación que pueden ser utilizadas o mejoradas para cumplir con un objetivo empresarial específico. Al partir del objetivo clave, se desglosan los comportamientos necesarios de los usuarios, se definen las acciones que deben realizar en la aplicación, se identifican las características necesarias para habilitar esas acciones, se evalúa el impacto potencial de cada característica en el logro del objetivo, y finalmente se crea un plan de acción detallado que guía el desarrollo y mejora continua de la aplicación, alineando así las acciones de los usuarios con los objetivos estratégicos de la empresa.

![Artefacto creado en UXPressia](Resources/cap2/impact-map.png)

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



#### 4.1.1.1. *Candidate Context Discovery*



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
