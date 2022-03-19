# Unit-14---LSTM-Stock-Predictor

This repository contains two deep learning recurrent neural network models to track BTC closing prices. 

The following questions were answered based on the two models:

## Which model has a lower loss?

The historical BTC prices model has a lower loss (0.0088) compared to the FNG Index model (0.0973). This makes sense, given how each model tracks the actual BTC price as discussed below in the next question.

## Which model tracks the actual values better over time?

The model based on historical BTC prices tracked actual BTC prices better over time than the model based on the FNG Index. The historical BTC price model tracked well for much of the data but under-predicted the price during the period of late June to mid-July. Tuning the above parameters mostly only benefited one of the models at a time, mainly the BTC historical price model. The FNG Index model poorly predicted the actual BTC price during virtually the entire data set.
