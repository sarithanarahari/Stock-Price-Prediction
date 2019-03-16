# Stock-Price-Prediction
Stock Price Prediction using Neural Network, LSTM and CNN

• Fully Connected Neural Network: Use the daily [Open, High, Low, Volume] to predict [Close] on that day using a fullyconnected neural network. Use the first 70% of the records for training and the remaining 30%
of the records for test. Report the RMSE of the model. Show the “regression lift chart” of your
test data.

• LSTM: Predict [Close] of a day based on the last 7 days’ data [Open, High, Low, Volume,
Close] using a LSTM model. In other words, we want to predict the price in the green cell
using all the numbers in the red cell. Use the first 70% of the available records for training and
the remaining 30% of the available records for test. Report the RMSE of the model. Show the
“regression lift chart” of your test data.

• CNN : Do the same as Task 2 but use a CNN model. Report the RMSE of the model. Show
the “regression lift chart” of your test data.

Dataset:

https://drive.google.com/open?id=1epxIFUlSWj9p11frJPqHq2hWY03EUQxh
The data has seven columns as follows:
Date, Open, High, Low, Close, Adj_Close, Volume
