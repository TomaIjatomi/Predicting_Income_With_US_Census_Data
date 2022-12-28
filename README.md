# Predicting Income - Project Overview
This is a binary classification task to predict if the income of a citizen would be above or below a certain threshold ($50,000) depending on factors presented.

## Resources
* Data Source: The data used is in a csv file from a US Census
* Python Version: 3.9.12
* Packages: pandas, numpy, sklearn, matplotlib, seaborn

## Data cleaning 
* Duplicate records were removed from the dataset.
* Unknown records were handled by labelling as 'unknown' and assigned a numerical value.

## Exploratory Data Analysis ( EDA)
Below are some of the highlights observed on the distributions of data and the value counts for some categorical variables. 

![2022-12-28 (2)](https://user-images.githubusercontent.com/117505903/209791242-b35ed491-4072-4251-84ee-7f81f3da1bb2.png)


![2022-12-28 (3)](https://user-images.githubusercontent.com/117505903/209791489-84da1598-8942-4ed4-9647-1d65009c4237.png)

## Model Building
* Numerical variables were scaled using Standard Scaler.
* Categorical variables were transformed into dummy variables.
* The target variable (Income) was encoded using Label Encoder.
* The data was split into train and tests sets with a test size of 40%.  
* Four (4) models were used: Logistic Regression, Random Forest, K-Nearest Neighbors and Decision Tree.

 ## Model performance.
* The Random Forest Classifier outperformed the other approaches in terms of Accuracy, Precision and Recall.






