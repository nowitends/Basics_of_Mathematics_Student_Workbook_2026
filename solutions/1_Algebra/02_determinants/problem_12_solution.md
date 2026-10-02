# Exercise 12

Begin with the suggested operation
$$
R_2\leftarrow R_2-2R_1.
$$
It does not change the determinant and gives
$$
\begin{pmatrix}
1&2&3\\
0&0&t-6\\
0&1&1
\end{pmatrix}.
$$

Expanding along the second row,
$$
\det A(t)
=-(t-6)
\det\begin{pmatrix}1&2\\0&1\end{pmatrix}
=6-t.
$$

The matrix is not invertible exactly when
$$
6-t=0,
$$
so
$$
t=6.
$$

For this value, the original second row becomes
$$
(2,4,6)=2(1,2,3),
$$
so the first two rows are linearly dependent. This explains directly why the determinant vanishes.
