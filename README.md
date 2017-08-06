# Finding Donors for CharityML

Supervised Learning (Classification) Project of Udacity Machine Learning Engineer Nanodegree Program


# Abstract

Investigated factors that affect the likelihood of charity donations being made based on real census data. Trained and tested several models, and selected the best one based on F-score and efficiency.


## Project Overview

This project applies supervised learning techniques and an analytical mind on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause.

This project consists of the following tasks:
* Explore the data to learn how the census data is recorded. 
* Apply a series of transformations and preprocessing techniques to manipulate the data into a workable format.
* Propose and evaluate several supervised learners on the data, and consider which is best suited for the solution.
* Optimize the selected model and present it to CharityML.
* Explore the chosen model and its predictions under the hood, to see just how well it's performing when considering the data it's given.


## Machine Learning Theory and Concept

* Supervised Learning: binary classification
* Ensemble Learning with Adaptive Boosting
* Logistic Regression
* Support Vector Machine (SVM)
* Naive Bayes Classifier
* Precision, Recall, Accuracy
* F1 Score: Useful when positive training examples are far more than negative ones, or vice versa.


## Technical Skills

* __sklearn.ensemble.AdaBoostClassifier__: select important features
* __sklearn.linear_model.LogisticRegression__: logistic regression
* __sklearn.svm.LinearSVC__: SVM with linear kernel
* __sklearn.naive_bayes.GaussianNB__: Naive Bayes Classifier
* __sklearn.model_selection.ShuffleSplit__: split labeled data into training and validation sets.


## Development Environment

* OpenSUSE Linux 42.2
* Anaconda 4.4 with Python 2.7
* pandas, numpy, sklearn
