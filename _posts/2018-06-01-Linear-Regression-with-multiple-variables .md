---
layout: mypost
title: Linear Regression with multiple variables
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

# Multiple features

Linear regression with multiple variables is also known as multivariable linear regression

![notations](1.png)

# Gradient descent for multiple variables

![Gradient descent](2.png)

![Gradient descent](3.png)

# Feature scaling

mean normalization


# Learning rate

确定梯度下降 最终能导致正确的结果，损失函数越来越小

判断收敛的条件

对于足够小的学习率，损失函数应该每次迭代都会减小

学习率太小的话，梯度下降将会用很长时间才能收敛

学习率太大，可能不会每次迭代之后都下降，也可能不会收敛，也可能收敛很慢

# Features and Polynomial Regression 多项式回归

特征的选择

多项式

# Normal equation


![求解theta](4.png)

用这种方法求解theta的话，Feature scaling不是很重要

梯度下降和Normal equation

![选择方法](5.png)

# Normal equation and non-invertibility

![不可逆的原因](6.png)




