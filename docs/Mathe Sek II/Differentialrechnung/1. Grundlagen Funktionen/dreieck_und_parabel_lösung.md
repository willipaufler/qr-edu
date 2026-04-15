# Dreieck und Parabel - Lösung

### a) Bestimmen des Scheitelpunkts $S$
Aus der Scheitelpunktform $f(x) = -(x - a)^2 + (4 - a)$ lässt sich der Scheitelpunkt direkt ablesen:
$$
\begin{aligned}
S(a \mid 4 - a)
\end{aligned}
$$

### b) Bestimmen des Parameters $a$ für die Fläche $A = 2$
**1. Rechte Nullstelle $N$ berechnen:**
$$
\begin{aligned}
0 &= -(x - a)^2 + (4 - a) \\\\
(x - a)^2 &= 4 - a \\\\
x - a &= \pm \sqrt{4 - a} \\\\
x &= a \pm \sqrt{4 - a}
\end{aligned}
$$
Da die rechte Nullstelle gesucht ist: $N(a + \sqrt{4 - a} \mid 0)$.

**2. Flächeninhalt aufstellen:**
Die Grundseite $g$ auf der $x$-Achse ist $x_n$, die Höhe $h$ ist $y_s$:
$$
\begin{aligned}
A &= \frac{1}{2} \cdot (a + \sqrt{4 - a}) \cdot (4 - a) = 2
\end{aligned}
$$
Mit dem Taschenrechner erhält man die Lösungen $a=3$ und $a=-1,679$. Die negative Lösung entfällt, da sie nicht im Intervall $0 < a < 4$ liegt.  
Der gesuchte Parameter ist $a = 3$.

### c) Rechtwinkligkeit

#### Rechter Winkel bei $O$
Ein rechter Winkel wäre im Ursprung denkbar. Dieser entsteht jedoch nur, falls $a=0$, was laut Aufgabenstellung $(0<a<4)$ nicht möglich ist.

#### Rechter Winkel bei $S$
Die Steigung $m_1$ von $O(0|0)$ zu $S(a|4-a)$ ist:
$$
\begin{aligned}
m_1 = \frac{4 - a - 0}{a - 0} = \frac{4 - a}{a}
\end{aligned}
$$
Die Steigung $m_2$ von $S(a|4-a)$ zu $N(a + \sqrt{4 - a}|0)$ ist:
$$
\begin{aligned}
m_2 = \frac{0 - (4 - a)}{(a + \sqrt{4 - a}) - a} = \frac{-(4 - a)}{\sqrt{4 - a}} = -\sqrt{4 - a}
\end{aligned}
$$
Bedingung für rechten Winkel: $m_1 \cdot m_2 = -1$
$$
\begin{aligned}
\frac{4 - a}{a} \cdot (-\sqrt{4 - a}) &= -1 \\\\
\frac{(4 - a) \cdot \sqrt{4 - a}}{a} &= 1 \\\\
(4 - a)^{1,5} &= a
\end{aligned}
$$
Diese Gleichung lässt sich für $a \approx 2,272$ (numerisch) mit dem Taschenrechner lösen.