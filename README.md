Titanic Survival Prediction

This project is a machine learning solution to the Titanic dataset from Kaggle, focused on predicting passenger survival using available features such as age, gender, and passenger class.

Project Overview

The Titanic dataset is a classic binary classification problem. The objective is to build a model that predicts whether a given passenger survived or not.

Dataset Description

The dataset includes the following columns:

PassengerId: Unique identifier for each passenger

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Passenger name

Sex: Gender

Age: Age of the passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Fare paid for the ticket

Cabin: Cabin number

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Target variable (0 = Did not survive, 1 = Survived)

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook 

Project Workflow

Data Cleaning

Handling missing values

Dropping or imputing irrelevant columns

Exploratory Data Analysis (EDA)

Understanding distributions and relationships

Visualizing patterns in the data

Feature Engineering

Converting categorical variables to numeric

Creating new features such as family size

Model Building

Logistic Regression

Model Evaluation

Accuracy score

Confusion matrix

Cross-validation

Results

Best accuracy achieved: 0.81

Final model used: Logistic regression
