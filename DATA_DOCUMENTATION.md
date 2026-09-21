# NYC Airbnb Data Preprocessing

## 1. Dataset

Dataset: NYC Airbnb Open Data

Source: Kaggle

Original dataset:
- Rows: 48,895
- Columns: 16

The dataset contains information about Airbnb listings in New York City, including price, room type, location, reviews, minimum nights, and availability.

## 2. Data Cleaning

### Missing Values
Missing values were checked and handled during preprocessing.

Final missing values: 0

### Duplicate Values
Duplicate rows were checked.

Final duplicate rows: 0

### Data Types
The data types of all columns were checked and corrected where required.

## 3. Outlier Treatment

The IQR method was used to identify potential outliers.

### Price
Extreme price values were capped at 334.

### Minimum Nights
Values above 365 days were capped at 365.

### Number of Reviews
High review counts were retained because they can represent legitimate listings.

### Availability
No outliers were found using the IQR method.

## 4. Feature Engineering

Four new features were created:

1. `has_reviews` – indicates whether a listing has reviews.
2. `availability_category` – groups availability into Low, Medium, and High.
3. `minimum_nights_category` – groups minimum stay into different categories.
4. `host_activity_level` – groups hosts according to the number of listings they manage.

## 5. Final Dataset

Final rows: 48,895

Final columns: 19

Missing values: 0

Duplicate rows: 0

The cleaned dataset was saved as:

`clean_airbnb.csv`

## 6. Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Anaconda

## 7. Conclusion

The NYC Airbnb dataset was successfully cleaned and preprocessed. Missing values and duplicate records were handled, relevant outliers were treated, and new features were created for further analysis.s