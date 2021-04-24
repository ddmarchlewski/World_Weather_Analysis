# World_Weather_Analysis

## Overview
In this project, we take a look at various weather patterns around the world and look for the best places to take a vaction based on the weather data. There are three folders that contain all of the data used for this analysis: weather_database, vacation_search, and vacation_itinerary.

### Weather Database
In this folder, an API code from Open Weather Map is used to gather data from 684 different cities around the world. The data the was gathered was:
  1. The country the city is in
  2. Latitude 
  3. Longitude
  4. Maximum teperature
  5. Humidity level
  6. How cloudy the city is
  7. The current wind speed
  8. The current weather discription
  9. Current rain inches
  10. Current snow inches
 
Travelors can take a look at this data and easily decide where they are wanting to go.

### Vacation Search
In this folder, we plotted hotels from different cities using the data from the weather database folder and a Google Maps API. In the image below, all hotels from the databased on marked and and the points show the name of the hotel, the city it's located in, the current weather, and its maximum temperature. 
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/80054925/115972685-79207a80-a515-11eb-9db4-0ab28edb9dc9.png)

### Vacation Itinerary
In this folder, we create a vacation itinerary by using the data gatherd from the vacation search folder and a Google Maps Api. The image below shows a four stop itinerary that goes through New York, Connecticut, and Massachusetts.
![WeatherPy_travel_map](https://user-images.githubusercontent.com/80054925/115973034-bb4abb80-a517-11eb-99a1-053b6974fc4f.png)
This one shows the hotel names for each location.
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/80054925/115973042-d0bfe580-a517-11eb-9535-b9c678228337.png)
