# World_Weather_Analysis

## Purpose
- The purpose of this project to pick random 2000 cities all over the world, and create a dataframe that includes latitudes, longitudes, temperature, and current weather descption of all cities. 
- This project mainly divided in to three part, and each part has a folder,
    - Weather_Database
    - Vacation_Search
    - Vacation_Itinerary

### Weather_database
- Weather_database folders includes data that runs random 2000 cities all over the world, and create a dataframe that includes latitudes, longitudes, temperature, and current weather descption of all cities. Then save as csv file that will help for next step. We used API keys from https://openweathermap.org/ to run and gather all the datas. 

### Vacation_Search
- Vacation_Search folders includes nearest hotels in that city found by latitudes and longitutdes. I first import and read the csv file from Weather_database folder, and use Google Cloud Platform API Keys to run and gather all the datas. Then I made a marker layer that shows all infos on google map.
- ![](https://github.com/helen3121433/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

### Vacation_Itinerary
- Catation_Itinerary folders is for creating a route map for multiple stops. User may choose filter the max and min temperature from the csv list in Vacation_search. Then the code will also create travel itinerary that shows rote between four cities chosen between starting point, ending destination, and stop 1, 2, 3. Then, also create a market layer map for each city on the itineary.
- ![](https://github.com/helen3121433/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)
- ![](https://github.com/helen3121433/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)

### Overview
- If to improve, I will add in couple more input string for customer to choose which four or more cities they want to add. Once they input city name, it will run all data for them.