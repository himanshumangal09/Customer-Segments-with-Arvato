# Arvato Capstone Project 
### Table of Contents

1. [Installation](#installation)
2. [Introduction](#introduction)
3. [Project Motivation](#motivation)
4. [Files](#files)
5. [Instructions](#instructions)
6. [Results](#results)
7. [Licensing, Authors, and Acknowledgements](#licensing)


## Introduction <a name="introduction"></a>
This project has 2 major parts and 1 minor at the end:
1. Customer Segmentation Report (Unsupervised Learning) - EDA, PCA and clustering analysis of the general and customer population with the goal of being able to describe the core customer base of the company.
2. Predict Customer Report (Supervised Learning) - Use what was observed in part 1 or parts of it to create a supervised learning model that could predict whether an individual would respond to a mail campaign.
3. Kaggle Competition - As a last step the predictions generated from the best performing model from part 2 could be submitted to Kaggle and compared against the other student submissions.

## Project Motivation <a name="motivation"></a>
This project provided by Arvato Financial Solutions was one of the available capstone projects. I chose this project mainly for two reasons:
* The data in this project is real and almost no cleaning has been done on it.
* Last part of the project gives me the opportunity to participate in a Kaggle competition with the other students.

## Project Overview
In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

The project was divided into three distinct parts to make them more manageable:
* Data Preprocessing — The first part was all about performing preprocessing steps to make data ready for further analysis. This involved converting missing value codes to NaN’s, analyzing missing values per column and row, and some feature engineering.

* Identify customer segments within the general population — The second part aimed to help the company create a more efficient way of targeting people who are more likely to become customers. This was done by comparing the customer demographics data against general population demographics data. Using the principal component and unsupervised techniques different segments were created which in turn made it possible to identify parts of the population that best described the core customer base of the German company.


* Predict customer response rate — The motivation for the third part was to create a machine learning model that could be used to predict whether or not a person would respond to a marketing campaign. As a final part, the best model was submitted to Kaggle to see how it stacked up against models created by other users.


### Technical overview:
Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we build preprocessing pipeline  to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments. Due to the nature of the data (details in notebook), AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook: 
* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Final Model Evaluation
* Feature Importance
* Analysis of identified important features in clusters to find relevance
* Scoring and submisstion to Kaggle


## Results <a name="results"></a>
![alt text](https://github.com/himanshumangal09/Arvato-capstone-project/blob/master/image.png?raw=true)


**See blog post** [here](https://medium.com/@himanshumangal09/exploring-customer-segments-and-predicting-customer-response-1e3dcd816e5f) 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
I would like to thank Arvato Financial Solutions for the datasets/files and Udacity for making this project possible.
This project is under MIT License.
