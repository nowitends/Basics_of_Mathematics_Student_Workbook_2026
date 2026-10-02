# Exercise 14

The coefficient matrix is
$$
A=\begin{pmatrix}1&2\\k&4\end{pmatrix},
$$
with determinant
$$
\det A=4-2k=2(2-k).
$$

The system $Ax=b$ has exactly one solution for every right-hand side $b$ precisely when $A$ is invertible. Therefore,
$$
k\neq2.
$$

For the exceptional value $k=2$,
$$
A=\begin{pmatrix}1&2\\2&4\end{pmatrix},
$$
and the second row is twice the first.

For example, take
$$
b=\begin{pmatrix}1\\2\end{pmatrix}.
$$
Then both equations reduce to
$$
x_1+2x_2=1,
$$
so there are infinitely many solutions.

On the other hand, take
$$
b=\begin{pmatrix}1\\0\end{pmatrix}.
$$
The equations would be
$$
x_1+2x_2=1,
\qquad
2x_1+4x_2=0.
$$
The left-hand side of the second equation is twice the left-hand side of the first, but the right-hand side is not twice the first right-hand side. Hence the system is inconsistent and has no solution.
