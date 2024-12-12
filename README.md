Obesity Dataset Analysis and Neural Network Implementation

This project analyzes data from a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas that asked people about their eating habits and weight. The dataset was obtained from the UCI Machine Learning Repository.

Overview

The analysis explores the relationship between eating habits, lifestyle, and obesity levels. Initially, categorical variables were transformed into numerical ones to facilitate analysis. The project focuses on:

Logistic Regression Model:

Predicts obesity levels based on survey responses.
Evaluates model accuracy using all features.
Feature Selection Using Wrapper Methods:
Applied Sequential Forward Selection, Sequential Backward Floating Selection, and Recursive Feature Elimination (RFE).
Evaluated and compared model performance using smaller feature subsets against all features.
Neural Network Implementation:
Developed a neural network to classify obesity levels.
Compared its performance with the logistic regression model.
Dataset Details
The dataset contains 18 predictor variables, briefly described below:

Gender: 1 for male, 0 for female.
Age: Respondent's age in years.
family_history_with_overweight: 1 if a respondent has an overweight family member, 0 otherwise.
FAVC: 1 if high-caloric food is frequently consumed, 0 otherwise.
FCVC: 1 if vegetables are usually included in meals, 0 otherwise.
NCP: Daily number of main meals (0 for 1-2 meals, 1 for 3 meals, 2 for more than 3).
CAEC: Frequency of food consumption between meals (scale of 0 to 3).
SMOKE: 1 if the respondent smokes, 0 otherwise.
CH2O: Water consumption (scale of 0 to 2).
SCC: 1 if the respondent monitors caloric intake, 0 otherwise.
FAF: Physical activity frequency (scale of 0 to 3).
TUE: Time spent using devices with screens (scale of 0 to 2).
CALC: Alcohol consumption frequency (scale of 0 to 3).
Transportation Modes: Automobile, Bike, Motorbike, Public Transportation, Walking (indicated by 1 for primary mode and 0 otherwise).
Project Objectives
Preprocessing and Exploration: Prepare the dataset for machine learning models.
Logistic Regression: Serve as a baseline model to classify obesity levels.
Wrapper Method Feature Selection: Identify the most relevant features for better model performance.
Neural Network Implementation: Apply a neural network to classify obesity levels and compare its performance with traditional models.
Neural Network Implementation
A neural network was designed with the following architecture:

Input Layer: Accepts all 18 predictor variables.
Hidden Layers: Two layers with ReLU activation to capture complex patterns.
Output Layer: A softmax layer for multiclass classification of obesity levels.
Results
Logistic regression performance improved after applying Wrapper Methods by selecting optimal subsets of features.
The neural network outperformed the logistic regression model, especially when using the entire feature set.
Feature selection reduced computational costs and slightly improved logistic regression performance, but the neural network showed robustness even without feature selection.


