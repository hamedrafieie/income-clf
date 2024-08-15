# Classification Comparison: Scikit-learn vs. H2O 

<img src="https://github.com/user-attachments/assets/4b13dccb-fdc6-4b68-a115-09199f84eae0"  style= "width:50%; height:50%" >

## Overview
This repository contains code and analysis comparing the performance of scikit-learn and H2O libraries for classifying income levels using the adult income dataset.

### Dataset
The adult income dataset contains various features related to individuals’ demographics, education, and occupation. The goal is to predict whether an individual earns more than $50K per year (binary classification).
### Steps Taken
Data Preprocessing:
Cleaned missing values.
Encoded categorical features.

### Model Training:
Trained scikit-learn DecisionTreeClassifier
Trained H2O models H2ORandomForestEstimator


Evaluation Metrics:
F1-score


Results:
Scikit-learn models achieved 70% accuracy.
H2O models achieved 69% accuracy.
