# Lösung – Basisaufgabe: Darstellungsformen von Ebenen

## Teil a) Umwandlung von $E_1: 2x_1 - 3x_2 + 4x_3 = 12$

### 1. Achsenabschnittsform:
Dividiere die Koordinatengleichung durch $12$:
$$
\begin{aligned}
\frac{2x_1}{12} - \frac{3x_2}{12} + \frac{4x_3}{12} = 1 \implies \frac{x_1}{6} + \frac{x_2}{-4} + \frac{x_3}{3} = 1
\end{aligned}
$$
Die Spurpunkte lauten somit $S_1(6 \mid 0 \mid 0)$, $S_2(0 \mid -4 \mid 0)$ und $S_3(0 \mid 0 \mid 3)$.

### 2. Parameterform:
Wähle $S_1$ als Stützpunkt und bilde die Richtungsvektoren $\vec{S_1S_2}$ und $\vec{S_1S_3}$:

$$
\begin{aligned}
\vec{u} = \begin{pmatrix} 0-6 \\ -4-0 \\ 0-0 \end{pmatrix} = \begin{pmatrix} -6 \\ -4 \\0 \end{pmatrix}, \quad 
\vec{v} = \begin{pmatrix} 0-6 \\ 0-0 \\ 3-0 \end{pmatrix} = \begin{pmatrix} -6 \\ 0 \\ 3 \end{pmatrix}
\end{aligned}
$$

(Hinweis: Richtungsvektoren können auch gekürzt werden, z. B. $\begin{pmatrix} 3 \\ 2 \\ 0 \end{pmatrix}$ und $\begin{pmatrix} 2 \\ 0 \\ -1 \end{pmatrix}$).

Mögliche Parameterform:
$$
\begin{aligned}
E_1: \vec{x} = \begin{pmatrix} 6 \\\\ 0 \\\\ 0 \end{pmatrix} + r \cdot \begin{pmatrix} 3 \\\\ 2 \\\\ 0 \end{pmatrix} + s \cdot \begin{pmatrix} 2 \\\\ 0 \\\\ -1 \end{pmatrix} \quad (r, s \in \mathbb{R})
\end{aligned}
$$

---

## Teil b) Umwandlung von $E_2$ in Koordinatenform

### 1. Normalenvektor über Kreuzprodukt:
$$
\begin{aligned}
\vec{n} = \begin{pmatrix} 2 \\ 1 \\ 1 \end{pmatrix} \times \begin{pmatrix} 0 \\ 3 \\ -1 \end{pmatrix} = \begin{pmatrix} 1 \cdot (-1) - 1 \cdot 3 \\ 1 \cdot 0 - 2 \cdot (-1) \\ 2 \cdot 3 - 1 \cdot 0 \end{pmatrix} = \begin{pmatrix} -4 \\ 2 \\ 6 \end{pmatrix}
\end{aligned}
$$

Vereinfachter Normalenvektor (durch $-2$ dividiert): $\vec{n} = \begin{pmatrix} 2 \\ -1 \\ -3 \end{pmatrix}$.

### 2. Koordinatenform aufstellen:
Ansatz: $2x_1 - x_2 - 3x_3 = d$.

Setze den Stützpunkt $(1 \mid 2 \mid 0)$ ein:
$$
\begin{aligned}
2(1) - 1(2) - 3(0) = d \implies 0 = d
\end{aligned}
$$

Koordinatengleichung für $E_2$:
$$
\begin{aligned}
E_2: 2x_1 - x_2 - 3x_3 = 0
\end{aligned}
$$
*(Hinweis: Da $d=0$ ist, verläuft die Ebene durch den Koordinatenursprung).*

---

## Teil c) Analyse und Parameterform von $E_3: 3x_1 + 2x_3 = 6$

### i) Begründung der Achsenparallelität:
Da die Koordinate $x_2$ in der Gleichung nicht vorkommt (ihr Koeffizient ist $0$), ist der Wert der $x_2$-Koordinate beliebig wählbar. Der Normalenvektor $\vec{n}_3 = \begin{pmatrix} 3 \\ 0 \\ 2 \end{pmatrix}$ steht senkrecht auf der $x_2$-Achse (Richtungsvektor $\begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix}$).

Daraus folgt: Die Ebene $E_3$ ist **parallel zur $x_2$-Achse**.

### ii) Parameterform aufstellen:
* Spurpunkt auf der $x_1$-Achse ($x_3=0$): $3x_1 = 6 \implies x_1 = 2 \implies S_1(2 \mid 0 \mid 0)$.
* Spurpunkt auf der $x_3$-Achse ($x_1=0$): $2x_3 = 6 \implies x_3 = 3 \implies S_3(0 \mid 0 \mid 3)$.
* Richtungsvektor 1: $\vec{S_1S_3} = \begin{pmatrix} -2 \\ 0 \\ 3 \end{pmatrix}$.
* Richtungsvektor 2: Vektor in Richtung der $x_2$-Achse $\begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix}$.

Mögliche Parameterform:
$$
\begin{aligned}
E_3: \vec{x} = \begin{pmatrix} 2 \\\\ 0 \\\\ 0 \end{pmatrix} + r \cdot \begin{pmatrix} -2 \\\\ 0 \\\\ 3 \end{pmatrix} + s \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 0 \end{pmatrix} \quad (r, s \in \mathbb{R})
\end{aligned}
$$