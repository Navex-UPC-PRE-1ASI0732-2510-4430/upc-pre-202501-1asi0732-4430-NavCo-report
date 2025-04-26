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

### Software Deployment Configuration

> En esta sección, describiremos la configuración necesaria para
> desplegar satisfactoriamente cada uno de los productos digitales de
> nuestra solución, incluyendo Landing Page, los Web Services.

Pasos para el despliegue

1.  Landing Page:

- Clonar o descargar el repositorio desde GitHub.

- Configurar el servidor web para alojar la Landing Page.

- Copiar los archivos HTML5, CSS y JavaScript en el directorio
  correspondiente del servidor.

- Configurar cualquier dependencia adicional, como bibliotecas de
  JavaScript o imágenes.

- Verificar que la Landing Page se cargue correctamente en el navegador.

2.  Web Services (API):

- Preparar el código fuente del servicio web, asegurando que esté
  correctamente estructurado y documentado.

- Configurar un entorno de desarrollo o pruebas para realizar pruebas
  exhaustivas del servicio antes del despliegue.

- Desplegar el código en un servidor adecuado para el entorno de
  producción.

- Configurar la seguridad y la autenticación según los requisitos del
  sistema.

- Documentar la API utilizando OpenAPI Specification para facilitar su
  integración y uso por parte de otros sistemas.

## Product Implementation & Deployment

### Sprint Backlogs

> El Sprint está centrado en la versión inicial de nuestro servicio web,
> priorizando las historias de usuario identificadas. Nuestro objetivo
> principal es proporcionar a los usuarios una experiencia inicial
> sólida al presentar una navegación intuitiva y acceso rápido a las
> funcionalidades relevantes. Al completar las tareas asociadas a las
> historias de usuario definidas, sentaremos una buena base para el
> servicio web, asegurando que lo propuesto contribuya al éxito del
> proyecto.

+------+----------+-----+------+-----------+-----+--------+----------+
| > Sp | > Sprint |     |      |           |     |        |          |
| rint | > 1      |     |      |           |     |        |          |
| > \# |          |     |      |           |     |        |          |
+======+==========+=====+======+===========+=====+========+==========+
| >    | > W      |     |      |           |     |        |          |
| User | ork-Item |     |      |           |     |        |          |
| > S  | > / Task |     |      |           |     |        |          |
| tory |          |     |      |           |     |        |          |
+------+----------+-----+------+-----------+-----+--------+----------+
| > Id | > Title  | >   | > T  | > De      | > E | > As   | > Status |
|      |          |  Id | itle | scripción | sti | signed | > (To-do |
|      |          |     |      |           | mat | > to   | > / In / |
|      |          |     |      |           | ion |        | >        |
|      |          |     |      |           | > ( |        |  Process |
|      |          |     |      |           | Hou |        | > /      |
|      |          |     |      |           | rs) |        | >        |
|      |          |     |      |           |     |        | >        |
|      |          |     |      |           |     |        | ToReview |
|      |          |     |      |           |     |        | >        |
|      |          |     |      |           |     |        | > /      |
|      |          |     |      |           |     |        | > Done)  |
+------+----------+-----+------+-----------+-----+--------+----------+
| >    | > Visua  | >   | > De | > Crear   | > 4 |        | > Done   |
| US01 | lización | T01 | sarr | > una     |     |        |          |
|      | > de     |     | ollo | >         |     |        |          |
|      | >        |     | > de |  interfaz |     |        |          |
|      | paquetes |     | >    | > para la |     |        |          |
|      | > en     |     | inte | > a       |     |        |          |
|      | tregados |     | rfaz | plicación |     |        |          |
|      | > por un |     | > y  | > web que |     |        |          |
|      | > trans  |     | > ló | > permita |     |        |          |
|      | portista |     | gica | > al      |     |        |          |
|      |          |     | >    | > gerente |     |        |          |
|      |          |     | para | > se      |     |        |          |
|      |          |     | > v  | leccionar |     |        |          |
|      |          |     | isua | > un      |     |        |          |
|      |          |     | liza | > tran    |     |        |          |
|      |          |     | ción | sportista |     |        |          |
|      |          |     | > de | > y       |     |        |          |
|      |          |     | >    | > v       |     |        |          |
|      |          |     | paqu | isualizar |     |        |          |
|      |          |     | etes | > el      |     |        |          |
|      |          |     | > en | >         |     |        |          |
|      |          |     | treg |  registro |     |        |          |
|      |          |     | ados | > de      |     |        |          |
|      |          |     |      | >         |     |        |          |
|      |          |     |      |  paquetes |     |        |          |
|      |          |     |      | > que ha  |     |        |          |
|      |          |     |      | > e       |     |        |          |
|      |          |     |      | ntregado. |     |        |          |
+------+----------+-----+------+-----------+-----+--------+----------+

