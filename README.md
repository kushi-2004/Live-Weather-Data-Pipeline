# 🌦️ Real-Time Weather Data Pipeline (Python + SQL)

This project is a mini data engineering pipeline that fetches live weather data for **Colombo, Sri Lanka**, cleans it using Python (Pandas), and stores it in an SQL database for historical tracking.

## 🚀 Features
- **API Integration:** Fetches real-time data from OpenWeatherMap API.
- **Data Transformation:** Cleans and formats raw JSON data into structured DataFrames.
- **Persistent Storage:** Saves data into an SQLite database (`live_weather.db`) using SQL `append` mode.
- **Data Visualization:** Generates live trend charts using Matplotlib.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Requests, Matplotlib, SQLite3
- **Tools:** Google Colab / Jupyter Notebook

## 📖 How to Use
1. Get your API Key from [OpenWeatherMap](https://openweathermap.org/).
2. Run the `weather_pipeline.ipynb` file.
3. Check `live_weather.db` for stored records.