<div align="justify">

<div align="center">
<img src="https://github.com/samugd17/gitlab/blob/feature_2/img/gitlab-logo-100.png">
</div>

## ÍNDICE
- [¿Qué son las herramientas CI/DC?](#qué-son-las-herramientas-cicd)

- [¿Qué es y dentro de que grupo de las herramientas CI/DC está?](#qué-es-y-dentro-de-que-grupo-de-las-herramientas-cicd-está)

- [¿Qué ofrece?](#qué-ofrece)

- [Plan de precios.](#plan-de-precios)

- [Ejemplo de integración con repositorios de código](#ejemplo-de-integración-con-repositorios-de-código)

- [Ejemplo de documentación de proyectos](#ejemplo-de-documentación-de-proyectos)

- [Otras herramientas con las que se integra](#otras-herramientas-con-las-que-se-integra)

- [Comparativa con otras herramientas](#comparativa-con-otras-herramientas)

- [¿Por qué escoger la herramienta frente a otras?](#por-qué-escoger-la-herramienta-frente-a-otras)

- [Referencias](#referencias)

## Qué son las herramientas CI/CD

Las herramientas CI/CD hacen referencia a un método para distribuir las aplicaciones a los clientes con frecuencia, mediante el uso de la automatización en las etapas del desarrollo de las aplicaciones. Los principales conceptos que se le atribuyen son la Integración Continua (CI) y la Distribución e Implementación Continua (CD). 

### Integración Continua (CI)
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
<img src="img\gitlab_workflow.png">
</div>

## Qué es y dentro de que grupo de las herramientas CI/CD está
GitLab es una plataforma de desarrollo de software integral basada en Git y de código abierto. Con control de versiones y ___DevOps*___ integrado, seguimiento de incidencias, revisión de código, CI/CD y mucho más. Además, puede ser instalada en tus propios servidores, en un contenedor o en un proveedor en la nube.

Es una herramienta que se encuentra en el grupo de herramientas CI/CD, lo que significa que ofrece características tanto de Integración Continua (CI) como de Despliegue Continuo (CD). Permite automatizar y orquestar el proceso de desarrollo, pruebas y despliegue de software, brindando una solución integral para respaldar las prácticas ágiles de desarrollo y las metodologías de DevOps.

Fue escrito en 2011 por los programadores ucranianos Dmitriy Zaporozhets y Valery Sizov en el lenguaje de programación Ruby3​ y Go, inicialmente como una solución de gestión de código fuente para colaborar con su equipo en el desarrollo de software. Luego evolucionó a una solución integrada que cubre el ciclo de vida del desarrollo de software, y luego a todo el ciclo de vida de DevOps. La arquitectura tecnológica actual incluye Go, Ruby on Rails y Vue.js.

La compañía, GitLab Inc. cuenta con un equipo de 1309 miembros. Es usado por organizaciones como la NASA, el CERN, IBM o Sony.

- - - 
___*DevOps:__ Es una metodología que busca integrar el desarrollo de software (Dev) con las operaciones de tecnología de la información(Ops). Estas operaciones se refieren a las actividades y procesos relacionados con la gestión y el mantenimiento de los sistemas de tecnología de la información en una organización: Gestión de infraestructura, soporte técnico, monitoreo y seguridad..._

<div align="center">
<img src="img\gitlab.png">
</div>

<div align="center">
<img src="img\gitlabcicd.png">
</div>
:sound: <a href="https://youtu.be/l5705U8s_nQ?t=369">Profundiza un poco más en Gitlab CI/CD</a>


## Qué ofrece

- Administración, creación y conexión de repositorios con diferentes aplicaciones e integración con ellas, ofreciendo un ambiente y una plataforma en la que se pueden realizar las diferentes etapas de su ciclo de vida de desarrollo de software (SDLC) y DevOps. 
- Alojamiento de wikis
- Sistema de seguimiento y detección de errores

## Plan de precios

## Ejemplo de integración con repositorios de código
Gitlab es una herramienta con una amplia gama de aplicaciones con las que se puede integrar. En este caso, nosotros hemos elegido Asana. Una aplicación web y móvil para la gestión de tareas, que está diseñada para facilitar a las personas y a los equipos la planificación y la gestión de sus proyectos. Cada equipo tiene un espacio de trabajo. Los espacios de trabajo contienen proyectos y los proyectos contienen tareas.

Actualmente esta tecnología es usada por empresas como Paypal, Spotify o Amazon entre otras muchas más.

<div align="center">
<img src="img\asana-logo.png" width="400">
</div>

- Paso 1: Loging en Asana.
- Paso 2: Integración a través de Unito. App que es capaz de crear un flujo de trabajo con integraciones personalizables y de autoservicio, que permiten a todos los miembros del equipo trabajar en la herramienta de su elección sin perderse nada gracias a una sincronización bidireccional automatizada y sin código.

<div align="center">
<img src="img\asana1.png" width="1000">
</div>

## Conecta tus herramientas
<div align="center">
<img src="img\asana2.png" width="1000">
</div>

## Establezca la dirección de flujo entre sus herramientas
<div align="center">
<img src="img\asana3.png" width="1000">
</div>

## Elija las tareas que desea sincronizar
<div align="center">
<img src="img\asana4.png" width="1000">
</div>

## Resultado
<div align="left">
<img src="img\asana8.png" width="1000">
<img src="img\asana9.png" width="1000">
</div>

## Ejemplo de documentación de proyectos
## Repositorios

<div align="center">

[![Documentación en Gitlab](https://res.cloudinary.com/marcomontalbano/image/upload/v1684606423/video_to_markdown/images/youtube--w-eQoSPhphw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/w-eQoSPhphw "Documentación en Gitlab")

</div>

## Wikis
Si no quieres tener tu documentación en tu repositorio, pero quieres mantenerla en el mismo proyecto que tu código, puedes usar el wiki que GitLab proporciona en cada proyecto GitLab. Cada wiki es un repositorio Git separado, así que puedes crear páginas wiki en la interfaz web, o localmente usando Git. Además, si utilizas grupos de GitLab para gestionar varios proyecto, puedes crear wikis de grupo, en lugar de wikis de proyecto, para asegurarte de que todos los miembros del grupo tienen los permisos de acceso correctos para contribuir.

Los wikis de GitLab soportan Markdown, Rdoc, AsciiDoc y Org para el contenido. Además, aportan diferentes funcionalidades, como puede ser la rápida creación de tablas, menús desplegables e incluso un propio sistema de creación y edición de diagramas.

<div align="center">
<img src="img\gitlabdoc1.png" width="1000">

<img src="img\gitlabdoc-diagram.png" width="1000">

<img src="img\gitlabdoc4.png" width="1000">
</div>

## Otras herramientas con las que se integra
## Comparativa con otras herramientas
## Por qué escoger la herramienta frente a otras

<div align="center">
<img src="img\g2results.png" width="1000">
</div>

### Aplicación única:
GitLab reúne todas las funciones de DevOps en una sola aplicación con un almacén de datos unificado para que todo esté en el mismo sitio.

### Integración múltiple:
Gitlab posee una gran adaptabilidad para integrarse con multitud de herramientas de cualquier tipo.

### Documentación:
Cualquier problema, duda o forma de proceder puede ser solucionada por la extensa pero a la vez accesible documentación presente en Gitlab.

### Automatización:
Las herramientas de automatización de GitLab son más fiables y tienen más funciones, lo que ayuda a eliminar la carga cognitiva y el trabajo pesado innecesario.

### Seguridad integrada, no añadida:
Las funciones de seguridad de GitLab -como DAST, pruebas fuzz, escaneo de contenedores y detección de API- están integradas de principio a fin.

### Sin ataduras a la nube:
GitLab no está vinculado comercialmente a un único proveedor de servicios en la nube, lo que elimina el riesgo de dependencia del proveedor.

:money_with_wings: :chart_with_upwards_trend: <a href="https://about.gitlab.com/calculator/roi/?calculator=time">Calculadora ahorro de Gitlab</a>

[![Gitlab](https://res.cloudinary.com/marcomontalbano/image/upload/v1684695824/video_to_markdown/images/vimeo--799236905-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://vimeo.com/799236905 "Gitlab")

## Referencias
https://www.redhat.com/es/topics/devops/what-is-ci-cd

https://docs.gitlab.com/

</div>
