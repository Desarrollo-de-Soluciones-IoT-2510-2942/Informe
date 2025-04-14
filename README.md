<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br><img src="https://www.upc.edu.pe/static/img/logo_upc_red.png"></img><br>
    <br>
    <strong>Ingeniería de Software - 2025-10</strong><br>
    <br>
    <strong>1ASI0572 - Desarrollo de Soluciones IoT - 2942</strong><br>  
    <br>
    <strong>Profesor: Marco Antonio León Baca</strong><br>
    <br> <strong>INFORME DE TB1</strong> 
</p>
<p align="center">
    <strong>Startup: </strong><br>
    <strong>Producto:  </strong>
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
| Morales Calderón, Hernan Emilio (U202216263) | Soy Hernan Morales, tengo 19 años y actualmente estoy cursando el 7mo ciclo de Ingeniería de Software. Me considero una persona sumamente responsable y organizada, especialmente en trabajos universitarios. Mi objetivo es culminar exitosamente el curso y nuestro proyecto junto a mi equipo, asegurando que cada detalle se ejecute con precisión. Tengo conocimientos sólidos en lenguajes como C++, C#, y JavaScript, así como en frameworks como Angular y Vue, lo que me permite desarrollar interfaces dinámicas y adaptarme rápidamente a diferentes entornos de desarrollo. Además, manejo SQL para la gestión y optimización de bases de datos. Estoy convencido de que, con buena planificación y comunicación, entregaremos un proyecto de alta calidad que supere las expectativas. | ![Hernan Morales](Resources/Chapter%2001/Team%20Members/Morales-Hernan.png)             |
| Valle Zuta, Abel Andrés (U202210297) | Soy Abel Andrés Valle Zuta, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), tengo 20 años y actualmente estoy cursando el 7mo ciclo en la sede de Monterrico. Sé programar y editar videos. Además, sé resolver problemas, trabajar en equipo y lograr unir más al grupo. Mis hobbies son jugar básquet, fútbol, tenis, videojuegos, escuchar música, salir a pasear con mis amigos, ver películas, nadar, hacer ejercicio, pasear a mis mascotas y pasar tiempo con mi familia. Finalmente, siempre estoy dispuesto a trabajar y terminar a tiempo los deberes, esforzándome para aprender y comprender lo máximo posible y finalizar con éxito todos mis objetivos.                                                                     | ![Abel Valle](Resources/Chapter%2001/Team%20Members/Valle-Abel.jpg)               |

</div>

<div style="page-break-after: always;"></div>

## 1.2. Solution Profile

<div align="justify">
En el contexto agrícola de Sudamérica, y particularmente en Perú, los productores enfrentan una combinación de desafíos estructurales y emergentes que afectan profundamente la eficiencia y sostenibilidad del sector. Uno de los problemas más urgentes es la escasez de agua: según el Centro Nacional de Planeamiento Estratégico (Ceplan), se estima que para el año 2030 más del 58% de la población peruana vivirá en zonas con estrés hídrico, mientras regiones como Piura ya se encuentran en estado de emergencia por déficit hídrico. Esta crisis compromete gravemente la capacidad de riego de los cultivos y exige una gestión más eficiente del agua. A ello se suma el incremento sostenido en los precios de los fertilizantes, cuya importación anual en Perú supera el millón de toneladas y ha alcanzado un valor de más de 800 millones de dólares, impulsado por factores como la pandemia, los conflictos geopolíticos y las limitaciones en la cadena de suministro global. Este aumento ha afectado especialmente a pequeños y medianos productores, reduciendo sus márgenes de ganancia y dificultando el acceso a insumos esenciales. Por otro lado, la agricultura peruana aún presenta una marcada brecha tecnológica: mientras los grandes productores comienzan a incorporar tecnologías de precisión, la mayoría de agricultores no cuenta con herramientas que les permitan monitorear en tiempo real variables clave como la humedad, el pH del suelo o la disponibilidad de nutrientes, lo que limita su capacidad para tomar decisiones informadas frente a condiciones climáticas cada vez más impredecibles.
<br><br>
En respuesta a estos desafíos, AgroSense presenta NutriControl, una solución tecnológica integral que automatiza el proceso de fertilización mediante sensores inteligentes capaces de medir en tiempo real variables críticas del suelo como el pH, la humedad y los niveles de nutrientes. A partir de estos datos, el sistema activa de forma autónoma el riego por goteo solo cuando el cultivo lo necesita, garantizando una aplicación precisa y oportuna de agua y fertilizantes. Esta tecnología no solo reduce el uso innecesario de insumos y agua, sino que también mejora significativamente el rendimiento de los cultivos. Con NutriControl, buscamos contribuir y ayudar a los agricultores peruanos y sudamericanos con herramientas accesibles e inteligentes que los ayuden a producir más con menos, adaptándose a las condiciones específicas de cada terreno y enfrentando con resiliencia los desafíos del cambio climático, la escasez hídrica y los altos costos productivos.
<br><br>
</div>

