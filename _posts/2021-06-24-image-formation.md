---
layout: post
title: "Image Formation"
categories: journal
tags: [documentation]
image: image-formation.jpg
---
Here is my summarization from the book Computer Vision: Algorithms and Applications by Richard Szeliski.
## 2D points
Representation:
* Vector $\mathbf x=[x\quad y]^T$  
* Homogeneous vector  $\tilde {\mathbf x} = (\tilde x, \tilde y, \tilde w) \in \mathcal P^2$  where $\mathcal P^2 = \mathcal R^3 - (0,0,0)$ is 2D projective space.  
* Inhomogeneous vector $\tilde {\mathbf x} = \tilde w \bar{\mathbf x} = \tilde{w} (x, y, 1)$  where $\bar x = (x,y,1)$ is augmented vector -> $\tilde w = 0$ called points at infinity and have no inhomogeneous representation.  

## 2D lines
Representation:
* Homogeneous coordinates $\tilde {\mathbf l} = (a,b,c)$
* Line equation $\tilde {\mathbf x} \tilde{\mathbf l}$ = ax+by+c = 0
* Nomarlized vector $\mathbf l = (\hat n_x,\hat n_y,d)=(\hat n,d)$
  * Normal vector$\lVert\hat n\rVert=1$
  * Distance to origin $d$.
* Function of rotation angle $\mathbf l=(\cos\theta,\sin\theta,d)$
*
updating...

## References
[1] Richard Szeliski. 2010. <i>Computer Vision: Algorithms and Applications</i> (1st. ed.). Springer-Verlag, Berlin, Heidelberg.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE5MzA3MzY5MCwtNjM2NjU5OCw5NTQ2OD
k5MTQsLTY4OTk3Nzk5MiwyNjkwNTIwMjgsMjc1NTA3NTYzLC02
MjQxMjA5NjcsNDE0NTYyNDQ5LDEwMzQ3NzIyOCwtMjEyOTMyOD
ExMSwxNzA1MTg5LC0yMDQzNjMxNTQ3LDEyMjcwNDQ4MDksMTUx
NTcwOTQ0Nyw2OTczNDgwMDMsLTEzMjc3MzQ5OTksLTE2NjA5Mj
c5MzcsLTE5ODEyNzgwMTAsLTUxOTU1OTY2NiwyMDYxMjYyMzUw
XX0=
-->