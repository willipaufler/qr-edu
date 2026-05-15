# Beschleunigender Radfahrer - Lösung

### Zu Teilaufgabe a)
Die Geschwindigkeitsfunktion $v(t)$ ist die Stammfunktion von $a(t) = 0,6t - 2$:

$$v(t) = \int (0,6t - 2) \, dt = 0,3t^2 - 2t + C$$

Mit der Anfangsgeschwindigkeit $v(0) = 5$ folgt:

$$0,3 \cdot 0^2 - 2 \cdot 0 + C = 5 \implies C = 5$$

Die Funktionsgleichung lautet: **$v(t) = 0,3t^2 - 2t + 5$**.

### Zu Teilaufgabe b)
Die minimale Geschwindigkeit wird erreicht, wenn die Beschleunigung Null ist $v'(t) = a(t) = 0$:

$$0,6t - 2 = 0 \implies 0,6t = 2 \implies t = \frac{2}{0,6} = \mathbf{\frac{10}{3} \approx 3,33 \, \text{s}}$$

Dass es sich um ein Minimum handelt, lässt sich durch $a'(\frac{10}{3})=0,6>0$ nachweisen.

### Zu Teilaufgabe c)
Der zurückgelegte Weg $s$ im Intervall $[0; 10]$ ist das bestimmte Integral von $v(t)$:
$$
\begin{aligned}
s &= \int_{0}^{10} (0,3t^2 - 2t + 5) \, dt = [0,1t^3 - t^2 + 5t]_0^{10}\\\\
s &= (0,1 \cdot 1000 - 100 + 50) - 0 = 100 - 100 + 50 = \mathbf{50 \, \text{m}}
\end{aligned}$$