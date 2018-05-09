# Recurrent_LSTM_Stock_Prediction
Using the daily opening prices of GOOGL for the past 5 years, the RNN would predict the next day's opening price

A dataset was obtained of GOOGL price data from 2012 to 2017. This price data included the Open, High, Low, Close price as well as the Volume. However, for the RNN, I only used the Opening prices. I split the 2012 to 2016 data into training and the first month of 2017 as the test set. 

The RNN was built using Keras, and included 4 hidden layers with 50 LSTMs in each. The output was one neuron for the price of the next day. 

Every prediction was made using the past 2 months of daily opening prices.

The predicted and actual results were then graphed.
