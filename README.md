# Bayesian_and_Euclidean_classifiers


N is set to 1000, representing the number of data points.

The mean vectors m and covariance matrices Si are defined for two classes.

Class probabilities P1 and P2 are defined for the two classes.

genGaussClasses is used to generate data points for two datasets, X5 and X5_prime, with different class probabilities.

The plotData function is used to plot the generated data with known classes.

Bayesian and Euclidean classifiers (bayesClassifier and euclidClassifier) are applied to both X5 and X5_prime.

computeError is used to calculate classification errors for both Bayesian and Euclidean classifiers on both datasets.

The classification errors are stored in variables (X5_bayes_error, X5_euclid_error, X5_prime_bayes_error, X5_prime_euclid_error).
