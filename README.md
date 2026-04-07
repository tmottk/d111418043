**Initialization:**

$$
\hat{h}(0) = \text{zeros}(p)
$$

**Computation:** For \( n = 0, 1, 2, \ldots \)

$$
x(n) = [x(n), x(n-1), \ldots, x(n-p+1)]^T
$$

$$
e(n) = d(n) - \hat{h}^H(n)x(n)
$$

$$
\hat{h}(n+1) = \hat{h}(n) + \frac{\mu\, e^*(n)\, x(n)}{x^H(n)x(n)}
$$
