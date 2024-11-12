# penguin
This repo contains code for analysing the Penguins dataset, divided into three main parts:

1. EDA
2. Supervised Learning with Classification, which includes: K Neighbors Classifier, Ensemble Classification via Random Forest, compared them to a baseline model using DummyClassifier

In this test, the goal is to predict the penguin species, and the 3 methods are compared using a statistical t-test.

3. Unsupervised Learning

In this section, I aim to reduce features and project the data into 3 dimensions using Principal Component Analysis. The result shows that 3 principal components cover 90.12% of the variance. I then apply Gaussian Mixture Model and compare its performance to K-means clustering.

A t-test is used to compare the performance of the baseline model (K-means clustering) with GMM.
