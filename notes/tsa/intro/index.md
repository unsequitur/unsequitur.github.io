---
layout: page
title: Introduction
weight: 3
---
The art of time-series modeling is to identify the joint distribution of a set
of random variables $$X_1, X_2, \ldots, X_n$$ from a single realization of
those random variables $$x_1,x_2,\ldots, x_n$$. While this problem might seem
vastly underconstrained, assumptions of normality and stationarity greatly
simplify and regularize this problem.

One popular time series model is it $$MA(1)$$ model, which may be described as

$$X_{t+1} = e_t + \alpha e_{t-1}$$
