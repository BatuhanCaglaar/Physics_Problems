# Problem 9: Total Acceleration in Non-Uniform Circular Motion

An object moves in a circle of radius $R = 5$ meters. Its speed as a function of time is given by:
$$v(t) = 2t^2$$

We want to find the **total acceleration** vector magnitude ($a_{total}$) at $t = 2$ seconds.

---

## 1) Theory of Acceleration in Circular Motion

In circular motion, the total acceleration vector $\vec{a}$ consists of two perpendicular components:
1. **Tangential Acceleration ($a_t$):** Changes the magnitude of the velocity (speed).
2. **Centripetal (Radial) Acceleration ($a_c$):** Changes the direction of the velocity.

The total acceleration magnitude is given by the Pythagorean theorem:
$$a_{total} = \sqrt{a_t^2 + a_c^2}$$

---

## 2) Calculation of Tangential Acceleration ($a_t$)

Tangential acceleration is the first derivative of the speed function with respect to time:

$$a_t(t) = \frac{dv}{dt} = \frac{d}{dt}(2t^2)$$
$$a_t(t) = 4t$$

At **$t = 2$** seconds:
$$a_t(2) = 4 \cdot 2 = 8 \text{ m/s}^2$$

---

## 3) Calculation of Centripetal Acceleration ($a_c$)

Centripetal acceleration depends on the instantaneous speed and the radius of the path:

$$a_c(t) = \frac{[v(t)]^2}{R}$$

First, find the speed at **$t = 2$**:
$$v(2) = 2(2^2) = 8 \text{ m/s}$$

Now, substitute $v$ and $R$ into the formula:
$$a_c = \frac{8^2}{5} = \frac{64}{5} = 12.8 \text{ m/s}^2$$

---

## 4) Calculation of Total Acceleration ($a_{total}$)

Using the components calculated above ($a_t = 8$ and $a_c = 12.8$):

$$a_{total} = \sqrt{8^2 + (12.8)^2}$$
$$a_{total} = \sqrt{64 + 163.84}$$
$$a_{total} = \sqrt{227.84}$$

**Final Result:**
$$a_{total} \approx 15.09 \text{ m/s}^2$$

---

## 5) Angular Interpretation

The angle $\phi$ between the total acceleration vector and the radius of the circle can be found using:
$$\tan \phi = \frac{a_t}{a_c} = \frac{8}{12.8} = 0.625$$
$$\phi = \arctan(0.625) \approx 32^\circ$$
