# Machine Learning Laboratory Assignments

**Chitraju Vishnu Vineeth**

Machine Learning Laboratory, Semester 5

[GitHub: VishnuVineeth14](https://github.com/VishnuVineeth14)

## Abstract

This repository presents a structured collection of machine learning laboratory
experiments implemented in Python and Jupyter Notebook. The work covers
exploratory data analysis, data preparation, feature selection, supervised
classification, regression, hyperparameter optimization, cross-validation, and
model evaluation. The assignments use healthcare, finance, image, and spam
classification datasets to demonstrate the application of classical machine
learning methods to practical problems.

**Index Terms** - machine learning, exploratory data analysis, classification,
regression, model selection, cross-validation, Jupyter Notebook.

## I. Introduction

The purpose of this repository is to document the implementation and analysis
performed for the Machine Learning laboratory. Each assignment is organized as
an independent experiment containing its notebook, supporting dataset, report
artifacts where applicable, and a local README with execution notes.

The notebooks are intended for educational and reproducible experimentation.
Reported performance should therefore be interpreted in the context of the
preprocessing, train-test split, validation strategy, and dataset used in each
experiment.

## II. Repository Organization

```text
ML_LAB_ASSIGNMENTS/
├── Assignment1/       Foundational classification workflows
├── Assignment2/       Spam classification with Naive Bayes and KNN
├── Assignment3/       Linear and regularized regression analysis
├── Assignment4/       Spam classification with Logistic Regression and SVM
├── Assignment5/       Decision Tree and Random Forest comparison
├── Assignment6/       Ensemble classification with Bagging, Boosting, and Stacking
├── Assignment7/       Customer churn prediction with PCA and model comparison
├── Assignment8/       Human Activity Recognition dataset exploration
├── Assignment9/       Perceptron and MLP comparison
└── README.md          Repository overview
```

## III. Assignment Overview

### A. Assignment 1: Foundational Classification Workflows

[Assignment1](Assignment1/) contains four end-to-end workflows:

- **Diabetes prediction:** preprocessing, feature selection, scaling, and
  classification evaluation on tabular health data.
- **Loan approval prediction:** cleaning, encoding, scaling, feature selection,
  and supervised classification.
- **Iris analysis:** exploratory visualization and feature selection using
  statistical tests.
- **MNIST classification:** clustering-assisted label assignment followed by
  supervised multi-class prediction from image pixels.

The folder includes the corresponding CSV datasets, notebooks, and supporting
technical reports. Detailed notebook and dependency information is available in
the [Assignment1 README](Assignment1/README.md).

### B. Assignment 2: Spam Classification Using Naive Bayes and KNN

[Assignment2](Assignment2/) investigates binary spam-versus-ham classification
using Gaussian, Multinomial, and Bernoulli Naive Bayes models together with
K-Nearest Neighbors. The experiment includes exploratory analysis,
preprocessing, hyperparameter search, and comparison using accuracy,
precision, recall, F1-score, ROC-AUC, and diagnostic plots.

The folder contains the Spambase dataset, the experiment notebook, and a report.
See the [Assignment2 README](Assignment2/README.md) for execution details.

### C. Assignment 3: Regression Analysis

[Assignment3](Assignment3/) compares Linear Regression, Ridge, Lasso, and
Elastic Net for loan amount prediction. The workflow addresses mixed data
types through missing-value handling, one-hot encoding, scaling, and
cross-validation-based hyperparameter tuning. Results are compared using MAE,
MSE, RMSE, and $R^2$.

The source dataset is `test 2.csv`; the notebook currently references
`test.csv`, so the filename must be aligned before execution. Further notes are
provided in the [Assignment3 README](Assignment3/README.md).

### D. Assignment 4: Spam Classification Using Logistic Regression and SVM

[Assignment4](Assignment4/) studies linear and kernel-based decision
boundaries for the Spambase classification task. It evaluates baseline and
tuned Logistic Regression models and compares multiple SVM kernels using
randomized search, cross-validation, and standard classification metrics.

The dataset included in the folder is named `spambase_csv.csv`; the notebook
documentation refers to `spambase.csv`, so the input filename should be
verified before running the notebook. See the [Assignment4 README](Assignment4/README.md).

### E. Assignment 5: Decision Tree and Random Forest on WDBC

[Assignment5](Assignment5/) performs a comparative study of Decision Tree and
Random Forest classifiers using the Wisconsin Diagnostic Breast Cancer (WDBC)
dataset. The workflow includes label preparation, five-fold stratified
cross-validation, model comparison, confusion matrices, precision, recall,
F1-score, and ROC-AUC analysis.

The folder contains `wdbc.data`, `wdbc.names`, the notebook, and the associated
report materials. Detailed information is available in the [Assignment5 README](Assignment5/README.md).

### F. Assignment 6: Ensemble Classification

[Assignment6](Assignment6/) compares Bagging, AdaBoost, and Stacking classifiers
on the Wisconsin Diagnostic Breast Cancer dataset. The workflow uses stratified
cross-validation and evaluates the selected models with classification metrics,
confusion matrices, and ROC/AUC analysis. See the [Assignment6 README](Assignment6/README.md).

### G. Assignment 7: Customer Churn Prediction

[Assignment7](Assignment7/) studies customer churn prediction with standardized
features, PCA-based dimensionality reduction, hyperparameter tuning, and model
comparison. The notebook evaluates nine individual classifiers and a Stacking
ensemble using cross-validation, F1-score, ROC/AUC, and precision-recall analysis.
XGBoost is an additional dependency. See the [Assignment7 README](Assignment7/README.md).

### H. Assignment 8: Human Activity Recognition Exploration

[Assignment8](Assignment8/) loads and explores the UCI Human Activity Recognition
dataset. It combines train and test partitions, maps activity labels, checks
data quality, and plots activity frequencies. This notebook currently contains
data loading and exploratory analysis rather than model training. The required
`UCI HAR Dataset/` directory is not included in the repository; see the
[Assignment8 README](Assignment8/README.md) for the expected files.

### I. Assignment 9: Perceptron and MLP Comparison

[Assignment9](Assignment9/) compares a single-layer Perceptron with a
Multi-Layer Perceptron (MLP) for image classification. The experiment uses
the English handwritten-character dataset, prepares image data for learning,
trains both neural-network approaches, and compares their classification
performance. See the notebook and accompanying report in the assignment
folder for implementation details.

## IV. Software Requirements

The experiments use:

- Python 3.x
- Jupyter Notebook
- NumPy and Pandas for numerical and tabular data processing
- Matplotlib and Seaborn for visualization
- SciPy where required by Assignment 2
- scikit-learn for preprocessing, modeling, validation, and metrics
- XGBoost for Assignment 7

The common dependencies can be installed with:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn xgboost
```

SciPy is required by Assignment 2 and XGBoost is required by Assignment 7; the
remaining assignments primarily use the other packages listed above. Assignment
9 may additionally require the neural-network and image-processing packages
imported by its notebook.

## V. Execution Guidelines

1. Clone or download the repository and open it in Jupyter Notebook or VS Code.
2. Open the relevant assignment folder before running its notebook.
3. Confirm that the dataset filename and relative path match the notebook.
4. Execute the notebook cells in order so that preprocessing, training, and
   evaluation state is initialized consistently.
5. Review the assignment-specific README for dataset, dependency, and filename
   requirements.

The large `Assignment8/UCI HAR Dataset/` directory is excluded through
`.gitignore` to avoid repository size warnings. Download or extract the UCI
HAR dataset locally in that location before running the Assignment 8 notebook.

## VI. Scope and Reproducibility

The repository is an academic record of laboratory implementations. Results
may vary with library versions, random seeds, hardware, and changes to the
input data. For comparable results, use the documented preprocessing steps and
validation procedures and record the software environment used for execution.

## References

[1] F. Pedregosa *et al.*, “Scikit-learn: Machine Learning in Python,” *Journal
of Machine Learning Research*, vol. 12, pp. 2825-2830, 2011.

[2] W. McKinney, *Python for Data Analysis*, 3rd ed. Sebastopol, CA, USA:
O'Reilly Media, 2022.
