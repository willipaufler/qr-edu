# Pyramidenspitze und Volumen - Lösung

## 1. Berechnung der Grundfläche $G$ und der Höhe $h$

Die Seitenlänge $a$ der quadratischen Grundfläche lässt sich über den Vektor $\vec{AB}$ bestimmen:
$$
\begin{aligned}
\vec{AB} = \begin{pmatrix} 7 \\ 0 \\ -1 \end{pmatrix} - \begin{pmatrix} 3 \\ 0 \\ -1 \end{pmatrix} = \begin{pmatrix} 4 \\ 0 \\ 0 \end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
a = |\vec{AB}| = \sqrt{4^2 + 0^2 + 0^2} = 4
\end{aligned}
$$

Damit beträgt die Grundfläche:
$$
\begin{aligned}
G = a^2 = 4^2 = 16
\end{aligned}
$$

Mit dem gegebenen Volumen $V = 64$ berechnen wir die Höhe $h$:
$$
\begin{aligned}
V = \frac{1}{3} \cdot G \cdot h \\\\
64 = \frac{1}{3} \cdot 16 \cdot h \\\\
192 = 16 \cdot h \\\\
h = 12
\end{aligned}
$$

---

## 2. Bestimmung der Grundflächenebene

Alle drei gegebenen Punkte $A(3 \mid 0 \mid -1)$, $B(7 \mid 0 \mid -1)$ und $C(7 \mid 0 \mid 3)$ haben die $x_2$-Koordinate $0$.  
Die Grundfläche liegt somit in der Ebene mit der Koordinatengleichung:
$$
\begin{aligned}
E: x_2 = 0
\end{aligned}
$$

---

## 3. Bestimmung der möglichen Spitzen $S_1$ und $S_2$

Die Spitze $S$ liegt auf der Geraden $g: \vec{x} = r \cdot \begin{pmatrix} 1 \\ 3 \\ 1 \end{pmatrix}$.  
Daraus ergeben sich die allgemeinen Koordinaten der Spitze in Abhängigkeit von $r$:
$$
\begin{aligned}
S_r(r \mid 3r \mid r)
\end{aligned}
$$

Der Abstand der Spitze $S_r$ zur Ebene $E: x_2 = 0$ entspricht direkt dem Betrag ihrer $x_2$-Koordinate:
$$
\begin{aligned}
d(S_r, E) = |3r|
\end{aligned}
$$

Da dieser Abstand gleich der Höhe $h = 12$ sein muss, erhalten wir die Betragsgleichung:
$$
\begin{aligned}
|3r| = 12
\end{aligned}
$$

Dies liefert zwei Fälle für den Parameter $r$:

1. **Fall 1:**
$$
\begin{aligned}
3r = 12 \implies r_1 = 4
\end{aligned}
$$

2. **Fall 2:**
$$
\begin{aligned}
3r = -12 \implies r_2 = -4
\end{aligned}
$$

---

## 4. Ergebnis

Einsetzen von $r_1 = 4$ und $r_2 = -4$ in die Geradengleichung ergibt die Koordinaten der beiden möglichen Pyramidenspitzen:

$$
\begin{aligned}
S_1(4 \mid 12 \mid 4) \\\\
S_2(-4 \mid -12 \mid -4)
\end{aligned}
$$