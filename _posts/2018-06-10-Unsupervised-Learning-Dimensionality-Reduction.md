---
layout: mypost
title: Unsupervised Learning And Dimensionality
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

# Unsupervised Learning introduction

without labels

clustering

# K-means Algorithm

1. 随机选择k个中心点（聚类数目）
2. 通过判断每个点和中心点的距离，给它们确定聚类。
3. 均值计算新的中心点，重新聚类，迭代直到中心点不变以及每个点所属聚类不变。

# Optimization objective

最小化点到中心点的距离平方之和

# Random Initialization

# choosing the number of cluster

最常见的方法是通过观察图来确定数目

Elbow method，选择不同的k值，画出cost function J的值

根据聚类的目的来确定数目