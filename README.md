# Crypto-Price-Prediction-Using-ML
# This project builds an LSTM-based machine learning model to predict the future price of cryptocurrencies such as Bitcoin (BTC). The model is trained on historical price data and can forecast the next day's closing price with high accuracy.

# Features
 ✅ Fetches real-time cryptocurrency data from Yahoo Finance
 ✅ Uses LSTM (Long Short-Term Memory) model for time series forecasting
 ✅ Evaluates model performance using RMSE (Root Mean Squared Error)
 ✅ Provides a function to predict the next day's price for any cryptocurrency
 ✅ Visualizes price trends with Matplotlib & Seaborn

#  Data Source
 The dataset is obtained from Yahoo Finance using the yfinance API.

🔹 Features Used
 Date – The date of the observation
 Open – The opening price of the cryptocurrency
 High – The highest price of the cryptocurrency
 Low – The lowest price of the cryptocurrency
 Close – The closing price (used for prediction)
 Volume – The total trading volume

# Model Architecture
 The model is built using LSTM (Long Short-Term Memory), a deep learning architecture for time-series forecasting. The architecture includes:
 LSTM Layers: Capturing sequential price trends
 Dropout Layers: Preventing overfitting
 Dense Layers: Outputting the predicted price

# Future Improvements
 🔹 Implement multi-step forecasting (predict prices for the next 7/30 days)
 🔹 Add news sentiment analysis for better predictions
 🔹 Develop a trading bot using Reinforcement Learning
 🔹 Deploy as a web application using Flask or FastAPI

# License
 This project is licensed under the MIT License.
