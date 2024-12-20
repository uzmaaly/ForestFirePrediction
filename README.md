# Forest Fire Prediction

## Project Overview

This project uses **Linear Regression** to predict the **Fire Weather Index (FWI)** based on weather conditions such as temperature, humidity, wind speed, and rainfall. The application is built using **Flask** and provides an interactive form where users can input weather data and receive the predicted FWI value.

---

## Table of Contents
1. [Project Features](#project-features)
2. [Dataset Details](#dataset-details)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)

---

## Project Features

- **Interactive Form:** A user-friendly interface to input weather data.
- **FWI Prediction:** Predicts the Fire Weather Index based on the provided inputs using a trained linear regression model.
- **Flask Web Application:** The project is built using Flask, making it lightweight and efficient.

---

## Dataset Details

The project is based on weather data collected from June to September 2012, covering the following attributes:

### Weather Data Observations
- **Date**: Recorded in DD/MM/YYYY format.
- **Temp**: Temperature at noon (maximum temperature) in Celsius, ranging from **22°C to 42°C**.
- **RH**: Relative Humidity as a percentage, ranging from **21% to 90%**.
- **Ws**: Wind Speed in km/h, ranging from **6 km/h to 29 km/h**.
- **Rain**: Total rainfall during the day in mm, ranging from **0 mm to 16.8 mm**.

### Fire Weather Index (FWI) Components

- **Fine Fuel Moisture Code (FFMC):** Measures the moisture content of fine fuels, ranging from 28.6 to 92.5.
- **Duff Moisture Code (DMC):** Indicates the moisture content in compact organic layers, ranging from 1.1 to 65.9.
- **Drought Code (DC):** Represents the long-term drying effect, ranging from 7 to 220.4.
- **Initial Spread Index (ISI):** Relates to the rate of fire spread, ranging from 0 to 18.5.
- **Buildup Index (BUI):** Combines DMC and DC to estimate total fuel availability, ranging from 1.1 to 68.
- **FWI**: The target variable, representing the Fire Weather Index.

---
## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/uzmaaly/ForestFirePrediction.git
   cd ForestFirePrediction
2. Create a virtual environment and activate it:
  python -m venv venv
  source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install the required dependencies:
   pip install -r requirements.txt
4. Start the Flask application:
   python application.py
5. Access the application in your browser at http://127.0.0.1:5000.

---

## Usage
Open the web application in your browser.
Fill in the form with the data.
Click the Predict button.
The application will display the predicted Fire Weather Index (FWI).

---

## Contributing
Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   git checkout -b feature-name
3. Commit your changes and push to your branch:
   git commit -m "Add feature-name"
  git push origin feature-name
4. Submit a pull reequest



