# Es regnet - Lösung

### Zu Teilaufgabe a)
Das gesamte Wasservolumen nach 4 Stunden berechnet sich über das Integral:
$$
\begin{aligned}
V &= \int_{0}^{4} (-15t^2 + 60t) \, dt = [-5t^3 + 30t^2]_0^4\\\\
V &= (-5 \cdot 64 + 30 \cdot 16) - 0 = -320 + 480 = \mathbf{160 \, \text{Liter}}
\end{aligned}
$$

### Zu Teilaufgabe b)
1. **Volumen in cm³:** $V(t) = 1000 \cdot \int_{0}^{t} z(x) \, dx = 1000 \cdot (-5t^3 + 30t^2)$.
2. **Grundfläche $G$:** mit $r = 40 \, \text{cm}$ ist $A_G = \pi \cdot r^2 = 1600\pi \approx 5026,55 \, \text{cm}^2$.
3. **Höhenfunktion:** $H(t) = \frac{V(t)}{A_G}$

$$H(t) = \frac{1000 \cdot (-5t^3 + 30t^2)}{1600\pi} = \frac{5 \cdot (-5t^3 + 30t^2)}{8\pi} \approx \mathbf{0,199 \cdot (-5t^3 + 30t^2)}$$

