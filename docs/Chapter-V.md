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

  
* **Landing Page: [RepositorioLanding page ](https://github.com/StockVin/WineInventory-LandingPage)**
* **Frontend Web Applications: [Repositorio Front end ](https://github.com/StockVin/WineInventory-frontend-application)**
* **Web Services: [Repositorio Back end ](https://github.com/StockVin/WineInventory-backend-application)**

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
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en HTML para el landing page de StockVin a desarrollar.

* **Nomenclatura en CSS:**  
  Para la codificación del proyecto en Cascading Style Sheets (CSS), se utilizará el artículo *“Google HTML/CSS Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en CSS como capitalización en código de colores, referencias a imágenes, etc. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en CSS para el estilo de colores que se quiere agregar al landing page de StockVin a desarrollar.

* **Nomenclatura en TypeScript:**  
  Para la codificación del proyecto en TypeScript, se utilizará el artículo *“Google TypeScript Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que establece las convenciones de codificación que Google sigue para escribir código en TypeScript. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/tsguide.html](https://google.github.io/styleguide/tsguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockVin.  
    
* **Nomenclatura en Angular:**  
  Para la codificación del proyecto en Angular, se utilizará el artículo *“Angular coding style guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Angular recomienda para escribir código en sus aplicaciones. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Angular. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://angular.dev/style-guide](https://angular.dev/style-guide)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockVin.  
    
* **Nomenclatura en Java:**  
  Para la codificación del proyecto en Java, se utilizará el artículo *“Google Java Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Google sigue para escribir código en Java. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Google. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockVin.

* **Nomenclatura en Spring Boot:**  
  Para la codificación del proyecto en Spring Boot, se utilizará el artículo *“Spring Boot Features”.* Este artículo contiene información útil y necesaria para comprender las características fundamentales que ofrece Spring Boot para el desarrollo de aplicaciones en el ecosistema Spring. Su objetivo principal es presentar de forma estructurada los componentes clave del framework, promoviendo un desarrollo eficiente, coherente y escalable, especialmente para proyectos que buscan aprovechar la configuración automática, la modularidad y las mejores prácticas del desarrollo moderno con Java. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://docs.spring.io/spring-boot/reference/features/index.html](https://docs.spring.io/spring-boot/reference/features/index.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockVin.
En esta sección, se definen las referencias que se usaron para adoptar estrategias de nomenclatura de elementos de programación en los lenguajes que se usarán para la solución (HTML, CSS, JavaScript, TypeScript y Java). En general, la nomenclatura de los archivos y secciones en la programación se hará en inglés.

* **Nomenclatura en HTML:**  
  Para la codificación del proyecto en HTML, se utilizará el artículo *“HTML Style Guide and Coding Conventions”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en HTML como si se debe escribir en minúsculas o mayúsculas las secciones del cuerpo del documento. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://www.w3schools.com/html/html5\_syntax.asp](https://www.w3schools.com/html/html5_syntax.asp)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en HTML para el landing page de StockVin a desarrollar.

* **Nomenclatura en CSS:**  
  Para la codificación del proyecto en Cascading Style Sheets (CSS), se utilizará el artículo *“Google HTML/CSS Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que incluye la programación en CSS como capitalización en código de colores, referencias a imágenes, etc. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/htmlcssguide.html](https://google.github.io/styleguide/htmlcssguide.html)   
  Finalmente, se aplicará el contenido del artículo para la nomenclatura en CSS para el estilo de colores que se quiere agregar al landing page de StockVin a desarrollar.

* **Nomenclatura en TypeScript:**  
  Para la codificación del proyecto en TypeScript, se utilizará el artículo *“Google TypeScript Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura de los diversos aspectos que establece las convenciones de codificación que Google sigue para escribir código en TypeScript. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://google.github.io/styleguide/tsguide.html](https://google.github.io/styleguide/tsguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockVin.  
    
* **Nomenclatura en Angular:**  
  Para la codificación del proyecto en Angular, se utilizará el artículo *“Angular coding style guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Angular recomienda para escribir código en sus aplicaciones. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Angular. A continuación se adjunta el enlace para acceder al artículo de referencia: [https://angular.dev/style-guide](https://angular.dev/style-guide)  
  Finalmente, se aplicará el contenido del artículo para el Frontend Applications de StockVin.  
    
* **Nomenclatura en Java:**  
  Para la codificación del proyecto en Java, se utilizará el artículo *“Google Java Style Guide”.* Este artículo contiene información útil y necesaria para conocer cómo debe ser la nomenclatura que establece las convenciones de codificación que Google sigue para escribir código en Java. Su objetivo principal es promover un código consistente, legible y mantenible, especialmente para proyectos que podrían integrarse en el ecosistema de Google. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockVin.

* **Nomenclatura en Spring Boot:**  
  Para la codificación del proyecto en Spring Boot, se utilizará el artículo *“Spring Boot Features”.* Este artículo contiene información útil y necesaria para comprender las características fundamentales que ofrece Spring Boot para el desarrollo de aplicaciones en el ecosistema Spring. Su objetivo principal es presentar de forma estructurada los componentes clave del framework, promoviendo un desarrollo eficiente, coherente y escalable, especialmente para proyectos que buscan aprovechar la configuración automática, la modularidad y las mejores prácticas del desarrollo moderno con Java. A continuación se adjunta el enlace para acceder al artículo de referencia:  [https://docs.spring.io/spring-boot/reference/features/index.html](https://docs.spring.io/spring-boot/reference/features/index.html)  
  Finalmente, se aplicará el contenido del artículo para el Web Services de StockVin.


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

A continuación, se detalla, en la tabla siguiente, información sobre el planeamiento del primer sprint. En general, el objetivo de este sprint se centra en el desarrollo y despliegue de la primera versión del sitio web estático de StockVin.

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


## 5.2.2. Sprint 2
### 5.2.2.1. Sprint Planning 2.

A continuación, se detalla, en la tabla siguiente, información sobre el planeamiento del segundo sprint. Además, para este sprint se definieron dos objetivos para cubrir los aspectos de sitio web estático y aplicación front-end. El primer objetivo se centra en desarrollar una mejora visual para el sitio web estático y añadir secciones para Call-To-Action para los visitantes del sitio web. Por otro lado, el segundo objetivo se centra en el desarrollo y despliegue de la primera versión de la aplicación front-end de StockVin.

| Sprint #                                     | Sprint 2                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/10/04                                             |
| Time                                         | 11:00 AM                                               |
| Location                                     | Reunión por Discord |
| Prepared By                                  | Torres Apolinario Giovany Smith                        |
| Attendees                                    | Diaz Quispe, Matias Sebastian / Torres Apolinario Giovany Smith / Burga Loarte Anaely Zarely / Meza Solòrzano Didier Sebastiàn   |
| Sprint 1 Review Summary                      | En el sprint anterior, el equipo completó una primera vista de la Landing Page implementando las secciones y estilos básicos que necesitará, como Beneficios, Planes e Información sobre la Startup. |
| Sprint 1 Retrospective Summary               | El principal aspecto que el equipo debe mejorar es la mayor comunicación entre los miembros para que se mantengan al tanto del progreso de cada uno. Ahora, el plan para el próximo sprint es trabajar de forma más organizada para que cada miembro sepa qué hacer.  |
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 2 Goals                               | <b> Nuestro enfoque es ofrecer una visualización más detallada y una mayor adaptabilidad de la actual Landing Page de StockVin e implementar y desplegar la primera versión funcional de la aplicación Front-End con características clave como almacenes digitales, el panel de control, registro de productos, advertencias, guías de cuidado y navegación básica entre secciones. Creemos que ofrece diferentes formas de acceder a la Landing Page desde diferentes tamaños de pantalla e idiomas a los segmentos objetivo y visitantes y una primera visión completa de las funcionalidades que la aplicación ofrece a los segmentos objetivo. Esto se confirmará cuando nuestros segmentos objetivo y visitantes accedan a la Landing a través de diferentes dispositivos y cuando nuestros segmentos objetivo se registren en la aplicación y utilicen las principales funcionalidades como almacenes y guías de cuidado. | 
| Sprint 2 Velocity                            | 100                                                    |
| Sum of Story Points                          | 99                                                     |

### 5.2.2.2. Aspect Leaders and Collaborators.

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este segundo sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application. Para esto, hemos definido las siguientes secciones: Alertas, Reportes(cuidado y perdidas), Ordenes, Inventario y zona de almacenamiento y Cuenta de usuario(configuracion, registro, rol)

| Team Member                        | GitHub Username | Alertas | Reportes | Ordenes | Inventario | Cuenta de usuario | 
|------------------------------------|-----------------|---------------------|-----------|-------------------|---------------------------------------------------|---------|
| Diaz Quispe, Matias Sebastian      | equinox-1092    |         |  L       |          |            |        |         
| Torres Apolinario Giovany Smith    | Giovany7x       |         |          | L        |            | L      |     
| Burga Loarte Anaely Zarely         | userxx1000      |         |          |          | L          |        | 
| Meza Solòrzano Didier Sebastiàn    | Didier04x       |   L     |          |          |            |        |

### 5.2.2.3. Sprint Backlog 2.

Como se mencionó previamente en el planeamiento del sprint número 2, el objetivo del mismo es implementar secciones para que los usuarios puedan ser redirigidos a la aplicación web desde el sitio web estático e implementar secciones importantes como inventarios, almacenes, productos, alertas y guías en la aplicación front end del proyecto.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 
[Link Trello](https://trello.com/invite/b/68d83b4319d6b611ef129eaa/ATTI9202e1ccd8750a16ea951f9bff9ce9ecA9336686/stockvin-sprint-backlog-2)

<p align="center">
  <img src="../img/Chapter V/sprint-2.png" 
  alt="Sprint goal y Stories del Sprint #2"/>
</P>

A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este segundo sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 2     | Sprint Backlog 2                                              |             |                                                                                    |                                                                                                                                                                     |                    |                 |             |
|--------------|---------------------------------------------------------------|-------------|------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|-----------------|-------------|
| User Stories |                                                               | Work Item/Task                                                                                   |                                                                                                                                                                     |                    |                 |             |
| Id           | Title                                                         | Id          | Title                                                                              | Description                                                                                                                                                         | Estimation (Hours) | Assigned to     | Status      |
| US005        | Explorar la aplicación como visitante                   | US005T001   | Diseñar sección de vista previa del sistema| Crear una sección en la landing page donde los visitantes puedan visualizar características principales de la aplicación sin necesidad de iniciar sesión.| 8                  | Matias Diaz  | Done        |
| US009        | Registro de usuario                                     | US009T001   | Crear componente de registro| Implementar el formulario de registro con validaciones de campos y conexión a la API simulada para guardar datos de usuario.| 8                  | Matias Diaz  | Done        |
| US010        | Selección de rol durante registro                       | US010T001   |Implementar selector de rol | Agregar un componente con Angular Material que permita elegir el rol de usuario (cliente o proveedor) durante el registro.| 6                  | Matias Diaz  | Done        | 
| US011        | Inicio de sesión de usuario registrado                  | US011T001   | Crear formulario de inicio de sesión | Implementar un formulario de login con validaciones, conexión a la API y redirección al panel correspondiente según el rol del usuario.| 5                  | Matias Diaz  | Done        |
| US016        | Registrar nuevo producto al inventario                  | US016T001   | Crear formulario para añadir productos | Implementar un formulario con campos como nombre, tipo, cantidad e imagen del producto, enlazado al servicio de inventario. | 5                  |  Anaely Loarte | In-Progress |
| US017        | Visualizar lista completa de productos en stock         | US017T001   | Crear tabla de productos en stock | Mostrar los productos disponibles en el inventario mediante una tabla con paginación, filtrado y ordenamiento.| 4                  | Anaely Loarte  | Done        |
| US018        | Editar un producto registrado                           | US018T001   | Crear formulario de edición de producto | Reutilizar el componente base de formularios para permitir la edición de productos existentes dentro del inventario.| 4                  | Anaely Loarte  | Done        |
| US019        | Eliminar un producto del inventario                     | US019T001   | Implementar botón y diálogo de eliminación  | Agregar un botón para eliminar productos con una ventana de confirmación antes de realizar la acción.| 6                  | Anaely Loarte  | Done        |
| US020        | Detallar el estado de salida de productos del inventario| US020T001   | Crear sección de movimientos de salida | Diseñar una interfaz donde se registren y muestren los movimientos de salida de productos del inventario.| 4                  | Anaely Loarte     | Done        |
| US021        | Configurar alertas de reposición de productos           | US021T001   | Crear módulo de configuración de alertas  | Implementar una interfaz que permita al usuario definir el nivel mínimo de stock antes de recibir una alerta. | 6                  | Didier Meza     | Done        |
| US022        | Alertas por próximo vencimiento                         | US022T001   | Crear sistema de alertas automáticas  | Implementar un método que verifique las fechas de vencimiento y muestre alertas visuales en el panel principal.| 5                  | Didier Meza      | Done        |
| US024        |  Visualizar productos en riesgo de vencimiento o merma  | US024T001   | Crear sección de productos en riesgo | Desarrollar una vista que muestre los productos próximos a vencer con indicadores visuales de prioridad.| 7                  | Matias Diaz     | Done        |
| US025        | Crear guía de conservación por tipo de licor            | US025T001   | Implementar formulario para crear guía de conservación | Crear un formulario dinámico para que el usuario pueda registrar guías de conservación asociadas a tipos de licor.| 5                  | Didier Meza   | In-Progress |      
| US026        | Consultar guía de conservación desde el inventario      | US026T001   | Crear vista de consulta de guía  | Implementar una sección en la interfaz de inventario donde el usuario pueda consultar las guías de conservación disponibles.| 6                  | Anaely Loarte | In-Progress | 
| US027        | Generar reporte de pérdidas por tipo de baja            | US027T001   | Crear formulario de generación de reportes  | Diseñar un componente que permita generar reportes personalizados de pérdidas por tipo de baja, con exportación a PDF o Excel.| 5                  | Matias Diaz   | Done        |
| US028        | Visualizar resumen económico de pérdidas                | US028T001   | Crear panel de resumen de pérdidas  | Implementar una sección con métricas y gráficos que muestren el resumen de pérdidas económicas registradas.| 4                  | Matias Diaz   | Done        |
| US033        | Crear zonas de almacenamiento dentro del local          | US033T001   | Crear formulario de zonas de almacenamiento  | Diseñar un componente para registrar y visualizar las zonas internas de almacenamiento con imágenes referenciales.| 6                  | Matias Diaz   | Done        |
| US034        | Asignar productos a una zona específica                 | US034T001   | Implementar método de asignación de productos  | Desarrollar una funcionalidad que permita mover productos entre zonas de almacenamiento mediante un menú de selección.| 7                  | Matias Diaz     |Done |                                                                     
| US035        | Editar o eliminar una zona de almacenamiento            | US035T001   | Crear interfaz para editar y eliminar zonas  | Agregar opciones dentro de la sección de zonas para editar su información o eliminarlas del sistema.| 4                  | Giovany Torres     | Done        |
| US036        | Visualizar el mapa general de zonas y productos         | US036T001   | Crear vista de mapa interactivo | Implementar una vista con mapa que muestre la distribución general de zonas y productos en el local.| 8                  | Matias Diaz     | Done        |
| US037        | Visualizar resumen general en el panel de control       | US037T001   | Diseñar dashboard general  | Implementar un panel de control con tarjetas y gráficos para mostrar información resumida del sistema. | 4                  |Matias Diaz  | Done        |
| US038        | Ver alertas destacadas en el panel                      | US038T001   | Crear sección de alertas destacadas  | Agregar un módulo dentro del dashboard que muestre las alertas más relevantes o críticas.| 6                  | Didier Meza  | Done        |
| US043        | Consultar historial de guías emitidas                   | US043T001   | Crear lista de guías emitidas | Mostrar todas las guías creadas por el usuario con filtros por fecha o tipo de licor.| 5                  | Matias Diaz  | Done        |
| US044        | Cambiar estado de una guía a entregado                  | US044T001   | Implementar actualización de estado de guía | Desarrollar un método para actualizar el estado de una guía a “entregada” y reflejarlo visualmente en la interfaz.| 7                  | Giovany Torres  | Done        |
| US045        | Editar datos personales del perfil                      | US045T001   | Crear formulario de edición de perfil | Diseñar un formulario dentro de la sección de perfil que permita al usuario modificar su información personal. | 4                  | Giovany Torres   | Done        |
| US046        | Subir y actualizar foto de perfil                       | US046T001   | Implementar carga de imagen de perfil | Agregar funcionalidad para subir o cambiar la foto de perfil del usuario, integrando un servicio externo como Cloudinary. | 5                  | Giovany Torres   | Done        |
| US048        | Ver tipo de cuenta y plan actual                        | US048T001   | Mostrar detalles de plan de usuario | Crear una sección dentro del perfil que indique el tipo de cuenta y plan actual del usuario.| 4                  | Giovany Torres | Done        |
| US049        | Visualizar beneficios del Plan Premiumrcana a la fecha actual.| US049T001 | Crear vista de beneficios del plan premium | Diseñar un apartado con información visual y textual de los beneficios exclusivos del Plan Premium.| 8                  | Giovany Torres | Done        |
| US050        | Ver fecha de vencimiento del Plan Premium               | US050T001   | Implementar contador de vencimiento del plan | Crear un componente que muestre el tiempo restante de la suscripción premium del usuario con una barra de progreso o contador. | 6                  | Giovany Torres | Done        |


  
### 5.2.2.4. Development Evidence for Sprint Review.

En esta sección, se describen los principales avances de implementación realizados en este segundo sprint.

A continuación, se muestra una tabla que contiene la información sobre los commits hechos que contienen partes de las funcionalidades que debemos implementar para completar el primer sprint.

| Repository                           | Branch                      | Commit Id   | Commit Message                                                               | Commited On |
| ------------------------------------ | --------------------------- | ----------- | ---------------------------------------------------------------------------- | ----------- |
| Wineinventory/StockVin-Front-End-App | develop                     | 758bdf2     | chore: add domain-driven file structure.                                     | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | develop                     | 80feb21     | chore: add dependencies.                                                     | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/inventory           | 2b62152     | feat(warehouse): add json-server data.                                       | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/profile             | bac777a     | feat(profile): add profile page and components                               | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/i18n                | c36fa88     | feat(i18n): add language switcher component.                                 | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/inventory           | ce55380     | feat(warehouse): add inventory component.                                    | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/inventory           | 66d0aa9     | feat(warehouse): add product component.                                      | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/inventory           | f88e7bc     | feat(warehouse): add warehouse environment endpoints.                        | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/profile             | bac777a     | feat(profile): add profile page and components                               | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/authentication      | e19d7c2     | feat(authentication): add login page and components                          | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | develop                     | 9bfc008     | feat(public): add side navigation bar routing                                | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/dashboard           | 44a318c     | feat(analytics-and-reporting): update side navigation bar sections           | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/alerts              | a45f12e     | feat(alerts): add alerts component.                                          | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/order               | 7c500f7     | feat(orders): add distribution                                               | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/report              | 3c08d09     | feat(report-create): add section of report create                            | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/report              | 14425ddb    | feat(care-guide): add compontents for the section and form of care guides    | 06/10/2025  |
| Wineinventory/StockVin-Front-End-App | feature/order               | 96e99b3     | feat(orders): update orders.routes                                           | 06/10/2025  |

### 5.2.2.5. Execution Evidence for Sprint Review.


#### Landing Page

<p align="center">
  <img src="../img/Chapter V/review 1.PNG"/>
</p>


<p align="center">
  <img src="../img/Chapter V/review 2.PNG"/>
</p>


<p align="center">
  <img src="../img/Chapter V/review 3.PNG"/>
</p>


<p align="center">
  <img src="../img/Chapter V/review 4.PNG"/>
</p>

<p align="center">
  <img src="../img/Chapter V/review 5.PNG"/>
</p>


<p align="center">
    <img src="../img/Chapter V/review 6.PNG">
</p>

#### FronEnd:

* Interfaz de Sign-in Sign-Up:

<p align="center">
  <img src="../img/Chapter V/ev1.jpg"/>
</p>


<p align="center">
  <img src="../img/Chapter V/ev2.jpg"/>
</p>

* Sidevar de interfaces del FrontEnd
<p align="center">
  <img src="../img/Chapter V/ev3.jpg"/>
</p>

* Interfaz de Home

<p align="center">
  <img src="../img/Chapter V/ev4.jpg"/>
</p>

* Interfaz de Orders

<p align="center">
  <img src="../img/Chapter V/ev5.jpg"/>
</p>

* Interfaz de New-Orders

<p align="center">
    <img src="../img/Chapter V/ev6.jpg">
</p>


* Interfaz de Inventory

<p align="center">
  <img src="../img/Chapter V/ev7.jpg"/>
</p>


* Interfaz de New-Inventory

<p align="center">
  <img src="../img/Chapter V/ev8.jpg"/>
</p>

* Interfaz de NewProduct Output en Inventory

<p align="center">
    <img src="../img/Chapter V/ev9.jpg">
</p>

* Interfaz de Reports

<p align="center">
  <img src="../img/Chapter V/ev10.jpg"/>
</p>

* Interfaz de New-Reports

<p align="center">
  <img src="../img/Chapter V/ev11.jpg"/>
</p>

* Interfaz de New Care Guiode en Reports

<p align="center">
    <img src="../img/Chapter V/ev13.jpg">
</p>

* Interfaz de Alerts
<p align="center">
    <img src="../img/Chapter V/ev14.jpg">
</p>

* Interfaz de Settings

<p align="center">
    <img src="../img/Chapter V/ev15.jpg">
</p>

* Interfaz Edit Profile 

<p align="center">
    <img src="../img/Chapter V/ev16.jpg">
</p>





### 5.2.2.6. Services Documentation Evidence for Sprint Review.

<table border="1" cellpadding="8" cellspacing="0" style="border-collapse:collapse; width:100%; font-family:Arial, sans-serif;">
  <thead>
    <tr style="background:#f2f2f2;">
      <th>Endpoint</th>
      <th>Acción</th>
      <th>Verbo HTTP</th>
      <th>Descripción</th>
      <th>Sintaxis</th>
      <th>Ejemplo de Response</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/users</td>
      <td>Gestionar usuarios del sistema</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>Operaciones CRUD para usuarios administradores, distribuidores y productores</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"number","username":"string",<br>"password":"string","email":"string",<br>"role":"string","profileId":"number",<br>"createdAt":"string","updatedAt":"string","isActive":"boolean"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":1,"username":"admin",<br>"password":"******","email":"admin@example.com",<br>"role":"admin","profileId":10,<br>"createdAt":"2025-05-01T12:00:00Z","updatedAt":"2025-05-10T09:30:00Z","isActive":true}</div>
      </td>
    </tr>
    <tr>
      <td>/products</td>
      <td>Gestionar productos básicos</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>Operaciones CRUD para productos como vinos, rones, piscos</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"name":"string","type":"string",<br>"description":"string","imageUrl":"string",<br>"id":"string"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"p1001","name":"Cabernet Sauvignon",<br>"type":"vino","description":"Vino tinto seco",<br>"imageUrl":"https://example.com/images/cabernet.png"}</div>
      </td>
    </tr>
    <tr>
      <td>/catalog</td>
      <td>Gestionar catálogo de vinos</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>Operaciones CRUD para el catálogo completo de vinos con detalles específicos</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"string","name":"string",<br>"varietal":"string","vintage":"number",<br>"origin":"string","price":"number","imageUrl":"string",<br>"tastingNotes":"string"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"c2001","name":"Reserva Especial",<br>"varietal":"Cabernet Sauvignon","vintage":2018,<br>"origin":"Perú","price":120.5,"imageUrl":"https://example.com/images/reserva.png",<br>"tastingNotes":"Frutos rojos y roble"}</div>
      </td>
    </tr>
    <tr>
      <td>/inventory</td>
      <td>Gestionar inventario</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>Operaciones CRUD para el inventario con stock, fechas de expiración y ubicaciones</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"string","name":"string",<br>"type":"string","expirationDate":"string",<br>"currentStock":"number","minStockLevel":"number",<br>"price":"number","location":"string","imageUrl":"string"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"inv3001","name":"Cabernet",<br>"type":"vino","expirationDate":"2028-12-31",<br>"currentStock":50,"minStockLevel":10,<br>"price":120.0,"location":"Almacén A","imageUrl":"https://example.com/images/stock_cab.png"}</div>
      </td>
    </tr>
    <tr>
      <td>/orders</td>
      <td>Gestionar órdenes de venta</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>Operaciones CRUD para órdenes de clientes con items, cantidades y totales</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"string","code":"string",<br>"customerName":"string","customerEmail":"string",<br>"status":"string","createdAt":"string","expectedDelivery":"string",<br>"notes":"string","items":"array","subtotal":"number",<br>"tax":"number","total":"number"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"o4001","code":"ORD-0001",<br>"customerName":"Bodega El Sol","customerEmail":"ventas@el-sol.com",<br>"status":"Pendiente","createdAt":"2025-06-01T10:00:00Z","expectedDelivery":"2025-06-05",<br>"notes":"Entregar en la mañana","items":[{"productId":"p1001","quantity":10,"price":120}],<br>"subtotal":1200,"tax":216,"total":1416}</div>
      </td>
    </tr>
    <tr>
      <td>/purchase-orders</td>
      <td>Gestionar órdenes de compra</td>
      <td>GET, POST, PUT, DELETE</td>
      <td>Operaciones CRUD para órdenes de compra a proveedores</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"number","date":"object",<br>"status":"string","buyer":"object","supplier":"object",<br>"items":"array","totalAmount":"number","totalItems":"number"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":5001,"date":"2025-06-01T09:00:00Z",<br>"status":"Pendiente","buyer":{"id":1,"name":"Bodega Central"},"supplier":{"id":20,"name":"Distribuidora XYZ"},<br>"items":[{"productId":"p1001","quantity":100,"unitPrice":12}],<br>"totalAmount":1200,"totalItems":1}</div>
      </td>
    </tr>
    <tr>
      <td>/reporting</td>
      <td>Gestionar informes de productos</td>
      <td>GET, POST, DELETE</td>
      <td>Operaciones CRUD para informes de pérdidas y estadísticas de productos</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"number","products":"string",<br>"type":"string","price":"number","amount":"number",<br>"date":"string","lost":"number"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":7001,"products":"p1001",<br>"type":"pérdida","price":120,"amount":5,<br>"date":"2025-06-10","lost":600}</div>
      </td>
    </tr>
    <tr>
      <td>/careguides</td>
      <td>Gestionar guías de cuidado</td>
      <td>GET, POST, DELETE</td>
      <td>Operaciones CRUD para guías de cuidado y conservación de vinos</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"number","name":"string",<br>"type":"string","description":"string",<br>"imageUrl":"string"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":8001,"name":"Guía Conservación Vinos",<br>"type":"vino","description":"Conservar a 14°C y evitar luz directa",<br>"imageUrl":"https://example.com/images/guide.png"}</div>
      </td>
    </tr>
    <tr>
      <td>/subscriptionPlans</td>
      <td>Gestionar planes de suscripción</td>
      <td>GET, POST, PUT</td>
      <td>Operaciones CRUD para planes Free, Plus y Pro</td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"string","name":"string",<br>"price":"string","shortDescription":"string",<br>"benefits":"array"}</div>
      </td>
      <td>
        <div style="white-space:pre-wrap;font-family:monospace;margin:0;">{"id":"plan_free","name":"Free",<br>"price":"0","shortDescription":"Plan básico gratuito",<br>"benefits":["Acceso limitado","Soporte por correo"]}</div>
      </td>
    </tr>
  </tbody>
</table>

### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para asegurar un desarrollo estructurado y un despliegue eficiente, se organizaron los componentes del proyecto en dos partes principales: la Landing Page y el Frontend funcional. Cada uno fue alojado en su propio repositorio de GitHub, con procesos de desarrollo independientes y métodos de despliegue distintos. A continuación, se detalla el flujo de trabajo seguido en cada caso, junto con evidencia visual del resultado final.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue del sitio web estático.

#### Despliegue del Landing Page
Para el despliegue del sitio web estático, usamos GitHub Pages, una herramienta que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. A continuación, se detalla el proceso seguido para el despliegue del sitio web estático:

- Link al landing page: [WineInventory LandingPage](https://wineinventory-landing-page.web.app/)

* Partimos de la rama develop del repositorio del sitio web estático con todos los cambios realizados para el sprint actual.

* Luego, enviamos todos los cambios realizados en este segundo sprint desde la rama de desarrollo a una nueva rama de tipo release "release/landing-page-v2.0". Desde esa rama, se realizará un nuevo despliegue del sitio web estático.
<p align="center">
  <img src="../img/Chapter V/paso 3.PNG"/>
</p>

* A continuación, nos dirigimos a la sección de Configuración del repositorio (Settings). Luego, accedemos a la opción de páginas (Pages) dentro del bloque de secciones de código y automatización (Code and automation).
<p align="center">
  <img src="../img/Chapter V/Build pass2.PNG"/>
</p>

* Después, elegimos el tipo de origen para que despliegue desde una rama que escojamos. Luego, buscamos la rama de lanzamiento que hemos creado para realizar el despliegue de esta versión y guardamos la configuración.
<p align="center">
  <img src="../img/Chapter V/Build pass.PNG"/>
</p>

* A continuación, aparecerá el enlace público generado para poder acceder al sitio web estático desplegado.
<p align="center">
  <img src="../img/Chapter V/deploy ev1.PNG"/>
</p>

* Finalmente, se accede el sitio web desplegado gracias a GitHub Pages y se adjunta la siguiente evidencia.
<p align="center">
  <img src="../img/Chapter V/paso 5.PNG"/>
</p>

#### Despliegue del Frontend
Para el despliegue de esta aplicación, se utilizó Firebase Hosting, una plataforma que permite alojar aplicaciones web de manera sencilla y eficiente.
Para el paso inicial, nos basamos en la configuración inicial de los repositorios de los productos a desarrollar (Sección 5.1.4.). A continuación, se explica del proceso de despliegue de la aplicación Frontend:

Link a la aplicación: [WineInventory Frontend](https://wineinventory-front-end.web.app)

* Partimos de la rama develop del repositorio de la aplicación frontend con todos los cambios realizados para el sprint actual.

* Luego, enviamos todos los cambios realizados en este segundo sprint desde la rama de desarrollo a una nueva rama de tipo release "release/front-end-app-v1.0". Desde esa rama, se realizará el primer despliegue de la aplicación front-end.

* A continuación, se instaló Firebase CLI, lo que permite gestionar y desplegar aplicaciones en Firebase. Luego, se inicializó el proyecto de Firebase en la carpeta del Frontend. Inmediatamente, ejecutamos en la consola el comando "firebase --version" para verificar que se haya instalado correctamente.
<p align="center">
  <img src="../img/Chapter V/pas1 front.PNG"/>
</p>

* Luego, ejecutamos el comando npm run build en la consola de nuestro proyecto, este comando creara una carpeta llamada Dist que contiene todo nuestro proyecto.

<p align="center">
  <img src="../img/Chapter V/pas2 front.PNG" alt="Execution of npm run build command">

<p align="center">
  <img src="../img/Chapter V/pas3 front.PNG" alt="Creation of the dist folder">

* Luego, ingresamos a la página web Firebase e ingresamos con nuestra cuenta de Google y vamos a la consola, creamos un nuevo proyecto con el nombre de nuestra aplicación.

<p align="center">
  <img src="../img/Chapter V/pas4 front.PNG">

* Después, nos ubicamos en el apartado de hosting.
<p align="center">
  <img src="../img/Chapter V/pas5 front.PNG">

* Y se procede a agregar un nuevo sitio web, colocamos el nombre de nuestro sitio y damos clic en Agregar sitio.
<p align="center">
  <img src="../img/Chapter V/pas6 front.PNG">

* Regresamos a WebStorm y en la consola ingresamos el comando "firebase login" y decimos NO. Luego, nos solicitará que ingresemos con nuestra cuenta de Google con la que creamos el proyecto.
<p align="center">
  <img src="../img/Chapter V/pas66 front.PNG"> 


* Inmediatamente, inicializamos Firebase con el comando "firebase init".
<p align="center">
  <img src="../img/Chapter V/pas7 front.PNG"> 



* A continuación, ingresamos el comando firebase deploy, pero antes de eso ingresamos el comando npm run build para construir una nueva versión del proyecto con todos los últimos cambios.
<p align="center">
  <img src="../img/Chapter V/pas8 front.PNG"> 

* Finalmente, tras la ejecución del despliegue del Frontend a través de Firebase, se muestra la evidencia del despliegue:
<p align="center">
  <img src="../img/Chapter V/pas9 front.PNG"/>
</p>


### 5.2.2.8. Team Collaboration Insights during Sprint.

En esta sección se detalla cómo se llevaron a cabo las actividades de implementación durante el sprint, así como la participación de cada miembro del equipo. Para este sprint, el equipo se organizó en torno a los dos principales productos: Landing Page y Web Application (Frontend). Cada integrante asumió responsabilidades específicas en uno o más de estos componentes, trabajando mediante ramas individuales y siguiendo una estrategia de integración continua.

El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:

<p align="center">
  <img src="../img/Chapter V/deployev 1.jpeg"/>
</p>

A continuacion de detallara el trabajo que realizo cada integrante del equipo:
- El integrante Didier Meza fue responsable de implementar la sección de alertas en el Frontend, asegurando su correcto funcionamiento e integración con el resto de la aplicación.
- La integrante Matias Diaz implementó correcciones en el landing page. En el Frontend se encargo de realizar la autenticacion,como tambien implementó la seccion de reportes en el Frontend, dentro de esta seccion agrego las guias de conservacion. 
- El integrante Anaely Burga fue responsable de implementar la seccion de inventarios en el Frontend, se aseguro el correcto funcionamiento. 
- El integrante Giovany Torres implementó la seccion de ordenes en el Frontend, asegurandose su correcto funcionamiento, y tambien implemento el perfil del usuario y sus descripcion de este.

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="../img/Chapter V/sprint-2 ev1.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el landing page:
<p align="center">
  <img src="../img/Chapter V/sprint-2 ev2.PNG"/>
</p>

Commits de los integrantes en el Frontend:
<p align="center">
  <img src="../img/Chapter V/sprint-2 ev1F.PNG"/>
</p>

Grafico de los push y merge realizados por el equipo en el Frontend: 

<p align="center">
  <img src="../img/Chapter V/sprint-2 ev2F.PNG"/>
</p>

### 5.2.3. Sprint 3 ###

### 5.2.3.1. Sprint Planning 3 ###

En la siguiente tabla se ofrece información referente a la planificación del tercer sprint del proyecto. Para este sprint se estableció un objetivo que abarca los componentes del sitio web estático, la aplicación front-end y la aplicación back-end. Una parte de dicho objetivo se enfoca en implementar mejoras visuales en el sitio web estático, mientras que la segunda parte se orienta al desarrollo y despliegue de la versión mejorada de la aplicación front-end de StockVin.

| Sprint #                                     | Sprint 3                                               |
|----------------------------------------------|--------------------------------------------------------|
| <b> Sprint planning Background </b>          | --                                                     |
| Date                                         | 2025/10/25                                             |
| Time                                         | 15:10 PM                                               |
| Location                                     | Reunión virtual por la plataforma de Meet |
| Prepared By                                  | Torres Apolinario, Giovany Smith                       |
| Attendees                                    | Diaz Quispe, Matias Sebastian / Torres Apolinario, Giovany Smith / Burga Loarte, Anaely Zarely / Meza Solòrzano, Didier Sebastiàn |
| Sprint 2 Review Summary                      | During the previous sprint, the team developed the initial version of the Landing Page, incorporating the essential sections and styles such as Benefits, Plans, and Startup Information. |
| Sprint 2 Retrospective Summary               | The principal area the team has to improve is having more communication between the members to let each others know how is the progress is going for each member. Now, the plan for next sprint is to work more organized so each member know what to do.|
| <b> Sprint Goal & User Stories </b>          | --                                                     |
| Sprint 3 Goal                                | <b> Our primary objective </b> is to deliver comprehensive information, relevant content, and a product video, complemented by an introductory presentation of the team responsible for its development.<br> <b>We consider this strategy </b> oan effective means of ensuring accessibility to the landing page across multiple screen sizes and languages, thereby reaching a wider range of user segments and visitors.This hypothesis will be validated once our target users and visitors access the landing page through different devices.<br><br> <b> Our focus </b> for this stage is the implementation and deployment of the first functional version of the Front-End application, incorporating key modules such as digital inventory, a dashboard interface, product registration, alert management, order processing, and seamless navigation between sections. We believe this release provides an integrated initial view of the core functionalities the application aims to offer to its intended user base. <br> <b> This assumption will be confirmed when </b> our target users register within the application and actively engage with essential features, including warehouse management and the product order module. |
| Sprint 3 Velocity                            | 100                                                    |
| Sum of Story Points                          | 156                                                    |

### 5.2.3.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este tercer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada las principales secciones que presenta el Front-End Web Application y en su contraparte para el Back-End Application. Para esto, hemos definido las siguientes secciones: Inventarios, Productos, Cuenta de Usuario, Reportes, Ordenes de compra y Alertas.

| Team Member                        | GitHub Username | Alerts and Notifications | Analytics and Reporting | Authentication | Inventory Management  | Order Operation and Monitoring |Profile Management |
|------------------------------------|-----------------|--------------------------|-------------------------|----------------|-----------------------|--------------------------------|-------------------|
| Diaz Quispe, Matias Sebastian      | equinox-1092    |                          |         L               | L              |                       |                                |  L                |
| Torres Apolinario, Giovany Smith   | Giovany7x       |                          |                         |                |                       |    L                           |                   |
| Burga Loarte Anaely Zarely         | userxx1000      |                          |                         |                | L                     |                                |                   |
| Meza Solòrzano, Didier Sebastiàn   | Didier04x       |    L                     |                         |                |                       |                                |                   |

### 5.2.3.3. Sprint Backlog 3 ###

Como se mencionó previamente en el planeamiento del sprint número 3, el objetivo del mismo es concluir con el sitio web estatico integrando secciones que informen a los visitantes sobre los desarrolladores del producto y sobre el producto en si; implementar caracteristicas relacionadas con la realizacion de ordenes de compra en la aplicacion web e implementar endpoints en la aplicacion backend necesarios para la implementacion de caracteristicas fundamentales en la aplicacion web.

Luego de definir el objetivo del sprint, se identificaron las historias de usuario útiles para este sprint. A continuación, se dividió cada historia de usuario en tareas relacionadas a la implementación y cumplimiento de dicha historia. Para ello, se utilizó la aplicación _Trello_ que nos ayuda a gestionar el progreso del sprint. 

[https://trello.com/b/AYR7UijI/stockvin-sprintbacklog-3](https://trello.com/b/AYR7UijI/stockvin-sprintbacklog-3)

<p align="center">
  <img src="../img/Chapter V/Sprint-3-backlog.PNG" 
  alt="Sprint goal y Stories del Sprint #3"/>

  <p align="center">
  <img src="../img/Chapter V/Sprint-3-backlog-2.PNG" 
  alt="Sprint Backlog 3 en desarrollo"/>

  A continuación, se presenta la tabla con las tareas necesarias para completar satisfactoriamente este segundo sprint. Además, se asignó un miembro del equipo a cada tarea a desarrollar y el estado de cada tarea.

| Sprint 3     | Sprint Backlog 3                                       |                |                                                                               |                                                                                                                                                              |                    |                 |        |
| ------------ | -------------------------------------------------------- | -------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ | --------------- | ------ |
| User Stories |                                                          | Work Item/Task |                                                                               |                                                                                                                                                              |                    |                 |        |
| Id           | Title                                                    | Id             | Title                                                                         | Description                                                                                                                                                  | Estimation (Hours) | Assigned to     | Status |
| US059        | Generar orden de compra                                  | US059T001      | Crear formulario de nueva orden de compra                                     | Diseño e implementación del formulario para crear manualmente una orden de compra.                                                                           | 4                  | Giovany Torres  | Done   |
|              |                                                          | US059T002      | Validar productos en orden                                                    | Validación para evitar el envío de órdenes                                                                                                                   | 3                  | Giovany Torres  | Done   |
|              |                                                          | US059T003      | Implementar un snackbar para las notificaciones                               | Diseño e implementación de un componente snackbar para las notificaciones de órdenes creadas.                                                                | 3                  | Giovany Torres  | Done   |
|              |                                                          | US059T004      | Conexión con proveedor                                                        | Implementar la lógica para enviar la orden generada al proveedor correspondiente.                                                                            | 3                  | Giovany Torres  | Done   |
| US060        | Visualizar estado de la orden de compra                  | US060T001      | Crear vista de seguimiento de órdenes                                         | Vista para mostrar las órdenes realizadas por el usuario.                                                                                                    | 4                  | Giovany Torres  | Done   |
| US061        | Notificaciones sobre el estado de una orden              | US061T001      | Configurar notificación inicial                                               | Enviar notificación cuando se crea una orden de compra.                                                                                                      | 3                  | Giovany Torres  | Done   |
|              |                                                          | US061T003      | Crear notificaciones de orden aceptada o rechazada                            | Crear funcionalidad para enviar y mostrar notificación al dueño cuando la orden sea aceptada.                                                                | 4                  | Giovany Torres  | Done   |
| US062        | Coordinar fecha de entrega                               | US062T001      | Implementar función de propuesta de horario de entrega                        | Funcionalidad para que el proveedor proponga un horario al cliente.                                                                                          | 4                  | Giovany Torres  | Done   |
|              |                                                          | US062T002      | Crear función para aceptar/rechazar propuesta de horario                      | Implementar funcionalidad para que el cliente pueda aceptar o rechazar la propuesta del proveedor.                                                           | 3                  | Giovany Torres  | Done   |
|              |                                                          | US062T003      | Guardar fecha acordada en orden                                               | Persistencia de la fecha y hora confirmada entre ambas partes en la orden correspondiente.                                                                   | 3                  | Giovany Torres  | Done   |
| US056        | Creación de catálogo                                     | US056T001      | Crear formulario de catálogo                                                  | Diseño e implementación del formulario para crear un catálogo manualmente.                                                                                   | 4                  | Anaely Burga    | Done   |
|              |                                                          | US056T002      | Validar no publicación de catálogo vacío\|                                    | Implementar validación para impedir publicar catálogo sin productos.                                                                                         | 2                  | Anaely Burga    | Done   |
|              |                                                          | US056T003      | Implementar funcionalidad para publicar catálogo con productos                | Implementación de funcionalidad para publicar catálogo con productos visibles para clientes.                                                                 | 3                  | Anaely Burga    | Done   |
| US057        | Agregar producto al catálogo                             | US057T001      | Implementar funcionalidad para añadir producto con información completa       | Crear formulario y funcionalidad para agregar producto con datos completos al catálogo.                                                                      | 3                  | Anaely Burga    | Done   |
|              |                                                          | US057T002      | Implementar validación para campos obligatorios                               | Implementar validación para impedir añadir producto con campos incompletos o vacíos.                                                                         | 3                  | Anaely Burga    | Done   |
|              |                                                          | US057T003      | Crear función para agregar producto desde inventario                          | Crear funcionalidad para agregar productos ya existentes en inventario directamente al catálogo                                                              | 3                  | Anaely Burga    | Done   |
| US058        | Eliminacion de producto del catalogo                     | US058T001      | Crear funcionalidad para detectar productos sin stock y marcar en catálogo    | Agregar una funcionalidad que permita identificar productos sin stock y marcarlos como no disponibles en catálogo.                                           | 5                  | Anaely Burga    | Done   |
|              |                                                          | US058T002      | Crear funcionalidad para eliminar producto manualmente del catálogo           | Funcionalidad para que proveedor elimine manualmente un producto del catálogo sin eliminarlo del inventario.                                                 | 5                  | Anaely Burga    | Done   |
| US063        | Actualizar estado de la orden de venta                   | US063T001      | Implementar funcionalidad para actualizar el estado de una orden de venta.    | Crear una funcionalidad que permita al usuario cambiar el estado de una orden de venta a "Aceptado", "En preparación", "Enviando", "Entregado" o "Cancelado" | 2                  | Giovany Torres  | Done   |
|              |                                                          | US063T002      | Agregar funcionalidad para enviar notificaciones por orden cancelada          | Implementar una funcionalidad que envíe una notificación al dueño de licorería si su orden de compra se canceló por el proveedor.                            | 3                  | Giovany Torres  | Done   |
| US064        | Contabilizar productos en el inventario                  | US064T001      | Actualizar stock automáticamente al recibir pedido                            | Agregar método para incrementar stock en almacén digital al confirmar entrega.                                                                               | 4                  | Anaely Burga    | Done   |
|              |                                                          | US064T002      | Crear producto nuevo en inventario                                            | Implementar método para agregar nuevos productos recibidos y no existentes en almacén digital.                                                               | 4                  | Anaely Burga    | Done   |
| US020        | Detallar el estado de salida de productos                | US020T001      | Crear métodos para registrar el motivo de salida de productos                 | Crear un método para permitir al dueño de licorería registrar una salida de producto como venta                                                              | 3                  | Anaely Burga    | Done   |
| US021        | Configurar alertas de reposición                         | US021T001      | Crear función para definir umbral de stock mínimo                             | Crear un método para permitir que el dueño establezca un nivel mínimo por producto                                                                           | 3                  | Didier Meza     | Done   |
|              |                                                          | US021T002      | Crear una función para generar alerta cuando stock esté por debajo del mínimo | Automatizar alerta al alcanzar o pasar el umbral definido                                                                                                    | 3                  | Didier Meza     | Done   |
| US022        | Alertas por próximo vencimiento                          | US022T001      | Configurar margen de vencimiento                                              | Implementar opción para definir días previos al vencimiento para generar alerta                                                                              | 3                  | Didier Meza     | Done   |
|              |                                                          | US022T002      | Crear un componente para visualizar productos próximos a vencer               | Mostrar claramente los productos en riesgo de vencimiento próximo en un componente "card"                                                                    | 3                  | Didier Meza     | Done   |
| US039        | Crear un plan de reabastecimiento                        | US039T001      | Implementar una opción para crear plan de reabastecimiento para licorería     | Crear un formulario para ingresar datos de plan (cliente, productos, frecuencia)                                                                             | 4                  | Matias Diaz     | Done   |
|              |                                                          | US039T002      | Implementar un método para validar campos obligatorios                        | Añadir validaciones para asegurar datos completos antes de guardar                                                                                           | 2                  | Matias Diaz     | Done   |
| US040        | Editar plan de reabastecimiento existente                | US040T001      | Crear una opción para editar un plan existente                                | Permitir edición de datos en planes ya creados                                                                                                               | 3                  | Matias Diaz     | Done   |
|              |                                                          | US040T002      | Crear botón para cancelar edición sin guardar                                 | Implementar botón de cancelación que preserve los datos originales                                                                                           | 2                  | Matias Diaz     | Done   |
| US028        | Visualizar resumen económico de pérdidas                 | US028T001      | Crear una función para mostrar valor total de pérdidas                        | Calcular y mostrar el total monetario de pérdidas según precio de compra                                                                                     | 4                  | Didier Meza     | Done   |
|              |                                                          | US030T002      | Aplicar desglose por tipo de pérdida                                          | Mostrar subtotales por tipo: merma, consumo interno, donación                                                                                                | 3                  | Didier Meza     | Done   |
| US030        | Asociar productos comprados a inventario                 | US028T001      | Asociar productos de factura al inventario                                    | Registrar productos de una factura directamente en el stock                                                                                                  | 4                  | Matias Diaz     | Done   |
|              |                                                          | US030T002      | Agregar validaciones para evitar duplicados al ingresar productos             | Verificar existencia de producto y sumar unidades en lugar de duplicar                                                                                       | 3                  | Matias Diaz     | Done   |
| US031        | Registro de pedidos a proveedores                        | US031T001      | Crear una vista del historial de compras por proveedor                        | Mostrar pedidos pasados al seleccionar un proveedor                                                                                                          | 3                  | Giovany Torres  | Done   |
|              |                                                          | US031T002      | Filtrar historial por producto                                                | Implementar filtro de búsqueda por nombre de producto en historial                                                                                           | 3                  | Giovany Torres  | Done   |
|              |                                                          | US066T002      | Implementar lógica para seleccionar plan premium                              | Activar plan premium en el sistema al usuario luego del pago                                                                                                 | 4                  | Giovany Torres  | Done   |
|              |                                                          | US066T003      | Integrar visualización con flujo de pago PayPal                               | Asegurar coherencia entre información mostrada y el proceso de pago                                                                                          | 3                  | Giovany torres  | Done   |
| TS006        | Registrar productos en el inventario                     | TS006T001      | Crear modelo de producto                                                      | Definir esquema del producto: nombre, cantidad, tipo, fecha de vencimiento                                                                                   | 2                  | Anaely Burga    | Done   |
|              |                                                          | TS006T002      | Implementar POST para registrar productos en el inventario                    | Crear endpoint para registrar productos en inventario                                                                                                        | 3                  | Matias Diaz     | Done   |
|              |                                                          | TS006T003      | Validar duplicados y datos incompletos                                        | Controlar duplicación y campos requeridos                                                                                                                    | 2                  | Matias Diaz     | Done   |
| TS007        | Consultar inventario                                     | TS007T001      | Implementar GET para devolver un inventario                                   | Crear endpoint para devolver lista de productos del inventario                                                                                               | 2                  | Anaely Burga    | Done   |
|              |                                                          | TS007T002      | Crear función para manejar inventario vacío                                   | Crear una funcionalidad para devolver lista vacía con código 200 si no hay productos                                                                         | 1                  | Anaely Burga    | Done   |
| TS008        | Configurar alertas de reposición                         | TS008T001      | Crear modelo de alerta                                                        | Definir esquema para alertas (producto, umbral)                                                                                                              | 2                  | Didier Meza     | Done   |
|              |                                                          | TS008T002      | Implementar consulta POST para alertas                                        | Crear endpoint para guardar configuraciones de alerta                                                                                                        | 2                  | Didier Meza     | Done   |
| TS011        | Registrar guía de conservación                           | TS011T001      | Crear modelo de guía de conservación                                          | Definir estructura de guía (producto, condiciones de conservación, etc.)                                                                                     | 2                  | Matias Diaz     | Done   |
|              |                                                          | TS011T002      | Implementar consulta POST para registrar guías                                | Crear endpoint para registrar una nueva guía de conservación.                                                                                                | 2                  | Matias Diaz     | Done   |
|              |                                                          | TS011T003      | Validar campos obligatorios en las guías                                      | Manejar errores por datos incompletos                                                                                                                        | 1                  | Matias Diaz     | Done   |
| TS001        | Endpoint para registrar nuevo usuario                    | TS001T001      | Crear modelo y validaciones de usuario                                        | Definir esquema del usuario (nombre, correo, contraseña, rol) y validar campos requeridos                                                                    | 3                  | Matias Diaz     | Done   |
|              |                                                          | TS001T002      | Implementar consulta POST para registro de usuarios                           | Crear endpoint para registrar nuevos usuarios en la plataforma, creando su respectivo perfil                                                                 | 3                  | Matias Diaz     | Done   |
|              |                                                          | TS001T003      | Manejar errores por datos incompletos y duplicados                            | Incluir manejo de errores 400 (campos faltantes) y 409 (correo existente)                                                                                    | 2                  | Matias Diaz     | Done   |
| TS002        | Endpoint para iniciar sesión                             | TS002T001      | Implementar lógica de autenticación                                           | Verificar correo y contraseña del usuario                                                                                                                    | 2                  | Matias Diaz     | Done   |
|              |                                                          | TS002T002      | Implementar método para generar y devolver token JWT                          | Configurar JWT y retornarlo con datos del usuario                                                                                                            | 2                  | Matias Diaz     | Done   |
|              |                                                          | TS002T003      | Crear métodos para validar cuenta activa del usuario                          | Verificar si el usuario está activo antes de permitir acceso                                                                                                 | 1                  | Matias Diaz     | Done   |
| TS012        | Generar reporte de pérdidas                              | TS012T001      | Implementar lógica para detectar pérdidas                                     | Detectar productos vencidos, merma u otros criterios de pérdida                                                                                              | 3                  | Matias Diaz     | Done   |
|              |                                                          | TS012T002      | Implementar consulta GET para obtener perdidas                                | Crear endpoint que devuelva las pérdidas encontradas                                                                                                         | 2                  | Matias Diaz     | Done   |
| TS014        | Endpoint para registrar una nueva zona de almacenamiento | TS014T001      | Crear modelo y migración para zona de almacenamiento                          | Definir estructura de datos para zonas (nombre, descripción) y crear migración en base de datos                                                              | 3                  | Anaely Burga    | Done   |
|              |                                                          | TS014T002      | Implementar endpoint POST para registrar zonas                                | Crear lógica de controlador para registrar nueva zona de almacenamiento                                                                                      | 4                  | Anaely Burga    | Done   |
|              |                                                          | TS014T003      | Validar datos de entrada y verificar duplicados                               | Verificar que no falten campos obligatorios y que la zona no exista ya en BD                                                                                 | 2                  | Anaely Burga    | Done   |
| TS015        | Endpoint para obtener resumen del panel del usuario      | TS015T001      | Diseñar DTO/respuesta para panel del usuario                                  | Definir estructura de respuesta del panel (alertas, inventario, movimientos)                                                                                 | 2                  | Didier Meza     | Done   |
|              |                                                          | TS015T002      | Implementar endpoint para obtener panel de usuario                            | Consultar datos relevantes y retornarlos en el formato definido y por tipo de rol de usuario (dueño de licorería o proveedor)                                | 4                  | Didier Meza     | Done   |
|              |                                                          | TS015T003      | Añadir middleware de autenticación                                            | Asegurar que solo usuarios autenticados accedan al panel                                                                                                     | 1                  | Didier Meza     | Done   |
| TS021        | Endpoint para generar una orden de compra                | TS021T001      | Diseñar estructura de orden de compra                                         | Definir modelo con sus relaciones (productos, cantidades, usuario)                                                                                           | 3                  | Matias Diaz     | Done   |
|              |                                                          | TS021T002      | Implementar endpoint POST para pedidos                                        | Crear lógica para registrar orden de compra y manejar errores                                                                                                | 4                  | Giovany torres  | Done   |
|              |                                                          | TS021T003      | Validar productos en orden                                                    | Verificar que la orden no esté vacía                                                                                                                         | 1                  | Giovany torres  | Done   |
| TS023        | Endpoint para actualizar estados de los pedidos          | TS023T001      | Definir lógica de transición de estados                                       | Permitir solo cambios válidos de estado (p. ej., pendiente → enviado)                                                                                        | 2                  | Giovany torres  | Done   |
|              |                                                          | TS023T002      | Implementar endpoint PUT para pedidos                                         | Crear lógica de actualización de estado y respuesta adecuada                                                                                                 | 3                  | Giovany torres  | Done   |
|              |                                                          | TS023T003      | Agregar validaciones de negocio (estado entregado)                            | Bloquear cambios a pedidos entregados                                                                                                                        | 1                  | Giovany torres  | Done   |


### 5.2.3.4. Development Evidence for Sprint Review ###

En esta sección, se describen los principales avances de implementación realizados en este tercer sprint.

A continuación, se muestra una tabla que contiene la información sobre los _commits_ hechos que contienen partes de las funcionalidades que debemos implementar para completar el tercer sprint.

| Repository                                 | Branch                   | Commit Id | Commit Message                                                                        | Commited On  |
| ------------------------------------------ | ------------------------ | --------- | ------------------------------------------------------------------------------------- | ------------ |
| StockVin/WineInventory-backend-application | inventories              | 2b40dbb   | feat: inventory.                                                                      | NOV 06, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | e429561   | feat(order): add controller orders.                                                   | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | 5b8ee64   | feat(order): update repositories orders.                                              | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | 8c72d1b   | feat(order): update query services orders.                                            | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | bc8fdbd   | feat(order): update entities orders.                                                  | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | c294c15   | feat(order): update command services orders.                                          | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | 4627a57   | feat(order): update aggregates orders.                                                | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | purchase-orders          | b6e56e1   | feat(order): update assembler orders.                                                 | NOV 07, 2025 |
| StockVin/WineInventory-backend-application | care-guides              | 0ab1890   | feat(care-guides): parameterize active alert lookup state for JPA compatibility.      | NOV 08, 2025 |
| StockVin/WineInventory-backend-application | alerts                   | ---   | feat(alerts-and-notifications): add external service in inventory management context. | NOV 20, 2025 |
| StockVin/WineInventory-backend-application | alerts                   | ---   | feat(alerts-and-notifications): add anti-corruption layer implementation.             | NOV 20, 2025 |
| StockVin/WineInventory-backend-application | alerts                   | ---   | feat(alerts): add alert commands.                                                     | NOV 20, 2025 |


### 5.2.3.5. Execution Evidence for Sprint Review ###
El objetivo de este sprint fue, mediante un trabajo colaborativo entre todos los integrantes del equipo, realizar la actualización del landing page, del frontend y la primera version del backend. Esta tarea incluyó la mejora de aspectos visuales y funcionales, así como la integración de los cambios en los repositorios correspondientes para su posterior despliegue.


#### **Landing Page**

**Video about the team**
<p align="center">
  <img src="https://i.imgur.com/Ek2vt1D.png"/>
</p>

<br>

**Video about the product**
<p align="center">
  <img src="https://i.imgur.com/via7j1p.png"/>
</p>

<br>

#### **Front End Application**

**Ordenes dueño**
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/Owners_orders.PNG?raw=true" alt="Órdenes del dueño" width="600"/>
</p>
<br>


**Ordesnes proveedor**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/orders_proovedor.PNG?raw=true" alt="Órdenes proveedor" width="600"/>
</p>
<br>

**Nueva orden**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/new_order.PNG?raw=true" alt="Nueva orden" width="600"/>
</p>
<br>



#### **Back End Application**
**Guias de conservacion**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/careguides.PNG?raw=true" alt="Guías de conservación" width="600"/>
</p>
<br>


**Order**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/Orders.PNG?raw=true" alt="Order" width="600"/>
</p>
<br>

**Product**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/inventory.PNG?raw=true" alt="Inventory" width="600"/>
</p>
<br>



**Alertas**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/Alerts.PNG?raw=true" alt="Alertas" width="600"/>
</p>
<br>


**Cuentas de usuario**

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/Accounts.PNG?raw=true" alt="Cuentas de usuario" width="600"/>
</p>
<br>

### 5.2.3.6. Services Documentation Evidence for Sprint Review ###

| Módulo      | Endpoint                                                                                          | Acción                                    | Verbo HTTP | Sintaxis                                       | Parámetros principales                                        | Enlace a Swagger                                              |
| ----------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------- | ---------- | ---------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                               | Obtener guía por ID                       | GET        | `/api/v1/care-guides/123`                      | `careGuideId`, `accountId`                                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                               | Actualizar guía                           | PUT        | `/api/v1/care-guides/123`                      | Body con nuevos campos                                        | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}`                                                               | Eliminar guía                             | DELETE     | `/api/v1/care-guides/123`                      | `careGuideId`                                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}/deallocations`                                                 | Desasignar guía                           | PUT        | `/api/v1/care-guides/123/deallocations`        | `careGuideId`                                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Care Guides | `/api/v1/care-guides/{careGuideId}/allocations/{productId}`                                       | Asignar guía a producto                   | PUT        | `/api/v1/care-guides/123/allocations/45`       | `careGuideId`, `productId`                                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| order    | `/api/v1/order/{productId}/care-guide`                                                           | Obtener guía por producto                 | GET        | `/api/v1/order/45/care-guide`               | `productId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| order    | `/api/v1/order/{productId}/exits`                                                                | Obtener salidas por producto              | GET        | `/api/v1/order/45/exits`                    | `productId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| order    | `/api/v1/order/{productId}`                                                                      | Obtener producto por ID                   | GET        | `/api/v1/order/45`                          | `productId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| order    | `/api/v1/order/{productId}`                                                                      | Actualizar producto                       | PUT        | `/api/v1/order/45`                          | Body con valores actualizados                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| order    | `/api/v1/order`                                                                                  | Crear producto                            | POST       | `/api/v1/order`                             | Body con nuevos campos                                        | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| order    | `/api/v1/order`                                                                                  | Obtener productos por perfil              | GET        | `/api/v1/order?profileId=10`                | `profileId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory`                                                                               | Obtener todos los almacenes               | GET        | `/api/v1/inventory`                           | —                                                             | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory`                                                                               | Crear un almacén                          | POST       | `/api/v1/inventory`                           | Body con datos del almacén                                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}`                                                                 | Obtener almacén por ID                    | GET        | `/api/v1/inventory/123`                       | `warehouseId`                                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}`                                                                 | Actualizar almacén                        | PUT        | `/api/v1/inventory/123`                       | Body actualizado + `warehouseId`                              | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}`                                                                 | Eliminar almacén                          | DELETE     | `/api/v1/inventory/123`                       | `warehouseId`                                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/inventories/product/{productId}`                                 | Agregar stock a producto                  | POST       | `/inventory/123/inventories/product/456`      | `expirationDate`, `quantity`                                  | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/inventories/product/{productId}/additions`                       | Añadir stock                              | PUT        | `.../additions`                                | `addedQuantity`, `stockExpirationDate`                        | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/inventories/{productId}/substractions`                           | Quitar stock                              | PUT        | `.../substractions`                            | `removedQuantity`, `expirationDate`                           | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/inventories/product/{productId}/moves`                           | Mover stock entre almacenes               | PUT        | `.../moves`                                    | `newWarehouseId`, `movedQuantity`, `movedStockExpirationDate` | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/inventories/product/{productId}/expiration-date/{expirationDate}`| Obtener inventario por fecha              | GET        | `/.../expiration-date/2025-06-22`              | `warehouseId`, `productId`, `expirationDate`                  | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/inventories/product/{productId}`                                 | Eliminar stock con fecha                  | DELETE     | `/.../product/456` (en body: `expirationDate`) | `warehouseId`, `productId`                                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/product-exits/{productId}`                                       | Registrar salida de producto              | POST       | `.../product-exits/456`                        | `expirationDate`, `quantityExited`, `exitReason`              | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/product-exits/{productId}`                                       | Obtener salidas por producto              | GET        | `.../product-exits/456`                        | `warehouseId`, `productId`                                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/product-exits`                                                   | Obtener salidas por almacén               | GET        | `/.../product-exits`                           | `warehouseId`                                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/order`                                                           | Obtener productos por almacén             | GET        | `/.../order`                                | `warehouseId`                                                 | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| inventory  | `/api/v1/inventory/{warehouseId}/order/provider/{providerId}`                                     | Obtener productos por proveedor y almacén | GET        | `/.../order/provider/789`                   | `warehouseId`, `providerId`                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Alerts      | `/api/v1/alerts/{alertId}`                                                                       | Obtener alerta por ID                     | GET        | `/api/v1/alerts/123`                           | `alertId`                                                     | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides/{careGuideId}`                                         | Obtener Care Guide por ID                 | GET        | `/accounts/1/care-guides/10`                   | `accountId`, `careGuideId`                                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides`                                                       | Obtener todos los Care Guides             | GET        | `/accounts/1/care-guides`                      | `accountId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides`                                                       | Crear Care Guide sin producto             | POST       | `/accounts/1/care-guides`                      | `accountId`, Body                                             | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/care-guides/product/{productId}`                                   | Crear Care Guide con producto             | POST       | `/accounts/1/care-guides/product/99`           | `accountId`, `productId`, Body                                | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/order`                                                             | Obtener productos por cuenta              | GET        | `/accounts/1/order`                         | `accountId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/inventory`                                                         | Obtener almacenes por cuenta              | GET        | `/accounts/1/inventory`                       | `accountId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |
| Accounts    | `/api/v1/accounts/{accountId}/alerts`                                                            | Obtener alertas por cuenta                | GET        | `/accounts/1/alerts`                           | `accountId`                                                   | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html) |


