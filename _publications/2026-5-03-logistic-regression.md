---
title: "Hyperparameter Tuning and Regularization Paths in Logistic Regression"
collection: publications
category: school
permalink: /publication/2026-5-03-logistic-regression
excerpt: 'In this project, we implemented logistic regression for binary classification using mini-batch stochastic gradient descent (SGD) with L2 regularization and applied it to the UCI Spambase dataset.'
# date:
# venue: 
#slidesurl: 
paperurl: "/files/comp551_2.pdf/"
#bibtexurl: 
#citation:
---

In this project, we implemented logistic regression for binary classification using mini-batch stochastic gradient descent (SGD) with L2 regularization and applied it to the UCI Spambase dataset. The dataset was intentionally split into a very small training set (5%) and a large held-out test set (95%) in order to emphasize overfitting and highlight the bias-variance trade-off. We first examined optimization behaviour under different batch sizes and learning rates, comparing training dynamics with and without L2 regularization. We then performed K-fold cross validation to tune hyperparameters, including learning rate, batch size, number of epochs, and regularization strength. Next, we explicitly demonstrated the bias-variance trade-off sweeping the L2 regularization parameter and evaluating training and validation performance. Finally, we studied L1-regularized logistic regression to visualize the regularization path, observe sparsity patterns in feature coefficients, and examine the trade-off between interpretability and predictive performance.

[View Paper](/files/comp551_2.pdf/) |
[Download Code](/files/comp551_2_code.ipynb)

![Model Architecture](/images/comp551a2graph.png)