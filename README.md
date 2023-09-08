# last-project

# Proyecto ETL: Análisis de Alquiler en Madrid

Este proyecto de Extracción, Transformación y Carga (ETL) tiene como objetivo analizar los datos de alquiler en Madrid. Para lograrlo, se han seguido los siguientes pasos:

## Proceso de ETL

1. **Extracción de Datos**: Se han utilizado técnicas de scrapping web para recopilar información de alquileres en varias páginas web relevantes. Se emplearon las librerías Selenium y Beautiful Soup para automatizar la extracción y el análisis de los datos. Además, con el fin de evitar las captchas, se implementó el uso de TunnelBear, una herramienta que permite cambiar las direcciones IP.

2. **Transformación de Datos**: Una vez obtenidos los datos en formato CSV, se cargaron en un DataFrame de Pandas para realizar su limpieza y transformación. Durante esta etapa, se han llevado a cabo diversas tareas, como eliminar registros duplicados, manejar valores faltantes, corregir formatos de datos y realizar la normalización de variables si fuera necesario. También se han aplicado técnicas de limpieza y preprocesamiento para garantizar la calidad de los datos.

3. **Carga de Datos**: Los datos transformados se han cargado en una base de datos MySQL para su almacenamiento persistente y acceso futuro. Se ha definido una estructura de tablas adecuada para almacenar la información recopilada, facilitando así su consulta y manipulación.

## Análisis Exploratorio de Datos (EDA)

Una vez completado el proceso de ETL y con los datos almacenados en la base de datos MySQL, se ha realizado un Análisis Exploratorio de Datos (EDA) para obtener una comprensión más profunda de los alquileres en Madrid. Algunas de las técnicas y visualizaciones empleadas durante el EDA incluyen:

- Estadísticas descriptivas: Calcular medidas estadísticas como mediana, media, desviación estándar, mínimo y máximo para diferentes variables, como el precio de alquiler, la ubicación geográfica o el tamaño del apartamento.
- Gráficos de distribución: Generar histogramas o gráficos de densidad para comprender la distribución de variables como el precio de alquiler, el número de habitaciones, entre otros.
- Gráficos de correlación: Explorar las relaciones entre diferentes variables mediante gráficos de dispersión o matrices de correlación.
- Análisis geoespacial: Utilizar mapas interactivos para visualizar la distribución geográfica de los alquileres en Madrid, destacando áreas con precios más altos o una mayor oferta de apartamentos.
- Segmentación de datos: Realizar análisis segmentados por diferentes características, como ubicación, tamaño del apartamento o tipo de propiedad, para identificar patrones o tendencias específicas en cada grupo.

El análisis EDA nos permitirá descubrir insights clave, identificar patrones interesantes y generar conocimientos relevantes sobre el mercado de alquileres en Madrid.

Si tienes alguna pregunta o necesitas más detalles sobre el proyecto o el análisis EDA, no dudes en contactarnos. Estaremos encantados de ayudarte.