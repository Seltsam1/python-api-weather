# python-api-weather
Analysis of weather and temperature using APIs


## Getting Started

All analyses are contained in the jupyter notebook files:
- WeatherPy.ipynb will generate a csv and scatter plots
- VacationPy.ipynb will use the csv previously generated and create maps

An API key is required for these. Include them in a seperate apy_keys.py file in order to run the code.


## Features

#### WeatherPy.ipynb:

- Code will generate a list of cities within a specific range for latitude (-90, 90) and longitude (-180, 180) coordinates. Using the Open Weather Map API, various metrics including temperature and humidity will be gathered and stored in a dataframe using sets of 50 records based on the lsit of cities. This is exported as a csv file to be used by the additional analyses in the accompanying juputer notebook (VacationPy).

- The final portion includes a collection of scatter plots comparing latitude of cities with different weather metrics. Lastly, regressions are performed to determine if there is any causal relationship between latitude and weather.

#### VacationPy.ipynb:

- Uses the csv dataset produced from the WeatherPy code to search for infomation on the Google Maps API.

- Includes a heat map using latitude and longitute values as weights

- Includes a map with markers showing Hotel name, city, and country for a subset of areas that were within ideal weather conditions. 


## Licensing by:

The code in this project is licensed under MIT license.
