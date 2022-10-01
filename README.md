# Prediction-of-Monthly-Milk-Production-using-LSTM

Timeseries forecasting using historical data of monthly production using LSTM and Recurrent Neural Network. The data is divided into test and train with last 10 months of data as test data. The date column of the dataset is converted into pandas datetime data which helps in forecasting. To avoid mismatch of range of data, all the values are scaled between values 0 & 1. The LSTM parameters are defined and the model is trained. The predictions are made and graph is plotted.
