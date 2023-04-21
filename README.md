# SC1015-Mini-Project

## About
This is a Mini-Project for the module SC1015 (Introduction to Data Science and Artificial Intelligence) in Nanyang Technological University.
Our group chose to explore on how we can predict the probability of winning in a chess match.

## The Team
Kenneth Lim Tze Kang [@trashken0906](https://github.com/trashken0906) - Data Preparation and Cleaning, Exploratory Data Analysis, Presenation Slides and Presentor

Srivikass Jeyaprakash [@vicks905](https://github.com/vicks905) - Exploratory Data Analysis, Machine Learning Models 1 and 2, Presentation Slides and Presentor

## Problem Definition
How different variables affect the probability of the white side winning?
### Dataset used
[Chess Game Dataset](https://www.kaggle.com/datasets/datasnaek/chess)
# Brief Overview of Project

## Data Cleaning
* Removing duplicate rows and invalid rows
* Remove Unnecessary column and added important columns
* Randomly selectly half of the total number of data points
* Export data as csv

## EDA & Visualisation
Explored,visualized and provided insights to the following
* Rated v Non-Rated Games
* Different Victory Status 
* Rating Distribution
* Difference in Rating

## Machine Learning Models Used
* Random Forest
* Logistic Regression (**Best**)

## Outcome
* Out of the 2 models we implemented, logistic regression performed better than random forest
* Out of the 5 variables that we used for the models,the difference in Rating is the best variable in predicting the winner of the chess game

## Key Learning Points
* How to use Github
* Logistic Regression Models
* Random Forest MOdels
* Plotting correlation matrix with categorical data
* We can improve our models through hyperparameter tuning of the random forest



## References
-https://medium.datadriveninvestor.com/choosing-the-best-algorithm-for-your-classification-model-7c632c78f38f

-https://builtin.com/data-science/random-forest-algorithm

-https://medium.com/@knoldus/how-to-find-correlation-value-of-categorical-variables-23de7e7a9e26

-https://towardsdatascience.com/better-heatmaps-and-correlation-matrix-plots-in-python-41445d0f2bec

-https://towardsdatascience.com/evaluating-performance-of-models-8d5c3ca6f8cf

