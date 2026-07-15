An interactive Weather Analytics Dashboard built in Power BI, providing real-time and 7-day forecast insights for multiple Indian cities.
The dashboard visualizes temperature trends, humidity, air quality, wind patterns, and other environmental factors using live API data.

Project Overview

This project aims to analyze and visualize weather and environmental data in a clear, interactive way.
Data is fetched from a Weather API and transformed for analytical reporting in Power BI, enabling users to monitor real-time weather conditions and trends across multiple cities.

Key Insights & Features

Current Weather Summary
Displays temperature, humidity, wind speed, pressure, and visibility.
7-Day Forecast
Line chart visualizing temperature trends over the next 7 days.
Sunrise & Sunset Tracker
Highlights daily sunrise and sunset timings for the selected city.
Air Quality Index (AQI)
Measures pollutants like PM10, PM2.5, CO, SO₂, NO₂, and O₃.
Rain Probability
Percentage chance of rainfall visualized through a dynamic bar chart.
Multi-City Comparison
Compare real-time weather between major cities such as Mumbai, Jaipur, Bangalore, and Ajmer.
Tools & Technologies Used

Category	Tools / Tech
Data Source	Weather API (OpenWeatherMap or similar)
Data Processing	Power Query (ETL in Power BI)
Visualization	Microsoft Power BI Desktop
Data Type	JSON / CSV (transformed to Power BI Model)
Analytics	DAX Measures, Dynamic Filters, and Custom Visuals
Project Workflow

Data Extraction

Collected weather data via API for multiple cities (7-day forecast).
Exported or connected to Power BI via JSON or CSV.
Data Transformation

Cleaned and structured data using Power Query.
Created calculated columns and measures using DAX.
Dashboard Development

Built dynamic visuals for temperature, AQI, rain probability, and more.
Used cards, line charts, bar charts, and gauges for better clarity.
Insights & Analysis

Compared inter-city weather patterns.
Monitored pollution levels and rain forecasts across locations.
Project Files

weather-analytics-dashboard/
├── Weather.pbix 
├── Dashboard.jpg
├── README.md 
└── icons/icons.jpg
└── Background/background.jpg
Dashboard Screenshots

Dashboard Image

How to Use

Download the .pbix file

Clone or download this repository.
Open the file Weather_Dashboard.pbix in Power BI Desktop.
Connect or Refresh Data

If using live API data, update the API key or endpoint in Power Query.
Otherwise, refresh the dataset to load the latest CSV or JSON data.
Explore the Dashboard

Use slicers to select cities.
Analyze weather parameters interactively.
Cities Covered

Mumbai
Jaipur
Bangalore
Ajmer
(You can easily extend to more cities using the same API.)

Future Enhancements

Integration of real-time API refresh through Power BI Service.
Addition of global city-level analytics.
Implementation of alert-based notifications for severe weather conditions.
Integration with Azure Data Factory for automated data ingestion.
