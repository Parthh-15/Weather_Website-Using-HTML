📌 Project Overview
This project demonstrates how to build Weather Display Widgets using HTML, CSS, and JavaScript with the Fetch API.
The widgets fetch real-time temperature data from a free weather API (Open-Meteo) and display it on a web page.
The project contains two implementations:
Weather by City Name
Fixed Location Weather Widget
🛠 Technologies Used
HTML5 – Structure of the webpage
CSS3 – Styling and layout
JavaScript (ES6) – Fetch API & DOM manipulation
Open-Meteo API – Free weather data (No API key required)
📂 Project Files
1️⃣ Weather by City (weather_assignment1.html)
Description:
Allows the user to enter a city name and fetches the current temperature for that city.
Features:
User input for city name
Converts city name to latitude & longitude using Geocoding API
Fetches live weather data
Proper error handling (empty input, city not found)
How it works:
User enters a city name
City name is converted to coordinates
Weather API fetches temperature
Temperature is displayed on screen
2️⃣ Weather Widget (weather_assignment2.html)
Description:
A simple weather widget that displays the temperature for a fixed location when a button is clicked.
Features:
Clean UI widget
One-click weather fetch
Displays real-time temperature
Uses Fetch API with .then() and .catch()
▶ How to Run the Project
Download or copy the HTML files
Open any file in a web browser (Chrome, Edge, Firefox)
Make sure you have an active internet connection
Enter a city name (for city-based widget) or click the button
🌐 API Used
Open-Meteo Weather API
URL: https://api.open-meteo.com
Free to use
No authentication required
🎯 Learning Outcomes
Understand how the Fetch API works
Learn how to handle JSON responses
Implement error handling in JavaScript
Build real-world widgets using APIs
✅ Conclusion
This project is ideal for beginners learning JavaScript and APIs.
It demonstrates real-time data fetching, clean UI design, and practical usage of fetch() in web development.
