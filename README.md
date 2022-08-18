Part 1: WeatherPy

In this section,created a Python script to visualize the weather of 500+ cities of varying distance from the equator. To do so, you'll use a simple Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities.

created a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

final notebook:
Randomly select at least 500 unique (non-repeated) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed, with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


Part 2: VacationPy

Created a heat map that displays the humidity for every city from Part 1, as in the following image:

Narrow down the DataFrame to following:
A max temperature lower than 295 degrees but higher than 290.
Wind speed less than 10 mph.
Zero cloudiness.
Drop any rows that don't satisfy all three conditions.


Used Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.

Plot the hotels on top of the humidity heatmap, with each pin containing the Hotel Name, City, and Country.
