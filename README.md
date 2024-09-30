# Análisis de Datos de Covid-19 en Estados Unidos
## Reto

Este proyecto tiene como objetivo realizar un análisis de datos históricos sobre la incidencia de Covid-19 en Estados Unidos, utilizando una API pública y gratuita que proporcionó datos hasta 2021. La API se encuentra en el siguiente enlace: [Covid Tracking Project API](https://covidtracking.com/data/api).

## Objetivo

El objetivo es cargar los datos desde la API utilizando Python, explorar la información, y elaborar un informe con conclusiones y descubrimientos relevantes. Se busca contar una historia basada en los datos recopilados.

## Tecnologías utilizadas

Este proyecto hace uso de las siguientes tecnologías:

- **Requests**: Para realizar solicitudes HTTP a la API y obtener los datos.
- **Pandas**: Para manipulación y análisis de datos.
- **Matplotlib**: Para visualización de datos.
- **Seaborn**: Para crear visualizaciones estadísticas atractivas y informativas.
- **Bokeh**: Para crear visualizaciones interactivas y dinámicas.

## Conclusiones
### Gráfico 1: Mapa de calor de casos positivos por estado y fecha

Este gráfico muestra la distribución de los casos positivos de COVID-19 a lo largo del tiempo en diferentes estados. Los estados están listados en el eje X y las fechas en el eje Y.

Observamos que los estados de **California (CA)** y **Texas (TX)**, así como otros estados como **Arizona (AZ)** y **Tennessee (TN)**, tienen áreas de mayor intensidad de color, lo que indica que han experimentado períodos con un alto número de casos positivos.

La relación entre los altos números de casos positivos en **CA** y **TX** podría estar ligada al hecho de que estos son dos de los estados más poblados de los EE. UU. (California es el estado más poblado, seguido de Texas). A mayor densidad de población, mayor probabilidad de propagación del virus.

El gráfico también sugiere que en algunos estados, los casos positivos se mantuvieron más estables y bajos a lo largo del tiempo, como en **Alaska (AK)**, **Hawái (HI)**, y otros estados menos poblados.

---

### Gráfico 2: Comparación de tasas de incidencia entre los estados con mayores y menores tasas

En este gráfico de barras se comparan los estados con las tasas de incidencia más altas y más bajas de COVID-19. La tasa de incidencia se refiere al porcentaje de la población que ha contraído la enfermedad.

### Los estados con las tasas de incidencia más altas son:
- **Idaho (ID)** con más del 20%.
- **Kansas (KS)**, **Alabama (AL)**, e **Iowa (IA)** también presentan tasas cercanas al 17-18%.

### En cambio, los estados con tasas de incidencia más bajas son:
- **Islas Marianas del Norte (MP)**, **Samoa Americana (AS)**, **Vermont (VT)**, y **Maine (ME)**, que presentan tasas muy bajas, menores al 5%.

### Mapa de calor de casos positivos por estado y fecha


Observamos que los estados de California (CA) y Texas (TX), así como otros estados como Arizona (AZ) y Tennessee (TN), tienen áreas de mayor intensidad de color, lo que indica que han experimentado períodos con un alto número de casos positivos.

El gráfico también sugiere que en algunos estados, los casos positivos se mantuvieron más estables y bajos a lo largo del tiempo, como en Alaska (AK), Hawái (HI), y otros estados menos poblados.

### Comparación de tasas de incidencia entre los estados con mayores y menores tasas

En este gráfico de barras se comparan los estados con las tasas de incidencia más altas y más bajas de COVID-19. La tasa de incidencia se refiere al porcentaje de la población que ha contraído la enfermedad.

Los estados con las tasas de incidencia más altas son:
- Idaho (ID) con más del 20%.
- Kansas (KS), Alabama (AL), e Iowa (IA) también presentan tasas cercanas al 17-18%.

En cambio, los estados con tasas de incidencia más bajas son:
- Islas Marianas del Norte (MP), Samoa Americana (AS), Vermont (VT), y Maine (ME), que presentan tasas muy bajas, menores al 5%.

### Mapa de calor de la tasa de mortalidad por estado y fecha
Observamos que California (CA), Texas (TX) y Nueva York (NY) muestran áreas con colores más oscuros, lo que indica que en estos estados la mortalidad ha sido considerablemente alta.

En cambio, estados como Alaska (AK), Hawái (HI), Maine (ME) y Samoa Americana (AS) presentan colores más claros, lo que indica que la mortalidad en estos estados ha sido baja a lo largo del tiempo.

### Estados más poblados y tasas altas de contagios:

Los estados con mayores poblaciones, como California y Texas, muestran una alta cantidad de casos positivos, lo que sugiere una correlación entre la densidad de población y la propagación del virus. Sin embargo, la tasa de mortalidad en estos estados podría estar influenciada por otros factores, como el acceso a los servicios de salud, la respuesta gubernamental, y la capacidad hospitalaria.

### Estados con menor densidad de población:

Estados menos poblados, como Idaho (ID) y Kansas (KS), sorprendentemente presentan altas tasas de incidencia, lo cual podría estar relacionado con diferencias en la gestión de la pandemia, factores culturales, y acceso limitado a los recursos médicos en áreas rurales.

### Estados con tasas bajas de incidencia:

Estados como Vermont (VT) y Maine (ME), que son conocidos por tener una baja densidad de población y una respuesta más estricta en términos de confinamientos y políticas de salud pública, han logrado mantener tasas de incidencia bajas.

### Mortalidad en estados altamente afectados:

Nueva York (NY), California (CA) y Texas (TX) destacan en los gráficos por tener una tasa de mortalidad más elevada en comparación con otros estados. En Nueva York, durante las primeras fases de la pandemia, la rápida propagación del virus en áreas metropolitanas densamente pobladas y la saturación del sistema de salud fueron factores clave en el aumento de la mortalidad. De manera similar, tanto California como Texas experimentaron un crecimiento notable de muertes, probablemente debido a su gran población y alta densidad en ciertas ciudades.
