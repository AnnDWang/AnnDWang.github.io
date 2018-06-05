---
layout: mypost
title: Neural Networks : Learning
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

# Cost function 

binary classification: 输出只有一个节点

multi-class classification: 输出有k个节点

损失函数：

L: 表示网络中的层数
Sl：表示在l层的单元数目，不包括偏置单元
K：表示输出单元数目或者是分类数目

![神经网络损失函数](1.png)

# Backpropagation algorithm

最小化cost function

![前向传播](2.png)

![后向传播](3.png)

![后向传播算法](4.png)

# Background Intuition

# Gradient checking

确定算法没有错误的话，关掉梯度检验，数值计算方法来计算梯度的话，计算方法非常慢

利用epsilon计算theta矩阵：

```
epsilon = 1e-4;
for i = 1:n,
  thetaPlus = theta;
  thetaPlus(i) += epsilon;
  thetaMinus = theta;
  thetaMinus(i) -= epsilon;
  gradApprox(i) = (J(thetaPlus) - J(thetaMinus))/(2*epsilon)
end;
```

# Random Intialization

在逻辑回归中，初始theta值全为0可以进行。

但是神经网络中，全部初始theta为0的话，会导致隐层的计算结果相同，使得神经网络性能下降。需要随机初始化。

随机初始化：Symmetry breaking

# trainning a neural network

![训练神经网络的6个步骤](5.png)



