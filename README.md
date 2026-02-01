# Weather API Dashboard

## Problem Statement
Many data analysis projects rely on static CSV files, which do not provide real-time or dynamic data. There is a need for a project that utilizes a live data source to demonstrate advanced Power BI capabilities and create an interactive, real-time dashboard. 

## Goal / Purpose
The primary goal of this project is to develop a **real-time weather dashboard** using Power BI by connecting to a weather API. This project demonstrates end-to-end data analysis skills, including:
- Connecting to live web data sources (APIs)
- Performing data transformation and cleaning in Power Query
- Setting up tables and data modeling
- Developing interactive dashboards with various visualizations
- Handling and visualizing dynamic data for multiple cities

## Key Visuals
The dashboard includes the following main visuals:
- **City Selection Slicer:** Horizontal slicer for selecting different cities, with a clean dark-themed design and rounded buttons
- **Current Temperature Card:** Displays the current temperature of the selected city in Celsius with conditional formatting
- **Location & Last Updated Info:** Shows city name, country, and last updated timestamp with icons
- **Current Weather Metrics Cards:** Individual cards for visibility, wind speed, pressure, humidity, etc., each with relevant icons
- **7-Day Forecast Slicer/Cards:** Displays the day of the week, weather icon, and average temperature for each day
- **Forecast Line Chart:** Visualizes 7-day average temperature trends with clear axes, data labels, and thematic colors

## Business Impact / Insights
This project demonstrates:
- **Real-time Data Utilization:** Moves beyond static datasets to support dynamic decision-making
- **Scalability for Multiple Locations:** Allows adding and combining data from multiple cities using a master table
- **Enhanced Data Presentation:** Polished, interactive dashboard enhances understanding and user experience
- **Showcasing Advanced Power BI Skills:** Highlights proficiency in Power Query, data modeling, DAX, and dashboard design

## Screenshot of Dashboard
![Dashboard Screenshot](https://github.com/JeeniyaShakya/Weather_API_Dashboard/blob/main/Screenshot%202026-01-28%20110936.png)

## Techniques Used
- **API Integration:** Connected Power BI to WeatherAPI.com via web data source
- **Power Query Transformations:**
  - Extracted data from JSON format
  - Appended queries to create a master table
  - Created separate tables for current, forecast day, and forecast hourly data
  - Removed unnecessary columns and duplicates
  - Replaced values to generate proper image URLs for weather icons
- **Data Modeling:** Established relationships between tables (Current, Forecast Day, Forecast Hours, Location) using the Location Name column
- **DAX (Data Analysis Expressions):**
  - Created measures for current and forecast temperatures
  - Calculated columns for day names
  - Formatted values with symbols (e.g., "°C", "km/h")
- **Dashboard Design & Visualization:**
  - Applied custom dark-mode themes
  - Implemented custom slicers and cards
  - Incorporated image URLs for dynamic weather icons
  - Used line charts for trend visualization

