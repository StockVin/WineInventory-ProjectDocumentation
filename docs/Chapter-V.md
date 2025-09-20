# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##



### 5.1.1. Software Development Environment Configuration ###

* **Project Management**

 En la gestión y desarrollo del ciclo del proyecto se emplearon las aplicaciones Discord y Google Meet para realizar reuniones grupales, en las que se discutieron los avances y se revisaron aspectos que requerían corrección. Posteriormente, la documentación del proyecto fue elaborada utilizando el formato MarkDown.

* **Requirements Management**

  Para la gestión de los requisitos del proyecto (historias de usuario, product backlog y sprint backlog) se empleó Trello, una herramienta muy útil para la administración de proyectos. Con esta plataforma es posible organizar el product backlog de manera visual a través de tableros, en los que se crean listas que representan las diferentes etapas del flujo de trabajo. Dentro de cada lista se añaden tarjetas que corresponden a las user stories o tareas específicas, las cuales pueden incluir información relevante como prioridades, etiquetas de colores, descripciones y listas de verificación, lo que facilita tanto el seguimiento como la colaboración entre los miembros del equipo.

* **Product UX/UI Design**

  Para la elaboración de las plantillas de User Persona y Impact Mapping se utilizó UXPressia, una plataforma especializada en diseñar mapas de experiencia del usuario. Su interfaz está enfocada en UX, lo que facilita una estructuración clara y profesional de estos elementos. Entre sus ventajas destacan las plantillas personalizables, la incorporación de datos reales, imágenes y métricas, así como la posibilidad de colaborar en tiempo real.
  
  En el caso del Lean UX Canvas, se empleó Canva, una herramienta versátil que permite crear distintos tipos de diseños. Esta aplicación favorece la colaboración entre los miembros del equipo y posibilita exportar los proyectos en formatos PNG o PDF, manteniendo un flujo creativo ordenado y atractivo.
  
  Para la realización de Journey Mapping, Empathy Mapping y otros mapas, se optó por Miro, ya que ofrece colaboración en tiempo real, una interfaz intuitiva y visual, además de plantillas prediseñadas que agilizan el trabajo sin sacrificar la calidad metodológica.
  
  Finalmente, para el diseño de wireframes, mockups y prototipos de la aplicación se utilizó Figma. Esta herramienta permite construir interfaces mediante colores, imágenes, formas y otros recursos visuales, además de probar distintos modelos de dispositivos. Su función de simulación interactiva resulta fundamental para el desarrollo del prototipo, pues facilita visualizar y experimentar el proyecto desde la perspectiva del usuario.


* **Software Development**

  Para el desarrollo del Landing Page, se emplearon dos herramientas principales: GitHub y JetBrains. La primera permitió gestionar de manera eficiente los avances colaborativos del proyecto, mientras que JetBrains facilitó el trabajo con los lenguajes HTML5, CSS y JavaScript. 
  
  En cuanto al desarrollo del Frontend Web Application, se utilizaron GitHub y WebStorm. GitHub cumplió la función de organizar y documentar correctamente los progresos realizados por el equipo, mientras que WebStorm fue el entorno donde se programó la aplicación Frontend utilizando HTML5, CSS y TypeScript, además del framework Angular.
  
  Finalmente, para el desarrollo de los Web Services, también se recurrió a GitHub y WebStorm. GitHub aseguró el control y la documentación de los avances del proyecto, mientras que WebStorm permitió implementar la aplicación Backend con el lenguaje Java, empleando el framework Spring junto con su extensión Spring Boot.

* **Software Testing**

  Las pruebas del Landing Page y del Frontend se realizarán mediante uso del navegador web para verificar que el diseño del mismo cumple con aspectos como el diseño responsivo en cualquier dispositivo desde el que se acceda al landing page y al frontend del proyecto. Además, para visualizar que se han implementado correctamente elementos visuales que deben aparecer en las distintas secciones de la página.

  Las pruebas del frontend se realizaron utilizando una fake API mediante JSON Server, que funcionó como una base de datos temporal para validar el correcto funcionamiento de las interfaces y las interacciones con los datos.

  Las pruebas del backend se realizaron mediante Swagger UI y Postman, herramientas que facilitaron la ejecución de consultas y solicitudes HTTP de manera visual e intuitiva, permitiendo verificar el correcto funcionamiento de los endpoints expuestos por la API. Gracias a estas herramientas, fue posible simular distintos escenarios de uso, validar las respuestas del servidor, analizar los códigos de estado HTTP y garantizar que la lógica del backend respondiera adecuadamente ante entradas válidas y erróneas.


