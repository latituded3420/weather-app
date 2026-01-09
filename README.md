# Weather App

A real-time weather application that allows users to search weather information by city name.

## Features

- Search weather by city name
- Display current temperature in Celsius
- Show weather conditions (sunny, rainy, cloudy, etc.)
- Display humidity percentage
- Display wind speed
- Beautiful gradient UI with smooth animations
- Responsive design
- Real-time weather data from OpenWeather API

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **API**: OpenWeather API
- **Tools**: VS Code, Git, GitHub

## Project Structure

```
weather-app/
├── index.html       # Main HTML file
├── style.css        # CSS styling
├── script.js        # JavaScript functionality
└── README.md        # This file
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/latituded3420/weather-app.git
   cd weather-app
   ```

2. Open `index.html` in your web browser

3. Enter a city name in the input field

4. Click "Get My Weather" button to fetch weather data

5. View the weather information displayed below

## API Setup

This project uses the OpenWeather API. The API key is already configured in `script.js`.

To use your own API key:
1. Visit [OpenWeather](https://openweathermap.org/api)
2. Sign up and get a free API key
3. Replace the API key in `script.js`:
   ```javascript
   const apiKey = 'your_api_key_here';
   ```

## What I Learned

- Asynchronous JavaScript (async/await)
- Fetching data from external APIs
- DOM manipulation
- CSS animations and transitions
- Error handling
- Form validation

## Future Enhancements

- Add weather forecast (5-day, 10-day)
- Add geolocation support
- Save favorite cities
- Dark/Light theme toggle
- Mobile app version
- Weather alerts

## Screenshots


### Main Interface
Weather app displays current temperature, weather conditions, humidity, and wind speed with a beautiful gradient background.

### Features in Action
- Real-time data fetching from OpenWeather API
- Smooth fade animations on result display
- Responsive design that works on mobile and desktop
- Error handling for invalid city names

## Author

Salim (BCA Student) 
for lerning api

## License

This project is open source.
