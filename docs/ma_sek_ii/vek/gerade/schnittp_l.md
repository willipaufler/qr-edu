# Schnittpunkt und Schnittwinkel - Lösung

### a) Bestimmen von Schnittpunkt und Schnittwinkel (2D)

**1. Schnittpunkt bestimmen:**

Gleichsetzen von $g$ und $h$:
$$
\begin{aligned}
\begin{pmatrix} 6 \\\\ 2 \end{pmatrix} + r \begin{pmatrix} 3 \\\\ 1 \end{pmatrix} &= \begin{pmatrix} -10 \\\\ 0 \end{pmatrix} + s \begin{pmatrix} -2 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Daraus ergibt sich das lineare Gleichungssystem:
$$
\begin{aligned}
(1) \quad 6 + 3r &= -10 - 2s \\\\
(2) \quad 2 + r &= s
\end{aligned}
$$

Einsetzen von $(2)$ in $(1)$:
$$
\begin{aligned}
6 + 3r &= -10 - 2(2 + r) \\\\
6 + 3r &= -10 - 4 - 2r \\\\
5r &= -20 \\\\
r &= -4
\end{aligned}
$$

Einsetzen von $r = -4$ in Gleichung $(2)$:
$$
\begin{aligned}
s &= 2 + (-4) = -2
\end{aligned}
$$

Einsetzen von $r = -4$ in $g$:
$$
\begin{aligned}
\vec{OS} &= \begin{pmatrix} 6 \\\\ 2 \end{pmatrix} + (-4) \begin{pmatrix} 3 \\\\ 1 \end{pmatrix} = \begin{pmatrix} -6 \\\\ -2 \end{pmatrix}
\end{aligned}
$$

Der Schnittpunkt lautet $S(-6 \mid -2)$.

**2. Schnittwinkel berechnen:**

Mit den Richtungsvektoren $\vec{u} = \begin{pmatrix} 3 \\ 1 \end{pmatrix}$ und $\vec{v} = \begin{pmatrix} -2 \\ 1 \end{pmatrix}$:
$$
\begin{aligned}
\vec{u} \cdot \vec{v} &= 3 \cdot (-2) + 1 \cdot 1 = -5 \\\\
|\vec{u}| &= \sqrt{3^2 + 1^2} = \sqrt{10} \\\\
|\vec{v}| &= \sqrt{(-2)^2 + 1^2} = \sqrt{5}
\end{aligned}
$$

Anwendung der Winkelformel:
$$
\begin{aligned}
\cos(\alpha) &= \frac{|-5|}{\sqrt{10} \cdot \sqrt{5}} = \frac{5}{\sqrt{50}} = \frac{5}{5\sqrt{2}} = \frac{1}{\sqrt{2}} \\\\
\alpha &= 45^\circ
\end{aligned}
$$

---

### b) Bestimmen von Schnittpunkt und Schnittwinkel (3D)

**1. Schnittpunkt bestimmen:**

Gleichsetzen von $g$ und $h$:
$$
\begin{aligned}
\begin{pmatrix} 0 \\\\ 2 \\\\ 0 \end{pmatrix} + r \begin{pmatrix} -5 \\\\ -1 \\\\ -2 \end{pmatrix} &= \begin{pmatrix} 1 \\\\ -2 \\\\ -1 \end{pmatrix} + s \begin{pmatrix} 8 \\\\ 4 \\\\ 4 \end{pmatrix}
\end{aligned}
$$

Zeilenweises Gleichungssystem:
$$
\begin{aligned}
(1) \quad -5r &= 1 + 8s \\\\
(2) \quad 2 - r &= -2 + 4s \\\\
(3) \quad -2r &= -1 + 4s
\end{aligned}
$$

Subtraktion von $(3)$ von $(2)$:
$$
\begin{aligned}
(2 - r) - (-2r) &= (-2 + 4s) - (-1 + 4s) \\\\
2 + r &= -1 \\\\
r &= -3
\end{aligned}
$$

Einsetzen von $r = -3$ in $(2)$:
$$
\begin{aligned}
2 - (-3) &= -2 + 4s \\\\
5 &= -2 + 4s \\\\
7 &= 4s \\\\
s &= \frac{7}{4}
\end{aligned}
$$

Probekontrolle in $(1)$:
$$
\begin{aligned}
-5 \cdot (-3) &= 1 + 8 \cdot \frac{7}{4} \\\\
15 &= 1 + 14 = 15 \quad \text{(wahre Aussage)}
\end{aligned}
$$

