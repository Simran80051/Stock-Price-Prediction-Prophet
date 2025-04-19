#
<p align = "center" draggable=”false” ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8HNB-ex4xb4H3-PXRcywP5zKC_3U8VzQTPA&usqp=CAU" 
     width="200px"
     height="auto"/>
</p>

#
# Stock Price Prediction using Facebook Prophet


## About the Project

The project uses historical stock data from Yahoo Finance to train a time series forecasting model using Prophet. The model is then used to make future predictions about the stock price.

## Features

* Fetches historical stock data using the `yfinance` library.
* Preprocesses the data to fit the format required by Prophet.
* Trains a Prophet model on the historical data.
* Makes future predictions about the stock price.
* Visualizes the predictions using interactive plots.
* Deploys the prediction model using Gradio and Huggingface Spaces.

## Usage

1. Open the Colab notebook.
2. Run all the code cells in order.
3. Input the stock ticker symbol, start date, end date, and number of days to predict.
4. Click the "Predict" button to generate the forecast.

## Dependencies

* Python 3.6 or higher
* Prophet
* yfinance
* pandas
* matplotlib
* Gradio (for deployment)

## Usage

1. Clone this repository to your local machine or open it in Google Colab.
2. Install the required libraries if you haven't already.
3. Run the notebook cells sequentially.
4. Modify the `stock` variable to change the stock ticker symbol.
5. Adjust the date ranges and forecast periods as needed.

## Results

The notebook provides visualizations of the predicted stock prices, including the trend, seasonality, and uncertainty intervals. The forecasted prices can be used for making investment decisions or for further analysis.

## Deployment

The notebook includes optional sections for deploying the model using Gradio or Huggingface Spaces. This allows for interactive prediction using a web interface.

