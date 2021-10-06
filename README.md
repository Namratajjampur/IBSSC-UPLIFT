# UPLIFT: Usage of Poverty Level Indicators to Facilitate Transformation

## Abstract
UPLIFT: Usage of Poverty Level Indicators to Facilitate Transformation, as the name suggests, is a study that aims at analysing data consisting of various socio-economic factors that effect households in order to alleviate poverty by understanding and identifying various aspects that may have an impact on poverty levels. 
As a use case, data pertaining to the Latin American nation of Costa Rica has been studied. Initially, we perform exploratory data analysis to discover patterns in the data and gain an insight to the relationship between attributes. We then perform feature selection and normalization to render the data suitable for modeling with machine learning techniques. We use these models to predict the poverty standard of each household and map them into four categories corresponding to the level of poverty. Finally, the data is then analyzed in the light of this classification to elicit the factors that strongly effect each category, towards recommending methods for improvement and an appropriate allocation of social welfare benefits.

## Data 
Data on Costa Rican households that is provided by Inter-American Development Bank and is available in Kaggle
https://www.kaggle.com/c/costa-rican-household-poverty-prediction/overview

## Overview of Code
The repository has been divided into sections as published in the paper.

### Section III - Data
1. Raw Data (from Kaggle) 
2. File consisting of description of the attributes in the data 
3. Preprocessed Data - Raw data after cleaning, feature extraction, PCA

### Section IV(A) - Preprocessing 
1. Preprocessing.Rmd : R markdown file used for data cleaning and preprocessing. It results in 2 output csv files.
2. UpsamplingAndDTModel.ipynb : Script to implemenet upsampling and testing on a sample model for training(DT)
3. PCA : Folder consists of implementation and analysis of PCA on the data

### Section IV(B) - EDA
1. EDA.Rmd: R Markdown file that contains preliminary EDA on the preprocessed data and exploratory analysis using visualization.
2. EDA_HTML.html: knit file showing EDA, data visualization and analysis.

### Section IV(C) - Modelling
1. SavedModels: Folder contains the .sav of all models to load and test the models.
2. Models.ipynb: Script consisting of the four models we have used i.e, Ridge, XGBoost, Decision Trees and RandomForest Classifiers
From this, the model that was the most well suited was Random Forest.
The models can be stored in the folder SavedModels

### Section V - Dicussions
This folder consists of the script that analysis the results from the ML models and discusses the insigts shared.



## Authors
### Namrata Ramesh - namrata.ajjampur@gmail.com 
### Diya Chandra
### Chiranth Jawahar
### Gowri Srinivasa