Einsetzen von $r = -3$ in $g$:
$$
\begin{aligned}
\vec{OS} &= \begin{pmatrix} 0 \\\\ 2 \\\\ 0 \end{pmatrix} + (-3) \begin{pmatrix} -5 \\\\ -1 \\\\ -2 \end{pmatrix} = \begin{pmatrix} 15 \\\\ 5 \\\\ 6 \end{pmatrix}
\end{aligned}
$$

Der Schnittpunkt lautet $S(15 \mid 5 \mid 6)$.

**2. Schnittwinkel berechnen:**

Mit den Richtungsvektoren $\vec{u} = \begin{pmatrix} -5 \\ -1 \\ -2 \end{pmatrix}$ und $\vec{v} = \begin{pmatrix} 8 \\ 4 \\ 4 \end{pmatrix}$:
$$
\begin{aligned}
\vec{u} \cdot \vec{v} &= (-5) \cdot 8 + (-1) \cdot 4 + (-2) \cdot 4 = -52 \\\\
|\vec{u}| &= \sqrt{(-5)^2 + (-1)^2 + (-2)^2} = \sqrt{30} \\\\
|\vec{v}| &= \sqrt{8^2 + 4^2 + 4^2} = \sqrt{96}
\end{aligned}
$$

Anwendung der Winkelformel:
$$
\begin{aligned}
\cos(\alpha) &= \frac{|-52|}{\sqrt{30} \cdot \sqrt{96}}  = \frac{13}{6\sqrt{5}} \\\\
\alpha &\approx 14,31^\circ
\end{aligned}
$$

---

### c) Bestimmen der Parameter $a, b$ und des Schnittpunkts

**1. Bestimmung von $b$ über Orthogonalität:**

Damit sich die Geraden rechtwinklig schneiden, muss das Skalarprodukt der Richtungsvektoren null sein:
$$
\begin{aligned}
\begin{pmatrix} b \\ -1 \\ -2 \end{pmatrix} \cdot \begin{pmatrix} 8 \\ 4 \\ 4 \end{pmatrix} &= 0 \\\\
8b - 4 - 8 &= 0 \\\\
8b &= 12 \\\\
b &= \frac{3}{2}
\end{aligned}
$$

**2. Bestimmung von $a$ und des Schnittpunkts:**

Gleichsetzen von $g$ und $h$ mit $b = \frac{3}{2}$:
$$
\begin{aligned}
\begin{pmatrix} a \\\\ 2 \\\\ 0 \end{pmatrix} + r \begin{pmatrix} \frac{3}{2} \\\\ -1 \\\\ -2 \end{pmatrix} &= \begin{pmatrix} 1 \\\\ -2 \\\\ -1 \end{pmatrix} + s \begin{pmatrix} 8 \\\\ 4 \\\\ 4 \end{pmatrix}
\end{aligned}
$$

Das Gleichungssystem lautet:
$$
\begin{aligned}
(1) \quad a + \frac{3}{2}r &= 1 + 8s \\\\
(2) \quad 2 - r &= -2 + 4s \\\\
(3) \quad -2r &= -1 + 4s
\end{aligned}
$$

Aus den Gleichungen $(2)$ und $(3)$ (wie in Teilaufgabe b) ergeben sich:
$$
\begin{aligned}
r &= -3 \\\\
s &= \frac{7}{4}
\end{aligned}
$$

Einsetzen von $r = -3$ und $s = \frac{7}{4}$ in Gleichung $(1)$:
$$
\begin{aligned}
a + \frac{3}{2} \cdot (-3) &= 1 + 8 \cdot \frac{7}{4} \\\\
a - \frac{9}{2} &= 1 + 14 \\\\
a &= \frac{39}{2}
\end{aligned}
$$

Einsetzen von $s = \frac{7}{4}$ in $h$ liefert den Schnittpunkt:
$$
\begin{aligned}
\vec{OS} &= \begin{pmatrix} 1 \\\\ -2 \\\\ -1 \end{pmatrix} + \frac{7}{4} \begin{pmatrix} 8 \\\\ 4 \\\\ 4 \end{pmatrix} = \begin{pmatrix} 15 \\\\ 5 \\\\ 6 \end{pmatrix}
\end{aligned}
$$

Der Schnittpunkt lautet $S(15 \mid 5 \mid 6)$ für die Parameter $a = \frac{39}{2}$ und $b = \frac{3}{2}$.