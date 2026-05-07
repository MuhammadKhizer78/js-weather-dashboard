# Real-Time Weather App

A clean, responsive web application that fetches real-time weather data for any city in the world using vanilla JavaScript and the OpenWeatherMap API.

### Features
* **Live API Integration:** Uses the JavaScript `fetch` API to retrieve live data from OpenWeatherMap.
* **JSON Parsing:** Asynchronously processes JSON responses to extract specific data points (temperature and weather conditions).
* **Error Handling:** Includes logic to catch invalid inputs and display a user-friendly "City not found!" message (handling 404 response codes).
* **Metric Conversion:** Automatically requests and displays the temperature in Celsius.
* **Responsive UI:** Features a modern, centered card layout with a CSS gradient background that adapts to mobile screens.

### Tech Stack
* **HTML5:** App structure.
* **CSS3:** Flexbox layout, gradients, and responsive media queries.
* **JavaScript (ES6):** Asynchronous `fetch` requests, Promises (`.then()`), DOM manipulation, and template literals.
* **API:** [OpenWeatherMap API](https://openweathermap.org/api)

### How to Run Locally
The live link is available in the description section.

### Security Note
*For the purpose of this academic assignment, the OpenWeatherMap API key is included in the front-end code to allow immediate grading and testing. In a production environment, this key would be secured on a backend server or obscured using environment variables.*
