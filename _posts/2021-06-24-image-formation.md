---
layout: post
title: "Image Formation"
categories: journal
tags: [documentation]
image: image-formation.jpg
---
Here is my summarization from the book Computer Vision: Algorithms and Applications by Richard Szeliski.
## 2D points
Representations:
* Vector $\mathbf x=[x\quad y]^T$  
* Homogeneous vector  $\mathbf {\tilde x} = (\tilde x, \tilde y, \tilde w) \in \mathcal P^2$ 
  *  $\mathcal P^2 = \mathcal R^3 - (0,0,0)$ is 2D projective space.  
* Inhomogeneous vector $\mathbf {\tilde x} = \tilde w \mathbf{\bar x} = \tilde{w} (x, y, 1)$
  *  $\bar x = (x,y,1)$ is augmented vector 
  *  $\tilde w = 0$ called points at infinity and have no inhomogeneous representation.  

## 2D lines
Representations:
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
Representations:
* Inhomogeneous coordinate vector $\mathbf x=(x,y,z)\in\mathcal R^3$  
* Homogeneous vector  $\mathbf {\tilde x} = (\tilde x, \tilde y, \tilde w, \tilde z) \in \mathcal P^3$ 
* Inhomogeneous vector $\mathbf {\tilde x} = \tilde w \mathbf{\bar x}$
  *  $\bar x = (x,y,z,1)$ is augmented vector 
## 3D planes
Representations:
* Homogeneous coordinates $\tilde m=(a,b,c,d)$
* Plane equation $\mathbf{\bar x \tilde m} = ax+by+cz+d = 0$
* Normailized plane equation $\mathbf m = (\hat n_x,\hat n_y,\hat n_z,d)=(\mathbf {\hat n},d)$
  * $\lVert\mathbf{\tilde n}\rVert=1$
  * $d$ distance to origin
 * Spherical coordinate $\mathbf{\hat n}=(\cos\theta\cos\phi,\sin\theta\cos\phi,\sin\phi)$
## 3D lines
*It's not pretty like 2D*
Representations:
* Linear combination of two points \

updating...



## References
[1] Richard Szeliski. 2010. <i>Computer Vision: Algorithms and Applications</i> (1st. ed.). Springer-Verlag, Berlin, Heidelberg.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMjI1OTQ4OTI3LDU5MzIyMTAyLC02MzY2NT
k4LDk1NDY4OTkxNCwtNjg5OTc3OTkyLDI2OTA1MjAyOCwyNzU1
MDc1NjMsLTYyNDEyMDk2Nyw0MTQ1NjI0NDksMTAzNDc3MjI4LC
0yMTI5MzI4MTExLDE3MDUxODksLTIwNDM2MzE1NDcsMTIyNzA0
NDgwOSwxNTE1NzA5NDQ3LDY5NzM0ODAwMywtMTMyNzczNDk5OS
wtMTY2MDkyNzkzNywtMTk4MTI3ODAxMCwtNTE5NTU5NjY2XX0=

-->