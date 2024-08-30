# Weather App

This is a simple weather application that allows users to search for weather forecasts by city or use their GPS location to get the current weather and a 5-day forecast. The app also displays previous searches done by other users.

## Features

- **Search by City**: Enter a city name to get the current weather and a 5-day forecast.
- **GPS Location**: Use your device's GPS to get the weather for your current location.
- **Previous Searches**: View a list of previous searches done by other users.
- **Responsive Design**: The app is designed to be responsive and works well on both desktop and mobile devices.

## Technologies Used

- **HTML**: For the structure of the app.
- **CSS**: For styling the app.
- **JavaScript**: For the app's functionality.
- **Firebase**: For storing and retrieving previous searches.
- **AccuWeather API**: For fetching weather data.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. Open `index.html` in your browser to view the app.

## Configuration

To use this app, you need to set up a Firebase project and get an API key from AccuWeather. Replace the placeholders in the code with your own Firebase and AccuWeather API keys.

```javascript
const firebaseConfig = {
    apiKey: "YOUR_FIREBASE_API_KEY",
    authDomain: "YOUR_FIREBASE_AUTH_DOMAIN",
    projectId: "YOUR_FIREBASE_PROJECT_ID",
    storageBucket: "YOUR_FIREBASE_STORAGE_BUCKET",
    messagingSenderId: "YOUR_FIREBASE_MESSAGING_SENDER_ID",
    appId: "YOUR_FIREBASE_APP_ID",
    measurementId: "YOUR_FIREBASE_MEASUREMENT_ID"
};

const YOUR_API_KEY = 'YOUR_ACCUWEATHER_API_KEY';

## Usage

Enter a city name in the search box and press Enter to get the weather forecast.
Click the “Use GPS Location” button to get the weather for your current location.
View the weather forecast and previous searches done by other users.

## License
Unknown license.