# Gebrochen-rationale Funktion I - Lösung

### a) Definitionsbereich
Der Nenner einer gebrochen-rationalen Funktion darf nicht Null werden.
$$\begin{aligned}
x^2 + 1 &= 0 \\\\
x^2 &= -1
\end{aligned}
$$
Diese Gleichung hat im Bereich der reellen Zahlen keine Lösung, da ein Quadrat niemals negativ sein kann ($x^2 \geq 0$).
Ergebnis: $D_f = \mathbb{R}$.

### b) Symmetrieuntersuchung
Wir prüfen $f(-x)$:
$$\begin{aligned}
f(-x) &= \frac{-x}{(-x)^2 + 1} \\\\
f(-x) &= \frac{-x}{x^2 + 1} \\\\
f(-x) &= -f(x)
\end{aligned}
$$
Ergebnis: Der Graph der Funktion ist **punktsymmetrisch zum Ursprung**.

### c) Extrempunkte bestimmen
Ableitung mit der Quotientenregel:
$u = x \implies u' = 1$
$v = x^2 + 1 \implies v' = 2x$
$$\begin{aligned}
f'(x) &= \frac{1 \cdot (x^2 + 1) - x \cdot (2x)}{(x^2 + 1)^2} \\\\
f'(x) &= \frac{x^2 + 1 - 2x^2}{(x^2 + 1)^2} \\\\
f'(x) &= \frac{1 - x^2}{(x^2 + 1)^2}
\end{aligned}
$$
**Notwendige Bedingung $f'(x) = 0$:**
$$\begin{aligned}
1 - x^2 &= 0 \\\\
x^2 &= 1 \\\\
x_1 &= 1; \quad x_2 = -1
\end{aligned}
$$

**Hinreichende Bedingung & Art:**

* $f''(1) = \frac{2 - 6}{(1+1)^3} = \frac{-4}{8} = -0,5 < 0 \implies$ **Hochpunkt (H)**
* $f''(-1) = \frac{-2 + 6}{(1+1)^3} = \frac{4}{8} = 0,5 > 0 \implies$ **Tiefpunkt (T)**

**Y-Werte (Einsetzen in $f(x)$):**

* $f(1) = \frac{1}{1^2 + 1} = \frac{1}{2}$
* $f(-1) = \frac{-1}{(-1)^2 + 1} = -\frac{1}{2}$

Aufgrund der Symmetrie und des Verlaufs (für sehr große $x$ nähert sich die Funktion der Null an) folgt:
Ergebnis: $H(1 | \frac{1}{2})$ und $T(-1 | -\frac{1}{2})$.