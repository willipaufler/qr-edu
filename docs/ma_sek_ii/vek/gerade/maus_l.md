# Nächtlicher Einsatz am Bauernhof - Lösung

### a) Geradengleichung des Laufwegs aufstellen

**1. Mittelpunkt $M_{DA}$ berechnen:**

$$
\begin{aligned}
\vec{OM_{DA}} &= \frac{1}{2} \left[ \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix} + \begin{pmatrix} 40 \\ 0 \\ 0 \end{pmatrix} \right] = \begin{pmatrix} 20 \\ 0 \\ 0 \end{pmatrix}
\end{aligned}
$$

Der Startpunkt lautet $M_{DA}(20 \mid 0 \mid 0)$.

**2. Geradengleichung aufstellen:**

Verbindungsvektor vom Startpunkt $M_{DA}(20 \mid 0 \mid 0)$ zum Zielpunkt $C(0 \mid 60 \mid 0)$:
$$
\begin{aligned}
\vec{M_{DA}C} &= \begin{pmatrix} 0 - 20 \\\\ 60 - 0 \\\\ 0 - 0 \end{pmatrix} = \begin{pmatrix} -20 \\\\ 60 \\\\ 0 \end{pmatrix}
\end{aligned}
$$

Als gekürzter Richtungsvektor bietet sich $\vec{v} = \begin{pmatrix} -1 \\ 3 \\ 0 \end{pmatrix}$ an.

Geradengleichung $g$:
$$
\begin{aligned}
g: \vec{x} &= \begin{pmatrix} 20 \\\\ 0 \\\\ 0 \end{pmatrix} + t \begin{pmatrix} -1 \\\\ 3 \\\\ 0 \end{pmatrix}
\end{aligned}
$$

*(Hinweis: Für $t = 0$ startet die Maus bei $M_{DA}$, für $t = 20$ erreicht sie den Eckpunkt $C$.)*

---

### b) Überprüfung, ob der Bewegungsmelder ausgelöst wird

**1. Lotfußpunkt (geringster Abstand zum Bewegungsmelder $M$) berechnen:**

Ein beliebiger Punkt auf dem Laufweg besitzt die Koordinaten $S_t(20 - t \mid 3t \mid 0)$.

Der Verbindungsvektor vom Geradenpunkt $S_t$ zum Bewegungsmelder $M(0 \mid 30 \mid 4)$ lautet:
$$
\begin{aligned}
\vec{S_t M} &= \begin{pmatrix} 0 - (20 - t) \\\\ 30 - 3t \\\\ 4 - 0 \end{pmatrix} = \begin{pmatrix} t - 20 \\\\ 30 - 3t \\\\ 4 \end{pmatrix}
\end{aligned}
$$

Orthogonalitätsbedingung mit dem Richtungsvektor $\vec{v} = \begin{pmatrix} -1 \\ 3 \\ 0 \end{pmatrix}$:
$$
\begin{aligned}
\vec{S_t M} \cdot \vec{v} &= 0 \\\\
\begin{pmatrix} t - 20 \\ 30 - 3t \\ 4 \end{pmatrix} \cdot \begin{pmatrix} -1 \\ 3 \\ 0 \end{pmatrix} &= 0 \\\\
-(t - 20) + 3(30 - 3t) + 0 \cdot 4 &= 0 \\\\
-t + 20 + 90 - 9t &= 0 \\\\
-10t + 110 &= 0 \\\\
10t &= 110 \\\\
t &= 11
\end{aligned}
$$

Da $t = 11$ im Intervall $[0; 20]$ liegt, befindet sich der dichteste Punkt tatsächlich auf der gelaufenen Strecke.

**2. Minimalen Abstand berechnen:**

Einsetzen von $t = 11$ in den Verbindungsvektor $\vec{S_t M}$:
$$
\begin{aligned}
\vec{S_{11} M} &= \begin{pmatrix} 11 - 20 \\\\ 30 - 33 \\\\ 4 \end{pmatrix} = \begin{pmatrix} -9 \\\\ -3 \\\\ 4 \end{pmatrix}
\end{aligned}
$$

Berechnen des Abstands $d$:
$$
\begin{aligned}
d &= |\vec{S_{11} M}| = \sqrt{(-9)^2 + (-3)^2 + 4^2} = \sqrt{81 + 9 + 16} = \sqrt{106} \approx 10{,}30\,\text{m}
\end{aligned}
$$

**3. Alternativ über das Kreuzprodukt:**

Mit Stützpunkt $A = M_{DA}(20 \mid 0 \mid 0)$, Richtungsvektor $\vec{v} = \begin{pmatrix} -1 \\ 3 \\ 0 \end{pmatrix}$ und $M(0 \mid 30 \mid 4)$:

$$
\begin{aligned}
\vec{AM} &= \begin{pmatrix} -20 \\ 30 \\ 4 \end{pmatrix} \\\\
\vec{AM} \times \vec{v} &= \begin{pmatrix} -20 \\ 30 \\ 4 \end{pmatrix} \times \begin{pmatrix} -1 \\ 3 \\ 0 \end{pmatrix} = \begin{pmatrix} -12 \\ -4 \\ -30 \end{pmatrix} \\\\
|\vec{AM} \times \vec{v}| &= \sqrt{(-12)^2 + (-4)^2 + (-30)^2} = \sqrt{144 + 16 + 900} = \sqrt{1060} \\\\
|\vec{v}| &= \sqrt{(-1)^2 + 3^2 + 0^2} = \sqrt{10} \\\\
d &= \frac{\sqrt{1060}}{\sqrt{10}} = \sqrt{106} \approx 10{,}30\,\text{m}
\end{aligned}
$$

**Ergebnis:**

Der geringste Abstand der Hofmaus zum Bewegungsmelder beträgt ca. $10{,}30\,\text{m}$. Da dieser Wert knapp über der Reichweite des Bewegungsmelders ($10\,\text{m}$) liegt, **wird der Bewegungsmelder nicht ausgelöst** und das Licht bleibt aus.