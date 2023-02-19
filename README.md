# 

# Linear Algebra notes
A matrix is a "different form" of writing a series or system of linear equations such as:
$$4x_1 + 3x_2 + 4x_3 = 2 \\

2x_1 + 5x_2 + 2x_3 = 5 \\

7x_1 + 1x_2 + 9x_3 = 10$$

In the form: 
$$\begin{bmatrix} a_{1,1} & \cdots & a_{1,n}\\
                                    \vdots & & \vdots \\
                                    a_{n,1} & \cdots & a_{n,n} \end{bmatrix} = \begin{bmatrix} 4 & 3 & 4 \\ 2 & 5 & 2 \\ 7 & 1 & 9 \end{bmatrix}$$
                                    
## Singular and non-singular
Singular matrixes 

## Determinant
If $det A = 0$ the matrix is singular, otherwise it is non-singular. 
Mathematically it's a bit more complicated, but its written as: 
$$det(A) = \begin{vmatrix} a_{1,1} & \cdots & a_{1,n}\\
                                    \vdots & & \vdots \\
                                    a_{n,1} & \cdots & a_{n,n} \end{vmatrix} = \sum_{\sigma \in S_n} \left( sgn(\sigma)\prod_{i=1}^n \right) = \sum_{\sigma \in S_n} sgn(\sigma)a_{1,\sigma_1} \cdots a_{n,\sigma_n}$$