# DAO-Attack-Anomaly-Detection

Simple RNN Autoencoder based on the method used in the paper: <br>
 `A Deep Learning Approach for Detecting Security Attacks on Blockchain`
 
 There are some slight differences that appear to be associated with the tuning of the parameters in the model but also may be associated with the quantile moving average or the normalization / standardization methods.

The model was trained on D1 similar to the paper and T1 for the test dataset. The results were similar but the anomaly was detected the day after the attack unlike the paper..
Potentially due to the method of normalization or processing of data prior to training.

Results:

