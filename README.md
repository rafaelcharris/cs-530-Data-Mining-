# CS 530 Data Mining

This repository contains my homeworks for the Data Mining course at Chapman University.

## Built by me
These notebooks have 'hand-made' versions of different alogithtms and I compare them with the `sckit-learn` versions.

* `Naive Bayes Classifier.ipynb`: In this notebook I apply Naive Bayes Classifier to a breast cancer data set, and compare my version with `scikit-learn` built in version.
 * `Random Forest.ipynb`: In this notebook, I implement a Random Forest algorithm by hand. Later, I trained and test it on the famous iris data set, and compare my result with the `scikit-learn`'s built-in Random Forest. `scikit-learn`'s one was much better than mine.
* `Decision Trees.ipynb`:  In this notebook, I implement a Decision Tree by hand. I trained the model on a data set that shows information that shows weather conditions for tennis matches. The idea is to predict whether the match was played or not. I then compared the results of my algorithm to the built-in in `scikit-learn`.
* `LinearRegression.ipynb`: In this notebook, I implement an OLS regression 'by hand' on a data set of school achievement in portuguesse high schools. Different to how it is used in economics and other social sciences, I use the OLS to predict grades in a test dataset in a Machine Learning fashion.

## Aplications

In these notebooks, I train 'sckit-learn' and keras models on example data sets.

* `Neural Networks Part 1.ipynb`: In this notebook, I implement a neural network using keras to predict house prices
* `Neural Networks Part 2.ipynb`: In this notebook, I fine tune a HuggingFace model that classify tweets as ironic
* `Regularized Logistic Regressions.ipynb`: In this notebook, I run logistic regressions with different regularizations (l1, l2, and both), and a Naive Bayes. I use all this algorithms to predict income, and compare the out-of-sample accuracy.
* `DigitRecognition.ipynb`: In this notebook, I run different machine learning models, and I use cross-validation to tune the hyper-parameters.
