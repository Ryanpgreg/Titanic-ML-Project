# Titanic-ML-Project
Machine learning project predicting Titanic passenger survival using Python, pandas, and scikit-learn. Includes full data preprocessing, model training, and evaluation pipeline.

## Project Overview

The goal is to build a model that predicts the `Survived` outcome (1 = survived, 0 = did not survive) based on passenger characteristics such as age, class, and sex.

### Key Steps
1. Data Loading — Imported `train.csv`, `test.csv`, and `gender_submission.csv`
2. Data Cleaning — Filled missing values with median and mode
3. Feature Encoding — Converted categorical features like `Sex` and `Embarked` into numerical values
4. Model Training — Used Logistic Regression to train and validate survival predictions
5. Evaluation — Measured accuracy and classification metrics on a validation set
6. Prediction — Generated survival predictions for the test set and saved them as `submission.csv`

## Model and Performance

**Algorithm:** Logistic Regression  
**Libraries:** pandas, numpy, scikit-learn, seaborn, matplotlib  

Typical accuracy achieved: around 80% on validation data.

## Dataset Description

- **train.csv** — Training data with labels (`Survived`)
- **test.csv** — Test data without labels
- **gender_submission.csv** — Sample submission file for Kaggle format

Key features include:

| Feature | Description |
|----------|--------------|
| `Pclass` | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) 
| `Sex` | Passenger gender 
| `Age` | Passenger age in years 
| `SibSp` | Number of siblings/spouses aboard 
| `Parch` | Number of parents/children aboard 
| `Fare` | Ticket fare 
| `Embarked` | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) 

## Packages

- NumPy / Pandas — Data wrangling  
- Matplotlib / Seaborn — Visualization  
- Scikit-Learn — Machine learning modeling  
