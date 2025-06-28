#  Water Quality Classification using Machine Learning

This project applies supervised machine learning techniques to classify water potability (drinkable or not) based on various chemical attributes such as pH, hardness, solids, and chloramines.

## 📂 Project Description

Access to safe drinking water is essential for public health. This project investigates the use of different machine learning classifiers to predict whether a water sample is potable, using a dataset of chemical properties. The work was completed as part of the CS522 course project.

##  Dataset

The dataset includes the following features:

- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic_carbon
- Trihalomethanes
- Turbidity
- Potability (target)

Missing values are handled using imputation, and the dataset is balanced using resampling techniques.

##  Models Used

- **Random Forest Classifier**
- **XGBoost Classifier**
- **LightGBM Classifier**

Hyperparameter tuning was performed using `GridSearchCV`.

##  Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

The best-performing model achieved an accuracy of approximately **85%**.

##  How to Run

1. Install required libraries:
   ```bash
   pip install xgboost lightgbm scikit-learn pandas numpy
