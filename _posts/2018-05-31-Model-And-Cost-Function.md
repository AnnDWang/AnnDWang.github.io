---
layout: mypost
title: Model and Cost Function
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

## Model Representation

To establish notation for future use, we'll use x^(i) to denote the input variables, also called input features. and y^(i) to denote the output or target variable that we are trying to predict.

(i) is simply an index into the training set, and has nothing to do with exponentiation.

## Cost Function

We can measure the accuracy of our hypothesis function by using a cost function. This takes an average difference (actually a fancier version of an average ) of all the results of the hypothesis with inputs from x's and the actual output y's.

![cost function](1.png)

The function is otherwise called the "Squared error function", or "Mean squared error". 

## Cost Function  - Intuition I

形成一个假设，可以尽可能的经过更多的数据点。希望可以获得最好的这条线，使得cost function的值最小化。

## Cost Function - Intuition II

contour plots: 等高线图

当有两个值时，cost function的图是3D的，