# Weather App

A simple web-based weather application that allows users to check the current weather conditions for any city using the OpenWeatherMap API.

## Features

- Search for weather by city name
- Display temperature in Celsius
- Show weather description, humidity, and wind speed
- Dynamic weather icons based on current conditions
- Error handling for locations not found

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- OpenWeatherMap API

## Installation

1. Clone the repository:
   ```
   git clone <your-repository-url>
   cd WeatherApp
   ```

2. Open `index.html` in your preferred web browser.

## Usage

1. Enter the name of a city in the search input field.
2. Click the search button (magnifying glass icon).
3. The app will display the current weather information for that location.

## API Key

The application uses a free API key from OpenWeatherMap, which is included in `app.js` for demonstration. For production or heavy usage, please obtain your own API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the `api_key` variable in `app.js`.

## Project Structure

- `index.html`: Main HTML file
- `style.css`: Stylesheet for the application
- `app.js`: JavaScript logic for fetching and displaying weather data
- `assets/`: Folder containing weather icons and error images

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