* **Software Deployment**

  Para el despliegue del Landing page se uso la el servicio web de github pages, este servicio se especializa en el despliegue de sitios web staticos directamente desde un repositorio.
  Para el despliegue del Frontend se uso beeceptor y firebase. Beeceptor es una herramienta en línea (basada en la web) que nos permite crear endpoints HTTP falsos (mock) para probar APIs, se uso ver qué datos está enviando nuestra aplicación. Firebase es una plataforma desarrollada por Google que permite crear aplicaciones web y móviles más rápido, sin tener que construir un backend completo desde cero, ofrece servicios listos para usar que se pueden usar para conectar facilmente nuestro Frontend.
  Para el despliegue del Backend se utilizo Render. Render es una plataforma en la nube que permite desplegar aplicaciones web, APIs, bases de datos, sitios estáticos y más de forma sencilla y automatizada, sin necesidad de gestionar servidores manualmente. Permite que una aplicación backend (como una API REST hecha en Spring Boot) esté disponible públicamente en internet, funcionando 24/7 con un dominio propio o asignado automáticamente.



### 5.1.2. Source Code Management ###
  En esta parte se detallan los métodos y estructuras de organización destinados a manejar eficientemente los archivos de los proyectos de Landing Page, Web Services y Aplicaciones Web Frontend. Para los repositorios se empleará GitHub como plataforma de almacenamiento, complementado con la estrategia GitFlow. Esta metodología permitirá al equipo trabajar en paralelo mediante ramas específicas para nuevas funcionalidades y versiones de lanzamiento, asegurando un control adecuado del progreso y las versiones del proyecto.En esta parte se detallan los métodos y estructuras de organización destinados a manejar eficientemente los archivos de los proyectos de Landing Page, Web Services y Aplicaciones Web Frontend. Para los repositorios se empleará GitHub como plataforma de almacenamiento, complementado con la estrategia GitFlow. Esta metodología permitirá al equipo trabajar en paralelo mediante ramas específicas para nuevas funcionalidades y versiones de lanzamiento, asegurando un control adecuado del progreso y las versiones del proyecto.


#### **5.1.2.1. Repositorios**
  A continuación, se presentan los enlaces de acceso para cada repositorio donde se almacenarán los archivos relacionados al Landing Page, Frontend Web Applications y Web Services.

  
