# Project: Visualizing Real World Data: COVID-19 stats

## Overview
The following notebook contains interactive dashboards with the information of COVID-19 cases worldwide.

##Dataset:
Data information it's provided by an api conection request: https://covid19api.com/. This API refresh every day
its information from the official information source https://github.com/CSSEGISandData/COVID-19 from the Center for Systems Science and 
Engineering at John Hopkins University 

### URL: https://api.covid19api.com/all 

Contains all the aggregated data by countries

### Field description
* Country: country/region name conforming to WHO (will be updated).
* Province: China - province name; US/Canada/Australia/ - city name, state/province name; Others - name of the event (e.g., "Diamond Princess" cruise ship); other countries - blank.
* Lat: Latitude at Province/State level - China, US, Canada, Australia; Country level - other countries. All points shown on the map are based on geographic centroids, and are not representative of a specific address, building or any location at a spatial scale finer than a province/state.
* Lon: Longitude at Province/State level - China, US, Canada, Australia; Country level - other countries. All points shown on the map are based on geographic centroids, and are not representative of a specific address, building or any location at a spatial scale finer than a province/state.
* Date: YYYY/MM/DDTHH:mm:ssZ format ISO_8601.
* Cases: Number of cases
* Status: 
  * Confirmed: the number of confirmed cases. For Hubei Province: from Feb 13 (GMT +8), we report both clinically diagnosed and lab-confirmed cases. 
    For lab-confirmed cases only (Before Feb 17), please refer to [who_covid_19_situation_reports](https://github.com/CSSEGISandData/COVID-19/tree/master/who_covid_19_situation_reports). 
    For Italy, diagnosis standard might be changed since Feb 27 to "slow the growth of new case numbers." ([Source](https://apnews.com/6c7e40fbec09858a3b4dbd65fe0f14f5))
  * Deaths: the number of deaths.
  * Recovered: the number of recovered cases.
  
The dashboards pressent in the final part a little insight of the data obtained.