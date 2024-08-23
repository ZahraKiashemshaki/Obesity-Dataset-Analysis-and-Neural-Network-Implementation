# Wrapper_Method_ObesityDataSet
Overview

This project analyzes data from a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas that asked people about their eating habits and weight. The data was obtained from the UCI Machine Learning Repository. Categorical variables were changed to numerical ones in order to facilitate analysis.

First, a logistic regression model to try to predict whether survey respondents are obese based on their answers to questions in the survey. After that, it used three different wrapper methods to choose a smaller feature subset.
Sequential forward selection, sequential backward floating selection, and recursive feature elimination. 

After implementing each wrapper method, it evaluated the model accuracy on the resulting smaller feature subsets and compared that with the model accuracy using all available features.

Project Description

The goal of this project is to apply the Wrapper Method for feature selection on the Obesity Data Set. The Wrapper Method involves training a machine learning model on different subsets of features and selecting the subset that provides the best performance. This technique is computationally intensive but often yields better performance than filter-based methods.

The key components of this project include:

Data preprocessing and exploration
Implementation of the Wrapper Method
Evaluation of feature subsets using machine learning models
Analysis of the selected features and model performance

Dataset

The Obesity Data Set used in this project contains various attributes related to lifestyle, dietary habits, and physical activities.


