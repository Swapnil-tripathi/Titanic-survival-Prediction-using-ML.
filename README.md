# Titanic-survival-Prediction-using-ML.
**Introduction:**
The RMS Titanic was one of the most famous ship in the maritime history.It was esteemed for its sheer size,opulence and maiden voyage that ended in disaster
▪The Titanic was built at the Harland and Wolf shipyard in Belfast,Northern Ireland.
▪The ship set sail on its maiden voyage from southampton,England on April 10,1912 with stops in Cherbourg,France,Cobh formerly known as Queenstown,Ireland before heading across the atlantic to New York City.
▪On 15 April,1912 the Titanic struck an iceberg in the North Atlantic Ocean, approximately 600 kilometres south-southeast off the coast of Newfoundland.
▪The collision caused a series of breaches in the ship's hull,leading to its eventual sinking.
▪While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

**Data Description:**
PassengerId: Id of passenger.
Survived : This column indicates whether a passenger survived or not.1 indicates survival and 0 indicates no survival.
Pclass : Its full form is passenger class and it denotes the class.
Name : The name of the passenger.
Sex : Gender of the passenger(Male or Female).
Age : Age of the passenger.
SibSp : Number of siblings or spouses the passenger had on board.
Parch : Number of parent or children the passenger had on board.
Ticket : Ticket number of the passenger.
Fare : Amount paid by the passenger for the ticket.
Cabin : Cabin number where the passenger stayed.
Embarked : The port at which passenger boarded the Titanic(C=Cherbourg,Q=Queenstown,S=Southampton).

**Data Exploration:**
In Data Exploration I will explore the dataset.
data.shape - It denotes shape of the dataset ,shape means number of rows and column in the dataset.
data.info() - Info function gives information about the dataset i.e number of column,count of each column and datatype of each column.
data.describe() - Describe function gives the statistical measure of the data.
data.corr() - It gives the correlation matrix.

**Data Cleaning:**
In data cleaning I am going to check is there any missing value exist in the dataset or not . If any missing value exist then we have 2 options either we can drop the null values using dropna function or we can 
fill the null values using fillna function we can fill the null values with the mean of that particular column.

**Before doing Data Visualization we are going to drop unnecessary columns.**

**Data Visualization:**

In this we are going to analyze each feature of the dataset with the help of various plots using Matplotlib and Seaborn library.

**Label Encoding:**
Label Encoding is a technique used to convert these categorical variables into numerical labels.

**Train Test and Split:**
Splitting the dataset into train dataset and test dataset

**Modelling:**
Using various models like Logistic Regression,Random Forest Classifier,Decision trees and many more to predict the survival of individuals present on the ship.
We will also evaluate each model using the Confusion matrix , Classification report and Accuracy score.
