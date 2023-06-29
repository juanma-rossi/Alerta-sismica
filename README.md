<p align="right">
  <img src="https://i.ibb.co/qgrt3cm/Logo-Grupo-7-150px.png">
</p>


# Proyecto Creación de "Sistema de Alertas Sísmicos" 

Este proyecto está a cargo del equipo de atención de desastres de México (SSN), en consideración con la posible alianza tri-nacional en conjunto con el Estados unidos (USGS) y Japón (JMA) llamado ***“Working towards global standardization of seismological networks and effective communication to the civilian community”***. Se realizó el proyecto de **Alertas Sísmicas** a partir de los datos históricos y actuales sobre sismos de cada uno de los países miembros.

## Entendimiento se la situación actual(Marco Teórico)

### ¿Qué son los sismos?

Los terremotos suelen estar asociados mayormente a una condición natural de la tierra como planeta, la cual tiene una capa superior llamada Litosfera, se diferencia de las otras capas del planeta por ser sólida, más fría y encontrarse en la parte exterior.  La litosfera está dividida en distintas áreas denominadas placas tectónicas. 

Los movimientos de las capas internas de la tierra, hacen que las placas tectónicas se muevan en distintas direcciones, se conoce que la mayoría de las manifestaciones sísmicas de la litosfera se producen en los límites de las placas, debido a la liberación de energía desde el punto de fricción, el sismo emite su fuerza en forma de 3 ondas de energía, llamadas primarias, secundarias y superficial, siendo la última la que mas nos afecta en forma de daños. *Fuente: Instituto Geográfico Nacional de España, [Sismología - Instituto Geográfico Nacional (ign.es)](https://www.ign.es/web/ign/portal/sis-teoria-general)*

Otra causa asociada a menor escala, son los terremotos inducidos, los cuales pueden estar relacionados con el llenado de embalses, agotamiento de los yacimientos de petróleo y gas, minería, eliminación subterránea de desechos, generación de energía geotérmica y franking. *Fuente: libertaddigital.com, [La verdad sobre la relación entre 'fracking' y terremotos - Libertad Digital](https://www.libertaddigital.com/ciencia-tecnologia/ciencia/2015-02-25/la-verdad-sobre-la-relacion-entre-fracking-y-terremotos-1276541587/)*

### ¿Qué acciones se han tomado?

Debido al daño causado por los efectos secundarios de estos movimientos sísmicos, la humanidad ha venido documentando cada uno de estos sucesos, con el fin de crear mecanismos de educación, prevención y predicción. Incluso una rama científica especializada llamada “sismología”. El estudio del estudio de las ondas y los tipos de movimientos de la tierra a dado lugar a mejorar los sistemas de construcción, crear sistemas de alertas que con los mecanismos de prevención en las comunidades, hace que cada vez las perdidas materiales y humanas sean menores. 

### Justificación

Con los avances de la tecnología se puede acceder a los datos casi en tiempo real sobre la actividad sísmica en distintas partes del mundo, no obstante los estándares de captación y estandarización de la información no se encuentra del todo unificada. Adicionalmente la documentación y el acceso a los datos se orienta al consumo a especialistas en la materia. Limitando a una gran mayoría de la población al conocimiento. Ante esta situación se ha creado la alianza Tri-Nacional y el auspicio de la creación del presente proyecto.

## Misión

*Organizar la Información de forma estandarizada, entendible y útil sobre la actividad sísmica de los países de la alianza Tri-Nacional, para el conocimiento de sus habitantes.*

## Visión

*La información sísmica útil y sencilla estará disponible para la educación y toma de decisión sobre prevención de desastre.*

## Objetivos

- Crear una base de datos, con la información sobre la actividad sísmica de los países Estados Unidos, Japón y México.
- Identificar las zonas de mayor riesgo a través de la individualización de patrones y tendencias dentro de los datos.
- Clasificar los eventos sísmicos a partir de sus características.
- Informar sobre los posibles efectos secundarios de los eventos sísmicos conforme a su clasificación.

## Alcance

El proyecto persigue la segmentación, filtración y transformación de la data disponible, acerca de los distintos eventos sísmicos que se encuentren relacionados o tengan implicación con el área geográfica de los países miembros de la alianza Tri-Nacional y a su vez, contengan la información necesaria para el cumplimiento de los objetivos trazados.

## Indicadores Claves de Rendimiento (KPI)

- Aumento de la frecuencia de eventos sísmicos en relación a los años anteriores.
- Reducción del tiempo de emisión de alerta en relación al año anterior en Japón, México, Estados Unidos.
- Reducción de bajas humanas en sismos de riesgo grave, en comparación a eventos pasados.

## Gestión del proyecto
Para la gestión del proyecto se está trabajando con Github Projects [https://github.com/users/gabygonalons/projects/1/views/1] utilizando el esquema de tarjetas KanBan.

## Repositorio del proyecto

Para el trabajo colaborativo el equipo estará trabajando con el repositorio público de Github [juanma-rossi/Groups01 (github.com)](https://github.com/juanma-rossi/Groups01), dónde estará contenida la documentación oficial del proyecto, y el despliegue de las distintas versiones y cambios.

## Solución Propuesta

El equipo ha decidido, a groso modo ha llegado recabará los datos desde la API, de [Documentación de API - Catálogo de terremotos (usgs.gov)](https://earthquake.usgs.gov/fdsnws/event/1/) , cargarlos a la plataforma de SnowFlakes, automatizar el procesado de la data, desplegar el modelo de clasificación de machine learning, analizar los datos obtenidos y crear un dashboard interactivo con la información clave.

### Stack Tecnológico:

**Github:** A través de esta plataforma se puede organizar y controlar las distintas versiones del proyecto, integrante del equipo podrá disponer y cargar los aportes de una manera eficiente y organizada.

**Discord:** Mediante esta plataforma el equipo se comunica entre a diario y tome las decisiones importantes. 

**Google Meet:** Plataforma para presentarle al project manager el estado de las tareas y objetivos.

**AWS:** Como recurso de almacenamiento y procesamiento de la data desde la nube.

**Power Bi:** Herramienta de Visualización de los datos para comunicar el resultado de los análisis.

### Metodología de Trabajo

La metodología de trabajo a utilizar se denomina scrum, entra dentro de las metodologías ágiles.

### Equipo de Trabajo

Para la ejecución de este proyecto los 4 integrantes del equipo se dividen en 2 Data Engineer, 2 Data Analyst.  

### Cronograma General

<img src=https://i.ibb.co/vJJHjx1/Crono-General.png>

### Búsqueda Preliminar de Información

(por completar)

Información sobre SISMOS

Sismos en Chile:
[https://ds.iris.edu/latin_am/evlist.phtml?region=chile]

Sismos en Colombia:
[https://www2.sgc.gov.co/ProgramasDeInvestigacion/geoamenazas/Paginas/Sistema-de-Consulta-de-la-Amenaza-Sismica-de-Colombia.aspx]

Sismos en Perú:
[https://www.datosabiertos.gob.pe/dataset/catalogo-sismico-1960-2021-igp]

Sismos de Ciudad de México:
[https://datos.cdmx.gob.mx/sk/dataset/sismos-registrados-cdmx] actualizado al 13 de abril de 2023 (archivos en formato .pdf, .shp y .shx)
[http://www2.ssn.unam.mx:8080/catalogo/] Catalogo de Sismos del area de Geofísica de la Universidad Autónoma de México. Formato .csv archivos desde 1900
Se puede filtrar la información por período, magnitud, profundidad y estado.

[http://geografica.cenapred.unam.mx:8080/reporteSismosGobMX/] Reportes sismicos de México (se actualiza cada 24 hs)

[http://www.atlasnacionalderiesgos.gob.mx/archivo/descargas.html] Gobierno de México - Guía para Reducción del Riesgo Sismico

