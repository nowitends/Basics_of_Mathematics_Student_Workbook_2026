# Exercise 2

For
$$
A=\begin{pmatrix}
1&2&-1\\
0&3&4\\
2&1&5
\end{pmatrix},
$$
Sarrus' rule gives
$$
\det A
=1\cdot3\cdot5+2\cdot4\cdot2+(-1)\cdot0\cdot1
-(-1)\cdot3\cdot2-2\cdot0\cdot5-1\cdot4\cdot1.
$$
Thus
$$
\det A=15+16+0+6-0-4=33.
$$

As a check, perform the determinant-preserving row operation
$$
R_3\leftarrow R_3-2R_1.
$$
Then
$$
\det A=
\det\begin{pmatrix}
1&2&-1\\
0&3&4\\
0&-3&7
\end{pmatrix}
=
\det\begin{pmatrix}3&4\\-3&7\end{pmatrix}
=21+12=33.
$$

The independent check confirms the result.
