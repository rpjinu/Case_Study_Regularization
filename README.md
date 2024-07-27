# Case_Study_Regularization
ALL python jupyter notebook
## Problem Statement

There is a business requirement where we need to classify the gender based on the various features using the concept of regularization. Here we are going to apply the L1 and L2 regularization and using logistic regression we are going to apply the same. There are around 5000 records on which we need to create the model and come up with the solution.
**Data Dictionary**

**long_hair** - Length of hair

**forehead_width_cm** - Forehead width of individual

**forehead_height_cm** - Forehead height of individual

**nose_wide** -	Nose width of individual

**nose_long** -	Nose length of the individual

**lips_thin** -	lips structure of the individual

**distance_nose_to_lip_long** - Distance from nose to lip

**gender** -	Dependent variables i.e. Gender
# Table of Content

1. **[Import Libraries](#lib)**
2. **[Data Preparation](#prep)**
    - 2.1 - **[Understand the Data](#read)**
    - 2.2 - **[Exploratory Data Analysis](#eda)**
    - 2.3 - **[Missing Value Treatment](#null)**
    - 2.4 - **[Encoding and Feature Scaling](#enc)**
3. **[What is Regularization](#lr)**
    - 3.1 - **[Understanding the need of Regularization](#gi)**
    - 3.2 - **[Understanding the L2 Regularization or Ridge Regression](#gi)**
    - 3.3 - **[Understanding the L1 Regularization or Lasso Regression](#mf)**
    - 3.4 - **[Understanding the Elastic Net](#sf)**
4. **[Splitting the data into Train and Test](#sd)**
5. **[Creating the model on training dataset](#model)**
6. **[Run the model on the Test Dataset](#test)**
7. **[Check the accuracy of the model](#acc)**
    - 7.1 - **[Accuracy Score](#accscore)**
    - 7.2 - **[Confusion Matrix](#cm)**
    - 7.3 - **[ROC Curve](#roc)**
    - 7.4 - **[F1 Score](#f1score)**
    - 7.5 - **[Log Loss](#logloss)**
8. **[Comparing the Training and Testing Accuracies](#overunder)**
9. **[Applying K-Fold Cross Validation to find the best value of Lamda](#kfcv)**
