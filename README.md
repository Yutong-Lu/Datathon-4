# Predictive Modelling for In-Hospital Mortality: A Comparative Analysis
## Authors: Pourya Momtaz, Rachel Yeung, Yutong Lu, Rohini Datta

**Datathon 4, CHL5230, Dalla Lana School of Public Health**

### Introduction
- Aimed to predict in-hospital death using ICU patient data within the first 24 hours of admission.
- Importance: Early mortality prediction aids medical professionals in patient care, resource allocation, and decision-making.

## Data Engineering Process
- Utilized a dataset of 91,713 ICU patient observations with 186 variables.
- Preprocessed data involved handling missing values, scaling, feature selection, and balancing the outcome.
- Split data into training, validation, and test sets for different models.

## Analysis
- Employed XGBoost, logistic regression, and two neural network models for mortality prediction.
- Tuned hyperparameters for XGBoost via grid search and RFECV for logistic regression.
- Evaluated model performance on test sets using metrics like accuracy, recall, and f1-score.

## Findings
- XGBoost showed high overall accuracy but struggled with recall for predicting deaths due to imbalanced outcomes.
- Logistic regression did not effectively predict hospital deaths despite high accuracy and moderate discriminatory power.
- Both neural network models exhibited high accuracy but low recall and f1-scores for mortality prediction.

## Conclusion
- Models demonstrated high accuracy but lacked effectiveness in identifying actual death instances.
- Precision for mortality was unsatisfactory, posing risks for patient outcomes.
- Caution advised in using these models for mortality prediction in ICU patients.

## Resources
- [Google Slides for presentation](https://docs.google.com/presentation/d/1ppLDI1yYeg0nWaywNHUkJP7tVQm9S9Wsg2RspHJs13U/edit#slide=id.p)

## #References
- Included key studies related to ICU mortality prediction and the dataset used.

For a detailed understanding, kindly refer to the full report available in the provided GitHub repository.







