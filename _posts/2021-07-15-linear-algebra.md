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
& = \begin{bmatrix}\sum_{j,k}H_{1j}P_{jk}H_{1k} & \cdots & \sum_{j,k}H_{1j}P_{jk}H_{pk} \\ \vdots & \ddots & \vdots \\ \sum_{j,k}H_{pj}P_{jk}H_{1k} & \cdots & H_{pn} \end{bmatrix}
\end{split}
$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI5NDk3NzIzNCwtMTkxMDY2MzM4NSwtMz
YxOTI3MjY1LC03Nzk0MTQ2NzMsMTU3Mzg1MDE2OF19
-->