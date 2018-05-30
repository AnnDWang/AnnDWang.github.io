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