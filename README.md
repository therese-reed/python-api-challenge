# python-api-challenge
python-api-challenge
WeatherPy
Background Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using CityPy, a simple Python library, and the OpenWeatherMap API.
The visualizations includce a series of scatter plots to showcase the following relationships:
Temperature (F) vs. Latitude Humidity (%) vs. Latitude Cloudiness (%) vs. Latitude Wind Speed (mph) vs. Latitude
The script accomplishes the following:
Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.
Performs a weather check on each of the cities using a series of successive API calls.
Includes a print log of each city as it's being processed with the city city name.
Saves both a CSV of all data retrieved and png images for each scatter plot.

**Observable Trends**
Temperature peaks at around 20 degrees latitude, not exactly at the equatorial line. This may be due to the Earth's tilt in the axis known as obliquity.
Cloudiness and humidity do not show a strong correlation to latitude. The visualizations below show a great variety of values at similar latitudes.
Wind speed appears to slightly increase as we move away from the equator. We would need to go beyond the ranged examined to make a definitive conclusion.
Part II - VacationPy
Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places Create a heat map that displays the humidity for every city from Part I.
 
•	Narrow down the DataFrame to find your ideal weather condition. For example:
o	A max temperature lower than 80 degrees but higher than 70.
o	Wind speed less than 10 mph.
o	Zero cloudiness.
o	Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
Rows numbers  have been limited.
•Google Places API used to find the first hotel for each city located within 5000 meters of your coordinates.
•	Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
Methods used
•	analysis using a Jupyter notebook.
•Matplotlib or Pandas plotting libraries.
•	For Part I, you must include a written description of three observable trends based on the data.
•	 screenshot of the heatmap you create and include it in your submission.
•	plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.
•	For max intensity in the heat map, try setting it to the highest humidity 


