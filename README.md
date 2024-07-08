Heart Disease Prediction Model

Overview
This project aims to predict the likelihood of heart disease based on various health parameters using machine learning techniques.

Dataset
The dataset used contains information about patients, including their age, sex, cholesterol levels, and other relevant medical indicators.

Model Used
Logistic Regression was employed for this prediction task due to its interpretability and effectiveness in binary classification problems.

Accuracy
Training Data Accuracy: 85.24%
Testing Data Accuracy: 80.49%
Usage
To use the model for prediction:

Provide input data in the format: (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal).
The model will predict whether the person is likely to have heart disease or not.
Dependencies
numpy
pandas
scikit-learn
Files
heart_disease_prediction.ipynb: Jupyter notebook containing the code.
data.csv: Dataset used for training and testing.
How to Run
Install necessary dependencies (numpy, pandas, scikit-learn).
Run heart_disease_prediction.ipynb in a Python environment that supports Jupyter notebooks.
Future Improvements
Explore other machine learning algorithms.
Fine-tune hyperparameters for better accuracy.
