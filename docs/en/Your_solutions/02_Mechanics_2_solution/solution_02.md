# Problem 2: Harmonic Motion and Energy Analysis (Derivation-Based Solution)

**Mass:** $m = 10 \text{ kg}$  
**Equation of Motion:** $x(t) = 0.2 \cos(10\pi t)$

---

## 1) Identification of Parameters via Standard Form

Comparing the given equation with the general SHM form:

$$x(t) = A \cos(\omega t + \phi)$$

* **Amplitude:** $A = 0.2 \text{ m}$
* **Angular Frequency:** $\omega = 10\pi \text{ rad/s}$
* **Phase:** $\phi = 0$

---

## 2) Calculation of the Spring Constant

Using the relationship for angular frequency:

$$\omega^2 = \frac{k}{m}$$

Solving for $k$:

$$k = m \omega^2$$
$$k = 10 \cdot (10\pi)^2 = 1000\pi^2$$
$$k \approx 9869.6 \text{ N/m}$$

---

## 3) Velocity Derivation

Velocity is the derivative of position with respect to time:

$$v(t) = \frac{dx}{dt}$$
$$v(t) = \frac{d}{dt}[0.2 \cos(10\pi t)]$$
$$v(t) = -0.2 \cdot 10\pi \sin(10\pi t)$$
$$v(t) = -2\pi \sin(10\pi t)$$

---

## 4) Total Mechanical Energy

Total energy is derived from the sum of kinetic and potential energy:

### Kinetic Energy
$$K = \frac{1}{2} m v^2$$

### Potential Energy
$$U = \frac{1}{2} k x^2$$

### Total Energy
$$E = K + U$$

Substituting the expressions for $v(t)$ and $x(t)$:

$$E = \frac{1}{2} m (-A\omega \sin(\omega t))^2 + \frac{1}{2} k (A \cos(\omega t))^2$$
$$E = \frac{1}{2} A^2 [ m\omega^2 \sin^2(\omega t) + k \cos^2(\omega t) ]$$

Using the substitution $k = m\omega^2$:

$$E = \frac{1}{2} k A^2 (\sin^2(\omega t) + \cos^2(\omega t))$$
$$E = \frac{1}{2} k A^2$$

---

## Final Calculation

$$E = \frac{1}{2}(1000\pi^2)(0.2)^2 = 20\pi^2$$
$$E \approx 197.39 \text{ J}$$

---

## 5) Interactive HTML

file:///C:/Users/batuh/OneDrive/Masa%C3%BCst%C3%BC/S2.html

---

## Conclusion
* Energy is derived from kinetic and potential energy.
* Total energy remains **constant** throughout the motion.
* This confirms the principle of **energy conservation** in SHM.
