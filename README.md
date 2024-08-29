# JavaScript Weather App

This repository contains a simple weather application built using JavaScript. The app fetches and displays the current weather for a specified location using the OpenWeatherMap API.

## Features

- **Current Weather Data**: Displays the current temperature, weather conditions, humidity, and wind speed.
- **Location-Based Search**: Enter the name of a city to get the current weather for that location.
- **Responsive Design**: The app is designed to work on both desktop and mobile devices.

## Getting Started

### Prerequisites

To run the app, you'll need a web browser that supports HTML5, CSS3, and JavaScript.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/joseph-krohn/javascript-weather_app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd javascript-weather_app
    ```

3. Open the `index.html` file in your web browser:
    ```bash
    open index.html
    ```

### Usage

1. Open the app in your web browser.
2. Enter the name of a city in the search bar and click the "Search" button.
3. The current weather for the specified location will be displayed.

### API Configuration

To use the app, you'll need to have an API key from [OpenWeatherMap](https://openweathermap.org/).

1. Sign up for a free API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Replace the placeholder API key in the `script.js` file with your actual API key:
    ```javascript
    const apiKey = 'YOUR_API_KEY';
    ```

## Project Structure

- `index.html`: The main HTML file that contains the structure of the app.
- `style.css`: The CSS file that defines the styling and layout of the app.
- `script.js`: The JavaScript file that contains the logic for fetching and displaying weather data.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository and submit a pull request with your improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to retrieve weather data.
