# Series temporales

**Datos globales** capturados automáticamente desde los siguientes repositorios del **Centro de Ciencia de Ingeniería y Sistemas de la Universidad Johns Hopkins**:

- Serie temporal de **casos confirmados**: [time_series_19-covid-Confirmed.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_19-covid-Confirmed.csv)
- Serie temporal de **recuperaciones**: [time_series_19-covid-Recovered.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_19-covid-Recovered.csv)
- Serie temporal de **fallecimientos**: [time_series_19-covid-Deaths.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_19-covid-Deaths.csv)

A partir del `22` de marzo de `2020` no se actualizan los datos anteriores y no se ofrecen datos de `Recuperaciones` (supongo que temporalmente). Los nuevos archivos actualizados son:

- Serie temporal de **casos confirmados**: [time_series_covid19_confirmed_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)
- Serie temporal de **fallecimientos**: [time_series_covid19_deaths_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv)

Para simplificar la consulta de los repositorios anteriores, se han creado tablas fácilmente navegables con la ayuda de la librería [**`DT`**](https://rstudio.github.io/DT/) para **`R`**. 

Se puede consultar la página en <https://eclectikus.github.io/jhutimeseries/> (se actualiza cada mañana)