## **Ejemplos Detallados**


### Care Guides

#### Endpoint: Endpoint: `/api/v1/care-guides/{careGuideId}` – `GET`

- **Descripción:** Obtiene una guía de cuidado específica sin necesidad de que esté vinculada a un producto.
    
- **Parámetros:**
    
    - `careGuideId` (path)
    - `accountId` (path)
        
- **Ejemplo de llamada:**

	- GET /api/v1/care-guides/123
    
- **Respuesta (`200 Ok`):**
    
{
  "id": "123",
  "accountId": "456",
  "productId": "789",
  "title": "Guía de Almacenamiento",
  "summary": "Indicaciones para conservar el producto correctamente",
  "minTemp": 5,
  "maxTemp": 15,
  "placeStorage": "Ambiente fresco",
  "recommendation": "Evitar exposición directa al sol"
}


### Products

### Endpoint: `/api/v1/products` – `POST`

- **Descripción:** Registra un nuevo producto asociado a un proveedor..
    
- **Body:**

{
  "additionalName": "Whisky Etiqueta Azul",
  "liquorType": "Whisky",
  "brandName": "Blue Label",
  "unitPriceAmount": 250,
  "minimumStock": 10,
  "imageUrl": "http://example.com/image.png",
  "providerId": "sup123"
}

	
- **Respuesta exitosa (`201 Created`):**

	{
	  "id": "prod678",
	  "imageUrl": "http://example.com/image.png",
	  "name": "Whisky Etiqueta Azul",
	  "brandName": "Blue Label",
	  "liquorType": "Whisky",
	  "unitPriceAmount": 250,
	  "minimumStock": 10,
	  "providerId": "sup123"
	}
	
