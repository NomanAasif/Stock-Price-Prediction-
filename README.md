# Stock-Price-Prediction-

In this project, i did predicting different stock prices using Long Short-Term Memory Recurrent Neural Network(RNN) in Python using TensorFlow and Keras.

I am using yahoo_fin module, it is essentially a Python scraper that extracts finance data from Yahoo Finance platform.The model built is an RNN that has a dense layer as output layer with 1 neuron, this model requires a sequence of features of sequence_length (in this case, we will pass 50 or 100) consecutive time steps (which are days in this dataset) and outputs a single value which indicates the price of the next time step. Increase number of echos(if required), for improving accuracy of the Neura Network built. But, increasing number of echos will relatively consume hours of time in general, but it would be based on the GPU backend and also the hardware of the system one uses.
