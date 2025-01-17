Weather App

The Weather App is a responsive web application designed to provide real-time weather updates and forecasts for cities worldwide. By utilizing the OpenWeatherMap API, the app delivers detailed weather information including temperature, humidity, wind speed, and a 5-day forecast.

Features

City Search: Enter any city name to get instant weather details.

Real-Time Data: Current weather conditions including temperature, humidity, and wind speed.

Dynamic Weather Icons: Icons change dynamically to reflect the current weather.

5-Day Forecast: Scrollable forecast showing weather snapshots for the next five days.

Responsive Design: Works seamlessly across various devices and screen sizes.

Technologies Used

Frontend

HTML5: Structuring and presenting the content.

CSS3: Styling, animations, and responsive design.

JavaScript (ES6): Logic and API interaction.

APIs

OpenWeatherMap API: Provides weather and forecast data.

Setup and Installation

Follow these steps to run the project locally:

Clone the repository:

git clone https://github.com/fabiojsdev/weather-app.git
cd weather-app

Replace the API key:

Open the app.js file and replace the placeholder API key (c538c7a6d4db6e6aaceab03e243db1be) with your own API key from OpenWeatherMap.

Open the project in your browser:

Open the index.html file in any modern browser to run the app.

File Structure

weather-app/
├── assets/
│   ├── bg.jpg             # Background image for the app
│   ├── message/
│   │   ├── search-city.png
│   │   ├── not-found.png
│   ├── weather/
│       ├── clear.svg
│       ├── clouds.svg
│       ├── drizzle.svg
│       ├── rain.svg
│       ├── snow.svg
│       ├── thunderstorm.svg
│       ├── atmosphere.svg
├── index.html             # Main HTML file
├── style.css              # CSS file for styling
├── app.js                 # JavaScript file for app logic

How It Works

Search Functionality:

Users can input a city name and press Enter or click the search icon to retrieve weather data.

Weather Display:

Displays current weather conditions when a valid city is searched.

Shows an error message if the city is not found.

Forecast Display:

Fetches a 5-day forecast, displaying one weather snapshot per day at 12:00 PM.

Dynamic Icons:

Weather icons update based on the retrieved weather condition data.

Screenshots

Home Page: Initial display before a search.

Search Results: Weather information displayed after a successful search.

Not Found: Error message displayed when the city is not found.

Future Enhancements

Geolocation Support: Automatically detect and display weather for the user's current location.

Additional Details: Include sunrise/sunset times, atmospheric pressure, and UV index.

Improved Responsiveness: Enhance design for tablets and larger screens.

License

This project is open-source and licensed under the MIT License.

Contributing

Contributions are welcome! If you want to improve this project, feel free to open an issue or submit a pull request.

Author: Fabio Marinho - Credits for CodeArry
GitHub Repository: Weather_App
