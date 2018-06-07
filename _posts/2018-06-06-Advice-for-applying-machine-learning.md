---
layout: mypost
title: Advice For Applying Machine Learning And Machine Learning System Design
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

# Deciding what to try next

Machine learning diagnostic

# Evaluating a Hypothesis

将数据集分为训练集和测试集

从训练集来获取参数

在测试集中计算error

Misclassification error --- 0/1 misclassification error 误分类率

# Model Selection and Train/Validation/Test Sets

模型选择 训练集 验证集 测试集

cross validation 交叉验证

![](1.png)

# Diagnosing bias vs. variance

偏差和方差

![](2.png)

![](3.png)

# Regularization and Bias/Variance

选择lambda：

![](4.png)

# Learning curves

![high bias](5.png)

![high variance](6.png)

对高bias的情况来说，更多的训练数据并不会有什么帮助

但是对于高方差的算法而言，更多的训练集有用

# Deciding what to do next visited

![不同的方法的作用](7.png)

小型的神经网络容易欠拟合

大型神经网络容易过拟合，但是可以通过正则化来修正。



