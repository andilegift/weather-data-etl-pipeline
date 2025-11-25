# 🌤️ Weather Data ETL Pipeline

A sophisticated web-based ETL (Extract, Transform, Load) pipeline for processing real-time weather data with advanced quality control and anomaly detection.



## 🚀 Features

- **Real-time Data Extraction**: Fetches live weather data from OpenWeatherMap API
- **Data Transformation**: Processes and enriches raw weather data
- **Quality Assessment**: Automated data quality scoring and validation
- **Anomaly Detection**: Identifies unusual weather patterns and data errors
- **Batch Processing**: Support for single city or multi-city processing
- **Interactive Dashboard**: Real-time visualization of ETL process metrics
- **Forecast Analysis**: 5-day weather forecasting with confidence scores

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **API**: OpenWeatherMap API
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Roboto, Poppins)

## 📊 ETL Process Overview

1. **Extract**: Pull raw weather data from OpenWeatherMap API
2. **Transform**: Clean, validate, and enrich data with quality metrics
3. **Load**: Store processed data with timestamps and quality scores
4. **Monitor**: Real-time dashboard with process logs and statistics

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/weather-data-etl-pipeline.git
```

2. Open `index.html` in your web browser

3. Configure your OpenWeatherMap API key in the script.js file

4. Select a city and run the ETL process

## ⚙️ Configuration

- Adjust data quality thresholds using the slider
- Enable batch mode for multi-city processing
- Monitor real-time processing logs
- View detected anomalies and data quality scores

## 📈 Data Quality Metrics

- Temperature range validation (-50°C to 60°C)
- Humidity range checks (0% to 100%)
- Pressure validation (900hPa to 1100hPa)
- Wind speed anomaly detection
- Missing data field identification

## 🔧 API Integration

This project integrates with the [OpenWeatherMap API](https://openweathermap.org/api) to fetch real-time weather data. You'll need to:

1. Sign up for a free API key at OpenWeatherMap
2. Replace the demo API key in the script with your own


## 🎯 Use Cases

- Weather data analysis and monitoring
- ETL process demonstration and education
- Data quality assessment workflows
- Real-time dashboard development
- API integration examples

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Developer

Developed by [Your Name] - Data Engineering Portfolio Project
