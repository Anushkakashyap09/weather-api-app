
# 📍 Weather Report CLI Application

A lightweight Python Command-Line Interface (CLI) application that fetches, parses, and displays real-time weather data for any specified city globally. 

Built as an entry-level portfolio project, this application demonstrates foundational concepts in Python programming, API integration, data parsing, and structured terminal output.

---

## 🚀 Features

- **Real-Time Data Retrieval:** Integrates with the OpenWeatherMap API to fetch live meteorological data.
- **Dynamic Metrics:** Displays localized temperature (Celsius), weather conditions, humidity percentage, and calculated wind speeds.
- **Smart Analytics & Alerts:** Implements automated conditional logic to provide user-friendly health and safety recommendations based on extreme temperatures, precipitation, or high winds.
- **Secure Key Management:** Uses Google Colab's native `userdata` secrets management to protect API authentication keys securely.

---

## 📊 Connection to Data Science & Statistics

As a Statistics student pivoting into Data Science, this project serves as a foundational step toward programmatic data acquisition. Before data can be cleaned, modeled, or analyzed, it must first be collected. This application showcases:
- **Data Engineering Basics:** Querying web-based REST APIs.
- **Semi-Structured Data Handling:** Mapping, filtering, and parsing nested JSON payloads into accessible data formats.
- **Metric Transformations:** Programmatic unit conversion (e.g., transforming wind velocity vectors from meters per second (m/s) to kilometers per hour (km/h)).

---

## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.x
- **Libraries:** - `requests` (HTTP requests management)
  - `google.colab.userdata` (Secure API key storage)

---

## 🔧 Installation & Setup

To run this notebook script in Google Colab, follow these steps:

1. **Get an API Key:**
   Sign up at [OpenWeatherMap](https://openweathermap.org/) and generate a free API key.

2. **Configure Secrets in Colab:**
   - Open your Google Colab notebook.
   - Click on the **Secrets** icon (the key icon 🔑 on the left sidebar).
   - Add a new secret with the Name: `OPENWEATHER_KEY`.
   - Paste your OpenWeatherMap API key into the Value field.
   - Toggle on **Notebook access**.

3. **Execute the Code:**
   Run the cell, enter your desired city when prompted, and view the generated weather report.

---

## 📸 Sample Output

```text
Enter the city: London

==============================
📍WEATHER REPORT: LONDON
==============================
🌡Temperature: 14.2 C
☁Condition: broken clouds
💧Humidity: 72 %
💨wind Speed: 15.1 km/h
==============================

🥶Very cold weather
Wear layered clothing to trap body heat effectively 🧥
==============================
☁Sky is cloudy
```
