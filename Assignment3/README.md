# Assignment 3 - Regression Analysis with Linear and Regularized Models

## Overview
This assignment implements and compares classical regression models for loan amount prediction. It includes careful preprocessing, feature engineering for mixed data types, hyperparameter tuning, and performance comparison using multiple regression metrics.

## Notebook

1. `Experiment_3_Regression_Analysis.ipynb`
- Performs regression modeling with `LinearRegression`, `Ridge`, `Lasso`, and `ElasticNet`.
- Applies missing-value handling, one-hot encoding, scaling, and train/test separation.
- Uses cross-validation-based tuning and compares MAE, MSE, RMSE, and R2.

## Dependencies Used in Assignment 3 Notebooks

### Core Environment
- Python 3.x
- Jupyter Notebook

### Python Libraries
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

### scikit-learn Modules/Algorithms Referenced
- model selection: `train_test_split`, `GridSearchCV`, `RandomizedSearchCV`, `learning_curve`
- preprocessing: `StandardScaler`
- regression models: `LinearRegression`, `Ridge`, `Lasso`, `ElasticNet`
- metrics: `mean_absolute_error`, `mean_squared_error`, `r2_score`

## Data Files
- `test 2.csv`

## Notes
- The notebook currently reads `test.csv`; in this folder the file is named `test 2.csv`. Update the filename in the notebook or rename the CSV before execution.
- Quick install command: `pip install numpy pandas matplotlib seaborn scikit-learn`.
