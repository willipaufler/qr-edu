# Polynomdivision - Lösung

### a) Bestimmen einer Nullstelle durch Probieren
Wir testen einfache Teiler der Zahl $12$:
$$
\begin{aligned}
f(1) &= 1^3 - 13 \cdot 1 + 12 \\\\
f(1) &= 1 - 13 + 12 \\\\
f(1) &= 0
\end{aligned}
$$
Damit ist $x_1 = 1$ eine Nullstelle. Der zugehörige Linearfaktor ist $(x - 1)$.

### b) Berechnung der weiteren Nullstellen
**Schritt 1: Polynomdivision**
$$
\begin{aligned}
(x^3 \quad \quad - 13x + 12) &: (x - 1) = x^2 + x - 12 \\\\
-(x^3 - x^2) \quad \quad \quad & \\\\
\overline{\quad \quad \quad x^2 - 13x} \quad & \\\\
-(x^2 - x) \quad & \\\\
\overline{\quad \quad -12x + 12} & \\\\
-(-12x + 12) & \\\\
\overline{\quad \quad \quad \quad \quad \quad 0} &
\end{aligned}
$$

**Schritt 2: Nullstellen des Ergebnisterms berechnen**
$$
\begin{aligned}
x^2 + x - 12 &= 0 \\\\
x_{2,3} &= -\frac{1}{2} \pm \sqrt{\left(\frac{1}{2}\right)^2 - (-12)} \\\\
x_{2,3} &= -0,5 \pm \sqrt{0,25 + 12} \\\\
x_{2,3} &= -0,5 \pm \sqrt{12,25} \\\\
x_{2,3} &= -0,5 \pm 3,5
\end{aligned}
$$
Somit ergeben sich $x_2 = 3$ und $x_3 = -4$.

**Ergebnis:**
Die Nullstellen der Funktion liegen bei $x_1 = 1$, $x_2 = 3$ und $x_3 = -4$.