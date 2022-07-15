# Laboratorio Curso de DevSecOps / SRE - Escuela de Verano
**Objetivo:** Crear un proyecto de desarrollo de software cuyo producto final sea una implementación del caso de estudio Linker.

# Cadena de Valor
Con el objetivo de facilitar el desarrollo de las actividades de nuevos miembros del equipo, se configuró este flujo que permite al desarrollador realizar despliegues seguros en ambientes operativos.

1. Sitio colaborativo con la inclusión de herramientas aplicables par ael desarrollo y operación de los servicios.
2. Equipos autoorganizados capaces de desarrollar nuevas características de producto.
3. Estandarización de herramientas y extensiones para que todos los miembros cuenten con las dependencias necesarias.
4. El nuevo miembro del equipo deberá clonar el repositorio apra tener la última versión del código y trabajar en el flujo.

# ¿Qué hay en el repositorio?
- **Circleci:** Aqui se encuentra la configuración para realizar pruebas de código.
- **CodeQL:** Aquí se encuentra la configuración del motor de análisis de código desarrollado por GitHub para automatizar los controles de seguridad.
- **Carpeta /pages:** Aquí se encuentran los archivos js.
- **Carpeta /prisma:** Aquí se encuentra la configuración del ORM.
- **Carpeta /style:** Aqui se ebcuentran los archivos css.

# ¿Cómo trabajamos en equipo? 

Nuestro equipo es pequeño, lo cual nos facilita la forma de trabajar bajo el marco de trabajo "SCRUM", sobre el cual definimos los siguientes artefactos, eventos y participantes: 

**Product Owner:** Área de negocio encargada de la solicitud o requerimiento de mejoramiento, mantenimiento u operación de la aplicación.
**Team Development:**
- Scrum Master: MR 
- Team: MJ - JSP - JU - SA

**Eventos:**
- Daily: Todos los días de 8:00 am a 8:15 am.
- Spring planning: Cada 15 días, Martes de 8:00 am a 9:00 am.
- Spring review: Cada 15 días, Viernes o lunes (según si aplican festivos) de 4:00 pm a 5:00 pm.
- Spring retrospective: Cada 20 días, los miércoles de 2:00pm a 4:00pm (cada sesión será liderada por un integrante del equipo y al finalizar la sesión se escoge quién dirige la próxima sesión).

**Artefactos:**
- Product Backlog: Consolidado de tareas, incluyedo requerimientos e incidentes/eventos de la operación para mantener el sistema en línea.
- Issues: Las tareas se verán reflejadas y asignadas en esta pestaña del repositorio en github, la cual creará una rama para esta tarea con el propósito de no alterar la rama de producción (rama main / trunk) y permitirnos aplicar las técnicas de *Pair Programming*  y *Peer Reviews*.
- Spring Backlog: Según la críticidad de las tareas, se dará prioridad cada 15 días a ciertas tareas que pueden afectar la operación, y se establecerá un tiempo "muerto" para la demanda de incidentes/eventos en la operación.
- Tablero Kanban: Consolidado de tareas del spring con el estado de ejecución (to-do, doing & done).

**Eventualidades / Situaciones fuera de lo común en la operación:**
- Ante eventos inesperados en el desarrollo de la operación, el integrante del equipo que requiere apoyo para la gestión de su actividad dado que es crítica para la operación, todos los integrantes del equipo involucraremos nuestros esfuerzos para cumplir y apoyar en la finalización de dicha tarea. Esta actividad debe ser reportada desde los daily, con el objetivo de dar oportunidad en seguimiento y cumplimiento.
- De acuerdo con la composición del grupo, el dueño del requerimiento es nuestro Product Owner, sin embargo, el equipo de desarrollo (team development) es único dueño y responsable del cumplimiento y operación de la aplicación encargada. Teniendo en cuenta esto, es importante que la colaboración (principio lean) haga parte del apoyo entre el equipo.
- Adicional como equipo ágil y especialista en la aplicación de negocio, el equipo se basará en los principio de lean para el desarrollo del trabajo, en el cual, uno de los más importantes es la autogestión, debido que siendo el equipo responsable cada integrante puede escoger las tareas para su operación, sin dejar de lado el cumplimiento y la responsabilidad de hacer la gestión correspondiente para finalizarla.
- El producto estará en la etapa de "Terminado", una vez se hayan ejecutado todas las pruebas correspondientes y se obtenga por parte de las áreas responsables las aprobaciones o visto bueno por parte del área de negocio o área solicitante (product owner). Si dichas aprobaciones se encuentran demoradas, el equipo puede continuar gestionando y/o solucionando las tareas de interrupción que surgen en la operación. 

# Recursos
Los recursos utilizados para el desarrollo de linker fueron
NEXT.js
PRISMA
REACT
PostgreSQL

# Links utiles
**GitHub repository**
https://github.com/DevSecOps2022I/devSecOps-Linker-1.git

**Heroku App**
https://proyecto2022i.herokuapp.com/

# Linker App

[![CircleCI](https://circleci.com/gh/DevSecOps2022I/devSecOps-Linker-1.svg?style=svg)](https://circleci.com/gh/DevSecOps2022I/devSecOps-Linker-1/tree/main)

Linker app is a url shortener based on  [Linker](https://github.com/ecampidoglio/Linker) by [@ecampidoglio](https://github.com/ecampidoglio)

# Herramientas minimas para trabajar

Visual Studio Code,
Heroku,
CircleCI.

# Licencia
Licencia de funcionamiento GNU

# Miembros
Developer Team 
* Juan Camilo Posso - JCP
* Maria Jose Torres - MJT
* Miguel Rojas - MR
* Johannes Uribe - JU
Product Owner 
* Sebastian Aguado - SA

