Bitcoin Price Prediction using Machine Learning.
So, to begin with, the project I have used Binance to get
the data set for bitcoin price and used Binance's API Key
and Secret key to establishing a connection with my
python code on jupyter notebook in IBM CLOUD. After
that I have used a few python libraries such as; pandas -
to read data and make data frame, NumPy - to perform
mathematical operations on data, Keras - to import sub
libraries such as model and then further importing
some classes from this such as Sequential, dense, and
LSTM.
My algorithm part starts with pre-processing the data
fetched from binance and then splitting them into the
train and test set. The algorithm I used to train the
model is LSTM which is Long Short-Term Memory(LSTM).
This uses the layered approach to train the model and
then finally the model is fit using fit_tranform method
on X_train and Y_train and prediction is made via predict method.
