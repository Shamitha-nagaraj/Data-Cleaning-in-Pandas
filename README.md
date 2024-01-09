# Data-Cleaning-in-Pandas
Data cleaning is a crucial step in the data analysis process, and Pandas is a powerful Python library that provides various tools for data cleaning and manipulation.


1.Handling Missing Values:

Identify missing values using isnull() or info() method.
Fill missing values using fillna() with a specific value or method (e.g., mean, median, forward fill, or backward fill).
Drop rows or columns with missing values using dropna().

2.Removing Duplicates:

Identify and remove duplicate rows using duplicated() and drop_duplicates().

3.Correcting Data Types:

Convert data types using astype() or pd.to_numeric(), pd.to_datetime(), etc.

4.Handling Outliers:

Identify and handle outliers using statistical methods or visualization tools.

5.Text Cleaning:

Remove unnecessary spaces, convert text to lowercase, and handle special characters.

6.Handling Inconsistent Data:

Standardize or correct inconsistent data entries.
[df['column_name'].replace({'incorrect_value': 'correct_value'}, inplace=True)]
