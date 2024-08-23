# Wrapper_Method_ObesityDataSet
Overview

This project analyzes data from a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas that asked people about their eating habits and weight. The data was obtained from the UCI Machine Learning Repository. Categorical variables were changed to numerical ones in order to facilitate analysis.

First, a logistic regression model to try to predict whether survey respondents are obese based on their answers to questions in the survey. After that, it used three different wrapper methods to choose a smaller feature subset.
Sequential forward selection, sequential backward floating selection, and recursive feature elimination. 

After implementing each wrapper method, it evaluated the model accuracy on the resulting smaller feature subsets and compared that with the model accuracy using all available features.


Evaluating a Logistic Regression Model
The data set obesity contains 18 predictor variables. Here's a brief description of them.

Gender is 1 if a respondent is male and 0 if a respondent is female.
Age is a respondent's age in years.
family_history_with_overweight is 1 if a respondent has family member who is or was overweight, 0 if not.
FAVC is 1 if a respondent eats high caloric food frequently, 0 if not.
FCVC is 1 if a respondent usually eats vegetables in their meals, 0 if not.
NCP represents how many main meals a respondent has daily (0 for 1-2 meals, 1 for 3 meals, and 2 for more than 3 meals).
CAEC represents how much food a respondent eats between meals on a scale of 0 to 3.
SMOKE is 1 if a respondent smokes, 0 if not.
CH2O represents how much water a respondent drinks on a scale of 0 to 2.
SCC is 1 if a respondent monitors their caloric intake, 0 if not.
FAF represents how much physical activity a respondent does on a scale of 0 to 3.
TUE represents how much time a respondent spends looking at devices with screens on a scale of 0 to 2.
CALC represents how often a respondent drinks alcohol on a scale of 0 to 3.
Automobile, Bike, Motorbike, Public_Transportation, and Walking indicate a respondent's primary mode of transportation. Their primary mode of transportation is indicated by a 1 and the other columns will contain a 0.

Project Description

The goal of this project is to apply the Wrapper Method for feature selection on the Obesity Data Set. The Wrapper Method involves training a machine learning model on different subsets of features and selecting the subset that provides the best performance. This technique is computationally intensive but often yields better performance than filter-based methods.

The key components of this project include:

Data preprocessing and exploration
Implementation of the Wrapper Method
Evaluation of feature subsets using machine learning models
Analysis of the selected features and model performance

Dataset

The Obesity Data Set used in this project contains various attributes related to lifestyle, dietary habits, and physical activities.


