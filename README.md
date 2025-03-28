# 🌍 Global Weather Analysis and Forecasting ☁️🌡️

![GitHub Repo Stars](https://img.shields.io/github/stars/prabhatadvait/Weather_forecasting?style=social) ![GitHub forks](https://img.shields.io/github/forks/prabhatadvait/Weather_forecasting?style=social)

## 📌 Project Overview
This project analyzes global weather data, performs exploratory data analysis (EDA), detects anomalies, and builds predictive models for temperature forecasting using machine learning techniques.

## 🎯 PM Accelerator Mission
By making industry-leading tools and education available to individuals from all backgrounds, the PM Accelerator program empowers future PM leaders. This project aligns with that mission by leveraging advanced data analytics, machine learning, and forecasting models to enhance decision-making and predictive capabilities.

---

## 📜 Table of Contents
- [🌟 Introduction](#-introduction)
- [📊 Dataset](#-dataset)
- [🛠️ Data Processing and Cleaning](#-data-processing-and-cleaning)
- [📈 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [🤖 Forecasting Models](#-forecasting-models)
- [⚠️ Anomaly Detection](#-anomaly-detection)
- [🔍 Feature Importance Analysis](#-feature-importance-analysis)
- [🗺️ Geospatial Weather Visualization](#-geospatial-weather-visualization)
- [📌 Results and Key Insights](#-results-and-key-insights)
- [📂 Project Structure](#-project-structure)
- [🚀 How to Run](#-how-to-run)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## 🌟 Introduction
### 🎯 Objective
- Analyze global weather trends
- Perform exploratory data analysis (EDA)
- Detect anomalies
- Build predictive models for temperature forecasting

### 🔍 Scope
- Data Cleaning and Preprocessing
- Time-Series Forecasting using ARIMA and Prophet models
- Anomaly Detection
- Feature Importance Analysis using Machine Learning
- Geospatial Weather Visualization

---

## 📊 Dataset
**📂 Data Source:**
The dataset includes global weather records with attributes like temperature, humidity, wind speed, and geographic information.

---

## 🛠️ Data Processing and Cleaning
- **Handling Missing Values:** Forward fill method (`ffill`) applied.
- **Outlier Detection:** Interquartile Range (IQR) method used.
- **Feature Scaling:** StandardScaler applied.
- **Datetime Conversion:** `last_updated` column formatted.

---

## 📈 Exploratory Data Analysis (EDA)
### 🔑 Key Insights:
- Temperature trends visualized over time.
- Correlation analysis via heatmaps.
- Moving averages for seasonal trends.

### 📊 Visualizations Used:
- 📈 Line plots
- 🔥 Correlation heatmaps
- 📅 Seasonal rolling averages

---

## 🤖 Forecasting Models
### 📌 ARIMA Model
- Modeled temperature trends.
- Training and testing split (80-20).
- Evaluated using Mean Absolute Error (MAE) and Mean Squared Error (MSE).

### 🚀 Prophet Model
- Used for long-term forecasting.
- Forecasted temperature trends for the next 30 days.

---

## ⚠️ Anomaly Detection
- **Z-score Method:** Points with a Z-score > 3 flagged as anomalies.
- **Example Anomalies:**
  ```plaintext
  Country: Canada, Location: Ottawa, Temperature: -3.04°C (Anomaly)
  Country: Sweden, Location: Stockholm, Temperature: -3.00°C (Anomaly)
  ```

---

## 🔍 Feature Importance Analysis
- **Random Forest Regressor** trained to analyze feature importance.
- Identified key weather attributes affecting temperature.

---

## 🗺️ Geospatial Weather Visualization
- **🌍 Folium Maps:** Interactive maps created.
- **📌 Geospatial Analysis:** Showed temperature variations across locations.

---

## 📌 Results and Key Insights
- ✅ Data preprocessing improved model performance.
- ✅ ARIMA and Prophet models captured seasonal trends effectively.
- ✅ Machine learning analysis identified key weather attributes.
- ✅ Geospatial visualization helped in climate studies.

---

## 📂 Project Structure
```plaintext
├── 📂 data/               # Raw and processed datasets
├── 📂 notebooks/          # Jupyter notebooks for analysis
├── 📂 scripts/            # Python scripts for data processing and modeling
├── 📂 visualizations/     # Generated plots and maps
├── 📄 README.md           # Project documentation
└── 📄 requirements.txt    # Dependencies
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/prabhatadvait/Weather_forecasting.git
   cd Weather_forecasting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```bash
   python scripts/main.py
   ```

---

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** this repository and submit **pull requests**. 🌟

---

## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

🚀 **Happy Coding!** 🌍☁️
