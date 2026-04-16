# Berührungsproblem - Lösung

### a) Nachweis des Berührens im Punkt Q
Damit sich die Graphen berühren, müssen Funktionswert und Steigung an der Stelle $x = 0$ übereinstimmen.

**1. Prüfung der Funktionswerte:**
$$
\begin{aligned}
f(0) &= \frac{1}{4}(0)^4 - \frac{1}{3}(0)^3 + \frac{1}{2}(0) + \frac{3}{4} = \frac{3}{4} \\\\
g(0) &= \frac{1}{5}(0)^5 - \frac{1}{4}(0)^4 + \frac{1}{2}(0) + \frac{3}{4} = \frac{3}{4}
\end{aligned}
$$
Beide Graphen gehen durch den Punkt $Q(0 | \frac{3}{4})$.

**2. Prüfung der Steigungen:**
Zuerst bilden wir die Ableitungen:

$f'(x) = x^3 - x^2 + \frac{1}{2}$ und $g'(x) = x^4 - x^3 + \frac{1}{2}$

Einsetzen von $x = 0$:
$$
\begin{aligned}
f'(0) &= 0^3 - 0^2 + \frac{1}{2} = 0,5 \\\\
g'(0) &= 0^4 - 0^3 + \frac{1}{2} = 0,5
\end{aligned}
$$
Da $f'(0) = g'(0)$ gilt, haben beide Graphen an dieser Stelle die gleiche Steigung.

**Ergebnis:** Da sowohl die Funktionswerte als auch die Steigungen übereinstimmen, berühren sich die Graphen im Punkt $Q$.

---

### b) Gleichung der gemeinsamen Tangente
Die Tangente hat die Steigung $m = 0,5$ und verläuft durch den Punkt $Q(0 | \frac{3}{4})$.
Da $Q$ auf der $y$-Achse liegt, entspricht der $y$-Wert direkt dem Achsenabschnitt $c = \frac{3}{4} = 0,75$.
$$
\begin{aligned}
t(x) &= m \cdot x + c \\\\
t(x) &= 0,5x + 0,75
\end{aligned}
$$

**Ergebnis:** Die gemeinsame Tangente lautet $t(x) = 0,5x + 0,75$.