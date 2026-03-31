# Problem 2: Harmonic Motion and Energy Analysis (Derivation-Based Solution)

**Mass:** $m = 10 \text{ kg}$  
**Equation of Motion:** $x(t) = 0.2 \cos(10\pi t)$

---

## 1) Identification of Parameters via Standard Form
Comparing the given equation $x(t) = 0.2 \cos(10\pi t)$ with the general SHM equation $x(t) = A \cos(\omega t + \phi)$:

* **Amplitude ($A$):** $0.2 \text{ m}$
* **Angular Frequency ($\omega$):** $10\pi \text{ rad/s}$
* **Phase ($\phi$):** $0$

---

## 2) Calculation of the Spring Constant ($k$)
The angular frequency is defined by the physical properties of the system (mass and stiffness). From the derivation of the SHM differential equation:
$$\omega^2 = \frac{k}{m} \implies k = m \cdot \omega^2$$

Substituting the values:
$$k = 10 \cdot (10\pi)^2 = 10 \cdot 100\pi^2 = 1000\pi^2$$
$$k \approx \mathbf{9869.6 \text{ N/m}}$$

---

## 3) Velocity Derivation (As requested by the Instructor)
To find the total energy at any point, we must first find the velocity $v(t)$. As emphasized in the lecture, velocity is the **time derivative of position**:

$$v(t) = \frac{dx}{dt} = \frac{d}{dt} [0.2 \cos(10\pi t)]$$
$$v(t) = 0.2 \cdot (-10\pi) \sin(10\pi t) = -2\pi \sin(10\pi t)$$

---

## 4) Total Mechanical Energy ($E_{total}$)
Total energy is the sum of Kinetic Energy ($K$) and Potential Energy ($U$).

### A) Potential Energy ($U$)
The potential energy of a spring is the **integral of the restorative force** ($F = -kx$):
$$U = \int kx \, dx = \frac{1}{2} k x^2$$

### B) Total Energy Verification
$$E_{total} = K + U = \frac{1}{2} m v(t)^2 + \frac{1}{2} k x(t)^2$$

Substituting $x(t) = A \cos(\omega t)$ and $v(t) = -A\omega \sin(\omega t)$:
$$E_{total} = \frac{1}{2} m (-A\omega \sin(\omega t))^2 + \frac{1}{2} k (A \cos(\omega t))^2$$
$$E_{total} = \frac{1}{2} A^2 [m\omega^2 \sin^2(\omega t) + k \cos^2(\omega t)]$$

Since $k = m\omega^2$, the equation simplifies using the identity $\sin^2\theta + \cos^2\theta = 1$:
$$E_{total} = \frac{1}{2} k A^2$$

**Calculation:**
$$E_{total} = \frac{1}{2} (1000\pi^2) \cdot (0.2)^2 = 500\pi^2 \cdot 0.04 = 20\pi^2$$
$$E_{total} \approx \mathbf{197.39 \text{ J}}$$

---

## 5) Physical Conclusion & Instructor's Notes
1.  **Derivation vs. Memorization:** This solution follows the instructor's requirement to derive velocity through differentiation rather than using a static formula.
2.  **Energy Conservation:** As shown in the provided lecture slides, while $K$ and $U$ oscillate (sine and cosine components), their sum $E_{total}$ remains constant at $20\pi^2 \text{ J}$.
3.  **System Stiffness:** The high spring constant ($\approx 10^4 \text{ N/m}$) is necessary to oscillate a $10\text{ kg}$ mass at a high frequency of $5 \text{ Hz}$ ($f = \frac{10\pi}{2\pi}$).


## 6) Interactive HTML

file:///C:/Users/batuh/OneDrive/Masa%C3%BCst%C3%BC/S2.html
