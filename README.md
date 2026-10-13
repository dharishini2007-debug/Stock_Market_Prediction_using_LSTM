# 📈 Stock Market Prediction Using LSTM

## 📌 Project Overview

This project uses **Deep Learning and LSTM (Long Short-Term Memory)** neural networks to predict stock closing prices based on historical stock market data. It explores time-series forecasting by analyzing past stock prices, trading volume, and technical indicators.

The project is developed using **Python in Google Colab** and demonstrates how deep learning can be applied to stock market data analysis and price prediction.

## 🎯 Objectives

- Analyze historical stock market data.
- Perform data cleaning and preprocessing.
- Create useful features from stock prices and trading volume.
- Train an LSTM model to learn patterns in time-series data.
- Predict stock closing prices and evaluate model performance.

## ✨ Features

- **Data Preprocessing:** Cleans and prepares historical stock market data for analysis.
- **Feature Engineering:** Calculates daily returns, moving averages, and volatility.
- **Moving Average Analysis:** Computes 5-day, 20-day, and 50-day moving averages.
- **Volatility Analysis:** Measures fluctuations in daily stock returns over a 10-day window.
- **Trading Volume Analysis:** Calculates average volume and volume ratios.
- **Data Scaling:** Uses MinMaxScaler to scale features before model training.
- **LSTM Model Training:** Learns temporal patterns from historical stock data.
- **Stock Price Prediction:** Predicts closing prices based on previous observations.
- **Performance Evaluation:** Uses MAE and RMSE to evaluate prediction errors.
- **Visualization:** Compares actual and predicted stock closing prices using graphs.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Cloud-based development environment |
| TensorFlow / Keras | Building and training the LSTM model |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical computations |
| Scikit-learn | Feature scaling and evaluation metrics |
| Matplotlib | Data visualization |

## ⚙️ Methodology

1. **Data Collection:** Obtain historical stock market data.
2. **Data Cleaning:** Prepare the dataset and handle missing values.
3. **Feature Engineering:** Generate daily returns, moving averages, volatility, and volume-related features.
4. **Data Scaling:** Scale the selected features using MinMaxScaler.
5. **Sequence Preparation:** Create sequences from historical observations for LSTM training.
6. **Model Building:** Build an LSTM neural network for time-series forecasting.
7. **Model Training:** Train the model using historical training data.
8. **Prediction:** Generate predicted stock closing prices.
9. **Evaluation:** Calculate MAE and RMSE and visualize actual versus predicted prices.

## 📊 Evaluation Metrics

- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted prices.
- **Root Mean Squared Error (RMSE):** Measures prediction error while giving greater weight to larger errors.

Lower values generally indicate smaller prediction errors on the evaluated dataset.

## 🚀 How to Run

1. Open the project notebook in Google Colab.
2. Upload the notebook to your Google Drive or open it directly in Colab.
3. Install any required libraries that are not already available.
4. Run the notebook cells in order.
5. Review the prediction results, evaluation metrics, and visualizations.

## 📚 Learning Outcomes

- Understanding LSTM networks and time-series forecasting.
- Learning data preprocessing and feature engineering.
- Applying moving averages and volatility calculations.
- Training and evaluating a deep learning model.
- Visualizing and interpreting stock price predictions.

## ⚠️ Disclaimer

This project is intended for educational purposes only. Stock prices are affected by many unpredictable factors, and model predictions are not guaranteed to be accurate. This project should not be considered financial or investment advice.

## 👩‍💻 Project Status

Developed as a learning project to explore deep learning applications in stock market analysis.

