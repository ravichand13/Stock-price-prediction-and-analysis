# Stock-price-prediction-and-analysis
This is about predicting and analyzing the stock prices of various companies

There will be No relation between analysis and prediction, 

the analysis part is to compare one company to another, knowing  where the return would be high, value to risk, how much the company returns compared to others, etc

the prediction part is about predicting the stock's closing value in the upcoming days or months too.

We will predict only using the closing values of the company and will not use another feature.

As we are using a single numpy array, we use data from the last 60 days to predict today. so (today-60 days to yesterday) data to predict today's value. we will send this data to LSTM model to predict.
