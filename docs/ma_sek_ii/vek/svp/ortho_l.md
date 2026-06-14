# Paarweise orthogonale Vektoren - Lösung

### a) Bestimmen von $a$ und $b$

Drei Vektoren sind paarweise orthogonal oder senkrecht zueinander, wenn alle drei möglichen Skalarprodukte gleich $0$ sind. Wir stellen die entsprechenden Gleichungen auf:

$$
\begin{aligned}
\text{(I)} \quad \vec{u} \cdot \vec{v} &= 0 \\
\text{(II)} \quad \vec{v} \cdot \vec{w} &= 0 \\
\text{(III)} \quad \vec{u} \cdot \vec{w} &= 0
\end{aligned}
$$

Wir berechnen die Skalarprodukte im Einzelnen:

Aus Gleichung (I):
$$
\begin{aligned}
\begin{pmatrix} a \\\\ 4 \\\\ 4 \end{pmatrix} \cdot \begin{pmatrix} 0 \\\\ b \\\\ -2 \end{pmatrix} &= 0 \\\\
a \cdot 0 + 4 \cdot b + 4 \cdot (-2) &= 0 \\\\
b &= 2
\end{aligned}
$$

Wir setzen $b = 2$ in Gleichung (II) ein:
$$
\begin{aligned}
\begin{pmatrix} 0 \\\\ 2 \\\\ -2 \end{pmatrix} \cdot \begin{pmatrix} 2 \\\\ 2a \\\\ 0 \end{pmatrix} &= 0 \\\\
0 \cdot 2 + 2 \cdot 2a + (-2) \cdot 0 &= 0 \\\\
a &= 0
\end{aligned}
$$

Zuletzt überprüfen wir das Ergebnis mit Gleichung (III) für $a = 0$ und $b = 2$:
$$
\begin{aligned}
\begin{pmatrix} 0 \\\\ 4 \\\\ 4 \end{pmatrix} \cdot \begin{pmatrix} 2 \\\\ 0 \\\\ 0 \end{pmatrix} &= 0 \\\\
0 \cdot 2 + 4 \cdot 0 + 4 \cdot 0 &= 0 \\\\
0 &= 0
\end{aligned}
$$

Die Überprüfung ist erfolgreich. Die gesuchten Parameter sind $a = 0$ und $b = 2$.

### b) Bestimmen von $a$ und $b$

Wir stellen wieder die drei Bedingungen für die Skalarprodukte auf:

$$
\begin{aligned}
\text{(I)} \quad \vec{u} \cdot \vec{w} &= 0 \\
\text{(II)} \quad \vec{u} \cdot \vec{v} &= 0 \\
\text{(III)} \quad \vec{v} \cdot \vec{w} &= 0
\end{aligned}
$$

Wir beginnen mit Gleichung (I), da diese nur den Parameter $a$ enthält:
$$
\begin{aligned}
\begin{pmatrix} a \\\\ 3a \\\\ 1 \end{pmatrix} \cdot \begin{pmatrix} a \\\\ 1 \\\\ 0 \end{pmatrix} &= 0 \\\\
a \cdot a + 3a \cdot 1 + 1 \cdot 0 &= 0 \\\\
a^2 + 3a &= 0 \\\\
a(a + 3) &= 0
\end{aligned}
$$

Hieraus ergeben sich zwei Fälle (Satz vom Nullprodukt):
$a_1 = 0$ oder $a_2 = -3$. Wir müssen beide Fälle separat untersuchen.

**Fall 1: $a = 0$**

Wir setzen $a = 0$ in die Vektoren ein und nutzen Gleichung (II):
$$
\begin{aligned}
\begin{pmatrix} 0 \\\\ 0 \\\\ 1 \end{pmatrix} \cdot \begin{pmatrix} -1 \\\\ 0 \\\\ b \end{pmatrix} &= 0 \\\\
0 \cdot (-1) + 0 \cdot 0 + 1 \cdot b &= 0 \\\\
b &= 0
\end{aligned}
$$

Wir prüfen Fall 1 mit Gleichung (III) für $a = 0$ und $b = 0$:
$$
\begin{aligned}
\begin{pmatrix} -1 \\\\ 0 \\\\ 0 \end{pmatrix} \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 0 \end{pmatrix} &= 0 \\\\
(-1) \cdot 0 + 0 \cdot 1 + 0 \cdot 0 &= 0 \\\\
0 &= 0
\end{aligned}
$$

Die erste Lösungskombination lautet somit: $a = 0$ und $b = 0$.

**Fall 2: $a = -3$**

Wir setzen $a = -3$ in die Vektoren ein und nutzen Gleichung (II):
$$
\begin{aligned}
\begin{pmatrix} -3 \\\\ -9 \\\\ 1 \end{pmatrix} \cdot \begin{pmatrix} -1 \\\\ -3 \\\\ b \end{pmatrix} &= 0 \\\\
(-3) \cdot (-1) + (-9) \cdot (-3) + 1 \cdot b &= 0 \\\\
3 + 27 + b &= 0 \\\\
b &= -30
\end{aligned}
$$

Wir prüfen Fall 2 mit Gleichung (III) für $a = -3$ und $b = -30$:
$$
\begin{aligned}
\begin{pmatrix} -1 \\\\ -3 \\\\ -30 \end{pmatrix} \cdot \begin{pmatrix} -3 \\\\ 1 \\\\ 0 \end{pmatrix} &= 0 \\\\
(-1) \cdot (-3) + (-3) \cdot 1 + (-30) \cdot 0 &= 0 \\\\
0 &= 0
\end{aligned}
$$

Die zweite Lösungskombination lautet somit: $a = -3$ und $b = -30$.