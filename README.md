# World_Weather_Analysis

This analysis uses knowledge of pandas dataframes and APIs. It creates a dataframe of locations, uses citypy to link the locations to cities, then uses the Open Weather API to get weather data for the cities, then uses the google maps API to plot all the city locations with weather data, and finally use the google directions API to create a directions map of 4 locations.

## Deliverable 1 - Weather Data
Deliverable 1 includes the jupyter notebook file that creates a database of cities with their weather pulled from Open Weather API, and the output in a csv file.

## Deliverable 2 - Hotel Map

Deliverable 2 includes a jupyter notebook file, an output csv and a map image. This deliverable used the output csv created in deliverable 1, requested input from the user. This then sorted that data. Next we used the nearby places API to find hotels for all the cities that met the input criteria. Finally, this was plotted on a map with markers that included the city, country, weather, and hotel information.

## Deliverable 3 - Driving Directions

Deliverable 3 includes a jupyter notebook file and 2 image files. In this deliverable, the data output from step 2 was used and 4 cities were selected. The google directions API was used to create a map with driving directions to the 4 selected cities.
