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
* Homogeneous vector  $\mathbf {\tilde x} = (\tilde x, \tilde y, \tilde w) \in \mathcal P^2$ 
  *  $\mathcal P^2 = \mathcal R^3 - (0,0,0)$ is 2D projective space.  
* Inhomogeneous vector $\mathbf {\tilde x} = \tilde w \mathbf{\bar x} = \tilde{w} (x, y, 1)$
  *  $\bar x = (x,y,1)$ is augmented vector 
  *  $\tilde w = 0$ called points at infinity and have no inhomogeneous representation.  

## 2D lines
Representation:
* Homogeneous coordinates $\mathbf {\tilde l} = (a,b,c)$
  * Intersection of two lines $\mathbf{\tilde x} =\mathbf{\tilde l_1}\times\mathbf{\tilde l_2}$
  * Line joining two points $\tilde{\mathbf l} = \mathbf{\tilde x_1}\times\mathbf{\tilde x_2}$
* Line equation $\mathbf {\tilde x} \mathbf{\tilde l}$ = ax+by+c = 0
* Nomarlized vector $\mathbf l = (\hat n_x,\hat n_y,d)=(\hat n,d)$
  * Normal vector$\lVert\hat n\rVert=1$
  * Distance to origin $d$.
* Function of rotation angle $\mathbf l=(\cos\theta,\sin\theta,d)$
* 
updating...

## References
[1] Richard Szeliski. 2010. <i>Computer Vision: Algorithms and Applications</i> (1st. ed.). Springer-Verlag, Berlin, Heidelberg.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTgzNjQ2MTYwOSwtNjM2NjU5OCw5NTQ2OD
k5MTQsLTY4OTk3Nzk5MiwyNjkwNTIwMjgsMjc1NTA3NTYzLC02
MjQxMjA5NjcsNDE0NTYyNDQ5LDEwMzQ3NzIyOCwtMjEyOTMyOD
ExMSwxNzA1MTg5LC0yMDQzNjMxNTQ3LDEyMjcwNDQ4MDksMTUx
NTcwOTQ0Nyw2OTczNDgwMDMsLTEzMjc3MzQ5OTksLTE2NjA5Mj
c5MzcsLTE5ODEyNzgwMTAsLTUxOTU1OTY2NiwyMDYxMjYyMzUw
XX0=
-->