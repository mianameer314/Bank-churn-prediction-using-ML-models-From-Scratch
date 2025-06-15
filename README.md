Bank Churn Prediction and Analysis
This repository contains a Jupyter Notebook (Bank churn.ipynb) that performs an exploratory data analysis (EDA) and builds a churn prediction model using a neural network on a bank customer dataset.

Dataset Description
The dataset focuses on bank customers and their characteristics, including whether they have churned (exited the bank). The features are as follows:

Customer ID: A unique identifier for each customer.

Surname: The customer's surname or last name.

Credit Score: A numerical value representing the customer's credit score.

Geography: The country where the customer resides (e.g., France, Spain, Germany).

Gender: The customer's gender.

Age: The customer's age.

Tenure: The number of years the customer has been with the bank.

Balance: The customer's account balance.

NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card).

HasCrCard: Whether the customer has a credit card (binary: 0 or 1).

IsActiveMember: Whether the customer is an active member (binary: 0 or 1).

EstimatedSalary: The estimated salary of the customer.

Exited: Whether the customer has churned (Target Variable, binary: 0 for not churned, 1 for churned).

Aim and Objective
The primary objectives of this project are:

Complete Exploratory Data Analysis (EDA): To understand the dataset's characteristics, identify patterns, and visualize relationships between variables, especially in relation to customer churn.

Churn Prediction using Neural Network: To build and evaluate a neural network model to predict whether a customer will churn (Exited = 1).

Analysis Highlights & Observations
The initial exploratory data analysis revealed several key insights:

Credit Score:

Average credit score is approximately 656, with a standard deviation of 80.1.

Scores range from 350 to 850, with most customers falling between 597 and 710.

Age:

The average age of customers is around 38 years, with a standard deviation of 8.87.

Ages range from 18 to 92, and most customers are between 32 and 42 years old.

Balance:

The average balance is about 55,478, but the distribution is right-skewed, indicating many customers have a zero balance.

Balances range from 0 to 250,898.09.

Number of Products (NumOfProducts):

Customers, on average, use 1.55 products, with most having 1 or 2 products.

Has Credit Card (HasCrCard):

Approximately 75.4% of customers possess a credit card.

Active Membership (IsActiveMember):

The distribution between active and inactive members is nearly even, with about 49.8% being active.

Estimated Salary:

The average estimated salary is around 112,575, with a standard deviation of 50,292.

Salaries range from 11.58 to 199,992.48.

Churn (Exited):

About 21.2% of the customers in the dataset have churned. This indicates an imbalanced dataset, where the majority of customers have not churned.

Tenure:

Average tenure is 5 years, ranging from 0 to 10 years.

Data Preprocessing
The notebook includes steps for data preprocessing, such as:

Loading train.csv and test.csv datasets.

Checking for missing values (it was found that there are no missing values in the dataset).

Summary statistics of the numerical features.

(Further steps like encoding categorical variables, scaling numerical features, and splitting the data for model training are expected to be present in the full notebook for the neural network implementation.)

How to Run the Notebook
To run this notebook, ensure you have Jupyter Notebook or JupyterLab installed.

Clone the repository (if applicable) or download the notebook and data files.

Install necessary libraries:

pip install pandas numpy matplotlib seaborn plotly scikit-learn tensorflow keras warnings

Open the notebook:

jupyter notebook "Bank churn.ipynb"

Run all cells within the notebook to see the EDA, preprocessing steps, and the neural network model's performance.
