# Data-Cleaning-in-Pandas
Data cleaning is a crucial step in the data analysis process, and Pandas is a powerful Python library that provides various tools for data cleaning and manipulation.


### 1.Handling Missing Values:

Identify missing values using isnull() or info() method.
Fill missing values using fillna() with a specific value or method (e.g., mean, median, forward fill, or backward fill).
Drop rows or columns with missing values using dropna().

       [df['column_name'].fillna(df['column_name'].mean(), inplace=True)]

### 2.Removing Duplicates:

Identify and remove duplicate rows using duplicated() and drop_duplicates().

         [df.drop_duplicates(subset='column_name', keep='first', inplace=True)]
         
### 3.Correcting Data Types:

Convert data types using astype() or pd.to_numeric(), pd.to_datetime(), etc.

         [df['numeric_column'] = pd.to_numeric(df['numeric_column'], errors='coerce')]

### 4.Handling Outliers:

Identify and handle outliers using statistical methods or visualization tools.

### 5.Text Cleaning:

Remove unnecessary spaces, convert text to lowercase, and handle special characters.

### 6.Handling Inconsistent Data:

Standardize or correct inconsistent data entries.

            [df['column_name'].replace({'incorrect_value': 'correct_value'}, inplace=True)]
