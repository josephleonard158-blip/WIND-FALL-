# 📊 Wind Fall Climate Analysis Of Rainfall and Humdity  (2024-2025)

>  **Tools:** Power BI | Excel | DAX | Power Query | Data Modeling

>  **Domain:** AQI Index | Rainfall Analysis

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Domain-Winfall](https://img.shields.io/badge/Domain-Windfall-blue)
![Language-DAX](https://img.shields.io/badge/Language-DAX-orange)


## 🧩 Project Overview
This project analyzes the **Wind Climate Analysis of Rainfall and Humidity(2025)**,Tracks rainfall (mm), humidity (%), temperature (°C), and cloud cover (%)
Compares these metrics across multiple cities like Delhi, Bengaluru, Chennai, Ahmedabad, etc.Study Air Quality Impact **AQI (Air Quality Index)**
Using **Power BI**, the data was cleaned, modeled, and visualized to uncover key by analyzing “Revenue of Humidity”.

---

## 🎯 Project Objectives

### 1. Analyze Weather Patterns
To study and compare rainfall, humidity, temperature, and cloud cover across different cities and states
Identify patterns and seasonal variations in weather conditions

### 2. Evaluate Air Quality Impact
To examine how climatic factors influence AQI (Air Quality Index) categories
Understand the distribution of air quality levels (Good to Poor) across regions

### 3. Geographic and Place-Based Insights
To visualize and compare climate conditions across multiple locations in India
Highlight regional differences using maps and location-based visuals

### 4. Identify Relationships Between Variables
To explore correlations such as: Cloud cover vs temperature Rainfall vs humidity
Detect trends and dependencies among environmental factors

---

## 📂 Data Sources

**Sources & Timeline:**

- 📅 *Indian Climate (2024-2025)*

**Domain:** Climate 

----

## ❓ Problem Statement
- Analyzing the Sum of AQI by category
- Identify patterns and correlations between weather variables and AQI levels
- Track trends over time (e.g., Year-to-Date performance)
- Provide insights into how these environmental factors may impact outcomes like humidity-related revenue or efficiency
- Difficulty in identifying relationships between multiple variables
- Limited tools for interactive and location-based analysis

---

## 🧾 Attribute Details
| **Attribute Name** | **Data Type** | **Description** |
|--------------------|---------------|-----------------|
| Event ID  | Count | Represented as the "Total Count of Event ID |
| YTD | Date | Reporting date (monthly) |
| Day | State data | Used as a time dimension for tracking changes in rainfall and state data |
| Avr | Average | A specific numerical attribute or identifier associated with geographic locations and cloud cover |
| Rainfall | Average Rainfall | Captured as "Average Rainfall" and "Sum of Rainfall (mm)" |
| Temperature | Includes various metrics such as "Sum of Temperature_Avg (°C)," | Sum of Temperature_Min (°C)," and "Temperature_Max (°C)" |
| AQI (Air Quality Index) | Category | Measures the air quality, categorized into levels such as Poor, Very Poor, Moderate, Satisfactory, and Good |

---


## 🧹 Data Preprocessing Steps


1. **Data Cleaning:**
   Ensuring each observation is unique to avoid skewing results, such as ensuring each city's data is only counted once per time period

2. **Data Integration:**
   For example, joining a "Weather" table containing rainfall and temperature with an "Air Quality" table based on a common field like "City" or "Date"

3. **Data Transformation:**
   Normalization/Scaling: Adjusting the range of variables so they can be compared fairly

4. **Data Reduction:**
   Keeping only the most relevant variables for your specific analysis, such as focusing on AQI, Temperature, and Rainfall for a climate report.   
     
5. **Data Formatting:**
   Ensuring fields are correctly categorized as "Date," "Currency," "Text," or "Decimal Number"

   ---

   ## 📉 Analysis & Visualizations

   Developed **interactive Power BI dashboards** addressing all problem statements using:
   - Bar charts
   - Line graphs
   - Scatter plots
   - Donut charts
   - Treemaps
   - Gauge indicators

   **Highlights:**
   - Core Weather & Climate Metrics - Rainfall Analysis: The project tracks an average rainfall of approximately 5.75 mm
   - Geographic Coverage - States Involved: Gujarat, Karnataka, Madhya Pradesh, Tamil Nadu, Delhi, Telangana, Rajasthan, West Bengal, Uttar Pradesh etc..
   - Visualizations and Insights - Wind Speed Analysis: Cities are categorized by wind speed

  ![Dashboard Preview]
