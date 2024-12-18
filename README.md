# Titanic - Machine Learning from Disaster

## Overview
This project implements various machine learning models to predict survival on the Titanic. Using passenger data (name, age, gender, socio-economic class, etc.), we build and compare different models to predict which passengers survived the tragic voyage.

## Models Implemented
- Neural Network
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree

## Results
Best performing models on Kaggle's test set:
1. Neural Network: 77.03%
2. Logistic Regression: 76.79%
3. Random Forest: 76.08%
4. KNN: 75.84%
5. XGBoost: 74.16%

## Features Engineering
The following features were processed and engineered:
- Title extraction from names (Mr, Mrs, Miss, etc.)
- Numerical encoding of categorical variables
- Age imputation using mean
- Fare normalization
- Feature scaling to range (-1, 1)
- Weighted importance for key features (Title, Sex, Age)

## Requirements
python
pandas
numpy
scikit-learn
tensorflow
xgboost
seaborn
matplotlib

## Usage
1. Install required packages
2. Uncomment the first two cells in the notebook to download the dataset and unzip it.
3. Run the notebook


## Model Comparison
The project includes a detailed comparison of model performances using:
- Accuracy scores
- Precision and recall metrics
- ROC curves
- Prediction similarity matrix
- Cross-validation scores

## Feature Importance
Key findings on feature importance:
- Passenger class (Pclass)
- Sex
- Age
- Title (extracted from Name)
were the most significant predictors of survival.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Dataset provided by Kaggle
- Inspired by the Titanic: Machine Learning from Disaster competition

