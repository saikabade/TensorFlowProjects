The solution steps of this problem is listed below:
1) Load the dataset into a dataframe
2) Check if there is any Nan records
3) Find the columns which are impacting the output column 'not.fully.paid' using the df.corr()
4) EDA:- draw a heat map for the correlation matrix and find out the columns that attribute to the change in the 'not.fully.paid'
5) perform the One hot encoding of the categorical column 'purpose'
6) perform scaling on the numeric columns after checking the unique values of each column
7) As the dataset is imbalanced use the undersampling technique to create a modified dataset in which both minority and majority records are equal.
8) Build a ANN with 11 neurons and perform the training
9) note the accuracy and the classification report