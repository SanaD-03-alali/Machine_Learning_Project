# Machine Learning Project: Classification and Time Series Prediction

This repository contains the code and results for a machine learning project that involves both classification and time series prediction tasks. The project utilizes various machine learning models to achieve high accuracy and predictive performance on the given datasets.

## Datasets

1. **Car Evaluation Dataset**: This dataset is used for the classification task.
   - [Car Evaluation Data](https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set)

2. **Gold Price Historical Dataset**: This dataset is used for the time series prediction task.
   - [Gold Price Data](https://www.kaggle.com/datasets/faisaljanjua0555/daily-gold-price-historical-dataset)

## Classification

### Models Used:
- **Support Vector Machine (SVM)**
- **Gradient Boosting Classifier**
- **Multilayer Perceptron (MLP)**

### Results:
- **MLP**
  - Training Accuracy: 98.01%
  - Testing Accuracy: 94.04%
- **SVM (RBF Kernel)**
  - Training Accuracy: 93.09%
  - Testing Accuracy: 92.98%
- **Gradient Boosting Classifier**
  - Training Accuracy: 97%
  - Testing Accuracy: 95%

## Time Series Prediction

### Models Used:
- **Long Short-Term Memory (LSTM)**
- **Bidirectional LSTM (BiLSTM)**
- **Echo State Network (ESN)**

### Results:
1. **LSTM and BiLSTM**
   - LSTM achieved a loss of 0.0013, while BiLSTM achieved a slightly higher loss of 0.0014 on the single-layer architecture.
   - In another comparison, BiLSTM had a loss of 0.0024, while LSTM had a higher loss of 0.0045.

2. **Echo State Network (ESN)**
   - Achieved competitive performance with a reservoir size of 100 and a spectral radius of 0.9.
   - Utilized tanh activation function for non-linearity.

## Key Findings

1. **Classification Models**:
   - MLP outperformed the other models with the highest training and testing accuracy.
   - Gradient Boosting Classifier also performed well, with robust testing accuracy.
   - SVM, while slightly lower in performance, still achieved high accuracy.

2. **Time Series Prediction Models**:
   - LSTM and BiLSTM models demonstrated strong performance with minimal loss.
   - ESN provided competitive results, indicating its potential for efficient and effective time series prediction with appropriate tuning.

## Conclusion

This project showcases the effectiveness of different machine learning models for both classification and time series prediction tasks. The high accuracy and low loss values obtained demonstrate the potential of these models in practical applications.

## Repository Structure

- `datasets/`: Contains the datasets used in the project.
- `classification/`: Code and results for classification models.
- `time_series_prediction/`: Code and results for time series prediction models.
- `results/`: Consolidated results and key findings.

For detailed implementation and further information, refer to the respective directories and files within this repository.

---

Feel free to explore the code and results to understand the methodologies and findings in detail. Contributions and feedback are welcome!

---

**Author:** [Your Name]  
**Date:** May 2024
