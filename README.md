# Weather App

This is a simple web application that displays the current weather information for a given city.

## Features

*   Displays the current temperature in Celsius.
*   Displays the wind speed, humidity, and visibility.
*   Displays a weather icon and a brief description of the weather conditions.

## How to Run

1.  **Get an API Key:**
    *   Go to the [OpenWeatherMap website](https://openweathermap.org/api) and sign up for a free account.
    *   Navigate to the "API keys" section and get your API key.

2.  **Configure the project:**
    *   Open `script.js`.
    *   Update the `apiKey` variable with your OpenWeatherMap API key.

3.  **Run the application:**
    *   Open `index.html` in your web browser.

## How it Works

The application uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch the current weather data for a given city. The user enters a city name in the input field, and the application makes a request to the API. The API returns a JSON object with the weather data, which is then used to update the UI.
