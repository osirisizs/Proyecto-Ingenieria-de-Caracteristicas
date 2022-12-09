# Proyecto-Ingenieria-de-Caracteristicas

El objetivo de este proyecto es aplicar los conocimientos adquiridos en la materia de Ingeniería de Características para generar un Dashboard que nos cuente la historia sobre la inseguridad en el estado de Sonora utilizando datos públicos sobre incidencias delictivas del [*Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública*](https://www.gob.mx/sesnsp), así como datos sobre la percepción de la inseguridad de la *Encuesta Nacional de Victimización y Percepción sobre la Seguridad Pública (ENVIPE)* y del *Censo Poblacional*, recabados por el [INEGI](https://www.inegi.org.mx/default.html). 

El proyecto se compone de 3 partes: 

## 1. Proyecto 1. [Descargando datos de la web](https://github.com/osirisizs/Proyecto-Ingenieria-de-Caracteristicas/blob/main/Proyecto1_Descargando_Datos.ipynb)
   En esta libreta se documenta la obtención de los datos de las 3 fuentes mencionadas al principio por medio de APIs, así como su respectiva limpieza, normalización,      unión y generación de [diccionarios de datos](https://github.com/osirisizs/Proyecto-Ingenieria-de-Caracteristicas/tree/main/Diccionarios) y [archivos parquet].

En este proyecto individual, cada uno va a desarrollar un pequeño programa que ayude a descargar datos a partir de diferentes APIs, o usando un método para descargas masivas.

Los requisitos para este proyeto deberán estar presentes en un repositorio de GitHub público con las siguientes características:

+ Un script o libreta que descargue datos de al menos dos fuentes diferentes, y que genere un archivo texto con la descripción de las fuentes, las fechas de descarga y de ser posible la descripción (o enlaces) que expliquen la naturaleza de los datos descargados. Si los datos venían sin explicación, agregar la explicación propia para simplificar el proceso.
+ Una libreta o script que transforme y utilice los datos de acuerdo a su tipo, selecciones la información que se desea utilizar y se generen los Dataframes necesarios.
+ Un diccionario de datos por cada dataframe
