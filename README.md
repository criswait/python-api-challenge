# python-api-challenge

# Project 1: Vacation Planning Using Weather Data and Geoapify API

## Project Description
This project aims to help plan future vacations by analyzing weather data and using Geoapify API to find nearby hotels. You will use the Python library hvplot to create interactive maps displaying cities with key weather attributes like humidity, temperature, and wind speed. The Geoapify Places API is utilized to find hotels near the cities identified in the dataset.

## Key Features
Data Filtering: The dataset is filtered to select cities based on temperature and humidity criteria.
Interactive Map: The map shows points for each city, with point sizes representing humidity levels. Hovering over the points provides additional information such as the city name, hotel name, and weather details.
Hotel Search: Uses the Geoapify API to find the first hotel within 10,000 meters of the city’s coordinates and adds the hotel name to the dataset.

## Files
output_data/cities.csv: stored jpeg of plot created
api_keys.py: Stores the API key for Geoapify.
WeatherPy.ipynb: Jupyter notebook where the analysis is performed.


# Project 2: Mapping Cities Based on Humidity and Hotel Information

## Project Description
This project maps global cities using weather data and provides a visualization based on humidity levels. Each city is plotted on an interactive map with distinct colors for each city, and information about nearby hotels is retrieved using the Geoapify API.

## Key Features
Interactive City Map: Cities are plotted on an interactive map with the point size corresponding to humidity levels.
Unique City Colors: Each city is represented with a unique color, making it easy to differentiate cities on the map.
Hover Information: Additional information such as city name, country, humidity, and nearby hotel name is displayed when hovering over city points.
Hotel Search: The Geoapify Places API is used to find the first hotel within 10,000 meters of each city's coordinates.

## Files
output_data/cities.csv: The CSV file with city weather data.
api_keys.py: Stores your API key for accessing Geoapify services.
VacationPy.ipynb: Jupyter notebook where the map and hotel search are executed.
