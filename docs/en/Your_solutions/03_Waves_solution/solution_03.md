# Problem 3: Formation of Standing Waves

**Given Equations:**
- $y_1(x, t) = A \sin(kx - \omega t)$
- $y_2(x, t) = A \sin(kx + \omega t)$

---

## Solution:
Using the trigonometric sum-to-product identity:
$$\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha+\beta}{2}\right) \cos\left(\frac{\alpha-\beta}{2}\right)$$

The resulting wave $y_{\text{res}} = y_1 + y_2$ is:
$$y_{\text{res}}(x, t) = A [\sin(kx - \omega t) + \sin(kx + \omega t)]$$
$$y_{\text{res}}(x, t) = \mathbf{2A \sin(kx) \cos(\omega t)}$$

**Node Identification:**
Nodes are points where the displacement is always zero. This occurs when:
$$\sin(kx) = 0 \implies kx = n\pi \quad (n = 0, 1, 2, \dots)$$
Since $k = 2\pi/\lambda$:
$$\frac{2\pi}{\lambda}x = n\pi \implies \mathbf{x = n \frac{\lambda}{2}}$$

**Answer:** The resulting standing wave is $2A \sin(kx) \cos(\omega t)$ and nodes are located at every **half-wavelength**.
