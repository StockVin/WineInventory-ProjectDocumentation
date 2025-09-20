# Capítulo 4: Product Design #

## _4.1. Style Guidelines_ ##

### 4.1.1. General Style Guidelines ###



### 4.1.2. Web Style Guidelines ###



## _4.2. Information Architecture_ ##

### 4.2.1. Organization Systems ###

La estructura jerárquica del *Landing Page* de **StockSip** fue diseñada para guiar al usuario de manera clara y efectiva desde el primer contacto con la solución hasta la conversión en cliente.  
Este enfoque responde a principios de arquitectura de la información que priorizan la simplicidad, la relevancia y la progresión lógica del contenido, asegurando que los visitantes comprendan de inmediato el valor del producto, su funcionamiento, los beneficios que ofrece y los pasos necesarios para adquirirlo.

---

## Inicio  
- **Objetivo:** Captar la atención del visitante con un mensaje directo y atractivo.  
- **Contenido:** Presentación del nombre del producto, propuesta de valor principal y un llamado a la acción (CTA).  

---

## Información explicativa  
- **Servicios:** Explicación funcionamiento del sistema.  
- **FAQ:** Listado de las soporte con explicacion para cada tipo de usuario.  
- **App:** Informacion sobre la aplaicacion de **WineInventory**.  

---

## Conversión  
- **Planes:** Presentación detallada de los diferentes planes de suscripción disponibles para los clientes.

<p align="center">
  <img src="../img/Chapter IV/landingpage.png">

  > <p align="center">Organización en el landing page</p>

La arquitectura jerárquica de la interfaz de la aplicación web **WineInventory** fue diseñada para facilitar el acceso y la gestión eficiente de sus múltiples funcionalidades.  
Esta organización permite una distribución lógica del contenido, reduciendo la carga cognitiva de los usuarios y mejorando su capacidad para ubicar rápidamente las herramientas que necesitan.

<p align="center">
  <img src="../img/Chapter IV/frontend.png">

  > <p align="center">Organización en la aplicación</p>

---

## Pantalla de inicio
La vista inicial presenta un **dashboard general** con los siguientes elementos:

- Tarjetas de resumen sobre stock actual, productos próximos a vencer y alertas activas.  
- Notificaciones destacadas relacionadas con vencimiento o bajo nivel de stock.  
- Gráficos simples que muestran tendencias recientes de entradas y salidas.  

---

## Navegación principal
La aplicación incorpora un sistema de navegación jerárquico mediante un **menú lateral** con iconografía clara, que organiza las siguientes secciones:

- Dashboard  
- Inventario  
- Zonas de almacenamiento  
- Alertas  
- Facturación  
- Guías  
- Perfil  

---

## Filtrado y organización avanzada

### a. Para dueños de licorerías
- **Filtros disponibles:** Tipo de producto, nivel de stock y fecha de vencimiento.  
- **Funciones principales:** Visualización de productos críticos, registro de entradas y salidas, y gestión de zonas de almacenamiento.  

### b. Para proveedores de licores
- **Filtros disponibles:** Temporalidad de pedidos (última semana, último mes).  
- **Funciones principales:** Emisión y consulta de guías, gestión de facturación y seguimiento de entregas.  

---

## Segmentación por audiencia

### a. Dueños de licorerías
- Enfoque en gestión de stock y reducción de pérdidas por caducidad.  
- Herramientas para registrar movimientos y planificar compras.  
- Visualización de productos prioritarios y reorganización de zonas de almacenamiento.  

### b. Proveedores de licores
- Acceso al historial de pedidos y entregas.  
- Información sobre demanda por producto y licorería.  
- Funcionalidades para seguimiento y emisión de guías y facturas directamente desde la plataforma.  

### 4.2.2. Labeling Systems ###

# Sistema de etiquetado en StockSip

