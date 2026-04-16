# Wurzel-Tangente - Lösung

### Bestimmen der Tangentengleichung
Gegeben ist $f(x) = \sqrt{x} + 1$ und die Stelle $x_0 = 9$.
Zuerst bilden wir die Ableitung: $f'(x) = \frac{1}{2\sqrt{x}}$.

Für die Tangente $t(x) = m \cdot x + c$ gelten an der Stelle $x_0 = 9$ folgende Bedingungen:

**I: Gemeinsamer Punkt** ($f(x_0) = t(x_0)$)
$$
\begin{aligned}
f(9) &= \sqrt{9} + 1 = 4 \\\\
4 &= m \cdot 9 + c
\end{aligned}
$$

**II: Gemeinsamer Anstieg** ($f'(x_0) = m$)
$$
\begin{aligned}
f'(9) &= \frac{1}{2\sqrt{9}} = \frac{1}{6} \\\\
m &= \frac{1}{6}
\end{aligned}
$$

### Lösen des Gleichungssystems
Wir setzen $m = \frac{1}{6}$ aus Bedingung **II** in die Gleichung aus Bedingung **I** ein:
$$
\begin{aligned}
4 &= \frac{1}{6} \cdot 9 + c \\\\
4 &= 1,5 + c \\\\
c &= 2,5
\end{aligned}
$$

**Ergebnis:**
Durch Einsetzen von $m$ und $c$ in die allgemeine Geradengleichung erhalten wir:
$t(x) = \frac{1}{6}x + 2,5$