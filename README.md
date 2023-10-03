# MachineLearning

This project contains different projects of machine learning

## 1. Clustering

### K-Means Clustering

### EM Clustering
EM (Expectation-Maximization) algorithm for clustering is an iterative method used to estimate the parameters of a Gaussian mixture model. Gaussian mixture model assumes that the data is generated from a mixture of several Gaussian distributions with unknown parameters. EM algorithm tries to learn these parameters from the data. The algorithm alternates between two steps: the E-step and the M-step.

E-step: The algorithm computes the posterior probabilities that each data point belongs to each of the Gaussian components.
M-step: The algorithm computes a new estimate of the parameters of each Gaussian component given the responsibilities of the data points


## 2. Fake News Detector

### Problem statement
In today's world articles, posts, news can be generated and spread easily. Analyzing the articles, detecting misinformation and stopping from spreading is crucial to maintaing the safety in society. Fake information can spread false information, leading people to make incorrect decisions based in inaccruate data. Fake information can impact the election results, economic, social, health and safety of people.

Dataset: https://www.kaggle.com/datasets/jainpooja/fake-news-detection

### Overview
This application generates different models to identify the fake news and evaluate the performance of those models. As part of this project, we are considering following methods to create the models:

Passive Aggressive Classifier
Gradient Boost Classifier
Support Vector
Extreme Gradient Boost Classifier
I also used same methods on news text and tokenized/lemmanized text to evaluate the performance of the different models.
