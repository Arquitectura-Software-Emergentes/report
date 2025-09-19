<div align="center">
    <h3>Universidad Peruana de Ciencias Aplicadas</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 8vo Ciclo</strong><br>
    <strong>Arquitecturas De Software Emergentes</strong><br>
    <strong>1ASI0572</strong><br>
    <strong>Profesor: Royer Edelwer Rojas Malasquez</strong><br>
    <br><strong>Report</strong><br>
    <!--<strong>name solution</strong>-->
    <!--<strong>name startup</strong>-->
</div>

<h3> Team Members: </h3>

<div align="center">

| Member                              |    Code    |
| :---------------------------------- | :--------: |
| Baldeon Fabian, Aldo Alberto        | u202122633 |
| Cama Salvatierra, Jimena Tamara     | u202210778 |
| Castillo Robles, Steve Roger        | u202121679 |
| Castillo Castillo, Jair Alexander   | u202211390 |
| Quezada Portalatino, Barbara Susana | u202211800 |

</div>

<h3 align="center">Septiembre, 2025</h3>

<br><br>

<div align="justify">

## Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva e incluye un cuadro con la siguiente estructura:

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0.1</td>
      <td>07/09/2025</td>
      <td>Equipo completo</td>
      <td>Creación inicial del informe con la estructura base y distribución de responsabilidades</td>
    </tr>
  </tbody>
</table>
<br>

# Project Report Collaboration Insights

<br>Para desarrollar el proyecto, se empleó GitHub como herramienta para gestionar versiones y facilitar la colaboración en tiempo real. A continuación, se proporciona el enlace al repositorio del proyecto:

|     **Descripción**      |                              **Enlace**                               |
| :----------------------: | :-------------------------------------------------------------------: |
| Repositorio del Proyecto | https://github.com/orgs/Arquitectura-Software-Emergentes/repositories |
| Link de la Organización  |       https://github.com/orgs/Arquitectura-Software-Emergentes        |

**TB1:**

Para el TB1, se asignaron responsabilidades específicas a cada integrante, las cuales se detallan a continuación:

| Miembro del Equipo | Tarea Asignada |
| :----------------: | :------------: |
|    Aldo Baldeon    |                |
|  Barbara Quezada   |                |
|   Steve Castillo   |                |
|    Jimena Cama     |                |
|   Jair Castillo    |                |

Cabe destacar que, durante la creación del informe, se realizaron commits específicos para cada tarea asignada, lo que permitió garantizar un control de versiones y una colaboración efectiva en tiempo real. El equipo mantuvo reuniones semanales de sincronización para asegurar la coherencia entre los diferentes capítulos y compartir avances.

Miembros

- Aldo Baldeon (CodAress)
- Barbara Quezada (BarbaraQP15)
- Steve Castillo (Salchichon057)
- Jimena Cama (aksonie)
- Jair Castillo (U202211390)

El uso de GitHub ha permitido gestionar versiones y fomentar la colaboración en tiempo real, facilitando que los integrantes del equipo trabajen tanto de forma asincrónica como sincrónica en el proyecto. Asimismo, la metodología Gitflow ha posibilitado la creación de diversas ramas para el desarrollo de las tareas asignadas, promoviendo un trabajo autónomo y colaborativo entre los miembros.

La rama "develop" se utilizó como un entorno para integrar las tareas de cada miembro de manera estructurada y organizada, mientras que la rama "main" se destinó a la entrega de la versión final del proyecto. Esta estrategia permitió una revisión conjunta del contenido antes de su integración final, reduciendo errores y asegurando la calidad del informe presentado.

# Contenido

## Tabla de Contenidos

## Capítulo I: Introducción

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

