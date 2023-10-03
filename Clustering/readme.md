# MachineLearning

This project contains the algorithm implementation of the followings:

## Clustering

### K-Means Clustering

### EM Clustering
EM (Expectation-Maximization) algorithm for clustering is an iterative method used to estimate the parameters of a Gaussian mixture model. Gaussian mixture model assumes that the data is generated from a mixture of several Gaussian distributions with unknown parameters. EM algorithm tries to learn these parameters from the data. The algorithm alternates between two steps: the E-step and the M-step.

E-step: The algorithm computes the posterior probabilities that each data point belongs to each of the Gaussian components.
M-step: The algorithm computes a new estimate of the parameters of each Gaussian component given the responsibilities of the data points
