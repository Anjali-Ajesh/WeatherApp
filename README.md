# Simple Weather App

A beautiful and responsive weather application that provides real-time weather data for any city. Built with Vanilla JavaScript and styled with Tailwind CSS, this app fetches data from the OpenWeatherMap API to deliver a seamless user experience.

![Weather App Screenshot](https://placehold.co/600x400/60a5fa/FFFFFF?text=Weather+App+UI)

## Features

- **Real-time Weather Data:** Get up-to-date weather information for any city.
- **Key Weather Metrics:** Displays temperature (in Celsius), humidity, wind speed, and a weather description.
- **Dynamic Icons:** Shows a weather icon that corresponds to the current conditions.
- **Sleek & Modern UI:** A clean, responsive interface that looks great on all devices.
- **Error Handling:** Provides user-friendly messages for invalid city names or API errors.
- **Lightweight:** Built with no frameworks for fast loading and performance.

## Technologies Used

- **HTML5:** For the application's structure.
- **Tailwind CSS:** For all styling and the responsive design.
- **Vanilla JavaScript:** For API requests and all client-side logic.
- **OpenWeatherMap API:** As the source for real-time weather data.

## Setup and Usage

To run this project, you need a free API key from OpenWeatherMap.

1.  **Get an API Key:**
    * Go to [OpenWeatherMap](https://openweathermap.org/appid) and sign up for a free account.
    * Navigate to the "API keys" tab and copy your default API key.

2.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/weather-app.git](https://github.com/your-username/weather-app.git)
    ```

3.  **Add Your API Key:**
    * Open the `index.html` file in a code editor.
    * Find the line `const apiKey = 'YOUR_API_KEY';` in the `<script>` section.
    * Replace `'YOUR_API_KEY'` with the key you copied from OpenWeatherMap.
