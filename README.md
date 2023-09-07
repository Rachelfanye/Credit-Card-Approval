# Credit-Card-Approval-


## Project Overview

This project aims to build machine learning models to predict the creditworthiness of loan applicants. Given their financial and personal details, the models predict whether an applicant is a 'good' or 'bad' client. This can be invaluable information for financial institutions in assessing loan eligibility.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Data](#data)
4. [Methodology](#methodology)
5. [Results](#results)


## Installation

### Requirements

- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- XGBoost
- SMOTE (for handling class imbalance)

### Setup

```bash
git clone https://github.com/Rachelfanye/Credit-Card-Approval.git
cd Credit-Risk-Prediction
pip install -r requirements.txt
```

## Data

The dataset consists of two main files:

1. `application_record.csv`: Contains the personal details and financial histories of the applicants.
2. `credit_record.csv`: Contains the credit records of the applicants.

## Methodology

1. **Data Preprocessing**
    - Handling Missing Values
    - Outlier Treatment
    - Feature Engineering
  
2. **Exploratory Data Analysis**
    - Univariate Analysis
    - Bivariate Analysis
  
3. **Data Transformation**
    - One-Hot Encoding for Categorical Variables
    - Standardization for Numerical Variables
  
4. **Model Building**
    - Random Forest Classifier
    - Logistic Regression
    - XGBoost Classifier
  
5. **Model Evaluation**
    - F1-Score
    - Precision
    - Recall
  
6. **Handling Class Imbalance**
    - SMOTE
  
7. **Hyperparameter Tuning**
    - Random Search CV

## Results

- Random Forest Classifier: F1 Score = 0.9966, Precision = 0.9964, Recall = 0.9968
- Logistic Regression: F1 Score = 0.7819, Precision = 0.9957, Recall = 0.6436
- XGBoost Classifier: F1 Score = 0.9957, Precision = 0.9957, Recall = 0.9956

