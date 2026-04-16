# Funktionsscharen und Ortskurven - Lösung

### a) Bestimmen von $a$ für eine Extremstelle bei $x_0 = 1$
Ableitungen bilden:
$$\begin{aligned}
f_a'(x) &= 3ax^2 - 4x \\\\
f_a''(x) &= 6ax - 4
\end{aligned}
$$
Notwendige Bedingung $f_a'(1) = 0$:
$$\begin{aligned}
3a(1)^2 - 4(1) &= 0 \\\\
3a - 4 &= 0 \\\\
a &= \frac{4}{3}
\end{aligned}
$$
Art der Extremstelle prüfen mit $f_{4/3}''(1)$:
$$\begin{aligned}
f_{4/3}''(1) &= 6 \cdot \frac{4}{3} \cdot 1 - 4 \\\\
f_{4/3}''(1) &= 8 - 4 = 4
\end{aligned}
$$
Da $f_{4/3}''(1) = 4 > 0 \implies$ Tiefpunkt/Minimum (T).

### b) Extrempunkte in Abhängigkeit von $a$
Notwendige Bedingung $f_a'(x) = 0$:
$$\begin{aligned}
3ax^2 - 4x &= 0 \\\\
x \cdot (3ax - 4) &= 0
\end{aligned}
$$
$x_1 = 0$ und $x_2 = \frac{4}{3a}$.
Hinreichende Bedingung:

* $f_a''(0) = -4 < 0 \implies$ Hochpunkt/Maximum (H).
* $f_a''(\frac{4}{3a}) = 6a \cdot \frac{4}{3a} - 4 = 8 - 4 = 4 > 0 \implies$ Tiefpunkt/Minimum (T).

$y$-Koordinaten:

* $f_a(0) = 4 \implies H(0|4)$
* $f_a(\frac{4}{3a}) = a \cdot (\frac{4}{3a})^3 - 2 \cdot (\frac{4}{3a})^2 + 4 = a \cdot \frac{64}{27a^3} - 2 \cdot \frac{16}{9a^2} + 4 = \frac{64}{27a^2} - \frac{32}{9a^2} + 4 = \frac{64-96}{27a^2} + 4 = 4 - \frac{32}{27a^2}$

Ergebnis: $H(0|4)$ und $T(\frac{4}{3a} | 4 - \frac{32}{27a^2})$.

### c) Ermitteln der Ortskurve der Tiefpunkte
Die Koordinaten des Tiefpunkts sind $x = \frac{4}{3a}$ und $y = 4 - \frac{32}{27a^2}$.

1. $x$-Koordinate nach $a$ auflösen:
$$\begin{aligned}
x &= \frac{4}{3a} \\\\
a &= \frac{4}{3x}
\end{aligned}
$$
2. $a$ in $y$-Koordinate einsetzen:
$$\begin{aligned}
y &= 4 - \frac{32}{27 \cdot (\frac{4}{3x})^2} \\\\
y &= 4 - \frac{32}{27 \cdot \frac{16}{9x^2}} \\\\
y &= 4 - \frac{32 \cdot 9x^2}{27 \cdot 16} \\\\
y &= 4 - \frac{2 \cdot x^2}{3}
\end{aligned}
$$
Ergebnis: Die Ortskurve der Minima ist $y = -\frac{2}{3}x^2 + 4$ für $x>0$.