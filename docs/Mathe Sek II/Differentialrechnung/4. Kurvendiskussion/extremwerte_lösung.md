# Extremwerte - Lösung

### a) Bestimmen der Extrempunkte von $f(x) = x^2 - 5x + 7$
Zuerst bilden wir die Ableitungen:
$$\begin{aligned}
f'(x) &= 2x - 5 \\\\
f''(x) &= 2
\end{aligned}
$$
Notwendige Bedingung $f'(x) = 0$:
$$\begin{aligned}
2x - 5 &= 0 \\\\
2x &= 5 \\\\
x &= 2,5
\end{aligned}
$$
Hinreichende Bedingung prüfen:  
$f''(2,5) = 2 > 0 \implies$ Tiefpunkt/Minimum (T)  
$y$-Koordinate berechnen: $f(2,5) = 2,5^2 - 5 \cdot 2,5 + 7 = 0,75$.  
Ergebnis: $T(2,5|0,75)$

### b) Bestimmen der Extrempunkte von $f(x) = x \cdot (\sqrt{x} - 3)$
Funktion umformen: $f(x) = x^{1,5} - 3x$.
Ableitungen bilden:
$$\begin{aligned}
f'(x) &= 1,5x^{0,5} - 3 \\\\
f''(x) &= 0,75x^{-0,5}
\end{aligned}
$$
Notwendige Bedingung $f'(x) = 0$:
$$\begin{aligned}
1,5\sqrt{x} - 3 &= 0 \\\\
1,5\sqrt{x} &= 3 \\\\
\sqrt{x} &= 2 \\\\
x &= 4
\end{aligned}
$$
Hinreichende Bedingung prüfen:  
$f''(4) = 0,75 \cdot 4^{-0,5} = 0,375 > 0 \implies$ Tiefpunkt/Minimum (T)  
$y$-Koordinate berechnen: $f(4) = 4 \cdot (\sqrt{4} - 3) = 4 \cdot (-1) = -4$.  
Ergebnis: $T(4|-4)$

### c) Bestimmen der Extrempunkte von $f(x) = x^3 - 12x$
Ableitungen bilden:
$$\begin{aligned}
f'(x) &= 3x^2 - 12 \\\\
f''(x) &= 6x
\end{aligned}
$$
Notwendige Bedingung $f'(x) = 0$:
$$\begin{aligned}
3x^2 - 12 &= 0 \\\\
3x^2 &= 12 \\\\
x^2 &= 4 \\\\
x_1 &= 2, \quad x_2 = -2
\end{aligned}
$$
Hinreichende Bedingung prüfen:

* $f''(2) = 6 \cdot 2 = 12 > 0 \implies$ Tiefpunkt/Minimum (T)
* $f''(-2) = 6 \cdot (-2) = -12 < 0 \implies$ Hochpunkt/Maximum (H)

$y$-Koordinaten berechnen:

* $f(2) = 2^3 - 12 \cdot 2 = 8 - 24 = -16$
* $f(-2) = (-2)^3 - 12 \cdot (-2) = -8 + 24 = 16$

Ergebnis: $H(-2|16)$ und $T(2|-16)$