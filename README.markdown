# Weather AI Web App

This Weather AI Web App provides real-time weather information and a 5-day forecast for any city or the user's current location. It features interactive charts, a filterable forecast table, and a chatbot powered by Google Gemini API for weather-related queries.

---

## 🌟 Features

### Main Features

- **City Search**: Enter a city name to retrieve its weather details.
- **Location-Based Weather**: Fetch weather data for the user's current location using geolocation.
- **Temperature Unit Toggle**: Switch between Celsius and Fahrenheit.
- **Weather Forecast Charts**:
  - **Vertical Bar Chart**: Displays temperature trends over the next 5 days.
  - **Doughnut Chart**: Visualizes weather conditions for the next 5 days.
  - **Line Chart**: Shows temperature trends as a line graph.
- **Filterable Forecast Table**: View detailed 5-day forecasts with options to sort by temperature, filter rainy days, or highlight the warmest day.
- **Loading Spinner**: Displays a loading animation during data fetching.
- **Responsive Design**: Optimized for all screen sizes using Tailwind CSS.
- **Interactive Chatbot**: Query weather details and temperature statistics via a built-in chatbot.

🔹 **Technologies Used**:

- **Frontend**: HTML5, CSS3 (Tailwind CSS), JavaScript (ES6+)
- **APIs**:
  - OpenWeather API for real-time weather and forecast data
  - Google Gemini API for chatbot functionality
- **Visualization**: Chart.js for interactive charts

---

## 🛠️ Installation Instructions

### Prerequisites

🔹 **OpenWeather API Key**: Sign up at OpenWeather to obtain an API key.\
🔹 **Google Gemini API Key**: Register at Google AI Studio to get an API key.

### Setup

- **Clone the Repository**:

  ```bash
  git clone <your-repo-url>
  ```

- **Configure API Keys**:

  - Open `index.html` and `table.html`.
  - Replace `YOUR_API_KEY` placeholders in the JavaScript sections with your OpenWeather and Google Gemini API keys.

- **Run Locally**:

  - **Option 1: VSCode Live Server**:
    1. Install the Live Server extension in Visual Studio Code.
    2. Right-click `index.html` and select "Open with Live Server".
  - **Option 2: Manual Deployment via Netlify**:
    1. Log in or create an account on Netlify.
    2. Add a new site by uploading the project folder.
    3. Copy the generated site URL from Site Settings.
    4. Access the live app by pasting the URL in a browser.

### Access the App

- **Dashboard**: Open `index.html` to view weather details and forecast charts.
- **Forecast Table**: Open `table.html` for a filterable 5-day forecast table.

---

## 📖 Usage

### Dashboard (`index.html`)

- **Search Weather**: Enter a city name and click "Get Weather" to view current weather and 5-day forecast.
- **Toggle Units**: Select Celsius or Fahrenheit from the dropdown.
- **Use Location**: Click "Use My Location" to fetch weather for your current location.
- **View Charts**: Explore bar, doughnut, and line charts for the 5-day forecast.

### Forecast Table (`table.html`)

- **Search Weather**: Enter a city name and click "Get Weather".
- **Toggle Units**: Choose Celsius or Fahrenheit.
- **Filter Options**:
  - Sort temperatures (ascending/descending).
  - Show only rainy days.
  - Highlight the day with the highest temperature.

### Chatbot

- Click the chat icon to open the chatbot.
- Enter queries (e.g., "What's the weather in London?") to get weather details or temperature statistics.

---

## 🌐 Live Demo

Check out the live website: https://zippy-muffin-1424a3.netlify.app

---

## 📁 Project Structure

```plaintext
.
├── index.html              # Main dashboard with weather and charts
├── table.html              # Filterable forecast table
├── css/                    # Tailwind CSS and custom styles
├── js/                     # JavaScript for API calls, charts, and chatbot
└── README.md               # Project documentation
```

---

## ⚖️ License
This project is for **academic and personal skill development purposes only**.  
Reuse is allowed for **learning and research** with proper credit.

---
