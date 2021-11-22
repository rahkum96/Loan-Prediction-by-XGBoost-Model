# Loan-Prediction-by-XGBoost-Model
Predict the potential loan defaulters 

## Problem statement 
Predict the potential loan defaulters using the Gradient Boosting Method. Following attributes are available:

### About the Data
The risk_flag indicates whether there has been a default in the past or not

## Usage

- Just run `jupyter notebook` in terminal and it will run in your browser.

  Install Jupyter [here](http://jupyter.readthedocs.io/en/latest/install.html) i've you haven't.

- install xgboost by using `pip install xgb` in command line prompt/ anconda  i've you haven't.

## Modules needed:
```
- xgboost
- Pandas
- Scikit-Learn &
- seaborn
```

## Model performance
- I have acheived model accuracy 78%, but the goal is predict the correctly classified who, approved for loan, means we have more focused on recall, (81%)

                 precision   recall  f1-score   support

           0       0.97      0.83      0.90     66329
           1       0.40      0.80      0.54      9271

    accuracy                           0.83     75600
   macro avg       0.68      0.82      0.72     75600
weighted avg       0.90      0.83      0.85     75600

- 82.96% Accurate

## Dataset:



