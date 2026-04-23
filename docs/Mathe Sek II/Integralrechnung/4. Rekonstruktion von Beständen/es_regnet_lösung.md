# Es regnet - Lösung

### Zu Teilaufgabe a)
Berechnung des gesamten Zuflusses über 4 Stunden:
$$
\begin{aligned}
V_{zu} &= \int_{0}^{4} (-15t^2 + 60t) \, dt \\\\
V_{zu} &= \left[ -5t^3 + 30t^2 \right]_0^4 \\\\
V_{zu} &= (-5 \cdot 64 + 30 \cdot 16) - 0 = \mathbf{160\,\text{Liter}}
\end{aligned}
$$

### Zu Teilaufgabe b)
Grundfläche $A_G = \pi \cdot (40\,\text{cm})^2 = 1600\pi\,\text{cm}^2$.  
Umrechnung in Liter: $1000\, \text{cm}^3$=$1\,\text{Liter}$.

Funktionsgleichung für die Höhe $H(t)$ in cm:
$$
\begin{aligned}
H(t) &= \frac{V(t)}{A_G}\\\\
H(t) &= \frac{(200 - 5t^3 + 30t^2) \cdot 1000}{1600\pi}
\end{aligned}
$$

Füllhöhe nach $t = 2,5\,\text{h}$:
Zuerst Volumen berechnen: $V(2,5) = 200 + (-5 \cdot 2,5^3 + 30 \cdot 2,5^2) = 309,375\,\text{l}$.
$$
\begin{aligned}
H(2,5) &= \frac{309375}{1600\pi} \approx \mathbf{61,55\,\text{cm}}
\end{aligned}
$$

### Zu Teilaufgabe c)
Abflussrate: $4,5\,\text{l/min} \cdot 60\,\text{min/h} = \mathbf{270\,\text{l/h}}$.
Gesucht ist der Zeitpunkt $T$, an dem das zusätzliche Volumen (seit $t=0$) wieder auf Null gesunken ist:
$$
\begin{aligned}
\int_{0}^{2,5} z(t) \, dt + \int_{2,5}^{T} (z(t) - 270) \, dt &= 0
\end{aligned}
$$

Mittels CAS ergibt sich:  **$T = 3\,\text{h}$**.

**Ergebnis:** Nach etwa **3 Stunden** hat die Tonne wieder ihren Anfangsbestand von 200 Litern erreicht.