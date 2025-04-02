# Mount Studentloans Intelligence Console 🏔️📊

Welcome to the **Mount Studentloans Intelligence Console**, a Splunk-powered monitoring and analytics dashboard built for a fictional higher-ed institution struggling with rapid digital transformation and remote collaboration challenges.

## Project Purpose

This project was created as part of a Splunk panel presentation. The goal is to demonstrate how machine learning and data visualization can provide deep insights into organizational behavior, system usage, and potential security threats during and after a shift to remote work.

## Features

- **Teams Activity Over Time**  
  Visualize historical Microsoft Teams usage trends, broken down by year and month, with insights into total user activity.

- **Suspicious Logins**  
  Detect multi-location logins in short timeframes to flag potential account compromise or credential sharing.

- **Machine Learning Forecasting**  
  Forecast Teams activity using the `LLP5` algorithm for future planning and resource allocation.

- **Geographic Analysis**  
  Identify top countries by activity and visualize regional usage across your Teams network.

- **KPI Panels**  
  - Average actions per country  
  - Highest activity month  
  - Forecasted daily actions 45 days ahead

## Machine Learning Model

**Model Used:** LLP5 (Linear Law Polynomial Order 5)  
LLP5 captures long-term, seasonal, and subtle nonlinear patterns in time-series data. It works by fitting polynomial trends to local data segments for smoother, more reliable forecasts.

- Confidence Interval: 95%  
- Forecast Window: 150 days  
- Holdback: 0 (full dataset used)

## 🛠Technologies

- Splunk Enterprise
- Splunk Machine Learning Toolkit (MLTK)
- SPL (Search Processing Language)
- AI-generated synthetic data
- Power Point

## Dashboard Overview

This project includes:

- A full intelligence console built in **Splunk Dashboard Studio**
- Pre-trained ML model and visualizations
- Fake company branding: `Mount Studentloans`


## Fake Company Lore

> **Mount Studentloans** is a fictional university navigating remote collaboration after COVID-19. Like many institutions, they faced challenges transitioning to digital platforms while keeping systems secure and observable.


## Author

Matthew Saxby  



---

*This project is a fictional demonstration for educational purposes. No real user or institutional data is used.*
