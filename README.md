# World_Weather_Analysis

## Overview
### Help the *Plan My Trip* company provide better reccommendations for ideal hotels based on clients' weather preferences. To do so we have been tasked to collect and analyze weather data across cities worldwide. Our analysis performed was split into 3 main stages:

1. *Collect the Data*
	- Generate over 1500 random latitudes and longitudes and find the nearest city to these coordinates. 
	- Request current weather data from OpenWeatherMap API for each unique city in the list.
	- Parse the JSON data from the API request and collect the following data:
		- City, country, and date
		- Latitude and longitude
		- Maximum temperature
		- Humidity
		- Cloudiness
		- Wind speed

2. *Exploratory Analysis with Visualization*
	- Create scatter plots of the weather data for the following comparisons:
		- Latitude versus temperature
		- Latitude versus humidity
		- Latitude versus cloudiness
		- Latitude versus wind speed
	- Determine the correlations for the following weather data:
		- Latitude and temperature
		- Latitude and humidity
		- Latitude and cloudiness
		- Latitude and wind speed
	- Create a series of heatmaps using the Google Maps and Places API that showcases the following:
		- Latitude and temperature
		- Latitude and humidity
		- Latitude and cloudiness
		- Latitude and wind speed

3. *Visualize Travel Data*
	- Create a heatmap with pop-up markest that display information on specific cities based on customers' travel preferences.

4. *Take the App to the Next Level*
	- Add the weather description to the weather data
	- Filter the data for weather preferences
	- Create a travel route between four cities as well as a marker layer map

