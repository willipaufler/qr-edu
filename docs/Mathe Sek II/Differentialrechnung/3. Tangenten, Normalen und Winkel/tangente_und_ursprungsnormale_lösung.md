# Tangente und Normale - Lösung

### a) Bestimmen der Tangentenstelle
Zuerst bilden wir die Ableitung von $f(x) = \frac{1}{3}x^3 - 3x$:
$f'(x) = x^2 - 3$.

Die Tangente $t(x) = 6x + 18$ hat die Steigung $m = 6$. Wir suchen Stellen mit dieser Steigung:
$$
\begin{aligned}
f'(x) &= 6 \\\\
x^2 - 3 &= 6 \\\\
x^2 &= 9 \\\\
x_1 = 3&, x_2 = -3
\end{aligned}
$$

Nun prüfen wir die Funktionswerte an diesen Stellen:

$f(3) = \frac{1}{3}(3)^3 - 3(3) = 9 - 9 = 0$  
$f(-3) = \frac{1}{3}(-3)^3 - 3(-3) = -9 + 9 = 0$

Vergleich mit den Werten der Tangente $t(x)$:

$t(3) = 6(3) + 18 = 36 \neq f(3)$  
$t(-3) = 6(-3) + 18 = -18 + 18 = 0 = f(-3)$

**Ergebnis:** Die Gerade $t$ ist eine Tangente an $f$ an der Stelle $x = -3$.

---

### b) Ermitteln der Ursprungsgeraden als Normalen
Wir setzen für die Ursprungsgerade $n(x) = m \cdot x$ an. Eine solche Gerade ist eine Normale an der Stelle $x$, wenn gilt:
$$
\begin{aligned}
\text{I: }\quad & m \cdot x = f(x) \\\\
\text{II: }\quad & \frac{-1}{m} = f'(x)
\end{aligned}
$$

Einsetzen der Funktionsterme:
$$
\begin{aligned}
\text{I: }\quad & m \cdot x = \frac{1}{3}x^3 - 3x \\\\
\text{II: }\quad & \frac{-1}{m} = x^2 - 3
\end{aligned}
$$


Die Lösung dieses Systems (z. B. mittels CAS) liefert die möglichen Steigungen $m$ für die gesuchten Ursprungsgeraden:
$$
\begin{aligned}
n_1(x) &= \frac{1}{3}x \\\\
n_{2,3}(x) &= (\pm \frac{\sqrt{6}}{3} - 1) \cdot x
\end{aligned}
$$

**Ergebnis:** Es gibt drei Ursprungsgeraden, welche Normalen der Funktion $f$ sind.