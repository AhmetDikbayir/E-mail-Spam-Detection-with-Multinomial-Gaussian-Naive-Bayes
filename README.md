# E-mail-Spam-Detection-with-Multinomial-Gaussian-Naive-Bayes
## Problem Statement 

The main aim of this project is to determine the spam mail.  

## About the Dataset 

I downloaded dataset from Kaggle. The dataset has 5572 row and 5 columns.  

## Preprocessing Data 

For analysis, I just used 2 columns one of them text column and other one is classification column. I deleted other columns while preparing the dataset for analysis. I cahnged the column's name and check the duplicates mesaages. I also, clean the messages from punctuation. Finally, I transform the words into numbers and split the data as a train and test set.  

## Build the Model 

I used Multinomial Gaussian Naive Bayes for determining the spam mails.  

## Evaluate the Model 

I reached 0.99 accuracy on the train dataset and 0.98 f1 score. When it comee to test data, accuracy is 0.95 and f1 score is 0.86. So, I can say that this model can be trustfully determine the mails as a spam or ham.
