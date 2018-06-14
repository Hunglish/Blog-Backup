---
title: Logistic Regression的思考
date: 2018-03-21 15:03:58
tags: Algorithm
categories: Machine Learning
---

Spark Mllib 在做LR的时候，官方demo里给出了两个输出一个是coefficient 还有一个是intercept 那么这两个变量是什么意思？

我们回顾一下LR模型：hθ(x)=1/1+e(−θTx)

θTx 就是 θx + b  coefficient就是系数矩阵，而intercept就是截距的意思，就是这个b
