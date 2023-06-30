<p align="right"><img src="https://i.ibb.co/7RPfjpk/Banner-para-Linkedin-Licenciada-Marketing-Minimalista-Beige-1.png"></p>

<h1 align="center">
  :large_blue_circle: Proyecto "Creación de un Sistema de Alertas Sísmicas"
</h1>

El presente proyecto llevado adelante por la empresa *"Analitic World"* se orienta a la *"Creación de un Sistema de Alertas Sísmicas"* que nace como parte de un proyecto mayor denominado  ***“Working towards global standardization of seismological networks and effective communication to the civilian community”***. El mismo surge del trabajo mancumunado entre el *Servicio Geológico de Estados Unidos* **UGS**, la *Agencia Meteorológica de Japón* **JMA** y el *Servicio Sismológico Nacional" de México **SSN** a fin de promover la normalización de las redes sísmicas a nivel mundial  y la comunicación eficaz a la sociedad de los eventos sísmicos.

## Entendimiento se la situación actual(Marco Teórico)

### ¿Qué son los sismos?

Un terremoto​, también llamado sismo, temblor de tierra o movimiento telúrico, es la sacudida brusca y pasajera de la corteza terrestre. 
El punto de origen de un terremoto se denomina foco o hipocentro, a partir de allí se propaga en forma de ondas sísmicas.  

Los terremotos suelen estar asociados mayormente a una condición natural de la tierra como planeta, la cual tiene una capa superior llamada Litosfera, que se diferencia de las otras capas del planeta por ser sólida, más fría y encontrarse en la parte exterior.  La litosfera está dividida en distintas áreas denominadas placas tectónicas. 

