# Problem 2: Harmonic Motion and Energy Analysis (Derivation-Based Solution)
**Mass:** $m = 10 \text{ kg}$  
**Equation of Motion:** $x(t) = 0.2 \cos(10\pi t)$
---
## 1) Identification of Parameters via Standard Form  
Comparing the given equation $x(t) = 0.2 \cos(10\pi t)$ with the general SHM equation $x(t) = A \cos(\omega t + \phi)$:
- **Amplitude ($A$):** $0.2 \text{ m}$  
- **Angular Frequency ($\omega$):** $10\pi \text{ rad/s}$  
- **Phase ($\phi$):** $0$
---
## 2) Calculation of the Spring Constant ($k$)  
The angular frequency is defined by the physical properties of the system (mass and stiffness). From the SHM relationship:
$$
\omega^2 = \frac{k}{m} \implies k = m \cdot \omega^2
$$
Substituting the values:
$$
k = 10 \cdot (10\pi)^2 = 10 \cdot 100\pi^2 = 1000\pi^2
$$
$$
k \approx \mathbf{9869.6 \text{ N/m}}
$$
---
## 3) Velocity Derivation (As requested by the Instructor)  
To derive the total mechanical energy, we must first determine the velocity from the position function.  
Velocity is the **time derivative of position**:

$$
v(t) = \frac{dx}{dt} = \frac{d}{dt} [0.2 \cos(10\pi t)]
$$

$$
v(t) = 0.2 \cdot (-10\pi) \sin(10\pi t) = -2\pi \sin(10\pi t)
$$
---
## 4) Total Mechanical Energy ($E_{total}$)  
Total mechanical energy is obtained by **explicitly summing kinetic and potential energy**, not by directly using a memorized formula.
### A) Kinetic Energy ($K$)
$$
K = \frac{1}{2} m v(t)^2
$$
### B) Potential Energy ($U$)
The potential energy of a spring is derived from the restoring force ($F = -kx$):
$$
U = \int kx \, dx = \frac{1}{2} k x^2
$$
### C) Total Energy (Derivation)
$$
E_{total} = K + U = \frac{1}{2} m v(t)^2 + \frac{1}{2} k x(t)^2
$$
Substituting $x(t) = A \cos(\omega t)$ and $v(t) = -A\omega \sin(\omega t)$:
$$
E_{total} = \frac{1}{2} m (-A\omega \sin(\omega t))^2 + \frac{1}{2} k (A \cos(\omega t))^2
$$
$$
E_{total} = \frac{1}{2} A^2 \left[ m\omega^2 \sin^2(\omega t) + k \cos^2(\omega t) \right]
$$
Using $k = m\omega^2$ and the identity $\sin^2\theta + \cos^2\theta = 1$:
$$
E_{total} = \frac{1}{2} k A^2
$$
This shows that the total mechanical energy is **derived from kinetic and potential energy** and is **constant in time**.
---
**Calculation:**
$$
E_{total} = \frac{1}{2} (1000\pi^2) \cdot (0.2)^2 = 500\pi^2 \cdot 0.04 = 20\pi^2
$$
$$
E_{total} \approx \mathbf{197.39 \text{ J}}
$$
---
## 5) Physical Conclusion & Instructor's Notes
1. **Derivation-Based Approach:** The total energy is obtained by starting from $K$ and $U$, as required, rather than directly assuming the final formula.  
2. **Energy Conservation:** Although $K$ and $U$ vary with time (sine and cosine terms), their sum $E_{total}$ remains constant.  
3. **System Stiffness:** A large spring constant ($\approx 10^4 \text{ N/m}$) is consistent with oscillating a $10\text{ kg}$ mass at a relatively high frequency.
---
## 6) Interactive HTML
file:///C:/Users/batuh/OneDrive/Masa%C3%BCst%C3%BC/S2.html
