# Proyecto Individual de Análisis de Datos

## Presentación general del proyecto

  Mi nombre es Federico Molina, soy Analista de Datos y en esta oportunidad les traigo un proyecto que es muy importante para todos aquellos que somos parte de la sociedad y del sistema de tránsito, y que desafortunadamente como en mi caso, han sufrido la terrible experiencia de lamentar la triste pérdida de un ser amado en un sinistro vial.
  
  Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre autos, motos, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.
  
  Los siniestros viales pueden ser una preocupación importante en Argentina en general, y específicamente en la ciudad de Buenos Aires, debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.
  
  Es importante destacar que la prevención de siniestros viales involucra medidas como la educación vial, el cumplimiento de las normas de tráfico, la infraestructura segura de carreteras y calles, así como la promoción de vehículos más seguros. El seguimiento de las estadísticas y la implementación de políticas efectivas son esenciales para abordar este problema de manera adecuada.

  
#### Contexto

  En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país. Los informes del Sistema Nacional de Información Criminal (SNIC), del Ministerio de Seguridad de la Nación, revelan que entre 2018 y 2022 se registraron 19.630 muertes en siniestros viales en todo el país. Estas cifras equivalen a 11 personas por día que resultaron víctimas fatales por accidentes de tránsito.
  
  Solo en 2022, se contabilizaron 3.828 muertes fatales en este tipo de hechos. Los expertos en la materia indican que en Argentina es dos o tres veces más alta la probabilidad de que una persona muera en un siniestro vial que en un hecho de inseguridad delictiva.

  
#### Introducción

  El Observatorio de Movilidad y Seguridad Vial (OMSV), organismo dependiente del gobierno de la Ciudad Autónoma de Buenos Aires, solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para este estudio, disponibiliza un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Se puede encontrar en https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales.
  
  Para el análisis exploratorio, realizaré una serie de scripts en un Jupyter Notebook y para el apartado gráfico utilizaré principalmente `seaborn`, una librería de visualización de datos basada en `matplotlib`.
  
  Durante el primer análisis de datos no se observó presencia de outliers en la edad ni en la cantidad de víctimas en un accidente (variables que consideré unas de las más importantes en mi estudio), como tampoco de duplicados. Existen valores faltantes, pero en proporciones mínimas(menos del 10% en el mayor de los casos) y por lo tanto consideré que no era necesario realizar ninguna transformación importante respecto a eso.
  
  A la hora de realizar gráficas comencé a notar cosas que en mis primeras hipótesis ya estaba prácticamente seguro: la mayor cantidad de víctimas de accidentes de tránsito circulan en moto y son jóvenes menores de 30 años, y en contrapartida, los mayores responsables de estos siniestros son conductores de autos y vehículos de carga. También es triste notar que las personas de la tercera edad ocupan la mayoría del porcentaje de muertes de peatones.

  También se pudo observar que hay comunas que registran una cantidad muy superior de siniestros respecto a otras, lugares donde se deben tomar medidas con mayor exhaustividad, así como noté que en ciertos tipos de calles hay ciertos vehículos que marcan predominancia, tanto en víctimas como en acusados.
     

#### Dashboard
  Con todos estos datos e información procedí a realizar un dashboard interactivo con diversos tipos de gráficos que no hicieron otra cosa más que concordar con los análisis anteriormente realizados. Realice un gráfico de líneas para mostrar las cantidades de siniestros respecto al tiempo, un gráfico de columnas que mostrara la edad y los vehículos en los que circulan las víctimas, indicando también en qué circulan los acusados de esos siniestros y un gráfico circular que muestre mejor esto último. También realicé una tabla que mostrara las comunas que tienen mayor cantidad de fallecidos por accidentes de tránsito. Sin embargo, lo más importante del dashboard fue la medición de 3 KPIS, dos que me había solicitado la organización y uno adicional que consideré adecuado incluir. Sin embargo, hacer comparaciones con el año anterior, en el cual se desarrolló la pandemia casi en su totalidad, terminó mostrando resultados frustrantes, de todas maneras creo que dadas las circunstancias, los valores apenas por arriba del año anterior de cuarentena, no deberían mirarse como totalmente negativos.

### Repositorio
  En este repositorio se puede encontrar para su consulta:
  - Readme.md: explicación del proceso de trabajo
  - PIDA.ipynb: jupyter Notebook con la lectura de datos y el EDA
  - homicidios.xlsx: dataset original
