Curso introductorio a las tecnologías geoespaciales, entre ellas los
Sistemas de Información Geográfica (SIG)
================
José Martínez
2025-02-01

> El repo GitHub de este curso, conteniendo dossier y programa, se
> encuentra [aquí](https://github.com/geofis/curso-tg-enero-2025)

<figure>
<img src="qr.jpg" style="width:25.0%" alt="Visita el repo en GitHub" />
<figcaption aria-hidden="true">Visita el repo en GitHub</figcaption>
</figure>

> La versión más legible (HTML) del curso se encuentra
> [aquí](https://geofis.github.io/curso-tg-enero-2025/README.html)

<!-- # OUTPUT FORMAT -->
<!-- ```{r} -->
<!-- output_format -->
<!-- ``` -->

# Fecha

- Días: aula FC-101
- Horario: 3 a 7 pm
- Lugar: 6 y 7 de febrero, 2025

![Localización del aula FC-101. En [este
HTML](https://geofis.github.io/curso-tg-enero-2025/README.html) se ve
mejor](map.png)

# Programa

## Día 1: Introducción a las tecnologías geoespaciales

> Se añadirán pausas cortas de 5 minutos entre sesiones.

### Primera sesión (1 hora)

- Introducción a las tecnologías geoespaciales, entre ellas los Sistemas
  de Información Geográfica (SIG)
- Breve historia y evolución, comenzando en los SIG
- Aplicaciones de las tecnologías geoespaciales en diversas disciplinas

### Segunda sesión (1.5 horas)

- Ejercicios prácticos:
  1.  Interfaz gráfica de QGIS
  2.  SRC (CRS), fuentes (WMS) para colocar como base
  3.  Cargar una fuente ráster, identificar, enmascarar, analizar,
      exportar
  4.  Cargar una fuente vectorial, seleccionar, identificar, modificar
  5.  ¿Python? ¿R? ¿Qué pintan en las tecnologías geoespaciales?

### Tercera sesión (1.5 horas)

- Formulación de “proyectos analíticos”. En el ámbito del curso, los
  proyectos son las distintas piezas que apoyan estudios reales,
  específicamente, necesidades muy concretas que la información y las
  técnicas geoespaciales, así como el software asociado, podrían ayudar
  a resolver. Dos ejemplos:

  - Realizar un diseño de muestreo espacial estratificado para
    garantizar muestra representativa y que ayude a responder la
    pregunta de investigación planteada. Resuelto esto, se podrían
    intentar pasos siguientes, como por ejemplo, cómo colectar datos en
    terreno con coordenada siguiendo el diseño, cómo preparar cuadernos
    de análisis para cuando lleguen los datos, cómo redactar resultados
    integrados con código, etc.

  - Obtener información de una fuente de uso y cobertura del suelo para,
    por ejemplo, usarla como covariable en un modelo. Resuelto esto, se
    podría intentar avanzar en el procesamiento, por ejemplo, generar
    unidades de análisis (un kernel), preparar los análisis o redactar
    de forma integrada los resultados.

- Votación de proyectos, orden de prelación.

## Día 2. Desarrollo de proyectos

### Primera sesión. Desarrollo del proyecto 1 (1.5 horas)

- Planteamiento del problema
- Evaluación de alternativas
- Implementación

### Segunda sesión. Desarrollo del proyecto 2 (1.5 horas)

- Mismo esquema que la anterior

### Tercera sesión (1 hora)

- ¿Necesito esto de las tecnologías geoespaciales realmente? ¿Necesito
  un nivel avanzado?
- Próximos pasos

# Recursos

## Hardware necesario

- **(imprescindible)** Necesitarás una PC o Mac. Mi capacidad de dar
  soporte de instalación de paquetes de software en Windows y MacOS es
  muy limitada. Alguna IA seguramente te puede ayudar más que yo. Si
  usas una PC Linux, entonces seguramente seré un mejor soporte para la
  instalación de software.

## Software

- **(imprescindible)** QGIS versión 3.x. La versión más reciente
  funcionará bien (con suerte). Si ya tienes QGIS instalado, versión
  3.x, es probable que las tareas del curso las puedas realizar sin
  problemas. No te funcionará la 2.x.

  - Estos vídeos parecen concisos y recientes sobre cómo instalarlo en
    Windows (lo de “gratis”, pues no sé por qué lo ponen en el título,
    será para ganar audiencia):
    - [Descargar e Instalar QGIS en Windows Gratis \| Paso a Paso
      2024](https://www.youtube.com/watch?v=3rYAAm1y5Vc)
    - [QGIS \| Descarga e Instalación. “GRATIS” Y ACTUALIZADO
      2024](https://www.youtube.com/watch?v=k31aQ1RdTZ8)
  - Este vídeo luce una buena fuente para MacOS (conciso, aunque al
    final abriendo no hace una demo de si le funciona o no):
    - [How to Download QGIS on MacBook
      2024?](https://www.youtube.com/watch?v=uVJVOZYB92Q)

- **(imprescindible)** Navegador. Seguramente ya tienes uno instalado
  (Chrome, Safari, Edge; Firefox todavía funciona, pero está teniendo
  algunos inconvenientes últimamente). Usarás el navegador para acceder
  a diversos servicios, así que usa el que te resulte cómodo. Aunque en
  esta primera edición del curso no programaremos intensamente, si
  llegara a haber una fase avanzada, seguramente programaremos más. De
  todas formas, proveeré acceso a un servidor de RStudio para el que
  sólo necesitarás el navegador, así que asegúrate de tener uno
  actualizado y que te resulte cómodo.

- Pensando en el futuro, o si quisieras tener independencia, puedes
  instalar por tu cuenta las herramientas de software que relaciono a
  continuación. Te recomiendo que lo hagas, porque, una vez terminado el
  curso, si quieres seguir usando, por ejemplo, RStudio o cuadernos
  Jupyter, necesitarás estas aplicaciones.

- **(opcional)** [R + RStudio
  Desktop](https://posit.co/download/rstudio-desktop/). Si quieres
  ejecutar código de R en tu propia PC, necesitarás el intérprete de R y
  la IDE (“entorno de desarrollo integrado”) más usada para dicho
  lenguaje, que es RStudio. Es recomendable que uses la versión más
  reciente disponible.

- **(opcional)** Python3 \| Anaconda \| Jupyter Hub \| Jupyter Notebook
  \| JupyterLab \| Spyder \| VS Code. Si quieres ejecutar código de
  Python en tu propia PC, necesitarás el intérprete (aunque seguramente
  ya tienes uno), y una IDE. Anaconda, en su distribución completa, te
  ofrece instalar el intérprete, paquetes (los más importantes, de
  hecho) e IDE (ofrece varias, de hecho), pero ocupa mucho espacio en
  disco. Mi recomendación es que uses una IDE sencilla, como Spyder o
  Visual Studio Code, o una IDE integrada en la web, como Jupyter
  Notebook (sencilla) o JupyterLab (avanzada).

- **(opcional)** GRASS GIS. Normalmente, se instala con QGIS. Sólo que
  estés pendiente a la hora de elegir un instalador, pues si uno te
  ofrece GRASS GIS además de QGIS, prefiere ese.

Considera instalar estos programas adicionales si vas a dedicarte a
programar o a escribir manuscritos científicos en lo adelante. Si ya lo
haces con otras herramientas, pero quieres explorar nuevas formas de
trabajar, estas aplicaciones son realmente muy útiles.

- **(opcional)** Git. Es un programa para el control de versiones. Si
  terminas escribiendo código informático duradero, o código que
  compartirás y enriquecerás con otros personas, casi seguramente
  necesitarás Git.
- **(opcional)** LaTeX. Sistema de composición de texto (basado en el
  sistema tipográfico TeX), pensado sobre todo para artículos
  científicos.
- **(opcional)** Docker. Si te queda mucha vida profesional por delante,
  aprender Docker es una gran inversión. Los viejos también estamos
  autorizados a aprender Docker, porque el infierno de las dependencias
  de software afecta a todos, jóvenes y viejos. Docker resuelve las
  dependencias bastante bien.

## Servicios ofrecidos por terceros, todos opcionales

- Algún servicio de grandes modelos de lenguaje (“inteligencia
  artificial”), como ChatGPT, Gemini, DeepSeek, Claude, Devin u otros.
- [Google Earth Engine](https://earthengine.google.com/). Este servicio,
  aunque lo incluí en la sección de los opcionales, es demasiado útil
  como para ignorarlo. En el curso no enseñaré a usarlo, pero te vendría
  bien tener una cuenta desde ya.
- [GitHub](https://github.com/). Obtén una cuenta en GitHub si aún no la
  tienes. Es recomendable crear un tóken de GitHub también para poder
  “empujar” cambios hacia repos remotos. Crea uno con los permisos
  básicos.
- [Earth Explorer del USGS](https://earthexplorer.usgs.gov/)
- [Alaska Satellite Facility (ASF)](https://search.asf.alaska.edu/)
- [Copernicus Data Space Ecosystem](https://dataspace.copernicus.eu/) o
  [Sentinel Hub](https://apps.sentinel-hub.com/eo-browser/)
- [Google Colab](https://colab.research.google.com/)
- [Overleaf](https://www.overleaf.com/). Obtén una cuenta en Overleaf
  para crear documentos avanzados.
- Zotero Desktop y cuenta en Zotero. Te podría ayudar a manejar citas y
  referencias. Existen otros servicios de apoyo para construir una buena
  lista de referencias, tales como Scite, CiteDrive y Perplexity, pero
  hay que andarse con cuidado con estos servicios, porque bien sabemos
  que en algunos casos, alucinan (valga añadir que han mejorado mucho en
  los últimos meses).

## Fuentes de datos

### Recomendación general

- **Datos:** Imágenes satelitales (por ejemplo, Landsat, Sentinel),
  bases de datos geográficos disponibles públicamente. Orientaré dónde
  obtener estas fuentes, pero últimamente recomiendo apuntar primero al
  Google Earth Engine.

### Algunos repositorios de GitHub con datos de ejemplo (muchos de RD) y cuadernos RMarkdown reproducibles

- [Material de apoyo de la asignatura “Análisis Espacial”, Maestría en
  Geografía, Teledetección y Ciencias de la Información
  Geográfica](https://github.com/maestria-geotel-master/material-de-apoyo)
- [Estadística zonal multipropósito sobre información geoespacial de
  República Dominicana, usando Google Earth Engine, Python y
  R](https://github.com/geofis/zonal-statistics)
- [Scripts de análisis de BCI (ecología
  numérica)](https://github.com/biogeografia-master/scripts-de-analisis-BCI/).
  Este repositorio está asociado con una lista de reproducción de mi
  canal de YouTube titulada [Ecología numérica con
  R](https://www.youtube.com/playlist?list=PLDcT2n8UzsCRDqjqSeqHI1wsiNOqpYmsJ)
- Repositorio “maestro” y las distintas ediciones de la asignatura
  “Biogeografía” que imparto en el grado. ¿Cómo usarlos? Cada uno de los
  enlaces de abajo, lleva a una edición de la materia (Año-Semestre),
  donde se alojan varios repositorios, incluidos los de alumnos y
  alumnas. Normalmente, el repositorio “material-de-apoyo” en cada una
  es el que muestra el programa seguido, y en otros casos es posible
  encontrar repositorios titulados “asignaciones-practicas” y
  “asignaciones-de-manuscrito”. Estos últimos muestran ejercicios
  asignados. En el de 2022-02 comento algunos detalles
  - [Repositorio
    Maestro](https://github.com/orgs/biogeografia-master/repositories)
  - [2019-02](https://github.com/orgs/biogeografia-201902/repositories)
  - [2020-02](https://github.com/orgs/biogeografia-202002/repositories)
  - [2021-01](https://github.com/orgs/biogeografia-202101/repositories)
  - [2021-02](https://github.com/orgs/biogeografia-202102/repositories)
  - [2022-01](https://github.com/orgs/biogeografia-202201/repositories)
  - [2022-02](https://github.com/orgs/biogeografia-202202/repositories).
    Notar que en esta edición, hay un subdirectorio nombrado
    [“demos-personalizadas”](https://github.com/biogeografia-202202/material-de-apoyo/tree/master/practicas/demos-personalizadas).
    Ahí se pueden encontrar cuadernos de análisis de ecología numérica
    con R aplicados a datos de GBIF. Recomiendo abrir los archivos
    Markdown, que tienen extensión `.md`. Por ejemplo, el de la familia
    [Fabaceae](https://github.com/biogeografia-202202/material-de-apoyo/blob/master/practicas/demos-personalizadas/practica-99-tu-manuscrito-3-resultados-fabaceae.md)
  - [2023-02](https://github.com/orgs/biogeografia-202302/repositories)
  - [2024-01](https://github.com/orgs/biogeografia-202401/repositories)
- [“Datos para proyectos” (datos a nivel municipal sobre viviendas y
  personas del Censo 2010; datos de geomorfometría a nivel municipal;
  datos de precipitación de
  ONAMET)](https://github.com/maestria-geotel-master/datos-para-proyectos)
- [Manuscrito “Generación de red hidrográfica densa de República
  Dominicana a partir de modelo digital de elevaciones de resolución
  media”](https://github.com/geofis/red-hidrografica-densa-rd)
- [Coberturas del suelo del polígono núcleo del campus de la Universidad
  Autónoma de Santo Domingo (UASD) en su sede
  central](https://github.com/geofis/coberturas-suelo-uasd)
- [Diseño de muestreo mediante índice espacial en Los Pilones / Los
  Boquerones. Asignaturas biogeografía y geomorfología,
  UASD](https://github.com/geofis/diseno-muestreo-los-pilones)
- [Reproducible R code for the manuscript entitled “Fire and forest loss
  in the Dominican Republic during the 21st
  Century”](https://github.com/geofis/forest-loss-fire-reproducible)
- [ENHOGAR-2018, TIC](https://github.com/geofis/enhogar-2018)
- [Microsoft Building Footprints, Distrito Nacional,
  RD](https://github.com/geofis/mbf-dn-rd)

## Otros recursos muy útiles

- Aula ¡con aire! (qué no se vaya la luz), mesas y sillas, y el resto de
  las instalaciones.
- Internet (esperemos que esto no falle).
- Proyector.
- Pizarra.

# Referencias destacadas

Bivand, R. S., Pebesma, E., & Gómez-Rubio, V. (2013). Applied Spatial
Data Analysis with R. Springer New York.
<https://doi.org/10.1007/978-1-4614-7618-4>

Olaya, V. (2020). Sistemas de Información Geográfica.
<https://volaya.github.io/libro-sig/>

Lovelace, R., Nowosad, J., & Muenchow, J. (2019). Geocomputation with R.
Chapman and Hall/CRC. <https://r.geocompx.org/>

Dorman, M., Graser A., Nowosad, J. & Lovelace, R. (2019). Geocomputation
with Python. Chapman and Hall/CRC. <https://py.geocompx.org/>
