# Udacity Data Scientist Nanodegree Capstone Project

All the code and report for my Udacity Data Scientist Nanodegree Capstone project are included in this repository.

## Starbucks Capstone Challenge: 
The objective of this project is to utilize Starbucks app user data to predict the effectiveness of offers.

### 1. Installations
The programming language used for this project is Python, and Jupyter Notebook on Anaconda was used as the development environment. The project required several Python packages including:

1- pandas
2- json
3- matplotlib
4- numpy
5- sklearn.model_selection (train_test_split module)
6- sklearn.preprocessing (StandardScaler, PolynomialFeatures)
7- from sklearn.tree (DecisionTreeClassifier,DecisionTreeRegressor)
8- sklearn.ensemble (RandomForestClassifier)
9- sklearn.metrics (mean_squared_error,classification_report)
10- sklearn.linear_model (Ridge)
11- time
12- sklearn.model_selection (GridSearchCV)
12- math

### 2. Project Motivation
As the Capstone project of my Data Scientist Nanodegree with Udacity, I had the opportunity to participate in the Starbucks Capstone Challenge.
This challenge involved working with simulated data provided by Udacity that emulates customer behavior on the Starbucks rewards mobile app.

In this project, I use the data to answer 2 business questions:

	a. What are the main drivers of an effective offer on the Starbucks app?
	b. Could the data provided, namely offer characteristics and user demographics, predict whether a user would take up an offer?
To address the two business questions, three distinct models were developed using the data related to the three offer types available in the simulated data, namely Buy One Get One Free (BOGO), Discount (discount with purchase), and Informational (providing product information).
As a brief summary of my findings:
- For Question 1, All three models indicated that the member's tenure is the most significant predictor of offer effectiveness. However, additional research would be required to determine the average tenure days that would result in an effective BOGO offer.

- For Question 2,Using three separate models to predict the effectiveness of each offer type produced highly accurate results for two of the models, with 82.83% accuracy for BOGO and 87.35% accuracy for discount. However, the accuracy of the third model, which predicted the effectiveness of informational offers, was slightly lower at 75.3%. Nevertheless, in a business setting, a 75% accuracy rate could be considered acceptable, especially since informational offers do not incur any cost to inform users about a product. Additionally, an accuracy rate of 80% or higher is generally acceptable in a business setting for showing offers to people, even if the model misclassifies a few, since the overall revenue increase may justify the few mistakes.

### 3. File Descriptions
The report for this project is titled 'Starbucks Capstone Challenge - Using Starbucks app user data to predict effective offers.ipynb' and is one of four files included in this repository. The project utilizes data from three files, namely portfolio.json, profile.json, and transcript.json, which are also included in the repository.

### 4. Licensing, Authors.

The data used in this coding project was supplied by Udacity.
