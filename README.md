# Multivariate-Time-Series-Forecasting
This project implements Vector Autoregression (VAR) to forecast closing prices of multiple stocks, accounting for dependencies between time series.
## **Project Title: Multivariate Time Series Forecasting of Stock Prices**
**Dataset:** Forecasting Multiple Variables: Case Study
**Overview**

This project aims to forecast the closing prices of multiple stocks using multivariate time series analysis. By considering the interdependencies between different stocks, this approach can provide more accurate predictions compared to forecasting each stock individually.

**Key Objectives**

* **Predict Stock Prices:** Forecast the closing prices of multiple stocks over a specified time horizon.
* **Capture Interdependencies:** Model the relationships between different stocks to improve prediction accuracy.
* **Evaluate Model Performance:** Assess the accuracy of the forecasting model using appropriate metrics.

**Methodology**

1. **Data Collection and Preprocessing:** Gather historical stock price data for the desired stocks and preprocess it to handle missing values and outliers.
2. **Exploratory Data Analysis (EDA):** Analyze the data to identify trends, seasonality, and relationships between stocks.
3. **Stationarity Testing:** Check if the time series data for each stock is stationary, as stationarity is a requirement for many forecasting models.
4. **Model Selection:** Choose a suitable multivariate time series forecasting model, such as Vector Autoregression (VAR), based on the characteristics of the data and the desired forecasting horizon.
5. **Model Training:** Train the selected model using the historical data.
6. **Forecasting:** Generate predictions for future stock prices using the trained model.
7. **Evaluation:** Evaluate the accuracy of the forecasts using appropriate metrics, such as Mean Squared Error (MSE), Mean Absolute Error (MAE), or Root Mean Squared Error (RMSE).

**Tools and Techniques**

* **Jupyter Notebook:** Workspace for combining code, documentation and visualization.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical computations.
* **Statsmodels:** For time series analysis and forecasting.
* **Matplotlib and Seaborn:** For creating visualizations.

**Expected Outcomes**

* **Stock Price Predictions:** Generate reliable forecasts of stock prices for the specified time horizon.
* **Improved Decision Making:** Provide valuable insights for investors and traders to make informed decisions.
* **Risk Management:** Help assess potential risks and opportunities in the stock market.

**Future Work**

* **Explore Other Models:** Experiment with different multivariate time series models, such as VARX or structural time series models, to compare their performance.
* **Incorporate External Factors:** Consider incorporating external factors, such as economic indicators or news sentiment, to improve prediction accuracy.
* **Real-time Forecasting:** Implement real-time forecasting to provide up-to-date predictions as new data becomes available.

By following this methodology and utilizing the specified tools, this project aims to provide reliable forecasts of stock prices, enabling informed decision-making in the financial markets.
