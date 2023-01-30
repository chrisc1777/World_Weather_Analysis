# World_Weather_Analysis
## Overview
PlanMyTrip is a travel technology company that specializes in internet-related services in the hotel and lodging industry. They are beta testing their app to identify potential travel destinations and nearby hotels for app users. The beta test requires creating a DataFrame with a random list of cities along with API calls for weather info, filtering city list based on customer weather preferences, and generating a map route for user traveling destinations.


## Objetives
- Use Jupyter Notebook and Pandas to generate a random list of 2,000 latitudes and longitudes and use citipy to find the nearest city. Then retrieve weather data for each city by calling OpenWeatherMap APIs. Add the lists of cities and weather descriptions to a DataFrame.
- Filter the data with the customer's preferred minimum and maximum weather temperature preferences for travel. Create a new DataFrame with the filtered cities to add a new column for hotels and use Geoapify API calls to find the nearest hotels. Also, create a map visual using GeoViews to display potential vacation locations with city and weather descriptions.
- Modify the DataFrame using Pandas to filter and merge four cities within a country. Then use Geoapify Routing API to retrieve the map route for the selected destinations. Finally, create a  map route visual for the four traveling cities with Geoviews and its Path function. 

## Results
- DataFrame with cities and weather descriptions

![wwa1](https://user-images.githubusercontent.com/106359564/215585358-dbc09a67-f74f-4aeb-8ac7-e8a9fc821aef.png)


- List of cities with customer prefered weather and map visual of potential traveling destinations

![wwa3](https://user-images.githubusercontent.com/106359564/215585502-ab7dab25-d3b3-44c7-a962-513eccdb1ea0.png)
![wwa2](https://user-images.githubusercontent.com/106359564/215585415-57c92fd0-829b-44a7-98fe-2aee868cf5b9.png)
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106359564/215576133-1f231cbe-7c7f-415a-aa17-4cffa4ca5922.png)


- Filtered data with the four traveling cities and map route visual for customer

![wwa4](https://user-images.githubusercontent.com/106359564/215585516-6d94f3ba-7743-44b9-aabf-41114e4c1835.png)
![WeatherPy_travel_map](https://user-images.githubusercontent.com/106359564/215576179-bcd0dc8d-9861-4bf8-8ef2-8570d992111e.png)

## Summary
