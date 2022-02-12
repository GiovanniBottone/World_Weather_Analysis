# World_Weather_Analysis

## Purpose
The purpose of this analysis was to build the recommended changes from the beta testers for the 'PlanMyTrip App.' These changes include adding the weather description to the weather data and allowing users to use input statements to filter their data for individual weather preferences, which they will use to identify potential travel destinations and nearby hotels. Once these changes have been implemented, the beta testers/users will have the ability to choose four cities to create their ideal travel itinerary. A sample travel itinerary can be seen below:

![WeatherPy_travel_map](https://user-images.githubusercontent.com/95371617/152472613-4ac07e71-ed73-498f-83b2-aa22fdc464fc.png)

## Weather Database
The weather database contains 712 City IDs obtained through the Open Weather Map API, as well as City, Country, Lat, Lng, Max Temp, Humidity, Cloudiness, Wind Speed, and Current Weather Description information. Ideally, users will filter this information to match their vacation preferences before making any travel plans. For reference, see WeatherPy_Database.csv located in the Weather_Database folder.

## Vacation Search
The vacation search database contains 156 city IDs where the minimum temperature is 75 degrees fahrenheit and the maximum temperature is 90 degrees fahrenheit, as well as the City name, Country, Actual Max Temperature, Current Weather Description, Lat, Lng, and suggested Hotel names for users to consider. For reference, see WeatherPy_vacation.csv located in the Vacation_Search folder.

## Vacation itinerary
A sample travel itenerary was created through the Google Directions API to map a route between five cities. 

![WeatherPy_travel_map](https://user-images.githubusercontent.com/95371617/152474339-0eeffe27-4cab-44b7-a0ab-ee69d0bff2cb.png)

An additional sample travel itenerary was created to show the recommended Hotel name, City, Country, and Current Weather for the selected cities on the users route. 

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/95371617/152474490-fb5b5ccf-59e0-49aa-897f-302075af79f1.png)

