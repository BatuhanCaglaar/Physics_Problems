# Problem 10: Relative Velocity in Two Dimensions

Two particles, $A$ and $B$, move in the $xy$-plane. Their position vectors as a function of time are given by:
$$\vec{r}_A(t) = (3t)\hat{i} + (4t^2)\hat{j}$$
$$\vec{r}_B(t) = (2t^2 - 5)\hat{i} + (8t)\hat{j}$$

We want to find:
1. The relative velocity vector of $B$ with respect to $A$ ($\vec{v}_{B/A}$) at $t = 1$ s.
2. The magnitude of this relative velocity.

---

## 1) Velocity of Particle A

Velocity is the time derivative of the position vector:
$$\vec{v}_A(t) = \frac{d\vec{r}_A}{dt} = \frac{d}{dt}(3t)\hat{i} + \frac{d}{dt}(4t^2)\hat{j}$$

Computing term-by-term:
- $v_{Ax} = 3$
- $v_{Ay} = 8t$

At **$t = 1$**:
$$\vec{v}_A(1) = 3\hat{i} + 8\hat{j}$$

---

## 2) Velocity of Particle B

Similarly, for particle $B$:
$$\vec{v}_B(t) = \frac{d\vec{r}_B}{dt} = \frac{d}{dt}(2t^2 - 5)\hat{i} + \frac{d}{dt}(8t)\hat{j}$$

Computing term-by-term:
- $v_{Bx} = 4t$
- $v_{By} = 8$

At **$t = 1$**:
$$\vec{v}_B(1) = 4\hat{i} + 8\hat{j}$$

---

## 3) Relative Velocity Vector ($\vec{v}_{B/A}$)

The relative velocity of $B$ with respect to $A$ is defined as the vector difference:
$$\vec{v}_{B/A} = \vec{v}_B - \vec{v}_A$$

Substitute the vectors found for $t = 1$:
$$\vec{v}_{B/A} = (4\hat{i} + 8\hat{j}) - (3\hat{i} + 8\hat{j})$$
$$\vec{v}_{B/A} = (4 - 3)\hat{i} + (8 - 8)\hat{j}$$

**Resulting Vector:**
$$\vec{v}_{B/A} = 1\hat{i} + 0\hat{j} \text{ (or simply } \hat{i}\text{)}$$

---

## 4) Magnitude of Relative Velocity

The magnitude is calculated using the components:
$$|\vec{v}_{B/A}| = \sqrt{1^2 + 0^2} = \mathbf{1 \text{ m/s}}$$

---

## 5) Physical Interpretation

At $t = 1$ second, both particles are moving upward (y-direction) at the exact same speed ($8 \text{ m/s}$). Therefore, there is no relative motion between them in the vertical axis. The only relative movement is in the x-direction, where particle $B$ is moving $1 \text{ m/s}$ faster than particle $A$.

---

## Final Answer
The relative velocity of $B$ with respect to $A$ at $t=1$ is:
$$\vec{v}_{B/A} = 1\hat{i} \text{ m/s}$$