- **Respuesta de error (`400`):**  
    `"Product could not be created..."`


### Warehouses

### Endpoint: `/api/v1/warehouses/{warehouseId}/inventories/product/{productId}` – `POST`

- **Descripción:** Agrega existencias de un producto a un almacén específico, registrando su fecha de vencimiento.
    
- **Parámetros:**
    
    - `warehouseId`: ID del almacén
        
    - `productId`: ID del producto
        
 - Body:
        
	 {
	  "expirationDate": "2025-12-01T00:00:00",
	  "quantity": 100
	 }
        
- **Respuesta exitosa (`201 Created`):**

	{
	  "id": "inv123",
	  "productId": "prod456",
	  "warehouseId": "wh789",
	  "bestBeforeDate": "2025-12-01T00:00:00",
	  "stock": 100,
	  "productState": "FRESH"
	}



### Alerts

### Endpoint: `/api/v1/alerts/{alertId}` – `GET`

- **Descripción:** Recupera la información de una alerta del sistema mediante su identificador único.
    
- **Parámetros:**
    
    - `alertId` (path): ID de la alerta.
        
- **Ejemplo de llamada:**
    
    `GET /api/v1/alerts/a123`
    
- **Ejemplo de respuesta (`200 OK`):**
    
    {
	  "id": "a123",
	  "title": "Alerta de Temperatura",
	  "message": "La temperatura ha superado el límite permitido.",
	  "severity": "HIGH",
	  "type": "STORAGE_CONDITION",
	  "productId": "p456",
	  "warehouseId": "w789"
	  }
    
