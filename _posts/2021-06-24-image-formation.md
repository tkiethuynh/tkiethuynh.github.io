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
  * Intersection of two lines $\mathbf{\tilde x =\tilde l_1\times\tilde l_2}$
  * Line joining two points $\mathbf{\tilde l = \tilde x_1\times\tilde x_2}$
* Line equation $\mathbf {\tilde x\tilde l}$ = ax+by+c = 0
* Nomarlized vector $\mathbf l = (\hat n_x,\hat n_y,d)=(\hat n,d)$
  * Normal vector$\lVert\mathbf{\hat n}\rVert=1$
  * Distance to origin $d$.
* Function of rotation angle $\mathbf l=(\cos\theta,\sin\theta,d)$

## 2D conics
* Conic sections $\mathbf {\tilde x^TQ\tilde x}=0$

## 3D points
Representation:
* Inhomogeneous coordinate vector $\mathbf x=(x,y,z)\in\mathcal R^3$  
* Homogeneous vector  $\mathbf {\tilde x} = (\tilde x, \tilde y, \tilde w, \tilde z) \in \mathcal P^3$ 
* Inhomogeneous vector $\mathbf {\tilde x} = \tilde w \mathbf{\bar x}$
  *  $\bar x = (x,y,z,1)$ is augmented vector 
## 3D planes
Representation:
* Homogeneous coordinates $\tilde m=(a,b,c,d)$
* Plane equation $\mathbf{\bar x \tilde m} = ax+by+cz+d = 0$
* Normailized plane equation $\mathbf m = (\hat n_x,\hat n_y,\hat n_z,d)=(\mathbf {\hat n},d)$
  * $\lVert\mathbf{\tilde n}\rVert=1$
  * $d$ distance to origin
 * Spherical coordinate $\mathbf{\hat n}=(\cos\theta\cos\phi,\sin\theta\cos\phi,\sin\phi)$

updating...



## References
[1] Richard Szeliski. 2010. <i>Computer Vision: Algorithms and Applications</i> (1st. ed.). Springer-Verlag, Berlin, Heidelberg.



<!--stackedit_data:
eyJoaXN0b3J5IjpbNTkzMjIxMDIsLTYzNjY1OTgsOTU0Njg5OT
E0LC02ODk5Nzc5OTIsMjY5MDUyMDI4LDI3NTUwNzU2MywtNjI0
MTIwOTY3LDQxNDU2MjQ0OSwxMDM0NzcyMjgsLTIxMjkzMjgxMT
EsMTcwNTE4OSwtMjA0MzYzMTU0NywxMjI3MDQ0ODA5LDE1MTU3
MDk0NDcsNjk3MzQ4MDAzLC0xMzI3NzM0OTk5LC0xNjYwOTI3OT
M3LC0xOTgxMjc4MDEwLC01MTk1NTk2NjYsMjA2MTI2MjM1MF19

-->