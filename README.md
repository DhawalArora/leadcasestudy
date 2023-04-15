# README for Leads Case Study

This repository contains the code and data for a case study on improving lead conversion rate for X Education, a company that markets courses online. The case study involves building a logistic regression machine learning model using Python and Jupyter Notebook.

Problem Statement:
The lead conversion rate of X Education is poor, and the company wants to understand which data variables may play an important role in increasing the lead conversion rate. The goal is to identify potential leads that are more likely to choose a course and focus on communicating with them effectively.

Data and Libraries:
The case study uses a CSV file containing leads data, which is imported into Jupyter Notebook using the Pandas library. Other libraries used in the case study include Seaborn, Matplotlib, Sklearn, and Statsmodel.

Data Cleaning and Preprocessing:
The data is cleaned and preprocessed to handle missing values, drop irrelevant columns, handle unbalanced data, and handle outliers for numeric variables. Dummy variables are also created for categorical columns with more than two categories.

Model Building:
The case study involves building a logistic regression model using Recursive Feature Elimination (RFE) to select important features, checking for multicollinearity using Variance Inflation Factor (VIF), and eliminating columns with high p-values and VIF. The model is evaluated based on accuracy, precision, recall, and specificity.

Results and Conclusion:
The final logistic regression model achieved an accuracy of 91%, sensitivity (recall) of around 81%, and specificity of around 97% using a cutoff value of 0.3. The model was also applied to test data, and the results showed an accuracy of 90%, sensitivity of 96%, specificity of around 87%, precision score of 83%, and recall score of 96%. Based on the results, recommendations are made for the marketing team to focus on specific types of leads for improved lead conversion.

##Usage:

Clone the repository to your local machine.
Install the required libraries (Pandas, Seaborn, Matplotlib, Sklearn, Statsmodel) using pip or conda.
Open the Jupyter Notebook file (.ipynb) in a Jupyter Notebook environment.
Follow the step-by-step instructions in the notebook to run the code and analyze the results.
You can modify the code or experiment with different approaches to further enhance the results.
Note: Please refer to the license file for terms of use and distribution.
