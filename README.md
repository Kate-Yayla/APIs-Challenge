# Python API Project

## Overview


Using g_key and OpenWeather key, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.I utilized a simple Python library, the OpenWeatherMap API, and also create a representative model of weather across world cities.

![Equator](Images/equatorsign.png)

### Part I - WeatherPy

Serious of scatter plots created to show the relation between Latitude and Cloudiness, Humidity, Temperature and Wind Speed. 

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


#### Latitude vs. Cloudiness Plot
![](output_data/Latitude%20vs.%20Cloudiness%20Plot.png )

#### Latitude vs. Humidity Plot
![](output_data/Latitude%20vs.%20Humidity%20Plot.png)

#### Latitude vs. Temperature Plot.png
![](output_data/Latitude%20vs.%20Temperature%20Plot.png)

#### Latitude vs. Wind Speed Plot
![](output_data/Latitude%20vs.%20Wind%20Speed%20Plot.png)

Run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
![](output_data/NH-MT.png)
* Southern Hemisphere - Temperature (F) vs. Latitude
![](output_data/SH-MT.png) 
* Northern Hemisphere - Humidity (%) vs. Latitude
![](output_data/NH-H.png)
* Southern Hemisphere - Humidity (%) vs. Latitude
![](output_data/SH-H.png)
* Northern Hemisphere - Cloudiness (%) vs. Latitude
![](output_data/NH-C.png)
* Southern Hemisphere - Cloudiness (%) vs. Latitude
![](output_data/SH-C.png)
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
![](output_data/NH-WS.png)
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
![](output_data/SH-WS.png)


### Part II - VacationPy

Used exported data from weatherpy and configured as gmaps. After cleanup the data, added heatmap layer to map. Narrowed the cities and found the hotels with 5000 meters. Used Google Places API for each city's coordinates and plot them on the heatmap. 

#### Heatmap
  ![heatmap](Images/heatmap.png)

#### Hotel Map
![hotel map](Images/hotel_map.png)
