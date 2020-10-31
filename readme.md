# Overview

This is an advanced class of industrial application at Academy DQLab where previously I prepared data as well as did data cleansing, so now is the time for me to create the right model to predict customer churn.

DQLab Telco is a Telco company which already has many branches scattered everywhere. Since its establishment in 2019, DQLab Telco has consistently paid attention to its customer experience so that customers will not leave it.

Even though it's only a little over 1 year old, DQLab Telco already has a lot of customers who have switched subscriptions to competitors. Management wants to reduce the number of customers who turn (churn) by using machine learning.

# Tasks and Steps

In project part 1 I have done Data Cleansing. Now, as a data scientist I am being asked to make the right model.

In this assignment, I will do Machine Learning Modeling using June 2020 data.

The steps that will be taken are:
1. Perform Exploratory Data Analysis
2. Perform Data Pre-Processing
3. Modeling Machine Learning
4. Determining the Best Model

# Library
1. Pandas (Python for Data Analysis) is a Python library that focuses on data analysis processes such as data manipulation, data preparation, and data cleaning.   
    - read_csv() used to read csv files
    - replace() used to replace values
    - value_counts() used to count the uniqueness of a column
    - drop() used to delete
    - describe() used to view data descriptions
2. Matplotlib is a Python library that focuses on visualizing data such as plotting graphs. Matplotlib can be used in Python scripts, Python and IPython shells, web application servers, and several other graphical user interface (GUI) toolkits.
    - figure() used to create a new figure figure
    - subplots() used to create an image and a set of subplots
    - title() used to give a title to the image
    - ylabel() used to label the Y axis of the image
    - xlabel() used to label the Y axis of the image
    - pie() used to create a pie chart
3. Seaborn builds on Matplotlib and introduces additional plot types. It also makes your traditional Matplotlib plot look a little prettier.
    - countplot() used to plot the number of observations in each variable categorical bin
    - heatmap() Plots rectangular data as a color-encoded matrix
4. Scikit-learn is a library in Python that provides many Machine Learning algorithms for both Supervised, Unsupervised Learning, and used to prepare data.
    - LabelEncoder() used to change the value of a variable to 0 or 1
    - train_test_split() used to divide data into 2 row sections (Training & Testing)
    - LogisticRegression() used to call the Logistic Regression algorithm
    - RandomForestClassifier() used to call the Random Forest Classifier algorithm
    - confusion_matrix() used to create confusion matrix
    - classification_report() used to create a classification report, which includes the accuracy of the model
5. Xgboost is a library in Python for the extreme gradient boosting (xgboost) algorithm
    - XGBClassifier() used to call the XG Boost Classifier algorithm
6. Pickle implements a binary protocol for serializing and de-serializing the Python object structure.
    - dump() used to save
    
# Dataset
For the dataset used has been provided in csv format, it can be loaded via this [link](https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/dqlab_telco_final.csv)   

The detailed data are as follows:
* UpdatedAt: Periode of Data taken
* customerID: Customer ID
* gender: Whether the customer is a male or a female (Male, Female)
* SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
* Partner: Whether the customer has a partner or not (Yes, No)
* tenure: Number of months the customer has stayed with the company
* PhoneService: Whether the customer has a phone service or not (Yes, No)
* InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
* StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
* MonthlyCharges: The amount charged to the customer monthly
* TotalCharges: The total amount charged to the customer
* Churn Whether: the customer churned or not (Yes or No)


