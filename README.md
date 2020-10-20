# Python-API-challenge

**These files uses API requests to obtain data from external databases such as OpenWeather and Google. Subsequently, pandas, matplotlib, linregress, and gmaps were utilized to create data visualization for further discussion and analysis.**

**WeatherPy: weather checks are performed in 500+ unique random cities with various weather conditions per city**  
  * Script includes 
    * Generate Openweather API calls 500+ randomly generated cities around the world based on latitude and longitude coordinates
    * Pull weather conditions from API calls and append to database such as maximum temperature, humidity, wind speed, and cloudiness 
    * Handle exceptions using try and except functions 
    * Export data and save plots to external files 
    * Create scatter plots to visualize relationship between latitude and other weather conditions listed previously 
    * Construct function to perform linear regressions and plots for trend analysis 

**VacationPy: using prior data from WeatherPy, cities are narrowed down by preferred weather criteria and visualized with google heat maps and hotel pins** 
  * Script includes
    * Create heat map for humidity for every city generated in WeatherPy
    * Narrow dataframe by preferred weather criteria 
    * Search for nearby hotels with specific parameters using Google API for preferred locations
    * Add additional layer of hotel pins to the heat map for preferred locations only 
