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
