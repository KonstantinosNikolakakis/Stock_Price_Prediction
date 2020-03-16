# Stock_Price_Prediction, RNN

 Training an LSTM to predict Google stock price
 Input: 59 timesteps (vector of opening prices), Output: the opening price of the next day
 Training data set: 1200 samples (opening prices 1/3/2012 - 12/30/2016) 
 Test data set: opening prices 1/3/2017 - 1/31/2017

 4 layers, optimizer = 'adam', loss = 'mean_squared_error', epochs = 100, batch_size = 32
