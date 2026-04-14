# Problem 9: Damped Harmonic Oscillator Analysis

The motion of a damped harmonic oscillator is governed by the second-order differential equation:
$$m \frac{d^2 x}{dt^2} + b \frac{dx}{dt} + k x = 0$$

## 1. General Solution
The solution depends on the roots of the characteristic equation $mr^2 + br + k = 0$. The auxiliary variable $\gamma = b/2m$ and the undamped angular frequency $\omega_0 = \sqrt{k/m}$ determine the behavior.

## 2. Classification of Cases
The system is classified based on the damping ratio:
1. **Underdamped ($b^2 < 4mk$):** The system oscillates with decaying amplitude.
   - Solution: $x(t) = Ae^{-\gamma t} \cos(\omega_d t + \phi)$
2. **Critically Damped ($b^2 = 4mk$):** The system returns to equilibrium as quickly as possible without oscillating.
   - Solution: $x(t) = (C_1 + C_2 t)e^{-\gamma t}$
3. **Overdamped ($b^2 > 4mk$):** The system returns to equilibrium slowly without oscillating.
   - Solution: $x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}$

## 3. Numerical Approach (RK4)
To solve this numerically, we convert the 2nd order ODE into a system of two 1st order ODEs:
1. $\frac{dx}{dt} = v$
2. $\frac{dv}{dt} = -\frac{b}{m}v - \frac{k}{m}x$
We then apply the 4th Order Runge-Kutta method to iterate through time.
