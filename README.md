<div align="justify">

<div align="center">
<img src="https://github.com/samugd17/gitlab/blob/feature_2/img/gitlab-logo-100.png">
</div>

## ÍNDICE
- [¿Qué son las herramientas CI/DC?](#¿qué-son-las-herramientas-ci/cd?)

- [¿Qué es y dentro de que grupo de las herramientas CI/DC está?](#¿qué-es-y-dentro-de-que-grupo-de-las-herramientas-ci/cd-está?)

- [¿Qué ofrece?](#¿qué-ofrece?)

- [Plan de precios.](#plan-de-precios)

- [Ejemplo de integración con repositorios de código](#ejemplo-de-integración-con-repositorios-de-código)

- [Ejemplo de documentación de proyectos](#ejemplo-de-documentación-de-proyectos)

- [Otras herramientas con las que se integra](#otras-herramientas-con-las-que-se-integra)

- [Comparativa con otras herramientas](#comparativa-con-otras-herramientas)

- [¿Por qué escoger la herramienta frente a otras?](#¿por-qué-escoger-la-herramienta-frente-a-otras?)

- [Referencias](#referencias)

## ¿Qué son las herramientas CI/CD?

Las herramientas CI/CD hacen referencia a un método para distribuir las aplicaciones a los clientes con frecuencia, mediante el uso de la automatización en las etapas del desarrollo de las aplicaciones. Los principales conceptos que se le atribuyen son la Integración Continua (CI) y la Distribución e Implementación Continua (CD). 

### Integración Continua (IC)
La Integración Continua es una práctica de desarrollo que requiere que los desarrolladores integren su código en un repositorio compartido con el resto de sus compañeros, varias veces al día.

Cada rama, es verificada automáticamente por un compilador, permitiendo al equipo de programadores detectar los diferentes problemas que puedan existir y solucionarlos lo antes posible, asegurando de esta forma que la rama "main", siempre se encuentre lo más limpia y viable posible para su posterior desarrollo.


__Objetivo:__ Entregar un código mejor, más rápido y fácil de mantener.

### Distribución e Implementación Continua (CD)
La Distribución e Implementación Continua es la etapa que procede a la Integración Continua. Sin embargo, dentro de ésta, se pueden diferenciar dos conceptos en los que, aunque a menudo se confundan y se usen indistintivamente, ya que ambos se refieren a la automatización de las etapas posteriores del proceso, se usan por separado para explicar hasta dónde llega la automatización.

- __Distribución Continua:__
La Distribución Continua es la etapa donde los cambios realizados con éxito en la Integración Continua son cargados en un repositorio, para que luego el equipo de operaciones pueda implementarlos en un entorno de producción en vivo.

    - **Objetivo:** Mejorar la poca supervisión y comunicación entre los equipos comerciales y de desarrollo y garantizar que la implementación del código nuevo se lleve a cabo con el mínimo esfuerzo.

- __Implementación Continua:__ 
La Implementación Continua hace referencia al lanzamiento automático de los cambios que implementa el desarrollador desde el repositorio hasta la producción, para ponerlos a disposición de los clientes. 

    - **Objetivo:** No sobrecargar a los equipos de operaciones con procesos manuales que retrasan la distribución de las aplicaciones y aprovechar los beneficios de la distribución continua automatizando la siguiente etapa del proceso.
<div align="center">
<img src="https://github.com/samugd17/gitlab/blob/feature_2/img/gitlab_workflow.png">
</div>

## ¿Qué es y dentro de que grupo de las herramientas CI/CD está?
Gitlab es un servicio web de forja, control de versiones y ___DevOps*___ basado en Git y publicado bajo una licencia de código abierto. Es una herramienta que se encuentra en el grupo de herramientas CI/CD, lo que significa que ofrece características tanto de Integración Continua (CI) como de Despliegue Continuo (CD). Permite automatizar y orquestar el proceso de desarrollo, pruebas y despliegue de software, brindando una solución integral para respaldar las prácticas ágiles de desarrollo y las metodologías de DevOps.

Fue escrito en 2011 por los programadores ucranianos Dmitriy Zaporozhets y Valery Sizov en el lenguaje de programación Ruby3​ y Go, inicialmente como una solución de gestión de código fuente para colaborar con su equipo en el desarrollo de software. Luego evolucionó a una solución integrada que cubre el ciclo de vida del desarrollo de software, y luego a todo el ciclo de vida de DevOps. La arquitectura tecnológica actual incluye Go, Ruby on Rails y Vue.js.

La compañía, GitLab Inc. cuenta con un equipo de 1309 miembros. Es usado por organizaciones como la NASA, el CERN, IBM o Sony.

- - - 
___*DevOps:__ Es una metodología que busca integrar el desarrollo de software (Dev) con las operaciones de tecnología de la información(Ops). Estas operaciones se refieren a las actividades y procesos relacionados con la gestión y el mantenimiento de los sistemas de tecnología de la información en una organización: Gestión de infraestructura, soporte técnico, monitoreo y seguridad..._

:sound: <a href="https://youtu.be/l5705U8s_nQ?t=369">Profundiza un poco más en Gitlab CI/CD</a>

## ¿Qué ofrece?

Gitlab es una de las herramientas más reconocidas por ofrecer prácticamente todos los servicios que podemos necesitar durante el desarrollo:

- Administración, creación y conexión de repositorios con diferentes aplicaciones e integración con ellas, ofreciendo un ambiente y una plataforma en la que se pueden realizar las diferentes etapas de su ciclo de vida de desarrollo de software (SDLC) y DevOps. 

- Preparar y ser host de nuestro propio servidor con infraestructura personalizada de forma gratuita lo cual además permite trabajar en ellos sin necesidad de estar conectado

- Alojamiento de wikis

- Sistema de seguimiento y detección de errores

- Posibilidad de crear ramas y pull requests directamente dedicadas a los issues

- Registro en docker gratuito por repositorio

- Pîpelines para mas de un proyecto

- Registro de contenedores (no es necesario el de docker)


## Plan de precios

![<>](1_img/precios.png)

- Versión Gratuita: Adecuada para equipos pequeños. 

    - Incluye funciones básicas de gestión de proyectos como la gestión de problemas y ramas y la integración continua, además de funciones básicas de seguridad y soporte comunitario en línea. 

    - 5gb de espacio de almacenamiento, 10gb de transferencia mensual, 400 unidades de computación mensuales y un límite de 5 usuarios por espacio.

- Versión Premium: Adecuado para proyectos de medianos a grandes en entornos empresariales. 

    - Añade funciones avanzadas como la gestión de cartera de proyectos, mejor personalización de procesos e integración con herramientas de terceros. 

    - Mejores funciones de seguridad y cumplimiento tales como la autenticación avanzada, protección de ramas, escaneo de vulnerabilidades, amenazas y análisis de código. Además de soporte técnico especializado. 

    - 50gb de espacio de almacenamiento, 100gb de transferencia mensual y 10.000 unidades de computación mensuales.
    
- Versión Ultimate: Adecuado para entornos empresariales de gran escala. 

    - Incluye funciones adicionales, como la gestión de operaciones y de valor empresarial, permisos y roles más complejos, herramientas avanzadas de cumplimiento, como auditorías, informes y flujos de trabajo personalizados, además de nuevas integraciones empresariales.

    - Adiciones de seguridad y cumplimiento como el escaneo de dependencias y contenedores la gestión de identidades y accesos, políticas de seguridad y registros de auditoría. Además de soporte técnico prioritario y asistencia en línea y presencial. 

    - 250gb de espacio de almacenamiento, 500gb de transferencia mensual y 50.000 unidades de computación mensuales.

### Extras

![<>](1_img/addons.png)

### Comparativa

![<>](1_img/comparativa_precios.png)

## Ejemplo de integración con repositorios de código

## Ejemplo de documentación de proyectos

## Otras herramientas con las que se integra

Gitlab posee una gran librería de herramientas para su integración, aquí podemos ver algunas de las que conocemos y henos usado:

![<>](1_img/integraciones.png)

### Ejemplo: Jira

![<>](1_img/Jira%20Software%402x-blue.png)

La integración con jira se puede hacer desde dos perspectivas

    - Integración del sistema de Issues:
        - Crear y ver iissues de Jira directamente desde gitlab
        - Referenciar issues de Jira por id desde commits y merge requests de GitLab
        - Crear issues de jira para vulnerabilidades

    - Integración del panel de desarrollos
        - Incluidas las ramas referenciales, commits y merge requests.
        - Seguimiento de tiempo en un issue
        - uso de commit para pasar o cerrar un issue

## Comparativa con otras herramientas



 <!-- One of the worst parts of Jenkins for me is also it's main draw... There are plugins for EVERYTHING but they are not guaranteed to be maintained. I know that there is potentially the ability to pay for a commercial Cloudbees support potentially but relying on plugins that may or may not be supported and that may or may not break on an update makes Jenkins a pain sometimes. Also the other issue that I have with it is that so much is done through the UI. I am moving more and more towards tools where everything is in revision control because it is easier to maintain and easier to branch when needed.

In terms of a long term strategy I recommend the following:

    Pick tools that have been around for a while and avoid switching tools just because it is trendy. I know tools like GitLab and Artifactory are going to be around for a while.

    Avoid putting too much logic in the CI/CD tool. Rely on scripts where possible because this will make it easier to change CI/CD tools if necessary.

    CI/CD tools with native container support are the way to go because containers are here to stay. You want your build environments containerized and versioned.

    Automate everything. Minimize manual tasks as much as humanely possible. The more manual steps you have the more that can go wrong.

    Embrace everything as code and store it all in revision control. You do not want hand crafted servers or things built by hand in the software tool chain. Ideally in my mind everything should be able to be rebuilt from code from the ground up in an automated way. This is important if something foundational to the tech stack needs to change.

    Have your own artifact managers that proxy the public artifact managers. IE don't use NPM or Docker Hub directly. Use something like Artifactory or Nexus to proxy it. -->


## ¿Por qué escoger la herramienta frente a otras?

## Referencias
https://www.redhat.com/es/topics/devops/what-is-ci-cd

https://docs.gitlab.com/

</div>


<!-- 
Importar directamente de otra herramienta

Autoriza automaticamente con github si tienes la sesion iniciada 

División de proyectos por grupo

Importar proyectos propios, colaborativos y de organización

División por grupos o usuario

Crear etiquetas de proyecto

Import issue and pull request events

For example, opened or closed, renamed, and labeled or unlabeled. Time required to import these events depends on how many issues or pull requests your project has.
Use alternative comments import method

The default method can skip some comments in large projects because of limitations of the GitHub API.
Import Markdown attachments (links)

Import Markdown attachments (links) from repository comments, release posts, issue descriptions, and pull request descriptions. These can include images, text, or binary attachments. If not imported, links in Markdown to attachments break after you remove the attachments from GitHub. 

Prueba Commit
-->

