# python-api-challenge

WeatherPy
Script - perform weather checks and to visualize weather in 500+ unique cities around the world based on latitude and longitude coordinates using Openweather API. 
Scatterplots to visualize relationship between latitude and other variables such as humidity, maximum temperature, cloudiness and wind speed. 
Linear regression to observe trends in northern vs southern hemisphere cities in comparing latititude with humidity, and other variables. 
* Include a print log of each city as it's being processed with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.


vacationpy 
Use jupyter-gmaps and the Google Places API to use weather data to plan vacation
* Create a heat map that displays the humidity for every city from the part I of the homework.

  ![heatmap](Images/heatmap.png)

* Narrow down the DataFrame to find your ideal weather condition. For example:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

  * **Note:** Feel free to adjust to your specifications but be sure to limit the number of rows returned by your API requests to a reasonable number.

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.