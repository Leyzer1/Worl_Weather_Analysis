# World_Weather_Analysis

#Overview
In this project we created a weather database by creating our destinations with random functions. From this data we then generated a vacation search database, and lastly we created a road trip between 4 different destinations.

#Weather Database
In this folder we can find a cvs file that was generated with random functions. The data was extracted from the Open Weather Map API using a unique key. We were able to extract data for 684 different cities. The data includes: country, latitude, longitude, maximum temperature, humidity levels, cloudiness, wind speed, and current description. This database is prime information to anyone who whichs to travel to these cities.

#Vacation Search
In this folder you will find the code for how to use Google Maps API to plot the different destinations from the Weather Database.
In this code the user will be prompted to choose their ideal weather settings by choosing a minimum and maximum. After choosing the weather settings, the code will generate a Google map with all the possible locations that fit their criteria.


#Vacation Itinerary
In this folder you will find the code that takes the vacation search to the next level. With this code we can plan a 4 city trip based on the results from the previous exercise, then plan a route to travel. For the example below I chose a couple of cities in Central America and made my way down to South America.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/95899763/153818710-242ba3f2-5a2c-491b-844c-25cb0ffc9920.png)

Unfortunately, I was not able to make the route destinations to work. I tried using all three forms of "Travel Mode'': driving, bicycling, or walking, but none seem to work. This will need to be reviewed at a later time. It is possible that there is no current route from these destinations. These results will be pending for now.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/95899763/153818792-947e5f9c-82ca-4e8b-9012-93f724d2c003.PNG)