- **Respuesta de error (`404 Not Found`):**
    
    `Alert not found...`


### Account

### Endpoint: `/api/v1/accounts/{accountId}/care-guides` – `POST`

- **Descripción:** Crea una nueva guía de cuidado vinculada a una cuenta, sin asociarla directamente a un producto.
    
- **Parámetros:**
    
    - `accountId` (path): ID de la cuenta.
        
- **Body:**
    
	{
	  "title": "Guía de temperatura baja",
	  "summary": "Almacenar bajo 8 °C",
	  "minTemp": 2,
	  "maxTemp": 8,
	  "placeStorage": "Refrigerado",
	  "recommendation": "Evitar exposición al calor."
	}
    
- **Respuesta (`201 Created`):**
    
	{
	  "id": "cg01",
	  "accountId": "acc01",
	  "productId": null,
	  "title": "Guía de temperatura baja",
	  "summary": "Almacenar bajo 8 °C",
	  "minTemp": 2,
	  "maxTemp": 8,
	  "placeStorage": "Refrigerado",
	  "recommendation": "Evitar exposición al calor."
	}

### 5.2.3.7. Software Deployment Evidence for Sprint Review ###

#### Despliegue del Back End
* Primero, se creó un repositorio en GitHub para alojar el código fuente del Backend, permitiendo así una gestión centralizada y control de versiones
* Segundo, cada miembro del equipo creó una rama individual para desarrollar una función específica del BackEnd, lo que permitió trabajar en paralelo de manera organizada.

