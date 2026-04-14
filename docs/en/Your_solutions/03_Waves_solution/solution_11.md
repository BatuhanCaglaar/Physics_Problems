# Problem 11: Young's Two-Slit Interference Analysis

**Objective:** To simulate the classic Young’s experiment using two coherent point sources to visualize constructive and destructive interference.

---

## 1. Theoretical Framework
When two coherent waves overlap, they interfere. The resultant displacement is given by the sum of two partial waves originating from positions $\vec{r_1}$ and $\vec{r_2}$:
$$u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_1}|} \sin(k |\vec{r} - \vec{r_1}| - \omega t) + \frac{A}{|\vec{r}-\vec{r_2}|} \sin(k |\vec{r} - \vec{r_2}| - \omega t)$$

## 2. Condition for Interference
The type of interference at any point depends on the **Path Difference** ($\Delta L = |d_1 - d_2|$):
- **Constructive Interference (Bright Fringes):** Occurs when $\Delta L = n\lambda$. The waves arrive in phase.
- **Destructive Interference (Dark Fringes):** Occurs when $\Delta L = (n + \frac{1}{2})\lambda$. The waves arrive $180^\circ$ out of phase.

## 3. Variable Effects
- **Distance ($d$):** As the distance between the two slits $|\vec{r_1} - \vec{r_2}|$ increases, the interference fringes become narrower and more frequent.
- **Wavelength ($\lambda$):** Increasing the wavelength results in wider spacing between the interference maxima.

**Implementation Note:** The interactive HTML simulation visualizes the intensity pattern. Dark areas represent destructive interference where the waves cancel each other out, while bright areas represent constructive interference.

file:///C:/Users/batuh/OneDrive/Masa%C3%BCst%C3%BC/3-Q11.html
