# Assignment 5 - Decision Tree vs Random Forest on WDBC

## Overview
This assignment presents a comparative classification study between Decision Tree and Random Forest on the Wisconsin Diagnostic Breast Cancer dataset. The notebook includes data preparation, cross-validation-based hyperparameter comparison, final model evaluation, and ROC/AUC analysis.

## Notebook

1. `Experiment_5.ipynb`
- Loads and preprocesses the WDBC dataset.
- Tunes Decision Tree and Random Forest configurations using 5-fold cross-validation.
- Compares final models with confusion matrices, precision/recall/F1, and ROC-AUC.

## Dependencies Used in Assignment 5 Notebooks

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
- classifiers: `DecisionTreeClassifier`, `RandomForestClassifier`
- model selection: `train_test_split`, `StratifiedKFold`, `cross_val_score`
- preprocessing: `LabelEncoder`
- metrics: `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `confusion_matrix`, `roc_curve`, `auc`, `classification_report`

## Data Files
- `wdbc.data`
- `wdbc.names`
- `breast+cancer+wisconsin+diagnostic/wdbc.names`

## Notes
- The notebook uses `wdbc.data` in this folder and internally defines column names.
- Quick install command: `pip install numpy pandas matplotlib seaborn scikit-learn`.
