# Credit Risk Classification

## Overview of the Analysis

The purpose of the analysis was to develop machine learning models to predict loan statuses based on financial information. The dataset contained various financial features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The primary objective was to predict the loan status, which could be categorized as 'Fully Paid' or 'Charged Off'. Understanding the distribution and characteristics of loan statuses within the dataset was crucial for model development. 

The analysis went through several stages of the machine learning process, starting with data preprocessing, which involved handling missing values, encoding categorical variables, and scaling numerical features. Then, models were selected and trained using techniques such as Logistic Regression. Model evaluation was performed to assess performance using metrics like accuracy, precision, recall, and F1-score. Finally, model tuning was conducted to optimize performance if necessary. Throughout the analysis, methods such as train-test split, confusion matrix, and classification report were utilized to ensure thorough evaluation and interpretation of model performance.

## Results

Machine Learning Model 1:
- Accuracy: 98%
- Precision for class 0: 0.96
- Precision for class 1: 0.85
- Recall for class 0: 0.99
- Recall for class 1: 0.91


## Summary

- Among the evaluated models, Model 1 performs the best, with high accuracy, precision, and recall scores for both classes. It particularly excels in identifying instances of loan defaults (class 1).
- Performance may depend on the problem context, with a balance needed between predicting 'Fully Paid' and 'Charged Off' loans. In this case, correctly predicting 'Charged Off' loans (class 1) might be more crucial.
- Therefore, Model 1 is recommended for predicting loan statuses, considering its balanced performance and importance in identifying loan defaults accurately.
