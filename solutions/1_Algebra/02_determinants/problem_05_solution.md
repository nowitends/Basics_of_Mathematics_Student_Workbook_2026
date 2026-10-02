# Exercise 5

Start from
$$
A=\begin{pmatrix}
1&2&3\\
2&1&0\\
-1&4&2
\end{pmatrix}.
$$

Use the row replacements
$$
R_2\leftarrow R_2-2R_1,
\qquad
R_3\leftarrow R_3+R_1.
$$
Neither operation changes the determinant. We obtain
$$
\begin{pmatrix}
1&2&3\\
0&-3&-6\\
0&6&5
\end{pmatrix}.
$$

Expanding along the first column,
$$
\det A
=
\det\begin{pmatrix}
-3&-6\\
6&5
\end{pmatrix}
=(-3)\cdot5-(-6)\cdot6
=-15+36=21.
$$

Hence
$$
\det A=21.
$$
