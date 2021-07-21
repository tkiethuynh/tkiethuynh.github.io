---
layout: post
title: "Linear Algebra Notes"
categories: journal
tags: [documentation]
image: linear-algebra.jpg
---
## Simplify a general matrix multiplication  
Suppose $H$ a matrix $p\times n$, $P$ a matrix $n\times n$
$$
\begin{split}
HPH^T & = \begin{bmatrix}H_{11} & \cdots & H_{1n} \\ \vdots & \ddots & \vdots \\ H_{p1} & \cdots & H_{pn} \end{bmatrix}
\begin{bmatrix}P_{11} & \cdots & P_{1n} \\ \vdots & \ddots & \vdots \\ P_{n1} & \cdots & P_{nn} \end{bmatrix}
\begin{bmatrix}H_{11} & \cdots & H_{p1} \\ \vdots & \ddots & \vdots \\ H_{1n} & \cdots & H_{pn} \end{bmatrix} \\
& = \begin{bmatrix}H_{11}P_{11}H_{11} & \cdots & H_{11}P_{11}H_{p1} \\ \vdots & \ddots & \vdots \\ H_{p1}P_{11}H_{11} & \cdots & H_{p1}P_{11}H_{p1}\end{bmatrix}+\cdots+\begin{bmatrix}H_{1n}P_{nn}H_{1n} & \cdots & H_{1n}P_{nn}H_{pn} \\ \vdots & \ddots & \vdots \\ H_{pn}P_{nn}H_{1n} & \cdots & H_{pn}P_{nn}H_{pn}\end{bmatrix}\\
& = \begin{bmatrix}\sum_{j,k}H_{1j}P_{jk}H_{1k} & \cdots & \sum_{j,k}H_{1j}P_{jk}H_{pk} \\ \vdots & \ddots & \vdots \\ \sum_{j,k}H_{pj}P_{jk}H_{1k} & \cdots & \sum_{j,k}H_{pj}P_{jk}H_{pk}\end{bmatrix}\\
&=H_1P_{11}H_1^T+\dots+H_nP_{nn}H_n^T\\
&=\sum_{j,k}H_jP_{jk}H_k^T
\end{split}
$$
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDIwMDIxNDQyLC0yMDMyMjY2MzQxLC0xOT
EwNjYzMzg1LC0zNjE5MjcyNjUsLTc3OTQxNDY3MywxNTczODUw
MTY4XX0=
-->