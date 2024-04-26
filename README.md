# Stock Price Prediction using LSTM

This project utilizes Long Short-Term Memory (LSTM) networks to predict the stock prices of Apple Inc. The dataset used in this project is retrieved from the Yahoo Finance library.

## Project Overview

The project aims to predict the future stock prices of Apple Inc. based on historical data. It involves the following steps:

1. **Data Retrieval:** Historical stock price data of Apple Inc. is fetched from Yahoo Finance using the yfinance library.

2. **Data Preprocessing:** The retrieved data is preprocessed to prepare it for training the LSTM model. This includes scaling the data and reshaping it to match the input requirements of the LSTM model.

3. **Model Building:** An LSTM model is constructed using the Keras library. The model architecture consists of multiple LSTM layers with dropout regularization to prevent overfitting. The model is trained on the preprocessed data.

4. **Model Evaluation:** The trained model is evaluated on the training dataset to analyze its performance. The loss function is plotted against the number of epochs to visualize the training process.

5. **Prediction:** The trained model is used to predict future stock prices of Apple Inc. These predictions are compared with the actual stock prices to assess the model's accuracy.

## File Descriptions

- **stock_price_prediction.ipynb**: Jupyter Notebook containing the Python code for data retrieval, preprocessing, model building, evaluation, and prediction.
- **train.csv**: CSV file containing the training dataset, which includes historical stock prices of Apple Inc.
- **test.csv**: CSV file containing the testing dataset, which includes future stock prices of Apple Inc.

## Requirements

- Python 3.9
- TensorFlow
- Keras
- NumPy
- pandas
- Matplotlib

## Usage

1. Clone the repository:

```
git clone https://github.com/your_username/stock-price-prediction.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook `stock_price_prediction.ipynb` to execute the code and generate predictions.

## Results

The trained LSTM model demonstrates promising results in predicting future stock prices of Apple Inc. However, further fine-tuning and optimization may be required to improve the model's accuracy.
