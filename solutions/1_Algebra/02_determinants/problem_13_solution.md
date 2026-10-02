# Exercise 13

Let
$$
A=\begin{pmatrix}
1&2&3\\
2&5&7\\
1&0&2
\end{pmatrix}.
$$

Use
$$
R_2\leftarrow R_2-2R_1,
\qquad
R_3\leftarrow R_3-R_1.
$$
These row replacements do not change the determinant:
$$
\det A=
\det\begin{pmatrix}
1&2&3\\
0&1&1\\
0&-2&-1
\end{pmatrix}.
$$

Now use
$$
R_3\leftarrow R_3+2R_2,
$$
again without changing the determinant:
$$
\det A=
\det\begin{pmatrix}
1&2&3\\
0&1&1\\
0&0&1
\end{pmatrix}.
$$

The resulting matrix is upper triangular, therefore
$$
\det A=1\cdot1\cdot1=1.
$$

No row swaps or row scalings were used, so no correction factor is required.
