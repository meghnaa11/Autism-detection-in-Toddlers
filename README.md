# Autism detection in Toddlers

In this project, autism is detected in toddlers using Decision Tree and Random forest

## Introduction

Autistic Spectrum Disorder (ASD) is a neurodevelopmental condition associated with significant healthcare costs, and early diagnosis can significantly reduce these. Unfortunately, waiting times for an ASD diagnosis are lengthy and procedures are not cost effective. The economic impact of autism and the increase in the number of ASD cases across the world reveals an urgent need for the development of easily implemented and effective screening methods. Therefore, a time efficient and accessible ASD screening is imminent to help
health professionals and inform individuals whether they should pursue formal clinical diagnosis. In this project, we will be using random decision forest on a given data set to estimate the predictive power of machine learning techniques in detecting autistic traits.

## DATA SET
Data type: Predictive/Descriptive: Nominal/Categorical, binary
and continuous
Task: Classification
Attribute Type: Categorical, continuous and binary
Area: Medical, health and social science
Missing values: 0
Number of Instances (records in your data set): 1054
Number of Attributes (fields within each record): 18
(including class variable)
DATA ATTRIBUTES:
 The given data set is descriptive, predictive, binary and continuous.
 There are no missing values
 There are 18 attributes including class variable.
 There are 10 behavioural features (Qchat-10) plus other individual characteristics.
 Total 1054 records are there.
 Age number age in years
 Sex String Male or Female
 Ethnicity String List of common ethnicities in text format
 Born with jaundice Boolean (yes or no) Whether the case was born with jaundice
 Family member with PDD Boolean (yes or no) whether any immediate family member has a PDD
 Attributes A1 – A10: Items within Qchat-10 in which questions with possible answers “Always, Usually, Sometimes, Rarely and Never” are mapped to “1” or “0”.
 For questions 1-9 (A1-A9), if the response was “Sometimes”, “Rarely” or “Never” then “1” is assigned to the question.
 For question 10 (A10) if the response was “Always”, “Usually” or “Sometimes” then “1” is assigned to that question.
 Qchat-10-score: If the user obtained more than 3, add points together for all ten questions
 If score more than 3, then there are potential ASD traits, otherwise no ASD traits are observed
 The remaining features in the datasets are collected from the “submit” screen in the ASDTests screening app.

### LIBRARIES USED
 pandas: for data manipulation and analysis
 numpy: for high level mathematical functions
 matplotlib: for data visualization
 seaborn: for data visualization
 sklearn: for machine learning algorithms

### Steps of analysis
 Import libraries
 Load the dataset
 Data cleaning
 Removing unnecessary attributes
 Exploratory data analysis
 Converting categorical features and cleaning
 Train-test splitting
 Training of data with model
 Testing
 Analysis

## CONCLUSION
The accuracy of both the algorithms was 100% because of the clean data set