El sistema de etiquetado de **WineInventory** fue diseñado para ser claro, conciso y fácil de interpretar.  
Se utilizan palabras clave con un número mínimo de términos, manteniendo siempre la precisión y evitando tecnicismos innecesarios.  
El objetivo es reducir la carga cognitiva del usuario y garantizar una experiencia más intuitiva.

---

## Principios

- **Consistencia**: Las etiquetas se mantienen uniformes en botones, menús y mensajes relacionados.  
  Ejemplo: *“Nuevo Producto”*, *“Ver Detalles”*.  

- **Simplicidad**: Se evitan jergas técnicas o frases extensas.  
  Ejemplo: *“Stock mínimo”*, *“Fecha de caducidad”*, *“Alerta activa”*.  

---

## Etiquetado en el Landing Page

- **Inicio**: Primera sección visible para el usuario. Resume de manera clara qué es StockSip y atrae la atención con un mensaje directo.  
- **Cómo Funciona**: Explica paso a paso el uso de la plataforma, mostrando lo sencillo que resulta gestionar el inventario.  
- **Beneficios**: Destaca las principales ventajas de la solución, como el ahorro de tiempo, la reducción de pérdidas y la toma de decisiones informadas.  
- **Testimonios**: Presenta opiniones de usuarios actuales, lo que refuerza la confianza en la plataforma.  
- **Planes**: Muestra los planes de suscripción disponibles, con precios, características y comparaciones para facilitar la elección.  

---

## Etiquetado en la Aplicación Web

- **Inventario**: Sección central destinada a la visualización y gestión del stock disponible.  
- **Nuevo Producto**: Permite registrar un nuevo artículo con sus datos básicos.  
- **Alertas**: Informa sobre productos próximos a caducar para agilizar decisiones.   
- **Reportes**: Área para la consulta y descarga de informes relacionados con movimientos e inventario.  
- **Configuración**: Espacio para personalizar preferencias, notificaciones y datos de la cuenta.  
- **Perfil**: Acceso a información personal, con opciones de edición y cierre de sesión.  


### 4.2.3. SEO Tags and Meta Tags ###

La página de aterrizaje de WineInventory comunica la propuesta de valor de la herramienta de forma breve y orientada a SEO, destacando su capacidad para optimizar la gestión de inventarios mediante alertas, recomendaciones y análisis inteligente para licorerías y proveedores.

**Landing Page**

- **Title:** 
<title>WineInventory</title>

- **Meta Description:**

<meta name="description" content="WineInventory es una plataforma pensada para licorerías y proveedores que facilita la gestión de inventario.">

- **Meta Keywords:**

<meta name="keywords" content="gestión de inventarios, licorerías, proveedores, plataforma de stock, control de vencimientos, optimización de productos, recomendaciones de compra, WineInventory">

- **Meta Author:**

<meta name="author" content="Equipo de WineInventory — Diseño UX/UI y Desarrollo Web">

---

**Web Application**

- **Title:**

<title>Panel de Control – WineInventory</title>

- **Meta Description:**

<meta name="description" content="En el Panel de Control de WineInventory el usuario encuentra toda la información operativa: administración de inventarios, reportes detallados, recomendaciones de compra y control de productos próximos a vencer, todo centralizado para facilitar la toma de decisiones.">

- **Meta Keywords:**

<meta name="keywords" content="dashboard de inventario, stock inteligente, gestión operativa, productos próximos a vencer, reportes automáticos, control para licorerías, recomendaciones de compra, WineInventory">

- **Meta Author:**

<meta name="author" content="Equipo de Desarrollo Web — WineInventory, 2025">

### 4.2.4. Searching Systems ###

En la sección de **Inventario**, el sistema de búsqueda está diseñado de forma sencilla y eficiente para que el usuario localice productos con rapidez. Se dispone un campo de búsqueda principal, ubicado en la parte superior de la tabla junto a los botones de acción, que permite filtrar por nombre de producto o por tipo (por ejemplo: `Whiskey`, `Vino`).

## Filtros de búsqueda

