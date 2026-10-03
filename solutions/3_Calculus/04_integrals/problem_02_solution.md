## Question

Compute $\int(2\sqrt{x}+3/x^2-x^{1/3})\,dx$, first rewriting powers and determining the original domain, then verify by differentiation.

## Solution

The integrand can be written as

$$2x^{1/2}+3x^{-2}-x^{1/3}.$$

Because the square root requires a nonnegative input, the domain of the original expression is $x\geq0$.

Applying the power rule term by term,

$$\int\left(2x^{1/2}+3x^{-2}-x^{1/3}\right)dx
=\frac43x^{3/2}-\frac3x-\frac34x^{4/3}+C.$$

On differentiating,

$$\left(\frac43x^{3/2}-\frac3x-\frac34x^{4/3}+C\right)'
=2x^{1/2}+3x^{-2}-x^{1/3},$$

which recovers the integrand.
