# Stock Prediction Model #
In this project, I designed and implemented a machine learning model for predicting the future value of stocks based on historical price data and market indicators. 
- - - -

### Dataset Details ###
- Yahoo Finance - I used Yahoo Finance's dataset and the YFinance Python library for stock data. The dataset provides open, high, low, and close prices of every trade day for major listings on Nasdaq. I divided the dataset into train (65%) and test (35%) sets for predicting stock values.
- Quandl - I used Python stock API 'Quandl' to fetch data regarding the stock market in a desired time span and create a dataset for the purpose of stock prediction. Quandl contains data in two fromats - Time-series and Table. I intended to make heavy use of the table format to extract information regarding different stocks and training the model based on it.
- - - -

### Proposed Architecture ###
I used TensorFlow's Sequential Model with LSTM and Dense layers for stock prediction, focussing on Apple and Microsoft stocks.
- - - -

### Method ###
- Employed machine learning algorithms such as linear regression, decisions trees, and neural networks to build the stock prediction model. 
- Incorporated features derived from historical price data and technical indicators as input variables.
- Trained the model on historical stock data and evaluated its performance using appropriate metrics. 
- - - -

### Results ###
- LSTM demonstrated good regression capability for stock prediction.
- Future predictions showed fluctuations, but overall effectiveness in capturing trends.
- LSTM proved effective in capturing stock trends based on historical data.
- - - -

### References ###
- Gregg Hogg's youtube video on LSTMs and stock prediction model.
- Krish Naik's youtube video on LSTMs and stock prediction model.





