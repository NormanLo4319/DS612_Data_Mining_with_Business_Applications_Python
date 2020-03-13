# Data Mining with Business Application (Python)
An introduction to statistical learning with application in Python.  This course helps students develop Statistical Learning techniques to extract pertinent information from data and make informed business decisions.

## Textbook
This repositary bases on "An Introduction to Statistical Learning with Application in R" by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani in this course.  You can check the textbook details [online](http://faculty.marshall.usc.edu/gareth-james/).

<img src="./images/ISL Cover.jpg" width="200" height="270">

## Course Outline
### Introduction to Python:
---
In this lab, we will introduce some simple Python commands.  The best way to learn a new language is to try it out.  Python can be downloaded from [here](https://www.python.org/downloads/).  Specifically, we are utilizing an IDE (intergrated development environment) "Anaconda" and presentation layout "Jupyternotebook" in this course, which the installation instruction can be found [here](https://jupyter.org/install)

Learning Objectives:
1. Learning how to find and set your working directory on your machine.
2. Learning how to use simple function to create vector and matrix
3. Leanring how to use the help function in Python.
4. Learning the basic mathematical operation in Python.
5. Learning the basic of data indexing in Python.
6. Learning the basic plot function for visualization in Python.
7. Learning how to load data from working directory and saving it to a specific directory.


### Statistical Learning:
---
In this section, we explain the use of statistical learning.  We outline some of the key theoretical concepts that we used to build the founction of statistical learning.

Learning Objectives:
1. What is Statistical Learning?
2. Trade-Off between Prediction Accuracy and Model Interpretability
3. Supervised vs. Unsupervised Learning
4. Regression vs. Classification Problems
5. Assessing Model Accuracy (Measuring the Quality of Fit, Bias-Variance Trade-off, and Classification Setting)
6. K-Nearest Neighbors Model

### Linear Regression:
---
Students learn to apply one of the most popular supervised learning technique called "Linear Regression".  It is a useful tool for predicting a quantitative response and has been arround for a long time.  In this section, we review some of the key ideas underlying the linear regression model, as well as the least squares approach that is most commonly used to fit this model.

Learning Objectives:
1. Estimating and Assessing the Accuracy of the Coefficient
2. Evaluating the Goodness of Fit of the Model
3. Estimating Multiple Regression Coefficients
4. Using the Qualitative Predictors (Categorical Analysis)
5. Potential Problems of the Model

### Classification:
---
The linear regrssion model assumes that the response variable (dependent variable) is quantitative (coninuous).  However, the response varaible is instead qualitative (discrete / categorical).  A process used for predicting qualitative responses is known as classification.  There are many classification techniques, or classifiers, that one might use to predict a qualitative response.  In this section, we cover three of the most widely-used classifiers: Logistic Regression, Linear Discriminant Analysis, and K-Nearnest Neighbors.

Learning Ojbectives:
1. Logistic Regresion
- Estimating the Regression Coefficents
- Logistic Regression for More than 2 Response Classes
2. Linear Discriminant Analysis
- Using Bayes' Theorem for Classification
- Linear Discriminant Analysis for P = 1
- Linear Discriminant Analysis for P > 1
- Quadratic Discriminant Analysis
3. Comparison of Classification Methods

### Resampling Methods:
---
In this section, we consider a class of methods that estimate the test error rate by holding out a subset of the training observatios from the fitting process, and then applying the statistical learning method to those held out observations.

Learning Objectives:
1. Cross Validation
- Validation SEt Appraoch
- Leave-One-Out Cross Validation
- k-Fold Cross Validation
- Bias Variance Trade-Off for k-Fold Cross Validation
2 Bootstrap
- Estimating the stardard error of the coefficients

### Tree-Based Methods:
---
Tree-Based Methods for regression and classification are simple and useful for interpretation.  These methods involve stratifying or sementing the predictor space into a number of simple regions.  Since the set of splitting rules used to segment the predictor space can be summarized in a tree, these type of approaches are known as decision tree methods.  In this section, we introduce bagging, random forests, and boosting, which involves producing multiple trees and combined to yiled a single consensus prediction.

Learning Objectives:
1. Basic of Decision Tree
- Regression Tree
- Classification Trees
- Trees vs. Linear Models
- Advantages and Disavantages of Trees
2. Bagging, Random Forests, Boosting
- Bagging
- Random Forests
- Boosting

### Moving Beyond Linearity
---
In this section, we are relaxing the linearity assumption while still attempting to maintain as much interpretability as possible.  We do this by examining very simple extensions of linear model like polynomial regression and step functions, as well as more sophisticated approaches such as splines, local regression, and generalized additive models.
1. Polynomial Regression
2. Step Functions
3. Regression Splines
4. Smoothing Splines
5. Local Regression
