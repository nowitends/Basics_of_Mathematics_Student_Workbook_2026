# Exercise 3

Expanding along the first row,
$$
\det A
=
1\begin{vmatrix}3&1\\1&1\end{vmatrix}
-2\begin{vmatrix}0&1\\2&1\end{vmatrix}
=
(3-1)-2(0-2)=6.
$$

Matrix $B$ is obtained by interchanging the first two rows. A single row swap changes the sign of the determinant, so before any further calculation we predict
$$
\det B=-\det A=-6.
$$

Indeed,
$$
B=
\begin{pmatrix}
0&3&1\\
1&2&0\\
2&1&1
\end{pmatrix},
$$
and expansion along the first row gives
$$
\det B
=-3\begin{vmatrix}1&0\\2&1\end{vmatrix}
+1\begin{vmatrix}1&2\\2&1\end{vmatrix}
=-3+(1-4)=-6.
$$

This verifies the row-swap property directly.
