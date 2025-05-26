# Day_1
I HAVENT DOWNLOADED THE DATASET INSTEAD I DIRECTLY USED IT FROM SEABORN LIBRARY IN GOOGLE COLAB
Here are 6 steps describing what i have done in the code:

1.   Loaded the Titanic dataset using seaborn and explored its initial state, including checking for missing values, unique values, shape, and data types.
2.   Handled missing values in the 'age' column by filling them with the mean of the existing ages, and filled missing values in 'embarked' and 'embark_town' with the most frequent values ('S' and 'Southampton' respectively).
3.   Removed the 'deck' column from the dataset as it had a large number of missing values.
4.   Performed one-hot encoding on categorical columns ('sex', 'embarked', 'class', 'who', 'adult_male', 'embark_town', 'alive', 'alone') to convert them into a numerical format, dropping the first category to avoid multicollinearity.
5.   Applied Min-Max normalization and then Z-score standardization to several numerical columns to scale their values.
6.   Visualized potential outliers in the numerical columns using box plots and then implemented and applied a function to remove outliers from the 'age' and 'fare' columns using the Interquartile Range (IQR) method.
