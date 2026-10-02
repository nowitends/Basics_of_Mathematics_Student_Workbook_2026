# Exercise 10

The second row is exactly twice the first:
$$
(2,4,6)=2(1,2,3).
$$

Therefore the rows are linearly dependent. A matrix with linearly dependent rows has determinant zero, so
$$
\det\begin{pmatrix}
1&2&3\\
2&4&6\\
0&1&5
\end{pmatrix}=0.
$$

Equivalently, the rows do not span three independent directions, so the matrix cannot be invertible.
