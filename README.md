# Linear Regression Analysis on Fire Weather Index (FWI)

## Project Overview

This project uses **Linear Regression** to analyze how weather conditions and other factors influence the **Fire Weather Index (FWI)**. The dataset, collected from June to September 2012, includes various meteorological variables and FWI components. The primary objective is to predict FWI based on temperature, humidity, wind speed, and rainfall, and to evaluate the significance of these factors.

---

## Dataset Details

### Weather Data Observations
- **Date**: Recorded in DD/MM/YYYY format from June to September 2012.
- **Temp**: Temperature at noon (maximum temperature) in Celsius, ranging from **22°C to 42°C**.
- **RH**: Relative Humidity as a percentage, ranging from **21% to 90%**.
- **Ws**: Wind Speed in km/h, ranging from **6 km/h to 29 km/h**.
- **Rain**: Total rainfall during the day in mm, ranging from **0 mm to 16.8 mm**.

### Fire Weather Index (FWI) Components
- **Fine Fuel Moisture Code (FFMC)**: Measures the moisture content of fine fuels, ranging from **28.6 to 92.5**.
- **Duff Moisture Code (DMC)**: Indicates the moisture content in compact organic layers, ranging from **1.1 to 65.9**.
- **Drought Code (DC)**: Represents the long-term drying effect, ranging from **7 to 220.4**.
- **Initial Spread Index (ISI)**: Relates to the rate of fire spread, ranging from **0 to 18.5**.
- **Buildup Index (BUI)**: Combines DMC and DC to estimate total fuel availability, ranging from **1.1 to 68**.

---

## Objective

The main goal is to:
- Predict the **Fire Weather Index (FWI)** using linear regression.
- Analyze the impact of weather variables (temperature, humidity, wind speed, and rainfall) on FWI.

---

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Scikit-learn
- **Methodology**: Data preprocessing, exploratory data analysis (EDA), Feature Selection, Feature Scaling, Model Training, and evaluation.

---


