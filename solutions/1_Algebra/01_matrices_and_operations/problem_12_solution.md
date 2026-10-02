# Exercise 12

$$A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\quad
A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\quad
A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}.$$

So the formula should be
$$A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}.$$

Assume it is true for $n$. Then
$$A^{n+1}=A^nA
=\begin{pmatrix}1&n\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
=
\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.$$

induction step works so formula is ok.
