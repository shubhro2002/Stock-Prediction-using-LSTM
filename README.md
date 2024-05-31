# Stock Price Prediction Using LSTM

This project demonstrates an end-to-end approach to predicting stock prices using a Long Short-Term Memory (LSTM) neural network. The project involves fetching historical stock data, preprocessing the data, building and training the LSTM model, making predictions, and visualizing the results. The primary objective is to accurately forecast stock prices based on historical data.

## Project Components

### Data Fetching:
- Historical stock data is fetched from the Alpha Vantage API.

### Data Preprocessing:
- The data is normalized and split into training and testing sets.
- Features and labels are created using a sliding window approach.

### Model Building and Training:
- An LSTM model is built and tuned using Keras Tuner to find the optimal hyperparameters.
- The model is trained on the training dataset.

### Prediction and Evaluation:
- The trained model is used to make predictions on both training and test datasets.
- Root Mean Squared Error (RMSE) is calculated to evaluate model performance.

### Visualization:
- The actual and predicted stock prices are visualized to compare model performance visually.

## RESULT
- The RMSE values for the training and test datasets indicate the model's accuracy.
- Visualization plots provide a clear comparison between actual and predicted stock prices.
## CONCLUSION
This project provides a comprehensive guide to building and deploying an LSTM model for stock price prediction. By following the steps outlined, you can customize the model for different stocks and improve its accuracy through hyperparameter tuning and model optimization.
