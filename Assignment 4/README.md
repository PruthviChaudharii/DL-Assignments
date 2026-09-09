# Assignment 4: LSTM-Based Time-Series Forecasting

## Problem Statement

Develop an LSTM-based model for time-series forecasting using stock price, weather, or sales datasets.

## Objective

To develop and implement a Long Short-Term Memory (LSTM) neural network for time-series forecasting and analyze its ability to learn patterns and predict future values.

## Dataset

The assignment uses a time-series dataset such as:

- Stock Price Dataset
- Weather Dataset
- Sales Dataset

## Technologies Used

- Python
- Jupyter Notebook / Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

## Methodology

1. Load the time-series dataset.
2. Explore and visualize the data.
3. Handle missing values and preprocess the dataset.
4. Normalize the time-series data.
5. Create training and testing sequences.
6. Reshape the data for LSTM input.
7. Design and implement the LSTM model.
8. Train the model using the training data.
9. Forecast values using the trained model.
10. Compare predicted and actual values.
11. Evaluate and visualize the forecasting performance.

## LSTM Model

The model consists of:

- LSTM Layer(s)
- Dense Output Layer

The LSTM network is trained to learn temporal patterns and dependencies present in the time-series data.

## Evaluation

The model performance can be evaluated using appropriate regression metrics such as:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

Prediction plots are also used to compare actual and predicted values.

## Files

- `Assignment-4_DL.ipynb` – Jupyter Notebook containing the complete LSTM implementation, training, forecasting, evaluation and results.

## Conclusion

The LSTM-based model is implemented for time-series forecasting. The predicted values are compared with the actual values to analyze the effectiveness of LSTM in learning temporal patterns and forecasting future observations.
