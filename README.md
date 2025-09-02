# AppyWay_Task
# London Bike Rentals Analysis (2015–2017)

## Overview
This project explores the **London bike share dataset (2015–2017)** and demonstrates how to turn raw data into insights using **Python (EDA)** and **Power BI (dashboard)**.  
It was built as part of my application to AppyWay, focusing on urban mobility, transport efficiency, and data-driven decision making.

## Dataset
- Source: [Kaggle – London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)  
- 48,000+ records with features such as:
  - `cnt`: number of bike rentals (target variable)
  - `t1`, `t2`: temperatures (Celsius, normalized)
  - `hum`: humidity
  - `weather_code`: weather conditions
  - `is_holiday`, `is_weekend`: calendar flags
  - `timestamp`: datetime of measurement

## Tools Used
- **Python (pandas, matplotlib)** → data cleaning, EDA
- **Power BI** → interactive dashboard (KPIs, time-series, bar, scatter)
- **GitHub** → project documentation and portfolio

## Dashboard (Power BI)

### Default View
![Dashboard](screenshots/dashboard.png)

### Weekday Filter Example: Tuesday
![Tuesday Filter](screenshots/dashboard_tuesday.png)

### Weekday Filter Example: Saturday
![Saturday Filter](screenshots/dashboard_saturday.png)

The dashboard is **interactive**. Selecting a weekday automatically updates all charts and KPIs, allowing users to explore patterns dynamically.

## Insights & Learnings
- **Total Rentals**: ~20 million bike rentals between 2015–2017.  
- **Seasonality**: Strong summer peaks, winter dips.  
- **Weekday Patterns**:  
  - Tuesdays and Thursdays peak, linked to commuting.  
  - Saturdays and Sundays are lower, showing less commuter traffic.  
- **Weather Effect**: Rentals increase with temperature up to ~25°C, then plateau.

This project helped me practice:
1. Cleaning and exploring data with Python.  
2. Designing interactive Power BI dashboards.  
3. Using drill-downs and filters for stakeholder exploration.  
4. Translating raw data into **clear insights for decision-making**.

## Next Steps
- Explore forecasting models for demand prediction.  

---
