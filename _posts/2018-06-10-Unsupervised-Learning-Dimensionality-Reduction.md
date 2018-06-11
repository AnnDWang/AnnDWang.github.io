---
layout: mypost
title: Unsupervised Learning And Dimensionality Reduction
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

# Data Compression

数据压缩可以减少内存占用空间，还可以加速算法运行

# Data Visualization

# Principal Component Analysis algorithm

预处理数据：feature scaling/mean normalization

compute covariance matrix

compute eigenvectors of matrix

计算出U之后取前k列，转置，乘以X

# Recontruction from compressed representation

近似重构原始的数据

X=Ureduce*X

# choosing the number of principal components

选择K的值

![](1.png)

![](2.png)

# Advice for applying PCA

加速监督学习

PCA可以用于数据压缩：减少所需的内存，加速算法的运行

PCA可以用于可视化，plot 2维或者3维的图

PCA不好的应用：阻止过拟合，应该使用正则化