+------+----------+-----+------+-----------+-----+--------+----------+
| >    | > Visua  | >   | > Im | > Crear   | > 5 | > Ma   | > Done   |
| US04 | lización | T02 | plem | > una     |     | uricio |          |
|      | > de     |     | enta | >         |     | >      |          |
|      | > envíos |     | ción |  interfaz |     | Chacon |          |
|      | > a      |     | > de | > en la   |     |        |          |
|      | signados |     | >    | > a       |     |        |          |
|      |          |     |  sis | plicación |     |        |          |
|      |          |     | tema | > web     |     |        |          |
|      |          |     | > de | > donde   |     |        |          |
|      |          |     | > v  | > los     |     |        |          |
|      |          |     | isua | > trans   |     |        |          |
|      |          |     | liza | portistas |     |        |          |
|      |          |     | ción | > puedan  |     |        |          |
|      |          |     | > de | > ver los |     |        |          |
|      |          |     | > en | > envíos  |     |        |          |
|      |          |     | víos | > que les |     |        |          |
|      |          |     | > a  | > han     |     |        |          |
|      |          |     | sign | > sido    |     |        |          |
|      |          |     | ados | > a       |     |        |          |
|      |          |     |      | signados, |     |        |          |
|      |          |     |      | > junto   |     |        |          |
|      |          |     |      | > con     |     |        |          |
|      |          |     |      | > todos   |     |        |          |
|      |          |     |      | > los     |     |        |          |
|      |          |     |      | >         |     |        |          |
|      |          |     |      |  detalles |     |        |          |
|      |          |     |      | > r       |     |        |          |
|      |          |     |      | elevantes |     |        |          |
|      |          |     |      | > (       |     |        |          |
|      |          |     |      | destinos, |     |        |          |
|      |          |     |      | >         |     |        |          |
|      |          |     |      | horarios, |     |        |          |
|      |          |     |      | > etc.).  |     |        |          |
+======+==========+=====+======+===========+=====+========+==========+
| >    | > Visua  | >   | > De | > Crear   | > 4 |        | > Done   |
| US06 | lización | T03 | sarr | > una     |     |        |          |
|      | > de     |     | ollo | > sección |     |        |          |
|      | >        |     | > de | > en      |     |        |          |
|      | reportes |     | >    | > laa     |     |        |          |
|      | > re     |     | inte | plicación |     |        |          |
|      | alizados |     | rfaz | > web     |     |        |          |
|      |          |     | > y  | > donde   |     |        |          |
|      |          |     | > ló | > los     |     |        |          |
|      |          |     | gica | > trans   |     |        |          |
|      |          |     | >    | portistas |     |        |          |
|      |          |     | para | > puedan  |     |        |          |
|      |          |     | > v  | > ver un  |     |        |          |
|      |          |     | isua | >         |     |        |          |
|      |          |     | liza | historial |     |        |          |
|      |          |     | ción | > de      |     |        |          |
|      |          |     | > de | > todos   |     |        |          |
|      |          |     | >    | > los     |     |        |          |
|      |          |     | repo | >         |     |        |          |
|      |          |     | rtes |  reportes |     |        |          |
|      |          |     | > re | > de      |     |        |          |
|      |          |     | aliz | > in      |     |        |          |
|      |          |     | ados | cidencias |     |        |          |
|      |          |     |      | > que se  |     |        |          |
|      |          |     |      | > han     |     |        |          |
|      |          |     |      | > r       |     |        |          |
|      |          |     |      | ealizado. |     |        |          |
+------+----------+-----+------+-----------+-----+--------+----------+
| >    | > As     | >   | > De | > Crear   | > 4 |        | > Done   |
| US07 | ignación | T04 | sarr | > una     |     |        |          |
|      | > de     |     | ollo | > sección |     |        |          |
|      | > envíos |     | > de | > en la   |     |        |          |
|      |          |     | >    | > a       |     |        |          |
|      |          |     | inte | plicación |     |        |          |
|      |          |     | rfaz | > web que |     |        |          |
|      |          |     | > y  | > permita |     |        |          |
|      |          |     | > ló | > al      |     |        |          |
|      |          |     | gica | > gerente |     |        |          |
|      |          |     | >    | > se      |     |        |          |
|      |          |     | para | leccionar |     |        |          |
|      |          |     | > as | > y       |     |        |          |
|      |          |     | igna | > asignar |     |        |          |
|      |          |     | ción | > envíos  |     |        |          |
|      |          |     | > de | > a los   |     |        |          |
|      |          |     | > en | > transp  |     |        |          |
|      |          |     | víos | ortistas. |     |        |          |
+------+----------+-----+------+-----------+-----+--------+----------+

