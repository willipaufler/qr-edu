# Tangente mit Parameter - Lösung

### a) Bestimmung des Parameters $a$
Die Funktion ist $f_a(x) = a \cdot x^{-2}$. Die Ableitung lautet:
$f_a'(x) = -2a \cdot x^{-3} = -\frac{2a}{x^3}$.

Damit die Tangente mit den Achsen ein gleichschenkliges Dreieck bildet, muss ihre Steigung $m = -1$ sein (da sie den I. Quadranten von links oben nach rechts unten schneidet).
$$
\begin{aligned}
f_a'(1) &= -1 \\\\
-\frac{2a}{1^3} &= -1 \\\\
-2a &= -1 \\\\
a &= 0,5
\end{aligned}
$$

---

### b) Angabe der Tangentengleichung
Mit $a = 0,5$ lautet die Funktion $f_{0,5}(x) = \frac{0,5}{x^2}$.
Der Berührpunkt bei $x_0 = 1$ ist:
$y_0 = f_{0,5}(1) = \frac{0,5}{1^2} = 0,5 \Rightarrow P(1|0,5)$.

Die Steigung ist $m = -1$. Einsetzen in die Punkt-Steigungs-Form:
$$
\begin{aligned}
t(x) &= -1 \cdot (x - 1) + 0,5 \\\\
t(x) &= -x + 1 + 0,5 \\\\
t(x) &= -x + 1,5
\end{aligned}
$$

---

### c) Berechnung des Flächeninhalts
Das Dreieck wird begrenzt durch die Achsenabschnitte der Tangente $t(x) = -x + 1,5$.

* $y$-Achsenabschnitt ($x=0$): $t(0) = 1,5$.
* $x$-Achsenabschnitt ($y=0$): $0 = -x + 1,5 \Rightarrow x = 1,5$.

Da es ein gleichschenklig-rechtwinkliges Dreieck mit den Katheten $a = 1,5$ und $b = 1,5$ ist, gilt:
$$
\begin{aligned}
A &= \frac{1}{2} \cdot 1,5 \cdot 1,5 \\\\
A &= \frac{1}{2} \cdot 2,25 \\\\
A &= 1,125
\end{aligned}
$$

**Ergebnis:** Der Flächeninhalt des Dreiecks beträgt $1,125$ Flächeneinheiten.