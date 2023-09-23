# someMLclassifiers
CS401 Introduction to Machine Learning Assignment 1 NIT Goa Dr. Veena Thenkanidiyoor

Dataset: 2-dimensional data of 2, 3 or 4 classes:
(a) Linearly separable data set
(b) Nonlinearly separable data set
(c) Overlapping data set

Classifier built:
1) Nearest neighbor classifier
2) K nearest neighbor classifier (Value of K to be chosen experimentally)
3) Reference template based classifier
a. Mean vector as reference template for a class
b. Mean vector and covariance matrix as reference template for a class
4) Bayes classifier-Unimodal Gaussian density
a. Covariance matrix for all the classes is the same and is σ^2I
i. You can obtain the same covariance matrix for all the classes by taking
the average of covariance matrices of all the classes. You can
obtain same variance by averaging all the variances.
b. Full covariance matrix for all the classes and is same for all the classes
i. Same covariance matrix for all the classes may be obtained by taking
a verage of covariance matrices of all the classes
ii. Same covariance matrix for all the classes by computing the
covariance matrix of training data of all the classes combined.
c. Covariance matrix is diagonal and is different for each class
d. Full covariance matrix for each class and is different
