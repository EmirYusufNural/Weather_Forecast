# Weather_Forecast
# Weather App

This is a simple Python script that uses the OpenWeatherMap API to get the current weather and temperature of any city in the world. It takes the city name as user input and prints the weather information on the screen.

## Requirements

To run this script, you need to have Python 3 installed on your system. You also need to install the requests library using pip:

`pip install requests`

You also need to get a free API key from OpenWeatherMap by signing up here: https://openweathermap.org/api

## Usage

To run the script, open a terminal and navigate to the folder where you saved the file. Then type:

`python weather_app.py`

You will be prompted to enter a city name. For example:

`Enter city: London`

The script will then make a request to the OpenWeatherMap API and display the weather and temperature of the city. For example:

`The weather in London is: Clouds`
`The temperature in London is: 64ºF`

If you enter an invalid or unknown city name, the script will print:

`No City Found`

## Improvements

There are some possible ways to improve this script, such as:

- Adding error handling for network issues or invalid API key
- Adding a graphical user interface (GUI) using Tkinter or PyQt
- Adding more weather information such as humidity, wind speed, sunrise and sunset times
- Adding a feature to convert between Fahrenheit and Celsius units
- Adding a feature to save the weather data to a file or database
