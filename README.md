# Python API Project - What's the Weather Like?

## Part I - WeatherPy

I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), to create a representative model of weather across world cities.

I created a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot I added a sentence explaining what the code is and analyzing.

I also ran linear regression on each relationship, only this time I separated them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots I explained what the linear regression is modeling.

### Part II - VacationPy

For this project, I used my skills in working with weather data to plan future vacations. For this part of the project, I used jupyter-gmaps and the Google Places API.

* I created a heat map that displays the humidity for every city from the part I of the homework.

  ![heatmap](Images/heatmap.png)

* I narrowed down the DataFrame to find my ideal weather condition. 

* I used Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.

* I plotted the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

  ![hotel map](Images/hotel_map.png)

