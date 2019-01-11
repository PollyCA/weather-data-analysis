# Weather Data Analysis
What's the Weather Like?
---

Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.


## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. The purpose of this proyect is to use Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

The obvious answer is to say that the closer to the Ecuador, the hotter the weather gets. Let's prove it.

## Objective

* Randomly process a minumum of 500 cities based on latitude and longitude to debunk the idea that the closer a city is from the Equator the warmer the weather.


In this proyect we are creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we'll be utilizing a the **citypy**, the **OpenWeatherMap API**, and a little common sense to create a representative model of weather across world cities.

The objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

* You'll find the csv here: 

## Conclusions

- **The closest you are to the Equator the warmer the weather:** As we can see in the ScatterPlot "City Latitude vs Temperature", the closest you are to the equator the warmer the weather is. Also because we are on January, it is winter season (at least in the north part of the planet) the weather is significanlty colder.. having cities below -40 C.
- **No obvious relationship between Latitude vs Humidity or Latitude vs Cloudiness** It seems that there is no relationship between Latitude vs Humidity or Latitude vs Cloudiness. Humidity and Cloudiness can be affected by many variables like whether the city is close to the sea, if there is some meteorological event close to a city, or even some random weather conditions going on. 
- **Windy places seem to be in the North** There is no obvious relationship between Wind Speed and Latitude, however it seems that there are some cities in the North that have high wind speeds. This might or might not be related to the weather. It can also be related to special conditions on those places.