# Problem 1: Electric Force on a Center Charge

**Given:**
- Square side: $a = 1.0 \, \text{m}$
- Four corner charges: $q_1 = q_2 = q_3 = q_4 = +1.0 \, \text{C}$
- Center charge: $q_{center} = -2.0 \, \text{C}$

---

## Solution:
The distance from each corner to the center ($r$) is half of the diagonal:
$$d = \sqrt{1^2 + 1^2} = \sqrt{2} \, \text{m} \implies r = \frac{\sqrt{2}}{2} \, \text{m}$$

The magnitude of the force from **one** corner charge on the center charge is:
$$F = k \frac{|q_1 \cdot q_{center}|}{r^2} = k \frac{|1.0 \cdot (-2.0)|}{(\sqrt{2}/2)^2} = k \frac{2}{0.5} = 4k$$

## Vector Analysis:
- The force from the top-left charge pulls the center charge toward the top-left.
- The force from the bottom-right charge pulls the center charge toward the bottom-right with the **same magnitude**.
- These two forces are equal in magnitude and opposite in direction, so they cancel each other out ($\vec{F}_{1} + \vec{F}_{3} = 0$).
- Similarly, the forces from the top-right and bottom-left charges also cancel each other out ($\vec{F}_{2} + \vec{F}_{4} = 0$).

**Answer:**
The net electric force on the center charge is **0 N**.
