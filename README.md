# Stock_Prediction

## Project OverView
This project focuses on predicting stock prices using historical data. The approach involves preprocessing stock data, normalizing it, and employing an LSTM model to forecast future prices. The model's performance is evaluated using MAE and RMSE metrics.

## Description
The objective of this project is to forecast stock prices based on historical data, including Open, Close, High, and Low prices. The project involves several key steps: data preprocessing, visualization, model training, and evaluation. The LSTM model is utilized for its effectiveness in handling sequential data and making accurate predictions. The results provide insights into the accuracy of the model and its ability to predict future stock prices.

## Key Features:
- **Date Conversion:** Converts the 'Date' column to datetime format for accurate time series analysis.
- **Normalization:** Applies Min-Max scaling to normalize the stock price data, ensuring consistent input for the model.
- **Plotting:** Creates visualizations for stock prices over time, including individual plots for Open, Close, High, and Low prices, both in single row and grid formats.
- **LSTM Model:** Uses a Long Short-Term Memory (LSTM) network with dropout to prevent overfitting and predict future stock prices based on historical sequences.
- **Training:** Trains the LSTM model on historical data with 100 epochs and evaluates it using validation data.
- **Forecasting:** Generates predictions for the next 30 days based on the trained model.
- **Metrics:** Calculates Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to evaluate the model's prediction accuracy.
- **Predictions:** Compares actual and predicted stock prices through various visualizations, including future price forecasts.

  ## Steps to Run the Project

1. **Clone the repository:**
  ```
   git clone https://github.com/Adithi13/Stock_Prediction.git
  ```

2. **Navigate to the project directory:**

    ```
      cd Stock_Prediction
    ```

## Results
The LSTM model accurately forecasts stock prices with low Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), providing reliable 30-day future predictions. Visualizations effectively compare actual and predicted stock prices.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
