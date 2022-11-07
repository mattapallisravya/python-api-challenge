# python-api-challenge

Part 1: WeatherPy

- Created a Python script to visualize the weather of over 500 cities of varying distances from the equator. Used the citipy Python libraryLinks and the OpenWeatherMap to create a representative model of weather across cities.

- Generated random geographic coordinates and the nearest city to each latitude and longitude combination is provided

- Created a dataframe from the list of the cities containing columns such as max temperature, date, lat, long and country.

- Created series of scatter plots to show the relationship between weather variables and latitude.
      
      - Latitude vs. Temperature

      - Latitude vs. Humidity

      - Latitude vs. Cloudiness

      - Latitude vs. Wind Speed
 
- Separated plots for southern hemisphere and northen hemisphere and calculated regression equation plotted line of regression.

        - Northern Hemisphere: Temperature vs. Latitude

        - Southern Hemisphere: Temperature vs. Latitude

        - Northern Hemisphere: Humidity vs. Latitude

        - Southern Hemisphere: Humidity vs. Latitude

        - Northern Hemisphere: Cloudiness vs. Latitude

        - Southern Hemisphere: Cloudiness vs. Latitude

        - Northern Hemisphere: Wind Speed vs. Latitude

        - Southern Hemisphere: Wind Speed vs. Latitude
        
Part 2: VacationPy

- Created a map that displays a point for every city in the city_data_df DataFrame. The size of the point is relative to the humidity in each city.

- narrowed down the number cities based on the ideal conditions such as max temerature less tha 27, greater than 23 and windspeed less than 4.5 m/s, Zero cloudiness. 

- used the Geoapify API to fetch the nearest hotels to the city with in range of 10000m and gmaps to create map visualizations.



