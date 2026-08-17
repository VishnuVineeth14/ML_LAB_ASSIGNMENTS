# Assignment 4 - Binary Classification with Logistic Regression and SVM

## Overview
This assignment studies binary spam/ham classification using both linear and kernel-based classifiers. It includes EDA, preprocessing, baseline modeling, hyperparameter optimization, cross-validation, and comparative analysis.

## Notebook

1. `Experiment_4_Spambase.ipynb`
- Builds a complete classification pipeline on Spambase features.
- Trains baseline and tuned Logistic Regression models.
- Evaluates SVM across kernels, performs randomized hyperparameter search, and compares performance.

## Dependencies Used in Assignment 4 Notebooks

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
- model selection: `train_test_split`, `GridSearchCV`, `RandomizedSearchCV`, `cross_val_score`, `StratifiedKFold`
- preprocessing: `StandardScaler`
- classifiers: `LogisticRegression`, `SVC`
- metrics: `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `confusion_matrix`, `classification_report`

## Data Files
- Notebook expects: `spambase.csv`

## Notes
- Ensure `spambase.csv` is available in this folder before running the notebook.
- Quick install command: `pip install numpy pandas matplotlib seaborn scikit-learn`.