* **Landing Page: [https://wineinventory-landing-page.web.app/](https://wineinventory-landing-page.web.app/)**
* **Frontend Web Applications: [https:](https:)**
* **Web Services: [https:](https:)**

#### **5.1.2.2. GitFlow**

  Tal como se indicó anteriormente, GitFlow permitirá al equipo de desarrollo administrar de forma eficiente el ciclo de vida del proyecto. En términos generales, GitHub contribuirá a optimizar el trabajo colaborativo, ya que ofrece una mayor facilidad para coordinar y desarrollar tareas en conjunto dentro de los repositorios del proyecto.


##### **5.1.2.2.1. Main Branches**

  * **Main Branch**   
  Llamada también rama principal del proyecto, esta es la rama predeterminada del proyecto creado en el repositorio. Esta rama representa el historial del proyecto lo que ayuda a llevar el control de versiones del mismo.

    
* **Develop Branch**  
  Llamada también rama de desarrollo del proyecto. Esta rama es una bifurcación de código original del proyecto para definir nuevos rumbos respecto del proyecto original que servirá para evaluar variaciones del proyecto para su evolución. Además, ayudan a incorporar nuevas funciones al proyecto.

##### **5.1.2.2.2. Supporting Branches**

* **Feature Branch**  
  También llamada rama de característica del proyecto, es una rama de desarrollo que ayuda a incorporar nuevas funciones al proyecto en desarrollo. Además, permite el aislamiento de la función agregada y que varios colaboradores puedan trabajar simultáneamente en dicha funcionalidad.

* **Release Branch**  
  También llamada rama de lanzamiento del proyecto, es una versión de código del proyecto que se usa para empezar un nuevo ciclo de lanzamiento del producto de software. Además, en esta rama se pueden realizar correcciones de errores de la versión pasada del proyecto. Finalmente, una vez terminada con esta rama, se suma a la rama principal del proyecto y se le asigna un nuevo número de versión de proyecto.

* **Hotfix Branch**  
  También llamada rama de corrección del proyecto, es una rama que permite dar mantenimiento al código del proyecto. Se utiliza principalmente para arreglar errores en alguna sección del producto de software de manera rápida.


#### **5.1.2.3. Release Versioning Conventions**

  Para la nomenclatura de los lanzamientos del Landing Page, se utilizará Semantic Versioning que consta de tres partes para describir cambios mayores, cambios menores y parches para corrección de bugs, según la siguiente estructura:

* Número principal: Incrementa cuando se realiza un cambio mayor y significativo al proyecto.  
* Número secundario: Incrementa cuando se realiza un cambio menor al proyecto como arreglo de errores o agregación de características.  
* Número terciario: Incrementa cuando se realiza un parche al proyecto como una corrección de bugs o errores visuales.

#### **5.1.2.3. Commits Conventions**

  Para los textos de mensajes en los *‘commits’* del proyecto en Git, se utilizará Conventional Commits. Estos son mensajes de confirmación que son fáciles de entender por los colaboradores del proyecto. Finalmente, estos mensajes siguen la siguiente estructura:  

<!-- Commits-->
<p align="center">
  <img src="https://i.imgur.com/vfirypa.png" alt="Commits">


La sección *‘type’* indica el tipo de mensaje de confirmación que se usará. A continuación, la sección *‘description’* indica la descripción que se le agrega al mensaje de confirmación, por ejemplo, una característica agregada. Además, la sección *‘body’* incluye una descripción más detallada del cambio aplicado al proyecto.  
Luego, se tienen distintos tipos de mensajes de confirmación. Por ejemplo, se tiene el mensaje tipo *‘fix’* que incluye una corrección al proyecto. Utilizar este tipo conlleva aumentar el número terciario de la versión del proyecto (por ejemplo, de 1.0.0. a 1.0.1.). Después, utilizar el mensaje de tipo *‘feat’* conlleva agregar una nueva función a la aplicación, por lo tanto, se debe aumentar el número secundario de la versión (por ejemplo, de 1.0.0. a 1.1.0.). Finalmente, si se agrega una sección de tipo ‘BREAKING CHANGE’ indicaría que las versiones anteriores del proyecto dejarán de ser compatibles entre sí, lo que conlleva un cambio significativo y el aumento del número principal de la versión (por ejemplo, de 1.0.0. a 2.0.0.).


### 5.1.3. Source Code Style Guide & Conventions ###

  En esta sección, se definen las referencias que se usaron para adoptar estrategias de nomenclatura de elementos de programación en los lenguajes que se usarán para la solución (HTML, CSS, JavaScript, TypeScript y Java). En general, la nomenclatura de los archivos y secciones en la programación se hará en inglés.

* **Nomenclatura en HTML:**  
  Para la codificación del proyecto en HTML, se utilizará el artículo *“HTML Style Guide and Coding Conventions”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en HTML como si se debe escribir en minúsculas o mayúsculas las secciones del cuerpo del documento. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://www.w3schools.com/html/html5\_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en HTML para el landing page de StockSip a desarrollar.

* **Nomenclatura en CSS:**  
  Para la codificación del proyecto en Cascading Style Sheets (CSS), se utilizará el artículo *“Google HTML/CSS Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en CSS como capitalización en código de colores, referencias a imágenes, etc. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en CSS para el estilo de colores que se quiere agregar al landing page de StockSip a desarrollar.

* **Nomenclatura en TypeScript:**  
  Para la codificación del proyecto en TypeScript, se utilizará el artículo *“Google TypeScript Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que establece las convenciones de codificación que Google sigue para escribir código en TypeScript. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/tsguide.html](https://google.github.io/styleguide/tsguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.  
    
* **Nomenclatura en Angular:**  
  Para la codificación del proyecto en Angular, se utilizará el artículo *“Angular coding style guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Angular recomienda para escribir código en sus aplicaciones. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Angular. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://angular.dev/style-guide](https://angular.dev/style-guide)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockSip.  
    
* **Nomenclatura en Java:**  
  Para la codificación del proyecto en Java, se utilizará el artículo *“Google Java Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Google sigue para escribir código en Java. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Google. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.

* **Nomenclatura en Spring Boot:**  
  Para la codificación del proyecto en Spring Boot, se utilizará el artículo *“Spring Boot Features”.* Este artículo contiene información útil y necesaria para comprender las características fundamentales que ofrece Spring Boot para el desarrollo de aplicaciones en el ecosistema Spring. Su objetivo principal es presentar de forma estructurada los componentes clave del framework, promoviendo un desarrollo eficiente, coherente y escalable, especialmente para proyectos que buscan aprovechar la configuración automática, la modularidad y las mejores prácticas del desarrollo moderno con Java. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://docs.spring.io/spring-boot/reference/features/index.html](https://docs.spring.io/spring-boot/reference/features/index.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.
En esta sección, se definen las referencias que se usaron para adoptar estrategias de nomenclatura de elementos de programación en los lenguajes que se usarán para la solución (HTML, CSS, JavaScript, TypeScript y Java). En general, la nomenclatura de los archivos y secciones en la programación se hará en inglés.

* **Nomenclatura en HTML:**  
  Para la codificación del proyecto en HTML, se utilizará el artículo *“HTML Style Guide and Coding Conventions”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en HTML como si se debe escribir en minúsculas o mayúsculas las secciones del cuerpo del documento. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://www.w3schools.com/html/html5\_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en HTML para el landing page de StockSip a desarrollar.

* **Nomenclatura en CSS:**  
  Para la codificación del proyecto en Cascading Style Sheets (CSS), se utilizará el artículo *“Google HTML/CSS Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en CSS como capitalización en código de colores, referencias a imágenes, etc. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en CSS para el estilo de colores que se quiere agregar al landing page de StockSip a desarrollar.

* **Nomenclatura en TypeScript:**  
  Para la codificación del proyecto en TypeScript, se utilizará el artículo *“Google TypeScript Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que establece las convenciones de codificación que Google sigue para escribir código en TypeScript. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/tsguide.html](https://google.github.io/styleguide/tsguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.  
    
* **Nomenclatura en Angular:**  
  Para la codificación del proyecto en Angular, se utilizará el artículo *“Angular coding style guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Angular recomienda para escribir código en sus aplicaciones. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Angular. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://angular.dev/style-guide](https://angular.dev/style-guide)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockSip.  
    
* **Nomenclatura en Java:**  
  Para la codificación del proyecto en Java, se utilizará el artículo *“Google Java Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Google sigue para escribir código en Java. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Google. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.

* **Nomenclatura en Spring Boot:**  
  Para la codificación del proyecto en Spring Boot, se utilizará el artículo *“Spring Boot Features”.* Este artículo contiene información útil y necesaria para comprender las características fundamentales que ofrece Spring Boot para el desarrollo de aplicaciones en el ecosistema Spring. Su objetivo principal es presentar de forma estructurada los componentes clave del framework, promoviendo un desarrollo eficiente, coherente y escalable, especialmente para proyectos que buscan aprovechar la configuración automática, la modularidad y las mejores prácticas del desarrollo moderno con Java. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://docs.spring.io/spring-boot/reference/features/index.html](https://docs.spring.io/spring-boot/reference/features/index.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockSip.


### 5.1.4. Software Deployment Configuration ###

  En esta sección, se especifica la configuración para realizar el despliegue de la solución en el repositorio. Para realizar esto, se usó GitHub Pages para lanzar el landing page, Web Services y Frontend Web Applications. A continuación, se describen los pasos necesarios para desplegar el Landing Page del proyecto, empezando por la creación del repositorio hasta el lanzamiento del proyecto.

  **Paso 1: Creación del repositorio**  
  Como primer paso, se debe crear el repositorio en GitHub que será el lugar donde se aloja todo lo relacionado al Landing Page.

<p align="center">
  <img src="../img/Chapter V/paso 1.jpeg">

* **Paso 2: Carga de archivos necesarios**   
  Como segundo paso, se importan todos los archivos necesarios para el desarrollo del landing page como imágenes, archivos HTML, CSS y JavaScript.

<p align="center">
  <img src="../img/Chapter V/paso 2.PNG">

* **Paso 3: Preparar el lanzamiento**  
  Como tercer paso, se juntan todas las características del proyecto en una sola para verificar el correcto funcionamiento de cada una. Luego, se envía todo a la rama principal donde se encuentra, por defecto, el proyecto.

<p align="center">
  <img src="../img/Chapter V/paso 3.PNG">

* **Paso 4: Lanzar el Landing Page**  
  Como cuarto paso, cuando todo se encuentre en la rama principal, se accede a la sección Configuración del repositorio, luego, se selecciona la opción “GitHub Pages” y se seleccionará la rama principal que es la que se desea desplegar.

<p align="center">
  <img src="../img/Chapter V/paso 4.jpeg">
  
* **Paso 5: Acceder al Landing Page**  
  Como paso final, el entorno otorgará un enlace para poder acceder al proyecto desplegado.

  <img src="../img/Chapter V/paso 5.PNG">


## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

#### 5.2.1.1. Sprint Planning 1 ####

A continuación, se detalla, en la tabla siguiente, información sobre el planeamiento del primer sprint. En general, el objetivo de este sprint se centra en el desarrollo y despliegue de la primera versión del sitio web estático de StockSip.

| Sprint #                                     | Sprint 1                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                                                                                                                                                                                                                                                                                                |
| Date                                         | 2025/08/20                                                                                                                                                                                                                                                                                                                        |
| Time                                         | 02:30 PM                                                                                                                                                                                                                                                                                                                          |
| Location                                     | Reunión mediante llamada virtual en Google meet                                                                                                                                                                                                                                                                                       |
| Prepared By                                  | Diaz Quispe, Matias Sebastian                                                                                                                                                                                                                                                                                                     |
| Attendees                                    | Diaz Quispe, Matias Sebastian / Torres Apolinario Giovany Smith / Hermoza Paredes Bryan Norberto / Burga Loarte Anaely Zarely / Meza Solòrzano Didier Sebastiàn                                                                                                                                                          |
| <b> Sprint Goal & User Stories </b>          | --                                                                                                                                                                                                                                                                                                                                |
| Sprint 1 Goal                                | <b> Nos enfocamos en el desarrollo e implementación de la versión inicial de la página de destino nuestra landing page. Consideramos que brinda una primera aproximación a lo que nuestro producto ofrece a los segmentos objetivo. Esto se validará cuando dichos segmentos visiten el sitio y puedan explorar y comprender las ventajas de utilizar nuestro producto. |
| Sprint 1 Velocity                            | 16                                                                                                                                                                                                                                                                                                                                |
| Sum of Story Points                          | 16                                                                                                                                                                                                                                                                                                                                |


#### 5.2.1.2. Aspect Leaders and Collaborators ####

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este primer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada sección y el estilo que debe contener este mismo: inicio, funcionamiento de la aplicación, beneficios para cada segmento, testimonios, exploración de la aplicación, planes y contacto.

| Team Member                        | GitHub Username | Sección Inicio | Nosotros | Servicios | Planes | FAQ | Acerca |  
|------------------------------------|-----------------|----------------|---------------------------------|------------|-------------|--------|----------|
| Diaz Quispe, Matias Sebastian      | equinox-1092      |               |                                |L            |             |        |         |        |
| Torres Apolinario Giovany Smith    | Giovany7x     |                | L                               |            |             |    L    |          |     |
| Hermoza Paredes Bryan Norberto  | WasNeo          |                |                                 |          |             |        |L          |
| Burga Loarte Anaely Zarely | userxx1000      |                |                                 |            | L           |        |          |
| Meza Solòrzano Didier Sebastiàn      | Didier04x    |L                |                                 |            |             |      | 


#### 5.2.1.3. Sprint Backlog 1 ####

    
Tal como se indicó en la planificación del sprint 1, el propósito principal es desarrollar y publicar una primera versión del landing page del producto. Esto implica construir las distintas secciones propias de una página de destino que permitan a los visitantes conocer mejor el producto en desarrollo.

Una vez establecido el objetivo del sprint, se definieron las historias de usuario correspondientes. Posteriormente, cada historia se desglosó en tareas específicas orientadas a su implementación y cumplimiento. Para la gestión y seguimiento del avance del sprint se empleó la herramienta Trello.

[https://trello.com/invite/b/68cdead316cdf8f725d31dc4/ATTIb2c26157068ddd697d52ec199a465bb222D27F2B/stockvin-sprint-backlog-1](https://trello.com/invite/b/68cdead316cdf8f725d31dc4/ATTIb2c26157068ddd697d52ec199a465bb222D27F2B/stockvin-sprint-backlog-1)

<p align="center">

<img src="../img/Chapter V/sprint Back 1.PNG">

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este primer sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 1     | Sprint Backlog 1                                              |     |                                         |                                                                                                            |                    |                |            |
|--------------|---------------------------------------------------------------|-----|-----------------------------------------|------------------------------------------------------------------------------------------------------------|--------------------|----------------|------------|
| User Stories |                                                               | Work Item/Task                                |                                                                                                            |                    |                |            |
| Id           | Title                                                         | Id  | Title                                   | Description                                                                                                | Estimation (Hours) | Assigned to    | Status     |
| US001        | Ver propuesta de valor clara                                  | 001 | Diseñar sección inicio                  | Diseñar el encabezado con logo, menú de navegación y sección principal.                                    | 0.5                | Matias Diaz | Done       |
|              |                                                               | 002 | Crear estructura principal del Landing Page  | Crear la estructura principal de la página en HTML y los estilos iniciales en CSS.                         | 0.5                | Matias Diaz | Done       |
|              |                                                               | 003 | Diseñar sección contacto                | Diseñar el pie de página con información de contacto y enlaces a otras secciones                           | 0.5                | Matias Diaz | Done       |
|              |                                                               | 004 | Describir visión y misión del startup   | Agregar espacios que detallen la misión y visión de la empresa.                                            | 0.5                | Giovany Torres | Done       |
|              |                                                               | 005 | Añadir estilos a la sección Inicio      | Estilizar las secciones de contacto e inicio para que sean visiblemente agradables y llamativas.           | 0.5                | Matias Diaz | Done       |
| US002        | Acceder a explicación detallada sobre el uso de la aplicación | 001 | Añadir sección sobre funcionamiento de la aplicación | Separar una sección de la estructura general para agregar el contenido de explicación de cómo funciona la aplicación. | 0.3     | Didier Meza | Done       |
|              |                                                               | 002 | Describir las funcionalidades           | Resumir cada funcionalidad que podrá utilizar cada segmento objetivo.                                      | 0.4                | Didier Meza | Done       |
|              |                                                               | 003 | Añadir imágenes referenciales sobre funcionalidades | Para cada funcionalidad detallada, agregar una imágen referencial.                                         | 0.5                | Didier Meza | Done       |
|              |                                                               | 004 | Ordenar las imagenes y las descripciones de funcionalidades | Ordenar y organizar cada funcionalidad descrita con su imagen.                                             | 0.4                | Didier Meza | Done       |
|              |                                                               | 005 | Añadir estilos a la sección de funcionamiento | Usando CSS, añadir estilos a esta sección para que sea visiblemente llamativa.                             | 0.6                | Matias Diaz | Done      |
| US003        | Ver beneficios para licorerías	                               | 001 | Implementar sección beneficios para licorerías         | Diseñar la subsección de beneficios para dueños de licorerías agregando tarjetas con listas de beneficios. | 0.6                | Bryan Hermosa  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes a la sección beneficios para licorerías | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Bryan Hermosa  | Done      |
|              |                                                               | 003 | Añadir estilos a la sección de beneficios para licorerías | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Bryan Hermosa  | Done      |
| US004        | Ver beneficios para proveedores                               | 001 | Implementar sección beneficios para proveedores | Diseñar la subsección de beneficios para proveedores agregando tarjetas con listas de beneficios.          | 0.6                | Bryan Hermosa  | Done      |
|              |                                                               | 002 | Agregar íconos e imágenes a la sección beneficios para proveedores | Añadir imágenes referenciales al segmento objetivo al que son dirigidos los beneficios.                    | 0.5                | Bryan Hermosa  | Done      |
|              |                                                               | 003 | Añadir estilos a la sección de beneficios para proveedores | Añadir estilos usando CSS a la subsección para dar detalles visualmente agradables.                        | 0.5                | Bryan Hermosa  | Done      |    
| US006        | Leer testimonios de clientes		                               | 001 | Añadir sección para testimonios         | Usando HTML, separar una sección para colocar todo el contenido de esta sección.                           | 0.5                | Giovany Torres | Done      |
|              |                                                               | 002 | Redactar testimonios de personas sobre la aplicación  | Redactar uno o varios testimonios para cada segmento objetivo que den su opinión sobre la aplicación.     | 0.4                | Giovany Torres | Done      |
|              |                                                               | 003 | Añadir tarjetas para cada testimonio    | Crear tarjetas en la estructura. Estas tarjetas contendrán el texto del testimonio.                        | 0.4                | Giovany Torres | Done      |
|              |                                                               | 004 | Añadir imágenes de personas para testimonios  | Agregar al lado del texto, una imagen referencial de la persona que está dando su testimonio.              | 0.4                | Giovany Torres | Done      |
|              |                                                               | 005 | Añadir estilos a la sección de testimonios | Agregar estilos a la sección usando CSS.                                                                   | 0.6                | Giovany Torres | Done      |
| US007        | Comparar planes gratis y premium	                             | 001 | Añadir sección de planes de suscripción | Diseñar la sección de planes con tarjetas que detallen las características de cada plan.                   | 0.5                | Anaely Burga | Done      |
|              |                                                               | 002 | Añadir información para segmentos de dueños de licorería y proveedores | Añadir texto diferenciando funcionalidades que incluye el plan para cada segmento objetivo.                | 0.6                | Anaely Burga | Done      |
|              |                                                               | 003 | Agregar comparación entre planes  | Añadir texto en las tarjetas que pueda ser utilizado para saber qué contiene el plan premium.              | 0.6                | Matias Diaz | Done      |
|              |                                                               | 004 | Añadir íconos relacionados a planes | Añadir íconos relacionados a lo que ofrece cada plan para cada segmento objetivo.                          | 0.6                | Anaely Burga | Done      |  
|              |                                                               | 005 | Añadir estilos a la sección planes | Estilizar la sección usando CSS.                                                                           | 0.5                | Anaely Burga | Done      |
| US008        | Conocer el precio y condiciones	                             | 001 | Añadir espacio para precios en las tarjetas de planes | En la sección de planes, agregar un recuadro que indique el precio para cada plan                          | 0.3                | Anaely Burga | Done      |
|              |                                                               | 002 | Añadir estilos a los precios | Estilizar los recuadros para precios usando CSS.                                                           | 0.3                | Anaely Burga | Done      |


#### 5.2.1.4. Development Evidence for Sprint Review ####

En esta parte se detallan los principales progresos de implementación alcanzados durante el primer sprint. El logro más relevante corresponde al desarrollo inicial de cada una de las secciones del landing page en su primera versión.

Cada integrante del equipo avanzó de manera progresiva en la construcción de dichas secciones. Finalmente, se incorporaron estilos mediante CSS para darles mejor presentación.

Seguidamente, se presenta una tabla que recopila la información de los commits realizados, los cuales incluyen fragmentos de las funcionalidades necesarias para completar este primer sprint.
| Repository                             | Branch                           | Commit Id | Commit Message                                                   | Commited On |
|----------------------------------------|----------------------------------|-----------|------------------------------------------------------------------|-------------|
| StockVin/WineInventory-LandingPage         | master                           | f35ecc2   | chore: add home section                                          | 16/09/2025  |
| StockVin/WineInventory-LandingPage         | master                           | df4416f   | feat(home): add home section and styles                          | 16/09/2025  |
| StockVin/WineInventory-LandingPage         | master                           | fead8af   | chore: add images in home section                                | 16/09/2025  |
| StockVin/WineInventory-LandingPage         | master                           | 85a32a0   | feat(footer): add footer section and style                       | 16/09/2025  |
| StockVin/WineInventory-LandingPage         | feature/how-it-works             | b35b8a1   | chore: add image file.                                           | 05/09/2025  |
| StockVin/WineInventory-LandingPage         | feature/how-it-works             | f730632   | feat(how-it-works): add how it works html                        | 26/09/2025  |
| StockVin/WineInventory-LandingPage         | feature/how-it-works                     | ece8b35   | feat(how-it-works): add how it works style css                   | 24/04/2025  |
| StockVin/WineInventory-LandingPage         | feature/premium-plans            | c11a1db   | feat(section-premium-plans): add premium plans section and styles| 24/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/premium-plans            | a441e10   | feat(section-premium-plans): add premium plans section and styles| 24/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/benefits                 | 1985575   | feat(benefits): add benefits section                             | 25/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/benefits                 | 4ac613f   | feat(benefits): add css styles                                   | 25/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/how-it-works             | bc1c0ae   | fix(how-it-works): fix styles.                                   | 25/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/how-it-works             | 34bbff6   | fix(how-it-works): fix index html.                               | 25/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/testimonials             | 5274230   | feat(testimonials): add html structure for testimonials section. | 26/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/testimonials             | 2f4f14a   | feat(testimonials): add css styles for testimonials section.     | 26/08/2025  |
| StockVin/WineInventory-LandingPage         | feature/testimonials             | d2ca22d   | docs: add testimonials images.                                   | 26/08/2025  |



#### 5.2.1.5. Execution Evidence for Sprint Review ####

El objetivo de este sprint fue realizar, en collaboration con todo el equipo, la creación de la landing page. A continuación, se explica a detalle la evidencia del proceso de ejecución del sitio web estático.

Se implementó la sección de inicio que contiene información general sobre el producto y sobre la startup detrás del producto. Además, se incluye la visión general de la startup relacionada con el producto y los valores del equipo de desarrollo. Esto tiene un motivo de implementación y es el de llamar la atención de los visitantes del sitio web estático.

<p align="center">
  <img src="../img/Chapter V/review 1.PNG"/>
</p>

También, se implementó una sección con un resumen de nosotros en la cual se da a conocer el equipo de trabajo  y sobre nuestra vision y mision como equipo de trabajo.
<p align="center">
  <img src="../img/Chapter V/review 2.PNG"/>
</p>

También, se implementó la sección de servicios donde se da a conocer el servicio que brindamos mediante nuestra app WineInvetory, tanto para proveedores como propietarios de negocios.
<p align="center">
  <img src="../img/Chapter V/review 3.PNG"/>
</p>

Además, se implementó una sección de planes donde se da a conocer los planes disponibles que cuenta nuestra app de Wineinventory.
<p align="center">
  <img src="../img/Chapter V/review 4.PNG"/>
</p>

También, se implementó la sección de "Preguntas Frecuentes", donde se ponen algunas preguntas comunes para que las personas que visiten nuestra pagina tengan un poco de informacion sobre nuestra app.
<p align="center">
  <img src="../img/Chapter V/review 5.PNG"/>
</p>

Finalmente, se agrego la seccion de "Acerca de", donde brindamos un video explicativo sobre nuestra startup y sobre algunas cualidades con las que cuenta WineInventory.


<p align="center">
    <img src="../img/Chapter V/review 6.PNG">
</p>


### 5.2.1.6. Services Documentation Evidence for Sprint Review ###

En el primer sprint el equipo de desarrollo de StockVin ha diseñado, programado y puesto en funcionamiento el sitio web(Landing Page) Para presentar la aplicacion web propuesta denominada "WineInventory". En este sitio webm se logra visualizar varias secciones que ilustran en que consiste WineInventory, cada integrante del equipo de desarrollo de StockVin estuvo a cargo de una seccion en especifico.

| End Point                             | Funciones | 
|----------------------------------------|----------------------------------|
|https://wineinventory-landing-page.web.app/ | Mostrar Landing Page desplegada|


#### 5.2.1.7. Software Deployment Evidence for Sprint Review ####

La organization de nuestro code se realizó en un repositorio en GitHub y para el despliegue de la landing page se utilizó GitHub Pages. Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue del sitio web estático.

Se adjunta el enlace para acceder al sitio web estático desplegado: 

[WineInventory](https://wineinventory-landing-page.web.app/)

#### 5.2.1.8. Team Collaboration Insights during Sprint ###

En esta sección, se explica la colaboración aportada por cada miembro del equipo durante este sprint. Este proyecto se realizo mediante repositorio en GitHub con los siguientes integrantes participantes:

<p align="center">
  <img src="../img/Chapter V/deployev 1.jpeg">
</p>

Respecto del avance realizado por cada integrante en este sprint, se detallan las secciones realizadas por cada integrante: A continuacion, se detallara el trabajo que realizo cada integrante del equipo:

- El integrante Giovany Torres fue responsable de implementar la sección de "Nosotros" y "FAQ" en el Landing page.
- La integrante Matias Diaz implementó las seccion "Servicios" en el Landing page.
- El integrante Bryan Hermosa fue responsable de implementar la seccion "Acerca de" en el landing page.
- El integrante Anaely Burga implementó la seccion de "Planes" en el Landing page.
- El integrante Didier Meza implementó la seccion de "Inicio" en el Landing page.

A continuación, se adjunta el gráfico con la cantidad de commits realizados por cada integrante del equipo durante este sprint para el desarrollo de la primera versión del sitio web estático:
<p align="center">
  <img src="../img/Chapter V/commit 1.PNG"/>
</p>

Finalmente, se muestra el gráfico los avances realizados por los integrantes en las ramas creadas para cada característica que se implementó al sitio web estático en este sprint:
<p align="center">
  <img src="../img/Chapter V/commit 2.jpg"/>
</p>
