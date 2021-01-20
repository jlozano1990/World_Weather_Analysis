# World_Weather_Analysis
## Purpose
The purpose of this project is to be able to provide real-time suggestions for PlanMyTrip's client's ideal hotels. This project will involve weather analysis as well as hotel options for the cities PlanMyTrip's clients say they're interested in. We will also provide these clients with a map of their destinations and a map displaying a suggested itinerary based on their inputs.
## Results
We began by creating a random set of 2000 random latitudes and longitudes by using the Python CityPy module. From these sets of coordinates, we identified the closest cities and gave descriptive statistics of said cities which included the max temperature, the humidity, the percentage of cloudiness, the wind speed and live description of the weather in the area.
  - Latitude VS Max Temp
    
    ![Latitude vs Max Temp](https://github.com/jlozano1990/World_Weather_Analysis/blob/main/weather_Data/Fig1.png)
  - Latitude VS Humidity
    
    ![Latitude vs Humidity](https://github.com/jlozano1990/World_Weather_Analysis/blob/main/weather_Data/Fig2.png)
  - Latitude VS % Cloudiness
   
    ![Latitude vs %Cloudiness](https://github.com/jlozano1990/World_Weather_Analysis/blob/main/weather_Data/Fig3.png)
  - Latitude VS Wind Speed
    
    ![Latitude vs Wind Speed](https://github.com/jlozano1990/World_Weather_Analysis/blob/main/weather_Data/Fig4.png)
    
After combing through some of the data from the Weather API, we created a tool for clients to plan out their vacation destinations. We used the Google Maps API to show hotels in a close area of the cities we found. The map shows an option for a hotel close to each city as well as a description of what the weather would be like in these areas.
  - WeatherPy Travel Map Example
    
    ![WeatherPy Travel Map Example](https://github.com/jlozano1990/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)
  - WeatherPy Travel Map Marker Example
  
    ![WeatherPy Travel Map Marker Example](https://github.com/jlozano1990/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
