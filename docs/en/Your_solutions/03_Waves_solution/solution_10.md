# Problem 10: Multi-Source Wave Superposition Analysis

**Objective:** To simulate and analyze the interference pattern created by multiple point sources emitting spherical waves with a specific amplitude decay.

---

## 1. Mathematical Model
Each source located at $\vec{r_0}$ contributes to the total displacement $u$ at any point $\vec{r}$ according to the following wave equation:
$$u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_0}|^\alpha} \sin(k |\vec{r} - \vec{r_0}| - \omega t)$$

Where:
- **$|\vec{r}-\vec{r_0}|$**: The distance from the source to the observation point.
- **$\alpha$**: Damping parameter (Power-law decay).
- **$k$**: Wave number ($2\pi/\lambda$).
- **$\omega$**: Angular frequency.

## 2. Superposition Principle
The total displacement at any point is the algebraic sum of the displacements from $N$ individual sources:
$$u_{total}(\vec{r},t) = \sum_{i=1}^{N} \frac{A}{|\vec{r}-\vec{r_i}|^\alpha} \sin(k |\vec{r} - \vec{r_i}| - \omega t)$$

## 3. Analysis of Parameter $\alpha$
- **$\alpha = 0$**: Represents a plane-wave-like behavior where amplitude does not decrease with distance.
- **$\alpha = 0.5$**: Typical for surface waves (ripples on water).
- **$\alpha = 1.0$**: Standard spherical wave decay in 3D (Inverse Square Law for Intensity).
- **$\alpha = 2.0$**: Very high damping, waves vanish almost immediately after leaving the source.

**Implementation Note:** The provided HTML animation allows users to dynamically place sources and adjust $\alpha$ to observe these physical transitions in real-time.
