![Mi imagen](/logo_vigilancia.png)

# Indice
- [Programa](#programa)
- [Sesión 1: Introducción a R y Rstudio, Objetos, Funciones y sintaxis básica](#Sesión-1)
- [Sesión 2: Importación, limpieza de datos y funciones de procesamiento básicas](#Sesión-2)
- [Sesión 3: Unión de datos, pivoteos de datos, vicualización de tablas](#Sesión-3)
- [Sesión 4: Visualización de datos, mapas y exportación de Quarto presentación](#Sesión-4)
- [Sesión Git-Github](#Sesión-Git)
- [Enlaces de utilidad](#enlaces-de-utilidad)

------------

# Programa de Capacitación para la Vigilancia Epidemiológica: Automatización de reportes en R

**Docente:** Andrés Martín Pereira, Velén Pennini y María Florencia Mena

**Año:** 2024

## A- Introducción y fundamentación de la propuesta formativa:

<p>
La necesidad de formación continua es una de los elementos característicos comunes para el trabajo de los equipos de salud. En específico, en lo relativo a la vigilancia epidemiológica, la necesidad de fortalecer las competencias y capacidades de los equipos de epidemiología locales y jurisdiccionales de la provincias en Argentina está en relación no sólo con la incorporación de nuevas herramientas informáticas para el análisis de datos, visualizaciones y generación de reportes automatizados. A su vez el contexto desafiante que presenta el avance de las enfermedades virales a nivel nacional (ETMa, IRAG, entre otras), en conjunto con la ampliación de la estrategia de vigilancia centinela de IRAG, se presenta con un escenario que resalta la importancia del uso de  herramientas avanzadas y métodos eficientes para la gestión de datos epidemiológicos. 

La presente capacitación está orientada a profesionales de distintas disciplinas o integrantes de los equipos de salud y de gestión de la salud que desempeñen tareas de vigilancia epidemiológica. 

Como requerimiento mínimos para poder realizar la capacitación se necesita la disponibilidad de computadora con la instalación del programa R y RStudio con permisos para instalar paquetes nuevos. Es valorado el conocimiento básico de manejo de bases de datos y la lectocomprensión del idioma inglés.

</p>



## B- Objetivos
  
**General**:
 <p>
  Fortalecer las habilidades y competencias para el procesamiento, visualización y elaboración de reportes automáticos en R.
</p>

*Específicos*:

<p>

- Caracterizar e identificar los circuitos de los datos producidos por la vigilancia epidemiológica a nivel jurisdiccional 

- Incorporar herramientas de procesamiento y visualización de los datos en R

- Elaborar un proyecto de automatización de reportes en R a nivel jurisdiccional

- Desarrollar autonomía en el uso de R aplicado al análisis de datos epidemiologicos

</p>

## C- Contenidos

<p>
Se propone una capacitación en el uso del programa R con un formato de taller práctico que incluya el uso de RMarkdown y Quarto para la creación de informes automatizados y diversos paquetes de R para análisis y visualizaciones. La propuesta es que al finalizar la capacitación el equipo de vigilancia epidemiológica tenga armado un proyecto para la generación automática de reportes con los datos producidos por la vigilancia epidemiológica. 
</p>
  
#### C. 1. Módulo 1: Presentación de las herramientas de trabajo

Este primer módulo tiene algunos contenidos de carácter de optativo para aquellas personas que ya están familiarizadas con el uso de R y RStudio. Se propone con el objetivo de instalar y familiarizarse con las herramientas básicas y presentar la propuesta general de la capacitación.

- Presentación de R y RStudio como software estadístico. Instalación. [The R Project for Statistical Computing](https://www.r-project.org/)
- ¿Cómo funciona R? Introducción al lenguaje R.
- ¿Cómo funciona R Studio?
- Paquetes: instalación y carga.
- Introducción al lenguaje orientado a objetos (POO).
- Presentación de los principales objetos de R
- Descripción de los objetivos de la  propuesta formativa. Presentación de la plataforma GitHub, RMarkdown.
- Uso de IA (Chat GPT) para la programación en R
 

#### C.2. Módulo 2: Plan de análisis
En este módulo se trabajará colaborativamente con la estrategia de vigilancia epidemiológica seleccionada por la jurisdicción. De acuerdo a esta elección se trabajará en el armado de los circuitos de los datos producidos localmente por los diferentes niveles y efectores de salud intervinientes. Se diseñará un plan de análisis de los datos producidos en el marco de las actividades de vigilancia

- Construcción del circuito de datos de la vigilancia epidemiológica local. Transferencia de datos. Lectura de dataset. 
- Búsqueda y transferencia de archivos de bases de datos epidemiológicos para su utilización en Rstudio.
- Paquetes de datos y uso de marcos de data frames compartidos
- Diseño colaborativo de un plan de análisis

#### C.3. Módulo 3: Procesamiento y análisis de datos

Se propone como tercer paso presentar las principales herramientas para el procesamiento de datos en R en el marco del plan de análisis propuesto. Se presentarán herramientas básicas de la visualización de los datos seleccionados.

- Interfases: RStudio: Cuatro ventanas/Rmarkdown
- Validación, subconjunto de datos, creacion de variables
- Combinación de marcos de datos. Funciones de joint.
- Estadística descriptiva en R. Medidas de resumen: tendencia central y dispersión, frecuencias relativas y absolutas.
- Elaboración de gráficos para variables categóricas y numéricas. Librería ggplot2


#### C.4. Módulo 4: Cartografía temática
Se seleccionarán los indicadores para la representación cartográfica de los mismos utilizando R. Se producirán mapas temáticos que permitan describir y analizar la distribución espacial del evento en la jurisdicción.

- Instalación de paquetes y librerias necesarias
- Elaboración de datos georeferenciados
- Utilización de filtros, incorporación de nuevos datos
- Utilización de shape files y creación de capas.


#### C.5. Módulo 5:  Elaboración automatizada de reportes

Elaboración del modelo y esquema de reporte a elaborar de manera automatizada.  R Markdown. Integración de código R, texto y gráficos en un solo documento. Exportación en Documentos de Microsoft Word, PDF  y Archivos HTML.

#### C.6. Módulo 6: Seguimiento y Monitoreo

Se realizará seguimiento de la implementación del proyecto y relevamiento de obstáculos en la puesta en práctica en el marco de las actividades de vigilancia epidemiológica a nivel jurisdiccional.

## D -Estrategia de evaluación

La evaluación será una instancia continua que permita presentar y resumir los resultados alcanzados con las actividades propuestas en cada módulo. El resultado principal a alcanzar con la capacitación es un resultado colectivo, que permita el fortalecimiento de los equipos de vigilancia epidemiológica a nivel jurisdiccional. En este sentido si bien habrá actividades realizadas de forma individual y que serán resultados de las actividades desarrolladas en los distintos módulos, el acento está colocado en el proyecto grupal de elaboración de reportes automatizados. Se propone también como parte de la estrategia de evaluación de esta capacitación el monitoreo y seguimiento en el proceso de implementación del proyecto en la jurisdicción.


## E- Productos esperados:

Se espera que los/as alumnos/as elaboren un plan de análisis para sus datos y con el mismo puedan diseñar y programar un reporte automatizado en R y Quarto. Se espera que estos reportes sean un importante insumo para los equipos que trabajan en vigilancia a nivel provincial.

------------

# Sesión 1 

Dentro de este directorio encontraremos:
- "Cápsula 1": Introducción básica a R y Rstudio.
- "Cápsula 2": Objetos, funciones, principales paquetes ylibrerías.
- "Cápsula 3": Factores, datos faltantes, Pipe (tuberías). Creación de proyecto en R y rutas de directorios de trabajo. 

Estos archivos se encuentran en el repositorio en la "Sesión 1", desde donde se lo podrán descargar o acceder desde los siguientes links:

[Cápsula 1](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%201/C%C3%A1psula%201.html)

[Cápsula 2](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%201/C%C3%A1psula%202.html)

[Cápsula 3](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%201/C%C3%A1psula%203.html)

[Material para encuentro sincrónico](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%201/Material_para_sincr%C3%B3nica.html)

# Sesión 2

Dentro de este directorio encontraremos:
- "Cápsula 4": Importación de datos con diferntes paquetes y formatos. 
- "Cápsula 5": Limpieza y normalización de datos. Datos faltantes, trabajo con caracteres y fechas. Exportación de dataframe.
- "Cápsula 6": Procesamiento de datos. Filtrado, y trabajo con duplicados.
- "Cápsula 7": Procesamiento de datos. Modificación de columnas, variables condiconales, creación de rangos, agrupamientos.
- "Material funciones": Ayuda visual para la sintaxis de principales funciones de porcesamiento de datos. 

[Cápsula 4](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%202/C%C3%A1psula%204.html)

[Cápsula 5](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%202/C%C3%A1psula%205.html)

[Cápsula 6](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%202/C%C3%A1psula%206.html)

[Cápsula 7](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%202/C%C3%A1psula%207.html)

[Material funciones](https://vigilanciaenr.github.io/VigilanciaenR/Clase%202/Material_funciones.html)




# Sesión 3: 

Dentro de este directorio encontraremos:
- "Cápsula 8": Unión de datos. 
- "Cápsula 9": Pivoteo de datos para gráficos. 
- "Cápsula tablas": Formatos y visualización de tablas

[Cápsula 8](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%203/C%C3%A1psula%208.html) 

[Cápsula 9](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%203/C%C3%A1psula%209.html) 

[Cápsula tablas](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%203/C%C3%A1psula%20tablas.html#tablas-con-gt) 




# Sesión 4:

Dentro de este directorio encontraremos:
- "Mapas": Armado de mapas 
- "PPT Visualización de datos": Material visualización de datos para buenas prácticas.
- "Quarto presentación": Ejemplo para exportar archivo Quarto en formato presentación.

[Mapas](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%204/mapas_neuquen.html)

[PPT Visualización de datos](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%204/ppt_visualizaciones.html)

[Quarto presentación](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%204/Quarto%20presentaci%C3%B3n.html#/title-slide)

# Sesión Git

Dentro de este directorio encontraremos:
- Documento presentación y guía para la descarga y conexión de Git y Github con Rstudio

[Presentación Git-Github](https://vigilanciaenr.github.io/VigilanciaenR/Sesi%C3%B3n%20Git-Github/ppt_git.html)


# Enlaces de utilidad

[Rstudio](https://posit.co/downloads/ "Rstudio")

[Video de instalación de R y Rstudio](http://www.youtube.com/watch?v=hbgzW3Cvda4&ab_channel=HerbertLizama "Video de instalaciónn de R y Rstudio")

[Quarto](https://quarto.org/docs/get-started/ "Descarga de Quarto")

[Video instalación de Quarto](https://www.youtube.com/watch?v=uHaDmPtO-YQ&ab_channel=Estad%C3%ADstica%C3%BAtil "Video instalación de Quarto")

<!-- 

-->








  
