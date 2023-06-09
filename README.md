# Predicting Wine Quality

It is hypothesized that the chemical characteristics of a white wine, measured early in the production cycle, can be used to predict the sensory quality of the wine when it is ready for sale and consumption.  It is further hypothesized that certain chemical features have a stronger correlation to the quality output rating than others, and this subset of features can achieve the same predictive power as the full set of features.

This project aims to perform statistical analysis on a dataset consisting of 4,898 observations containing 11 chemical features and 1 output variable that rates the quality of the wine on an ordinal scale.  This analysis first assessed the strength of the correlation between each explanatory variable and the output variable.  Based on this analysis, several experiments were conducted to evaluate the performance of two predictive models (Random Forest Classifier and SVM) on the full dataset and two feature-selected datasets that contain the most strongly correlated explanatory variables.  

# How to use this project

All code for this project has been packaged into a Jupyter Notebook: wine-quality-analysis.ipynb.  
The dataset used within this notebook is winequality-white.csv

Ensure that all dependent python packages are installed in your local environment and step through the notebook to execute the analysis.

DATA:
Cortez,Paulo, Cerdeira,A., Almeida,F., Matos,T., and Reis,J.. (2009). Wine Quality. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.
