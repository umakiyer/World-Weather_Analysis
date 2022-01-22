# World-Weather_Analysis
## Purpose of the repository :
1. Weather Database:

   * Created 2000 latitude & longitudes using random number function.
   * Using Citipy , created list of the citites from longitudes & latitude.
   * Using openweathermap , created city dataframe for the cities found in open weather map. 
   * Saved the dataframe to a csv file (WeatherPy_Database).

2.  Database for Hotel for the cities database:

    * Customers are prompted to enter their preference of low & high temperature range for the vacation.
    * Created new DataFrame based on the minimum & maximum temperature. Dropped the empty rows.
    * Hotel name is retrived (from GMAPS) and added to the DataFrame & dropped the rows that didn't have hotel name.
    * The DataFrame is saved as CSV file( WeatherPy_vacation).
    * A marker layer map with pop-up marker for the cities in the vacation DataFrame was created.
    * Each marker included the hotel name, city, country, weather description & temperature.
    * Saved the map with marker as Weather_vacation_map.PNG.
![image](Vacation_Search/WeatherPy_vacation_map.PNG)

3. Create Travel Itinerary Map:

    * Created four DataFrames for four cities in the same country.
    * Extracted the longitude & latitude of the cities.
    * Directional layer map between the four cities & travel map is created (saved the map as WeatherPy_travel_map.PNG).
![image](Vacation_Itinerary/WeatherPy_travel_map.PNG)    
    * A marker layer map with a pop-up marker( hotel name, city, country , weather description & temperature) for the cities on the itinerary is created ( saved the map as WeatherPy_travel_map_marker.PNG).
![image](Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)    
