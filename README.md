Implementation using **only** the Numpy library of classifiers and the evaluation of their performance on the IRIS PLANT and the PIMA INDIANS DIABETES datasets.

The classifiers implemented are the following:
---
- A k-nearest neighbours (k-NN) classifier, allowing for the selection of the distance metric between euclidean distance, manhattan distance, Mahalanobis distance and Chebyshev distance.
- A Bayesian classifier, able to utilize different assumptions about the covariance of the features:
  - diagonal covariance matrices
  - non-diagonal covariance matrices
  - Components of the feature vectors that are mutually statistically independent (Naïve Bayes approach)
- Finally, the single-layer perceptron algorithm was implemented.
