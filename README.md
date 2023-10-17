# python-api-challenge
Module 6 Homework Assignment - Python API Challenge

## Part 1: WeatherPy
For this challenge we were tasked wtih creating plots to showcase the relationship between weather variables and latitude.

To fulfill this first requirement, we used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. We created a series of scatter plots to showcase the following relationships:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

To fulfill the second requirement, we had to compute the linear regression for each relationship. We than seperated the plots into Northern and Southern Hemisphere. The following plots were created for each hemisphere:

* Temperature vs. Latitude
* Humidity vs. Latitude
* Cloudiness vs. Latitude
* Wind Speed vs. Latitude

## Part 2: VacationPy
The main task for this challenge was to be able to use the Geoapify API and the geoViews Python library to successfuly create the following map visualizations: 

1. A map that displays a point for every city in the city_data_df. 
2. A map that displays a point for every city in the hotel_df. In addition to creating the map, we were tasked with adding the hotel name and the country as additional information in the hover message for each city on the map. 

## Source and References
* How to get current date in python > https://www.programiz.com/python-programming/datetime/current-datetime
* How to format hover tool tip > https://discourse.holoviz.org/t/add-an-extra-field-when-hovering-in-hvplot-scatter/2331