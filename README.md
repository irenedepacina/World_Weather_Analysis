# World_Weather_Analysis

## Overview of the Project
This project makes a few changes to improve a weather app. Specifically, the weather description was added to the weather data already retrieved. Input statements were used to filter the data for their weather preferences, which were used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, four cities were chosen to create a travel itinerary. Finally, Google Maps Directions API were used to create a travel route between the four cities as well as a marker layer map.

### Purpose
The purpose of the project is collect and analyze weather data across cities worldwide. The app uses the data to recommend ideal hotels from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature. In addition, the app creates a travel itinerary using the Directions API. The hotels and itinerary are based on clients' weather preferences.

## Analysis

1. A set of 2,000 random latitudes and longitudes were generated to retrieve the nearest city and perform an API call with the OpenWeatherMap. In addition to the city weather data gathered in the module were used to retrieve the current weather description for each city. A new DataFrame containing the updated weather data was created.

2. Input statements were used to retrieve customer weather preferences, then those preferences identified potential travel destinations and nearby hotels. Those destinations on a marker layer map with pop-up markers was setup and saved a png file.

3. Google Directions API was used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. A marker layer map with a pop-up marker for each city on the itinerary was created and saved a png file.