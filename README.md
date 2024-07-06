# Data Science Project

## Table of Contents
1. [Description](#description)
2. [Projects](#projects)
    1. [Travel Insurance Classification](#travel-insurance)
    2. [Titanic Survival Prediction](#titanic)

## 1. [Description](description)
This repository consists of two projects: Travel Insurance Classification Project and Titanic Survival Prediction.

## 2. [Projects](projects)

### 2.1 [Travel Insurance Classification](travel-insurance)
*Source: https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data*

In this project, I will be constructing a predictive model for classifying which customers would be interested to buy the travel insurance based on the historical dataset.

I will be performing data preparation and data wrangling, as well as exploratory data analysis, then followed by constructing classification machine learning model. 

`Accuracy`, `Overall Precision`, `Overall Recall`, `roc_auc_score` will be used to evaluate the predictive model. Additionally, I will perform preprocessing in a pipline, using `sklearn.pipeline`, to improve ROC curve and its AUC. 

Dataset contains:

|Variable|Definition|
|-----|------|
|`Age`|Age of the customer|
|`Employment Type`|The sector in which customer is employed|
|`AnnualIncome`|Whether the customer is college graduate or not|
|`FamilyMembers`|Number of members in customer's family|
|`ChronicDisease`|Whether the customer suffers from any major disease or conditions|
|`FrequentFlyer`|Derived data based on customer's history of booking air tickets|
|`EverTravelledAbroad`|Has the customer ever travelled to a foreign country|
|`TravelInsurance`|Did the customer buy travel insurance package|

### 2.2 [Titanic Survival Prediction](titanic)
*Source: https://www.kaggle.com/competitions/titanic*

In this project, I will be constructing a predictive model for an online competition, posted on *Kaggle*, to answer the following question:

***"What sorts of people were more likely to survive?"***

In this competition, I obtained two datasets (`train.csv` and `test.csv`). The `train.csv` file contains the details of a subset of the passengers on board and also contains information whether they have survived or not.The `test.csv` file contains similar information but does not disclose the survival status of each passenger. I will be conducting statistical analysis and applying supervised machine learning algorithms to train and predict the "unknown" labels in `test.csv`. 

Datasets contain:
|Variable|Definition|
|------|------|
|`survived`|whether the passenger survived or not (0 = No, 1 = Yes)|
|`pclass`|passenger's ticket class (1 = Upper, 2 = Middle, 3 = Lower)|
|`sex`|passenger's sex|
|`age`|passenger's age|
|`sibsp`|number of siblings/spouses aboard the Titanic|
|`parch`|number of parents/children aboard the Titanic|
|`ticket`|passenger's ticket number|
|`fare`|passenger fare|
|`cabin`|cabin number|
|`embarked`|port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)|