# World_Weather_Analysis

## Purpose

The purpose of the project is to provide aid to PlanMyTrip to use the data to recommend ideal hotels based on clients' weather preferences. Using Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process entails the following collecting, analyzing, and visualizing the data.

In the project some modules will be used as:
- NumPy module will help to generate latitudes and longitudes.
- citypy to list the coordenates.
- OpenWeatherMap API to collect current weather data.

At the start of the project it would be neccesary the creation of several scatter plots, in order to determine correlation between the data collected

- Latitude and temperature
- Latitude and humidity
- Latitude and cloudiness
- Latitude and wind speed 

In addition, the project would require to Create a series of heatmaps using the Google Maps and Places API:
- Latitude and temperature
- Latitude and humidity
- Latitude and cloudiness
- Latitude and wind speed
- Visualize Travel Data


## Deliverable 1: Retrieve Weather Data

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

Retrieve all of the following information from the API call

- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description 
- Add the weather data to a new DataFrame 


## Deliverable 2: Create a Customer Travel Destinations Map 

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

Input statements are written to prompt the customer for their minimum and maximum temperature preferences. 
A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped. 
The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped. 
The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.

A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
- Hotel name
- City
- Country
- Current weather description with the maximum temperature


##Deliverable 3: Create a Travel Itinerary Map

Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

You will earn a perfect score for Deliverable 3 by completing all requirements below:

- Four DataFrames are created, one for each city on the itinerary.
- The latitude and longitude pairs for each of the four cities are retrieved.
- A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png.
- A DataFrame that contains the four cities on the itinerary is created. 

A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information:
- Hotel name
- City
- Country
