# Python API Homework - What's the Weather Like?

This is a two part project with the first part using an API request, and the second part using a Python script to visualize the weather data of 500+ citiees across the world of varying distance from the equator, and sourced under the WeatherPy folder. Using Python and the OpenWeaterMap API, I created a representative model of weather across world cities. The data analyzed and displayed on WeatherPy jupyter notebook, and the results are exported in a CSV format cities.csv, and the regression plots in the output folder.

The other project VacationPy is used the output data from the previous WeatherPy csv, aand investigate the data to plan for future vacations and to select hotels. For this part of the analysis gmaps and Google Places were used and the results were displayed in the VacationPy notebook.  The analysis covers humitity heatmap in the cities that sourced from the weather data, and spot the hotels on top of the humidity heatmap. The images of the heatmap and the hotel heatmap are located in the output folder.

# API Keys

To run locally the python files for both WeatherPy and VacationPy projects you need to obtain API keys.  For part one, you will need to obtain an API key is located in the OpenWeatherMap API key. After you have opened the OpenWeatherMap API key in the WeatherPy folder you will find the config.py file. 

api_keys ="API_KEY_HERE"

For part two, you will need to optain a Google API key from the Google Cloud Platform at https://cloud.google.com and enable the Placess API. After you have the Google API key from config.py file add the API key there.

g_key ="API_KEY_HERE"

# Observable Trends

The findings of these analysis showed that there is a higher temperature for cities that found near the equator, however, when we go farther from the equator towards the north the temperature decreases. On the other hand, even though the temperature decreases as we go south, it decreases at a much lower rate compared to the north. The regression analysis and plot also showed that there is a strong negative correlation between temperature and latitude in the northern hemisphere as well as the southern.

The findings from the analysis of the relationship between wind speed(mph), and latitude showed that the cities closest to the equator had the lowest wind speed.  in theThe regression analysis also showed that there is a low positive correlation between Wind Speed and Latitude in the Northern Hemisphere cities.


