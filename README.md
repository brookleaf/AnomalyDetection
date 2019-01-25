# AnomalyDetection


The iPython notebook walks through training an LSTM model over the boiler temperature dataset with the following distribution.

training set: 6484
test set: 2000

RMSE is impressive and we have been able to confidently trace the operational behaviour.

However, there is another PNG file in the repo that shows the plots of another LSTM trained on the following distribution.

training set:8474
testing set: 10

RMSE seems to be really good enough to trust for anomaly detection especially.

Note: Before an attempt inmade to run the code, please be aware the training of the two LSTMs have taken nearly 15 hrs.

