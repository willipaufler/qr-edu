# Schnittpunkt zum Quadrat - Lösung

## Teil a) Ebenengleichung aufstellen

Wir wählen $A(0 \mid 0 \mid 2)$ als Stützpunkt und bilden zwei Spannvektoren:
$$
\begin{aligned}
\vec{AD} = \begin{pmatrix} -1 \\\\ 2 \\\\ 0 \end{pmatrix} - \begin{pmatrix} 0 \\\\ 0 \\\\ 2 \end{pmatrix} = \begin{pmatrix} -1 \\\\ 2 \\\\ -2 \end{pmatrix} \\\\
\vec{AC} = \begin{pmatrix} 1 \\\\ 4 \\\\ 1 \end{pmatrix} - \begin{pmatrix} 0 \\\\ 0 \\\\ 2 \end{pmatrix} = \begin{pmatrix} 1 \\\\ 4 \\\\ -1 \end{pmatrix}
\end{aligned}
$$

Der Normalenvektor $\vec{n}$ ergibt sich aus dem Kreuzprodukt:
$$
\begin{aligned}
\vec{n} = \vec{AD} \times \vec{AC} = \begin{pmatrix} -1 \\\\ 2 \\\\ -2 \end{pmatrix} \times \begin{pmatrix} 1 \\\\ 4 \\\\ -1 \end{pmatrix} = \begin{pmatrix} 2 - (-8) \\\\ -2 - 1 \\\\ -4 - 2 \end{pmatrix} = \begin{pmatrix} 6 \\\\ -3 \\\\ -6 \end{pmatrix}
\end{aligned}
$$

Zur Vereinfachung dividieren wir durch $3$:
$$
\begin{aligned}
\vec{n} = \begin{pmatrix} 2 \\\\ -1 \\\\ -2 \end{pmatrix}
\end{aligned}
$$

Ansatz für die Koordinatengleichung $E: 2x_1 - x_2 - 2x_3 = d$.  
Einsetzen von $A(0 \mid 0 \mid 2)$:
$$
\begin{aligned}
2(0) - 0 - 2(2) = -4 \implies d = -4
\end{aligned}
$$

**Ergebnis a):** $E: 2x_1 - x_2 - 2x_3 = -4$

---

## Teil b) Schnittpunkt $B$ und Nachweis des Quadrats

### 1. Schnittpunkt $B$ berechnen
Die Gerade $g$ lautet:
$$
\begin{aligned}
g: \vec{x} = \begin{pmatrix} 2 \\\\ 0 \\\\ 1 \end{pmatrix} + s \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 1 \end{pmatrix} \implies \begin{cases} x_1 = 2 \\\\ x_2 = s \\\\ x_3 = 1 + s \end{cases}
\end{aligned}
$$

Einsetzen der Koordinaten von $g$ in $E$:
$$
\begin{aligned}
2(2) - (s) - 2(1 + s) = -4 \\\\
4 - s - 2 - 2s = -4 \\\\
2 - 3s = -4 \\\\
-3s = -6 \\\\
s = 2
\end{aligned}
$$

Einsetzen von $s = 2$ in $g$ ergibt den Ortsvektor von $B$:
$$
\begin{aligned}
\vec{OB} = \begin{pmatrix} 2 \\\\ 0 \\\\ 1 \end{pmatrix} + 2 \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \\\\ 3 \end{pmatrix} \implies B(2 \mid 2 \mid 3)
\end{aligned}
$$

---

### 2. Nachweis, dass $ABCD$ ein Quadrat ist

Wir stellen die relevanten Seitenvektoren auf:
$$
\begin{aligned}
\vec{AB} = \begin{pmatrix} 2 \\\\ 2 \\\\ 3 \end{pmatrix} - \begin{pmatrix} 0 \\\\ 0 \\\\ 2 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix} \\\\
\vec{DC} = \begin{pmatrix} 1 \\\\ 4 \\\\ 1 \end{pmatrix} - \begin{pmatrix} -1 \\\\ 2 \\\\ 0 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix} \\\\
\vec{AD} = \begin{pmatrix} -1 \\\\ 2 \\\\ 0 \end{pmatrix} - \begin{pmatrix} 0 \\\\ 0 \\\\ 2 \end{pmatrix} = \begin{pmatrix} -1 \\\\ 2 \\\\ -2 \end{pmatrix}
\end{aligned}
$$

* **Eigenschaft 1: Parallelogramm**  
  Da $\vec{AB} = \vec{DC} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix}$, ist das Viereck $ABCD$ ein Parallelogramm.

* **Eigenschaft 2: Rechter Winkel**  
  Wir prüfen das Skalarprodukt der benachbarten Seiten $\vec{AB}$ und $\vec{AD}$:
$$
\begin{aligned}
\vec{AB} \cdot \vec{AD} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix} \cdot \begin{pmatrix} -1 \\\\ 2 \\\\ -2 \end{pmatrix} = 2(-1) + 2(2) + 1(-2) = -2 + 4 - 2 = 0
\end{aligned}
$$
  Da das Skalarprodukt $0$ ist, stehen die Seiten orthogonal aufeinander ($\vec{AB} \perp \vec{AD}$). Das Parallelogramm ist somit ein Rechteck.

* **Eigenschaft 3: Gleiche Seitenlängen**  
  Wir berechnen die Längen der benachbarten Seiten:
$$
\begin{aligned}
|\vec{AB}| = \sqrt{2^2 + 2^2 + 1^2} = \sqrt{4 + 4 + 1} = \sqrt{9} = 3 \\\\
|\vec{AD}| = \sqrt{(-1)^2 + 2^2 + (-2)^2} = \sqrt{1 + 4 + 4} = \sqrt{9} = 3
\end{aligned}
$$
  Da $|\vec{AB}| = |\vec{AD}| = 3$, sind alle vier Seiten gleich lang.

**Fazit:** Das Viereck $ABCD$ ist ein Quadrat.