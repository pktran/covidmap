# Project 3: Web Map Application

In this lab, I will design a web map application. This application consist of two maps: a proportional symbol map and a chloropleth map of COVID in 2020.

![rates](/img/rates.png)
[Covid Rates 2020](http://127.0.0.1:5500/map1.html)

![cases](/img/cases.png)
[Covid Cases 2020](http://127.0.0.1:5500/map2.html)

These maps were creating using Mapbox by converting shapefiles to geojson files using QGIS. The source of the data is from [The New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv), population data used for rate conversion was from [2018 ACS 5 year estimates](https://data.census.gov/cedsci/table?g=0100000US%24050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true), and county shapefile were from [the U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html). The data has been also processed by Steven Bao for this lab's purpose.  

