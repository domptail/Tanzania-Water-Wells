# Predicting the Operational Status of Water Wells in Tanzania
Driven Data competition - Pump it Up: Data Mining the Water Table

The datasets are hosted by DrivenData: https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/data/

The data consist of information (40 features) on water wells in Tanzania. The goal is to predict whether a well is "functional", "functional but in need of repairs", or "non functional".

The datasets are:
- Training set values (59,400 observations, 40 variables: id, date, location, installer, etc.)
- Training set labels (59,400 observations, 2 variables: id, status_group)
- Test set values (14,850 observations, 40 variables)

A large part of this analysis was conducted using Data Camp online course: DrivenData Water Pumps Challenge.

## Content
0. Introduction
1. Exploration and Visualization of the Data
2. Feature Engineering
3. Predictions using Random Forests
4. Predictions using Multinomial Logistic Regression
