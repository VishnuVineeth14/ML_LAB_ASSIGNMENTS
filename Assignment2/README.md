# Assignment 2 - Spam Classification with Naive Bayes and KNN

## Overview
This assignment focuses on binary email classification (spam vs ham) using probabilistic and distance-based models. The notebook includes EDA, preprocessing, model training, hyperparameter tuning, and comparative evaluation.

## Notebook

1. `Experiment_2_Spambase_NaiveBayes_KNN (2).ipynb`
- Performs classification on the Spambase dataset.
- Trains and compares multiple Naive Bayes variants and K-Nearest Neighbors.
- Uses validation/tuning strategies and reports standard classification metrics.

## Dependencies Used in Assignment 2 Notebooks

### Core Environment
- Python 3.x
- Jupyter Notebook

### Python Libraries
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn

### scikit-learn Modules/Algorithms Referenced
- model selection: `train_test_split`, `GridSearchCV`, `RandomizedSearchCV`, `cross_val_score`
- preprocessing: `MinMaxScaler`
- imputation: `SimpleImputer`
- classifiers: `GaussianNB`, `MultinomialNB`, `BernoulliNB`, `KNeighborsClassifier`
- metrics/plots: `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `roc_auc_score`, `confusion_matrix`, `ConfusionMatrixDisplay`, `RocCurveDisplay`, `PrecisionRecallDisplay`

## Data Files
- `spambase_csv.csv`

## Notes
- The notebook is expected to be run from inside this folder to correctly locate `spambase_csv.csv`.
- Quick install command: `pip install numpy pandas matplotlib seaborn scipy scikit-learn`.