### Implemented Landing Page Evidence

Se desarrolló e implementó una landing page funcional con diseño
responsivo, orientada a captar usuarios y prestar los servicios clave de
la plataforma.

![](media/image52.png){width="6.267716535433071in"
height="3.0972222222222223in"}

![](media/image90.png){width="6.267716535433071in"
height="3.7916666666666665in"}

Link:
[[https://navex-upc-pre-1asi0732-2510-4430.github.io/upc-pre-202501-1asi0732-4430-NavCo-landing-page/]{.underline}](https://navex-upc-pre-1asi0732-2510-4430.github.io/upc-pre-202501-1asi0732-4430-NavCo-landing-page/)

### Implemented Web Application Evidence

En NaVex se construyó la interfaz del usuario utilizando tecnologías web
modernas (HTML, CSS, JavaScript y Vue), asegurando una navegación
fluida, componentes interactivos y una experiencia de usuario optimizada
en distintos dispositivos.

### Implemented Mobile Application Evidence

### Implemented Backend Evidence

### Team Collaboration Insights

Durante este primer Sprint, hemos completado el desarrollo del Landing
Page y hemos colaborado estrechamente en su implementación. La
colaboración entre los miembros del equipo se refleja en los diversos
commits realizados en el repositorio de GitHub, los cuales han sido
debidamente documentados en las capturas de pantalla adjuntas. Para
asegurar una colaboración efectiva, hemos implementado GitFlow como
nuestra metodología de trabajo colaborativo en Git. Usando GitFlow,
hemos creado ramas para cada una de las secciones de nuestra landing
page.

Esto nos ha permitido trabajar de manera organizada y centrarnos en
completar correctamente las historias de usuario designadas para cada
sección. En cuanto a la elaboración del código, hemos asignado a cada
miembro del equipo una sección específica del landing page. Esta
estrategia nos ha permitido avanzar de manera más eficiente y completar
el trabajo antes de la fecha de entrega. Además, hemos realizado
reuniones adicionales para intercambiar ideas y resolver cualquier duda
o problema que pudiera surgir durante el desarrollo del landing page.
Estas sesiones han contribuido de manera positiva al éxito del proyecto.
A continuación, presentamos algunas capturas de pantalla que muestran
los commits realizados por los miembros del equipo en GitHub:

FOTO DE BRANCHES Y LOS CONVENTIONAL COMMITS DE CADA UNO

## Video About-the-Product

# Conclusiones y recomendaciones:

La introducción del enfoque Lean UX en la etapa inicial del proyecto fue
fundamental para establecer una comprensión profunda de las necesidades
del usuario y orientar de forma efectiva el desarrollo de nuestra
propuesta de servicio. Este enfoque facilitó la integración de
metodologías ágiles y centradas en el usuario, permitiendo una mejor
definición de los segmentos de mercado y una validación continua de las
decisiones de diseño.

El desarrollo de NavEx, una aplicación dirigida a transportistas y
empresarios con flotas de transporte, se benefició significativamente de
este marco metodológico. Gracias a un análisis exhaustivo de los
principales problemas del sector y a entrevistas directas con usuarios
potenciales, se identificaron oportunidades clave para mejorar la
experiencia del usuario. Esta retroalimentación permite ajustar
funcionalidades críticas para asegurar que la solución sea relevante,
intuitiva y funcional.

Durante este sprint, la planificación estructurada, el cumplimiento
riguroso del Sprint Backlog y la ejecución de pruebas fueron pilares del
progreso alcanzado. La documentación detallada de los servicios y
funcionalidades implementadas contribuyó a mantener la trazabilidad del
proyecto y a facilitar futuras iteraciones. El trabajo colaborativo, la
organización interna y la adaptación ante los desafíos técnicos
demostraron la solidez del equipo, posicionando a NavEx como una
solución viable y competitiva dentro del mercado de gestión de
transporte.

**Recomendaciones**

1.  Continuar aplicando Lean UX en las siguientes fases del desarrollo
    para mantener una visión centrada en el usuario y asegurar una
    evolución coherente del producto.

2.  Reforzar la validación con usuarios reales a través de pruebas de
    usabilidad y encuestas, para garantizar que cada iteración responda
    a necesidades concretas.

3.  Mantener una documentación técnica actualizada y detallada que
    facilite la escalabilidad del sistema y permita una integración
    fluida de nuevos miembros al equipo.

4.  Fomentar la mejora continua en los procesos de trabajo en equipo,
    incentivando espacios de retroalimentación regular y sesiones de
    revisión colaborativa.

# Video About-the-Team
**[Link:]{.underline}**

# Bibliografía

- Gajewska, T. & Walczyk, D. (2023). Development of Transport Management
  Software. *Sustainability (Multidisciplinary Digital Publishing
  Institute)*, *15*(15), 12083.
  [[https://doi.org/10.3390/su151512083]{.underline}](https://doi.org/10.3390/su151512083)

- Gothelf, J. & Seiden, J. (2021). Lean UX, 3rd Edition. O'Railly Media,
  Inc.
  [[https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/]{.underline}](https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/)

- He, L., Liu, S. & Shen, Z. M. (2022). Smart urban transport and
  logistics: A business analytics perspective. *Production and
  Operations Management*, *31*(10), 3771-3787.
  [[https://doi.org/10.1111/poms.13775]{.underline}](https://doi.org/10.1111/poms.13775)

- Instituto Nacional de Estadística e Informática. (2024). *A nivel
  nacional el movimiento de vehículos aumentó 6,1% en abril de 2024*
  (Nota de Prensa N°96).
  [[https://m.inei.gob.pe/media/MenuRecursivo/noticias/nota-de-prensa-n-096-2024-inei.pdf]{.underline}](https://m.inei.gob.pe/media/MenuRecursivo/noticias/nota-de-prensa-n-096-2024-inei.pdf)

- International Bank for Reconstruction and Development. (2023).
  *Connecting to Compete, Trade Logistics in the Global Economy*. The
  World Bank.
  [[https://lpi.worldbank.org/sites/default/files/2023-04/LPI_2023_report_with_layout.pdf]{.underline}](https://lpi.worldbank.org/sites/default/files/2023-04/LPI_2023_report_with_layout.pdf)

- International Transport Forum. (2023). *ITF Transport Outlook 2023*,
  OECD Publishing. Paris,
  [[https://doi.org/10.1787/b6cc9ad5-en]{.underline}](https://doi.org/10.1787/b6cc9ad5-en)

- Jiao, H. & Zhang, S. (2024). Multi-objective optimization of urban
  logistics land: a gradient-based method approach with Wuhan city as an
  example. *International Journal of Digital Earth, 18*(1), 1 - 17.
  [[https://doi.org/10.1080/17538947.2024.2449568]{.underline}](https://doi.org/10.1080/17538947.2024.2449568)

- Keil, M., Hagemann, V. & Glock, C. (2025). Promoting healthy and safe
  driving: Physiological and psychological evaluation of truck drivers
  for individualized shift and route planning. *Transportation Research
  Part F: Traffic Psychology and Behaviour, 111,* 409-434.
  [[https://doi.org/10.1016/j.trf.2025.03.017]{.underline}](https://doi.org/10.1016/j.trf.2025.03.017)

- Ministerio de Transporte y Comunicaciones. (2023). ANUARIO
  ESTADÍSTICO 2023.
  [[https://cdn.www.gob.pe/uploads/document/file/6778343/5871728-anuario-estadistico-2023.pdf]{.underline}](https://cdn.www.gob.pe/uploads/document/file/6778343/5871728-anuario-estadistico-2023.pdf)

- Mordor Intelligence. (2024). *Análisis de participación y tamaño del
  mercado de transporte de carga por carretera en Perú tendencias de
  crecimiento y pronósticos (2024-2029)*. Recuperado el 11 de abril de
  2025, de
  [[https://www.mordorintelligence.com/es/industry-reports/peru-road-freight-transport-market]{.underline}](https://www.mordorintelligence.com/es/industry-reports/peru-road-freight-transport-market)

- Nchimbi, S. A., Kisangari, M., Dida, M. A. & Barakabitze, A. A.
  (2022). Design a Services Architecture for Mobile-Based Agro-Goods
  Transport and Commerce System. *Mobile Information Systems*,
  *2022*(1), 1-10.
  [[https://doi.org/10.1155/2022/6041197]{.underline}](https://doi.org/10.1155/2022/6041197)

- Patil, D., Mane, S., Biradar, S., Rankhamb, S. & Bhonsle, M. (2023).
  *Fleet Management Mobile Application Using GPS Shortest Path*
  \[Documento de conferencia\]. International Conference on Data
  Intelligence and Cognitive Informatics, Tirunelveli, India.
  [[https://link.springer.com/chapter/10.1007/978-981-99-7962-2_16]{.underline}](https://link.springer.com/chapter/10.1007/978-981-99-7962-2_16)

- Patnaik, D. (2017). Needfinding: Design Research and Planning (4th
  Edition). CreateSpace Independent Publishing Platform.
  [[https://www.amazon.com/Needfinding-Design-Research-Planning-4th/dp/1974015580]{.underline}](https://www.amazon.com/Needfinding-Design-Research-Planning-4th/dp/1974015580)

- Pouliou, A., Kehagia, F. & Meselidis, C. (2025). A Model for the Crash
  Occurrence in Unexpected Incidents. *Transport and Telecommunication
  Journal*, *26*(1), 33-44.
  [[https://doi.org/10.2478/ttj-2025-0004]{.underline}](https://doi.org/10.2478/ttj-2025-0004)

- SafeLink Group. (2024). ¿Cuáles son los principales problemas de
  seguridad en el transporte de carga en Perú? SafeLink Marine.
  Recuperado el 15 de abril de 2025, de
  [[https://www.safelinkmexico.com/cuales-son-los-principales-problemas-de-seguridad-en-el-transporte-de-carga-en-peru/]{.underline}](https://www.safelinkmexico.com/cuales-son-los-principales-problemas-de-seguridad-en-el-transporte-de-carga-en-peru/)

- Smith, P, R. & Zook, Z.(2022). Marketing Communications: Integrating
  Online and Offline, Customer Engagement and Digital Technologies.
  Kogan Page.
  [[https://www.perlego.com/book/1589959/marketing-communications-integrating-online-and-offline-customer-engagement-and-digital-technologies-pdf]{.underline}](https://www.perlego.com/book/1589959/marketing-communications-integrating-online-and-offline-customer-engagement-and-digital-technologies-pdf)

- Sun, P. F., Zhang, Y., Wu, X. J., Du, J. Y., Hou, R. R. & Liu, J.
  (2024). SIMULATION AND ANALYSIS OF A PREEMPTIVE TRANSPORTATION MODEL
  USING FLEXSIM SOFTWARE. *International Journal of Simulation
  Modelling*, *23*(2), 335-346.
  [[https://doi.org/10.2507/IJSIMM23-2-CO7]{.underline}](https://doi.org/10.2507/IJSIMM23-2-CO7)

- Superintendencia de Transporte Terrestre de Personas, Carga y
  Mercancías. (2023). *MEMORIA ANUAL 2023*. Ministerio de Transportes y
  Comunicaciones.
  [[https://cdn.www.gob.pe/uploads/document/file/7461251/6352814-memoria-anual-2023.pdf?v=1736265456]{.underline}](https://cdn.www.gob.pe/uploads/document/file/7461251/6352814-memoria-anual-2023.pdf?v=1736265456)

- Superintendencia de Transporte Terrestre de Personas, Carga y
  Mercancías. (2024). REPORTE ESTADÍSTICO N.º 05-2023: FISCALIZACIÓN CON
  CINEMÓMETROS (Del 01 de enero al 31 de diciembre de 2023). Ministerio
  de Transportes y Comunicaciones.
  [[https://cdn.www.gob.pe/uploads/document/file/5784678/5137004-reporte-estadistico-n-005-2023-fiscalizacion-con-cinemometros.pdf?v=1706720388]{.underline}](https://cdn.www.gob.pe/uploads/document/file/5784678/5137004-reporte-estadistico-n-005-2023-fiscalizacion-con-cinemometros.pdf?v=1706720388)

- Wheeler, A. & Meyerson, R. (2024). Designing Brand Identity: A
  Comprehensive Guide to the World of Brands and Branding. Wiley.
  [[https://www.amazon.com/-/es/Alina-Wheeler-ebook/dp/B0CVVNPZWG?ref\_=ast_author_mpb]{.underline}](https://www.amazon.com/-/es/Alina-Wheeler-ebook/dp/B0CVVNPZWG?ref_=ast_author_mpb)

**Anexos**

- **PivotalTracker-ProductBacklog:**

- **Registro de Entrevistas:**

- **Figma de Proyecto:**

- **LandingPage:[[https://navex-upc-pre-1asi0732-2510-4430.github.io/upc-pre-202501-1asi0732-4430-NavCo-landing-page/]{.underline}](https://navex-upc-pre-1asi0732-2510-4430.github.io/upc-pre-202501-1asi0732-4430-NavCo-landing-page/)**

##
