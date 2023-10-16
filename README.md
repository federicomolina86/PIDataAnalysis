# Proyecto de Data Analytics sobre víctimas de siniestros viales
  Mi nombre es Federico Molina, soy Analista de Datos y en esta oportunidad les traigo mi primer proyecto de Data Analytics, uno que es muy importante para todos aquellos que somos parte de la sociedad y que desafortunadamente como en mi caso, han sufrido la terrible experiencia de lamentar la triste pérdida de un ser amado en un siniestro vial.

### Presentación general 
  Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas y consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados. En Argentina mueren cerca de 4.000 personas al año en siniestros viales, siendo la principal causa de muertes violentas. Son una preocupación importante en todo el país en general, y en CABA en particular, debido al alto volumen de tráfico y la densidad poblacional.
  
![](https://github.com/federicomolina86/Proyecto-DataAnalytics/blob/main/src/siniestro_vial.jpg)  

### Introducción

![](https://github.com/federicomolina86/Proyecto-DataAnalytics/blob/main/src/BA_logo.jpeg)

  El Observatorio de Movilidad y Seguridad Vial (OMSV), organismo dependiente del gobierno de la Ciudad Autónoma de Buenos Aires, me solicitó la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para este estudio, disponibiliza un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Se puede encontrar en https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales.
  Para el análisis exploratorio, realizaré una serie de scripts en un Jupyter Notebook y para el apartado gráfico utilizaré principalmente `seaborn`, una librería de visualización de datos basada en `matplotlib`.
  
## Dashboard
  Con todos estos datos e información procedí a realizar un dashboard interactivo en `Power BI` que mostrara 3 KPIS, dos solicitados por el organismo y uno recomendado por mí. Además incluí un gráfico de líneas para mostrar las cantidades de siniestros respecto al tiempo, un gráfico de columnas que mostrara la edad y los vehículos en los que circulan las víctimas, indicando también en qué circulan los acusados de esos siniestros y un gráfico circular para detallar esto último. Todos estos gráficos pueden mostrar información segmentada por dos filtros: uno por fechas y otro por tipo de calles.
  
![](https://github.com/federicomolina86/Proyecto-DataAnalytics/blob/main/src/Insight.png)

### Repositorio
  En este repositorio se puede encontrar para su consulta:
  - 'Dashboard-siniestros.pbix': dashboard interactivo.
  - 'ETL-EDA.ipynb': jupyter Notebook con la lectura de datos y el EDA.
  - 'homicidios.xlsx': dataset original.
  - 'README.md'
  - Carpeta 'src': con imágenes del README
