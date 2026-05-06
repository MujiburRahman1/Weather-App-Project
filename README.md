# Weather Dashboard App

A simple weather dashboard built with HTML, CSS, and vanilla JavaScript.  
It shows current weather and a 5-day forecast using the OpenWeatherMap API.

## Features

- Search weather by city name
- Get weather using current location (Geolocation API)
- Displays:
  - Current temperature, wind speed, humidity
  - 5-day forecast cards
- Responsive layout for desktop and mobile

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- OpenWeatherMap APIs:
  - Geocoding API
  - 5 Day / 3 Hour Forecast API

## Project Structure

- `index.html` - app layout and UI structure
- `style.css` - app styling and responsive design
- `script.js` - API calls, weather data processing, and DOM updates

## Setup Instructions

1. Clone or download this project.
2. Open the folder in your code editor.
3. Open `script.js` and replace `API_KEY` with your own OpenWeatherMap API key.
4. Run the app by opening `index.html` in your browser.

## Get OpenWeatherMap API Key

1. Go to [OpenWeatherMap](https://openweathermap.org/).
2. Create an account / sign in.
3. Generate an API key from your account dashboard.
4. Paste it into `script.js`:

```js
const API_KEY = "YOUR_API_KEY_HERE";
```

## Notes

- The app uses temperature data from OpenWeatherMap in Kelvin and converts it to Celsius.
- Location access is required for the "Use Current Location" button.
- If location permission is denied, the app shows an error alert.

## Future Improvements

- Add loading state while fetching data
- Better error messages in UI (instead of alerts)
- Add unit toggle (Celsius/Fahrenheit)
- Hide API key using backend proxy or environment-based setup

## Credits

- UI idea inspired by CodingNepal tutorial format
- Built by project team members listed in the app footer
