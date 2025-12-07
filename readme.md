# Project Dependencies & Installation Guide

This project requires Python 3.8+ and the libraries listed below for data processing, modeling, visualization, and handling class imbalance.

---

## Required Python Packages

### Core Data & Visualization
- pandas
- numpy
- matplotlib
- seaborn

### Data Cleaning
- skimpy — Used for cleaning and standardizing column names (clean_columns)
- 
### Scikit-Learn: Preprocessing & Pipelines
- scikit-learn
  - SimpleImputer
  - IterativeImputer
  - StandardScaler
  - RobustScaler
  - OneHotEncoder
  - ColumnTransformer
  - Pipeline (as SklearnPipeline)
  - train_test_split
  - Evaluation metrics (accuracy_score, precision_score, recall_score, f1_score, roc_auc_score)
  - confusion_matrix & ConfusionMatrixDisplay
  - BaseEstimator, TransformerMixin

### Class Imbalance Handling
- imblearn (imbalanced-learn)
  - SMOTE
- collections.Counter

### Machine Learning Models
- DecisionTreeClassifier
- RandomForestClassifier
- LogisticRegression
- KMeans
- RandomForestRegressor

---

## Installation

You can install all dependencies using:

pip install pandas numpy matplotlib seaborn skimpy scikit-learn imbalanced-learn
