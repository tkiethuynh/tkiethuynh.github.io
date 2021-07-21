---
layout: post
title: "Guass Distribution"
categories: journal
tags: [documentation]
image: linear-algebra.jpg
---
## Guassian distribution
Guass distribution or normal distribution is defined by:
$$
\mathcal N(x|\mu,\sigma^2)=\frac{1}{(2\pi\sigma^2)^{1/2}}\exp\left[\frac{1}{2\sigma^2}(x-\mu)^2\right]
$$
where:
* $\mu$ is the mean
* $\sigma^2$ is the variance => $\sigma$ is the standard deviation  

From the above form of distribution, the Guassian is always positive
$$\mathcal N(x|\mu,\sigma^2) > 0$$
It is also normalized
$$\int_{-\infin}^{\infin}\mathcal N(x|\mu,\sigma^2)\mathrm d x=1$$
Here the expectation
$$\mathbb E [x]=\int_{-\infin}^{\infin}\mathcal N (x|\mu,\sigma^2)x\mathrm d x=\mu$$
For the second order moment
$$\mathbb E [x^2]=\int_{-\infin}^{\infin}\mathcal N (x|\mu,\sigma^2)x^2\mathrm d x=\mu^2*\sigma^2$$
The variance
$$\mathrm {var}[x]=\mathbb E[x^2]-\mathbb E [x]^2=\sigma^2$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NTY0MjI1MTksMTkwMjkwNzMwOV19
-->