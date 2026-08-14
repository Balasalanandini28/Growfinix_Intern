# Weather App 🌤️

## 📌 Project Overview

The **Weather App** is a simple web application developed using **HTML, CSS, and JavaScript**.

The application allows users to enter a city name and retrieve its current weather information using the **OpenWeatherMap API**.

## 🚀 Features

* Search weather by city name
* Displays city name
* Displays current temperature in Celsius
* Displays weather condition
* Displays weather description
* Displays humidity
* Displays wind speed
* Loading message while fetching data
* Error message for invalid cities or API errors
* Responsive and simple user interface

## 🛠️ Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and responsive design
* **JavaScript** – API requests and dynamic content
* **OpenWeatherMap API** – Weather data

## 🔗 API Used

The application uses the OpenWeatherMap Weather API.

API endpoint:

```text
https://api.openweathermap.org/data/2.5/weather
```

## 📂 Project Structure

```text
Task-4-Weather-App/
│
├── index.html
└── README.md
```

## 🔑 API Key Setup

The project requires an OpenWeatherMap API key.

In `index.html`, find:

```javascript
const apiKey = "YOUR_API_KEY";
```

Replace `YOUR_API_KEY` with your actual API key:

```javascript
const apiKey = "YOUR_ACTUAL_API_KEY";
```

**Important:** Do not upload your real API key to a public GitHub repository. For an internship submission, use a placeholder such as `YOUR_API_KEY` or configure the key securely.

## ▶️ How to Run

1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Add your OpenWeatherMap API key.
4. Open `index.html` in a browser.

You can also use the **Live Server** extension in VS Code.

## 🔍 How It Works

1. The user enters a city name.
2. The application validates the input.
3. JavaScript sends a request to the OpenWeatherMap API.
4. The API returns weather information.
5. The application displays the weather details dynamically.
6. If the city is invalid or the API request fails, an error message is displayed.

## 🌡️ Weather Information Displayed

The application displays:

* City Name
* Temperature
* Weather Condition
* Weather Description
* Humidity
* Wind Speed

## 🎯 Internship Task

**Task:** Task 4 – Interactive API Consumer

**Project:** Weather App

**Domain:** Web Development

**Technologies:** HTML, CSS, JavaScript, REST API

## 👩‍💻 Author

**Balasala Nandini**

## 📄 License

This project is created for educational and internship purposes.
