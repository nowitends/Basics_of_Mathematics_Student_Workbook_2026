## Question

Compute

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Explain why the highest-degree terms determine the result.

## Solution

The numerator and denominator are both quadratic polynomials. To compare their
growth as $n$ becomes large, divide every term by the highest power, $n^2$:

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}
=\lim_{n\to\infty}\frac{4-3/n+1/n^2}{2+5/n-7/n^2}.
$$

As $n\to\infty$, both $1/n$ and $1/n^2$ tend to zero. Therefore all terms
coming from powers lower than $n^2$ vanish in the limit, while the leading
coefficients remain. The denominator tends to $2$, so it is nonzero for all
sufficiently large $n$, and the quotient law gives

$$
\lim_{n\to\infty}\frac{4-3/n+1/n^2}{2+5/n-7/n^2}
=\frac{4-0+0}{2+0-0}=2.
$$

Thus the highest-degree terms determine the result because, after scaling by
$n^2$, every lower-degree contribution tends to zero. The limit is
$\boxed{2}$.
