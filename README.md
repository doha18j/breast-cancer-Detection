Project Overview

This project focuses on classifying breast cancer tumors as malignant or benign using machine learning techniques. The dataset used comes from Breast Cancer Wisconsin (Diagnostic) Data. The model is trained using deep learning with a binary classification approach.

Data Preprocessing

NO missing values.
Applied feature scaling using MinMaxScaler for normalization.
Ensured no data leakage by correctly splitting training and test data.

Model & Performance

The model used is a Deep Neural Network (DNN) with the following configuration:
Loss Function: binary_crossentropy
Activation Function: sigmoid
Optimizer: Adam
Evaluation Metrics: Accuracy, Precision, Recall, F1-score

Performance Results

Accuracy Score: 96.49%

Confusion Matrix:
[[43  2]
 [ 2 67]]

Classification Report:

 precision    recall  f1-score   support

           0       0.96      0.96      0.96        45
           1       0.97      0.97      0.97        69

    accuracy                           0.96       114
   macro avg       0.96      0.96      0.96       114
weighted avg       0.96      0.96      0.96       114


Future Improvements

Implementing hyperparameter tuning for optimal model performance.

Exploring different feature selection techniques to reduce dimensionality.

Deploying the model as a web API for real-world applications.
