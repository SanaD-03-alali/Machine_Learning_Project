Description:
This project includes classification and time series prediction using various machine learning models.

Table of Contents:

Datasets
Classification
Time Series Prediction
Results



Datasets:

car_evaluation.csv
https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set

gold.csv
https://www.kaggle.com/datasets/faisaljanjua0555/daily-gold-price-historical-dataset


Classification
Models:

SVM
Gradient Boosting Classifier
MLP


Time Series Prediction

Models:

LSTM
BiLSTM
Echo State Network


Results
Key Findings
1. LSTM and BiLSTM
Both models achieved reasonable accuracy with a single-layer architecture.
LSTM achieved a training accuracy of 0.0013, while BiLSTM achieved a slightly higher training accuracy of 0.0014.
However, BiLSTM had lower loss of 0.0024, while LSTM had 0.0045.

2. Echo State Network (ESN)
Competitive performance with a reservoir size of 100 and spectral radius of 0.9.
Utilized tanh activation for non-linearity.

3. Classification Algorithms
MLP: Impressive training accuracy of 98.01%, testing accuracy of 94.04%.
SVM (RBF Kernel): Training Acc: 93.09%, Testing Acc: 92.98%.
Gradient Boosting Classifier: Training Acc: 97%, Testing Acc: 95%.

