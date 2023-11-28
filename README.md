# Titanic Spaceship Dataset

## Software and Tools Required
1. [Github Account](https://github.com/)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Heroku](https://www.heroku.com/)
4. [GitCli](https://cli.github.com/)

## Overview
The Titanic Spaceship Dataset is a collection of data related to passengers on the Titanic spaceship, which famously sank on its maiden voyage in April 1912. The dataset contains information about the passengers, including their demographics, ticket information, cabin details, and survival status.

## Dataset Source
Kaggle : [Kaggle Titanic competition page](https://www.kaggle.com/c/titanic)

## Files
- **train.csv**: Training dataset containing information about a subset of passengers, including whether they survived or not.
- **test.csv**: Test dataset with similar information but without the survival status.

## Columns
Here are the key columns in the dataset:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, or 3rd)
- **Name**: Passenger's name
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)


## Steps Performed
1. Data Preprocessing : Handling Missing Null values , Finding Correlation between features to prevent Multi collinearity , Handling Categorical Features
2. Model Selection and Training : Tried different models like Logistic Regression , Random Forest Classifier , SV Classifier and KNN , XGBoost Classifier , Neural Networks and found that SVM is getting the best accuracy of 73%.
