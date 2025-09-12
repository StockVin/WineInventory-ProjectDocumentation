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

  
* **Landing Page: [https:](https:)**
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



## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###



### 5.2.1.2. Aspect Leaders and Collaborators ###



### 5.2.1.3. Sprint Backlog 1 ###



### 5.2.1.4. Development Evidence for Sprint Review ###



### 5.2.1.5. Execution Evidence for Sprint Review ###



### 5.2.1.6. Software Deployment Evidence for Sprint Review ###



### 5.2.1.7. Software Deployment Evidence for Sprint Review ###



#### 5.2.1.8. Team Collaboration Insights during Sprint
