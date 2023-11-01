# Datathon 4: Mortality Prediction Using ML (Low-Fidelity Submission)

**Team 18: Pourya Momtaz, Rachel Yeung, Yutong Lu, Rohini Datta**

## Research Questions
- Can we predict mortality probability (in-hospital deaths) and compare prediction accuracy using traditional tree-based methods vs neural networks?

- Can we predict binary mortality (in-hospital deaths) and compare prediction accuracy using logistic regression vs neural networks?

## Steps 
Data Exploration and Preprocessing:
- To explore the dataset and gain an understanding, preliminary descriptive statistics will be performed
- Data will be visualized using appropriate methods (eg. box-plots, histograms, etc.)
- Data will be cleaned up, included imputation for missing data and recoding of necessary variables
- Additional steps include removal of outliers and collapsing of categories, if necessary

Question 1:

Tree-based

1. Hyperparameters tuning for xgboost model
2. Fit xgboost model

Neural Networks

1. Try each activation function (e.g. softmax)
2. Compare the performance of neural nets and xgboost

Question 2:

Logistic Regression (Rohini)

1. Check the assumptions for logistic regression
2. Feature selection using Recursive Feature Elimination with Cross-Validation (RFECV)

Neural Networks

1. Use sigmoid and/or hyperbolic tangent functions
2. Training loop with loss function
3. Check if data fits correctly using training and validation accuracy
4. Compare the performance of neural nets and logistic regression
