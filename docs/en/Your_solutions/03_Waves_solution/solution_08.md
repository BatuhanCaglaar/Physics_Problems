# Problem 8: Traveling Wave Verification

A function represents a traveling wave only if it maintains its shape while moving, which mathematically requires the form $f(x \pm vt)$.

---

## Analysis:
- **a) $y(x,t) = A \cos(kx^2 - \omega t)$:**
  **No.** The $x^2$ term causes the spatial frequency to change with position. It does not satisfy the linear wave equation.

- **b) $y(x,t) = A(x-vt)^2$:**
  **Yes.** This is in the form $f(x-vt)$. It represents a parabolic pulse traveling at speed $v$ in the positive x-direction.

- **c) $y(x,t) = A \log(x+vt)$:**
  **Yes.** This is in the form $f(x+vt)$. It satisfies the wave equation and represents a pulse traveling in the negative x-direction.
