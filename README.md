# Proyecto-Ingenieria-de-Caracteristicas

El objetivo de este proyecto es aplicar los conocimientos adquiridos en la materia de Ingeniería de Características para generar un Dashboard que nos cuente la historia sobre la inseguridad en el estado de Sonora utilizando datos públicos sobre incidencias delictivas del [*Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública*](https://www.gob.mx/sesnsp), así como datos sobre la percepción de la inseguridad de la *Encuesta Nacional de Victimización y Percepción sobre la Seguridad Pública (ENVIPE)* y del *Censo Poblacional*, recabados por el [INEGI](https://www.inegi.org.mx/default.html). 

El proyecto se compone de 3 partes: 

## 1. Proyecto 1. [Descargando datos de la web](https://github.com/osirisizs/Proyecto-Ingenieria-de-Caracteristicas/blob/main/Proyecto1_Descargando_Datos.ipynb)
   En esta libreta se documenta la obtención de los datos de las 3 fuentes mencionadas al principio por medio de APIs, así como su respectiva limpieza, normalización,      unión y generación de [diccionarios de datos](https://github.com/osirisizs/Proyecto-Ingenieria-de-Caracteristicas/tree/main/Diccionarios) y [archivos parquet]            (https://github.com/osirisizs/Proyecto-Ingenieria-de-Caracteristicas/blob/main/seguridad_df.parquet).

## 2. Proyecto 2. [Contando Historias](https://github.com/osirisizs/Proyecto-Ingenieria-de-Caracteristicas/blob/main/Proyecto2_Contando_Historias.ipynb)
   En esta libreta se documenta el analisis exploratorio de datos, generando un reporte automatico con [pandas_profiler]() además de un análisis más exahustivo realizado    manualmente, se realiza también un método de reducción de características para la visualización de multiples características en un gráfico 2-dimensional. A su vez se    realizó un [Mock-Up]() del tablero a realizar para contar nuestra historia.
