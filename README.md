# Data-Analysis Internship Task 1
Internship
I have done data cleaning and data preprocessing in a raw dataset named 'Customer Personality Analysis' obtained from kaggle.
There were 24 missing values in the income column which is replaced with the most frequent value using simple imputer function.
Text data is standardized which means the text data is coverted into lowercase and spaces were removed using .str.lower() and .str.replace('_', '') and .str.strip() method.
All the column names were also converted into lowercase and spaces were removed. This also comes under standardization of text.
Data types were identified by using data.dtypes function.
int data type in Year_Birth column was converted into datetime64[ns] format.
All the duplicates were removed using .drop_duplicates() function.
