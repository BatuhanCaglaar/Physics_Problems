# Problem 2: Harmonic Motion and Energy Analysis

A mass of $m = 10 \text{ kg}$ is attached to a spring and follows the displacement equation:
$$x(t) = 0.2 \cos(10\pi t)$$
where $x$ is in meters and $t$ is in seconds.

---

## 1) Theory: Standard Form of Simple Harmonic Motion (SHM)

The general equation for a Simple Harmonic Oscillator is defined as:
$$x(t) = A \cos(\omega t + \phi)$$

By comparing the given equation $x(t) = 0.2 \cos(10\pi t)$ to the standard form, we identify the following parameters:
- **Amplitude ($A$):** $0.2 \text{ m}$
- **Angular Frequency ($\omega$):** $10\pi \text{ rad/s}$
- **Phase Constant ($\phi$):** $0$

---

## 2) Calculation of the Spring Constant ($k$)

In a mass-spring system, the relationship between angular frequency, mass, and the spring constant is:
$$\omega = \sqrt{\frac{k}{m}} \implies \omega^2 = \frac{k}{m}$$

To find the spring constant $k$, we rearrange the formula:
$$k = m \cdot \omega^2$$

Substituting the known values ($m = 10 \text{ kg}$ and $\omega = 10\pi$):
$$k = 10 \cdot (10\pi)^2$$
$$k = 10 \cdot 100\pi^2 = 1000\pi^2$$

Using the approximation $\pi^2 \approx 9.8696$:
$$k \approx \mathbf{9869.6 \text{ N/m}}$$

---

## 3) Calculation of Total Mechanical Energy ($E_{total}$)

In a harmonic oscillator, total mechanical energy is the sum of kinetic ($K$) and potential ($U$) energy. At maximum displacement ($x = A$), all energy is stored as potential energy:
$$E_{total} = \frac{1}{2} k A^2$$

Substituting the calculated values for $k$ and $A$:
$$E_{total} = \frac{1}{2} (1000\pi^2) \cdot (0.2)^2$$
$$E_{total} = 500\pi^2 \cdot 0.04$$
$$E_{total} = 20\pi^2$$

Using the approximation $\pi^2 \approx 9.8696$:
$$E_{total} \approx \mathbf{197.39 \text{ J}}$$

---

## 4) Physical Interpretation and Soundness

1. **Spring Stiffness:** A value of nearly $10,000 \text{ N/m}$ indicates a very stiff spring. This is physically consistent with the system's ability to maintain a high angular frequency ($10\pi \approx 31.4 \text{ rad/s}$) while oscillating a relatively large mass of $10 \text{ kg}$.
2. **Energy Consistency:** Although the displacement is small ($20 \text{ cm}$), the energy level is significant (nearly $200 \text{ Joules}$) due to the high frequency, as energy is proportional to the square of the angular frequency ($\omega^2$).
3. **Conservation:** Since there is no damping term ($b=0$) in the motion equation, the total mechanical energy remains constant throughout the oscillation.

--

## 5) Interactive HTML

file:///C:/Users/batuh/OneDrive/Masa%C3%BCst%C3%BC/S2.html
