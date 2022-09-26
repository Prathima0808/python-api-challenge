# Observations:

Southern Hemisphere climates tend to be slightly milder than those at similar latitudes in the Northern Hemisphere. This is because the Southern Hemisphere has significantly more ocean and much less land; water heats up and cools down more slowly than land.

"Highest temperature is found at 0 latitude and as the latidude increases or decreases, temperature drops. This happens as equatorial region receives sunlight straight with less or no angle due to curvature shape of earth.\n",

"Latitude doesn't have a strong iinfluence on wind speed. The speed of the wind is controlled by the strength of the air pressure gradient, the stronger the pressure gradient the higher the wind speed. "




#  Part 1: WeatherPy

created a Python script to visualise the weather of over 500 cities of varying distances from the equatorlibrary 

 created  a series of scatter plots to showcase the following relationships:

-> Temperature (C) vs. Latitude

Humidity (%) vs. Latitude

Cloudiness (%) vs. Latitude

Wind Speed (m/s) vs. Latitude

After each plot, analysing.

The second requirement is to compute the linear regression for each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere: Temperature (C) vs. Latitude

Southern Hemisphere: Temperature (C) vs. Latitude

Northern Hemisphere: Humidity (%) vs. Latitude

Southern Hemisphere: Humidity (%) vs. Latitude

Northern Hemisphere: Cloudiness (%) vs. Latitude

Southern Hemisphere: Cloudiness (%) vs. Latitude

Northern Hemisphere: Wind Speed (m/s) vs. Latitude

Southern Hemisphere: Wind Speed (m/s) vs. Latitude

After each pair of plots, explain what the linear regression is modelling. Describe any relationships that you notice and any other findings you may uncover.

Your final notebook must meet the following requirements:

Randomly select at least 500 unique (not repeated) cities based on latitude and longitude.

Perform a weather check on each of the cities by using a series of successive API calls.

Include a print log of each city as it's being processed, with the city number and city name.

Save a CSV of all retrieved data and a PNG image for each scatter plot.

# Part 2: VacationPy

Now, use your weather data skills to plan future vacations. Use Jupyter gmaps and the Google Places API s.

*Create a heat map that displays the humidity for every city from the part I of the project.

heatmap

*Narrow down the DataFrame to find my ideal weather condition. For example:

     A max temperature lower than 27 degrees but higher than 21.

     Wind speed less than 4.5 m/s.


Zero cloudiness.

Drop any rows that don't contain all three conditions.

# To run the code:

--> Jupytor Python Notebook or Visual Studio Code. (Develop Code)

--> Install citypy in your python environment (https://pypi.python.org/pypi/citipy)

-->Save OpenWeatherMap API Key (https://openweathermap.org/) as 'weather_api_key'

-->Google API Key (https://console.developers.google.com/getting-started) as 'g_key'

-->Create API Keys and store it in the 'api_keys.py' file before running the Jupyter notebooks.


