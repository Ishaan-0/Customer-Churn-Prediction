# Customer-Churn-Prediction

## Project Overview

This project aims to predict customer churn using machine learning models. The dataset contains customer attributes, such as tenure, contract type, payment method, and internet service type. Various classification algorithms were implemented, including Logistic Regression, Random Forest, SVM, and KNN, to identify customers likely to churn.


### Dataset Features:
    Customer demographics (e.g., Senior Citizen, Partner, Dependents)
    
    Service-related attributes (e.g., Internet Service, Contract Type, Payment Method)
    
    Billing details (e.g., Monthly Charges, Total Charges)
    
    Target variable: Churn (Yes/No)

### Data Preprocessing:
    Handled missing values.
    
    Dropped uncorrelated features (Gender, Senior Citizen).
    
    Applied label encoding and one-hot encoding to categorical variables.
    
    Standardized numerical features using StandardScaler.
    
    Split data into training and testing sets.

### Model Selection & Training:

  Implemented multiple machine learning models-
    Logistic Regression
    
    Random Forest Classifier
    
    Support Vector Machine (SVM)
    
    K-Nearest Neighbors (KNN)
    
    Hyperparameter tuning was performed using GridSearchCV.

### Model Evaluation:

  Evaluated models using-
      Accuracy Score
      Precision, Recall, F1-Score
      Confusion Matrix

### Insights from Data:

    Customers with longer tenure are less likely to churn.
    
    Fibre optic is the most popular internet service category.
    
    Electronic check is the most used payment method.
    
    Gender and senior citizen status had little correlation with churn.

### Usage

To run the model:

    Install dependencies: pip install pandas numpy scikit-learn seaborn matplotlib
    
    Load the dataset: df = pd.read_csv('Customer Data.csv')
    
    Run preprocessing steps.
    
    Train models and evaluate performance.

### Future Improvements

  Implement deep learning models for better predictions.
  
  Add feature engineering techniques to enhance model performance.
  
  Deploy as a web app for real-time churn prediction.

