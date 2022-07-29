# House Price : Advance Regression

Table of Content:
Overview
Procedure
Future scope of project

# Introduction


Problem Description:

This project is addressing factors which can influence price negotiations besides the number of bedrooms or a white-picket fence in the real estate realm.

Two types of dataset are provided: training data set and test data set. In fact, the training data set is the initial dataset we will use to teach our machine learning models to recognize patterns or to extract features that are relevant to this specific goal. while the test data set will be used to evaluate the model’s accuracy and to make prediction as well.

Both data sets we have at hand consist of 79 explanatory variables describing (almost) every aspect of residential homes in Ames and Iowa. See Data for full description.

Our goal is to predict the final price of each home. That's, for each Id in the test data set, we want to predict the value of the SalePrice variable.

Personally, this project is timely in that a wide range of Machine Learning algorithms will be revisited including: Linear Regression, Rigide Regression, Lasso Regression, SVM, Random Forest Regression, XGBoost and so forth.

Finally, my major contribution to Kaggle's Community is all about some new approaches for conducting data analysis tasks based on a deep scientific thinking focused on the "Why" instead of only the "How".



# Step-by-Step Procedure 


I.    Explarotory data analysis

I.1. General exploration

I.2. Numerical features
    I.2.1. Explore and clean Numerical features
    I.2.2. Missing data of Numerical features

I.3. Categorical features
    I.3.1. Explore and clean Categorical features
    I.3.2. Missing data of Categorical features
    I.3.3. Transform Categorical features into Binary features (get_dummies)

I.4. Merge numerical and binary features into one data set

I.5. Drop outliers from the train set
II. Feature engineering

III. Preparing data for modeling

III.1. Split data into train and test and Standardization

III.2. Backward Stepwise Regression

III.3. Variance Inflation Factor

III.4. Cook distance
IV. Modeling

IV.1. Models and metrics selection

IV.2. Hyperparameters tuning and model optimization
    IV.2.1. Ridge regression
    IV.2.2. Lasso regression
    IV.2.3. XGBoost regression
    IV.2.4. LightGBM regression

IV.3. Choosing the best model
V. Prediction



# Future Scope of Project

 The project can be tuned for better parameters to optimize the model and to increase the accuracy of the project
