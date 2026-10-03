# Exercise 1. Dominant Terms in a Sequence — Solution

Compute
$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Divide the numerator and denominator by the highest power of $n$, namely $n^2$:

$$
\begin{aligned}
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
&=
\lim_{n\to\infty}
\frac{4-\frac{3}{n}+\frac{1}{n^2}}
{2+\frac{5}{n}-\frac{7}{n^2}}.
\end{aligned}
$$

Since
$$
\frac{1}{n}\to 0
\qquad\text{and}\qquad
\frac{1}{n^2}\to 0
\quad\text{as }n\to\infty,
$$
we obtain

$$
\boxed{
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
=
\frac{4}{2}=2
}.
$$

The highest-degree terms determine the result because, for large $n$, the lower-degree terms are negligible compared with $n^2$:

$$
4n^2-3n+1\sim 4n^2,
\qquad
2n^2+5n-7\sim 2n^2.
$$

Therefore the quotient behaves asymptotically like

$$
\frac{4n^2}{2n^2}=2.
$$

**Answer:** $\boxed{2}$.
