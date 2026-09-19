# Assignment 6 - Ensemble Classification with Bagging, Boosting, and Stacking

## Overview
This assignment compares ensemble learning strategies for classifying benign and malignant tumors in the Wisconsin Diagnostic Breast Cancer dataset. The notebook covers exploratory analysis, stratified data splitting, cross-validation, model evaluation, confusion matrices, and ROC/AUC analysis.

## Notebooks

1. `Experiment_7.ipynb`
- Loads and prepares the Wisconsin Diagnostic Breast Cancer dataset.
- Tunes and compares Decision Tree Bagging, AdaBoost, and a Stacking ensemble.
- Uses SVM, Gaussian Naive Bayes, and Decision Tree base estimators with Logistic Regression as the stacking meta-estimator.
- Reports accuracy, precision, recall, F1-score, classification reports, confusion matrices, and ROC/AUC results.

## Dependencies Used in Assignment 6 Notebooks

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
- model selection: `train_test_split`, `StratifiedKFold`, `cross_val_score`, `GridSearchCV`
- preprocessing: `LabelEncoder`, `StandardScaler`
- base classifiers: `SVC`, `GaussianNB`, `DecisionTreeClassifier`, `LogisticRegression`
- ensemble classifiers: `BaggingClassifier`, `AdaBoostClassifier`, `StackingClassifier`
- metrics/plots: `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `classification_report`, `confusion_matrix`, `roc_curve`, `auc`

## Data Files
- `wdbc.data`
- `wdbc.names`

## Notes
- Run the notebook from inside this folder so the relative path to `wdbc.data` resolves correctly.
- Quick install command: `pip install numpy pandas matplotlib seaborn scikit-learn`.