<p align="center">
  <img src="https://i.imgur.com/e31bJ1F.png"/>
</p>

* Tercero, se creó un proyecto en Rider y se conectó al repositorio remoto, facilitando la integración del código con el control de versiones desde el entorno de desarrollo.
* Cuarto, se implementaron las diferentes funcionalidades asignadas y se realizaron los commits respectivos, siguiendo buenas prácticas para mantener un historial de cambios claro.
* Quinto, una vez completado el desarrollo, se hizo merge de las ramas individuales a develop, donde se resolvieron conflictos y se corrigieron errores detectados en la integración.
* Sexto, tras verificar el correcto funcionamiento en develop, se realizó el merge final hacia la rama release, consolidando una versión estable del proyecto.
* Séptimo, se configuraron los archivos Dockerfile y appsettings.production.json para preparar el entorno de despliegue en Railway.
* Octavo, se configuró la base de datos en FreeSQLDatabase, vinculándola con Railway mediante las variables de entorno correspondientes para permitir la conexión remota.
* Noveno, se realizó el despliegue del Backend a través de Railway, donde se ejecutó correctamente la aplicación y se verificó su funcionamiento en el entorno de producción. A continuación, se muestra la evidencia del despliegue:
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/evidente.PNG?raw=true" alt="Evidence" width="600"/>
</p>
<br>


