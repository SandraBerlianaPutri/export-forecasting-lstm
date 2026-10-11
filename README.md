# Forecasting Non-Oil and Gas Export Value Using LSTM

## About
This project uses Long Short-Term Memory (LSTM) to forecast Indonesia's monthly non-oil and gas export value. The analysis covers data exploration, preprocessing, model training, evaluation, and future forecasting.

## Data

- **Source:** [Statistics Indonesia (BPS)](https://www.bps.go.id/id/statistics-table/2/MTc1MyMy/nilai-ekspor-migasnonmigas.html)
- **Period:** January 2005 – July 2025
- **Frequency:** Monthly
- **Variable:** Non-oil and gas export value
- **Unit:** Million US dollars (US$)
- **Data Type:** Secondary time series data

## Methods

1. **Data Preparation** — Load the monthly non-oil and gas export dataset and prepare it for analysis.
2. **Exploratory Data Analysis** — Examine export trends and patterns over time.
3. **Data Normalization** — Scale the data using Min-Max normalization.
4. **Sequence Preparation** — Transform the time series into input sequences for LSTM training.
5. **Model Development** — Build and train an LSTM model using the Adam optimizer and Early Stopping.
6. **Model Evaluation** — Evaluate forecasting performance using Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE).
7. **Future Forecasting** — Generate forecasts for the next 17 months using recursive prediction.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University, interested in data analysis and machine learning.
