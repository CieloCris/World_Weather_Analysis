# World Weather Analysis

## Overview

In this project, we helped Jack, a data analyst who works at PlanMyTrip,  a company dedicated to providing tourism services through the internet.

Our **purpose **was to collect and present data to tourists about weather conditions and hotels around the world according to their preferences. To accomplish this goal, we used Jupyter Notebook, Pandas, Numpy and APIs calls about the weather conditions, places, and directions. To do this task we also utilized _Citipy_ to randomly select city coordinates, and after that, we used requests on the Open Weather Map API, Google Places API, and Google Directions API in order to get information to create dataframes and maps.

The results of our work are in the Weather_Database, Vacation_Search, and Vacation_Intinerary folders.

##Resources
**Data sources:** WeatherPy_vacation.csv, WeatherPy_Database.csv
**Programming tools:** Python, Jupyter Notebook, Pandas, NumPy, CitiPy, SciPy, Requests, JSON, APIs.

## Results
### Deliverable 1: Retrieve Weather Data
The first part of our challenge was to create a CSV file about the weather conditions. Our task was to identify travel destinations according to client preferences about the weather. We generated a set of 2,000 random destinations using Citipy, and then we made an API call with the Open Weather Map to know the weather conditions of those places. After that, we created a DataFrame containing the information:

![Alt text](/Resources/1dataframe.png "imagen1")

Finally, is important to say that in the Weather_Database folder, we can find the Jupyter Notebook file Weather_Dabase.ipynb and the dataset WeatherPy_Database.csv.

### Deliverable 2: Create a Customer Travel Destinations Map

In the second part of the challenge, we identified potential travel destinations and their respective nearest hotel using the Google Places API. We also created a map that presented the cities and a marker layer map with a pop-up marker containing information. The following pictures show the results of our task:

![Alt text](/Resources/df_hotels.png "imagen2")

![Alt text](/Vacation_Search/WeatherPy_vacation_map.png "imagen3")

In the Vacation_Search folder, we can see the Vacation_Search.ipynb file, plus the WeatherPy_vacation.csv and the WeaterPy_vacation_map.png.

### Deliverable 3: Create a Travel Itinerary Map

In the last part of the project,  we used the Google Directions API to create a travel Itinerary that presented the route between four cities in India. In addition, we created another marker layer map with a pop-up marker for each destination on the route.
The following maps show the results of our work:

![Alt text](/Vacation_Itinerary/WeatherPy_travel_map.png "imagen4")

![Alt text](/Vacation_Itinerary/WeatherPy_travel_map_markers.png "imagen5")

In the Vacation_Itinerary folder, we saved the Vacation_Itinerary.ipynb and some maps.

## Summary

The use of APIs allowed us to improve MyPlanTrip application, which allows tourists to travel to different cities according to preferences in weather conditions and the location of nearby hotels.
