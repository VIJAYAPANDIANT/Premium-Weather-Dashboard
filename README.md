# 🌦️ Weather App JS

A sleek and responsive weather information application built with vanilla JavaScript, HTML, and CSS. This app provides real-time weather data for any city name entered by the user.

## 🚀 Features
- **City Search**: Enter any city name to fetch current weather details.
- **Real-time Data**: Fetches data from the Open-Meteo API.
- **Dynamic UI**: Displays temperature, humidity, weather description, and intuitive icons based on conditions.
- **Error Handling**: gracefully handles non-existent cities or network errors.

## 🛠️ Technology Stack
- **HTML5**: For structure and layout.
- **Vanilla CSS**: Styled with modern HSL colors, gradients, and a clean, responsive card-based design.
- **JavaScript (ES6+)**: Handles geocoding, weather API calls, and DOM manipulation.

## 🌐 API Reference
This project utilizes the following APIs from [Open-Meteo](https://open-meteo.com/):
1. **[Open-Meteo Geocoding API](https://geocoding-api.open-meteo.com/v1/search)**: Converts city names into precise latitude and longitude coordinates.
2. **[Open-Meteo Forecast API](https://api.open-meteo.com/v1/forecast)**: Retrieves current weather data using the coordinates obtained from the Geocoding API.

## 📂 File Structure
- `index.html`: The main entry point containing the entry form and results card.
- `style.css`: Modern styling with responsive design and clean aesthetic.
- `main.js`: Main application logic, including API orchestration and UI updates.

## 💻 How to Use
1. Clone the repository or download the source files.
2. Open `index.html` in your favorite web browser.
3. Enter a city name (e.g., "Paris", "New York") in the search field.
4. Click **Get Weather** to see the magic happen!

---

Developed with ❤️ using Vanilla Web Technologies.
