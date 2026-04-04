<h1 align="center">🌦️ Weather App JS</h1>

<h3 align="center">A sleek, responsive, and intuitive weather information application</h3>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

<br>

This application provides real-time weather data for any specified city using the Open-Meteo API, built entirely with vanilla JavaScript, HTML, and CSS.

## 🚀 Features

- **City Search**: Query current weather details for any global city.
- **Real-time Data**: Fetches accurate and up-to-date data from the Open-Meteo API.
- **Dynamic UI**: Responsive interface that dynamically displays temperature, humidity, weather description, and condition-specific icons.
- **Error Handling**: Gracefully manages invalid city queries and network interruptions.

## 🛠️ Technology Stack

- **HTML5**: For semantic structure and layout.
- **CSS3**: Employs modern HSL colors, gradients, and a clean, responsive card-based design for an enhanced user experience without relying on external frameworks.
- **JavaScript (ES6+)**: Handles asynchronous geocoding, weather API integration, and efficient DOM manipulation.

## 🌐 API Integration

This project relies on robust APIs from [Open-Meteo](https://open-meteo.com/):

1. **[Open-Meteo Geocoding API](https://geocoding-api.open-meteo.com/v1/search)**: Converts user-input city names into precise latitude and longitude coordinates.
2. **[Open-Meteo Forecast API](https://api.open-meteo.com/v1/forecast)**: Retrieves comprehensive current weather data utilizing the coordinates obtained from the Geocoding API.

## 📂 Project Structure

```text
├── index.html   # Main application entry point featuring the search form and weather display card
├── style.css    # Modern styling implementation ensuring a responsive and clean aesthetic
└── main.js      # Core application logic, API orchestration, and dynamic UI rendering
```

## 💻 Getting Started

Follow these instructions to run the project locally.

### Prerequisites

A modern web browser (e.g., Chrome, Firefox, Safari, Edge).

### Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VIJAYAPANDIANT/Weather-App.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd Weather-App
   ```
3. **Run the application:**
   - Open `index.html` directly in your preferred web browser.
   - Alternatively, serve it using a local development server (e.g., Live Server extension in VS Code).

### Usage Example

1. Enter a valid city name (e.g., "London", "Tokyo", "New York") into the designated search field.
2. Click the **Get Weather** button.
3. View the instantly updated weather conditions presented on the dynamic interface.

---

Developed with ❤️ using Vanilla Web Technologies.
