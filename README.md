# House Price Prediction - Kaggle Project

## Table of Contents  
* [Overview](#overview)  
  * [1. Data wrangling](#task1)  
  * [2. Exploratory data analysis (EDA)](#task2)  
  * [3. Machine Learning](#task3)   
* [Programming Language(s)](#programming_languages)
* [Tools](#tools)
* [Libraries](#libraries)

<a id="overview"></a>
## Overview

The goal of this project is to predict house prices with various machine learning models such as neural network, XGBoost, linear regression and etc. The dataset used for this project is the [Ames Housing dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). To achieve the goal, the following tasks are carried out.

<a name="task1"></a>
### 1. Data wrangling 
Data wrangling is performed on the Ames Housing dataset. Data wrangling consists of three steps - gathering, assessing and cleaning. Data is assessed with visual and programmatic assessment to look data quality issues such as duplicates, wrong data types, outliers/anomalous data, missing data and discrepancies in data. Subsequently, data is cleaned based on the issues found during assessment. Finally, clean data is saved in a file for subsequent tasks.

<a name="task2"></a>
### 2. Exploratory Data Analysis
Exploratory Data Analysis is carried out to further understand the data and to find insights in order to select the features that helpful in predicting house price. The steps for exploratory data analysis includes univariate and bivariate analysis. After EDA is completed, outliers, if there is any, will be removed from the dataset. Finally, clean data is saved in a file for subsequent tasks.

<a name="task3"></a>
### 3. Machine Learning
Machine learning is used to predict house price. The first step is to preprocess data based on the insights discovered during exploratory data analysis. Preprocessing steps include encoding categorical variables with various encoding algorithms (label encoding, one-hot encoding and hash encoding), standardization and KNN imputation. Subsequently, the preprocessed data is used to train various machine learning models, which are evaluated using root mean square log error (RMSLE) with 5-folds cross validation. RMSLE is chosen because there is big variation (left-skewed) in values of target variable. Machine learning models explored in this task include lasso regression, ridge regression, elastic net regression and XGBoost. The following table displays the performance of the best model, which is elastic net regression with alpha = 0.03 and l1_ratio = 0.03.

| | Training RMSLE | Validation RMSLE |
| --- | --- | --- |
| Fold 1 | 0.1016 | 0.1260 |
| Fold 2  | 0.1071 | 0.1026 |
| Fold 3  | 0.1018 | 0.1312 |
| Fold 4  | 0.1032 | 0.1182 |
| Fold 5  | 0.1080 | 0.1007 |
| Mean  | 0.1043 | 0.1157 |


<a name="programming_languages"></a>
## Programming Language(s)
- Python

<a name="tools"></a>
## Tools
- Jupyter Notebook

<a name="libraries"></a>
## Libraries
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

and additional libraries listed in the Jupyter notebook for each task
