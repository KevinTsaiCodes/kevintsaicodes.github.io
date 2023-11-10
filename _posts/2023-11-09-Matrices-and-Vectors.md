---
title: "Matrices and Vectors"
tags:
  - Linear Algebra
---

# Matrix

**Definition**

A matrix (_plural, matrices_) is a rectangular array of scalars. In general, we say that the size of the matrix is _m_ by _n_ if the matrix has m rows and n columns. If _m = n_ we can say this matrix is square. The scalar in the $i$_th_ row and $j$_th_ column is called the $(i, j)$-entry of the matrix.

**Zero-Matrix**

A zero matrix or null matrix is a matrix all of whose entries are zero.

$$
O = 
\begin{bmatrix}
  0 & 0 & 0 \\
  0 & 0 & 0 \\
  0 & 0 & 0
\end{bmatrix}
$$

**Identity Matrix**

An identity Matrix is the matrix which is a square matrix where the diagonal consist of ones and the other elements are all zeros. It is also called as a _Unit Matrix_ or _Elementary Matrix_.

$$
I_{1} = 
\begin{bmatrix}
  1
\end{bmatrix}
$$

$$
I_{2} = 
\begin{bmatrix}
  1 & 0 \\
  0 & 1 \\
\end{bmatrix}
$$

$$
I_{3} = 
\begin{bmatrix}
  1 & 0 & 0 \\
  0 & 1 & 0 \\
  0 & 0 & 1
\end{bmatrix}
$$

**Rotation Matrix**

$$
\begin{bmatrix}
  \cos \theta & - \sin \theta \\
  \sin \theta & \cos \theta
\end{bmatrix}
$$

**Properties of Matrix Addition and Scalar Mulitplication**

Let _A_, _B_, and _C_ be $m x n$, and let _s_ and  _t_ be any scalars. Then
- A + B = B + A
- (A + B) + C = A + (B + C)
- A + O = A
- A + (-A) = O
- (st)A = s(tA)
- s(A + B) = sA + sB
- (s + t)A = sA + tA
