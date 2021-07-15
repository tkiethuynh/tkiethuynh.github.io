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
\begin{bmatrix}H_{11} & \cdots & H_{p1} \\ \vdots & \ddots & \vdots \\ H_{1n} & \cdots & H_{pn} \end{bmatrix}=
\begin{bmatrix}H_{11} & \cdots & H_{1n} \\ \vdots & \ddots & \vdots \\ H_{p1} & \cdots & H_{pn} \end{bmatrix} \\
& = \begin{bmatrix}\sum_H_{11} & \cdots & H_{1n} \\ \vdots & \ddots & \vdots \\ H_{p1} & \cdots & H_{pn} \end{bmatrix}
\end{split}
$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMDE5NTMyOTUsLTE5MTA2NjMzODUsLT
M2MTkyNzI2NSwtNzc5NDE0NjczLDE1NzM4NTAxNjhdfQ==
-->