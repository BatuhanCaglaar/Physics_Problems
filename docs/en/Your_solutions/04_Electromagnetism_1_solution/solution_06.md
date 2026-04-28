# Problem 6: Electric Field Vector Analysis

**Given:**
- $+q$ at $(-a, 0)$
- $+2q$ at $(a, 0)$

---

## 1. General Field $\vec{E}(x,y)$
$$\vec{E}(x,y) = k \left[ \frac{q}{(x+a)^2 + y^2} \hat{r}_1 + \frac{2q}{(x-a)^2 + y^2} \hat{r}_2 \right]$$

## 2. Zero Field Condition ($\vec{E}=0$)
This can only happen on the x-axis between the charges because $y$-components would otherwise not cancel.
Between $(-a, 0)$ and $(a, 0)$:
$$\frac{kq}{(x+a)^2} = \frac{k(2q)}{(a-x)^2} \implies \frac{1}{(x+a)^2} = \frac{2}{(a-x)^2}$$
$$a - x = \sqrt{2}(x + a) \implies a - \sqrt{2}a = x + \sqrt{2}x$$
$$x = a \frac{1 - \sqrt{2}}{1 + \sqrt{2}} \approx -0.17a$$

## 3. Specific Calculation ($a=0.2, y=0.3, q=2\mu C$) at $(0,y)$
Distance $r = \sqrt{0.2^2 + 0.3^2} = \sqrt{0.13} \approx 0.36 \, \text{m}$
$E_y$ components from both charges add up:
$$E_y = \frac{kq}{r^2} \sin\theta + \frac{k(2q)}{r^2} \sin\theta = \frac{3kq}{r^2} \frac{y}{r}$$
$$E_y = \frac{3(8.99 \times 10^9)(2 \times 10^{-6})(0.3)}{(0.13)^{1.5}} \approx 3.47 \times 10^5 \, \text{N/C}$$
$E_x$ components:
$$E_x = \frac{k(2q)}{r^2} \cos\theta - \frac{kq}{r^2} \cos\theta = \frac{kq}{r^2} \frac{a}{r} \approx 7.7 \times 10^4 \, \text{N/C}$$

## 4. Limit $y \gg a$
The system acts like a single point charge of $+3q$:
$$\vec{E} \approx \frac{k(3q)}{y^2} \hat{j}$$


file:///C:/Users/batuh/OneDrive/Masa%C3%BCst%C3%BC/4-Q6.html
