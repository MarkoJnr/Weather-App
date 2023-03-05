## CLI Weather App
This is a command-line interface (CLI) application that fetches weather and temperature information for a city using OpenWeather's API. The app uses Python 3 and some standard libraries like argparse and json.

## Installation
Clone or download the project from GitHub.

Create an account with OpenWeather and obtain an API key.

Create a secrets.ini file in the root of the project and add your OpenWeather API key in the following format:

[openweather]
api_key=<YOUR-OPENWEATHER-API-KEY>
Install the required packages by running the following command in your terminal:

pip install -r requirements.txt

## How it works

The app takes a city name as input and makes an API request to OpenWeather's weather API to retrieve the current weather and temperature information for that city. The app then displays the information in the terminal using colors to distinguish between different weather conditions.

## How to use it

To use the app, navigate to the project directory in your terminal and run the following command:

python weather.py <city name>

Replace <city name> with the name of the city you want to retrieve weather information for. 

You can also use the optional flag -i or --imperial to display temperature information in Fahrenheit instead of Celsius.

Example usage:

python weather.py London -i

The optional -i flag can be used to display temperature in London in Fahrenheit instead of Celsius.

## Contributing
This app was created as a beginner's project to learn Python and API usage with the help of RealPython.com. Contributions and feedback are welcome!



