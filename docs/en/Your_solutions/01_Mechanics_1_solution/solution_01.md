# Section 1 — Mechanics I
## 1. Projectile Motion

### Problem Statement
Initial velocity $v_0 = 100 \text{ m/s}$ at an angle $\theta = 37^\circ$. (Assume $\sin 37^\circ \approx 0.6$ and $\cos 37^\circ \approx 0.8$, $g = 9.8 \text{ m/s}^2$).

---

### 1) Differential Equations of Motion
Assuming no air resistance, the only force is gravity acting downwards ($y$-direction).
- **Horizontal ($x$):** $m \frac{d^2x}{dt^2} = 0 \implies a_x = 0$
- **Vertical ($y$):** $m \frac{d^2y}{dt^2} = -mg \implies a_y = -g$

### 2) Time of Flight ($t_{flight}$)
The projectile hits the ground when $y(t) = 0$.
$$y(t) = (v_0 \sin \theta)t - \frac{1}{2}gt^2 = 0$$
$$t_{flight} = \frac{2 v_0 \sin \theta}{g} = \frac{2 \cdot 100 \cdot 0.6}{9.8} \approx 12.24 \text{ s}$$

### 3) Maximum Height ($H$)
Occurs when $v_y = 0$:
$$H = \frac{(v_0 \sin \theta)^2}{2g} = \frac{(100 \cdot 0.6)^2}{2 \cdot 9.8} = \frac{3600}{19.6} \approx 183.67 \text{ m}$$

### 4) Range ($R$)
$$R = (v_0 \cos \theta) \cdot t_{flight} = \frac{v_0^2 \sin(2\theta)}{g}$$
$$R = \frac{100^2 \cdot \sin(74^\circ)}{9.8} \approx \frac{10000 \cdot 0.96}{9.8} \approx 979.59 \text{ m}$$
