# Assignment 7 - Customer Churn Prediction with PCA and Model Comparison

## Overview
This assignment develops a customer churn classification workflow using dimensionality reduction and a broad comparison of supervised learning models. The notebook includes exploratory analysis, feature standardization, PCA variance analysis, hyperparameter tuning, cross-validation, and evaluation with classification and ranking metrics.

## Notebooks

1. `ass7 (2).ipynb`
- Loads and explores the customer churn dataset, including class distribution and missing-value checks.
- Compares models with and without PCA-based dimensionality reduction.
- Tunes SVM, Gaussian Naive Bayes, KNN, Logistic Regression, Decision Tree, Random Forest, AdaBoost, Gradient Boosting, and XGBoost models.
- Adds a Stacking classifier using SVM, KNN, and Decision Tree base estimators with Logistic Regression as the meta-estimator.
- Reports accuracy, F1-score, confusion matrices, ROC/AUC, precision-recall curves, and fold-level stability.

## Dependencies Used in Assignment 7 Notebooks

### Core Environment
- Python 3.x
- Jupyter Notebook

### Python Libraries
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

### scikit-learn Modules/Algorithms Referenced
- model selection: `GridSearchCV`, `StratifiedKFold`
- preprocessing: `StandardScaler`
- dimensionality reduction: `PCA`
- classifiers: `SVC`, `GaussianNB`, `KNeighborsClassifier`, `LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`, `AdaBoostClassifier`, `GradientBoostingClassifier`, `StackingClassifier`
- metrics/plots: `accuracy_score`, `f1_score`, `confusion_matrix`, `roc_curve`, `roc_auc_score`, `precision_recall_curve`

## Data Files
- `customer_churn_dataset.csv`

## Notes
- Run the notebook from inside this folder so the relative dataset path resolves correctly.
- The notebook installs XGBoost in an early cell if it is not already available.
- Quick install command: `pip install numpy pandas matplotlib seaborn scikit-learn xgboost`.