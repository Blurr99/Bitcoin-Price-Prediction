# Bitcoin Price Prediction 📊💰
This project aims to predict the price of Bitcoin using time series data from 2013 to 2020, with a focus on analyzing and forecasting price trends for the period from 2020 to 2023. Predictions are evaluated against actual historical data to assess the model's performance.

## Project Overview
The notebook explores various modeling approaches, from baseline models to advanced deep learning architectures, to capture Bitcoin’s volatility and trend patterns. Each experiment adjusts parameters such as the forecast horizon and window size, providing insights into which models perform best for short-term and long-term predictions.

## Modelling Experiments
Below is a summary of each model used:

- Model 0: Naive Model (Baseline)
- Model 1: Dense Model, Horizon = 1, Window = 7
- Model 2: Dense Model, Horizon = 1, Window = 30
- Model 3: Dense Model, Horizon = 7, Window = 30
- Model 4: Conv1D, Horizon = 1, Window = 7
- Model 5: LSTM, Horizon = 1, Window = 7
- Model 6: Dense Model with Multivariate Data, Horizon = 1, Window = 7
- Model 7: N-BEATS Algorithm, Horizon = 1, Window = 7
- Model 8: Ensemble Model (optimized on multiple loss functions), Horizon = 1, Window = 7
- Model 9: Future Prediction Model, Horizon = 1, Window = 7
- Model 10: Dense Model with Turkey Data Introduced, Horizon = 1, Window = 7

## Dataset
The dataset includes daily Bitcoin price data from 2013 to 2020 for training. The model’s performance is tested by comparing predictions to actual Bitcoin prices from 2020 to 2023.

## Results
Each model's accuracy is evaluated based on its ability to predict prices in the forecasted period (2020-2023). Results are compared across different architectures and parameters to identify the best-performing model for Bitcoin price prediction.

## How to Use
- Clone the repository.
- Run the notebook to train and evaluate each model.
