# Section 1 — Mechanics I
## 5. Relative Velocity: River Crossing

### Problem Statement
- **River Flow ($v_r$):** 2 m/s [East]
- **Boat Speed in still water ($v_b$):** 5 m/s
- **River Width ($d$):** 200 meters
- **Goal:** Cross the river directly **North**.

---

### Vector Analysis

To move directly North, the boat's velocity relative to the ground ($\vec{v}_g$) must have no eastward or westward component. This means the boat must head at an angle $\theta$ **West of North** to cancel out the river's eastward drift.

#### 1. Finding the Heading Direction ($\theta$)
We form a right-angled triangle where:
- The hypotenuse is the boat's speed ($v_b = 5$).
- The opposite side is the river's speed ($v_r = 2$).
- The adjacent side is the resulting ground speed ($v_g$).

$$\sin(\theta) = \frac{v_{river}}{v_{boat}} = \frac{2}{5}$$
$$\theta = \arcsin(0.4) \approx 23.58^\circ$$

**Heading:** The boat should head **$23.58^\circ$ West of North**.

#### 2. Calculating the Ground Speed ($v_g$)
Using the Pythagorean theorem:
$$v_g = \sqrt{v_b^2 - v_r^2} = \sqrt{5^2 - 2^2}$$
$$v_g = \sqrt{25 - 4} = \sqrt{21} \approx 4.58 \text{ m/s}$$

#### 3. Calculating the Crossing Time ($t$)
Since the ground speed $v_g$ is directed exactly North, we use it to cover the width of the river:
$$t = \frac{\text{Width}}{v_g} = \frac{200 \text{ m}}{4.58 \text{ m/s}} \approx 43.67 \text{ s}$$

---

### Final Result
- **Heading Angle:** $23.58^\circ$ West of North.
- **Crossing Time:** $\approx 43.67$ seconds.
