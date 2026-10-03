## Question

For

$$
f(x)=2\sqrt{x}-\frac{3}{x^2}+x^{3/2},
$$

rewrite the function using powers, determine its domain, compute the
derivative, and compare the domain of the function with the domain of its
derivative.

## Solution

Using $\sqrt{x}=x^{1/2}$ and $1/x^2=x^{-2}$ gives

$$
f(x)=2x^{1/2}-3x^{-2}+x^{3/2}.
$$

The square root requires $x\geq 0$, while the reciprocal term requires
$x\ne 0$. Together these restrictions give

$$
D_f=(0,\infty).
$$

Now apply the power rule term by term:

$$
\begin{aligned}
f'(x)
&=2\cdot\frac12 x^{-1/2}-3\cdot(-2)x^{-3}
  +\frac32 x^{1/2}\\
&=x^{-1/2}+6x^{-3}+\frac32x^{1/2}.
\end{aligned}
$$

Equivalently,

$$
f'(x)=\frac{1}{\sqrt{x}}+\frac{6}{x^3}+\frac32\sqrt{x}.
$$

The derivative contains both $1/\sqrt{x}$ and $1/x^3$, so it is defined
only for $x>0$. Therefore

$$
D_{f'}=(0,\infty)=D_f.
$$

In this example differentiation does not shrink the domain: the original
reciprocal term had already excluded the endpoint $x=0$.
