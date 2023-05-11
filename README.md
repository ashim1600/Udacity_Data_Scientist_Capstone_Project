# Udacity_Data_Scientist_Capstone_Project
This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.
## <b>Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers</b>
1. Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:
- pandas
- numpy
- math
- json
- sklearn.model_selection (train_test_split module)
- sklearn.preprocessing (StandardScaler, PolynomialFeatures)
- from sklearn.tree (DecisionTreeClassifier,DecisionTreeRegressor)
- sklearn.ensemble (RandomForestClassifier)
- sklearn.metrics (mean_squared_error,classification_report)
- sklearn.linear_model (Ridge)
- time
- sklearn.model_selection (GridSearchCV)
- matplotlib
### 2. Project Motivation
This project was the Capstone project for a Data Scientist nanodegree with Udacity, and the goal was to answer two business questions related to the Starbucks rewards mobile app. The questions were: What are the main drivers of an effective offer on the Starbucks app? Could the data provided predict whether a user would take up an offer? Three models were created for the three offer types (BOGO, discount, and informational) to answer these questions.
### 3. Summary of my findings:
Regarding Question 1, all three models indicated that the tenure of a member is the most significant predictor of offer effectiveness. However, further research is necessary to determine the average number of days of tenure that would lead to an effective BOGO offer.

Regarding Question 2, I developed three separate models to predict the effectiveness of each offer type. The BOGO and discount models achieved good accuracy, with 82.83% and 87.35% respectively. The model for informational offers had slightly less accuracy, with a rate of 75.3%. Nevertheless, in a business context, a 75% accuracy rate is acceptable for informational offers because there are no costs associated with informing users about a product. Moreover, an 80% or higher accuracy rate would be sufficient to display offers to customers because even if the model misclassifies a few customers, the overall increase in revenue may justify these
mistakes.
### 4. File Descriptions
The repository contains four files, including the project report and data files (portfolio.json, profile.json, and transcript.json)
### 5.Licensing, Authors, Acknowledgements, etc.
Data for coding project was provided by Udacity.
Link for the blog: https://ashimsharma50.blogspot.com/2023/05/cracking-code-analyzing-customer.html
