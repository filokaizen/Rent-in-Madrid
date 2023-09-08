# Proyecto ETL: Análisis de Alquiler en Madrid

Este proyecto de Extracción, Transformación y Carga (ETL) tiene como objetivo analizar los datos de alquiler en Madrid. Para recopilar los datos, se implementó un scrapping web utilizando Selenium y Beautiful Soup, y para evitar las captchas se utilizó TunnelBear para cambiar las direcciones IP.

## Proceso de ETL

1. **Extracción:** Se desarrolló un script de scrapping web que recopila los datos de alquiler en varias páginas web relevantes. Se utilizó Selenium para automatizar la interacción con el navegador y Beautiful Soup para extraer la información de las páginas.

2. **Transformación:** Una vez recopilados los datos en formato CSV, se cargaron en un DataFrame de Pandas para realizar la limpieza y transformación de los mismos. Esto incluyó eliminar registros duplicados, manejar valores faltantes, corregir formatos de datos y realizar la normalización de variables si fuera necesario.

3. **Carga:** Los datos transformados se cargaron en una base de datos MySQL para su almacenamiento persistente y acceso futuro. Se creó una estructura de tablas adecuada para almacenar la información recopilada.

## Visualización y Análisis

Para realizar la visualización y análisis de los datos recopilados, se utilizó Power BI. Los datos almacenados en la base de datos MySQL se conectaron a Power BI para generar gráficos interactivos, tablas dinámicas y paneles de control que faciliten el análisis y la comprensión de los patrones y tendencias en la oferta de alquileres en Madrid.

## Landing Page en Wordpress

Para presentar los resultados obtenidos y compartir información sobre el proyecto, se creó una landing page en Wordpress. Esta página incluye una descripción del proyecto, visualizaciones de datos interactivas y conclusiones principales. Además, se brinda información sobre el equipo de proyecto y posibles vías de contacto.

¡Explora la página para descubrir los detalles y análisis interesantes sobre el alquiler en Madrid!

Si tienes alguna pregunta o necesitas más detalles sobre el proyecto, no dudes en contactarnos. Estaremos encantados de ayudarte.