Al ejecutar una búsqueda, los resultados pueden afinarse mediante criterios relevantes que permiten adaptar la vista a necesidades concretas:

* **Categoría:** Filtrado por clase de bebida (destilados, vinos, cervezas, espumantes, etc.).
* **Disponibilidad por zona:** Comprobación de si el producto está disponible en alguna de las zonas definidas por el usuario.

## Resultados de búsqueda

Los resultados se muestran en una tabla de diseño visual pensado para ofrecer la información esencial de un vistazo. Cada fila contiene:

* Nombre del producto
* Tipo
* Precio
* Fecha de caducidad
* Stock actual
* Stock mínimo

Además, se emplea una codificación por colores para facilitar la lectura rápida del estado del inventario:

* **Verde:** Stock dentro de niveles aceptables.
* **Rojo:** Indica riesgo o alerta por bajo stock.

## Búsqueda avanzada (para proveedores)

WineInventory incorpora una búsqueda avanzada dirigida a proveedores de licores, con herramientas y recursos específicos:

* **Guías de conservación por tipo de producto:** Acceso a documentos y recomendaciones técnicas sobre las mejores prácticas de almacenamiento (temperatura, humedad, tiempos de conservación, etc.).
* **Planes de reabastecimiento:** Módulo que proyecta necesidades de reposición a partir de históricos de venta, frecuencia y patrones de consumo, facilitando la planificación logística y de compras.


### 4.2.5. Navigation Systems ###

**WineInventory** ofrece una experiencia de navegación pensada para que el usuario se desplace de forma clara y ágil tanto en la landing page como dentro de la aplicación web.

---

## Barra de navegación — Landing Page

En la página de aterrizaje, StockSip incorpora una barra de navegación fija que facilita el acceso rápido a las secciones principales destinadas a visitantes e interesados. Las opciones disponibles son:

* **Inicio**
* **Nosotros?**
* **Servicios**
* **Planes**
* **FAQ**
* **Acerca de**

<p align="center">
  <img src="../img/Chapter IV/nav.png">

  > <p align="center">Barra de navegación fija</p>

La barra se mantiene visible mientras el usuario explora la página para asegurar una navegación continua y directa hacia la información clave.

---

## Barra lateral — Aplicación web

Dentro de la aplicación, WineInventory utiliza una barra lateral fija con iconos que proporciona acceso inmediato a las funcionalidades esenciales del sistema. Las entradas del menú incluyen:

* **Inicio**
* **Inventario**
* **Alertas**
* **Reportes**
* **Compras**
* **Configuración**
* **Perfil**

Cada elemento se representa mediante un icono identificable y una etiqueta descriptiva que aparece al pasar el cursor o al expandir el menú, garantizando una interacción intuitiva y una navegación fluida en el entorno de trabajo.

---

WineInventory prioriza la claridad visual y la accesibilidad en su esquema de navegación para reducir fricción y permitir que los usuarios encuentren rápidamente las funcionalidades que necesitan.

## _4.3. Landing Page UI Design_ ##

### 4.3.1. Landing Page Wireframe ###



### 4.3.2. Landing Page Mock-up ###



## _4.4. Web Applications UX/UI Design_ ##

### 4.4.1. Web Applications Wireframes ###



### 4.4.2. Web Applications Wireflow Diagrams ###



### 4.4.3. Web Applications Mock-ups ###



### 4.4.4. Web Applications Userflow Diagrams ###



## _4.5. Web Applications Prototyping_ ##



## _4.6. Domain-Driven Software Architecture_ ##



### 4.6.1. Design-Level Event Storming ###



### 4.6.2. Software Architecture Context Diagram ###



### 4.6.3. Software Architecture Container Diagrams ###



### 4.6.4. Software Architecture Components Diagrams ###



## _4.7. Software Object-Oriented Design_ ##



### 4.7.1. Class Diagram ###



## _4.8. Database Design_ ##

### 4.8.1. Database Diagram ###


