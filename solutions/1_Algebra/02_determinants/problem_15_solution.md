# Exercise 15

Using multiplicativity of the determinant,
$$
\det(B^{-1}A^TB)
=
\det(B^{-1})\det(A^T)\det(B).
$$

Now
$$
\det(B^{-1})=\frac{1}{\det B}=\frac13,
$$
and transposition preserves the determinant:
$$
\det(A^T)=\det A=-2.
$$

Therefore,
$$
\det(B^{-1}A^TB)
=
\frac13\cdot(-2)\cdot3=-2.
$$

The factors involving $B$ cancel because
$$
\det(B^{-1})\det(B)
=
\frac{1}{\det B}\det B=1.
$$

Hence
$$
\det(B^{-1}A^TB)=-2.
$$
