# Section 1 — Mechanics I
## 3. Path Intersection: Alice vs. Bob

### 1) Do the paths intersect?
For paths to intersect, there must exist $t_1$ and $t_2$ such that $A(t_1) = B(t_2)$.
- $x$: $2 + t_1 = 2t_2 - 1 \implies t_1 = 2t_2 - 3$
- $y$: $8 - 3t_1 = 2t_2 + 2$

Substitute $t_1$:
$$8 - 3(2t_2 - 3) = 2t_2 + 2$$
$$8 - 6t_2 + 9 = 2t_2 + 2 \implies 17 - 6t_2 = 2t_2 + 2$$
$$8t_2 = 15 \implies t_2 = 1.875$$
$$t_1 = 2(1.875) - 3 = 0.75$$

The paths **intersect** at the coordinates $(2.75, 5.75)$.

### 2) Will they collide?
A collision only occurs if they reach the same point at the **same time** ($t_1 = t_2$).
Since $0.75 \neq 1.875$, they **will not collide**. They simply pass through the same point at different times.
