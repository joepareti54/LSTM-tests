# LSTM-tests

--------------- REFERENCE -------------------------------
https://curiousily.com/posts/demand-prediction-with-lstms-using-tensorflow-2-and-keras-in-python/

Demand Prediction with LSTMs using TensorFlow 2 and Keras in Python

the purpose of this exercise is not to create a valid dataset for
LSTM training, but to follow through the matrix transformations that need to be done,
especially to visualize that X_train is a 3d tensor where:
the 1st dimension is the batch
the 2nd dimension is the number of time steps
the 3rd dimension is the number of features

# this notebook is a simplified version of 12.time-series-demand_prediction
# the normalization is skipped in order to compare the initial dataframe 
# and the X_train variable that will be fed into LSTM
#
# The point I want to make is that the cnt column also goes into X_train
which I believe is wrong
