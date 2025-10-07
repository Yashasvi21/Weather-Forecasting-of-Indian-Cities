# 🌤️ Weather Forecast Power BI Dashboard

A comprehensive Power BI dashboard that provides real-time weather forecasting and analysis for multiple cities using weather API data.


## 📊 Project Overview

This Power BI project integrates with weather APIs to deliver detailed meteorological insights across 5 major cities. The dashboard provides comprehensive weather analysis including temperature trends, air quality, sunrise/sunset times, and various environmental factors.

## 🎯 Features

### Core Metrics
- **Temperature Analysis**: Current, minimum, maximum, and feels-like temperatures
- **Sunrise & Sunset Tracking**: Daylight hours and timing visualization
- **Air Quality Index (AQI)**: Real-time pollution levels and breakdown
- **Environmental Factors**: Humidity, wind speed, visibility, atmospheric pressure

### Dashboard Capabilities
- Multi-city comparison and individual city deep-dive
- Interactive filters and slicers for customized views
- Responsive design optimized for different devices
- Automated data refresh capabilities

## 🛠️ Technical Implementation

### Data Sources
- **Primary API**: Weather API
- **Update Frequency**: Real-time with scheduled refreshes
- **Cities Covered**:Bengaluru,Bhilai,Jaipur,Mumbai,Noida

### Power BI Components
- **Power Query**: API data extraction and transformation
- **Data Model**: Star schema with optimized relationships
- **DAX Measures**: Custom calculations for weather metrics
- **Visualizations**: Interactive charts, maps, and KPI indicators

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- Active internet connection for API calls
- Weather API key (see setup instructions)

### Installation Steps
1. Clone this repository
2. Open `WeatherDashboard.pbix` in Power BI Desktop
3. Configure API credentials
4. Refresh data connections
5. Explore the interactive dashboard

## 📈 Key Visualizations

### Main Dashboard
- **City Overview Cards**: Key metrics at a glance
- **Temperature Trends**: 5-day forecast comparison
- **AQI Analysis**: Air quality breakdown by components
- **Weather Factors**: Humidity, wind, visibility correlation
- **Daylight Analysis**: Sunrise/sunset timing visualization

### Interactive Features
- City selection slicers
- Date range filters
- Drill-through capabilities
- Tooltip enhancements

## 🔧 Configuration

### API Setup
Refer to `docs/api-configuration.md` for detailed instructions on:
- Obtaining API keys
- Configuring data source permissions
- Setting up automated refresh

### Data Refresh
- **Manual**: Refresh within Power BI Desktop
- **Scheduled**: Configure in Power BI Service
- **Frequency**: Recommended every 6 hours for optimal accuracy

## 🎓 Skills Demonstrated

- **API Integration**: REST API data consumption
- **Data Modeling**: Star schema design
- **DAX Programming**: Custom measures and calculations
- **Data Visualization**: Effective chart selection and design
- **ETL Processes**: Power Query transformations
- **Dashboard Design**: User-friendly interface creation

## 📊 Metrics Tracked

| Category | Metrics |
|----------|---------|
| Temperature | Current, Min, Max, Feels Like |
| Time Data | Sunrise, Sunset, Daylight Hours |
| Air Quality | AQI, PM2.5, PM10, O3, NO2, CO |
| Environmental | Humidity, Wind Speed, Pressure, Visibility |
| Weather Conditions | Main, Description, Icon |

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any enhancements. Suggestions for additional features or improvements are welcome!

## 📄 License

This project is for portfolio and educational purposes. Please ensure compliance with your weather API's terms of service.