* Link publico: [Backend Desplegado](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html)

### 5.2.3.8. Team Collaboration Insights durint Sprint ###
En esta sección se detalla cómo se llevaron a cabo las actividades de implementación durante el sprint, así como la participación de cada miembro del equipo. Para este sprint, el equipo se organizó en torno a los tres principales productos: Landing Page, Web Application (Frontend) y Web Services(BackEnd). Cada integrante asumió responsabilidades específicas en uno o más de estos componentes, trabajando mediante ramas individuales y siguiendo una estrategia de integración continua.

El proyecto se realizo mediante repositorio en GitHub. Integrantes participantes:

<p align="center">
  <img src="../img/Chapter V/deployev 1.jpeg"/>
</p>

A continuacion de detallara el trabajo que realizo cada integrante del equipo:
- El integrante Didier Meza fue responsable de implementar la sección de alertas en el Frontend y creacion del bounded context alerts and notifications
- El integrante Giovany Torres agrego los videos about the team y about the product. En el Frontend se encargo de realizar el apartado de las ordenes, como tambien en el backend su desarrollo de las ordenes.
- El integrante Matias Diaz implementó la seccion de planes de reabastecimiento en el Frontend y creacion del bounded context analytics and reporting, la creacion del bounded context authentication, y profile management
- La integrante Anaely Burga  implementó la creacion del bounded context inventory management

Commits de los integrantes en el Landing Page:
<p align="center">
  <img src="../img/Chapter V/commit 1.PNG"/>
</p>

Grafico de los push y merge realizados por el equipo en el landing page:
<p align="center">
  <img src="https://imgur.com/5JbEW7W.png"/>
</p>


Commits de los integrantes en el Frontend:
<p align="center">
  <img src="../img/Chapter V/sprint-2 ev1F.PNG"/>
</p>

Grafico de los push y merge realizados por el equipo en el Frontend: 

<p align="center">
  <img src="../img/Chapter V/sprint-2 ev2F.PNG"/>
</p>

Commits de los integrantes en el BackEnd:
<p align="center">
  <img src="https://imgur.com/wSvBkDm.png"/>
</p>

Grafico de los push y merge realizados por el equipo en el BackEnd 

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/main/img/Chapter%20V/networkghrapg.PNG?raw=true" alt="Gráfico de push y merge del equipo en el BackEnd" width="600"/>
</p>
<br>

### 5.2.4. Sprint 4 ###

#### 5.2.4.1. Sprint Planning 4

En esta sección se presenta el planeamiento correspondiente al último sprint del proyecto. Para este sprint se definieron objetivos enfocados en tres componentes principales: el sitio web estático, la aplicación front-end y la aplicación back-end. Uno de los objetivos estuvo orientado a mejorar el diseño visual del sitio web estático, así como a optimizar las secciones de videos sobre el producto y el equipo de desarrollo para los visitantes. Asimismo, se planteó como segundo objetivo la integración del consumo de servicios de la aplicación backend en la aplicación front-end de StockVin. Finalmente, el tercer objetivo estuvo enfocado en la implementación de endpoints relacionados con la gestión de órdenes de compra y la autenticación de usuarios.

| Sprint #                            | Sprint 4 |
|-------------------------------------|----------|
| <b> Sprint planning Background </b> | -- |
| Date                                | 2025/11/27 |
| Time                                | 11:00 AM |
| Location                            | Llamada virtual por Discord |
| Prepared By                         | Meza Solórzano, Didier Sebastian |
| Attendees                           | Torres Apolinario, Giovany Smith / Díaz Quispe, Matías Sebastian / Meza Solórzano, Didier Sebastian/ Burga Loarte, Anaely Zarely  |
| Sprint 3 Review Summary             | En el sprint anterior, el equipo logró completar la implementación de los videos correspondientes al producto y al equipo de trabajo dentro de la Landing Page. Además, se finalizó gran parte de las secciones de la aplicación front-end, asegurando su correcto funcionamiento mediante un servidor de API simulada. Por otro lado, se implementaron los principales endpoints del backend relacionados con  productos, inventarios, alertas y guías. |
| Sprint 3 Retrospective Summary      | Durante este sprint, el equipo fortaleció notablemente la comunicación interna entre todos los integrantes, lo que permitió aumentar el nivel de confianza y coordinación. Este avance fue clave para afrontar de manera más organizada las tareas pendientes del último sprint y asegurar la finalización del desarrollo del producto. |
| <b> Sprint Goal & User Stories </b> | -- |
| Sprint 4 Goal                       | El objetivo de este sprint es brindar información completa y detallada, junto con videos explicativos sobre los beneficios y características del producto, así como un video final que muestre al equipo responsable del desarrollo de la plataforma a lo largo de su ciclo de vida. Asimismo, se busca integrar el consumo de servicios web en la aplicación front-end para los endpoints relacionados con productos, almacenes, inventarios, alertas, guías de cuidado, órdenes, cuentas, usuarios, perfiles y autenticación. Además, se pretende ampliar las posibilidades de implementación de funciones relacionadas con las preferencias de perfil, la creación de cuentas con suscripción y la generación de órdenes. Se considera que estos objetivos se cumplirán cuando se evidencie un aumento en el registro de usuarios, cuando los propietarios de licorerías utilicen la aplicación para el control de inventarios, cuando los proveedores gestionen sus pedidos mediante la plataforma y cuando los desarrolladores implementen nuevas funcionalidades relacionadas con perfiles, suscripciones y órdenes. |
| Sprint 4 Velocity                   | 91 |
| Sum of Story Points                 | 90 |


### 5.2.4.2. Aspect Leaders and Collaborators.

En esta sección se presenta la matriz de liderazgo y colaboración correspondiente al último sprint del proyecto. Los aspectos principales considerados en esta etapa están enfocados en los distintos módulos que conforman la aplicación Front-End, así como también en sus respectivos componentes del Back-End. Para ello, se han definido las siguientes áreas clave de trabajo: Inventario, Productos, Cuenta de Usuario, Reportes, Órdenes de Compra y Alertas.

| Integrante del equipo                | Usuario GitHub | Alertas | Reportes | Órdenes | Inventario | Cuenta de usuario | Pagos y suscripciones |
|--------------------------------------|----------------|---------|----------|---------|------------|-------------------|-----------------------|
| Díaz Quispe, Matías Sebastián        | equinox-1092   |         | L        | L       |            |                   | L                     |
| Torres Apolinario, Giovany Smith     | Giovany7x      |         |          | L       |            | L                 |                       |
| Burga Loarte, Anaely Zarely          | userxx1000     |         |          |         | L          |                   |                       |
| Meza Solórzano, Didier Sebastián     | Didier04x      | L       |          |         |            |                   |                       |

#### 5.2.4.3. Sprint Backlog 4

Tal como se definió en el planeamiento de este sprint, el objetivo principal es finalizar por completo el sitio web estático mediante la incorporación de mejoras en las secciones informativas sobre el producto y su equipo de desarrollo. Asimismo, se busca dotar a la aplicación frontend de la capacidad de consumir los servicios web proporcionados por la aplicación backend, además de implementar los endpoints necesarios para las funcionalidades relacionadas con las órdenes de compra y la autenticación de usuarios.

