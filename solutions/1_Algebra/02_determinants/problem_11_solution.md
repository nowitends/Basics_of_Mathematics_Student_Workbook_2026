# Exercise 11

Consider
$$
A=\begin{pmatrix}
1&2&3\\
1&3&4\\
1&4&6
\end{pmatrix}.
$$

Apply
$$
R_2\leftarrow R_2-R_1,
\qquad
R_3\leftarrow R_3-R_1.
$$
Both are row-replacement operations and therefore leave the determinant unchanged:
$$
\det A=
\det\begin{pmatrix}
1&2&3\\
0&1&1\\
0&2&3
\end{pmatrix}.
$$

Next apply
$$
R_3\leftarrow R_3-2R_2,
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

The final matrix is upper triangular, hence
$$
\det A=1\cdot1\cdot1=1.
$$
