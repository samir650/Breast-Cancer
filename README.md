#  Breasts Cancer Predictions

## Type of problem : Binary Classification problem

## Dataset Description:

- Description: This dataset consists of 32 baseline variables, such as diagnosis, radius mean, texture_worst, perimeter_worst, for Breast Cancer patients.

- Purpose: Commonly used for predicting Breast Cancer progression based on various medical diagnoses.


## The proposed framework is summarized in the following steps:
1- Data exploration 🔎 : Check the number of features and rows, missing values, duplicate values and generating descriptive statistics for this data 

2- Data visualization 📊 : 
* use histplot from Seaborn library to see the distribution of data for each feature and try to reach insight from it.
* comparing each feature with the dependent feature and try to reach insight from it.
* use heatmap to Check if there is high correlation between each attributes.

3- Data preprocessing 🛠 : Data Splitting ,Data Cleaning (Handling Missing Values & Outliers Values), Handling Imbalanced Data (Oversampling),Feature Engineering (
Feature Selection), Handing Categorical Data(One Hot Encoding).

4- Selecting and comparing models 🎯 : After many experiments and attempts with most of the famous models in classification problems, I found Three Models give me High performance (ExtraTreesClassifier, XGBClassifier, RandomForestClassifier). 

5- Fine tuning 🪄 : I used Optuna (optimization framework for machine learning models) to choose the best hyperparameters for Three Models.

8- Ensemble Model 📈: I used Hard Voting between this Models to improve overall performance and generalization.

6- Evaluation using test set ⚖ 

7- Saving model 🗃
