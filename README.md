Weather App

A simple weather application that fetches real-time weather data using the OpenWeatherMap API and displays relevant weather information, including temperature, humidity, and conditions. The background dynamically updates with locally stored GIFs based on the weather condition.

Features

Get weather data by entering a city name.

Fetch weather data using the user's current location.

Temperature toggle between Celsius and Fahrenheit.

Dynamic background updates based on weather conditions.

Minimal and responsive design.

Running the Project Locally

Prerequisites

Ensure you have the following installed on your system:

A modern web browser (Chrome, Firefox, Edge, etc.)

A code editor (VS Code, Sublime Text, etc.)

Node.js (optional, if you want to run a local server)

Steps

Clone the GitHub repository:

git clone <your-repository-url>

Navigate to the project directory:

cd weather-app

Open index.html in a browser, or use a local server:

npx http-server .

Then, open http://localhost:8080/ in your browser.

Project Structure

weather-app/
│-- img/               # Contains weather condition GIFs
│-- index.html         # Main HTML file
│-- style.css          # Styling for the application
│-- script.js          # JavaScript for handling API calls and UI updates
│-- README.md          # Project documentation

Approach & Challenges

Approach

Used OpenWeatherMap API to fetch weather data.

Implemented Geolocation API to get the user's current location.

Updated the background dynamically based on weather conditions using locally stored GIFs.

Ensured a responsive design for a seamless experience across devices.

Utilized CSS animations and flexbox/grid layout for UI structuring.

Challenges & Solutions

GIFs not displaying properly

Issue: External GIF URLs had loading issues.

Solution: Stored GIFs locally and referenced them directly.

Geolocation permissions blocked by the browser

Issue: Some users denied location access, causing errors.

Solution: Added an alert message guiding users to enter their city manually if denied.

Weather icon was too large and dark

Issue: The default OpenWeather icons were large and black, making them difficult to see.

Solution: Adjusted the size via CSS and replaced them with white-themed icons.

Future Improvements

Implement a forecast feature for multi-day weather predictions.

Add dark mode for better night-time usability.

Improve UI with more interactive elements.

🎉 Thank you for checking out this project! Happy coding! 🚀
