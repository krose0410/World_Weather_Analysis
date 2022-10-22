# World_Weather_Analysis
## Overview
This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.
## Weather Database
This folder uses Open Weather Map API to pull weather information on over 720 different cities around the world. That information consists of:
1. Maximum Temperature
2. Cloudiness
3. Wind Speed
4. Humidity
5. Current Weather Description
These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.
## Vacation Search
This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have a daily maximum temperature between 75- and 88-degrees Fahrenheit.
![WeatherPY_vacation_map](https://user-images.githubusercontent.com/109715441/197363166-f338c7dc-5a5e-4264-a673-938df7d81f86.png)
## Vacation Itinerary
This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4-stop itinerary in Northern California that features San Ramon, Merced, Orange Cove, and Half Moon Bay.<img width="1008" alt="Weather_travel_map" src="https://user-images.githubusercontent.com/109715441/197363210-23f6b1c7-c228-4be3-8bec-90514910e0d6.png">
Also, as with the vacation search folder, there is a hotel at each location.
![WeatherPY_vacation_map](https://user-images.githubusercontent.com/109715441/197363349-8185ba70-beba-4d45-b398-e8df11cae024.png)
## Bonus: Weather Data
As an addon to these three folders, there is a weather data folder that has valuable linear regression models looking at the correlation between different weather information and latitude. These take into consideration the different weather information that are used in the weather database folder. Please view this if you <img width="576" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/109715441/197363390-6b7492a9-9d08-4449-b1d1-971f49fc3131.png">
are interested.
