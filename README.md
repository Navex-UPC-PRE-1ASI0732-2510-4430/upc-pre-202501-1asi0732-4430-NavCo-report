<div align="center">

# Informe del Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">

**Universidad Peruana de Ciencias Aplicadas**

**FACULTAD DE INGENIERÍA**

**2025-01**

**Diseños de Experimentos de Ingeniería de Software**

**Sección:** 4430

**Docente:** Juan Carlos Tinoco Licas

**Informe del Trabajo Final**

**Nombre del Startup:** NavCo

**Nombre del Producto:** Navex

**Integrantes:**

Pinto Fuentes Rivera, Alvaro Felipe - U202213384

Loarte Matos, Anthony Brahan - U20211D563

Bustamante Leveau, Cameron Charllotte - U20231A804

Armestar Heredia, Matias Gabriel - U20221A553

Chacon Martinez, Mauricio Sebastian - U202212911


<hr>
<br>
<div align="justify">



# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

> Para administrar la configuración de software de nuestra app, nos
> centraremos en tres aspectos principales: el control del código
> fuente, que implica gestionar las versiones y establecer una
> estructura organizada para el código; la configuración del entorno de
> desarrollo, donde nos aseguramos de que todos los miembros del equipo
> cuenten con herramientas consistentes; y la configuración de
> implementación, que se ocupa del despliegue en entornos de producción.
> Estas decisiones garantizan la coherencia y eficacia a lo largo de
> todo el ciclo de vida de la aplicación.

### 5.1.1. Software Development Environment Configuration

> En esta sección, detallaremos y explicaremos los productos utilizados
> en el proyecto digital, así como su propósito y cómo se accede a cada
> uno de ellos y siguiendo las restricciones establecidas.

1.  Project Management: Para gestionar el proyecto, se utilizaron
    herramientas de comunicación y control de versiones. Se estableció
    una organización en GitHub para gestionar el código y las versiones
    del proyecto. Además, para las reuniones de equipo y la comunicación
    interna, se utilizaron plataformas como Google Meet y Discord.

