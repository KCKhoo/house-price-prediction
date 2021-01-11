# House Price Prediction - Kaggle Project

## Table of Contents  
* [Overview](#overview)  
  * [1. Data wrangling](#task1)  
  * [2. Exploratory data analysis (EDA)](#task2)  
  * [3. Machine Learning [On-going]](#task3)   
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
### 3. Machine Learning [On-going]
Machine learning will be used to predict house price. The first step is to preprocess data based on the insights discovered during exploratory data analysis. Subsequently, the preprocessed data will be used to train various machine learning models such as neural network, XGBoost, linear regression and etc in order to predict house price.

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
