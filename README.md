# LSTM_Ethereum_Classic
LSTM Ethereum Classic

Simple RNN Autoencoder based on the method used in the paper: <br>
 `A Deep Learning Approach for Detecting Security Attacks on Blockchain`
 
 There are some slight differences that appear to be associated with the tuning of the parameters in the model but also may be associated with the quantile moving average or the normalization / standardization methods.

The model was trained on D1 similar to the paper and T1 for the test dataset. The results were similar but the anomaly was detected several days after the attack unlike the paper..