## Capítulo II: Requirements Elicitation & Analysis

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
  - [2.3.3. Empathy Mapping](#233-empathy-mapping)
  - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

## Capítulo III: Requirements Specification

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## Capítulo IV: Strategic-Level Software Design

- [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
  - [4.1.1. Design Purpose](#411-design-purpose)
  - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
    - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
    - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
    - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.2.4. Architectural Drivers Backlog](#4124-architectural-drivers-backlog)
  - [4.1.3. Architectural Design Decisions](#413-architectural-design-decisions)
  - [4.1.4. Quality Attribute Scenario Refinements](#414-quality-attribute-scenario-refinements)
- [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
  - [4.2.1. EventStorming](#421-eventstorming)
  - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
  - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
  - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
  - [4.2.5. Context Mapping](#425-context-mapping)
- [4.3. Software Architecture](#43-software-architecture)
  - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
  - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
  - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
  - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)

### [Conclusiones](#conclusiones)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET – EAC - Student Outcome 5**
**Criterio:** La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

<table>
    <tr>
        <th><b>Criterio específico</b></th>
        <th><b>Acciones realizadas</b></th>
        <th><b>Conclusiones</b></th>
    </tr>
    <tr>
        <td rowspan="1"><b>Trabaja en equipo para proporcionar liderazgo en forma conjunta</b></td>
        <td>
            <b>TB1:</b><br>
            <b>Baldeon Fabian, Aldo Alberto</b><br>
            - 
            <br><br> 
            <b>Cama Salvatierra, Jimena Tamara</b><br>
            - 
            <br><br>
            <b>Castillo Castillo, Jair Alexander</b><br>
            - 
            <br><br>
            <b>Castillo Robles, Steve Roger</b><br>
            - 
            <br><br>
            <b>Quezada Portalatino, Barbara Susana</b><br>
            - 
            <br><br>
            <b>TP1:</b><br>
            <b>Baldeon Fabian, Aldo Alberto</b><br>
            - 
            <br><br>
            <b>Cama Salvatierra, Jimena Tamara</b><br>
            - 
            <br><br>
            <b>Castillo Castillo, Jair Alexander</b><br>
            - 
            <br><br>
            <b>Castillo Robles, Steve Roger</b><br>
            - 
            <br><br>
            <b>Quezada Portalatino, Barbara Susana</b><br>
            - 
            <br><br>
        </td>
        <td>
            <b>TB1:</b><br>
            Hemos demostrado un liderazgo compartido al asumir responsabilidades clave en cada capítulo del proyecto, asegurando que cada integrante tome la iniciativa en distintas áreas. La colaboración entre Aldo y Jair en la introducción y conceptualización del problema, el liderazgo de Franz en la investigación de requerimientos, y la toma de decisiones técnicas y estratégicas por parte de Jimena y Bárbara reflejan un liderazgo distribuido y coherente. Esto ha permitido que el equipo avance con una visión unificada del proyecto y tome decisiones informadas en conjunto.
            <br><br>
            <b>TP1:</b><br>
            Como equipo, ejercimos un liderazgo conjunto al asumir responsabilidades según nuestras fortalezas individuales, distribuyendo tareas de forma equitativa y coordinada. A lo largo del proyecto, tomamos decisiones colaborativas que permitieron mantener una visión unificada del sistema, y nos apoyamos mutuamente para superar obstáculos técnicos y organizativos. Esta dinámica nos permitió liderar desde distintos frentes del desarrollo —diseño, backend, frontend y gestión—, asegurando que todos los módulos avanzaran de forma integrada y con sentido de propósito común.
        </td>
    </tr>
    <tr>
        <td rowspan="1"><b>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</b></td>
        <td>
            <b>TB1:</b><br>
            <b>Baldeon Fabian, Aldo Alberto</b><br>
            - 
            <br><br> 
            <b>Cama Salvatierra, Jimena Tamara</b><br>
            - 
            <br><br>
            <b>Castillo Castillo, Jair Alexander</b><br>
            - 
            <br><br>
            <b>Castillo Robles, Steve Roger</b><br>
            - 
            <br><br>
            <b>Quezada Portalatino, Barbara Susana</b><br>
            - 
            <br><br>
            <b>TP1:</b>
            <b>Baldeon Fabian, Aldo Alberto</b><br>
            - 
            <br><br>
            <b>Cama Salvatierra, Jimena Tamara</b><br>
            - 
            <br><br>
            <b>Castillo Castillo, Jair Alexander</b><br>
            - 
            <br><br>
            <b>Castillo Robles, Steve Roger</b><br>
            - 
            <br><br>
            <b>Quezada Portalatino, Barbara Susana</b><br>
            - 
            <br><br>
        </td>
        <td>
            <b>TB1:</b><br>
            A lo largo del desarrollo del proyecto, hemos construido un entorno de trabajo colaborativo y respetuoso, donde cada voz ha sido escuchada y valorada. La planificación de tareas se realizó en base a las fortalezas individuales, estableciendo metas claras para cada entrega. La comunicación constante entre los miembros del grupo permitió resolver dudas, alinear criterios y asegurar el cumplimiento de los objetivos establecidos. Esta dinámica no solo optimizó la ejecución del proyecto, sino que fortaleció la cohesión del equipo.
            <br><br>
        </td>
    </tr>
</table>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

[actualizar]

### 1.1.2. Perfiles de integrantes del equipo

## 1.1.2. Perfiles de integrantes del equipo

| Foto                                                        | Información                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Perfil de Aldo](./images/profiles/aldo_profile.jpg)       | **Nombre y Apellido:** Aldo Alberto Baldeon Fabian<br>**Código:** U202122633<br>**Carrera:** Ingeniería de Software<br>**Acerca de:** Soy Aldo Alberto Baldeon Fabian, estudio la carrera de Ingeniería de Software en la UPC. Escogí esta carrera porque me interesó el desarrollo de aplicaciones. Soy responsable y me gusta trabajar en equipo. Poseo conocimientos básicos en C#, java, JavaScript, HTML y CSS. También, poseo conocimientos intermedios en C + +, SQL y MongoDB, además de contar con experiencia en Git y GitHub.                                                                                                                                                                                                                                              |
| ![Perfil de Barbara](./images/profiles/barbara_profile.jpg) | **Nombre y Apellido:** Barbara Susana Quezada Portalatino<br>**Código:** U202211800<br>**Carrera:** Ingeniería de Software<br>**Acerca de:** Barbara Susana Quezada Portalatino, cursando el séptimo ciclo de la carrera de software, trabajo mayormente bajo un rol de líder que me ayuda a poder organizar no solo la ideas de mi grupo sino que las ideas aterricen en la ejecución. Soy una persona muy disciplinada y detallista.                                                                                                                                                                                                                                                                                                                                                |
| ![Perfil de Jimena](./images/profiles/jimena_profile.jpg)   | **Nombre y Apellido:** Jimena Tamara Cama Salvatierra<br>**Código:** U2022210778<br>**Carrera:** Ingeniería de Software<br>**Acerca de:** Soy estudiante de la carrera de Ingeniería de Software en la UPC y actualmente estoy cursando el 8vo ciclo. Me considero una persona curiosa, determinada y organizada. Con la experiencia en proyectos de startup y trabajos en equipo, trabajaré junto a mis compañeros para lograr un óptimo resultado del proyecto.                                                                                                                                                                                                                                                                                                                     |
| ![Perfil de Jair](./images/profiles/jair_profile.jpg)       | **Nombre y Apellido:** Jair Alexander Castillo Castillo<br>**Código:** U202211390<br>**Carrera:** Ingeniería de Software<br>**Acerca de:** Soy estudiante de la carrera de Ingeniería de Software en la UPC y me encuentro en el 7to ciclo. Me considero una persona dedicada, comprensiva y metódica. Con mis habilidades de liderazgo y mi capacidad para trabajar en equipo en un ambiente de respeto, estoy segura de que podré dirigir la implementación de la startup de nuestro proyecto de manera exitosa.                                                                                                                                                                                                                                                                    |
| ![Perfil de Franz](./images/profiles/steve_profile.jpg)     | **Nombre y Apellido:** Steve Roger Castillo Robles<br>**Código:** U202012378<br>**Carrera:** Ingeniería de Software<br>**Acerca de:** Soy Steve, estudiante del 9no ciclo de Ingeniería de Software y desarrollador Full-Stack, con experiencia en tecnologías como Angular, React.js, Next.js, Spring Boot, Flutter, PostgreSQL y servicios cloud como Azure, Firebase y Supabase. Mi experiencia abarca desde el desarrollo y migración de aplicaciones hasta el diseño y optimización de bases de datos, aplicando principios de arquitectura limpia, DDD y metodologías ágiles como Scrum. Me destaco por mi capacidad para trabajar en equipo, mi enfoque metódico y mi constante pasión por aprender y aplicar nuevas tecnologías para llevar los proyectos al siguiente nivel. |

## 1.2. Solution Profile

**[Nombre del proyecto]**

Nuestra propuesta es crear una plataforma urbana inteligente centrada en Lima, que aprovecha tecnologías de visión por computadora y análisis geoespacial para transformar la gestión de incidencias urbanas. A través de una aplicación móvil, los limeños podrán reportar problemas específicos como baches y acumulación de basura, adjuntando fotografías y ubicación automática. Estas imágenes serán procesadas por un backend con inteligencia artificial, donde un sistema de visión por computadora YOLO entrenado con un dataset local mínimo de 2,000 imágenes identificará y clasificará automáticamente cada incidencia en estas dos categorías prioritarias.

Simultáneamente, la plataforma generará mapas de calor georreferenciados utilizando herramientas de análisis geoespacial, mostrando en tiempo real las zonas con mayor concentración de reportes. Estas herramientas permitirán a las autoridades visualizar la distribución de incidencias por distrito y planificar intervenciones de forma estratégica.

### 1.2.1. Antecedentes y problemática

Lima Metropolitana, capital de Perú, alberga cerca de 10.29 millones de habitantes (30,2 % de la población nacional) y es una de las ciudades más densamente pobladas de América Latina, con distritos que superan los 30,000 habitantes por km². Esta alta densidad genera desafíos significativos en infraestructura y movilidad: según reportes oficiales, los limeños pierden en promedio 155 horas al año en el tráfico. Sin embargo, la conectividad digital es elevada: el 85.3 % de los residentes utiliza Internet, lo que abre oportunidades para soluciones tecnológicas de reporte ciudadano.

A pesar de este potencial, la gestión de incidencias urbanas en Lima sigue siendo mayoritariamente reactiva y fragmentada. La mayoría de municipios atiende reportes aislados por teléfono o presencialmente, sin un sistema digital unificado. La información sobre baches y otros problemas se dispersa entre diferentes plataformas y registros físicos, dificultando la identificación de patrones y la toma de decisiones preventivas. Como consecuencia, muchas incidencias permanecen sin resolver y los ciudadanos perciben que sus reclamos no son atendidos oportunamente.

**¿Qué problema resuelve la plataforma?**

El principal reto es la gestión reactiva de incidencias urbanas. Lima carece de una plataforma única que detecte y procese tempranamente los problemas en calles y espacios públicos. Sin integración tecnológica, las autoridades dependen de reportes aislados y no pueden visualizar fácilmente los focos recurrentes de deterioro, lo que deriva en intervenciones tardías y frecuentes quejas ciudadanas.

**¿Cuándo ocurre la problemática?**

La situación es constante, pero se agrava en momentos críticos como temporadas de lluvias, picos de actividad urbana (festividades, marchas) y emergencias ambientales (inundaciones, deslizamientos), donde la falta de información en tiempo real retrasa la respuesta municipal y aumenta los daños.

**¿Dónde impacta?**

El impacto se concentra en Lima Metropolitana, especialmente en distritos céntricos y de alta densidad como San Juan de Lurigancho, Ate y Surquillo, donde el deterioro vial y la acumulación de basura son más frecuentes. También afecta barrios periféricos con menor inversión en infraestructura y canales informales de reporte. La plataforma cubrirá toda la ciudad, permitiendo mapear incidencias en los 43 distritos limeños.

**¿Quiénes son los beneficiarios?**

- **Ciudadanos limeños:** Vecinos que reportan problemas y pueden dar seguimiento a sus solicitudes, obteniendo transparencia en el proceso de resolución.
- **Autoridades municipales:** Personal técnico y de gestión (gerencias de obras, mantenimiento, servicios públicos) que requieren herramientas para supervisar infraestructuras, priorizar recursos y asignar cuadrillas de manera eficiente.

**¿Por qué persiste el problema?**

La gestión reactiva se mantiene por baja adopción tecnológica, información fragmentada, recursos limitados y una brecha digital operativa. Aunque la mayoría de limeños está conectada, las plataformas gubernamentales no aprovechan esa conectividad, generando desconfianza y falta de respuesta eficiente.

**Detalle de la Solución**

La plataforma se compone de tres módulos principales:

- **Aplicación Móvil Ciudadana:** Interfaz intuitiva para reportar incidencias con foto y geolocalización automática. Un sistema de visión por computadora integrado valida que la imagen corresponde a un problema urbano, evitando reportes falsos. La app funciona offline y envía los datos cuando se recupera la conexión.
- **Backend Inteligente y Base de Datos:** Motor central en la nube que procesa y almacena los reportes. Un sistema de visión por computadora entrenado con datos locales identifica el tipo de incidencia. Los reportes se almacenan en una base de datos espacial, permitiendo consultas georreferenciadas y análisis predictivo. El backend ofrece APIs seguras para integración con sistemas municipales y protocolos de privacidad.
- **Visualización Geoespacial y Dashboard Analítico:** Herramientas para interpretar los datos y apoyar la toma de decisiones. Se generan mapas de calor urbanos y dashboards con gráficos de tendencias y KPIs relevantes, facilitando la gestión basada en datos.

**¿Cuánto afecta?**

Las consecuencias son notables: la congestión vehicular y el deterioro vial obligan a los limeños a perder tiempo y calidad de vida. Atender problemas de forma reactiva puede incrementar hasta un 40 % el costo de mantenimiento vial frente a una gestión preventiva. La solución requiere una inversión moderada en desarrollo de software, servidores, almacenamiento y capacitación, pero estos gastos se justifican por los ahorros en tiempo y recursos.

**Beneficiarios directos e impacto adicional**

La plataforma impacta a casi toda la población de Lima (~10.29 millones), permitiendo a las autoridades municipales detectar incidencias temprano, asignar recursos óptimamente y tomar decisiones informadas. El personal municipal visualiza puntos críticos mediante mapas de calor y dashboards analíticos, facilitando la priorización y asignación eficiente de recursos. Los ciudadanos cuentan con un canal claro para reportar problemas y recibir transparencia en el seguimiento. Además, Lima avanzaría hacia una ciudad más inteligente y resiliente, optimizando inversiones y mejorando la preparación ante emergencias.

**Innovación tecnológica y valor diferencial**

El proyecto integra tecnologías emergentes adaptadas al contexto limeño:

- Visión por computadora avanzada: Sistemas entrenados con imágenes locales para detección en tiempo real, compatibles con dispositivos móviles.
- Herramientas de análisis geoespacial interactivas: Soluciones para mapas dinámicos y exploración visual.
- Inteligencia artificial predictiva y optimización: Algoritmos para anticipar problemas y optimizar rutas de mantenimiento.

**Valor diferencial:**

- Para autoridades: Detección automatizada, mapas de calor y KPIs en tiempo real.
- Para ciudadanos: Canal directo y transparente para reportar problemas y seguimiento.
- Para Lima: Transformación hacia una smart city, reducción de costos operativos y cierre de la brecha digital.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statement

**Problem Statement:**

La gestión de incidencias urbanas en Lima Metropolitana es actualmente reactiva, fragmentada y opaca para el ciudadano. Los canales existentes (teléfono, formularios municipales aislados o visitas presenciales) no ofrecen confirmación estructurada, trazabilidad del estado ni consolidación de datos para análisis transversal.

**Problema:**

Ciudadanos conectados digitalmente (18–45 y segmentos activos de reporte cívico) experimentan frustración y desconfianza al no poder visualizar el progreso de sus reportes de baches y acumulación de basura, dos de las incidencias urbanas más frecuentes del espacio público. Paralelamente, las gerencias municipales carecen de un repositorio unificado y de analítica geoespacial que permita detectar patrones (hotspots) y priorizar intervenciones preventivas. Esto ocasiona: duplicidad de reclamos, tiempos prolongados a primera acción, uso ineficiente de cuadrillas y percepción negativa de respuesta institucional.

**Impacto:**

La ausencia de un circuito transparente y analítico retrasa intervenciones, incrementa costos correctivos frente a mantenimiento preventivo y deteriora la participación cívica sostenida. Un sistema integrado con reporte estructurado, validación automática de imágenes, clasificación asistida por IA y dashboards geoespaciales habilita: reducción de tiempos de priorización, asignación más eficiente de recursos, incremento de confianza ciudadana y generación de datos abiertos para innovación externa. El éxito temprano se medirá a través de adopción inicial (reportes válidos únicos), precisión de clasificación, disminución de reportes inválidos/duplicados, tiempo a primera acción y retención (usuarios que reportan nuevamente en ventana piloto).

#### 1.2.2.2. Lean UX Assumptions

**Business Outcomes:**

- ≥70% de reportes creados en el piloto con todos los campos completos (foto válida, ubicación, categoría confirmada).
- ≥80% de precisión promedio del modelo de clasificación de incidencias en dataset de validación local.
- <15% de reportes inválidos o duplicados tras filtrado automático + revisión mínima.
- ≥30% de usuarios recurrentes (segundo reporte dentro de 45 días).
- ≥25% de reducción del tiempo promedio a primera acción municipal registrada (baseline vs. piloto).
- ≥1 gerencia municipal (distrito piloto) usando el dashboard semanalmente (≥4 sesiones mensuales) durante piloto.
- ≥40% de reducción del tiempo de priorización manual al disponer de mapas de calor y ranking automatizado.

**Users (Segmentos Objetivo Simplificados):**

- Ciudadano Reportante: residente urbano con smartphone que observa incidencias y registra evidencia (foto + ubicación) mediante la aplicación móvil.
- Municipalidad (Gerencia / Unidad Responsable): personal técnico y de gestión que consume analítica (mapas de calor, KPIs) para priorizar y dar seguimiento a intervenciones.

**User Outcomes & Benefits:**

Ciudadano Reportante:

- Registro rápido (≤3 pantallas) y confirmación inmediata de recepción.
- Visibilidad del estado de su incidencia que reduce incertidumbre y motiva reuso.
- Retroalimentación de cierre que incrementa percepción de efectividad institucional.

Municipalidad:

- Consolidación automática y visual (mapas de calor, filtros temporales) para priorizar.
- Reducción de ruido (reportes inválidos/duplicados) que optimiza revisión.
- Métricas operativas (tiempo a primera acción, distribución por tipo, severidad) para gestión y rendición de cuentas.

**Feature Assumptions:**

- Captura guiada (foto + geolocalización automática + sugerencia de categoría por IA).
- Clasificación automática y validación básica de calidad de imagen.
- Estado visible del ciclo de vida (recibido, en verificación, programado, en proceso, cerrado).
- Dashboard geoespacial con mapas de calor, filtros por tipo, tiempo y severidad.
- Modo offline con sincronización diferida.
- Notificaciones (push / correo) en hitos clave.

**Business Assumptions:**

- Creemos que el ciudadano reportará nuevamente si percibe confirmación y avance dentro de un plazo razonable.
- Creemos que la gerencia municipal adoptará el dashboard si reduce tiempo de priorización y consolida evidencias georreferenciadas.
- Creemos que la diferenciación radica en la unión de captura estructurada + clasificación automática + visualización geoespacial continua.
- Creemos que financiamiento inicial puede surgir de presupuesto de modernización o cooperación interinstitucional.
- Riesgo principal: baja precisión temprana del modelo o falta de acción visible en reportes, afectando retención.
- Mitigación: ajuste iterativo del modelo con dataset local y acuerdos de SLA mínimos para primera acción.

**User Assumptions:**

- ¿Quién es el usuario?

  Dos segmentos núcleo:

  - Ciudadano Reportante
  - Municipalidad (gerencia responsable)

¿Qué problema resuelve nuestro producto?

- Para el ciudadano: falta de canal único y trazable para reportar incidencias. Para la municipalidad: ausencia de consolidación y priorización geoespacial rápida.

¿Qué características son importantes?

- Ciudadano: flujo corto, confirmación inmediata, estado visible. Municipalidad: analítica visual, filtrado, métricas operativas.

¿Dónde encaja en su rutina?

- Ciudadano: durante desplazamientos cuando detecta una incidencia. Municipalidad: sesiones de revisión y planificación diaria/semanal.

¿Cuándo y cómo se usa?

- App móvil (ciudadano) en el momento del hallazgo; dashboard web (municipalidad) para priorizar y monitorear indicadores.

¿Cómo debe verse y comportarse?

- App: simple, rápida, ≤3 pasos, validación inmediata. Dashboard: panel claro con mapas responsivos y filtros eficientes.

#### 1.2.2.3. Lean UX Hypothesis Statements

A continuación, se presentan las hipótesis clave relacionadas con las funcionalidades y comportamientos esperados. Cada hipótesis es específica y medible.

- Hypothesis Statement 1:
  Creemos que un flujo de reporte simplificado (foto + geolocalización + sugerencia de categoría) reducirá la fricción inicial y aumentará la completitud de datos.
  Sabremos que hemos tenido éxito cuando ≥70% de los reportes del primer mes incluyan foto válida, coordenadas y categoría confirmada sin edición manual.

- Hypothesis Statement 2:
  Creemos que la clasificación automática mediante un modelo entrenado localmente disminuirá la proporción de reportes inválidos o irrelevantes.
  Sabremos que hemos tenido éxito cuando la tasa de reportes descartados manualmente sea <15% y la precisión validada sea ≥80%.

- Hypothesis Statement 3:
  Creemos que mostrar estados visibles del ciclo de vida incrementará la retención y el re-reporte responsable.
  Sabremos que hemos tenido éxito cuando ≥30% de los usuarios con un primer reporte registren un segundo dentro de 45 días.

- Hypothesis Statement 4:
  Creemos que un dashboard geoespacial con mapas de calor temporales permitirá priorizar intervenciones preventivas de forma más eficiente.
  Sabremos que hemos tenido éxito cuando al menos 1 gerencia lo use semanalmente y reporte una reducción ≥20% en tiempo de priorización comparado con la línea base.

- Hypothesis Statement 5:
  Creemos que notificaciones de avance y cierre aumentarán la percepción de transparencia y satisfacción.
  Sabremos que hemos tenido éxito cuando >60% de encuestados indiquen satisfacción con la visibilidad del proceso y el NPS del seguimiento sea ≥30.

- Hypothesis Statement 6:
  Creemos que el modo offline incrementará la cobertura en zonas de conectividad limitada.
  Sabremos que hemos tenido éxito cuando ≥15% de los reportes provengan de sesiones iniciadas sin conexión y sincronizadas posteriormente.

Estas hipótesis se priorizarán por impacto y nivel de incertidumbre; las de mayor riesgo (precisión del modelo, adopción institucional, retención inicial) serán abordadas en los primeros ciclos experimentales para reducir desperdicio de esfuerzo.

#### 1.2.2.4. Lean UX Canvas

El siguiente Lean UX Canvas presentado busca estructurar la propuesta presentada. Diseñada bajo los principios de Lean UX con el fin de validar tempranamente las hipótesis de valor y factibilidad. Este marco sintetiza el problema central, los objetivos de negocio, los usuarios clave y las soluciones planteadas, permitiendo orientar el diseño hacia resultados medibles y enfocados en las verdaderas necesidades de ciudadanos y autoridades municipales.

![lean_ux_canvas](<images/lean_ux_canvas/LEAN UX CANVAS.png>)

Esta propuesta aborda la gestión fragmentada de incidencias urbanas en Lima mediante una aplicación móvil ciudadana, un backend con inteligencia artificial de visión por computadora y un dashboard geoespacial para autoridades. Los principales beneficiarios son los ciudadanos, que ganan un canal confiable y trazable, y las municipalidades, que obtienen herramientas de priorización basadas en datos.

El éxito se medirá en términos de reportes válidos, precisión en la clasificación, reducción de tiempos de respuesta y adopción institucional. La hipótesis central sostiene que la combinación de captura estructurada, validación automática y analítica geoespacial generará mayor eficiencia y confianza. Para validar esto, el primer aprendizaje clave es confirmar la disposición de las municipalidades a adoptar la plataforma, lo cual se evaluará con un prototipo de baja fidelidad en pruebas iniciales con ciudadanos y funcionarios.

### 1.3. Segmentos Objetivo

Esta sección define los segmentos objetivo iniciales sobre los cuales se construirá y validará la propuesta de valor de la plataforma. La selección se orienta a maximizar aprendizaje validado en el menor tiempo, reduciendo incertidumbre sobre adopción y utilidad. Se priorizan únicamente dos segmentos núcleo para mantener foco operativo y claridad en las métricas tempranas.

### 1.3.1 **Segmento: Ciudadano Reportante**

**Descripción:** Residente urbano con smartphone (predominio Android) que se desplaza por la ciudad y está dispuesto a registrar incidencias visibles específicamente baches y acumulación de basura mediante fotografía y ubicación automática. Utilizará exclusivamente la aplicación móvil.

**Necesidades Clave:**

- Canal único y confiable para reportar incidencias sin procesos burocráticos.
- Confirmación visible y trazable del estado del reporte.
- Retroalimentación que evidencie que su acción genera efecto.

**Propuesta de Valor Específica:** Reducir fricción del registro a menos de 40 segundos, entregar confirmación inmediata y mostrar evolución de estado para incentivar reuso y participación cívica continua.

**Indicadores (Métricas Tempranas):**

- Tasa de completitud de reporte (foto válida + geolocalización + categoría confirmada). Objetivo piloto: ≥70%.
- Usuarios recurrentes (segundo reporte dentro de 45 días). Objetivo piloto: ≥30%.
- Tiempo medio de creación de reporte (apertura → envío). Objetivo piloto: <40 s.
- Satisfacción percibida sobre transparencia (encuesta corta in‑app). Objetivo piloto: ≥60% positiva.

**Riesgos Principales:**

- Falta de percepción de impacto (disminuye retención).
- Problemas de conectividad (impide envío inmediato).

**Mitigaciones:**

- Notificaciones de avance / cierre.
- Modo offline con sincronización diferida.
- Mensajes educativos breves sobre cómo tomar fotos válidas.

### 1.3.2 **Segmento: personal Municipal (técnico y de gestión)**

**Descripción:** Equipo técnico y de gestión (obras, mantenimiento, servicios públicos o innovación) que revisa, prioriza y asigna recursos para intervención de incidencias. Consumirá exclusivamente el dashboard web (visualización geoespacial, panel de métricas y filtros).

**Necesidades Clave:**

- Consolidación automática de reportes ciudadanos filtrando ruido y duplicados.
- Priorización visual (mapas de calor, ranking por severidad / frecuencia).
- Métricas operativas para soporte de decisiones y rendición de cuentas.

**Propuesta de Valor Específica:** Disminuir el tiempo de priorización y brindar evidencia georreferenciada para justificar asignación de cuadrillas y presupuestos menores a mantenimiento correctivo tardío.

**Indicadores (Métricas Tempranas):**

- Uso semanal del dashboard (≥1 sesión/semana). Objetivo piloto: ≥1 gerencia sostenida.
- Reducción del tiempo medio de priorización respecto a línea base. Objetivo: ≥40%.
- Porcentaje de incidencias con primera acción registrada dentro del SLA definido. Objetivo piloto: ≥25% de mejora vs. baseline.
- Tasa de reportes inválidos tras depuración automática. Objetivo: <15%.

**Riesgos Principales:**

- Falta de adopción institucional por procesos internos rígidos.
- Precisión insuficiente del clasificador que genere desconfianza.

**Mitigaciones:**

- Piloto acotado con feedback quincenal.
- Ajuste incremental del modelo con dataset local.
- SLA interno acordado para registrar primera acción.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Se identificaron los siguientes competidores y proyectos relacionados dentro del contexto académico y de soluciones ciudadanas:

| Competidor / Trabajo                              |                              Tipo | Descripción breve                                                                                                          | Fortalezas principales                                                  |
| ------------------------------------------------- | --------------------------------: | -------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| **TheShield App**                                 |        App de seguridad ciudadana | Aplicación móvil orientada a reportes y alertas de seguridad; incluye gestión y moderación de incidencias.                 | Orientación comunitaria; reglas de moderación; adopción vecinal.        |
| **Proyectos UPC — Módulos Reportes/Dashboard**    |  Prototipos / Trabajos académicos | Varios trabajos que incluyen paneles de control y módulos de reporte ciudadano; suelen ser prototipos o MVPs de gestión.   | Conceptos validados; prototipos funcionales; enfoque analítico.         |
| **Tesis y estudios — Conservación vial / Baches** | Investigación académica / Técnica | Tesis enfocadas en identificación de baches, métricas de mantenimiento y propuestas de intervención; menos foco en UX/app. | Rigor técnico; metodologías aplicables a priorización de mantenimiento. |

### 2.1.1. Análisis competitivo

**Objetivo:** Identificar similitudes, diferencias y ventajas competitivas frente a los trabajos y soluciones detectadas.

**Resumen comparativo (alto nivel):**

| Ítem / Atributo       |                                                                         Nuestra Plataforma (Propuesta) | TheShield App                                                      | Proyectos UPC (Reportes/Dashboard)                                       | Tesis Conservación Vial                                           |
| --------------------- | -----------------------------------------------------------------------------------------------------: | ------------------------------------------------------------------ | ------------------------------------------------------------------------ | ----------------------------------------------------------------- |
| **Perfil / overview** | App móvil + backend con detección IA (YOLO), PostGIS y dashboards geoespaciales para reportes urbanos. | App centrada en seguridad ciudadana (reportes y alertas).          | Prototipos con paneles de control y gestión de reportes.                 | Estudios técnicos sobre identificación y priorización de baches.  |
| **Valor ofrecido**    |       Detección automática + mapas de calor + priorización para municipalidades; API para integración. | Canal de reporte y gestión de incidentes de seguridad.             | Visualización de datos y métricas; enfoque académico/prueba de concepto. | Metodologías y métricas para mantenimiento vial; poco foco en UX. |
| **Mercado objetivo**  |                                                               Ciudadanos limeños y personal municipal. | Vecinos y comités de seguridad.                                    | Organizaciones que requieren gestión de procesos y reporting.            | Autoridades técnicas y consultoras de infraestructura.            |
| **Fortalezas**        |                                             IA geoespacial y priorización; enfoque integrable con SIG. | Adopción comunitaria y reglas de moderación.                       | Prototipos funcionales y validados en contexto académico.                | Rigor técnico y metodológico en mantenimiento vial.               |
| **Debilidades**       |                           Necesidad de dataset local y validación municipal; recursos para despliegue. | Alcance limitado a seguridad; no enfocado en infraestructura vial. | Escalabilidad y soporte limitados; entregables académicos.               | No orientado a producto; falta UX / integración con apps.         |

### 2.1.2. Estrategias y tácticas frente a competidores

A continuación se detallan estrategias (nivel estratégico) y tácticas (acciones operativas) recomendadas para posicionar la plataforma y enfrentar a los competidores identificados.

#### Estrategias (alto nivel)

- **Diferenciación técnica por IA + enfoque geoespacial:** modelo YOLO entrenado específicamente para detectar baches y basura con dataset local mínimo de 2,000 imágenes, complementado con mapas de calor para priorizar incidencias.
- **Go-to-Market B2G / B2C:** pilotos con municipalidades pequeñas para validar flujo operativo y KPIs.
- **Posicionamiento dual ciudadano-municipal:** canal directo para reportes ciudadanos con herramientas analíticas para personal municipal.
- **Verificación híbrida (IA + validación humana):** reducir falsos reportes y aumentar la confianza municipal.

#### Tácticas (acciones concretas)

- **Producto:** Implementar filtro inicial con IA en el móvil, sincronización offline y flag de confianza en cada reporte. Documentar endpoints de la API en anexos.
- **Piloto:** Ofrecer un piloto de 3 meses con un distrito pequeño. KPIs sugeridos: tiempo medio de atención, % de reportes verificados, reducción de falsos positivos.
- **Comercial:** Talleres de adopción con gerencias de obras; dashboards personalizados para supervisores.
- **Marketing / Comunidad:** Programa de embajadores vecinales para promover uso ciudadano responsable.
- **Alianzas:** MOUs con municipalidades para acceso a datos SIG y flujos de atención.
- **Defensa competitiva:** Lanzar MVP centrado en una categoría (p.ej. baches) y mostrar resultados cuantificables antes de escalar.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Para comprender las necesidades, comportamientos y expectativas de nuestros segmentos objetivo, se ha diseñado un proceso de entrevistas estructurado con guías específicas por perfil. Estas entrevistas buscan validar hipótesis clave sobre el uso de la plataforma y descubrir insights no anticipados.

#### **Objetivos generales de las entrevistas**

- Validar el problema percibido de gestión reactiva de incidencias urbanas
- Entender el flujo actual de reporte y seguimiento de problemas urbanos
- Identificar barreras potenciales para la adopción de la plataforma
- Descubrir preferencias específicas sobre experiencia de usuario y funcionalidades
- Recopilar información sobre patrones de uso de tecnología móvil

#### **A. Entrevista: Ciudadano Reportante**

Preguntas demográficas y contextuales

1. ¿Cuál es su nombre y edad?
2. ¿En qué distrito de Lima reside actualmente?

Experiencia actual con problemas urbanos

1. ¿Ha observado problemas de infraestructura en su distrito durante el último mes? ¿Cuáles?
2. Cuando detecta un problema urbano (bache, basura acumulada, poste caído), ¿suele reportarlo? ¿Por qué sí o por qué no?
3. Si ha reportado alguna vez, ¿qué canales utilizó? ¿Cómo fue su experiencia?
4. ¿Recibió algún tipo de seguimiento o confirmación? ¿Observó que el problema fuera resuelto?

Validación de concepto

1. ¿Qué le parece la idea de una aplicación que le permita reportar problemas urbanos con una foto y geolocalización automática?
2. ¿Qué beneficios personales percibiría al usar esta plataforma?
3. ¿Le interesaría ver reportes de otros ciudadanos en su zona? ¿Por qué?
4. ¿Qué factores lo motivarían a utilizar la aplicación de forma recurrente?

#### **B. Entrevista: Personal Municipal**

Preguntas de contexto profesional

1. ¿Cuál es su nombre y cargo dentro de la municipalidad?
2. ¿Cuánto tiempo lleva trabajando en gestión municipal?
3. ¿Cuáles son sus principales responsabilidades relacionadas con infraestructura urbana?

Proceso actual de gestión de incidencias

1. ¿Cómo llegan actualmente los reportes ciudadanos sobre problemas de infraestructura?
2. ¿Qué proceso siguen desde que se recibe un reporte hasta su resolución?
3. ¿Cómo determinan la prioridad de atención entre múltiples reportes?

Métricas y toma de decisiones

1. ¿Utilizan actualmente mapas o visualizaciones geográficas para análisis de incidencias?
2. ¿Cuentan con información histórica sobre patrones de problemas urbanos? ¿Cómo la utilizan?

Validación de concepto

1. ¿Qué utilidad le ve a una plataforma con estas características?
2. ¿Qué métricas o visualizaciones específicas serían más valiosas para su trabajo? _(Ejem: Concentración de incidencias según zona, satisfacción cuidadana tras la resolucipon del problema, etc)_
3. ¿Qué preocupaciones tendría sobre la implementación de este sistema?
4. ¿Sería compatible con sus sistemas actuales? ¿Qué consideraciones de integración serían importantes?

### 2.2.2. Registro de entrevistas

#### Entrevista 01

- **Nombres:** Rosalynn
- **Apellidos:** Saavedra
- **Edad:** 47 años
- **Distrito:** Lurigancho - Chosica
- **Perfil:** Ciudadano Reportante
- **Evidencia de la reunión:**

![interview_rosalynn](images/interviews/interview_rosalynn.png)

- **Inicio:** 0:00
- **Fin:** 3:24
- **Enlace de entrevista:** [https://drive.google.com/file/d/1k16nT_7CvDAej8H3e1fnXmgkZEBjm6CN/view?usp=sharing](https://drive.google.com/file/d/1k16nT_7CvDAej8H3e1fnXmgkZEBjm6CN/view?usp=sharing)

#### Entrevista 02

- **Nombres:** Silvia
- **Apellidos:** Salvatierra
- **Edad:** 51 años
- **Distrito:** Callao - Bellavista
- **Perfil:** Ciudadano Reportante
- **Evidencia de la reunión:**

![interview_silvia](images/interviews/interview_silvia.png)

- **Inicio:** 0:00
- **Fin:** 3:05
- **Enlace de entrevista:** [https://drive.google.com/file/d/1Trk5RaI-7b8vEiCClu6NsdXGdaMnVTXr/view?usp=sharing](https://drive.google.com/file/d/1Trk5RaI-7b8vEiCClu6NsdXGdaMnVTXr/view?usp=sharing)

#### Entrevista 03

- **Nombres:** xxx
- **Apellidos:** xxx
- **Edad:** xxx
- **Distrito:** xxx
- **Perfil:** Ciudadano Reportante
- **Evidencia de la reunión:**
- **Inicio:** xxx
- **Fin:** xxx
- **Enlace de entrevista:**
  [Entrevistas - Ciudadanos.mp4](https://drive.google.com/file/d/1234567890/view)

#### Entrevista 04

- **Nombres:** xxx
- **Apellidos:** xxx
- **Edad:** xxx
- **Distrito:** xxx
- **Perfil:** Personal Municipal
- **Evidencia de la reunión:**
<!-- ![Landing Page 1](./images/deployment/landing1.png) -->

- **Inicio:** xxx
- **Fin:** xxx
- **Enlace de entrevista:**
  [Entrevistas - Municipios.mp4](https://drive.google.com/file/d/1234567890/view)

### Entrevista 05

- **Nombres:** xxx
- **Apellidos:** xxx
- **Edad:** xxx
- **Distrito:** xxx
- **Perfil:** Personal Municipal
- **Evidencia de la reunión:**
<!-- ![Landing Page 1](./images/deployment/landing1.png) -->

- **Inicio:** xxx
- **Fin:** xxx
- **Enlace de entrevista:**
  [Entrevistas - Municipios.mp4](https://drive.google.com/file/d/1234567890/view)

#### Entrevista 06

- **Nombres:** Ana
- **Apellidos:** Torres
- **Edad:** 32
- **Distrito:** San Miguel
- **Perfil:** Personal Municipal
- **Evidencia de la reunión:**

![interview_ana](images/interviews/entrevista_ana.jpg)

- **Inicio:** 0:00
- **Fin:** 2:05
- **Enlace de entrevista:**
  [Entrevistas - Municipios.mp4](https://drive.google.com/file/d/1234567890/view)

### 2.2.3. Análisis de entrevistas

Para el proyecto de Plataforma Urbana Inteligente para Lima, se realizaron entrevistas a 3 ciudadanos reportantes y 3 funcionarios municipales de diversos distritos de Lima Metropolitana. A partir de sus respuestas, se identificaron las siguientes características y patrones:

#### Hallazgos clave - Ciudadanos Reportantes:

- **Perfil demográfico**: [Porcentaje]% de los entrevistados tienen entre [rango de edad] años, con residencia principalmente en los distritos de [nombres de distritos].

- **Experiencia con problemas urbanos**: [Porcentaje]% ha observado problemas de infraestructura en su distrito durante el último mes, siendo los más comunes [listar problemas frecuentes].

- **Comportamiento de reporte**: [Porcentaje]% ha intentado reportar algún problema urbano, principalmente a través de [canales más utilizados].

- **Nivel de satisfacción con canales actuales**: [Porcentaje]% expresa frustración con los mecanismos de reporte existentes, principalmente debido a [razones principales].

- **Seguimiento de reportes**: [Porcentaje]% indica no haber recibido ningún tipo de confirmación o seguimiento después de reportar un problema.

- **Uso de dispositivos móviles**: [Porcentaje]% utiliza smartphones de forma regular para diversas actividades, con [sistema operativo predominante] como plataforma principal.

- **Aceptación del concepto**: [Porcentaje]% muestra interés alto o muy alto en utilizar una aplicación para reportar problemas urbanos con foto y geolocalización automática.

- **Motivadores para adopción recurrente**:
  - [Porcentaje]% valora la transparencia y visibilidad del estado del reporte
  - [Porcentaje]% considera importante ver el impacto real de sus reportes
  - [Porcentaje]% mencionó la importancia de una interfaz sencilla y rápida

#### Hallazgos clave - Personal Municipal:

- **Perfil profesional**: Los entrevistados tienen un promedio de [número] años de experiencia en gestión municipal, con responsabilidades en [áreas principales].

- **Proceso actual de gestión**: [Porcentaje]% indica que los reportes ciudadanos llegan principalmente a través de [canales más comunes], siguiendo un flujo que toma en promedio [tiempo] para ser procesados.

- **Herramientas de análisis**: [Porcentaje]% no utiliza actualmente mapas o visualizaciones geográficas para el análisis de incidencias urbanas.

- **Priorización de atención**: La mayoría determina la prioridad basándose en [criterios más comunes], sin un sistema estructurado de clasificación.

- **Información histórica**: [Porcentaje]% no cuenta con sistemas eficientes para utilizar datos históricos en la prevención o planificación de mantenimiento urbano.

- **Aceptación del concepto**: [Porcentaje]% considera que una plataforma con las características propuestas sería [nivel de utilidad] para su trabajo.

- **Métricas valoradas**: Las visualizaciones y métricas más valoradas por el personal municipal incluyen:

  - [Porcentaje]% - [Métrica o visualización específica]
  - [Porcentaje]% - [Métrica o visualización específica]
  - [Porcentaje]% - [Métrica o visualización específica]

- **Preocupaciones de implementación**: Las principales inquietudes expresadas fueron:
  - [Preocupación 1]
  - [Preocupación 2]
  - [Preocupación 3]

#### Validación de hipótesis:

| Hipótesis                                                              | Resultado              | Evidencia                                                                                            |
| ---------------------------------------------------------------------- | ---------------------- | ---------------------------------------------------------------------------------------------------- |
| Los ciudadanos están frustrados con los canales actuales de reporte    | [Validada/No validada] | [Porcentaje]% expresó frustración con los canales actuales debido a [razones principales]            |
| Los problemas de conectividad son una barrera significativa            | [Validada/No validada] | [Porcentaje]% reporta problemas frecuentes de conectividad en [situaciones específicas]              |
| La retroalimentación sobre estado del reporte es crítica para adopción | [Validada/No validada] | [Porcentaje]% mencionó la importancia de recibir actualizaciones sobre el estado de sus reportes     |
| Los municipios carecen de herramientas para visualizar patrones        | [Validada/No validada] | [Porcentaje]% de funcionarios municipales confirmó no utilizar mapas o visualizaciones geoespaciales |
| La clasificación automática de incidencias agilizaría procesos         | [Validada/No validada] | [Porcentaje]% de funcionarios identificó valor en la automatización de la clasificación              |

#### Conclusiones y recomendaciones:

1. **[Conclusión principal 1]**: Basado en [hallazgos específicos], recomendamos [acción concreta].

2. **[Conclusión principal 2]**: Los datos muestran que [patrón identificado], por lo que se debería priorizar [característica o enfoque].

3. **[Conclusión principal 3]**: La brecha entre [expectativa] y [realidad actual] representa una oportunidad para [propuesta de valor específica].

4. **[Conclusión principal 4]**: Para incrementar la adopción y retención de usuarios, es fundamental [recomendación basada en entrevistas].

5. **[Conclusión principal 5]**: Las preocupaciones sobre [tema específico] deben ser abordadas mediante [estrategia o característica].

## 2.3. Needfinding

### 2.3.1. User Personas

#### Ciudadano Reportante

**Carlos Mendoza** representa al segmento de ciudadanos proactivos que utilizan la tecnología para mejorar su entorno urbano. Con 34 años y residente de Comas, Carlos combina su rutina diaria de trabajo y responsabilidades familiares con una participación cívica consciente. Su experiencia con aplicaciones móviles y frustración con los canales tradicionales de reporte lo convierten en el usuario ideal para adoptar una plataforma digital que le permita reportar problemas urbanos de manera eficiente. Su principal motivación es contribuir al mejoramiento de su distrito mientras obtiene transparencia sobre el seguimiento de sus reportes.

![User Persona 1](./images/needfinding/user-persona-cuidadano.png)

#### Personal Municipal

**Fátima Garaycochea** encarna el perfil del funcionario municipal moderno que busca optimizar la gestión de incidencias urbanas mediante herramientas tecnológicas. Como Supervisora de Mantenimiento Urbano en Surquillo con 8 años de experiencia, Fátima enfrenta diariamente el desafío de coordinar recursos limitados para atender múltiples reportes ciudadanos. Su expertise en gestión de equipos y análisis de datos la posiciona como usuaria clave para adoptar dashboards geoespaciales que le permitan tomar decisiones basadas en evidencia, reducir tiempos de priorización y mejorar la eficiencia operativa de su equipo.

![User Persona 2](./images/needfinding/user-persona-personalmunicipio.png)

### 2.3.2. User Task Matrix

Los segmentos considerados para este análisis son:

- **Carlos Mendoza** (Ciudadano Reportante): Representa a residentes urbanos que identifican y reportan problemas de infraestructura
- **Fátima Garaycochea** (Personal Municipal): Representa al equipo técnico municipal que gestiona y resuelve incidencias urbanas

#### Matriz de Tareas - Carlos Mendoza (Ciudadano Reportante)

| **Tareas**                                                         | **Frecuencia** | **Importancia** |
| ------------------------------------------------------------------ | :------------: | :-------------: |
| **Observar problemas urbanos durante desplazamientos diarios**     |      Alta      |      Alta       |
| **Tomar fotografías de incidencias detectadas**                    |     Media      |      Alta       |
| **Reportar problemas identificados a autoridades**                 |     Media      |      Alta       |
| **Buscar información sobre estado de reportes enviados**           |     Media      |      Alta       |
| **Consultar rutas alternativas para evitar zonas problemáticas**   |      Alta      |      Media      |
| **Verificar ubicación exacta de problemas antes de reportar**      |     Media      |      Media      |
| **Comunicarse con vecinos sobre problemas comunes del área**       |      Baja      |      Media      |
| **Buscar canales oficiales de comunicación municipal**             |      Baja      |      Alta       |
| **Documentar horarios o condiciones específicas de los problemas** |      Baja      |      Media      |

#### Matriz de Tareas - Fátima Garaycochea (Personal Municipal)

| **Tareas**                                                         | **Frecuencia** | **Importancia** |
| ------------------------------------------------------------------ | :------------: | :-------------: |
| **Revisar reportes ciudadanos recibidos**                          |      Alta      |      Alta       |
| **Validar veracidad de reportes**                                  |      Alta      |      Alta       |
| **Priorizar incidencias según urgencia**                           |      Alta      |      Alta       |
| **Asignar cuadrillas de trabajo a incidencias específicas**        |      Alta      |      Alta       |
| **Generar reportes de gestión semanales**                          |     Media      |      Alta       |
| **Consultar mapas para ubicar incidencias geográficamente**        |      Alta      |      Media      |
| **Monitorear cumplimiento de plazos de resolución**                |      Alta      |      Alta       |
| **Comunicar avances a ciudadanos reportantes**                     |      Baja      |      Media      |
| **Analizar patrones geográficos de incidencias**                   |      Baja      |      Media      |
| **Evaluar efectividad de intervenciones realizadas**               |      Baja      |      Alta       |
| **Coordinar con otras áreas municipales**                          |     Media      |      Media      |
| **Actualizar estados de incidencias en sistemas internos**         |      Alta      |      Media      |
| **Planificar mantenimiento preventivo basado en datos históricos** |      Baja      |      Alta       |

#### Análisis de Resultados

**Principales diferencias entre User Personas:**

La diferencia fundamental radica en la naturaleza de sus responsabilidades: Carlos se enfoca en detectar y comunicar problemas como ciudadano individual, mientras que Fátima gestiona recursos y coordina equipos como funcionaria municipal. Esto se refleja en el volumen y complejidad de sus tareas, Carlos maneja actividades más directas y puntuales relacionadas con la observación y reporte, mientras que Fátima supervisa procesos continuos que requieren análisis, priorización y coordinación institucional. Además, el impacto de sus decisiones varía significativamente: las acciones de Carlos afectan principalmente su experiencia personal y entorno inmediato, mientras que las decisiones de Fátima impactan a múltiples ciudadanos y determinan la eficiencia del servicio público municipal.

**Principales coincidencias entre User Personas:**

Ambos usuarios comparten la necesidad fundamental de información precisa sobre ubicaciones geográficas, aunque con propósitos diferentes, Carlos para reportar correctamente y Fátima para planificar intervenciones efectivas. También valoran el seguimiento y monitoreo del progreso de las incidencias: Carlos necesita transparencia sobre el estado de sus reportes para mantener confianza en el sistema, mientras que Fátima requiere visibilidad para cumplir con los plazos de resolución y rendir cuentas. Finalmente, ambos se benefician de una comunicación bidireccional eficiente, donde Carlos puede transmitir información clara sobre problemas urbanos y Fátima puede proporcionar actualizaciones sobre las acciones tomadas, creando un ciclo de retroalimentación que fortalece la participación ciudadana y mejora la gestión municipal.

### 2.3.3. Empathy Mapping

#### Ciudadano Reportante

![Empathy Mapping 1](./images/needfinding/Empathy%20map-carlos.png)

#### Personal Municipal

![Empathy Mapping 2](./images/needfinding/Empathy%20map-fatima.png)

### 2.3.4. As-is Scenario Mapping

#### Ciudadano Reportante

La siguiente tabla representa el escenario actual (as-is) desde la perspectiva del Ciudadano Reportante. Se detallan las fases que atraviesa un usuario al identificar un problema en el espacio público, desde su detección hasta la espera de una solución por parte de la municipalidad. Se incluyen las acciones que realiza (Doing), los pensamientos asociados (Thinking) y las emociones que experimenta (Feeling), junto con la identificación de puntos positivos, negativos y áreas donde se requiere mayor aprendizaje. <br>

| **Phases**                   | **Doing**                                                                                                                                                          | **Thinking**                                                                                                                                    | **Feeling**                                                                                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Detectar problema urbano** | - Observa baches, basura o postes dañados en la vía pública. <br> - Identifica que afecta su tránsito o seguridad. <br> - A veces toma fotos con su celular.       | - “Esto debería arreglarlo la municipalidad.” <br> - “No sé si alguien ya lo habrá reportado.” <br> - “¿Vale la pena gastar mi tiempo en esto?” | - Frustración al ver que los problemas se repiten. <br> - Desconfianza hacia la gestión municipal. <br> - Indiferencia si el problema no lo afecta directamente. |
| **Decidir si reportar**      | - Evalúa si usar teléfono, web o ir presencial. <br> - Considera el esfuerzo vs. posible respuesta. <br> - A veces comenta el problema con vecinos.                | - “¿Realmente harán algo si lo reporto?” <br> - “Tal vez alguien más ya lo informó.” <br> - “Si es muy grave, no me queda otra.”                | - Duda e inseguridad sobre el impacto de su acción. <br> - Falta de motivación. <br> - Molestia por procesos engorrosos.                                         |
| **Realizar reporte**         | - Llama por teléfono, escribe correo o llena un formulario web. <br> - Explica la ubicación y tipo de problema. <br> - Puede adjuntar foto si el canal lo permite. | - “Ojalá no sea tan complicado.” <br> - “Espero que entiendan bien lo que describo.” <br> - “¿Me pedirán demasiados datos?”                     | - Cansancio si el proceso es largo. <br> - Alivio si logra enviar el reporte. <br> - Impotencia si no recibe confirmación.                                       |
| **Esperar respuesta**        | - Revisa si alguien de la municipalidad responde. <br> - Pregunta a vecinos si vieron alguna acción. <br> - Vuelve a pasar por el lugar para verificar.            | - “Seguro no harán nada.” <br> - “¿Cuánto tiempo más tendré que esperar?” <br> - “¿A dónde reclamo si no contestan?”                            | - Impaciencia por falta de comunicación. <br> - Desconfianza en las autoridades. <br> - Desmotivación para futuros reportes.                                     |
| **Verificar resolución**     | - Observa si el problema sigue en la calle. <br> - Comenta con otros vecinos si hubo solución. <br> - Deja de hacer seguimiento si no ve cambios.                  | - “Al final nunca arreglaron nada.” <br> - “Funcionó esta vez, pero no sé si pasará siempre.” <br> - “¿Debo volver a reportar?”                 | - Satisfacción si el problema fue resuelto. <br> - Frustración si nada cambió. <br> - Resignación si el problema persiste.                                       |

#### Personal Municipal

La siguiente tabla describe el escenario actual (as-is) desde el punto de vista del Personal Municipal encargado de gestionar las incidencias reportadas por los ciudadanos. El flujo contempla las fases que inician con la recepción de un reporte, su verificación, priorización y posterior asignación para resolución. Asimismo, se presentan las acciones realizadas (Doing), los pensamientos (Thinking) y las emociones (Feeling) experimentadas, resaltando tanto los aspectos favorables como las limitaciones y oportunidades de mejora.<br>

| **Phases**                   | **Doing**                                                                                                                                                                                                    | **Thinking**                                                                                                                                            | **Feeling**                                                                                                                                          |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Recepción de reportes**    | - Recibe llamadas, correos, formularios o quejas presenciales. <br> - Escucha quejas repetitivas de ciudadanos. <br> - Revisa bandejas de entrada varias veces al día.                                       | - “Nos llegan demasiados reportes dispersos.” <br> - “No todos son relevantes o urgentes.” <br> - “¿Cómo organizamos todo esto?”                        | - Sobrecarga por el volumen de reportes. <br> - Estrés por falta de recursos. <br> - Impotencia al no poder atender todo.                            |
| **Registro y clasificación** | - Anota manualmente la información en hojas de cálculo o sistemas básicos. <br> - Categoriza incidencias según tipo (baches, basura, postes). <br> - A veces transcribe información incompleta o poco clara. | - “Los reportes llegan sin formato estándar.” <br> - “Perdemos tiempo en organizar lo mismo siempre.” <br> - “No tenemos datos consistentes.”           | - Cansancio por tareas repetitivas. <br> - Frustración al lidiar con información incompleta. <br> - Desmotivación por la falta de apoyo tecnológico. |
| **Priorización**             | - Evalúa la urgencia según gravedad, visibilidad o quejas acumuladas. <br> - Consulta con superiores en casos críticos. <br> - Elabora una lista de atención por orden de prioridad.                         | - “No tenemos criterios claros ni objetivos.” <br> - “Atendemos lo más urgente, lo demás queda pendiente.” <br> - “Siempre faltan recursos para todo.”  | - Ansiedad al tener que decidir qué dejar sin atender. <br> - Estrés por presión ciudadana. <br> - Resignación ante limitaciones.                    |
| **Coordinación de atención** | - Contacta cuadrillas de mantenimiento o contratistas. <br> - Informa ubicación y naturaleza del problema. <br> - Hace seguimiento por llamadas o visitas presenciales.                                      | - “Ojalá las cuadrillas tengan disponibilidad.” <br> - “Si no hay presupuesto, esto no se hará.” <br> - “Necesito comprobar que realmente intervengan.” | - Alivio cuando logra coordinar con éxito. <br> - Incomodidad si no hay respuesta rápida. <br> - Frustración por falta de recursos materiales.       |
| **Cierre y comunicación**    | - Verifica si el problema fue atendido. <br> - A veces notifica al ciudadano, otras no. <br> - Archiva el caso en registros internos.                                                                        | - “No siempre podemos avisar a todos los que reportaron.” <br> - “Los vecinos creen que no hacemos nada.” <br> - “Falta un sistema más transparente.”   | - Satisfacción al cerrar casos. <br> - Frustración por falta de seguimiento formal. <br> - Desgaste emocional por quejas constantes.                 |

---

## 2.4. Ubiquitous Language

Los términos seleccionados se presentan en inglés, con su equivalente en español entre paréntesis, y se acompañan de definiciones claras y concisas en español.

1. **Incident (Incidencia):** Situación reportada por un ciudadano relacionada con un problema urbano, como baches, basura acumulada, luminarias dañadas o infraestructura en mal estado.
2. **Reporter (Reportante):** Ciudadano que notifica una incidencia mediante la aplicación o canales municipales.
3. **Geolocation (Geolocalización):** Identificación de la ubicación exacta de una incidencia mediante coordenadas GPS.
4. **Status Tracking (Seguimiento de estado):** Proceso de monitoreo del avance de una incidencia desde su registro hasta su cierre.
5. **Verified Report (Reporte verificado):** Incidencia revisada y confirmada por el personal municipal como válida y prioritaria.
6. **Heatmap (Mapa de calor):** Visualización geoespacial que muestra la concentración de incidencias en determinadas zonas de la ciudad.
7. **Priority (Prioridad):** Nivel de urgencia asignado a una incidencia según su impacto en la seguridad, salud pública o movilidad urbana.
8. **Resolution Time (Tiempo de resolución):** Periodo estimado o real que toma atender y cerrar una incidencia desde su registro hasta la solución.
9. **Escalation (Escalamiento):** Proceso mediante el cual una incidencia es derivada a una unidad municipal de mayor jerarquía o especialización.
10. **Citizen Feedback (Retroalimentación ciudadana):** Opinión o calificación proporcionada por el ciudadano respecto al manejo y resolución de su reporte.
11. **Closed Report (Reporte cerrado):** Estado de una incidencia que ya fue atendida y solucionada por la municipalidad.
12. **Unresolved Case (Caso no resuelto):** Incidencia registrada que permanece sin solución debido a falta de recursos, información o coordinación.
13. **Urban Asset (Activo urbano):** Elemento de la infraestructura pública sujeto a supervisión y mantenimiento, como postes, semáforos, parques o calles.
14. **Case Traceability (Trazabilidad del caso):** Registro histórico que permite seguir cada paso de la gestión de una incidencia.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

El To-Be Scenario Mapping presenta la visión futura de cómo los dos segmentos objetivo interactuarán con la plataforma urbana inteligente una vez implementada. Este análisis se basa directamente en las necesidades clave, propuestas de valor e indicadores definidos en la sección 1.3 Segmentos Objetivo, diseñando experiencias que cumplan con las métricas tempranas establecidas y mitiguen los riesgos identificados.

### 3.1.1. To-Be Scenario: Segmento Ciudadano Reportante

Basándose en la propuesta de valor de "reducir fricción del registro a menos de 40 segundos, entregar confirmación inmediata y mostrar evolución de estado", el escenario futuro optimiza cada fase del journey ciudadano.

| **Phases**                           | **Doing**                                                                                                                                                                                           | **Thinking**                                                                                                                                                                   | **Feeling**                                                                                                                                                |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Detectar incidencia urbana**       | - Abre la app móvil al observar bache o acumulación de basura. <br> - Activa modo cámara con geolocalización automática. <br> - Ve overlay de guía para captura óptima de la incidencia específica. | - "La app reconoce automáticamente mi ubicación." <br> - "Las guías me ayudan a tomar una foto clara del bache/basura." <br> - "Solo necesito enfocar el problema específico." | - Confianza por simplicidad del proceso. <br> - Motivación al ver que la tecnología facilita la participación. <br> - Empoderamiento por facilidad de uso. |
| **Registrar reporte (meta: <40s)**   | - Captura foto con un tap. <br> - Confirma categoría sugerida por IA (bache o basura). <br> - Agrega descripción opcional en 1-2 palabras. <br> - Envía con confirmación inmediata.                 | - "El sistema identificó correctamente que es un bache/basura." <br> - "Solo tomó 30 segundos completar todo." <br> - "Ya tengo mi código de seguimiento #URB2025001."         | - Satisfacción por cumplir meta temporal. <br> - Alivio al recibir confirmación inmediata. <br> - Confianza en el sistema de trazabilidad.                 |
| **Seguimiento transparente**         | - Recibe notificación push: "Reporte verificado por municipalidad". <br> - Consulta estado en app: "En programación - Est. 7 días". <br> - Ve progreso en tiempo real con actualizaciones.          | - "Puedo ver exactamente en qué etapa está." <br> - "La municipalidad me mantiene informado automáticamente." <br> - "Sé cuándo esperar la solución."                          | - Tranquilidad por transparencia del proceso. <br> - Confianza en las autoridades por comunicación activa. <br> - Paciencia informada por expectativas.    |
| **Cierre y retroalimentación**       | - Recibe notificación: "Incidencia resuelta" con foto de evidencia. <br> - Califica atención en escala 1-5. <br> - Ve impacto de sus reportes en dashboard comunitario de zona.                     | - "Veo que realmente atendieron el problema con evidencia." <br> - "Mi opinión cuenta para mejorar el servicio." <br> - "Mis reportes generan impacto real."                   | - Satisfacción por ver resultados tangibles. <br> - Valoración personal por contribución efectiva. <br> - Orgullo cívico por participación constructiva.   |
| **Adopción recurrente (meta: ≥30%)** | - Explora mapa de zona para ver patrones de incidencias. <br> - Reporta nueva incidencia con mayor confianza. <br> - Comparte experiencia positiva con vecinos y familiares.                        | - "Entiendo mejor los problemas de mi distrito." <br> - "Vale la pena seguir participando." <br> - "Otros vecinos deberían usar esto también."                                 | - Empoderamiento cívico sostenido. <br> - Sentido de pertenencia comunitaria. <br> - Agencia personal en mejoramiento urbano continuo.                     |

**Métricas To-Be Logradas:**

- Tiempo de reporte: 25-35 segundos (meta <40s ✓)
- Completitud: >85% reportes con foto válida + geolocalización + categoría (meta ≥70% ✓)
- Satisfacción transparencia: >75% rating positivo (meta ≥60% ✓)
- Retención: 45% usuarios reportan segunda vez en 45 días (meta ≥30% ✓)

### 3.1.2. To-Be Scenario: Segmento Personal Municipal

Basándose en la propuesta de valor de "disminuir tiempo de priorización y brindar evidencia georreferenciada", el escenario futuro transforma la gestión municipal hacia un enfoque estratégico y basado en datos.

| **Phases**                            | **Doing**                                                                                                                                                                                       | **Thinking**                                                                                                                                                           | **Feeling**                                                                                                                                                                        |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Consolidación automática**          | - Accede al dashboard web con reportes pre-validados. <br> - Ve clasificación por IA con nivel de confianza ≥80%. <br> - Filtra por zona, tipo (baches/basura) y urgencia.                      | - "Los reportes llegan organizados y pre-categorizados." <br> - "Puedo confiar en la clasificación automática." <br> - "Solo reviso casos de baja confianza."          | - Alivio por reducción de carga administrativa. <br> - Confianza en calidad de datos automatizada. <br> - Optimismo por eficiencia operativa ganada.                               |
| **Priorización visual (meta: ≥40%)**  | - Consulta mapas de calor para identificar hotspots de incidencias. <br> - Usa ranking automático por severidad/frecuencia. <br> - Genera plan de asignación optimizado por rutas y recursos.   | - "Los patrones geográficos son evidentes y accionables." <br> - "La priorización automática tiene lógica clara." <br> - "Puedo justificar decisiones con data."       | - Confianza en decisiones basadas en evidencia. <br> - Reducción de estrés por criterios objetivos. <br> - Profesionalismo por herramientas avanzadas.                             |
| **Coordinación eficiente**            | - Asigna casos a cuadrillas desde dashboard con ubicación exacta. <br> - Monitorea progreso con notificaciones automáticas. <br> - Recibe alertas sobre demoras o impedimentos reportados.      | - "Las cuadrillas tienen información completa y precisa." <br> - "Tengo visibilidad total del progreso sin llamadas." <br> - "Los problemas se detectan antes."        | - Control operativo efectivo sin microgestión. <br> - Tranquilidad por supervisión automatizada. <br> - Proactividad en resolución de impedimentos.                                |
| **Seguimiento y métricas (SLA +25%)** | - Sistema actualiza automáticamente a ciudadanos por cada cambio de estado. <br> - Genera reportes semanales con métricas clave. <br> - Documenta cierre con evidencia fotográfica obligatoria. | - "La comunicación ciudadana es automática y consistente." <br> - "Tengo métricas claras de mi gestión." <br> - "La documentación es completa sin esfuerzo."           | - Liberación de carga comunicacional repetitiva. <br> - Orgullo por transparencia y profesionalismo. <br> - Satisfacción por calidad de documentación.                             |
| **Gestión estratégica**               | - Analiza tendencias históricas y patrones predictivos. <br> - Identifica zonas para mantenimiento preventivo. <br> - Justifica presupuestos con analítica de costos por tipo de intervención.  | - "Puedo anticipar problemas antes de que se agraven." <br> - "Los datos respaldan mis solicitudes de presupuesto." <br> - "Estamos siendo preventivos, no reactivos." | - Empoderamiento profesional por herramientas de gestión moderna. <br> - Satisfacción por impacto estratégico institucional. <br> - Motivación por innovación en servicio público. |

**Métricas To-Be Logradas:**

- Reducción tiempo priorización: 50% vs baseline (meta ≥40% ✓)
- Uso semanal dashboard: 100% gerencias piloto con ≥4 sesiones (meta ≥1 gerencia ✓)
- SLA primera acción: +35% mejora vs baseline (meta ≥25% ✓)
- Reportes inválidos: <10% tras depuración automática (meta <15% ✓)

### 3.1.3. Transformación Sistémica Habilitada

**Circuito de Retroalimentación Optimizado:**
El To-Be elimina las fricciones identificadas en el As-is creando un ciclo virtuoso donde:

- Ciudadanos reportan más por facilidad y transparencia (≥30% recurrencia)
- Municipalidad prioriza mejor con datos georreferenciados (≥40% reducción tiempo)
- Resoluciones más rápidas incrementan confianza ciudadana (≥60% satisfacción)
- Mayor volumen de reportes calificados mejora la analítica predictiva

**Diferenciación vs Competidores:**

- **TheShield App:** Enfoque integral urbano vs solo seguridad
- **Proyectos UPC:** Producción escalable vs prototipos académicos
- **Tesis viales:** UX ciudadana + dashboard municipal vs solo metodología técnica

**Alineación con Arquitectura:**

- **App móvil:** React Native con modo offline (ciudadanos)
- **Backend:** Microservicios con IA de clasificación (automatización)
- **Dashboard:** Mapas de calor PostGIS en tiempo real (municipalidad)
- **APIs:** Integración con sistemas municipales existentes (escalabilidad)

## 3.2. User Stories

### Epics

Las siguientes épicas representan funcionalidades de gran alcance que engloban un conjunto de necesidades o procesos clave dentro del proyecto. Su propósito es ofrecer una visión general de los objetivos estratégicos que debe cumplir la plataforma, sirviendo como punto de partida para dividir y organizar el trabajo en elementos más manejables.

| Epic ID |               Título               |                                                    Descripción                                                     |
| :-----: | :--------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
|   E01   |        Gestión de Usuarios         |          Funcionalidades para registro, inicio de sesión y perfiles tanto de autoridades como ciudadanos.          |
|   E02   | Gestión de Incidencias Ciudadanas  |      Funcionalidades que permiten a los ciudadanos reportar, visualizar y dar seguimiento a sus incidencias.       |
|   E03   | Gestión de Incidencias Municipales | Funcionalidades que permiten a las autoridades visualizar, filtrar, priorizar y dar seguimiento a las incidencias. |
|   E04   |    Comunicación y Transparencia    |               Funcionalidades de comentarios, estados y comunicación entre ciudadanos y autoridades.               |
|   E06   |     Información Institucional      |                        Funcionalidades de visualización de información de la municipalidad.                        |
|   E07   |        Landing Page Pública        |            Funcionalidades para visitantes de la landing page (información institucional y captación).             |

### User stories

Las presentes user stories descomponen las épicas en requerimientos más específicos, descritos desde la perspectiva del usuario final o del rol involucrado. Cada historia captura una necesidad concreta y el valor que aporta al sistema, permitiendo priorizar funcionalidades y mantener el enfoque en la experiencia de nuestros usuarios. </br> </br>

| Epic / User Story ID | Título                                | Descripción                                                                                                                                                                                     | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Relacionado con (Epic ID) |      Segmento      |
| -------------------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- | :----------------: |
| US01                 | Registro de personal municipales      | Como personal municipal, quiero registrarme en la plataforma para acceder a las funcionalidades de gestión.                                                                                     | Escenario 1: Registro exitoso<br>Dado que la personal municipal completa todos los campos<br>Cuando confirma el registro<br>Entonces el sistema crea su cuenta y envía confirmación.<br><br>Escenario 2: Datos incompletos<br>Dado que el formulario está incompleto<br>Cuando intenta registrarse<br>Entonces el sistema muestra un mensaje de error indicando los campos faltantes.<br><br>Escenario 3: Usuario ya existe<br>Dado que el correo ya está registrado<br>Cuando intenta registrarse<br>Entonces el sistema muestra mensaje de cuenta existente. | E01                       | Personal Municipal |
| US02                 | Inicio de sesión personal municipal   | Como personal municipal, quiero iniciar sesión para acceder al panel de gestión de incidencias.                                                                                                 | Escenario 1: Inicio exitoso<br>Dado que ingreso credenciales correctas<br>Cuando inicio sesión<br>Entonces accedo al panel principal.<br><br>Escenario 2: Credenciales incorrectas<br>Dado que ingreso datos erróneos<br>Cuando intento iniciar sesión<br>Entonces el sistema rechaza el acceso y muestra error.<br><br>Escenario 3: Campos obligatorios<br><br>Dado que intento iniciar sesión<br><br>Cuando dejo campos vacíos<br><br>Entonces el sistema me solicita completar la información.                                                              | E01                       | Personal Municipal |
| US03                 | Ver total de incidencias              | Como personal municipal, quiero ver el número total de incidencias registradas para monitorear el volumen general.                                                                              | Escenario 1: Visualización de total<br>Dado que accedo al panel<br>Cuando selecciono “Total de Incidencias”<br>Entonces se muestra el número acumulado.<br><br>Escenario 2: Actualización automática<br>Dado que se registra una nueva incidencia<br>Cuando refresco la vista<br>Entonces el total se actualiza automáticamente.<br><br>Escenario 3: Sin incidencias<br>Dado que no hay incidencias registradas<br>Cuando accedo al panel<br>Entonces veo el mensaje “No hay incidencias”.                                                                     | E03                       | Personal Municipal |
| US04                 | Filtrar incidencias                   | Como personal municipal, quiero filtrar incidencias por tipo, zona, prioridad o fecha para gestionarlas de forma más eficiente.                                                                 | Escenario 1: Filtrado por tipo<br>Dado que selecciono “tipo”<br>Cuando aplico el filtro<br>Entonces se muestran solo las incidencias de ese tipo.<br><br>Escenario 2: Filtrado por múltiples criterios<br>Dado que aplico varios filtros<br>Cuando ejecuto búsqueda<br>Entonces veo solo las incidencias que cumplen todos los criterios.<br><br>Escenario 3: Sin resultados<br>Dado que no existen coincidencias<br>Cuando aplico filtro<br>Entonces el sistema muestra “No se encontraron incidencias”.                                                      | E03                       | Personal Municipal |
| US05                 | Priorizar incidencias                 | Como personal municipal, quiero asignar prioridad a las incidencias para gestionar primero las más críticas.                                                                                    | Escenario 1: Asignar prioridad<br>Dado que veo una incidencia<br>Cuando selecciono un nivel de prioridad<br>Entonces se guarda la prioridad asignada.<br><br>Escenario 2: Cambiar prioridad<br>Dado que una incidencia ya tiene prioridad<br>Cuando la modifico<br>Entonces se actualiza correctamente.<br><br>Escenario 3: Visualización de prioridades<br>Dado que filtro por prioridad<br>Cuando selecciono “Alta”<br>Entonces solo se muestran incidencias de alta prioridad.                                                                              | E03                       | Personal Municipal |
| US06                 | Actualizar estado de incidencia       | Como personal municipal, quiero actualizar el estado de una incidencia para reflejar su progreso.                                                                                               | Escenario 1: Cambio exitoso<br>Dado que selecciono una incidencia<br>Cuando cambio su estado<br>Entonces el sistema guarda, muestra y notifica el nuevo estado al ciudadano.<br><br>Escenario 2: Validación de flujo<br>Dado que una incidencia ya está cerrada<br>Cuando intento reabrirla<br>Entonces el sistema solicita confirmación.<br><br>Escenario 3: Estado sin cambios<br>Dado que ingreso a una incidencia<br>Cuando no realizo ninguna modificación<br>Entonces el sistema mantiene el estado anterior.                                            | E03 / E04                 | Personal Municipal |
| US07                 | Enviar comentario sobre incidencia    | Como personal municipal, quiero enviar comentarios en las incidencias para comunicar acciones tomadas.                                                                                          | Escenario 1: Comentario exitoso<br>Dado que abro una incidencia<br>Cuando escribo un comentario<br>Entonces se guarda y asocia al caso.<br><br>Escenario 2: Comentario vacío<br>Dado que no escribo nada<br>Cuando intento enviar<br>Entonces el sistema muestra advertencia.<br><br>Escenario 3: Visualización de comentarios previos<br>Dado que accedo a una incidencia<br>Cuando reviso los comentarios<br>Entonces veo el historial completo.                                                                                                             | E04                       | Personal Municipal |
| US08                 | Exportar reporte de incidencias       | Como personal municipal, quiero exportar reportes en CSV para análisis y gestión.                                                                                                               | Escenario 1: Exportación exitosa<br>Dado que hay incidencias<br>Cuando selecciono el botón de exportar<br>Entonces se genera archivo descargable en formato CSV.<br><br>Escenario 2: Sin incidencias<br>Dado que no hay registros<br>Cuando intento exportar<br>Entonces se muestra mensaje de “No hay incidencias que exportar”.<br><br>Escenario 3: Botón siempre visible<br>Dado que estoy en la sección de reportes<br>Cuando accedo a la página<br>Entonces el botón de exportar está disponible.                                                         | E05                       | Personal Municipal |
| US09                 | Ver detalles de la municipalidad      | Como personal municipal, quiero ver los detalles de la municipalidad para acceder a información institucional centralizada.                                                                     | Escenario 1: Información visible<br>Dado que accedo a la sección municipalidad<br>Cuando entro<br>Entonces veo datos de la municipalidad.<br><br>Escenario 2: Datos actualizados<br>Dado que hay cambios<br>Cuando accedo<br>Entonces se muestran datos vigentes.<br><br>Escenario 3: Error de carga<br>Dado que ocurre un fallo<br>Cuando accedo<br>Entonces el sistema muestra mensaje “Error al cargar información”.                                                                                                                                        | E06                       | Personal Municipal |
| US10                 | Ver detalle de incidencia             | Como personal municipal, quiero ver información detallada de cada incidencia para analizar su contexto.                                                                                         | Escenario 1: Visualización completa<br>Dado que selecciono una incidencia<br>Cuando la abro<br>Entonces veo tipo, fecha, ubicación, prioridad y comentarios.<br><br>Escenario 2: Historial visible<br>Dado que reviso incidencia<br>Cuando entro<br>Entonces veo historial de cambios y estados.<br><br>Escenario 1: Filtrado por tipo<br>Dado que la incidencia fue eliminada<br>Cuando intento verla<br>Entonces el sistema muestra “Incidencia no disponible”.                                                                                              | E03                       | Personal Municipal |
| US11                 | Dashboard geoespacial municipal       | Como personal municipal, quiero visualizar incidencias en mapas de calor interactivos para priorizar intervenciones basadas en concentración espacial.                                          | Escenario 1: Visualización de hotspots<br>Dado que existen múltiples reportes<br>Cuando accedo al dashboard<br>Entonces veo mapas de calor actualizados.<br><br>Escenario 2: Filtrado temporal<br>Dado que aplico filtros de búsqueda<br>Cuando selecciono rango de fechas<br>Entonces el mapa se actualiza con esos datos.<br><br>Escenario 3: Sin incidencias en zona<br>Dado que no hay incidencias<br>Cuando consulto una zona<br>Entonces el sistema muestra “No hay incidencias en esta zona”.                                                           | E05                       | Personal Municipal |
| US12                 | Cerrar sesión como personal municipal | Como personal municipal, quiero cerrar mi sesión de manera segura desde la aplicación,<br>para proteger la información de la plataforma y garantizar que nadie más acceda con mis credenciales. | Escenario 1: Cierre de sesión exitoso<br>Dado que tengo mi sesión iniciada en la plataforma<br>Cuando selecciono la opción “Cerrar sesión”<br>Entonces el sistema me redirige al login y mi sesión queda invalidada.<br><br>Escenario 2: Intento de acceso luego del cierre<br>Dado que ya cerré sesión<br>Cuando intento acceder a un módulo de gestión<br>Entonces el sistema me solicita ingresar mis credenciales nuevamente.                                                                                                                              | E01                       | Personal Municipal |
| US13                 | Registro de ciudadanos                | Como ciudadano, quiero registrarme en la aplicación para poder reportar incidencias.                                                                                                            | Escenario 1: Registro exitoso<br>Dado que ingreso datos válidos<br>Cuando confirmo<br>Entonces se crea mi cuenta.<br><br>Escenario 2: Datos faltantes<br>Dado que omito campos<br>Cuando envío el formulario<br>Entonces el sistema muestra advertencia.<br><br>Escenario 3: Usuario ya existente<br>Dado que ingreso un correo ya registrado<br>Cuando confirmo<br>Entonces el sistema rechaza el registro.                                                                                                                                                   | E01                       |     Cuidadano      |
| US14                 | Inicio de sesión ciudadano            | Como ciudadano, quiero iniciar sesión para acceder a mis reportes y perfil.                                                                                                                     | Escenario 1: Inicio exitoso<br>Dado que ingreso datos correctos<br>Cuando confirmo<br>Entonces accedo al menú principal.<br><br>Escenario 2: Error de credenciales<br>Dado que ingreso mal los datos<br>Cuando intento entrar<br>Entonces el sistema muestra error.<br><br>Escenario 3: Campos obligatorios<br><br>Dado que intento iniciar sesión<br><br>Cuando dejo campos vacíos<br><br>Entonces el sistema me solicita completar la información.                                                                                                           | E01                       |     Cuidadano      |
| US15                 | Ver perfil                            | Como ciudadano, quiero ver mi perfil para revisar mis datos y configuraciones.                                                                                                                  | Escenario 1: Visualización exitosa<br>Dado que accedo a mi perfil<br>Cuando entro<br>Entonces veo mis datos registrados.<br><br>Escenario 2: Perfil incompleto<br>Dado que faltan datos<br>Cuando accedo<br>Entonces el sistema muestra campos vacíos con opción de completar.<br><br>Escenario 3: Error de carga<br>Dado que hay un fallo<br>Cuando accedo<br>Entonces se muestra mensaje de error.                                                                                                                                                           | E01                       |     Cuidadano      |
| US16                 | Reporte de incidencia con foto        | Como ciudadano, quiero reportar una incidencia urbana adjuntando fotografía y ubicación automática para documentar el problema de forma completa.                                               | Escenario 1: Captura exitosa<br>Dado que detecto una incidencia<br>Cuando tomo una foto<br>Entonces el sistema guarda la foto y coordenadas.<br><br>Escenario 2: Rechazo de captura<br>Dado que no deseo usar la foto<br>Cuando tomo otra<br>Entonces el sistema me permite reemplazarla.<br><br>Escenario 3: Reporte incompleto<br>Dado que no adjunto foto<br>Cuando confirmo<br>Entonces el incidente no se envía.                                                                                                                                          | E02                       |     Cuidadano      |
| US17                 | Ver resumen de incidencias reportadas | Como ciudadano, quiero ver un resumen de mis incidencias para dar seguimiento general.                                                                                                          | Escenario 1: Resumen visible<br>Dado que tengo incidencias<br>Cuando accedo al resumen<br>Entonces veo listado con fecha, tipo y estado.<br><br>Escenario 2: Sin incidencias<br>Dado que no he reportado<br>Cuando accedo<br>Entonces el sistema muestra “Aún no tienes incidencias”.<br><br>Escenario 3: Actualización automática<br>Dado que reporto una nueva incidencia<br>Cuando refresco<br>Entonces el listado se actualiza.                                                                                                                            | E02                       |     Cuidadano      |
| US18                 | Ver detalle de incidencia             | Como ciudadano, quiero ver los detalles de una incidencia que reporté para conocer su estado actual.                                                                                            | Escenario 1: Información completa<br>Dado que selecciono una incidencia<br>Cuando entro<br>Entonces veo todos los datos y estado.<br><br>Escenario 2: Incidencia cerrada<br>Dado que reviso una incidencia cerrada<br>Cuando entro<br>Entonces veo estado “Cerrado” con fecha de resolución.<br><br>Escenario 3: Incidencia no encontrada<br>Dado que selecciono un reporte eliminado<br>Cuando accedo<br>Entonces el sistema muestra “No disponible”.                                                                                                         | E02                       |     Cuidadano      |
| US19                 | Filtrar incidencias (App)             | Como ciudadano, quiero filtrar mis incidencias por tipo o zona para encontrar casos específicos.                                                                                                | Escenario 1: Filtrado por tipo<br>Dado que selecciono “tipo”<br>Cuando aplico el filtro<br>Entonces veo solo esas incidencias.<br><br>Escenario 2: Filtrado por zona<br>Dado que selecciono “zona”<br>Cuando aplico<br>Entonces aparecen incidencias en esa ubicación.<br><br>Escenario 3: Sin coincidencias<br>Dado que aplico filtros<br>Cuando no hay resultados<br>Entonces el sistema muestra mensaje vacío.                                                                                                                                              | E02                       |     Cuidadano      |
| US20                 | Ver estado de incidencias             | Como ciudadano, quiero ver el estado de mis reportes para mantenerme informado.                                                                                                                 | Escenario 1: Estado actualizado<br>Dado que el personal municipal cambia el estado<br>Cuando entro<br>Entonces veo el nuevo estado.<br><br>Escenario 2: Estado histórico<br>Dado que accedo a una incidencia<br>Cuando reviso<br>Entonces veo historial de cambios.<br><br>Escenario 3: Sin actualizaciones<br>Dado que la incidencia aún no se procesa<br>Cuando entro<br>Entonces aparece “En espera de revisión”.                                                                                                                                           | E02 / E04                 |     Cuidadano      |
| US21                 | Seguimiento de estado                 | Como ciudadano, quiero ver el progreso de mi reporte para mantenerme informado sobre su resolución.                                                                                             | Escenario 1: Visualización de cambio de estado<br>Dado que mi reporte cambia<br>Cuando la municipalidad actualiza<br>Entonces veo el nuevo estado.<br><br>Escenario 2: Transparencia del proceso<br>Dado que consulto historial<br>Cuando abro un reporte<br>Entonces veo historial completo de cambios.<br><br>Escenario 3: Estado sin cambios<br>Dado que consulto un reporte<br>Cuando aún no ha sido actualizado<br>Entonces el sistema muestra el estado actual sin modificaciones.                                                                       | E02 / E04                 |     Cuidadano      |
| US22                 | Ver comentarios sobre incidencia      | Como ciudadano, quiero ver los comentarios de la municipalidad en mis incidencias para entender el seguimiento dado.                                                                            | Escenario 1: Comentarios visibles<br>Dado que la municipalidad envía un comentario<br>Cuando accedo a la incidencia<br>Entonces veo el texto.<br><br>Escenario 2: Sin comentarios<br>Dado que aún no hay<br>Cuando accedo<br>Entonces el sistema muestra “Sin comentarios aún”.<br><br>Escenario 3: Historial de comentarios<br>Dado que reviso una incidencia<br>Cuando accedo<br>Entonces veo todos los comentarios previos.                                                                                                                                 | E04                       |     Cuidadano      |
| US23                 | Ver otrosincidentes reportados        | Como ciudadano, quiero ver incidencias de otros vecinos para estar informado de lo que ocurre en mi comunidad.                                                                                  | Escenario 1: Listado disponible<br>Dado que otros ciudadanos reportaron<br>Cuando accedo<br>Entonces veo listado general.<br><br>Escenario 2: Filtro de zona<br>Dado que quiero ver incidencias de mi zona<br>Cuando aplico filtro<br>Entonces se muestran solo esas.<br><br>Escenario 3: Sin incidencias públicas<br>Dado que no hay reportes<br>Cuando accedo<br>Entonces aparece “No hay incidencias disponibles”.                                                                                                                                          | E02                       |     Cuidadano      |
| US24                 | Cerrar sesión como ciudadano          | Como ciudadano, quiero cerrar mi sesión de manera segura desde la aplicación,<br>para proteger mis datos personales y evitar accesos no autorizados.                                            | Escenario 1: Cierre de sesión exitoso<br>Dado que estoy autenticado en la aplicación<br>Cuando selecciono la opción “Cerrar sesión”<br>Entonces la aplicación me redirige a la pantalla de inicio de sesión y mi sesión se invalida.<br><br>Escenario 2: Intento de acción tras cerrar sesión<br>Dado que he cerrado mi sesión<br>Cuando intento acceder a una funcionalidad restringida<br>Entonces se me solicita iniciar sesión nuevamente.                                                                                                                 | E01                       |     Cuidadano      |
| US25                 | Ver Home                              | Como visitante, quiero ver la página de inicio para conocer la propuesta de la plataforma.                                                                                                      | Escenario 1: Acceso exitoso<br>Dado que entro al sitio<br>Cuando cargo la página<br>Entonces se muestran secciones principales.<br><br>Escenario 2: Contenido incompleto<br>Dado que falta información<br>Cuando accedo<br>Entonces se indica “En actualización”.<br><br>Escenario 3: Navegación rápida<br>Dado que quiero ir a otra sección<br>Cuando hago clic en un menú<br>Entonces el sistema me redirige correctamente.                                                                                                                                  | E05                       |      Landing       |
| US26                 | Sobre nosotros                        | Como visitante, quiero ver la sección “Sobre nosotros” para conocer la misión y visión de la plataforma.                                                                                        | Escenario 1: Información disponible<br>Dado que accedo a la sección<br>Cuando hago scroll<br>Entonces veo misión, visión y valores.<br><br>Escenario 2: En construcción<br>Dado que aún no se publica contenido<br>Cuando accedo<br>Entonces la página muestra “En construcción”.<br><br>Escenario 3: Navegación correcta<br>Dado que quiero volver al home<br>Cuando hago clic en el logo<br>Entonces regreso al inicio.                                                                                                                                      | E05                       |      Landing       |
| US27                 | Ver testimonios                       | Como visitante, quiero ver testimonios de ciudadanos y municipalidades para confiar en la plataforma.                                                                                           | Escenario 1: Testimonios disponibles<br>Dado que hay testimonios cargados<br>Cuando accedo<br>Entonces los veo con nombre y foto.<br><br>Escenario 2: Sin testimonios<br>Dado que aún no hay<br>Cuando accedo<br>Entonces aparece un mensaje vacío.<br><br>Escenario 3: Cambio dinámico<br>Dado que hay varios testimonios<br>Cuando navego<br>Entonces se alternan en carrusel.                                                                                                                                                                               | E05                       |      Landing       |
| US28                 | Beneficios municipalidad              | Como visitante, quiero ver los beneficios de la plataforma para la municipalidad para evaluar su utilidad.                                                                                      | Escenario 1: Información visible<br>Dado que accedo<br>Cuando entro a la sección<br>Entonces veo lista de beneficios claros.<br><br>Escenario 2: Detalle incompleto<br>Dado que falta contenido<br>Cuando entro<br>Entonces se muestra “Información pendiente”.<br><br>Escenario 3: Navegación sencilla<br>Dado que quiero ir a contacto<br>Cuando hago clic en el botón<br>Entonces soy redirigido.                                                                                                                                                           | E05                       |      Landing       |
| US29                 | Beneficios ciudadano                  | Como visitante, quiero ver los beneficios de la plataforma para ciudadanos para saber cómo me ayuda.                                                                                            | Escenario 1: Información visible<br>Dado que accedo<br>Cuando entro a la sección<br>Entonces veo lista de beneficios claros.<br><br>Escenario 2: Sin información<br>Dado que aún no está publicada<br>Cuando entro<br>Entonces se muestra aviso de actualización.<br><br>Escenario 3: Navegación sencilla<br>Dado que quiero ir a registrarme<br>Cuando hago clic en el botón<br>Entonces soy redirigido al registro.                                                                                                                                          | E05                       |      Landing       |

### Technical User Stories

Las technical user stories abordan necesidades internas del sistema relacionadas con la arquitectura, la infraestructura y aspectos técnicos que no siempre son visibles para el usuario final, pero que resultan esenciales para la estabilidad, escalabilidad y seguridad de la plataforma.

| Epic / User Story ID | Título                                                  | Descripción                                                                                                                                                                                                                                          | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Relacionado con (Epic ID) | Segmento  |
| -------------------- | ------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- | :-------: |
| TS01                 | Infraestructura Azure                                   | Como equipo de desarrollo, quiero desplegar la plataforma exclusivamente en servicios de Microsoft Azure para cumplir con las políticas de infraestructura municipal establecidas y garantizar soporte técnico oficial.                              | Escenario 1: Despliegue exitoso<br>Dado que el equipo configura la infraestructura en Azure<br>Cuando se completa el despliegue<br>Entonces la plataforma queda operativa en los servicios de Azure.<br><br>Escenario 2: Cumplimiento de políticas<br>Dado que la infraestructura debe ajustarse a las normativas municipales<br>Cuando se valida el entorno<br>Entonces se confirma que cumple con los lineamientos oficiales.                                                                                                                                                                                                                                                                                                                                                                                                                                  | E01                       | Technical |
| TS02                 | Base de Datos Escalable                                 | Como equipo técnico, quiero configurar una base de datos en Azure SQL Database con escalabilidad automática para manejar el crecimiento de información de incidencias y usuarios.                                                                    | Escenario 1: Configuración inicial exitosa<br>Dado que se crea la base de datos en Azure SQL<br>Cuando se conecta con la plataforma<br>Entonces queda lista para almacenar información.<br><br>Escenario 2: Escalabilidad automática<br>Dado que aumenta la cantidad de registros<br>Cuando la carga supera el umbral<br>Entonces la base de datos escala automáticamente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | E01                       | Technical |
| TS03                 | Seguridad y Autenticación                               | Como equipo técnico, quiero integrar Azure Active Directory para el inicio de sesión del personal municipal y asegurar accesos con protocolos modernos de seguridad.                                                                                 | Escenario 1: Integración con Azure AD<br>Dado que el personal municipal inicia sesión<br>Cuando ingresa credenciales válidas<br>Entonces se valida contra Azure AD y accede al sistema.<br><br>Escenario 2: Acceso denegado<br>Dado que el personal ingresa credenciales inválidas<br>Cuando intenta autenticarse<br>Entonces el sistema rechaza el acceso.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | E01                       | Technical |
| TS04                 | Georreferenciación                                      | Como equipo de desarrollo, quiero integrar servicios de mapas de Azure Maps para mostrar incidencias en un tablero geoespacial.                                                                                                                      | Escenario 1: Visualización en mapa<br>Dado que existen incidencias registradas<br>Cuando se abre el tablero<br>Entonces se muestran las incidencias en el mapa con su ubicación georreferenciada.<br><br>Escenario 2: Filtro por estado<br>Dado que el usuario necesita gestionar incidencias<br>Cuando selecciona un estado en el tablero<br>Entonces solo se muestran las incidencias correspondientes.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | E05                       | Technical |
| TS05                 | API RESTful                                             | Como equipo técnico, quiero implementar una API RESTful para que las aplicaciones móviles y web puedan conectarse con el backend de forma estándar.                                                                                                  | Escenario 1: Respuesta exitosa<br>Dado que una aplicación solicita información<br>Cuando envía una petición válida a la API<br>Entonces recibe los datos en formato JSON.<br><br>Escenario 2: Manejo de errores<br>Dado que una aplicación envía una petición incorrecta<br>Cuando la API procesa la solicitud<br>Entonces responde con un código de error y mensaje adecuado.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | E01                       | Technical |
| TS06                 | Disponibilidad y Escalabilidad                          | Como equipo técnico, quiero configurar balanceadores de carga en Azure para asegurar que la aplicación esté disponible y escale automáticamente según la demanda.                                                                                    | Escenario 1: Balanceo exitoso<br>Dado que hay múltiples solicitudes de usuarios<br>Cuando se dirigen al sistema<br>Entonces el balanceador distribuye la carga de forma eficiente.<br><br>Escenario 2: Escalamiento automático<br>Dado que la demanda del sistema aumenta<br>Cuando se supera la capacidad de instancias actuales<br>Entonces se crean nuevas instancias automáticamente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | E01                       | Technical |
| TS07                 | Implementar notificaciones en tiempo real con WebSocket | Como developer, quiero implementar la comunicación en tiempo real mediante WebSocket para las notificaciones,<br>para que los badges de incidentes y los mensajes emergentes se actualicen automáticamente sin necesidad de refrescar la aplicación. | Escenario 1: Envío de notificación en tiempo real<br>Dado que se registra un nuevo incidente<br>Cuando el servidor lo transmite mediante WebSocket<br>Entonces el cliente recibe la notificación automáticamente.<br><br>Escenario 2: Actualización de badge en tiempo real<br>Dado que hay un incidente nuevo<br>Cuando el cliente recibe el evento<br>Entonces el badge del ícono de notificaciones incrementa su valor.<br><br>Escenario 3: Reinicio de badge al abrir notificaciones<br>Dado que el badge muestra incidentes pendientes<br>Cuando el usuario abre el módulo de notificaciones<br>Entonces el badge se reinicia a 0.<br><br>Escenario 4: Visualización del toast de incidente<br>Dado que el cliente recibe una notificación de incidente<br>Cuando el sistema procesa el evento<br>Entonces se muestra un toast con un resumen del incidente | E01                       | Technical |

## 3.3. Impact Mapping

El Impact Mapping es una técnica de planificación estratégica que conecta los objetivos de negocio con las funcionalidades del producto. La estructura sigue el formato: ¿Por qué? (objetivo) → ¿Quién? (actores) → ¿Cómo? (impactos) → ¿Qué? (funcionalidades), permitiendo priorizar el desarrollo basado en el valor real que aporta cada funcionalidad.

![impact_mapping](images/requirements_specification/Impact-mapping.drawio.png)

El impact mapping busca mejorar la gestión municipal mediante una plataforma digital que facilite el reporte y seguimiento de incidencias urbanas.

- **Ciudadanos**: podrán reportar problemas de forma rápida, dar seguimiento al estado de sus incidencias y mantenerse informados sobre lo que ocurre en su comunidad.

- **Personal municipal**: contará con herramientas para gestionar y priorizar incidencias, visualizar su distribución, mantener comunicación con los ciudadanos y tomar decisiones basadas en información consolidada.

Este enfoque garantiza que tanto ciudadanos como personal municipal trabajen de manera colaborativa, optimizando la atención de incidencias y fortaleciendo la transparencia en la gestión urbana.

## 3.4. Product Backlog

### User Stories Product Backlog

<table border="1">
  <thead>
    <tr>
      <th>Orden</th>
      <th>HU ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>E01_US13</td>
      <td>Registro de ciudadanos</td>
      <td>COMO ciudadano QUIERO registrarme en la aplicación PARA poder reportar incidencias.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>2</td>
      <td>E01_US14</td>
      <td>Inicio de sesión ciudadano</td>
      <td>COMO ciudadano QUIERO iniciar sesión PARA acceder a mis reportes y perfil.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>3</td>
      <td>E01_US01</td>
      <td>Registro de personal municipales</td>
      <td>COMO personal municipal QUIERO registrarme en la plataforma PARA acceder a las funcionalidades de gestión.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>4</td>
      <td>E01_US02</td>
      <td>Inicio de sesión personal municipal</td>
      <td>COMO personal municipal QUIERO iniciar sesión PARA acceder al panel de gestión de incidencias.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>E02_US16</td>
      <td>Reporte de incidencia con foto</td>
      <td>COMO ciudadano QUIERO reportar una incidencia urbana adjuntando fotografía y ubicación automática PARA documentar el problema de forma completa.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>6</td>
      <td>E02_US17</td>
      <td>Ver resumen de incidencias reportadas</td>
      <td>COMO ciudadano QUIERO ver un resumen de mis incidencias PARA dar seguimiento general.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>7</td>
      <td>E02_US21</td>
      <td>Seguimiento de estado</td>
      <td>COMO ciudadano QUIERO ver el progreso de mi reporte PARA mantenerme informado sobre su resolución.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>8</td>
      <td>E02_US18</td>
      <td>Ver detalle de incidencia</td>
      <td>COMO ciudadano QUIERO ver los detalles de una incidencia que reporté PARA conocer su estado actual.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>E02_US20</td>
      <td>Ver estado de incidencias</td>
      <td>COMO ciudadano QUIERO ver el estado de mis reportes PARA mantenerme informado.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>10</td>
      <td>E03_US11</td>
      <td>Dashboard geoespacial municipal</td>
      <td>COMO personal municipal QUIERO visualizar incidencias en mapas de calor interactivos PARA priorizar intervenciones basadas en concentración espacial.</td>
      <td>13</td>
    </tr>
    <tr>
      <td>11</td>
      <td>E03_US03</td>
      <td>Ver total de incidencias</td>
      <td>COMO personal municipal QUIERO ver el número total de incidencias registradas PARA monitorear el volumen general.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>12</td>
      <td>E03_US04</td>
      <td>Filtrar incidencias</td>
      <td>COMO personal municipal QUIERO filtrar incidencias por tipo, zona, prioridad o fecha PARA gestionarlas de forma más eficiente.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>13</td>
      <td>E03_US05</td>
      <td>Priorizar incidencias</td>
      <td>COMO personal municipal QUIERO asignar prioridad a las incidencias PARA gestionar primero las más críticas.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>14</td>
      <td>E03_US06</td>
      <td>Actualizar estado de incidencia</td>
      <td>COMO personal municipal QUIERO actualizar el estado de una incidencia PARA reflejar su progreso.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>15</td>
      <td>E03_US10</td>
      <td>Ver detalle de incidencia</td>
      <td>COMO personal municipal QUIERO ver información detallada de cada incidencia PARA analizar su contexto.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>16</td>
      <td>E04_US07</td>
      <td>Enviar comentario sobre incidencia</td>
      <td>COMO personal municipal QUIERO enviar comentarios en las incidencias PARA comunicar acciones tomadas.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>17</td>
      <td>E04_US22</td>
      <td>Ver comentarios sobre incidencia</td>
      <td>COMO ciudadano QUIERO ver los comentarios de la municipalidad en mis incidencias PARA entender el seguimiento dado.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>18</td>
      <td>E02_US19</td>
      <td>Filtrar incidencias (App)</td>
      <td>COMO ciudadano QUIERO filtrar mis incidencias por tipo o zona PARA encontrar casos específicos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>19</td>
      <td>E02_US23</td>
      <td>Ver otros incidentes reportados</td>
      <td>COMO ciudadano QUIERO ver incidencias de otros vecinos PARA estar informado de lo que ocurre en mi comunidad.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>20</td>
      <td>E01_US15</td>
      <td>Ver perfil</td>
      <td>COMO ciudadano QUIERO ver mi perfil PARA revisar mis datos y configuraciones.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>21</td>
      <td>E05_US08</td>
      <td>Exportar reporte de incidencias</td>
      <td>COMO personal municipal QUIERO exportar reportes en CSV PARA análisis y gestión.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>22</td>
      <td>E06_US09</td>
      <td>Ver detalles de la municipalidad</td>
      <td>COMO personal municipal QUIERO ver los detalles de la municipalidad PARA acceder a información institucional centralizada.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>23</td>
      <td>E07_US25</td>
      <td>Ver Home</td>
      <td>COMO visitante QUIERO ver la página de inicio PARA conocer la propuesta de la plataforma.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>24</td>
      <td>E07_US26</td>
      <td>Sobre nosotros</td>
      <td>COMO visitante QUIERO ver la sección "Sobre nosotros" PARA conocer la misión y visión de la plataforma.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>25</td>
      <td>E07_US27</td>
      <td>Ver testimonios</td>
      <td>COMO visitante QUIERO ver testimonios de ciudadanos y municipalidades PARA confiar en la plataforma.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>26</td>
      <td>E07_US28</td>
      <td>Beneficios municipalidad</td>
      <td>COMO visitante QUIERO ver los beneficios de la plataforma para la municipalidad PARA evaluar su utilidad.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>27</td>
      <td>E07_US29</td>
      <td>Beneficios ciudadano</td>
      <td>COMO visitante QUIERO ver los beneficios de la plataforma para ciudadanos PARA saber cómo me ayuda.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>28</td>
      <td>E01_US12</td>
      <td>Cerrar sesión como personal municipal</td>
      <td>COMO personal municipal QUIERO cerrar mi sesión de manera segura desde la aplicación PARA proteger la información de la plataforma.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>29</td>
      <td>E01_US24</td>
      <td>Cerrar sesión como ciudadano</td>
      <td>COMO ciudadano QUIERO cerrar mi sesión de manera segura desde la aplicación PARA proteger mis datos personales.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

### Technical Stories Product Backlog

<table border="1">
  <thead>
    <tr>
      <th>Orden</th>
      <th>TS ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>TS01</td>
      <td>Infraestructura Azure</td>
      <td>COMO equipo de desarrollo QUIERO desplegar la plataforma exclusivamente en servicios de Microsoft Azure PARA cumplir con las políticas de infraestructura municipal establecidas.</td>
      <td>13</td>
    </tr>
    <tr>
      <td>2</td>
      <td>TS02</td>
      <td>Base de Datos Escalable</td>
      <td>COMO equipo técnico QUIERO configurar una base de datos en Azure SQL Database con escalabilidad automática PARA manejar el crecimiento de información de incidencias y usuarios.</td>
      <td>13</td>
    </tr>
    <tr>
      <td>3</td>
      <td>TS05</td>
      <td>API RESTful</td>
      <td>COMO equipo técnico QUIERO implementar una API RESTful PARA que las aplicaciones móviles y web puedan conectarse con el backend de forma estándar.</td>
      <td>13</td>
    </tr>
    <tr>
      <td>4</td>
      <td>TS03</td>
      <td>Seguridad y Autenticación</td>
      <td>COMO equipo técnico QUIERO integrar Azure Active Directory para el inicio de sesión del personal municipal PARA asegurar accesos con protocolos modernos de seguridad.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>5</td>
      <td>TS04</td>
      <td>Georreferenciación</td>
      <td>COMO equipo de desarrollo QUIERO integrar servicios de mapas de Azure Maps PARA mostrar incidencias en un tablero geoespacial.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>6</td>
      <td>TS06</td>
      <td>Disponibilidad y Escalabilidad</td>
      <td>COMO equipo técnico QUIERO configurar balanceadores de carga en Azure PARA asegurar que la aplicación esté disponible y escale automáticamente según la demanda.</td>
      <td>13</td>
    </tr>
    <tr>
      <td>7</td>
      <td>TS07</td>
      <td>Notificaciones en tiempo real con WebSocket</td>
      <td>COMO developer QUIERO implementar la comunicación en tiempo real mediante WebSocket PARA que los badges de incidentes y los mensajes emergentes se actualicen automáticamente.</td>
      <td>8</td>
    </tr>
  </tbody>
</table>

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

El propósito del diseño arquitectónico de LimaUrban es establecer una base técnica sólida que permita la transformación digital de la gestión de incidencias urbanas, integrando tecnologías emergentes como análisis geoespacial e inteligencia artificial para crear un ecosistema eficiente de reporte y gestión ciudadana.

**Problemática:**

Los ciudadanos limeños enfrentan desafíos significativos para reportar incidencias urbanas debido a la falta de canales de comunicación eficientes y transparentes con las autoridades municipales. Los sistemas tradicionales de reporte son lentos, poco intuitivos y no ofrecen seguimiento en tiempo real, lo que genera desconfianza ciudadana y retrasos en la resolución de problemas urbanos críticos como baches, semáforos dañados, acumulación de basura y vandalismo.

**Objetivos principales del diseño:**

1. **Automatización inteligente del procesamiento de incidencias:** Mediante sistemas de visión por computadora con modelos YOLO entrenados localmente con un dataset mínimo de 2,000 imágenes, la arquitectura debe procesar automáticamente reportes ciudadanos con fotografías, clasificando y validando únicamente dos categorías prioritarias (baches y basura) en tiempo real para reducir el trabajo manual y mejorar la precisión. Esta limitación estratégica responde a los requisitos prácticos de entrenamiento de modelos YOLO que requieren mínimo 1,000 imágenes por categoría para alcanzar precisión operativa.

2. **Escalabilidad y disponibilidad urbana:** La solución debe soportar la carga de 10 mil habitantes, garantizando disponibilidad del 99.5% y capacidad de procesar miles de reportes simultáneos durante emergencias urbanas o eventos críticos.

3. **Integración geoespacial avanzada:** La arquitectura debe facilitar la generación de mapas de calor dinámicos que permitan a las autoridades municipales identificar la zona con más reportes de incidencias.

4. **Experiencia ciudadana simplificada:** Diseñar interfaces que reduzcan el tiempo de reporte a menos de 40 segundos, incluyendo captura fotográfica, geolocalización automática y confirmación de recepción.

5. **Interoperabilidad institucional:** Establecer APIs estandarizadas que permitan la integración con sistemas municipales existentes, facilitando el intercambio de datos y la adopción por parte de diferentes distritos de Lima Metropolitana.

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)

Las siguientes User Stories representan las funcionalidades primarias que tienen mayor impacto arquitectónico y son críticas para el éxito de la plataforma:

| Epic/User Story ID | Título                          | Descripción                                                                                                                                            | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Relacionado con (Epic ID) |
| ------------------ | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------- |
| US01               | Reporte de Incidencia con Foto  | Como ciudadano, quiero reportar una incidencia urbana adjuntando una fotografía y ubicación automática para documentar el problema de forma completa.  | **Escenario 1:** Captura exitosa<br>Dado que el ciudadano detecta una incidencia<br>Cuando abre la app y toma una fotografía<br>Entonces el sistema captura automáticamente las coordenadas GPS y permite categorizar la incidencia y la guarda en su base de datos<br><br>**Escenario 2:** Rechazo de captura<br>Dado que el usuario quiere descartar la foto<br>Cuando el usuario le da al icono de cámara otra vez<br>Entonces el sistema le permite otro intento de foto y se queda esperando la confirmación de la foto                                                                                                                                                                                                                                 | EP01                      |
| US02               | Clasificación Automática con IA | Como sistema, quiero clasificar automáticamente las incidencias reportadas mediante IA para reducir el trabajo manual de revisión.                     | **Escenario 1:** Clasificación precisa de categorías prioritarias<br>Dado que se recibe una imagen de incidencia<br>Cuando el modelo YOLO procesa la imagen<br>Entonces debe clasificar correctamente el tipo de incidencia (bache o basura) con precisión ≥80%<br><br>**Escenario 2:** Clasificación manual para casos ambiguos<br>Dado que el modelo YOLO no puede clasificar una imagen<br>Cuando la confianza es <70%<br>Entonces el sistema envía la incidencia para revisión manual por personal municipal<br><br>**Escenario 3:** Requisitos de entrenamiento<br>Dado que necesito entrenar el modelo YOLO<br>Cuando preparo el dataset<br>Entonces debe contener mínimo 1,000 imágenes por categoría (baches y basura) capturadas en contexto limeño | EP02                      |
| US03               | Dashboard Geoespacial Municipal | Como personal municipal, quiero visualizar incidencias en mapas de calor interactivos para priorizar intervenciones basadas en concentración espacial. | **Escenario 1:** Visualización de hotspots<br>Dado que existen múltiples reportes en el sistema<br>Cuando accedo al dashboard de "Mapa de Incidencias"<br>Entonces debo ver mapas de calor actualizados que muestren concentración de incidencias por zona<br><br>**Escenario 2:** Filtrado temporal<br>Dado que estoy en el dashboard<br>Cuando aplico filtros de búsqueda<br>Entonces debo ver la información específica que quiero<br><br>**Escenario 3:** No hay información sobre una zona<br>Dado que no hay incidencias en una zona<br>Cuando el usuario quiere ver la zona<br>Entonces el sistema le muestra un mensaje de "No hay incidencias en esta zona"                                                                                         | EP03                      |
| US04               | Seguimiento de Estado           | Como ciudadano, quiero ver el progreso de mi reporte para mantenerme informado sobre su resolución.                                                    | **Escenario 1:** Visualización de cambio de estado<br>Dado que mi reporte cambia de estado<br>Cuando el personal municipal actualiza el progreso<br>Entonces debo ver el nuevo estado de mi reporte<br><br>**Escenario 2:** Transparencia del proceso<br>Dado que accedo a mi historial de reportes<br>Cuando consulto un reporte específico<br>Entonces debo ver el historial completo de estados y acciones realizadas                                                                                                                                                                                                                                                                                                                                     | EP01                      |

#### 4.1.2.2. Quality Attribute Scenarios

En esta sección se incluye la especificación de la primera versión de los escenarios de atributos de calidad que tienen mayor impacto en la arquitectura de la solución LimaUrban. Los escenarios identificados están directamente relacionados con las funcionalidades primarias del sistema y abordan aspectos críticos como disponibilidad, rendimiento, precisión de IA, escalabilidad y usabilidad. Estos escenarios sirven como input fundamental para el proceso de diseño arquitectónico y permiten validar que la solución cumple con los estándares de calidad requeridos para la gestión urbana inteligente.

##### Escenario QA-01: Disponibilidad durante Alta Concurrencia

| **Campo**               | **Descripción**                                                                                                                                                                                    |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Escenario**           | Ciudadano reporta incidencia urbana durante hora pico matutina cuando miles de usuarios acceden simultáneamente al sistema para registrar problemas de infraestructura en toda Lima Metropolitana. |
| **ID**                  | QA-01                                                                                                                                                                                              |
| **User Stories**        | US01 – Reporte de Incidencia con Foto                                                                                                                                                              |
| **Atributo de Calidad** | Disponibilidad                                                                                                                                                                                     |
| **Fuente de Estímulo**  | Ciudadano limeño                                                                                                                                                                                   |
| **Estímulo**            | Usuario intenta reportar una incidencia durante hora pico (8:00-9:00 AM) cuando el sistema experimenta alta concurrencia de 5,000+ usuarios simultáneos.                                           |
| **Artefacto**           | Aplicación móvil Flutter y backend Django                                                                                                                                                          |
| **Entorno**             | Operación normal con alta concurrencia durante horarios de mayor movilidad urbana en Lima                                                                                                          |
| **Respuesta**           | El sistema procesa el reporte, captura la geolocalización, almacena la fotografía y confirma la recepción sin interrupciones.                                                                      |
| **Medida de respuesta** | El sistema debe mantener 99.5% de disponibilidad mensual y procesar reportes en menos de 3 segundos durante picos de carga.                                                                        |

##### Escenario QA-02: Precisión del Modelo de IA

| **Campo**               | **Descripción**                                                                                                                                                                     |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Escenario**           | El modelo de inteligencia artificial debe clasificar automáticamente imágenes de incidencias urbanas enviadas por ciudadanos para reducir el trabajo manual del personal municipal. |
| **ID**                  | QA-02                                                                                                                                                                               |
| **User Stories**        | US02 – Clasificación Automática con IA                                                                                                                                              |
| **Atributo de Calidad** | Precisión                                                                                                                                                                           |
| **Fuente de Estímulo**  | Sistema de visión por computadora                                                                                                                                                   |
| **Estímulo**            | El modelo YOLO recibe una imagen de bache o acumulación de basura en condiciones variables de iluminación y calidad fotográfica típicas de reportes ciudadanos.                     |
| **Artefacto**           | Modelo YOLO entrenado con dataset local de Lima (mínimo 2,000 imágenes: 1,000 baches + 1,000 basura)                                                                                |
| **Entorno**             | Dataset de validación con 1,000 imágenes representativas de incidencias urbanas reales en Lima Metropolitana                                                                        |
| **Respuesta**           | El sistema clasifica correctamente el tipo de incidencia y asigna un nivel de confianza a la predicción.                                                                            |
| **Medida de respuesta** | El modelo debe alcanzar precisión ≥80% en condiciones reales y procesar cada imagen en menos de 2 segundos.                                                                         |

##### Escenario QA-03: Escalabilidad durante Emergencias

| **Campo**               | **Descripción**                                                                                                                                                                |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Escenario**           | Durante una emergencia urbana (inundación, terremoto), miles de ciudadanos reportan incidencias simultáneamente, sobrecargando el sistema con un volumen excepcional de datos. |
| **ID**                  | QA-03                                                                                                                                                                          |
| **User Stories**        | US01 – Reporte de Incidencia con Foto, US02 – Clasificación Automática con IA                                                                                                  |
| **Atributo de Calidad** | Escalabilidad                                                                                                                                                                  |
| **Fuente de Estímulo**  | Múltiples usuarios durante emergencia                                                                                                                                          |
| **Estímulo**            | 10,000 ciudadanos intentan reportar incidencias simultáneamente durante una emergencia urbana que afecta múltiples distritos de Lima.                                          |
| **Artefacto**           | Arquitectura modular monolítica desplegada en Azure                                                                                                                            |
| **Entorno**             | Pico de carga excepcional durante emergencia que supera 10x el tráfico normal                                                                                                  |
| **Respuesta**           | El sistema mantiene operatividad sin degradación significativa, procesando todos los reportes y mantiendo tiempos de respuesta aceptables.                                     |
| **Medida de respuesta** | Capacidad de procesar 10,000+ reportes por hora manteniendo latencia <5 segundos sin pérdida de datos.                                                                         |

##### Escenario QA-04: Rendimiento del Dashboard Geoespacial

| **Campo**               | **Descripción**                                                                                                                                                                     |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Escenario**           | Personal municipal necesita visualizar patrones geoespaciales de incidencias para planificar intervenciones preventivas y optimizar asignación de recursos de mantenimiento urbano. |
| **ID**                  | QA-04                                                                                                                                                                               |
| **User Stories**        | US03 – Dashboard Geoespacial Municipal                                                                                                                                              |
| **Atributo de Calidad** | Rendimiento                                                                                                                                                                         |
| **Fuente de Estímulo**  | Personal municipal autorizado                                                                                                                                                       |
| **Estímulo**            | Funcionario municipal accede al dashboard para generar mapas de calor con filtros temporales sobre una base de datos con 500+ reportes acumulados.                                  |
| **Artefacto**           | Dashboard Angular integrado con sistema de análisis geoespacial PostGIS                                                                                                             |
| **Entorno**             | Sesión de trabajo normal con base de datos poblada con reportes históricos de múltiples distritos                                                                                   |
| **Respuesta**           | El sistema genera visualizaciones interactivas de mapas de calor, aplicando filtros y mostrando concentraciones de incidencias por zona geográfica.                                 |
| **Medida de respuesta** | Visualización completa de mapas de calor en menos de 2 segundos, incluyendo aplicación de filtros temporales y geográficos.                                                         |

##### Escenario QA-05: Usabilidad para Usuarios Nuevos

| **Campo**               | **Descripción**                                                                                                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Escenario**           | Un ciudadano sin experiencia técnica previa utiliza la aplicación móvil por primera vez para reportar una incidencia urbana, requiriendo una experiencia intuitiva y eficiente. |
| **ID**                  | QA-05                                                                                                                                                                           |
| **User Stories**        | US01 – Reporte de Incidencia con Foto                                                                                                                                           |
| **Atributo de Calidad** | Usabilidad                                                                                                                                                                      |
| **Fuente de Estímulo**  | Ciudadano nuevo                                                                                                                                                                 |
| **Estímulo**            | Usuario sin experiencia previa descarga la aplicación e intenta completar su primer reporte de incidencia urbana siguiendo la interfaz intuitiva.                               |
| **Artefacto**           | Interfaz móvil Flutter                                                                                                                                                          |
| **Entorno**             | Usuario real sin capacitación previa, utilizando smartphone estándar en condiciones normales de uso                                                                             |
| **Respuesta**           | El usuario completa exitosamente el reporte incluyendo fotografía, geolocalización y categorización sin asistencia externa.                                                     |
| **Medida de respuesta** | 90% de usuarios nuevos deben completar su primer reporte en menos de 40 segundos sin errores críticos.                                                                          |

##### Escenario QA-06: Interoperabilidad con Sistemas Municipales

| **Campo**               | **Descripción**                                                                                                                                                            |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Escenario**           | Sistemas municipales existentes requieren integración con la plataforma para intercambiar datos de incidencias y mantener sincronización con procesos operativos actuales. |
| **ID**                  | QA-06                                                                                                                                                                      |
| **User Stories**        | US03 – Dashboard Geoespacial Municipal                                                                                                                                     |
| **Atributo de Calidad** | Interoperabilidad                                                                                                                                                          |
| **Fuente de Estímulo**  | Sistema municipal externo                                                                                                                                                  |
| **Estímulo**            | Sistema SIG municipal solicita datos de incidencias vía API para integración con flujos de trabajo de mantenimiento existentes.                                            |
| **Artefacto**           | API pública de la plataforma LimaUrban                                                                                                                                     |
| **Entorno**             | Integración con sistemas municipales heredados que utilizan estándares GIS convencionales                                                                                  |
| **Respuesta**           | La API entrega datos estructurados en formatos estándar compatibles con sistemas municipales existentes.                                                                   |
| **Medida de respuesta** | 100% compatibilidad con estándares GeoJSON y OGC, con tiempo de respuesta API <1 segundo para consultas estándar.                                                          |

#### 4.1.2.3. Constraints

Las siguientes restricciones técnicas han sido establecidas por el cliente y son no negociables para la elaboración de la solución:

| Technical Story ID | Título                          | Descripción                                                                                                                                                                                                                                     | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Relacionado con (Epic ID) |
| ------------------ | ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- | --- | ---- |
| TS01               | Infraestructura Azure           | Como equipo de desarrollo, quiero desplegar la plataforma exclusivamente en servicios de Microsoft Azure para cumplir con las políticas de infraestructura municipal establecidas y garantizar soporte técnico oficial.                         | **Escenario 1:** Despliegue exitoso en Azure<br>**Dado que** necesitamos cumplir políticas municipales de infraestructura cloud<br>**Cuando** desplegamos el backend y base de datos<br>**Entonces** debe utilizarse Azure App Service para el backend y Azure Database para almacenamiento<br>**Y** todos los servicios deben estar dentro del ecosistema Azure<br><br>**Escenario 2:** Validación de servicios<br>**Dado que** la infraestructura debe ser exclusivamente Azure<br>**Cuando** se configura el entorno de producción<br>**Entonces** no debe utilizarse ningún servicio de AWS, Google Cloud u otros proveedores<br>**Y** debe documentarse la justificación de cada servicio Azure seleccionado                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Todos los Epics           |
| TS02               | Frontend Web Angular            | Como desarrollador frontend, quiero implementar el dashboard municipal en Angular para mantener coherencia con los sistemas municipales existentes y aprovechar la expertise del equipo en este framework.                                      | **Escenario 1:** Compatibilidad con sistemas municipales<br>**Dado que** existen sistemas Angular en la municipalidad<br>**Cuando** desarrollo el dashboard municipal<br>**Entonces** debe usar Angular 15+ con TypeScript<br>**Y** debe ser compatible con navegadores Chrome, Firefox y Edge<br><br>**Escenario 2:** Integración API exitosa<br>**Dado que** necesito conectar con el backend Django<br>**Cuando** implemento las funcionalidades del dashboard<br>**Entonces** debe integrarse correctamente con APIs REST<br>**Y** debe manejar errores de conectividad de forma elegante<br><br>**Escenario 3:** Fallo de compatibilidad<br>**Dado que** un navegador no soporta las funcionalidades<br>**Cuando** un usuario accede desde Internet Explorer<br>**Entonces** debe mostrar un mensaje de navegador no compatible<br>**Y** sugerir navegadores alternativos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | EP03                      |
| TS03               | Backend Python Django           | Como arquitecto de software, quiero utilizar Python Django como framework principal del backend para aprovechar la integración nativa con el ecosistema de machine learning y YOLO, optimizando el rendimiento de la clasificación de imágenes. | **Escenario 1:** Implementación del framework<br>**Dado que** necesito integración nativa con YOLO y OpenCV<br>**Cuando** desarrollo los servicios del backend<br>**Entonces** debe usar Django 4.0+ con Python 3.9+<br>**Y** debe implementar arquitectura REST con Django REST Framework<br><br>**Escenario 2:** Integración con base de datos<br>**Dado que** necesito persistencia de datos<br>**Cuando** configuro la conexión a la base de datos<br>**Entonces** debe integrarse correctamente con Azure Database (PostgreSQL)<br>**Y** debe registrar errores apropiadamente para monitoring<br><br>**Escenario 3:** Integración ML nativa<br>**Dado que** requiero procesamiento de imágenes con YOLO<br>**Cuando** proceso un reporte con imagen<br>**Entonces** debe ejecutar el modelo YOLO directamente sin servicios externos<br>**Y** debe procesar la imagen en menos de 2 segundos .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Todos los Epics           |
| TS04               | Arquitectura Modular Monolítica | Como arquitecto de sistema, quiero implementar una arquitectura modular dentro de un monolito para simplificar el despliegue inicial manteniendo la flexibilidad para futuras migraciones a microservicios.                                     | **Escenario 1:** Separación modular exitosa<br>**Dado que** necesito flexibilidad futura para migración<br>**Cuando** diseño la arquitectura del sistema<br>**Entonces** debe tener módulos bien definidos por dominio (Reportes, IA, Gestión, Analytics)<br>**Y** cada módulo debe tener interfaces claras sin dependencias circulares<br><br>**Escenario 2:** Preparación para migración<br>**Dado que** puede requerirse migración a microservicios en el futuro<br>**Cuando** implemento los módulos<br>**Entonces** cada módulo debe poder separarse sin refactoring mayor<br><br>**Escenario 3:** Violación de modularidad<br>**Dado que** un desarrollador intenta crear dependencia directa entre módulos<br>**Cuando** compila el código<br>**Entonces** deben activarse reglas de análisis estático que detecten violaciones<br>**Y** debe fallar el build hasta corregir la violación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Todos los Epics           |
| TS05               | Aplicación Móvil Flutter        | Como desarrollador móvil, quiero desarrollar la aplicación ciudadana en Flutter para soportar Android e iOS con una sola base de código y reducir costos de desarrollo y mantenimiento.                                                         | **Escenario 1:** Multiplataforma exitosa<br>**Dado que** necesito soporte para Android e iOS<br>**Cuando** desarrollo la aplicación móvil<br>**Entonces** debe usar Flutter 3.0+ con Dart 3.0+<br>**Y** debe funcionar nativamente en ambas plataformas sin código específico<br><br>**Escenario 2:** Acceso a funcionalidades nativas<br>**Dado que** requiero acceso a cámara y GPS<br>**Cuando** implemento el reporte de incidencias<br>**Entonces** debe acceder correctamente a hardware del dispositivo<br>**Y** debe solicitar permisos de forma clara al usuario<br><br>**Escenario 3:** Fallo de permisos<br>**Dado que** el usuario deniega permisos de cámara<br>**Cuando** intenta reportar una incidencia<br>**Entonces** debe mostrar mensaje explicativo sobre la necesidad del permiso<br>**Y** debe ofrecer alternativa de cargar foto desde galería<br><br>**Escenario 4:** Dispositivo incompatible<br>**Dado que** un dispositivo muy antiguo no soporta la versión mínima<br>**Cuando** intenta instalar la aplicación<br>**Entonces** debe mostrar mensaje de compatibilidad en la tienda<br>**Y** debe sugerir actualización del sistema operativo                                                                                                                                                                                                                                                                                           | EP01                      |
| TS06               | Visión Artificial YOLO          | Como especialista en IA, quiero utilizar específicamente modelos YOLO para la clasificación de incidencias mediante visión artificial para garantizar precisión y rendimiento óptimos en el contexto urbano limeño.                             | **Escenario 1:** Implementación del modelo especializado<br>**Dado que** necesito clasificación automática de incidencias<br>**Cuando** proceso imágenes de reportes ciudadanos<br>**Entonces** debe usar YOLOv8 o superior entrenado con dataset local de Lima (mínimo 2,000 imágenes)<br>**Y** debe procesar imágenes en menos de 2 segundos<br>**Y** debe clasificar únicamente baches y basura<br><br>**Escenario 2:** Precisión para categorías específicas<br>**Dado que** el modelo debe ser confiable para uso municipal<br>**Cuando** clasifica 500 imágenes de validación por categoría<br>**Entonces** debe alcanzar precisión mínima del 80% para baches y basura<br>**Y** debe asignar nivel de confianza a cada clasificación<br><br>**Escenario 3:** Requisitos de dataset de entrenamiento<br>**Dado que** requiero entrenar el modelo con datos locales<br>**Cuando** preparo el dataset<br>**Entonces** debe incluir mínimo 1,000 imágenes de baches en calles de Lima<br>**Y** debe incluir mínimo 1,000 imágenes de basura en espacios públicos limeños<br>**Y** debe incluir variaciones de iluminación, ángulos y condiciones meteorológicas<br><br>**Escenario 4:** Clasificación con baja confianza<br>**Dado que** recibo una imagen ambigua o de mala calidad<br>**Cuando** el modelo procesa la imagen<br>**Entonces** debe asignar confianza <70% si no puede clasificar claramente<br>**Y** debe marcar el reporte para revisión manual | EP02                      |     | EP02 |

## 4.1.2.4. Architectural Drivers Backlog

Resultado del proceso de Quality Attribute Workshop, priorizando drivers por importancia para stakeholders e impacto en complejidad técnica arquitectónica:

| **Driver ID** | **Título**                      | **Descripción**                                                                                                                                       | **Importancia** | **Complejidad** |
| ------------- | ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | --------------- |
| **QA01**      | Precisión de Clasificación IA   | Garantizar ≥80% de precisión en la clasificación automática de incidencias mediante visión por computadora YOLO para reducir trabajo manual municipal | High            | High            |
| **QA02**      | Escalabilidad Urbana            | Soportar 10,000+ reportes simultáneos durante emergencias manteniendo rendimiento <5s para toda la población objetivo                                 | High            | High            |
| **C01**       | Restricción Tecnológica Azure   | Desplegar exclusivamente en Azure cumpliendo políticas municipales de infraestructura cloud                                                           | High            | High            |
| **FD01**      | Reporte con Geolocalización     | Permitir captura automática de ubicación GPS y fotografía para documentación completa de incidencias urbanas                                          | High            | Medium          |
| **FD02**      | Dashboard Geoespacial           | Proporcionar mapas de calor interactivos y análisis temporal para priorización municipal de intervenciones                                            | High            | High            |
| **QA03**      | Disponibilidad Ciudadana        | Mantener 99.5% disponibilidad mensual para garantizar acceso continuo de ciudadanos a la plataforma de reportes                                       | High            | Medium          |
| **C02**       | Arquitectura Modular Monolítica | Implementar estructura modular dentro de monolito para balance entre simplicidad de despliegue y flexibilidad                                         | High            | Medium          |
| **QA04**      | Experiencia de Usuario Móvil    | Lograr que 90% de usuarios nuevos completen reportes en <40 segundos con interfaz Flutter intuitiva                                                   | High            | Medium          |
| **C03**       | Backend Django                  | Utilizar Python Django como framework obligatorio para backend aprovechando la integración nativa con YOLO y el ecosistema de ML                      | Medium          | Medium          |
| **QA05**      | Seguridad de Datos              | Proteger información ciudadana y prevenir reportes maliciosos mediante autenticación y validación robusta                                             | Medium          | High            |
| **C04**       | Frontend Angular Municipal      | Desarrollar dashboard web en Angular para coherencia con sistemas municipales existentes                                                              | Medium          | Low             |
| **QA06**      | Interoperabilidad Municipal     | Facilitar integración con sistemas SIG municipales existentes mediante APIs estándar y formatos compatibles                                           | Medium          | Medium          |

El formato ahora es mucho más legible, con tablas claras que separan cada escenario y un backlog de drivers bien estructurado para facilitar la lectura y comprensión.

### 4.1.3. Architectural Design Decisions

Durante el proceso del Quality Attribute Workshop, se evaluaron múltiples patrones arquitectónicos para cada driver crítico. A continuación se presenta el análisis de las decisiones más importantes:

#### Candidate Pattern Evaluation Matrix

| Driver ID | Título de Driver              | Patrón 1: Modular Monolith                                                               | Patrón 2: Microservicios                                                                  | Patrón 3: Layered Architecture                                                                    |
| --------- | ----------------------------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| **QA01**  | Precisión de Clasificación IA | **Pro:** Menor latencia para procesamiento IA<br>**Con:** Acoplamiento con otros módulos | **Pro:** Servicio IA independiente<br>**Con:** Latencia de red adicional                  | **Pro:** Separación clara de responsabilidades<br>**Con:** Complejidad en procesamiento asíncrono |
| **QA02**  | Escalabilidad Urbana          | **Pro:** Escalado vertical simple<br>**Con:** Limitaciones en escalado horizontal        | **Pro:** Escalado granular por servicio<br>**Con:** Complejidad de orquestación           | **Pro:** Escalado por capas<br>**Con:** Cuellos de botella en capas inferiores                    |
| **C01**   | Restricción Azure             | **Pro:** Despliegue simple en App Service<br>**Con:** Menos flexibilidad de servicios    | **Pro:** Aprovecha servicios Azure nativos<br>**Con:** Mayor complejidad de configuración | **Pro:** Compatible con servicios Azure<br>**Con:** Subutilización de capacidades cloud           |

**Decisión Final:** Se seleccionó **Modular Monolith** como patrón principal debido a:

- Cumplimiento con restricción de simplicidad de despliegue inicial
- Menor complejidad operacional para el equipo municipal
- Facilidad de migración futura a microservicios cuando sea necesario
- Mejor rendimiento para procesamiento de IA al evitar latencia de red

#### Evaluación de Patrones para Procesamiento de IA

| Aspecto           | YOLO Embebido         | YOLO como Servicio | YOLO Híbrido |
| ----------------- | --------------------- | ------------------ | ------------ |
| **Latencia**      | <100ms                | 200-500ms          | 100-200ms    |
| **Escalabilidad** | Limitada por hardware | Alta               | Media        |
| **Mantenimiento** | Complejo              | Simple             | Medio        |
| **Costo**         | Bajo                  | Alto               | Medio        |

**Decisión:** YOLO Embebido dentro del monolito para minimizar latencia y cumplir con requisitos de precisión.

### 4.1.4. Quality Attribute Scenario Refinements

Al finalizar el Quality Attribute Workshop, se refinaron los escenarios más críticos para guiar la implementación:

| Scenario # | Scenario                                                                        | Business Goals                                                                            | Relevant Quality Attributes                | Stimulus Source                      | Environment                                                           | Artifact                                                        | Response                                                            | Response Measure                                              | Questions                                                                    | Issues                                                               |
| ---------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------ | ------------------------------------ | --------------------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| **1**      | Ciudadano reporta bache durante hora pico matutina con alta concurrencia        | Mantener confianza ciudadana asegurando disponibilidad durante períodos de máxima demanda | Disponibilidad, Rendimiento, Escalabilidad | Usuario móvil en Lima Metropolitana  | Hora pico con 5,000+ usuarios concurrentes                            | Aplicación Flutter y backend Spring Boot                        | Sistema procesa reporte, clasifica imagen YOLO y confirma recepción | 99% de reportes procesados en < 3 segundos durante horas pico | ¿Cómo garantizar rendimiento cuando tráfico aumenta 10x durante emergencias? | Implementar cache distribuido y optimización de consultas            |
| **2**      | Modelo IA clasifica imagen de bache en condiciones de iluminación nocturna      | Reducir trabajo manual de validación municipal manteniendo alta precisión                 | Precisión, Confiabilidad                   | Aplicación móvil con cámara estándar | Dataset validación con 500 imágenes de baches representativas de Lima | Modelo YOLO entrenado con datos locales (mínimo 2,000 imágenes) | Clasificación como "Bache" con nivel de confianza                   | 80% de precisión en clasificación con confianza ≥70%          | ¿Cómo mantener precisión con imágenes de calidad variable?                   | Entrenar modelo con dataset aumentado incluyendo variaciones típicas |
| **3**      | Personal municipal visualiza patrones deterioro vial para planificación semanal | Optimizar asignación de recursos mediante análisis geoespacial predictivo                 | Usabilidad, Rendimiento, Interoperabilidad | Personal municipal autorizado        | Dashboard Angular con 500+ reportes acumulados                        | Sistema análisis geoespacial con PostGIS                        | Mapa de calor interactivo con concentraciones de incidencias viales | Visualización completa en <2 segundos con filtros temporales  | ¿Cómo integrar insights con sistemas municipales existentes?                 | Diseñar APIs compatibles con estándares SIG municipales              |

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

### 4.2.2. Candidate Context Discovery

### 4.2.3. Domain Message Flows Modeling

### 4.2.4. Bounded Context Canvases

### 4.2.5. Context Mapping

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

### 4.3.2. Software Architecture Context Level Diagrams

### 4.3.3. Software Architecture Container Level Diagrams

### 4.3.4. Software Architecture Deployment Diagrams
