# Normalengleichung - Lösung

### a) Berechnen der Normalengleichung an der Stelle $x_0 = -1$
Zuerst bestimmen wir den Punkt $P(-1 | f(-1))$ und die Steigung $f'(-1)$:

$f(x) = -\frac{5}{4}x^3 + \frac{7}{4}x + 1$  
$f'(x) = -\frac{15}{4}x^2 + \frac{7}{4}$

Einsetzen von $x_0 = -1$:

$f(-1) = -\frac{5}{4}(-1)^3 + \frac{7}{4}(-1) + 1 = 0,5$  
$f'(-1) = -\frac{15}{4}(-1)^2 + \frac{7}{4} = -2$

Die Steigung der Normalen $m_n$ ist:
$$
\begin{aligned}
m_n &= -\frac{1}{f'(-1)} \\\\
m_n &= -\frac{1}{-2} = 0,5
\end{aligned}
$$

Aufstellen der Geradengleichung:
$$
\begin{aligned}
n(x) &= m \cdot (x - x_0) + y_0 \\\\
n(x) &= 0,5 \cdot (x - (-1)) + 0,5 \\\\
n(x) &= 0,5x + 0,5 + 0,5 \\\\
n(x) &= 0,5x + 1
\end{aligned}
$$

---

### b) Ermitteln der weiteren Stelle
Die Normale $n(x) = 0,5x + 1$ hat die Steigung $m_n = 0,5$. Damit sie an einer Stelle $x$ eine Normale ist, muss dort die Tangentensteigung $f'(x) = -2$ betragen:
$$
\begin{aligned}
f'(x) &= -2 \\\\
-\frac{15}{4}x^2 + \frac{7}{4} &= -2 \\\\
-\frac{15}{4}x^2 &= -3,75 \\\\
x^2 &= 1 \\\\
x_1 = -1& \text{ oder } x_2 = 1
\end{aligned}
$$

Die Stelle $x_1 = -1$ ist bereits aus a) bekannt. Wir prüfen die Stelle $x_2 = 1$:  
Punkt auf dem Graphen: $f(1) = -\frac{5}{4}(1)^3 + \frac{7}{4}(1) + 1 = 1,5$.  
Punkt auf der Normalen: $n(1) = 0,5(1) + 1 = 1,5$.

**Ergebnis:** Da $f(1) = n(1)$ und die Steigungsbedingung erfüllt ist, ist die Gerade auch an der Stelle $x_2 = 1$ eine Normale.