- Github: [[https://github.com/]{.underline}](https://github.com/)

- Google Meet:
  [[https://meet.google.com/]{.underline}](https://meet.google.com/)

- Discord:
  [[https://discord.com/download]{.underline}](https://discord.com/download)

2.  Requirements Management: Para la gestión de requisitos se llevó a
    cabo mediante el uso de herramientas personalizadas que permitieron
    recopilar, organizar y priorizar los requisitos del proyecto de
    manera eficiente. Se utilizó Trello, una herramienta visual para la
    gestión de requisitos, permitiendo la creación tableros
    personalizados para organizar y priorizar las tareas del proyecto
    que permitió realizar los Task board y Pivotal Tracker, utilizado
    para gestionar y realizar un seguimiento del Product Backlog del
    proyecto.

- Trello: [[https://trello.com/es]{.underline}](https://trello.com/es)

- Pivotal Tracker:
  [[https://www.pivotaltracker.com/]{.underline}](https://www.pivotaltracker.com/)

3.  Product UX/UI Design:Para el diseño de la experiencia de usuario
    (UX) y diseño de interfaz de usuario (UI) del producto se utilizó la
    herramienta Figma, esta herramienta permitió al equipo crear
    wireframes, mockups y prototipos interactivos para visualizar y
    validar el diseño del producto antes de la implementación. Por otro
    lado, para la creación de User Personas, Empathy Maps, Journey Maps
    e Impact Maps se utilizó UXPressia y para la creación de As-Is y
    To-Be Scenario Maps se utilizó Miro.

- Figma:
  [[https://www.figma.com/downloads/]{.underline}](https://www.figma.com/downloads/)

- UXPressia:
  [[https://uxpressia.com/]{.underline}](https://uxpressia.com/)

- Miro: [[https://miro.com/es/]{.underline}](https://miro.com/es/)

4.  Software Development: Para el desarrollo de software se utilizó
    HTML5, CSS3 y JavaScript para el desarrollo de la Landing Page de la
    startup, por otro lado, para la creación del Mobile Application de
    la startup se utilizará Kotlin por el lado del Frontend y en el
    Backend se utilizará ASP.NET Core Framework y C#. Para trabajar con
    estas tecnologías, se emplearon los siguientes IDEs: Visual Studio
    Code: Herramienta principal para el desarrollo Frontend y Backend,
    que ofrece una amplia gama de extensiones para mejorar la
    productividad del equipo. (En nuestro caso solo fue utilizado para
    la Landing Page). JetBrains Toolbox: Proporciona un entorno
    integrado para el desarrollo web, con características avanzadas de
    edición y depuración que facilitan la creación de aplicaciones web
    robustas.

- Visual Studio Code:
  [[https://code.visualstudio.com/]{.underline}](https://code.visualstudio.com/)

- JetBrains Toolbox:
  [[https://www.jetbrains.com/toolbox-app/]{.underline}](https://www.jetbrains.com/toolbox-app/)

5.  Software Documentation: La documentación del software se realizó
    utilizando GitHub, además de ser utilizado como plataforma de
    control de versiones, GitHub también se empleó para alojar la
    documentación técnica del proyecto. Se crearon repositorios
    específicos para almacenar toda la información. La documentación se
    gestionó mediante archivos Markdown para facilitar la creación y
    edición colaborativa.

- GitHub: [[https://github.com/]{.underline}](https://github.com/)

### 5.1.2. Source Code Management

> En este proyecto, utilizaremos GitHub como plataforma y sistema de
> control de versiones para gestionar el código fuente de nuestras
> diferentes partes del proyecto dentro de una organización. GitFlow
> Workflow Implementaremos el modelo GitFlow como Workflow de control de
> versiones, siguiendo las convenciones y prácticas establecidas para
> una gestión eficiente del desarrollo de software.

1.  Branches Principales

- main: Rama principal del repositorio, contiene el código estable y
  liberado.

- develop: Rama de desarrollo donde se integran las nuevas
  características y mejoras.

2.  Branches de Funcionalidades (Feature Branches)

- Para cada nueva funcionalidad, se creará una rama de funcionalidad con
  el prefijo feature/, seguido del nombre descriptivo de la función o
  característica. En nuestro caso, creamos 5 branches de características
  correspondientes a los 5 capítulos de nuestro informe, donde se
  realizan los commits respectivos antes de fusionarlos con la rama
  develop cuando estén listos.

3.  Branches de Lanzamiento (Release Branches) y Branches de Corrección
    (Hotfix Branches): En nuestro caso, no hicimos uso de estas branches
    ya que no lo vimos necesario al ser solo documentación del reporte.

> Versionado Semántico Seguimos la especificación Semantic Versioning
> 2.0.0 para nombrar nuestras versiones, siguiendo el formato:
> MAJOR.MINOR.PATCH.
>
> Conventional Commits Aplicamos el estándar de Conventional Commits
> para los mensajes de commit, siguiendo un formato estructurado que
> describe claramente los cambios realizados. Esto nos ayudó a
> automatizar la generación de notas de versión y facilitar la
> comprensión del historial de cambios del proyecto.
>
> Con estas prácticas y convenciones adaptadas a una organización en
> GitHub, buscamos mantener un flujo de desarrollo ordenado,
> colaborativo y bien documentado.

### 5.1.3. Source Code Style Guide & Conventions
> En esta sección, se establece las convenciones y prácticas que
> seguiremos para nombrar elementos y programar en los lenguajes
> utilizados en la solución, que incluyen HTML, CSS, JavaScript, Kotlin,
> C#, y Gherkin para los archivos .feature. Todas las convenciones
> seguirán la nomenclatura en inglés y adoptarán convenciones estándares
> de codificación.

1.  HTML y CSS:

- Basado en las recomendaciones de W3C y otras fuentes de la comunidad,
  se establecerán convenciones para el nombramiento de elementos hTML y
  estilo de la codificación CSS.

- Se seguirán las convenciones recomendadas por Google para HTML y CSS,
  que incluyen el uso de indentaciones de 2 espacios, el uso de comillas
  dobles para atributos y el uso de comentarios descriptivos.

- Se utilizará la metodología BEM para organizar las clases CSS en
  bloques, elementos y modificadores, lo que facilitará la modularidad y
  la reutilización del código.

- Se debe utilizar los elementos HTML de manera semántica para una
  correcta descripción del contenido del sitio web, incluyendo el uso
  adecuado de etiquetas.

- Para el desarrollo con Vue.js, se adoptarán las convenciones
  recomendadas por la comunidad de Vue, que incluyen el uso de
  PascalCase para los nombres y componentes y el uso de camelCase para
  las propiedades y métodos de los componentes.

2.  JavaScript:

- Se tomarán en cuenta las directrices proporcionadas por MDN para la
  escritura de JavaScript, que incluyen el uso de nombres descriptivos
  para variables y funciones en camelCase, el uso de declaración de
  variables con let o const en lugar de var, y el uso de punto y coma al
  final de cada declaración.

- Se seguirán las convenciones de codificación recomendadas por Google
  para JavaScript, que incluyen el uso de comillas simples para
  literales de cadena, el uso de comentarios descriptivos y el uso de
  funciones de flecha para expresiones de función.

3.  Kotlin:

- Se adoptarán las convenciones de codificación recomendadas por la
  comunidad de aplicaciones Kotlin.

4.  C#(ASP.NET Core)

- Se seguirán las convenciones de codificación establecidas por
  Microsoft para el lenguaje C#, que incluyen el uso de PascalCase para
  nombres de clases y métodos, el uso de camelCase para nombres de
  variables locales y parámetros, y el uso de comentarios XML para
  documentar el código.

- Para el desarrollo en ASP.NET Core, se adoptarán las directrices
  proporcionadas por Microsoft en sus guías de codificación, que
  incluyen el uso de inyección de dependencias, la separación clara
  entre capas de la aplicación y el uso de modelos de vista para la
  comunicación entre el controlador y la vista.

5.  Gherkin

- Se aplicarán las convenciones recomendadas para escribir
  especificaciones legibles en Gherkin, que incluyen el uso de palabras
  clave como Given, When y Then para describir el comportamiento del
  sistema, el uso de un lenguaje sencillo y claro, y la organización de
  los escenarios en contextos, acciones y resultados.

- Se seguirán las mejores prácticas recomendadas por Cucumber para
  escribir escenarios de prueba en Gherkin, que incluyen la
  reutilización de pasos de prueba, la modularización de escenarios y la
  escritura de pruebas autoexplicativas.

Además de estas referencias, se promoverá el uso de buenas prácticas y
metodologías

> estándar en el desarrollo de software, como la modularidad, la
> reutilización de código, la legibilidad del código, la optimización
> del rendimiento y la seguridad. Con estas guías de estilo y
> convenciones de codificación, buscamos asegurar la coherencia, la
> calidad y la mantenibilidad del código a lo largo de todo el proyecto.
