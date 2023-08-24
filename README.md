# Weather App

![image](https://github.com/SreayaaV/Interactive-Weather-App/assets/142159625/2af7a286-36d4-4778-bc30-75541f3bccf5)


The Weather App is a simple web application that provides real-time weather information for a user's location as well as a 5-day weather forecast. It uses the OpenWeatherMap API to fetch weather data and displays it in an intuitive and user-friendly interface.

## Features

- Current weather information, including temperature, humidity, pressure, wind speed, sunrise, and sunset times.
- Real-time updating of the current time and date.
- Display of weather forecast for the next 5 days, including day and night temperatures.
- Responsive design that works well on both desktop and mobile devices.
- Automatic detection of the user's location using geolocation.

## Technologies Used

- HTML, CSS for structuring and styling the user interface.
- JavaScript for fetching data from the OpenWeatherMap API and dynamically updating the content.
- [Moment.js](https://momentjs.com/) library for time and date formatting.
- OpenWeatherMap API for retrieving weather data based on the user's location.

## Usage

1. Open the `index.html` file in a web browser.
2. The app will prompt you to allow location access; grant the permission.
3. The app will display the current weather information and the 5-day forecast for your location.

## API Key

To use this app, you'll need to sign up on the [OpenWeatherMap](https://openweathermap.org/) website and get an API key. Replace `'YOUR_API_KEY'` in the `script.js` file with your actual API key.

```javascript
const API_KEY = 'YOUR_API_KEY';
```

## Credits

- Weather icons provided by [OpenWeatherMap](https://openweathermap.org/weather-conditions).
- Background image by [Unsplash](https://unsplash.com/).
