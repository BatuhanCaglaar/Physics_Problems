# Problem 8: Centripetal Acceleration at the Earth's Equator

The objective is to calculate the centripetal acceleration ($a_c$) of an object resting on the Earth's equator due to the Earth's rotation.

**Given Constants:**
- Earth's Radius at the equator ($R$): $\approx 6378 \text{ km} = 6.378 \times 10^6 \text{ m}$
- Earth's Rotation Period ($T$): $1 \text{ day} = 24 \text{ hours}$

---

## 1) Conversion of Units to SI

To obtain the result in $\text{m/s}^2$, we must convert the period $T$ into seconds:

$$T = 24 \text{ h} \times 60 \text{ min/h} \times 60 \text{ s/min}$$
$$T = 86400 \text{ s}$$

---

## 2) Calculation of Angular Velocity ($\omega$)

The angular velocity ($\omega$) is the rate of rotation in radians per second:

$$\omega = \frac{2\pi}{T}$$
$$\omega = \frac{2\pi}{86400} \approx 7.27 \times 10^{-5} \text{ rad/s}$$

---

## 3) Calculation of Centripetal Acceleration ($a_c$)

The formula for centripetal acceleration is:

$$a_c = \omega^2 \cdot R$$

Substitute the values:

$$a_c = (7.27 \times 10^{-5})^2 \cdot (6.378 \times 10^6)$$

First, compute the square of $\omega$:
$$(7.27 \times 10^{-5})^2 \approx 5.29 \times 10^{-9}$$

Now, multiply by the radius $R$:
$$a_c = (5.29 \times 10^{-9}) \cdot (6.378 \times 10^6)$$
$$a_c = 0.0337 \text{ m/s}^2$$

---

## 4) Comparison with Gravity ($g$)

To put this value into perspective, we compare it with the standard acceleration due to gravity ($g \approx 9.81 \text{ m/s}^2$):

$$\text{Ratio} = \frac{a_c}{g} = \frac{0.0337}{9.81} \approx 0.0034$$

This shows that the centripetal acceleration at the equator is only about **0.34%** of the acceleration due to gravity.

---

## Final Answer

The centripetal acceleration at the Earth's equator is:
$$a_c \approx 0.034 \text{ m/s}^2$$
