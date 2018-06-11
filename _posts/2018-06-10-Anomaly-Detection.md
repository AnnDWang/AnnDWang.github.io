---
layout: mypost
title: Anomaly Detection
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

# Problem motivation

# Gaussian Distribution

高斯分布 正态分布

![](3.png)

# 异常检测算法

![](4.png)

# Developing and evaluating an anomaly detection system

在训练集上训练之后，用交叉验证集或者测试集进行预测，最终结构用recall、precision来预测结果，用accuracy不准确，因为默认的值可能是0。

可以在验证集上选择epsilon。

# Anomaly detection  vs. supervised learning

![](5.png)

# Choosing what features to use

确定数据是按照高斯分布的，使用直方图

将非高斯分布的转换为高斯分布

![](6.png)

# Multivariate Gaussian Distribution

# Anomaly Detection using the Multivariate Gaussian Distribution

![](7.png)

![](8.png)

![](9.png)

![](10.png)






















