# Weather App

## Description
This Weather Dashboard is a responsive web application that allows users to fetch and display real-time weather data based on their current location or a user-inputted location. By leveraging the OpenWeatherMap API, the application provides detailed information, including current weather conditions, temperature, humidity, wind speed, and more.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Code Structure](#code-structure)
- [Installation](#installation)
- [License](#license)

## Features
- Search for weather information by city name.
- Display current temperature, weather description, and an icon representing the weather.
- Show hourly weather forecast for the next 24 hours.

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## How to Use
1. Enter a city name in the input field.
2. Click the "Get Weather" button.
3. The app will fetch and display the current weather and hourly forecast for the entered city.

## Code Structure

### HTML (`index.html`)
The HTML file provides the structure of the Weather App, which includes:
- A title for the app.
- An input field for entering the city name.
- A button to trigger the weather data fetch.
- Div elements to display the temperature, weather information, and hourly forecast.
- An image element to show the weather icon.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="app.css">
</head>
<body>
    <div class="container">
        <h1>Weather App</h1>
        <input type="text" id="city" placeholder="Enter city name" />
        <button onclick="getWeather()">Get Weather</button>
        <div id="temp-div"></div>
        <div id="weather-info"></div>
        <img id="weather-icon" src="" alt="" style="display:none;">
        <div id="hourly-forecast"></div>
    </div>
    <script src="jss.js"></script>
</body>
</html>
git clone https://github.com/yourusername/weather-app.git
cd weather-app

