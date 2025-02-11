
# Analysis of foot traffic in Wuerzburg

## Introduction

This repository analyses the foot traffic in a shopping street in the German city Wuerzburg.
Aside from some general aspects like time series, daily courses, etc., also the impact of weather
on foot traffic is analysed. The repository contains five jupyter notebooks:

1. prepare_Data.ipynb  
In this notebook, the foot traffic data is pre-processed. Data gaps are filled and information
on public holidays, black week, etc., is added.

2. prepare_weatherdata.ipynb  
In this notebook weather data is pre-processed. Missing values are converted to NaNs, and some statistics
like e.g. mean or max values are computed.

3. data_analysis1.ipynb  
The goal of this notebook is to analyse some general aspects of foot traffic behaviour,
like e.g. time series, outlier, daily courses, etc.

4. data_analysis_impact_weather.ipynb  
In this notebook the impact of weather on foot traffic is analysed. Aside from some exemplary
outliers also a systematic analysis is performed.

5. prediction.ipynb  
The aim of this notebook is to demonstrate the potential of using weather data as predictors
to accurately predict foot traffic.


## Datasets

The analysis is performed using the following datasets:

1. Foot traffic data from the city Wuerzburg (https://opendata.wuerzburg.de/pages/home/) as provided by
Hystreet (https://hystreet.com). 

2. Meteorological station data from the German Weather Service (DWD). These datasets are available
on the open data platform of the DWD (https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/). Here, the data for the station with ID 05705 is used, which
is closest to the city of Wuerzburg.  

3. School holiday dates from https://ferien-api.de/api/v1/holidays/.

4. Public holiday dates from https://date.nager.at/api/v3/PublicHolidays/.


## Instructions

Make sure you have Jupyter Notebook and the required Python libraries (e.g. Pandas, seaborn) installed, and clone or download this repository to your local machine. Please apply the notebooks in the numerical order given above.

## License

See https://opendata.wuerzburg.de/terms/terms-and-conditions/.
