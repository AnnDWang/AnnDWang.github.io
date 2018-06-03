---
layout: mypost
title: Logistic Regression and Regularization
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

# Classification

classification并不是线性回归的

提出了logistic regression

# Hypothesis Representation

Sigmoid function = Logistic Function

![interpretation of hypothesis output](8.png)

# Decision Boundary

# Cost Function

对于Logistic function而言 ，我们不能使用和线性回归一样的cost function，否则会导致局部最优，并且不收敛

![cost function](9.png)

# Simplified Cost Function and Gradient Descent

![cost function](10.png)

 maximum likelihood estimation: 最大似然估计

![J](11.png)

![梯度下降](12.png)

feature scaling对于逻辑回归也有用处，可以加快梯度下降的速度

![向量表示](13.png)

# Advanced Optimization

![优化方法](14.png)

# Multi-class clasification: One-vs-all

![多分类](15.png)

# The problem of overfitting

欠拟合 高偏差 没有很好地拟合训练数据

过度拟合 高方差 变量太多，没有足够的数据来约束这个变量过多的模型，就是过度拟合

过度拟合的没法泛化到新的数据样本。

泛化是指一个假设模型能够应用到新样本的能力

![解决过拟合的方法](15.png)

# Cost Function

![惩罚太大](17.png)

# regularized linear regression

![梯度下降的公式](18.png)

![正则化后求解公式](19.png)

# regularized logistic regression

![正则化后cost function](20.png)

![正则化后梯度下降](21.png)