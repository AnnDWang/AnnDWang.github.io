---
layout: mypost
title: Parameter Learning
categories: [Machine Learning]
---

> 内容来自于[机器学习课程](https://www.coursera.org/learn/machine-learning/home/welcome)

## Gradient Descent 梯度下降

So we have our hypothesis function and we have a way of measuring how well it fits into the data. Now we need to estimate the parameters in the hypothesis function. That's where gradient descent comes in.

use Gradient Descent to minimize some function

:= assignment

= truth assert

learning rate α , how big a step we take when updating my parameter

simultaneous update 同时更新

![simultaneous update](2.png)

## Gradient Descent Intuition

derivate term

![derivate term](3.png)

learning rate 

![learning rate](4.png)


gradient descent can converge to a local minimum, even with the learning rate α fixed.


## Gradient Descent For Linear

convex function

导数部分推导过程

![推导过程](5.png)

The point of all this is that if we start with a guess for our hypothesis and then repeatedly apply these gradient descent equations, out hypothesis will become more and more accurate.

batch gradient descent
