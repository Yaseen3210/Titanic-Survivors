Titanic Passengers 

This project aims to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, class, and others. It leverages machine learning techniques to build a classification model using the Titanic dataset.

## Project Overview

The Titanic disaster, which occurred in 1912, remains one of the most infamous maritime tragedies in history. The goal of this project is to predict whether a passenger survived the sinking based on the available dataset of passengers' information.

# Dataset
The dataset used for this project is the Titanic dataset, which contains information about the passengers aboard the Titanic.
### Features:
- **PassengerId**: Unique ID for each passenger.
- **Pclass**: The class of the ticket the passenger purchased (1 = First class, 2 = Second class, 3 = Third class).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: The ticket number.
- **Fare**: Amount of money the passenger paid for the ticket.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- **Survived**: Whether the passenger survived (0 = No, 1 = Yes).

### Data Source:
The dataset is available publicly from Kaggle:  
[https://www.kaggle.com/c/titanic](https://www.kaggle.com/c/titanic)

## Project Workflow

1. **Data Loading**: Import the dataset and explore the structure of the data.
2. **Data Preprocessing**: Handle missing values, encode categorical features, and normalize/scale numerical features as necessary.
3. **Exploratory Data Analysis (EDA)**: Visualize and analyze the relationships between features, particularly focusing on survival rates.
