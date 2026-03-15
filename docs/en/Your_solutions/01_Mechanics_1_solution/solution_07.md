# Problem 7: Elimination of Time and Interpretation of Acceleration

We are given the path equations in parametric form:
$$x(t) = 2t^2$$
$$y(t) = 3t^3$$

We want to:
1. Eliminate the parameter $t$ to find the trajectory equation.
2. Draw the trajectory using computational tools.
3. Calculate the velocity vector $\vec{v}(t)$ and its magnitude $|\vec{v}(t)|$.
4. Calculate the acceleration vector $\vec{a}(t)$ and its magnitude $|\vec{a}(t)|$.
5. Determine if the acceleration is constant.

---

## 1) Elimination of the Parameter $t$

To find the Cartesian equation of the trajectory, we express $y$ as a function of $x$. First, we solve for $t$ from the $x(t)$ equation:

$$x = 2t^2 \implies t^2 = \frac{x}{2} \implies t = \left( \frac{x}{2} \right)^{1/2}$$

Now, we substitute this expression for $t$ into the equation for $y(t)$:

$$y = 3t^3 = 3 \left[ \left( \frac{x}{2} \right)^{1/2} \right]^3$$

By applying the power rule $(a^m)^n = a^{m \cdot n}$:

$$y = 3 \left( \frac{x}{2} \right)^{3/2} = \frac{3}{2\sqrt{2}} x^{3/2}$$

**Trajectory Equation:**
$$y = \frac{3\sqrt{2}}{4} x\sqrt{x}$$

---

## 2) Velocity Vector and Speed

The velocity vector $\vec{v}(t)$ is defined as the first derivative of the position vector $\vec{r}(t) = (x(t), y(t))$ with respect to time:

$$\vec{v}(t) = \frac{d\vec{r}}{dt} = \left( \frac{dx}{dt}, \frac{dy}{dt} \right)$$

Computing the components term-by-term:
- $v_x = \frac{d}{dt}(2t^2) = 4t$
- $v_y = \frac{d}{dt}(3t^3) = 9t^2$

**Velocity Vector:**
$$\vec{v}(t) = 4t\hat{i} + 9t^2\hat{j}$$

**Speed (Magnitude of Velocity):**
$$|\vec{v}(t)| = \sqrt{v_x^2 + v_y^2} = \sqrt{(4t)^2 + (9t^2)^2}$$
$$|\vec{v}(t)| = \sqrt{16t^2 + 81t^4} = t\sqrt{16 + 81t^2}$$

---

## 3) Acceleration Vector and Magnitude

Acceleration is the derivative of the velocity vector with respect to time:

$$\vec{a}(t) = \frac{d\vec{v}}{dt} = \left( \frac{dv_x}{dt}, \frac{dv_y}{dt} \right)$$

Computing the components:
- $a_x = \frac{d}{dt}(4t) = 4$
- $a_y = \frac{d}{dt}(9t^2) = 18t$

**Acceleration Vector:**
$$\vec{a}(t) = 4\hat{i} + 18t\hat{j}$$

**Magnitude of Acceleration:**
$$|\vec{a}(t)| = \sqrt{a_x^2 + a_y^2} = \sqrt{4^2 + (18t)^2}$$
$$|\vec{a}(t)| = \sqrt{16 + 324t^2}$$

---

## 4) Interpretation: Is the Acceleration Constant?

For an acceleration to be constant, it must not change in magnitude or direction over time. This means its derivative with respect to time must be zero, or simply, it must not contain the variable $t$.

- The x-component $a_x = 4$ is constant.
- The y-component $a_y = 18t$ is a linear function of time.

Since the y-component of the acceleration depends on $t$, the **acceleration is NOT constant.**

---

## 5) Trajectory Visualization

Using WolframAlpha to plot the parametric equations from $t=0$ to $t=2$:

![Trajectory Plot](image_1a3a24.png)

*The plot confirms a power-law relationship, where the curve starts at the origin (0,0) and rises increasingly steeply as $x$ increases.*
