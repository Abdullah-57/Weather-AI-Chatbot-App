Weather Web App (Project by Abdullah Daoud Awan || 22I-2626 || SE-E)

	This Weather Web App provides real-time weather information and a 5-day forecast for any city entered by the user or based on their current location. The app displays weather data such as temperature, humidity, wind speed, and weather description, and it visualizes forecast data using interactive charts. It also offers a table-based forecast with filters like temperature sorting and condition-based filtering.

Features
	Main Features:
	City Search: Users can enter a city to get its weather details.
	Location-based Weather: The app can fetch weather data for the user's current location using geolocation.
	Temperature Unit Toggle: Users can switch between Celsius and Fahrenheit.
	Weather Forecast Charts:
	Vertical Bar Chart: Shows the temperature trend over the next 5 days.
	Doughnut Chart: Visualizes the weather conditions for the next 5 days.
	Line Chart: Displays the temperature trend as a line graph.
	Filterable Forecast Table: Users can view a detailed weather forecast in a table format, with filters for sorting temperature, displaying only rainy days, and more.
	Loading Spinner: Displays a loading animation while fetching data.
	Responsive Design: Optimized for different screen sizes with Tailwind CSS.
	Interactive Chatbot: A built-in chatbot provides users with weather information and temperature statistics based on their input.
	
	Technologies Used:
	HTML5, CSS3 (TailwindCSS for styling)
	JavaScript (ES6+)
	OpenWeather API for fetching weather data
	Chart.js for data visualization
	Google Gemini API for the interactive chatbot

Installation Instructions
	Prerequisites:
	OpenWeather API key: You need to create an account on OpenWeather and get an API key.
	Google Gemini API key: You need to create an account on Google AI Studio and get an API key.

	Setup:
	Clone the repository:
	git clone <your-repo-url>

	Configure API Key:
	Open index.html and table.html.
	Replace the placeholder YOUR_API_KEY in the JavaScript sections with your actual OpenWeather API key and Google Gemini API key.
	Run Locally: If you have a local web server setup, you can directly serve the files. Alternatively, you can use any local hosting tool to view the app.

	Option 1: Using VSCode Live Server extension:
	Install the Live Server extension for Visual Studio Code.
	Right-click on index.html and select "Open with Live Server".

	Option 2: Deploy the app manually using Netlify:
	Login or create an account on Netlify.
	Add a website by selecting the web app project folder to manually deploy it.
	Go to site settings to copy the website URL.
	Paste the URL in any web browser to use a live version of the website (From any device).

	Access the App:
	Open index.html to use the Dashboard with charts.
	Open table.html for the filterable weather table.

Usage
	Dashboard (index.html):
	Search for a city by entering its name in the search bar.
	Choose the temperature unit (Celsius or Fahrenheit) from the dropdown.
	Click "Get Weather" to view the city's weather and forecast.
	Use "Use My Location" to get weather data based on your current location.
	View the 5-day forecast displayed using the bar chart, doughnut chart, and line chart.

	Tables (table.html):
	Enter the city name and click "Get Weather."
	Choose a temperature unit (Celsius or Fahrenheit).
	Use the filter dropdown to:
	Sort temperatures in ascending or descending order.
	Show only rainy days.
	Show the day with the highest temperature.

	Built-in Chatbot:
	Click the chat icon to open the chatbot.
	Enter weather-related queries, and the chatbot will provide weather details and temperature statistics.

Check out the Live Website by the link below:
https://zippy-muffin-1424a3.netlify.app
