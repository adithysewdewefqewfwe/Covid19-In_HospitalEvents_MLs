# Covid19-In_HospitalEvents_MLs
Predicting Critical In-Hospital Events in COVID-19 Patients Using Machine Learning Methods

# COVID-19 Critical Event Prediction

This repository contains code and documentation for predicting critical in-hospital events in COVID-19 patients using various machine learning models.

## Project Structure

- `data/`: Data files.
- `code/`: Scripts for data preprocessing, model training, and evaluation.
- `results/`: Generated figures and tables.
- `report/`: Final project report.

## Requirements

- Python 3.x
- Libraries:pandas, numpy, sklearn.model_selection (train_test_split, GridSearchCV, cross_val_score), sklearn.preprocessing (StandardScaler, SplineTransformer),
- sklearn.linear_model (LogisticRegression), sklearn.svm (SVC), sklearn.metrics (roc_auc_score, brier_score_loss, roc_curve, accuracy_score, precision_score,
- recall_score, f1_score, classification_report), sklearn.pipeline (Pipeline, ColumnTransformer), matplotlib.pyplot, seaborn

## How to Run

1. Clone the repository.
2. Ensure all required libraries are installed.
3. Place the dataset in the `data/` folder.
4. Run the scripts in the following order:
   - `code/data_preprocessing.py`
   - `code/model_training.py`
   - `code/model_evaluation.py`

## Notes


- The code was tested on Python 3.10.12.

## Adithya Devan


