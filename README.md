# Time Series Analysis on Chicago Taxi Trips

## Project Overview

This project focuses on a comprehensive time series analysis of Chicago taxi trip data. By leveraging advanced modeling techniques and visualization tools, the project aims to uncover trends, analyze seasonality, and forecast taxi trip demand. The analysis includes implementing ARIMA and Prophet models, conducting stationarity tests, and creating an interactive Streamlit app for visualization and predictions.

## Technologies Used

---

## Key Features

### 1. Dataset

- The dataset contains historical Chicago taxi trip data, including trip dates and total trips.
- Data is preprocessed to handle missing values and formatted for time series analysis.

### 2. Stationarity Analysis

- **Augmented Dickey-Fuller (ADF) Test**: Determines if the data is stationary or requires differencing.
- **Kwiatkowski-Phillips-Schmidt-Shin (KPSS) Test**: Validates the stationarity assumption.

### 3. ARIMA Modeling

- **Auto ARIMA**: Automatically determines the optimal parameters (“p”, “d”, “q”).
- Captures temporal patterns for short-term forecasting.
- Includes seasonality adjustments to improve accuracy.

### 4. Prophet Modeling

- Robust forecasting model developed by Facebook.
- Handles strong seasonality, holidays, and changepoints automatically.
- Generates interpretable and reliable forecasts.

### 5. Visualization

- **Plotly**: Interactive and dynamic plots for trend analysis, model evaluation, and forecasting.
- Includes raw data visualizations, yearly aggregations, and forecast overlays.

### 6. Deployment with Streamlit

- User-friendly and interactive web application.
- Features include:
  - Raw data exploration.
  - Interactive stationarity tests.
  - ARIMA and Prophet forecasts.
- Hosted at: [Streamlit Deployment](https://project5chicagotaxitripstimeseries-wwn89ktpevfmjexzrssvfq.streamlit.app/)

---

## Results and Insights

1. **Trend Analysis**:

   - Identified overall trends and seasonality in taxi trip demand.
   - Yearly and monthly patterns provide actionable insights.

2. **Stationarity**:

   - ADF and KPSS tests guided the data transformation process.
   - Differencing was applied to achieve stationarity for ARIMA modeling.

3. **Model Performance**:

   - ARIMA: Suitable for short-term forecasting and seasonality analysis.
   - Prophet: Delivered robust forecasts with changepoint detection and seasonality adjustments.

4. **Visualization**:

   - Interactive visualizations enhance data exploration and communication of findings.
   - Users can compare raw data trends with model forecasts.

---

## How to Run the App Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/Makorg123/Project5_Chicago_Taxi_Trips_Time_Series.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## Conclusion

This project demonstrates the effective use of time series analysis techniques and interactive tools to understand and forecast taxi trip demand. By combining ARIMA and Prophet models with dynamic visualizations, the analysis provides valuable insights for decision-makers and stakeholders in the transportation industry.

Feel free to explore the code, results, and the interactive app. For any queries or suggestions, please reach out using the contact details below.

---

