# fin_inclusion
Machine learning model to predict if a person has a bank account or not

I first explored the data, i created a code to display the column Name, number of missing values, number of unique values, the unique values and the data type to understand the columns.

During the exploratory data analysis phase i plotted countplots of categories in each categorical column with bank account as hue to study the relationship between the bank accounts and each categorical column.

From the eda, i realised that the data wasn't balanced, there were way more people without bank account than those with bank account. There were almost no factor that greatly affected the bank account column

I then checked for outliers and realised there were outliers so i treated it with the minmaxscaler

I encoded the categorical columns using label encoder

I split the data and did hyperparameter tuning on several models and the best model was XGBoost with an accuracy of 0.892 
