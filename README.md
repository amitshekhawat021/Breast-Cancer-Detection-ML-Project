
# Breast-Cancer-Detection-ML-Project
a machine learning model to classify breast tumors as malignant or benign using the Breast Cancer Wisconsin dataset.

## Description
The project uses the sklearn load_breast_cancer dataset (569 entries, 30 features) to build a model that distinguishes between malignant and benign tumors. It includes data preprocessing, visualization, model training, and evaluation, with Random Forest achieving the highest accuracy (97.36%).

## Steps

Introduction: Highlights the importance of early breast cancer detection.

Load Data: Imports the dataset with 30 features (e.g., mean radius, texture).

Data Preprocessing: Creates a DataFrame, scales features using StandardScaler.

Exploration: Visualizes target distribution with a histogram.

Model Training:

Tests Logistic Regression, SVM, KNN, Decision Tree, and Random Forest.

Random Forest performs best (97.36% accuracy).

Hyperparameter Tuning: Uses GridSearchCV to optimize Random Forest parameters.

Model Saving: Saves the model using pickle for deployment.

## Learnings

Gained expertise in supervised classification and feature scaling.

Learned to tune models with GridSearchCV and evaluate performance using accuracy and cross-validation.


## Insights
Random Forest outperforms other models with 97.36% accuracy.

Cross-validation confirms robust performance (96.66% average accuracy).

Dataset is clean, with no missing values, enabling reliable predictions.

## Tools

Python: sklearn, pandas, numpy, matplotlib, seaborn, pickle.
