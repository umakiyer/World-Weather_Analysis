# World-Weather_Analysis
## Purpose of the repository :
1. Weather Database :

   * Create 500 latitude & longitudes using random number function
   * Using Citipy , created list of the citites from logitude & latitude 
   * Using openweathermap , created city dataframe of for the cities foung in open weather map. 
   * Saved the dataframe to a csv file (WeatherPy_Database)

2.  Database for Hotel for the cities database

    * Customers are prompted to enter their preference of low & high temperature range for the vacation.
    * Created new dataframe based on the minimum & maximum temperature. Dropped the empty rows.
    * Hotel name is retrived (from GMAPS) aand added to the dataframe & dropped the rows that didn't have rows.
    * The dataframe is saved as CSV file( WeatherPy_vacation).
    * A marker layer map with pop-up markers for the cities in the vacation DataFrame is created.
    * Each marker has the hotel name, city, country, weather description & temperature.
    * Saved the map with marker as Weather_vacation_map.PNG.

3. Create Travel Itinerary Map

    * Created four dataframe for cities.
    * extracted teh langitude & latitude of the cities.
    * Directional layer map between the four cities & travel map is created ( saved as WeatherPy_travel_map.PNG)
    * A marker layer map with a pop-up marker( hotel name, city, country , weather description & temperture) for the cities on the itinerary is created ( saved the map as WeatherPy_travel_map_marker.PNG)
