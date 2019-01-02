---
layout: post
title: "[Machine Learning] Linear Regression"
date: 2018-12-08
excerpt: Linear Regression 정리
tags: [Machine Learning]
comment: true
---

# Linear Regression (선형회귀)

## 목표
Linear Regression의 이해와 구현

# (Linear) Hypothesis
+ Linear model이 우리가 가진 데이터에 맞을 것이다 라고 가정하고 시작
+ 현실의 많은 것들이 실제 linear한 패턴을 가지는 경우가 많음

# H(x) = Wx + b
+ data를 가장 잘 표현해주는 최적의 Line을 찾는 공식

# 가장 잘 맞는 Linear model 찾기
+ 우리가 세운 가설(직선) H(x)와 실제 data point의 차이를 계산
+ Cost function (=Loss function)   
  + H(x) - y : 양수와 음수가 동시에 나오기 때문에 문제가 발생함
  + (H(x) - y)^2 : 양수만 나오고, 거리에 대한 패널티가 강함 (사용)
