### -------------------------------------------------------------------------------------------------------
# Logistic Regression - Titanic Survival
### -------------------------------------------------------------------------------------------------------
### Logistic Regression:
- an **algorithm**:
    - based on **Supervised Learning**
    - to solve **Classification problems**
    - where machines **learn with supervision**
    - **input data are labeled** and **expected output data is known**
    - used **to predict (classify) a categorical (qualitative) output value (y) based on given input variable(s) (x)**
    - where with evaluating the **logistic relationship between categorical dependent output variable (y) and independent input variable(s) (x)**, we try to identify **to which category, the new observation belongs to**
- **Classification analysis** is a **predictive modeling technique**

### Types of Logistic Regression based on the outcome of categorical dependent variable (y):
- **Binomial (Binary) Logistic Regression** - dependent variable can have only 2 possible types “0” or “1” (Yes / No)
- **Multinomial Logistic Regression** - dependent variable can have 3 or more possible **unordered** types (types having no quantitative significance) (e.g. Type A, Type B, Type C)
- **Ordinal Logistic Regression** - dependent variable can have 3 or more possible **ordered** types (types having a quantitative significance) (e.g. Poor, Good, Excellent)

### Examples of Logistic Regression problems:       
- Spam vs. “Ham” emails
- Loan default
- Disease diagnosis

### -------------------------------------------------------------------------------------------------------
### Project Objective: Predicting survived or deceased passengers on Titanic
Create a model that allows to put in a few features about passangers and returns back a prediction (classification) of survived or deceased passengers on Titanic. Information about the passangers is in the dataset 'Titanic_train.csv'. The Titanic dataset is from Kaggle (https://www.kaggle.com/c/titanic) and "semi-cleaned" version of the dataset will be used.

The Titanic dataset contains the following columns:
- **PassengerId** - An unique index for each passenger (it starts from 1 and increments by 1 for every new passenger)
- **Survived** - Shows if the passenger survived or not (0 = Deceased (Not Survived) and 1 = Survived)
- **Pclass** - Ticket class (1 = First class ticket, 2 = Second class ticket and 3 = Third class ticket)
- **Name** - Passenger's name (name also contain title: "Mr" for man, "Mrs" for woman, "Miss" for girl and "Master" for boy)
- **Sex** - Passenger's sex (it's either Male or Female)
- **Age** - Passenger's age in years ("NaN" values indicates that the age of that particular passenger has not been recorded)
- **SibSp** - Number of siblings or spouses travelling with each passenger
- **Parch** - Number of parents of children travelling with each passenger
- **Ticket** - Ticket number
- **Fare** - How much money the passenger has paid for the travel journey
- **Cabin** - Cabin number of the passenger ("NaN" values indicates that the cabin number of that particular passenger has not been recorded)
- **Embarked** - Port from where the particular passenger was embarked/boarded (C = Cherbourg, Q = Queenstown, S = Southampton)

### -------------------------------------------------------------------------------------------------------
### Table of Contents:
1. File Descriptions
2. Technologies Used
3. Structure of Notebook
4. Executive Summary

#### 1. File Descriptions
- Logistic Regression - Titanic_Survival.ipynb
- Titanic_train.csv and Titanic_test.csv
- README.md

#### 2. Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn

#### 3. Structure of Notebook
1. Import the Libraries
2. Load the Data
3. Exploratory Data Analysis
    - 3.1 Check out the Data
    - 3.2 Data Visualization
4. Data Preprocessing and Feature Engineering
    - 4.1 Identify the variables
    - 4.2 Dealing with Missing values
    	- 4.2.1 Dealing with Missing values in Columns
       	- 4.2.2 Dealing with Missing values in Rows
    - 4.3 Dealing with the Non-numerical features
5. Train and Test the Logistic Regression model
    - 5.1 Split the columns
    - 5.2 Split the data into Training dataset and Testing dataset
    - 5.3 Create the Logistic Regression model
    - 5.4 Train / fit the Logistic Regression model
    - 5.5 Predictions from the model on Testing data
    - 5.6 Evaluate the model on Testing data
    	 - 5.6.1 Classification report
    	 - 5.6.2 Confusion matrix
    	 - 5.6.3 Interpreting of Coefficient of the features
    - 5.7 GridSearchCV
         - 5.7.1 Create the Grid of parameters
         - 5.7.2 Create the GridSearchCV model (Re-create the Logistic Regression model)
         - 5.7.3 Train / fit the GridSearchCV model (Re-train / Re-fit the Logistic Regression model)
         - 5.7.4 Predictions from the GridSearchCV model (Re-predictions from the Logistic Regression model) on Testing data
         - 5.7.5 Evaluate the GridSearchCV model (Re-evaluate the Logistic Regression model) on Testing data
         	- 1. Classification report
         	- 2. Confusion matrix

#### 4. Executive Summary
TBA