Los movimientos de las capas internas de la tierra, hacen que las placas tectónicas se muevan en distintas direcciones, se conoce que la mayoría de las manifestaciones sísmicas de la litosfera se producen en los límites de las placas, debido a la liberación de energía desde el punto de fricción, el sismo emite su fuerza en forma de 3 ondas de energía; llamadas primarias, secundarias y superficial, siendo la última la que mas nos afecta en forma de daños. *Fuente: Instituto Geográfico Nacional de España, [Sismología - Instituto Geográfico Nacional (ign.es)](https://www.ign.es/web/ign/portal/sis-teoria-general)*

Otra causa asociada a menor escala, son los terremotos inducidos, los cuales pueden estar relacionados con el llenado de embalses, agotamiento de los yacimientos de petróleo y gas, minería, eliminación subterránea de desechos, generación de energía geotérmica y franking. *Fuente: libertaddigital.com, [La verdad sobre la relación entre 'fracking' y terremotos - Libertad Digital](https://www.libertaddigital.com/ciencia-tecnologia/ciencia/2015-02-25/la-verdad-sobre-la-relacion-entre-fracking-y-terremotos-1276541587/)*

Cuando ocurre un sismo, es importante evaluar su **magnitud** y **profundidad** para comprender la **naturaleza** y el **impacto** del evento.

- **Magnitud del sismo**: La magnitud de un sismo es una medida cuantitativa de la energía liberada durante el movimiento de las placas tectónicas. Se calcula utilizando escalas como la *Escala de Richter* o la *Escala de Magnitud de Momento*. Conocer la magnitud del sismo nos proporciona información sobre la fuerza y la violencia del terremoto en su origen. Es una medida fundamental para comparar y clasificar diferentes terremotos. *Fuente: http://www.ssn.unam.mx/, [Magnitud de un sismo](http://www.ssn.unam.mx/jsp/reportesEspeciales/Magnitud-de-un-sismo.pdf)*

- **Profundidad del sismo**: La profundidad del sismo se refiere a la ubicación vertical en la cual se origina el terremoto debajo de la superficie de la Tierra. Puede variar desde sismos superficiales hasta sismos profundos que se generan a gran profundidad. Conocer la profundidad del sismo es importante porque puede afectar la propagación de las ondas sísmicas y, por lo tanto, la forma en que el terremoto se siente en la superficie. Además, la profundidad puede influir en el nivel de daño causado por el sismo, ya que los terremotos más superficiales tienden a ser más destructivos en comparación con los sismos profundos. *Fuente: SAGE, [Efecto de la profundidad sobre la intensidad del temblor del suelo](https://www.iris.edu/hq/inclass/animation/mdulo_3_efecto_de_la_profundidad_sobre_la_intensidad_del_temblor_del_suelo))*

Por otro lado resulta relevante conocer la **intensidad** de los sismos. Si bien la magnitud y la profundidad son medidas objetivas del terremoto, la intensidad es subjetiva puesto que se refiere a los efectos y daños que el sismo causa en áreas pobladas. Conocer la intensidad es crucial para comprender el impacto real del sismo en términos de daños a edificios, infraestructuras y la vida de las personas. También ayuda a guiar las labores de rescate y respuesta ante desastres. Se evalúa mediante la *Escala de Mercalli* o escalas similares, que describen los efectos observados en las personas, estructuras y el entorno. *Fuente: Gobierno de México, [Escala de los sismos]([https://www.iris.edu/hq/inclass/animation/mdulo_3_efecto_de_la_profundidad_sobre_la_intensidad_del_temblor_del_suelo)*

En resumen, la magnitud y la profundidad del sismo proporcionan información sobre la fuerza y el origen del terremoto, mientras que la intensidad nos ayuda a comprender los efectos y el alcance de los daños causados. Estos datos son esenciales para la investigación sísmica, la planificación de la mitigación de riesgos, la respuesta a desastres y el diseño de estructuras resistentes a los terremotos. 

### ¿Qué acciones se han tomado?

La humanidad ha venido documentando cada uno de estos movimientos telúricos con el fin de crear mecanismos de educación, prevención y predicción.
En la actualidad, **GSN** es una red en tiempo real cuyos datos son generados diariamente por grupos operativos de monitoreo, tanto en los Estados Unidos como a nivel internacional. En los Estados Unidos, el **Centro Nacional de Información Sísmica** recibe datos de todas las estaciones de GSN a nivel mundial en tiempo real para ubicar terremotos. Los datos de esta red son una entrada esencial para el sistema de alarma automatizado **USGS PAGER** (localizador)  utilizado para evaluar de manera rápida y exacta la gravedad de los daños causados por un terremoto y para proporcionar información a organizaciones de socorro en emergencias, agencias gubernamentales y los medios de comunicación con una estimación del impacto social de la catástrofe potencial.

### Justificación

Los avances tecnológicos han permitido el accceso a los datos prácticamente en tiempo real desde cualquier lugar del planeta, no obstante la captación de datos se realiza desde diversas instituciones en distintos puntos del platena con equipamientos variados.  Consecuentemente los datos resultantes de los monitoreos realizados presetan variados formatos y calidades por lo que resulta imperioso el pre-procesamiento de los mismos y su adecuación a los estandares de la Red.

## Misión

*Proveer a la alianza tri-alianza los datos requeridos en formatos acordes a los estándares de la red en plazos que permitan el cuplimiento cabal de los objetivos.* 

## Visión

*Colaborar con la alianza tri-nacional con el máximo nivel de eficacia, eficiencia y profesionalimo.*

## Objetivos

- Crear una base de datos, con la información sobre la actividad sísmica de los países miembros de la alianza: Estados Unidos, Japón y México.
- Identificar las zonas de mayor riesgo a través de la individualización de patrones y tendencias dentro de los datos.
- Clasificar los eventos sísmicos a partir de sus características.
- Informar sobre los posibles efectos secundarios de los eventos sísmicos conforme a su clasificación.

## Alcance

El proyecto persigue la segmentación, filtración y transformación de la data disponible, acerca de los distintos eventos sísmicos que se encuentren relacionados o tengan implicación con el área geográfica de los países miembros de la alianza tri-Nacional y a su vez, contengan la información necesaria para el cumplimiento de los objetivos trazados.

## Indicadores Claves de Rendimiento (KPI)

- Aumento de la frecuencia de eventos sísmicos en relación a los años anteriores.
- Reducción del tiempo de emisión de alerta en relación al año anterior en Japón, México, Estados Unidos.
- Reducción de bajas humanas en sismos de riesgo grave, en comparación a eventos pasados.

## Gestión del proyecto
Para la gestión del proyecto se está trabajando con Github Projects [https://github.com/users/gabygonalons/projects/1/views/1] utilizando el esquema de tarjetas KanBan.

## Repositorio del proyecto

Para el trabajo colaborativo el equipo estará trabajando con el repositorio público de Github [juanma-rossi/Groups01 (github.com)](https://github.com/juanma-rossi/Groups01), dónde estará contenida la documentación oficial del proyecto, y el despliegue de las distintas versiones y cambios.

## Solución Propuesta

**Procesos involucrados**
- Extracción de datos de las API:[Documentación de API - Catálogo de terremotos (usgs.gov)](https://earthquake.usgs.gov/fdsnws/event/1/) ,
- Preprocesamiento de los datos: normalización de los mismos con Python previa a su uso.
- Disponibilización de los datos: carga de los DataSets a la plataforma de AWS.
- Automatización del procesado de la data.
- Despliegue del modelo de clasificación de machine learning: analisis de los datos obtenidos.
- Creación de un dashboard interactivo con la información clave.

### Stack Tecnológico:

**Github:** A través de esta plataforma se puede organizar y controlar las distintas versiones del proyecto, cada integrante del equipo podrá disponer y cargar los aportes de una manera eficiente y organizada.

**Discord:** Mediante esta plataforma el equipo se comunica entre a diario y tome las decisiones importantes. 

**Google Meet:** Plataforma para presentarle al project manager el estado de las tareas y objetivos.

**AWS:** Como recurso de almacenamiento y procesamiento de la data desde la nube.

**Power Bi:** Herramienta de Visualización de los datos para comunicar el resultado de los análisis.

**Python:** Lenguaje de Progamación principal para la manipulación de los datos.

### Metodología de Trabajo

La metodología de trabajo a utilizar se denomina scrum, entra dentro de las metodologías ágiles.

### Equipo de Trabajo

Para la ejecución de este proyecto los 4 integrantes del equipo se dividen en 2 Data Engineer, 2 Data Analyst.  

### Cronograma General

<img src=https://i.ibb.co/NxrWbn3/Crono-General-1.png>

### Búsqueda Preliminar de Información

(En Proceso)

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

