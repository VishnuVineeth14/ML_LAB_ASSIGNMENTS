# Assignment 1 - Foundational Classification Workflows

## Overview
This assignment contains four end-to-end machine learning notebook workflows covering structured tabular classification and image-based digit modeling. The notebooks follow a practical pipeline: dataset loading, exploratory data analysis (EDA), preprocessing, feature handling, model training, and evaluation.

## Notebooks

1. `Diabetes_Prediction_ML_Workflow.ipynb`
- Builds a diabetes prediction workflow on a tabular dataset.
- Includes EDA, missing-value handling, scaling, feature selection, and classification evaluation.

2. `Loan_Approval_ML_Workflow.ipynb`
- Implements a loan approval prediction pipeline.
- Covers data cleaning, EDA, encoding/scaling, feature selection, train/test split, and model evaluation.

3. `iris_dataset.ipynb`
- Performs supervised learning exploration on the Iris dataset.
- Includes data understanding, visual analysis, preprocessing, and feature selection using statistical tests.

4. `mnist_ml_workflow (1).ipynb`
- Works with MNIST image pixels in CSV format.
- Uses clustering for label assignment and then trains a supervised classifier for multi-class prediction.

## Dependencies Used in Assignment 1 Notebooks

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
- preprocessing: `LabelEncoder`, `StandardScaler`
- imputation: `SimpleImputer`
- feature selection: `SelectKBest`, `chi2`, `f_classif`
- model selection: `train_test_split`
- classifiers: `LogisticRegression`, `KNeighborsClassifier`, `RandomForestClassifier`, `MiniBatchKMeans`
- metrics: `accuracy_score`, `classification_report`, `confusion_matrix`

## Data Files
- `diabetes_prediction_dataset.csv`
- `loan_approval_dataset.csv`
- `iris.csv` (plus scikit-learn built-in Iris loader in notebook)
- `mnist_dataset.csv`

## Notes
- Keep dataset files in this folder before running notebooks so relative paths resolve correctly.
- If running in a fresh environment, install dependencies using `pip install numpy pandas matplotlib seaborn scikit-learn`.
