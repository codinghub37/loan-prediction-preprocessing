# Loan Prediction Data Preprocessing

## Overview

This project focuses on preprocessing and cleaning a loan prediction dataset using Python. The objective is to prepare the dataset for machine learning by handling missing values and improving data quality.

Data preprocessing is one of the most important steps in a machine learning workflow because the quality of input data directly affects model performance.

---

## Dataset

The dataset contains applicant information used for loan approval prediction.

### Features Included

* Gender
* Dependents
* Self Employed Status
* Loan Amount
* Credit History
* Marital Status
* Education
* Applicant Income
* Coapplicant Income
* Loan Status

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Code Implementation

### Data Loading

The dataset was loaded using Pandas:

```python
df = pd.read_csv('loanprediction.csv')
```

### Data Exploration

Initial analysis was performed using:

* head()
* describe()
* info()
* isnull().sum()

These functions helped understand dataset structure, statistics, and missing values.

### Missing Value Handling

Several missing values were identified and treated using appropriate techniques.

#### Categorical Features

Missing values were filled using the most frequent value (Mode):

* Gender
* Dependents
* Self_Employed
* Credit_History

#### Numerical Features

Missing values in LoanAmount were filled using the Median value to reduce the effect of outliers.

### Data Validation

After preprocessing, the dataset was checked again to confirm that missing values had been removed successfully.

---

## Analysis Performed

* Dataset Inspection
* Statistical Summary
* Missing Value Detection
* Missing Value Treatment
* Data Cleaning
* Data Preparation for Machine Learning

---

## Key Outcomes

* Successfully identified missing values.
* Applied suitable imputation techniques.
* Improved dataset quality.
* Prepared data for future machine learning modeling.
* Reduced the impact of incomplete records.

---

## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Missing Value Treatment
* Pandas Data Manipulation
* Data Preparation for Machine Learning
* Python Programming
---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
```
