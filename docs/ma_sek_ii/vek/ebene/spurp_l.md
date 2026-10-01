# Lösung – Spurpunkte und Pyramidenvolumen (oHiMi)

## Teil a) Bestimmung der Spurpunkte

Ebenengleichung: $E_a: ax + 2y + 3z = 12$ (mit $a > 0$)

1. **Spurpunkt $S_x$ ($y = 0, z = 0$):**
$$
\begin{aligned}
a \cdot x + 2(0) + 3(0) = 12 \implies ax = 12 \implies x = \frac{12}{a} \implies S_x\left(\frac{12}{a} \;\middle|\; 0 \;\middle|\; 0\right)
\end{aligned}
$$

2. **Spurpunkt $S_y$ ($x = 0, z = 0$):**
$$
\begin{aligned}
a(0) + 2y + 3(0) = 12 \implies 2y = 12 \implies y = 6 \implies S_y(0 \mid 6 \mid 0)
\end{aligned}
$$

3. **Spurpunkt $S_z$ ($x = 0, y = 0$):**
$$
\begin{aligned}
a(0) + 2(0) + 3z = 12 \implies 3z = 12 \implies z = 4 \implies S_z(0 \mid 0 \mid 4)
\end{aligned}
$$

---

## Teil b) Volumengleichung $V(a)$

Da das Koordinatensystem dreidimensional kartesisch ist, bilden die Strecken von $O$ zu den Spurpunkten die drei zueinander orthogonalen Kanten der Pyramide.

Das Volumen eines Achsentetraeders berechnet sich über:
$$
\begin{aligned}
V(a) = \frac{1}{6} \cdot x_{S_x} \cdot y_{S_y} \cdot z_{S_z}
\end{aligned}
$$

Einsetzen der Werte:
$$
\begin{aligned}
V(a) = \frac{1}{6} \cdot \frac{12}{a} \cdot 6 \cdot 4 = \frac{1}{6} \cdot \frac{288}{a} = \frac{48}{a} \quad (\text{in VE})
\end{aligned}
$$

---

## Teil c) Bestimmung von $a$ für $V(a) = 24\text{ VE}$

Ansatz:
$$
\begin{aligned}
V(a) = 24 \\\\
\frac{48}{a} = 24 \\\\
48 = 24a \implies a = 2
\end{aligned}
$$

Für $a = 2$ besitzt das Achsentetraeder der Ebene $E_2: 2x + 2y + 3z = 12$ ein Volumen von genau $24\text{ VE}$.