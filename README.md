# Stroke risk classification modelling

Model to help classify patients' stroke risk according to a range of reported health metrics. To tune and measure the performance of several modelling techniques, including logistic regression and ensemble algorithms, to determine optimal approach. Finally, to analyse model to determine key variables driving stroke risk.

## Data cleaning

- Conducted mono- and bi-variate analyses to understand and clean the data appropriately.
- Applied SMOTE to handle imbalanced target variable.

## Initial modelling

- Applied logistic regression,random forest, knn, svm, xgboost, lgbm and catboost algorithms to dataset to get feel for relative performance.
- Assessed model performance by comparing core metrics (accuracy, recall, precision, F1, Matthew's Correlation Coefficient).

## Hyperparameter tuning

- Performed model tuning using Optuna
- Used Matthew's Correlation Coefficient to compare models so metric would be sensitive to ratio of TN to FN given distress that could be caused by innaccurate categorisation.

## Model selection and analysis

- Based on performance, proceeded with tuned CatBoost model.
- Employed Shap analysis to determine variables driving stroke risk.
