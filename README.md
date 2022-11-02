# Cleaning-Data
I completed this project in both Python and R. 
In this project, I worked to clean a raw CSV data file to create a dataset that could be later analyzed. Steps I used included: 
-	Duplicates: I first looked for duplicated rows in the data. I determined that the dataset had no duplicate rows. 
-	Null Values: There were many columns that had null values in the dataset. I first visualized these using a missingno graph and then determined the distribution of data for all numeric columns with missing data. I used the median or mean to impute the data in columns with missing numeric values. For categorical/non-numeric missing values I used the mode to impute the data. 
-	Outliers: I created boxplots to check for outliers in all numeric columns. I determined that most outliers were valid. But for invalid outliers, I imputed the data with the median. 
-	Re-Express Categorical Variables: I used label encoding to change dichotomous binary columns to numeric values. Using ordinal encoding I changed the education column to also be represented with numeric values.
- Principal Component Analysis (PCA): I combined columns into the most important principal components using PCA. 
