# NYC Airbnb Data Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing the NYC Airbnb Open Data dataset.

The purpose of the project is to prepare the dataset for further data analysis and machine learning.

## Dataset

- Dataset: NYC Airbnb Open Data
- Source: Kaggle
- Original rows: 48,895
- Original columns: 16

## Preprocessing Steps

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked the structure and data types.
3. Handled missing values.
4. Checked duplicate records.
5. Checked and handled relevant outliers.
6. Performed feature engineering.
7. Validated the final dataset.
8. Saved the cleaned dataset.

## Feature Engineering

The following features were created:

- `has_reviews`
- `availability_category`
- `minimum_nights_category`
- `host_activity_level`

## Final Dataset

- Rows: 48,895
- Columns: 19
- Missing values: 0
- Duplicate rows: 0

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Anaconda

## Project Files

```text
NYC-Airbnb-Data-Preprocessing/
│
├── data/
│   ├── raw/
│   └── processed/
│       └── clean_airbnb.csv
│
├── notebook/
│   └── Airbnb_Data_Preprocessing.ipynb
│
├── screenshots/
│
├── DATA_DOCUMENTATION.md
└── README.mdss