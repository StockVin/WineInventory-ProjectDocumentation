# Capítulo 5: Product Implementation, Validation & Deployment #

## _5.1. Software Configuration Management_ ##



### 5.1.1. Software Development Environment Configuration ###



### 5.1.2. Source Code Management ###



#### **5.1.2.1. Repositorios**



#### **5.1.2.2. GitFlow**



##### **5.1.2.2.1. Main Branches**



##### **5.1.2.2.2. Supporting Branches**



#### **5.1.2.3. Release Versioning Conventions**



#### **5.1.2.3. Commits Conventions**



### 5.1.3. Source Code Style Guide & Conventions ###



### 5.1.4. Software Deployment Configuration ###



## _5.2. Landing Page, Services & Applications Implementation_ ##

### 5.2.1. Sprint 1 ###

### 5.2.1.1. Sprint Planning 1 ###

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


### 5.2.1.2. Aspect Leaders and Collaborators ###

En esta sección, se incluye la matriz de liderazgo y colaboración desarrollada para este primer sprint. Los principales aspectos que se toman en cuenta en este sprint se centran en cada sección y el estilo que debe contener este mismo: inicio, funcionamiento de la aplicación, beneficios para cada segmento, testimonios, exploración de la aplicación, planes y contacto.

| Team Member                        | GitHub Username | Sección Inicio | Nosotros | Servicios | Planes | FAQ | Acerca |  
|------------------------------------|-----------------|----------------|---------------------------------|------------|-------------|--------|----------|
| Diaz Quispe, Matias Sebastian      | equinox-1092      |               |                                |L            |             |        |         |        |
| Torres Apolinario Giovany Smith    | Giovany7x     |                | L                               |            |             |    L    |          |     |
| Hermoza Paredes Bryan Norberto  | WasNeo          |                |                                 |          |             |        |L          |
| Burga Loarte Anaely Zarely | userxx1000      |                |                                 |            | L           |        |          |
| Meza Solòrzano Didier Sebastiàn      | Didier04x    |L                |                                 |            |             |      | 


### 5.2.1.3. Sprint Backlog 1 ###

    
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



### 5.2.1.4. Development Evidence for Sprint Review ###



### 5.2.1.5. Execution Evidence for Sprint Review ###



### 5.2.1.6. Software Deployment Evidence for Sprint Review ###



### 5.2.1.7. Software Deployment Evidence for Sprint Review ###



#### 5.2.1.8. Team Collaboration Insights during Sprint
