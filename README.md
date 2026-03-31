# 🌤️ Weather App

A simple and responsive Weather Application built using **HTML, CSS, and JavaScript** that fetches real-time weather data using the OpenWeather API.
🌐 https://weather-app-prathamkun.vercel.app/
---

## 📌 Features

* 🔍 Search weather by city name
* 🌡️ Displays temperature in Celsius
* ☁️ Shows weather description (e.g., clear sky, cloudy)
* 🎨 Clean and responsive UI
* ⚡ Real-time API data fetching

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* OpenWeather API

---

## 📁 Project Structure

```
weather-app/
│
├── index.html        # Main HTML file
├── styles.css        # Styling file
├── script.js         # JavaScript logic
└── images/           # Background image
```

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```
   git clone https://github.com/your-username/weather-app.git
   ```

2. Open the project folder:

   ```
   cd weather-app
   ```

3. Open `index.html` in your browser
   OR use **Live Server** in VS Code for better performance

---

## 🔑 API Setup

1. Go to https://openweathermap.org/api
2. Sign up and generate your API key
3. Replace the API key in `script.js`:

   ```js
   const apiKey = 'YOUR_API_KEY';
   ```

⚠️ **Important:** Do not expose your API key in public repositories. Use environment variables or backend for production.

---

## ⚙️ How It Works

* User enters a city name
* JavaScript sends a request to the OpenWeather API
* API returns weather data in JSON format
* Data is displayed dynamically on the webpage

---

## 🧪 Example Output

* City: Mumbai
* Temperature: 30°C
* Condition: Clear sky

---

## 🐞 Common Issues

* ❌ API key not working → Wait a few minutes after generating
* ❌ City not found → Check spelling
* ❌ No data → Check internet or console errors

---

## 🔮 Future Improvements

* 🌍 Auto-detect user location
* 📱 Mobile-friendly UI improvements
* 🌈 Weather icons and animations
* 🔒 Secure API key using backend (Vercel functions)

---

## 🙌 Author

**Pratham Kun**

---

⭐ If you like this project, don’t forget to star the repository!
