# 🌤️ Weather Forecast Dashboard  

This project is a **Weather Forecast Dashboard** that provides real-time and forecasted weather conditions, air quality data, and other environmental insights for selected locations.  

![Weather Dashboard](Screenshot%202025-09-29%20151116.png)  

---

## 🚀 Features  

- **Current Weather Data**  
  - Location-based temperature (°C)  
  - Weather conditions (e.g., Mist, Sunny, Cloudy)  
  - Real-time updates  

- **Weather Forecast**  
  - 7-day temperature forecast with graphical visualization  
  - Sunrise & Sunset timings  

- **Environmental Data**  
  - Humidity, Wind Speed, Pressure, Visibility, UV Index, and Precipitation  
  - Chance of rain probability with percentage breakdown  

- **Air Quality Index (AQI)**  
  - AQI level with health advisory  
  - Detailed pollutant measures: PM10, PM2.5, O3, NO2, SO2, CO  

---

## 🛠️ Tech Stack  

- **Frontend**: React.js / HTML / CSS / JavaScript  
- **Backend**: Node.js / Express.js (for API calls)  
- **APIs Used**:  
  - [OpenWeather API](https://openweathermap.org/api) – for weather data  
  - [AirVisual API](https://www.iqair.com/air-pollution-data-api) – for AQI data  
- **Visualization**: Chart.js / Recharts / D3.js  

---

## 📂 Project Structure  

```
weather-forecast-dashboard/
│── public/               # Static files  
│── src/  
│   ├── components/       # Reusable UI components  
│   ├── pages/            # Dashboard pages  
│   ├── assets/           # Images and icons  
│   ├── services/         # API integration logic  
│   ├── App.js            # Main app entry  
│   └── index.js          # React root file  
│── package.json          # Dependencies and scripts  
│── README.md             # Project documentation  
```

---

## ⚙️ Installation & Setup  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/weather-forecast-dashboard.git
   cd weather-forecast-dashboard
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Create `.env` file** and add API keys  
   ```
   REACT_APP_WEATHER_API_KEY=your_openweather_api_key
   REACT_APP_AQI_API_KEY=your_airvisual_api_key
   ```

4. **Run the project**  
   ```bash
   npm start
   ```

---

## 📊 Example Output  

- Current weather in Noida: **35.1°C (Mist)**  
- AQI: **100 (Moderate)**  
- Chance of Rain: **89% on Monday**  
- Forecast: Gradual cooling from 31.3°C → 30.2°C over the week  

---

## 🌎 Future Enhancements  

- Add **multi-city comparison**  
- Integrate **satellite weather radar maps**  
- Implement **voice-based weather assistant**  
- Add **push notifications for severe weather alerts**  

---

## 📜 License  

This project is licensed under the **MIT License**.  
