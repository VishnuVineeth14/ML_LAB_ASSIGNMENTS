# Assignment 8 - Human Activity Recognition Dataset Exploration

## Overview
This assignment loads and explores the UCI Human Activity Recognition dataset. The notebook combines the training and test feature data, maps numeric activity labels to activity names, checks dataset structure and null values, and visualizes the activity distribution.

## Notebooks

1. `Ass8.ipynb`
- Loads the UCI HAR feature, label, and activity-name files.
- Combines the training and test partitions for exploratory analysis.
- Displays dataset shapes, sample records, null-value checks, activity counts, and an activity-distribution chart.
- This notebook currently focuses on data loading and EDA; it does not train a machine learning model.

## Dependencies Used in Assignment 8 Notebooks

### Core Environment
- Python 3.x
- Jupyter Notebook

### Python Libraries
- pandas
- matplotlib

## Data Files
The notebook expects the following files under `UCI HAR Dataset/`:
- `train/X_train.txt`
- `train/y_train.txt`
- `test/X_test.txt`
- `test/y_test.txt`
- `activity_labels.txt`

## Notes
- The `UCI HAR Dataset/` directory is not currently included in this folder. Download and place the dataset beside the notebook before running it.
- Run the notebook from inside this folder so the relative paths resolve correctly.
- Quick install command: `pip install pandas matplotlib`.