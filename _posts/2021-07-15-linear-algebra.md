---
layout: post
title: "Some Notes about Linear Algebra"
categories: journal
tags: [documentation]
image: linear-algebra.jpg
---
Simplify a general matrix multiplication  
$$
\begin{split}
HPH^T & = \begin{bmatrix}H_{11} & \cdots & H_{1n} \\ \vdots & \ddots & \vdots \\ H_{p1} & \cdots & H_{pn} \end{bmatrix}
\begin{bmatrix}P_{11} & \cdots & P_{1n} \\ \vdots & \ddots & \vdots \\ P_{n1} & \cdots & P_{nn} \end{bmatrix}
\begin{bmatrix}H_{11} & \cdots & H_{p1} \\ \vdots & \ddots & \vdots \\ H_{1n} & \cdots & H_{pn} \end{bmatrix} \\
& = \begin{bmatrix}H_{11}P_{11}H_{11} & \cdots & H_{11}P_{11}H_{p1} \\ \vdots & \ddots & \vdots \\ H_{p1}P_{11}H_{11} & \cdots & H_{p1}P_{11}H_{p1}\end{bmatrix}+\cdots+\\
& = \begin{bmatrix}\sum_{j,k}H_{1j}P_{jk}H_{1k} & \cdots & \sum_{j,k}H_{1j}P_{jk}H_{pk} \\ \vdots & \ddots & \vdots \\ \sum_{j,k}H_{pj}P_{jk}H_{1k} & \cdots & \sum_{j,k}H_{pj}P_{jk}H_{pk}\end{bmatrix}
\end{split}
$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyNzkxMjUxODIsLTE5MTA2NjMzODUsLT
M2MTkyNzI2NSwtNzc5NDE0NjczLDE1NzM4NTAxNjhdfQ==
-->