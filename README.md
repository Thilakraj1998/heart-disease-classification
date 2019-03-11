## Decision Trees

In this example, we explore the use of machine learning to predict heart disease status. We will specifically look at various decision tree ensemble models. This exercise has two objectives:

1. Learn more about decision trees and understand where to apply them. So we will restruct ourselves to decision trees.
2. Learn how to deploy machine learning models in the field


## Data
The data is from the UCI Machine Learning Repository. The csv is available in the /raw-data folder, but if you want to download it from the source you can do so at: https://archive.ics.uci.edu/ml/datasets/Heart+Disease .There are multiple datasets available and we use the one processed by the Cleveland Clinic Foundation.

The dataset has 14 predictors of heart disease, but we use only two of them for the sake of simplicity - maximum heart rate achieved (thalach) and serum cholesterol levels (chol). A scatter plot of the training dataset is shown below (Fig 1).

![scatter](images/eda.png)

## Analysis
The analysis consists of three parts in three different notebooks. Part 1 talks about preprocessing the data. Part 2 deals with the modeling procedure. Part 3 explains how to  deploy the models in a production.

## Dependencies:
Python 3.6
Packages:
- pandas
- numpy
- sci-kit learn
- matplotlib
- mlxtend
