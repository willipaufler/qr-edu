# Lagebeziehung zwischen Gerade und Gerade - Lösung

### a) Untersuchung von $g$ und $h$

**1. Kollinearität der Richtungsvektoren:**

$$
\begin{aligned}
\begin{pmatrix} -4 \\ 2 \\ -8 \end{pmatrix} &= k \cdot \begin{pmatrix} 2 \\ -1 \\ 4 \end{pmatrix} \implies k = -2
\end{aligned}
$$

Die Richtungsvektoren sind kollinear (Vielfache voneinander). Die Geraden sind somit echt parallel oder identisch.

**2. Punktprobe:**

Setze den Stützvektor von $g$ in $h$ ein:
$$
\begin{aligned}
\begin{pmatrix} 1 \\\\ 2 \\\\ 3 \end{pmatrix} &= \begin{pmatrix} 3 \\\\ 0 \\\\ 1 \end{pmatrix} + s \begin{pmatrix} -4 \\\\ 2 \\\\ -8 \end{pmatrix}
\end{aligned}
$$

Daraus folgt zeilenweise:
$$
\begin{aligned}
(1) \quad 1 &= 3 - 4s \implies s = \frac{1}{2} \\\\
(2) \quad 2 &= 0 + 2s \implies s = 1 \\\\
(3) \quad 3 &= 1 - 8s \implies s = -\frac{1}{4}
\end{aligned}
$$

Da die Werte für $s$ unterschiedlich sind, liegt der Stützpunkt von $g$ nicht auf $h$.

**Ergebnis:** Die Geraden $g$ und $h$ sind **echt parallel** ($g \parallel h$).

---

### b) Untersuchung von $g$ und $h$

**1. Kollinearität der Richtungsvektoren:**

$$
\begin{aligned}
\begin{pmatrix} 0 \\ 1 \\ 2 \end{pmatrix} &= k \cdot \begin{pmatrix} 1 \\ 2 \\ 0 \end{pmatrix}
\end{aligned}
$$

Aus der ersten Zeile folgt $0 = k \cdot 1 \implies k = 0$. In der zweiten Zeile ergibt sich jedoch $1 = 0 \cdot 2 = 0$ (Widerspruch). Die Richtungsvektoren sind nicht kollinear.

**2. Gleichsetzen der Geradengleichungen:**

$$
\begin{aligned}
\begin{pmatrix} 1 \\ 0 \\ 2 \end{pmatrix} + r \begin{pmatrix} 1 \\ 2 \\ 0 \end{pmatrix} &= \begin{pmatrix} 0 \\ 3 \\ 1 \end{pmatrix} + s \begin{pmatrix} 0 \\ 1 \\ 2 \end{pmatrix}
\end{aligned}
$$

Zeilenweises Gleichungssystem:
$$
\begin{aligned}
(1) \quad 1 + r &= 0 \implies r = -1 \\\\
(2) \quad 2r &= 3 + s \\\\
(3) \quad 2 &= 1 + 2s \implies 2s = 1 \implies s = \frac{1}{2}
\end{aligned}
$$

Einsetzen von $r = -1$ und $s = \frac{1}{2}$ in Gleichung $(2)$:
$$
\begin{aligned}
2 \cdot (-1) &= 3 + \frac{1}{2} \\\\
-2 &= \frac{7}{2} \quad \text{(Falsche Aussage)}
\end{aligned}
$$

Das Gleichungssystem hat keine Lösung.

**Ergebnis:** Die Geraden $g$ und $h$ sind **windschief**.

---

### c) Untersuchung von $g$ und $h$

**1. Schnittpunkt bestimmen:**

Beide Geraden besitzen denselben Stützvektor $\begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix}$. Für $r = 0$ und $s = 0$ ergibt sich jeweils dieser Vektor.

**Ergebnis:** Die Geraden schneiden sich im Punkt $S(2 \mid 1 \mid 0)$.

**2. Orthogonalität prüfen:**

Skalarprodukt der Richtungsvektoren $\vec{u} = \begin{pmatrix} 1 \\ 2 \\ -2 \end{pmatrix}$ und $\vec{v} = \begin{pmatrix} 2 \\ 1 \\ 2 \end{pmatrix}$:
$$
\begin{aligned}
\vec{u} \cdot \vec{v} &= 1 \cdot 2 + 2 \cdot 1 + (-2) \cdot 2 \\\\
\vec{u} \cdot \vec{v} &= 2 + 2 - 4 = 0
\end{aligned}
$$

Da das Skalarprodukt den Wert $0$ hat, stehen die Richtungsvektoren senkrecht zueinander.

**Ergebnis:** Die Geraden $g$ und $h$ **schneiden sich orthogonal** ($g \perp h$) im Schnittpunkt $S(2 \mid 1 \mid 0)$.