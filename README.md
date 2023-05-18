# Stock Price Prediction

# Purpose
The purpose of this project was to compare the effectiveness and accuracy of four different methods for predicting stock prices: linear regression, Autoregressive Integrated Moving Average (ARIMA), Facebook's Prophet model, and a custom LSTM model. By evaluating their performance on historical stock data, the project aimed to identify the best technique for forecasting future stock prices.

# Data
The dataset used was the historical pricing data of the SPDR S&P 500 ETF beginning on January 1, 2020 and ending on May 1, 2023. The data was gathered using the yfinance python library. Each model was given 80% of the data for testing and was evaluated on the final 20% of the data. 

# Evaluation
To compare the performance of the four stock price prediction methods, I used the mean absolute error (MAE). MAE measures the average absolute difference between the predicted and actual stock prices, providing a clear indication of the models' accuracy.

# Results
## Linear Regression: MAE of 3.35

## ARIMA: MAE of 3.36
![download](https://github.com/PeterD5353/Stock-Price-Prediction/assets/58152012/cdadfd9f-0000-4fb1-8352-ffc6fae7eb81)

## Prophet: MAE of 9.9
![download](https://github.com/PeterD5353/Stock-Price-Prediction/assets/58152012/64de7d2f-ab8d-4fd4-818a-330aacc693f3)

## LSTM: MAE of .047
![download](https://github.com/PeterD5353/Stock-Price-Prediction/assets/58152012/5341b259-9993-485b-af74-6455ee86c1d5)

# Results
| Model       | MAE         |
| ----------- | ----------- |
| Linear Regression      | 3.35       |
| ARIMA   | 3.36        |
| Prophet | 9.9 |
| LSTM    | .047 | 

#### The LSTM model's ability to capture long-term dependencies and its flexible architecture allowed it to most effectively model complex stock price patterns.

# What would I do next time?
To further bolster the project several ideas can be explored:
* More hyperperameter tuning for the LSTM to try to achieve even better results.
* Analysis of multiple stocks rather than just one.
* Additional feature engineering.
* Ensemble models to achieve better results.

