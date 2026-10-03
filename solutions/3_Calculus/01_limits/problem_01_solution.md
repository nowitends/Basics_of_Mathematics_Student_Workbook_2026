## Question

Compute

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Explain why the highest-degree terms determine the result.

## Solution

Both the numerator and denominator are polynomials of degree two. We therefore
divide every term by $n^2$, the highest power occurring in the quotient:

$$
\frac{4n^2-3n+1}{2n^2+5n-7}
=\frac{4-3/n+1/n^2}{2+5/n-7/n^2}
$$

As $n\to\infty$, the terms $1/n$ and $1/n^2$ tend to zero. The denominator
tends to $2$, so it stays nonzero for all sufficiently large $n$, and the
quotient law applies. Consequently,

$$
\lim_{n\to\infty}\frac{4-3/n+1/n^2}{2+5/n-7/n^2}
=\frac{4-0+0}{2+0-0}=2.
$$

This also explains the dominant-term rule here: after division by $n^2$, all
lower-degree contributions vanish and only the leading coefficients $4$ and
$2$ remain. Thus the requested limit is $\boxed{2}$.
