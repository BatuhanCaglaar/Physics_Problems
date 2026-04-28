# Problem 9: Magnetic Force Vector

**Given:**
- $q = 1.6 \times 10^{-19} \, \text{C}$ (Proton)
- $\vec{v} = 2\hat{i} - 4\hat{j} + \hat{k}$
- $\vec{B} = \hat{i} + 2\hat{j} - \hat{k}$

---

## Solution:
The force is $\vec{F} = q(\vec{v} \times \vec{B})$.
Calculate $\vec{v} \times \vec{B}$:
$$\vec{v} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{vmatrix}$$
$$= \hat{i}(4 - 2) - \hat{j}(-2 - 1) + \hat{k}(4 - (-4))$$
$$= 2\hat{i} + 3\hat{j} + 8\hat{k}$$

Magnitude of cross product: $\sqrt{2^2 + 3^2 + 8^2} = \sqrt{4 + 9 + 64} = \sqrt{77} \approx 8.775$

Magnitude of force:
$$F = q |\vec{v} \times \vec{B}| = (1.6 \times 10^{-19})(8.775) \approx 1.40 \times 10^{-18} \, \text{N}$$

**Answer:**
The force magnitude is **$1.40 \times 10^{-18} \, \text{N}$**.
