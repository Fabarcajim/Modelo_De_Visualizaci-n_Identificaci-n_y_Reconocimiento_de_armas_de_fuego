# Modelo dee Visualización Identificación y Reconocimiento de armas de fuego
Este repositorio explora el comportamiento de los tiroteos en Estados Unidos para la creación de un modelo de visualización, identificación y reconocimiento de armas de fuego para un proyecto de Tesis.

# Abstract

En los últimos años, los tiroteos en escuelas de Estados Unidos se han estado convirtiendo en una alarmante y polémica crisis social. De acuerdo con datos de “epdata”, el número de tiroteos escolares ha aumentado significativamente del año 1970 al 2022 lo que ah provocando una preocupación en la opinión pública y en los gobiernos locales.

El presente trabajo busca abordar esta problemática a través del diseño y desarrollo de un modelo de visualización, identificación y reconocimiento de armas de fuego el cual pueda ser aplicado en entornos de alta vulnerabilidad.

# Análisis exploratorio de datos (EDA)

Este análisis se basa en dos conjuntos de datos descargados del artículo "Tiroteos en colegios en Estados Unidos, datos, gráficos y estadísticas" de epdata, que proporcionan información sobre el número de incidentes entre 1970 y 2022, y los estados con mayor cantidad de incidentes. Los datos ya vienen limpios, sin valores nulos ni duplicados, lo que permite enfocarnos directamente en el análisis exploratorio.

1. Descripción General de los Datos
   * Base de datos 1: **Número de incidentes (1970-2022)**.
     
     Esta base nos ofrece una vista histórica de los tiroteos en colegios, detallando el número       de incidentes por año durante más de cinco décadas.

   * Base de datos 2: **Estados con mayor número de incidentes**.
     
     En esta base se nos muestra la distribución geográfica de los incidentes, detallando los         estados que presentan mayor recurrencia de estos eventos. Esto permite hacer un análisis         regional, comparando qué áreas del país han sido más afectadas

# Estructura de repositorio
     
El objetivo de este repositorio es implementar las buenas prácticas de acuerdo al paper ["Good Enough Practices in Scientific Computing"](https://arxiv.org/abs/1609.00037) por Greg Wilson, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, Tracy K. Teal.

La estructura que queremos que tenga este repositorio es la siguiente:

    ├── LICENSE             
    |  
    ├── README.md           
    |  
    ├── CONTRIBUTING.md     
    |  
    ├── CITATION.md         
    |  
    ├── data                
    |  
    ├── doc                 
    |  
    ├── results            
    |  
    └── src                 

