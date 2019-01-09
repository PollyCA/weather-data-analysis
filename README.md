# Weather Data Analysis
What's the Weather Like?
---

Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.


## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. The purpose of this proyect is to use Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

The obvious answer is to say that the closer to the Ecuador, the hotter the weather gets. Let's prove it.

## Script

In this proyect we are creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we'll be utilizing a the **citypy**, the **OpenWeatherMap API**, and a little common sense to create a representative model of weather across world cities.

The objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The final notebook must:

* Randomly select **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

As final considerations:

* It's needed to complete the analysis using a Jupyter notebook.
* It's needed to use the Matplotlib or Pandas plotting libraries.
* It's needed to include a written description of three observable trends based on the data.
* It's needed to use proper labeling of your plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.
