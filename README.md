# Python_API_Challenge
This is a repo containing my solutions to the Python API Challenge assignments.

## Part I: What's the weather like?
The first task was to create a Python script to visualize the weather of 500+ randomly-selected cities around the world. Using the OpenWeather API I collected data points for each city and displayed them in a dataframe. Then I built a series of scatter plots to show relationships between latitude and temperature, latitude and humidity, latitude and cloudiness, and latitude and wind speed.

Regression analysis showed a fairly strong negative correlation between latitude and temperature for all cities (randomly) selected. There was a positive correlation between latitude and humidity among the Southern hemisphere cities. Analysis revealed little to no correlation between wind speed and latitude in both hemispheres.

## Part II: Using weather data to plan hyptothetical vacations
Using jupyter-gmaps and the Google Places API I created a heatmap to display the humidity in each of the cities from Part I. Then I narrowed the list of cities based on my ideal conditions and called the 'nearby' search of the Google API to identify the nearest hotel for each destination. I plotted the hotels 40 hotels that met my criteria and added pins with the hotel name, city name, and country name.

