# Code_Alpha_Credit_Scoring_Model
This repository contains a credit scoring model built using machine learning techniques to predict the creditworthiness of individuals based on various features. The model is trained on a dataset containing historical data of individuals' attributes and their creditworthiness status.

#Dataset
The dataset used for training the model (data_test.csv) consists of the following columns:
Language: Language spoken by the individual
Sex: Gender of the individual
Marital: Marital status of the individual
Field: Field of occupation
Region: Region of residence
Changed_phone_number: Indicator for changed phone number
Age: Age of the individual
Years_at_address: Number of years at current address
Years_with_current_employer: Number of years with current employer
Number_of_credit_cards: Number of credit cards held
Credit_card_debt: Amount of credit card debt
Loan_payments: Monthly loan payments
Income: Monthly income
Current_credit_balance: Current credit balance
Maximum_open_credit: Maximum open credit
The target variable to predict is label, which indicates whether the individual is creditworthy or not.

#Preprocessing
Before training the model, the dataset undergoes preprocessing steps including:
Handling missing values by filling numerical values with mean
Encoding categorical features using label encoding
Scaling numerical features using StandardScaler
Splitting the data into training and testing sets

#Models Used
The following machine learning models are used for credit scoring:
Logistic Regression
K-Nearest Neighbors (KNN)
Random Forest

#Training and Evaluation
Each model is trained on the training data and evaluated using accuracy as the metric. Additionally, classification report and confusion matrix are generated to assess model performance.

#Usage
The trained models can be used to predict creditworthiness based on custom input features. Functions are provided to test the model on custom input features and to predict creditworthiness. Example usage is demonstrated in the code.

#Requirements
Python 3
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn




