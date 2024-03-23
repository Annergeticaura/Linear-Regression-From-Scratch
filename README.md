# Linear-Regression-From-Scratch
A Linear Regression model for multiple independent variable based predictions using Python (Google Colab)

**Linear Regression from Scratch**
This repository contains a Python implementation of simple linear regression from scratch. Linear regression is a fundamental technique in statistics and machine learning for modeling the relationship between two variables. This implementation aims to provide a clear understanding of how linear regression works without relying on external libraries such as scikit-learn.

**Overview**
Linear regression is a linear approach to modeling the relationship between a dependent variable and one or more independent variables. It assumes that the relationship between the variables can be approximated by a straight line. In simple linear regression, there is only one independent variable.

The equation of a multivariate linear regression model can be expressed as:
y=x0+w1x1+w2x2+...+wnxn

Where:
y is the dependent variable (the variable we are trying to predict).
x is the independent variable (the variable used to make predictions).
w is the slope of the line (the coefficient that represents the relationship between x and y).
x0 is the y-intercept (the value of y when x is 0).
The goal of linear regression is to find the best-fitting line through the data, which minimizes the difference between the predicted values and the actual values.

**Dataset**
Contains information about Sex, Length, Diameter, Height, Whole weight, Shucked weight,	Viscera weight,	Shell weight,	Rings,	Age.

**Implementation Details**
The implementation consists of the following steps:

Data Preprocessing: Load and preprocess the dataset. This includes tasks such as one hot encodingg, splitting the data into training and testing sets, normalization, and handling missing values.

Model Training: Implement the training algorithm to learn the parameters (slope and intercept) of the linear regression model. This typically involves minimizing the cost function (found by mean squared error calculation) using techniques such as gradient descent and updating the weights for the weighted sum of Y.

Model Evaluation: Evaluate the trained model using appropriate metrics such as mean squared error (MSE) or R-squared to assess its performance on the testing data.

**Clone the Repository**
git clone https://github.com/Annergeticaura/Linear-Regression-From-Scratch.git