Luego de establecer el objetivo general, se identificaron las historias de usuario más relevantes para este sprint. Posteriormente, cada historia fue descompuesta en tareas específicas orientadas a su correcta implementación. Para la gestión y seguimiento del avance del sprint, se utilizó la herramienta _Trello_, la cual permitió organizar y controlar el desarrollo de las actividades.
[https://trello.com/b/SVXnlzhD](https://trello.com/b/SVXnlzhD)

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/TrelloSprint4.png" 
  alt="Sprint goal and Stories of Sprint #4"/>
</p>

A continuación, se presenta la tabla con las tareas necesarias para completar de manera satisfactoria este último sprint. Además, se ha asignado a cada actividad un integrante del equipo responsable y su respectivo estado de avance.

| Sprint 4     | Sprint Backlog 4                                  |                |                                                                               |                                                                                                                                                              |                    |--------------------------------|----------|
|--------------|---------------------------------------------------|----------------|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|--------------------------------|----------|
| User Stories |                                                   | Work Item/Task |                                                                               |                                                                                                                                                              | Estimación (Horas) | Asignado a                     | Estado   |
| US052        | Consultar historial de facturación                | US052T001      | Desarrollar sección de historial de órdenes                                   | Implementación en el frontend de una sección que muestre todas las órdenes realizadas por el usuario.                                                         | 6                  | Díaz Quispe, Matías Sebastián  | Done     |
|              |                                                   | US052T002      | Implementar endpoint de historial de órdenes                                  | Desarrollo de un endpoint para obtener todas las órdenes asociadas a un usuario específico.                                                                  | 6                  | Díaz Quispe, Matías Sebastián  | Done     |
| US066        | Acceder al plan premium                           | US066T001      | Implementar sección informativa del plan premium                              | Desarrollo de una interfaz que muestre los beneficios y el costo del plan premium.                                                                          | 6                  | Torres Apolinario, Giovany Smith | Done  |
|              |                                                   | US066T002      | Integrar API de pagos                                                         | Integración del servicio de PayPal para la validación de pagos dentro del sistema.                                                                          | 8                  | Torres Apolinario, Giovany Smith | Done  |
| US065        | Acceder al plan gratuito                          | US065T001      | Implementar sección del plan gratuito                                         | Desarrollo de una sección informativa sobre el plan gratuito.                                                                                                | 4                  | Torres Apolinario, Giovany Smith | Done  |
| TS002        | Endpoint para iniciar sesión                      | TS002T001      | Implementar endpoint de autenticación                                         | Desarrollo de un endpoint para validar credenciales e iniciar sesión.                                                                                        | 5                  | Díaz Quispe, Matías Sebastián  | Done     |
|              |                                                   | TS002T002      | Implementar JWT para autenticación                                            | Implementación de JSON Web Tokens para el control de sesiones.                                                                                                | 4                  | Díaz Quispe, Matías Sebastián  | Done     |
| TS001        | Endpoint para registrar nuevo usuario             | TS001T001      | Implementar endpoint de registro de usuarios                                  | Desarrollo de un endpoint para el registro de nuevos usuarios en el sistema.                                                                                | 6                  | Díaz Quispe, Matías Sebastián  | Done     |
| US042        | Crear guía de remisión interna                    | US042T001      | Implementar lógica de traslado interno                                        | Desarrollo de la lógica de negocio para el traslado de productos entre inventarios.                                                                         | 6                  | Díaz Quispe, Matías Sebastián  | Done     |
| TS017        | Endpoint para registrar guía de remisión          | TS017T001      | Implementar endpoint de traslado                                              | Desarrollo de un endpoint que permita registrar el traslado de productos a otro inventario.                                                                 | 6                  | Díaz Quispe, Matías Sebastián  | Done     |
| TS009        | Endpoint para configurar alertas de vencimiento   | TS009T001      | Configurar alertas                                                            | Desarrollo de un endpoint que permita modificar la configuración de alertas.                                                                                | 6                  | Torres Apolinario, Giovany Smith | Done  |
| TS022        | Endpoint para visualizar el estado de pedidos     | TS022T001      | Implementar visualización de órdenes                                          | Desarrollo de un endpoint que permita consultar las órdenes de un usuario específico.                                                                       | 8                  | Díaz Quispe, Matías Sebastián  | Done     |
| TS016        | Endpoint para generar plan de reabastecimiento    | TS016T001      | Implementar botón de traslado                                                 | Desarrollo de un botón para ejecutar el traslado de productos entre inventarios.                                                                            | 6                  | Torres Apolinario, Giovany Smith | Done  |
| US032        | Visualizar historial de compras                   | US032T001      | Endpoint de órdenes por cuenta                                                | Implementar el endpoint que obtenga todas las órdenes asociadas a una cuenta.                                                                               | 8                  | Díaz Quispe, Matías Sebastián  | Done     |
|              |                                                   | US032T002      | Endpoint de órdenes por proveedor                                             | Implementar el endpoint que permita consultar las órdenes enviadas a un proveedor específico.                                                               | 6                  | Díaz Quispe, Matías Sebastián  | Done     |
| TS018        | Endpoint para actualizar perfil del usuario       | TS018T001      | Crear perfiles                                                                | Desarrollo de un endpoint para la creación de perfiles de usuario.                                                                                          | 6                  | Torres Apolinario, Giovany Smith | Done  |
|              |                                                   | TS018T002      | Actualizar perfiles                                                           | Desarrollo del endpoint que permite la actualización de perfiles.                                                                                           | 6                  | Torres Apolinario, Giovany Smith | Done  |
| TS004        | Endpoint para recuperar contraseña                | TS004T001      | Validación de códigos                                                         | Implementación de la lógica que valida los códigos enviados por correo para restablecer la contraseña.                                                      | 6                  | Díaz Quispe, Matías Sebastián  | To-Do    |
|              |                                                   | TS004T002      | Actualizar contraseña                                                         | Desarrollo del endpoint que permite actualizar la contraseña del usuario.                                                                                   | 5                  | Díaz Quispe, Matías Sebastián  | Done     |
| US014        | Cambiar contraseña desde configuración            | US014T001      | Implementar acceso a recuperación desde configuración                         | Desarrollo de un botón en el frontend que redirija al módulo de recuperación de contraseña.                                                                | 4                  | Díaz Quispe, Matías Sebastián  | Done     |
| US047        | Cambiar contraseña desde perfil                   | US047T001      | Implementar acceso a recuperación desde perfil                                | Desarrollo de un botón en el frontend para redirigir al proceso de recuperación de contraseña desde el perfil del usuario.                                 | 4                  | Díaz Quispe, Matías Sebastián  | Done     |
| US012        | Recuperar contraseña por correo                   | US012T001      | Botón de acceso a recuperación                                                | Implementación de un botón que dirija al módulo de recuperación de contraseña.                                                                              | 4                  | Díaz Quispe, Matías Sebastián  | Done     |
|              |                                                   | US012T002      | Servicio de envío de correos                                                  | Implementación de un servicio de terceros para el envío de correos de recuperación.                                                                        | 6                  | Díaz Quispe, Matías Sebastián  | To-Do    |
|              |                                                   | US012T003      | Validación de códigos                                                         | Implementación de la lógica que permite validar los códigos enviados al correo.                                                                             | 8                  | Díaz Quispe, Matías Sebastián  | To-Do    |
| US015        | Cerrar sesión manualmente                          | US015T001      | Implementar cierre de sesión                                                  | Desarrollo de un botón que permita al usuario cerrar sesión desde la aplicación.                                                                           | 4                  | Torres Apolinario, Giovany Smith | Done  |
|              |                                                   | US015T002      | Lógica de cierre de sesión                                                    | Implementación del proceso que invalida la sesión activa del usuario.                                                                                       | 4                  | Torres Apolinario, Giovany Smith | Done  |
| US013        | Elegir contraseña segura                          | US013T001      | Validación de seguridad de contraseña                                         | Desarrollo de un método que evalúe el nivel de seguridad de la contraseña ingresada.                                                                       | 4                  | Díaz Quispe, Matías Sebastián  | Done     |

#### 5.2.4.4. Development Evidence for Sprint Review

En esta sección se detallan los principales avances realizados durante el desarrollo correspondiente a este último sprint del proyecto.

A continuación, se presenta una tabla que resume los commits realizados en los distintos repositorios, los cuales contienen parte de las funcionalidades necesarias para completar los objetivos definidos para este sprint.

Repositorio del sitio web estático: https://github.com/StockVin/WineInventory-LandingPage.git  
Repositorio de la aplicación Frontend: https://github.com/StockVin/WineInventory-frontend-application.git  
Repositorio de la aplicación Backend: https://github.com/StockVin/WineInventory-backend-application.git  

| Repository                              | Branch                    | Commit Id | Commit Message                                                            | Commited On |
|-----------------------------------------|---------------------------|-----------|---------------------------------------------------------------------------|-------------|
| StockVin/WineInventory-LandingPage      | feature/testimonials      | d2d8cdd   | fix: change files and folders naming.                                     | 26/11/2025  |
| StockVin/WineInventory-FrontendApp      | feature/warehouse-logic   | 8344243   | feat(inventory): add warehouse logic.                                     | 26/11/2025  |
| StockVin/WineInventory-FrontendApp      | feature/accounts          | eef6170   | feat(accounts): add authentication service.                               | 26/11/2025  |
| StockVin/WineInventory-FrontendApp      | feature/subscription-view | 0082b32   | feat(SAP): add subscription view with responsive design.                  | 26/11/2025  |
| StockVin/WineInventory-FrontendApp      | feature/alerts            | 57b1c92   | feat(alerts): add alert integration in the dashboard.                     | 27/11/2025  |
| StockVin/WineInventory-BackendApp       | feature/orders            | 3e095c7   | feat(orders): add orders controller.                                      | 23/11/2025  |
| StockVin/WineInventory-BackendApp       | feature/catalogs          | 3e095c7   | feat(catalogs): add clients and dto.                                      | 23/11/2025  |
| StockVin/WineInventory-BackendApp       | feature/alerts            | 3e095c7   | feat(alerts): add events.                                                 | 26/11/2025  |
| StockVin/WineInventory-BackendApp       | feature/accounts          | 6a667c1   | feat(authentication): add acl to get account id for the sign in resource. | 26/11/2025  |

---

#### 5.2.4.5. Execution Evidence for Sprint Review

En esta sección se describen los resultados alcanzados durante el desarrollo de este sprint, respaldados por evidencias de las funcionalidades implementadas.

Entre los principales logros se encuentra la mejora de las secciones informativas del sitio web estático mediante la incorporación de dos videos dirigidos a los visitantes: uno enfocado en explicar las funcionalidades y beneficios que ofrece la aplicación web, y otro que presenta al equipo de desarrollo y su participación a lo largo del ciclo de vida del proyecto.

Asimismo, se logró que la aplicación frontend pueda consumir correctamente los servicios web proporcionados por la aplicación backend en todas las secciones implementadas previamente. Finalmente, se desarrollaron diversos endpoints en el backend relacionados con la gestión de órdenes de compra, alertas, autenticación, perfiles, cuentas y suscripciones.

A continuación, se presentan las capturas de pantalla correspondientes a las secciones implementadas tanto en la Landing Page como en la aplicación Frontend y en la aplicación Backend, las cuales evidencian el progreso alcanzado durante este sprint.

- Video de ejecución de los tres productos para este sprint:  


## **Landing Page**

Se adjuntan los enlaces para acceder al sitio web desplegado y al video de ejecución del sitio web estático. En dicho video se muestra el funcionamiento general de cada sección del sitio y su visualización en un navegador web.

Video sobre exploración de la aplicación  
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/explorationlandingpage.png" 
  alt="Exploration of the app section in landing page"/>
</p>

## **Front End Application**

Se adjuntan los enlaces para acceder a la aplicación frontend desplegada y al video de ejecución de la misma, donde se observa el funcionamiento de las secciones implementadas.

Sección de almacenes  
<p align="center">
  <img src="" 
  alt="Warehouses in frontend"/>
</p>

Sección de órdenes  
<p align="center">
  <img src="" 
  alt="Orders in frontend"/>
</p>

### **Back End Application**

Se adjuntan los enlaces para acceder a la aplicación backend desplegada y al video de ejecución de la misma. En el video se evidencia el funcionamiento de los endpoints desarrollados y la estructura de sus rutas.

Endpoints para catálogos en el backend  
<p align="center">
  <img src="" 
  alt="Catalogs in backend"/>
</p>

Endpoints para cuentas en el backend  
<p align="center">
  <img src="" 
  alt="Accounts in backend"/>
</p>

#### 5.2.4.6. Services Documentation Evidence for Sprint Review

En esta sección se presenta la evidencia correspondiente a la documentación de los endpoints implementados en la aplicación backend durante este sprint. En la siguiente tabla se muestra un resumen de las acciones principales, los requisitos y la información técnica de cada endpoint desarrollado.

| Módulo      | Endpoint                                            | Acción                  | Verbo HTTP | Sintaxis                        | Parámetros principales                        | Enlace a Swagger                                                  |
|------------|------------------------------------------------------|--------------------------|------------|----------------------------------|-----------------------------------------------|-------------------------------------------------------------------|
| Care Guides | `/api/v1/care-guides/{careGuideId}`                  | Obtener guía por ID      | GET        | `/api/v1/care-guides/123`        | `careGuideId`, `accountId`                    | [Ver Link](https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html)     |

---

#### 5.2.4.7. Software Deployment Evidence for Sprint Review

Con el objetivo de garantizar una correcta organización del desarrollo y un despliegue eficiente, el proyecto fue dividido en tres componentes principales: la Landing Page, la aplicación Frontend y la aplicación Backend. Cada uno de estos productos cuenta con su propio repositorio en GitHub, así como con procesos de integración y despliegue independientes. A continuación, se describe el flujo de despliegue seguido para cada uno de ellos, junto con la evidencia correspondiente.

Para el punto de partida, se tomó como base la configuración inicial de los repositorios definida en la Sección 5.1.4. Posteriormente, se detalla el proceso de despliegue del sitio web estático.

---

### Despliegue del Landing Page

Para el despliegue del sitio web estático se utilizó nuevamente **GitHub Pages**, herramienta que permite publicar sitios web estáticos directamente desde un repositorio de GitHub. El procedimiento ejecutado fue el siguiente:

* Se trabajó inicialmente sobre la rama `develop` del repositorio del sitio web estático, donde se encontraban integrados todos los cambios correspondientes a este sprint.
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/deploylanding1.png"/>
</p>

* Posteriormente, los cambios fueron migrados desde la rama de desarrollo hacia una nueva rama de tipo `release` denominada `release/landing-page-v4.0`, desde donde se realizó el despliegue final.
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/deploylanding2.png"/>
</p>

* Luego, se accedió a la sección **Settings** del repositorio y se ingresó a la opción **Pages** dentro del bloque de configuración de código y automatización.
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/deploylanding3.png"/>
</p>

* A continuación, se seleccionó como origen de despliegue la rama de tipo `release` previamente creada y se guardó la configuración.
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/deploylanding4.png"/>
</p>

* Finalmente, se generó el enlace público que permite el acceso al sitio web estático desplegado.
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/deploylanding5.png"/>
</p>

* Se verificó el correcto despliegue accediendo al enlace público proporcionado por GitHub Pages.
<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-4/img/Chapter%20IV/deploylanding6.png"/>
</p>

---

### Despliegue de la Aplicación Frontend

Para el despliegue de la aplicación frontend se utilizó **Firebase Hosting**, plataforma que permite publicar aplicaciones web de forma rápida y eficiente.

Enlace de la aplicación frontend desplegada:  
https://wine-inventory-front-end.web.app/sign-in

* Se partió desde la rama `develop` del repositorio frontend con todos los cambios actualizados.
<p align="center">
  <img src=""/>
</p>

* Los cambios fueron enviados a una nueva rama de tipo `release`, desde donde se realizó el despliegue definitivo.
<p align="center">
  <img src=""/>
</p>

* Luego, se ejecutó el comando `npm run build` para generar la carpeta `dist` con la versión de producción de la aplicación.
<p align="center">
  <img src="">

<p align="center">
  <img src="">

* A continuación, se ejecutó el comando `firebase login` e inició sesión con una cuenta de Google.
<p align="center">
  <img src=""> 

* Se comprobó el inicio de sesión exitoso.
<p align="center">
  <img src="">

* Finalmente, se ejecutó el comando `firebase deploy`, lo que permitió publicar la aplicación.
<p align="center">
  <img src=""> 

* Se accedió a la URL proporcionada por Firebase para verificar el correcto despliegue.
<p align="center">
  <img src="">

---

### Despliegue del Back End

El despliegue del backend se realizó utilizando la plataforma **Azure**, la cual permite automatizar el despliegue de aplicaciones al detectar cambios en el repositorio.

Enlace del backend desplegado:  
https://wineinventory-back-end.azurewebsites.net/swagger-ui/index.html

* Se trabajó desde la rama `develop` del repositorio del backend.
<p align="center">
  <img src=""/>
</p>

* Luego, se creó una rama de tipo `release` para el despliegue.
<p align="center">
  <img src=""/>
</p>

* Posteriormente, se configuró la base de datos mediante la plataforma **freesqldatabase**.
<p align="center">
  <img src="">

* Se realizó el despliegue desde la consola de Render.
<p align="center">
  <img src="">

* Se verificó el despliegue exitoso de la aplicación.
<p align="center">
  <img src=""/>
</p>

<p align="center">
  <img src=""/>
</p>

* Finalmente, se ingresó a la URL pública entregada por Render para validar el correcto funcionamiento del backend.
<p align="center">
  <img src=""> 
</p>


## 5.3. Validation Interviews

### 5.3.1. Diseño de entrevistas

En las entrevistas de validación se incluirá:

- **Exploración del Landing Page:**
    
    - ¿Comprendieron el propósito de la aplicación?
        
    - ¿Fue clara la propuesta de valor?
        
- **Validación de la Aplicación Web:**
    
    - Se validarán las funcionalidades clave según el flujo de cada user goal.
        
    - Se observarán comportamientos, puntos de confusión, y reacciones espontáneas.
        
- **Registro de métricas cualitativas y cuantitativas:**
        
    - Nivel de comprensión (autoevaluación del usuario).
        
    - Comentarios de usabilidad y experiencia.
        
    - Satisfacción con el flujo (escala del 1 al 5).
	
- **Flujos a Desarrollar:**

| **User Goal** | **Descripción del Flujo**                                                                                                        | **Objetivo de Validación**                                                         |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| **UG 1**      | El usuario ingresa al Landing Page, completa su registro con sus datos y automáticamente se le asigna el plan gratuito.          | Comprobar que el formulario sea claro y que el usuario entienda el plan inicial.   |
| **UG 2**      | El usuario inicia sesión con su cuenta y, si lo desea, puede optar por cambiar o seleccionar un plan premium.                    | Evaluar que el ingreso sea sencillo y que la elección del plan sea entendible.     |
| **UG 4**      | Desde el dashboard, el licorero puede dirigirse sin complicaciones a la sección de inventario.                                  | Asegurar que el acceso a inventario sea directo e intuitivo.                       |
| **UG 5**      | El licorero entra al inventario, registra un nuevo producto completando el formulario y este queda correctamente vinculado.      | Revisar que el formulario sea fácil de usar y que el proceso de registro sea claro.|
| **UG 8**      | El licorero accede a la sección de Reportes desde cualquier parte del sistema usando el ícono correspondiente.                  | Confirmar que la navegación hacia reportes sea evidente y sin obstáculos.          |
| **UG 9**      | Dentro de la sección de Reportes, el licorero crea un reporte nuevo completando los datos requeridos.                           | Verificar que los campos necesarios estén organizados de forma lógica y comprensible. |
| **UG 11**     | El licorero registra una orden de compra: selecciona productos, define cantidades y elige un proveedor antes de enviarla.        | Evaluar que el flujo sea fluido y que el proceso de selección y envío sea sencillo. |
| **UG 12**     | El proveedor entra a la sección de Conservación, completa los datos de una nueva guía y luego la revisa.                        | Validar que el proceso de elaboración y visualización de guías sea fácil de seguir. |


### 5.3.2. Registro de entrevistas


## Entrevista 1

|Entrevista|Registro|
|---|---|
|<p align="center"><img src="https://raw.githubusercontent.com/StockVin/WineInventory-ProjectDocumentation/738974c5cf84c8d968acf504cc67873edcb3eb0f/img/Chapter%20V/yadhir_interview.jpg" width="150"/></p>|**Distrito:** Santiago de Surco <br>**Entrevistado:** Yadhir Antonio|
|[Link al video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202319950_upc_edu_pe/IQCi6JccnzmeT5efqc3E5jYtAaioCBjCVVz3ClqB6gF70rk?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=Wh0iz6)|**Entrevistador:** Didier Sebastián Meza Solórzano|
|Timing: 0:00–9:54|**Resumen:** La entrevista fue realizada a **Yadhir Antonio**, de 24 años, con el objetivo de validar dos soluciones de software orientadas a empresas del sector licores. Durante la evaluación se revisaron la landing page, la fluidez de navegación, la claridad del contenido y el funcionamiento de secciones clave como planes, testimonios, dashboard, alertas, perfil y reportes. Yadhir destacó que la estructura general del sitio es clara y fácil de entender, valorando especialmente la presentación de testimonios, los beneficios de los planes y el monitoreo del inventario en tiempo real. Sugirió ampliar un poco el tamaño de la fuente y que la opción multilingüe esté disponible en todas las secciones. Señaló que los íconos y accesos rápidos del dashboard son intuitivos y que las alertas (vencimiento y bajo stock) son útiles para la toma de decisiones. Sobre registro y perfil, comentó que el diseño es amigable y que la inclusión de redes sociales sería un plus. Finalmente, indicó que la sección de reportes es clara y está bien ubicada.**Satisfacción del flujo:** 4.5/5|

---

## Entrevista 2

|Entrevista|Registro|
|---|---|
|<p align="center"><img src="https://raw.githubusercontent.com/StockVin/WineInventory-ProjectDocumentation/738974c5cf84c8d968acf504cc67873edcb3eb0f/img/Chapter%20V/Milton_interview.jpg" width="150"/></p>|**Distrito:** Villa el Salvador <br>**Entrevistado:** Milton Meza|
|[Link al video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202319950_upc_edu_pe/IQCk_idPqy7cTrbDXrrk0GDiAbNkREMedOwfqEICBaJWdoc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=5kM9d1)|**Entrevistador:** Didier Sebastián Meza Solórzano|
|Timing: 0:00–14:41|**Resumen:** La entrevista se realizó a **Milton Meza**, de 21 años, quien participó en la validación de la aplicación _Stock_. Durante la prueba, creó su cuenta, eligió su rol como dueño de licorería y accedió sin inconvenientes al dashboard, visualizando ventas, productos disponibles y alertas. Exploró el módulo de reportes y generó una guía de conservación configurando temperatura, tiempo de duración del producto abierto y notas para su equipo. Luego creó una orden de compra seleccionando artículos del catálogo y asignando un proveedor. Finalmente, ingresó a su perfil para actualizar sus datos, verificar su rol y revisar los beneficios del plan premium. Destacó la **gestión del stock mínimo y las alertas**, esenciales para la toma de decisiones. Valoró la estructura general de la app y consideró que con mayor uso podría familiarizarse aún más con todas sus funciones.**Satisfacción del flujo:** 4.8/5|

---


## Entrevista 3

|Entrevista|Registro|
|---|---|
|<p align="center"><img src="https://raw.githubusercontent.com/StockVin/WineInventory-ProjectDocumentation/738974c5cf84c8d968acf504cc67873edcb3eb0f/img/Chapter%20V/diego_interview.jpg" width="150"/></p>|**Distrito:** Villa el Salvador <br>**Entrevistado:** Diego Vilca|
|[Link al video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202319950_upc_edu_pe/IQApTQg1yV5VRb1S0HcVrxd2Ab5_U_dYReq979PIZ6OvfSs?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=FrUkV2)|**Entrevistador:** Didier Sebastián Meza Solórzano|
|Timing: 0:00–11:36|**Resumen:** La entrevista se realizó a **Diego Vilca**, de 20 años, quien participó en la validación de la aplicación. La evaluación se centró en el flujo de navegación y la experiencia visual en la landing page y distintas secciones del sistema. Diego valoró la estructura de la página principal, destacando testimonios, preguntas frecuentes, soporte en dos idiomas (español e inglés) y planes diferenciados (gratuito y premium). Destacó la combinación de colores y organización de los elementos visuales, la navegación mediante íconos en la barra lateral y la selección de roles al registrarse, edición de perfil y cambio de idioma. Sobre el módulo de inventario, indicó que la visualización de productos, imágenes, precios, stock y opciones de edición o creación es clara y práctica. Respecto a los reportes, comprendió sin dificultad las funciones de pérdidas, transportes, reposiciones y conservación, y opinó que están bien divididas y son fáciles de recorrer. Finalmente, destacó la importancia de las alertas por productos próximos a vencer o con stock crítico y sugirió accesos rápidos a catálogos y pedidos para agilizar el uso.**Satisfacción del flujo:** 4.7/5|




### 5.3.3. Evaluación según heurísticas

##### APP A EVALUAR: **WineInventory**
---

##### TAREAS A EVALUAR:

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Registro de un usuario nuevo  
2. Inicio de sesión de un usuario
3. Creación de un order
4. Visualización de las alertas de la aplicación
5. Visualización de reporte generado
6. Insertar una imagen a un inventario
7. Carga de alertas en la aplicación
8. Realización de una orden de compra

**No están incluidas en esta versión de la evaluación las siguientes tareas:**

1. Asignar un producto a un inventario
2. Registrar salidas de productos
3. Registrar reportes de pérdidas

---

##### ESCALA DE SEVERIDAD:

| Nivel | Descripción |
|-------|-------------|
| **1** | Inconveniente leve: se presenta de manera esporádica y el usuario puede manejarlo sin dificultad. Su corrección no es prioritaria y solo se abordará si existe tiempo disponible. |
| **2** | Contratiempo moderado: aparece con algo más de frecuencia o requiere un pequeño esfuerzo adicional del usuario para sortearlo. Puede programarse su solución con baja prioridad para la siguiente versión. |
| **3** | Problema significativo: sucede de forma recurrente o bloquea al usuario al intentar continuar. Su atención es necesaria y debe considerarse como una tarea de alta prioridad. |
| **4** | Falla crítica: afecta gravemente el funcionamiento, impidiendo el uso normal de la herramienta. Debe resolverse de manera obligatoria antes de cualquier lanzamiento. |


##### TABLA RESUMEN

| # | Problema                                                                                                       | Severidad | Heurística/Principio afectado                                                             |
|---|----------------------------------------------------------------------------------------------------------------|-----------|--------------------------------------------------------------------------------------------|
| **1** | El formulario de inicio de sesión no muestra mensajes claros cuando un campo es inválido (ej.: correo mal formateado). | 3 | Usabilidad: Facilitar que el usuario identifique el error, comprenda la causa y pueda corregirlo. |
| **2** | No existen reglas que impidan registrar o usar contraseñas débiles.                                        | 2 | Usabilidad: Prevención de errores. |
| **3** | Al intentar subir una imagen para crear un almacén, el sistema no informa al usuario si ocurre un fallo.   | 3 | Usabilidad: Facilitar que el usuario identifique el error, comprenda la causa y pueda corregirlo. |
| **4** | La vista de almacenes no cuenta con paginación ni un desplazamiento adecuado cuando hay muchos registros.  | 1 | Arquitectura de Información: ¿Es escalable? |



##### DESCRIPCIÓN DE PROBLEMAS

###### PROBLEMA #1: No existen validaciones que aseguren que el usuario ingrese un correo electrónico con un formato adecuado.

**Severidad:** 3  
**Heurística afectada:** Usabilidad – Facilitar que el usuario identifique el error, entienda qué ocurrió y pueda corregirlo.

**Descripción:**  
Actualmente, si el usuario ingresa un correo con un formato incorrecto o coloca texto no válido después del símbolo (@), la interfaz no muestra ningún mensaje que indique que el dato ingresado es inválido.

<p align="center">
  <img src="https://raw.githubusercontent.com/StockVin/WineInventory-ProjectDocumentation/dbf0282d3cfd0e0e17041471dce64f0495afe94a/img/Chapter%20IV/Corres.PNG">
</p>

**Recomendación:**  
Implementar validaciones de formato de correo electrónico que generen retroalimentación inmediata y clara, evitando la aceptación de direcciones no válidas (por ejemplo, textos aleatorios o dominios inexistentes).

###### PROBLEMA #2: No existe un control que garantice la creación de contraseñas seguras.

**Severidad:** 2  
**Heurística afectada:** Usabilidad – Prevención de errores.

**Descripción:**  
El sistema permite que un usuario se registre utilizando contraseñas demasiado simples, como aquellas con menos de 8 caracteres o sin incluir números, símbolos o mayúsculas, lo cual incrementa el riesgo de seguridad.

<p align="center">
  <img src="https://raw.githubusercontent.com/StockVin/WineInventory-ProjectDocumentation/dbf0282d3cfd0e0e17041471dce64f0495afe94a/img/Chapter%20IV/con2.PNG">
</p>


**Recomendación:**  
Implementar reglas mínimas de seguridad: longitud mayor a 8 caracteres, incluir al menos una letra mayúscula, un número y un símbolo especial para fortalecer la protección de las cuentas.

###### PROBLEMA #3: Los mensajes de error no brindan información clara ni ayudan al usuario a saber qué hacer.

**Severidad:** 2  
**Heurística afectada:** Usabilidad – Facilitar que el usuario identifique el error, comprenda qué ocurrió y pueda recuperarse.

**Descripción:**  
Los mensajes mostrados actualmente son genéricos y no ofrecen detalles útiles ni indicaciones para volver a intentar la acción, lo que dificulta al usuario entender el problema.

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20V/alertas.PNG?raw=true">
</p>

<p align="center"><strong>Más información para destacar</strong></p>

**Recomendación:**  
Mostrar mensajes más claros y accionables, por ejemplo:  
*"No se pudieron cargar las alertas. Verifica tu conexión e intenta nuevamente."*

###### PROBLEMA #4: Las alertas críticas no cuentan con una jerarquía visual adecuada

**Severidad:** 1  
**Heurística afectada:** Usabilidad – Estética y diseño minimalista

**Descripción:**  
Las notificaciones importantes, como “Urgent restock”, no se diferencian del resto, lo que dificulta que el usuario las identifique rápidamente.

<p align="center">
  <img src="https://github.com/StockVin/WineInventory-ProjectDocumentation/blob/feature/chap5-sprint-3/img/Chapter%20IV/ALER2.PNG?raw=true">
</p>

**Recomendación:**  
Aplicar elementos visuales como colores más llamativos, bordes o íconos de alerta para resaltar las prioridades y mejorar la visibilidad.


## 5.4. Video About The Product

En esta sección, se adjunta el enlace al video sobre el producto de software desarrollado. En este video, se detallan funcionalidades principales y beneficios que ofrece la aplicacion a los usuarios finales que usaran la aplicacion web para sus negocios.

Enlace al video acerca del producto: [Link about the product](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311938_upc_edu_pe/IQAKPOgobZW7QKYYNN56z7zkAXvaWHaIMkbGj4D_GcxcwoQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=cLjsrm)
<p align="center">
  <img src="https://i.imgur.com/via7j1p.png">
</p>

## 5.5. Video About The Team

En esta sección, se adjunta el enlace al video que presenta al equipo de trabajo que desarrolló el producto de software. En este video, cada miembro del equipo comparte su rol y contribuciones al proyecto, destacando la colaboración y el esfuerzo conjunto para crear una solución efectiva.

Enlace al video acerca del equipo de trabajo que desarrollo el producto de software:
[Link about the team ](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311938_upc_edu_pe/IQDMPrGPukyRT4vnuqWKqIXhAe1Pn5xUbRdhXAmwzaATXHg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=lBdcyJ)

<p align="center">
  <img src="https://i.imgur.com/Ek2vt1D.png">
</p>
