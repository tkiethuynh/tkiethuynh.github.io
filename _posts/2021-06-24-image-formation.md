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
## 2D conics
* Conic Sec
updating...

## References
[1] Richard Szeliski. 2010. <i>Computer Vision: Algorithms and Applications</i> (1st. ed.). Springer-Verlag, Berlin, Heidelberg.



<!--stackedit_data:
eyJoaXN0b3J5IjpbNzE1MjI0MjM3LC02MzY2NTk4LDk1NDY4OT
kxNCwtNjg5OTc3OTkyLDI2OTA1MjAyOCwyNzU1MDc1NjMsLTYy
NDEyMDk2Nyw0MTQ1NjI0NDksMTAzNDc3MjI4LC0yMTI5MzI4MT
ExLDE3MDUxODksLTIwNDM2MzE1NDcsMTIyNzA0NDgwOSwxNTE1
NzA5NDQ3LDY5NzM0ODAwMywtMTMyNzczNDk5OSwtMTY2MDkyNz
kzNywtMTk4MTI3ODAxMCwtNTE5NTU5NjY2LDIwNjEyNjIzNTBd
fQ==
-->