![Solution Profile](Resources/Chapter%2001/Solution%20Profile/Reference.jpg)

### 1.2.1. Antecedentes y problemática

<div align="justify">

***What***

* Los agricultores gestionan el riego y fertilización de forma empírica o mediante calendarios fijos.
* Esto genera uso excesivo de agua y fertilizantes, aumentando costos y reduciendo eficiencia.
* La falta de monitoreo en tiempo real impide decisiones oportunas y precisas sobre el manejo del cultivo.



***Who***

* A pequeños y medianos agricultores, quienes tienen menor acceso a tecnología.
* A cooperativas y asociaciones agrícolas, que buscan eficiencia pero no cuentan con datos.


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


2. Customer Segments:

3. Pain Points:
   
4. Gap:
   
5. Vision / Strategy:

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

* **Creemos que** . **Sabremos que**  **cuando** .

* **Creemos que** . **Sabremos que**  **cuando** .

* **Creemos que** . **Sabremos que**  **cuando** .

* **Creemos que** . **Sabremos que**  **cuando** .

* **Creemos que** . **Sabremos que**  **cuando** .

* **Creemos que** . **Sabremos que**  **cuando** .

</div>

#### 1.2.2.4. *Lean UX Canvas*

![Artefacto creado en Figma ([URL](https))]()

## 1.3. Segmentos objetivo

![Tabla del segmento 1](Resources/cap1/segmento-1.png)

![Tabla del segmento 2](Resources/cap1/segmento-2.png)

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

![](Resources/cap2/competidores-baner.png)

<div align="justify">



</div>

**Competidores:**

<div align="justify">

* ***:***
  

</div>

  ![Imagen extraída de ([URL]())](Resources/cap2/)

<div align="justify">

* ***:***
  

</div>

  ![Imagen extraída de ([URL]())](Resources/cap2/)

<div align="justify">

* ***:***
  

</div>

  ![Imagen extraída de ([URL]())](Resources/cap2/)

### 2.1.1. Análisis competitivo



### 2.1.2. Estrategias y tácticas frente a competidores

<div align="justify">



**Estrategias Competitivas para** ***:***

1. **Liderazgo en Costos:**

**Estrategia:** .

**Tácticas:**
* .
* .
* .

2. **Diferenciación a través de la Innovación:**

**Estrategia:** .

**Tácticas:**
* .
* .
* .


3. **Enfoque en segmentos específicos del mercado:**

**Estrategia:** .

**Tácticas:**
* .
* .
* .

**Tácticas Específicas para** ***:***

1. **Monitoreo Competitivo Continuo:**

**Táctica:** .

**Acciones:**
* .
* .

2. **Estrategias de Precios y Paquetes Competitivos:**

**Táctica:** .

**Acciones:**
* .
* .

3. **Inversión en Marketing Diferenciado:**

**Táctica:** .

**Acciones:**
* .
* .

4. **Alianzas Estratégicas y Colaboraciones:**

**Táctica:** .

**Acciones:**
* .
* .

</div>

## 2.2. Entrevistas

<div align="justify">

Para acceder al video de las entrevistas, haga click en la ([URL]())

### 2.2.1. Diseño de entrevistas

Entrevista a personas referentes a nuestro segmentos objetivo, las preguntas varían dependiendo del segmento debido a las diferentes situaciones:

**Segmento 1:** 

**Preguntas de introducción:**

1. ¿Cuántos años tiene?
2. ¿En qué ciudad del Perú reside?
3. ¿Cuál considera que es su estatus social limitando la descripción a Clase Baja, Clase Media, Clase Media-Alta y Clase Alta?
4. ¿?
5. ¿?
6. ¿?

**Preguntas principales:**

1. 
2. 
3. 
4. 
5. 
6. 
7. 
8. 
9. 
10. 
11. 
12. 
13. 
14. 
15. 
16. 
17. 
18. 
19. 
20. 
21. 
22. 

**Segmento 2:** 

**Preguntas de introducción:**

1. ¿Cuántos años tiene?
2. ¿En qué ciudad del Perú reside?
3. ¿Cuál es su ocupación principal?
4. ¿?
5. ¿?
6. ¿?
7. ¿?
8. ¿?
9. ¿?
10. ¿?

**Preguntas principales:**

1. ¿?
2. ¿?
3. ¿?
4. ¿?
5. ¿?
6. ¿?
7. ¿?
8. ¿?
9. ¿?
10. ¿?
11. ¿?


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



</div>

![Imagen extraída de Canva](Resources/cap2/needfind-baner.png)

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
