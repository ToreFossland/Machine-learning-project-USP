# Machine learning project, Universidade de São Paulo

This project contains the implementation and use of an SARIMA model and an LSTM
neural network in order to analyze temperature fluctuations in the world. Specifically, I
examine whether climate change is moving so fast that my models are not able to predict
the relatively sudden changes. The SARIMA model generally predicts simpler changes
than the LSTM, and is not able to adapt to a rapidly changing climate. The LSTM on the
other hand is able to predict jagged changes when it’s fed highly fluctuating input. I therefore conclude that predicting climate change accurately is a highly difficult task that may well not be possible without considering more data than the global average temperature. Also LSTM seems as good of a model as one could expect to build using one dimensional historical temperature data only.
