## Question

Compute

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4},
\qquad
\lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}.
$$

Compare the two cases and formulate a general observation about the degrees of
the polynomials in the numerator and denominator.

## Solution

For the first limit, the denominator has the higher degree. Dividing the
numerator and denominator by $n^2$ gives

$$
\frac{3n+1}{n^2+4}
=\frac{3/n+1/n^2}{1+4/n^2}.
$$

Every term containing $1/n$ or $1/n^2$ tends to zero, while the denominator
tends to $1$. Therefore

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4}=0.
$$

For the second limit, the numerator has degree three and the denominator has
degree two. Dividing by $n^2$ makes the remaining growth explicit:

$$
\frac{2n^3-n}{5n^2+1}
=\frac{2n-1/n}{5+1/n^2}.
$$

The numerator tends to $+\infty$ like $2n$, whereas the denominator tends to
the positive number $5$. Hence

$$
\lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}=+\infty.
$$

In general, for a quotient of polynomials as $n\to\infty$, a numerator of
lower degree gives limit $0$. Equal degrees give the ratio of the leading
coefficients. If the numerator has higher degree, the magnitude is unbounded;
the sign and whether the limit is $+\infty$ or $-\infty$ must be determined
from the leading terms and the direction of the limit.
