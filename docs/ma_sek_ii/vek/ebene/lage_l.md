# Lösung – Besondere Lagen einer Ebenenschar im Raum (oHiMi)

## Teil a) Parallelität zur $z$-Achse

Der Normalenvektor der Ebenenschar lautet:
$$
\begin{aligned}
\vec{n}_a = \begin{pmatrix} 2 \\\\ a - 3 \\\\ a \end{pmatrix}
\end{aligned}
$$

Damit $E_a$ parallel zur $z$-Achse verläuft, muss der $z$-Eintrag des Normalenvektors verschwinden ($a = 0$):
$$
\begin{aligned}
a = 0
\end{aligned}
$$

Für $a = 0$ lautet die Ebene $E_0: 2x - 3y = 6$. Sie verläuft parallel zur $z$-Achse.

---

## Teil b) Parallelität zur $xy$-Ebene

Die $xy$-Ebene wird durch die Gleichung $z = 0$ beschrieben und besitzt den Normalenvektor $\vec{n}_{xy} = \begin{pmatrix} 0 \\ 0 \\ 1 \end{pmatrix}$.

Damit $E_a$ parallel zur $xy$-Ebene ist, müsste $\vec{n}_a$ Vielfaches von $\vec{n}_{xy}$ sein:
$$
\begin{aligned}
\begin{pmatrix} 2 \\\\ a - 3 \\\\ a \end{pmatrix} = k \cdot \begin{pmatrix} 0 \\\\ 0 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Aus der 1. Zeile folgt die Bedingung $2 = 0 \cdot k = 0$, was ein Widerspruch ist.

**Ergebnis:** Es gibt kein $a \in \mathbb{R}$, sodass $E_a$ parallel zur $xy$-Ebene verläuft.

---

## Teil c) Spurpunkt $S_y(0 \mid 2 \mid 0)$

Einsetzen der Koordinaten $x = 0$, $y = 2$, $z = 0$ in die Ebenengleichung $E_a$:
$$
\begin{aligned}
2(0) + (a - 3) \cdot 2 + a(0) = 6 \\\\
2(a - 3) = 6 \\\\
2a - 6 = 6 \\\\
2a = 12 \implies a = 6
\end{aligned}
$$

Für $a = 6$ besitzt die Ebene $E_6: 2x + 3y + 6z = 6$ den Spurpunkt $S_y(0 \mid 2 \mid 0)$.