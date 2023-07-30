# Logistic Regression for Iris Dataset
This project demonstrates the implementation of a logistic regression model to classify the Iris dataset into two classes: "setosa" and "versicolor". The logistic regression model is implemented using Python and scikit-learn library.

Table of Contents
Introduction
Dataset
Requirements
Installation
Usage
Hyperparameter Tuning
Results
Contributing
License
# Introduction
Logistic regression is a popular algorithm used for binary classification tasks. In this project, we use the Iris dataset and consider only two classes, "setosa" and "versicolor", to perform binary classification using logistic regression.

# Dataset
The Iris dataset contains measurements of iris flowers, with four features (sepal length, sepal width, petal length, and petal width) and three classes ("setosa", "versicolor", and "virginica"). For this project, we only use the "setosa" and "versicolor" classes, converting the problem into a binary classification task.

# Requirements
Python 3.x
scikit-learn
numpy
# Installation
Clone this repository to your local machine.
Install the required libraries using pip:
bash
Copy code
pip install -r requirements.txt
# Usage
The main code for the logistic regression model is located in the logistic_regression_iris.py file. You can run it using the following command:
bash
Copy code
python logistic_regression_iris.py
The script will load the Iris dataset, preprocess it to consider only the "setosa" and "versicolor" classes, and then split it into training and testing sets. The logistic regression model will be trained on the training data and evaluated on the testing data.
# Hyperparameter Tuning
The logistic regression model is tuned using GridSearchCV from scikit-learn. The hyperparameters considered for tuning are:

Regularization strength (C)
Regularization type (penalty)
Solver for optimization (solver)
The best hyperparameters found during the search will be displayed in the output.

# Accuracy
Classification Report
With the provided hyperparameter tuning, you have achieved a 100% accuracy for this binary classification task.

# Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.





