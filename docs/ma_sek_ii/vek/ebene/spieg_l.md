# Spiegelung an Ebene - Lösung

## Teil a)

Gegeben sind $P(6 \mid 2 \mid 1)$ und $E: x - y - 4z = 18$.

Der Normalenvektor der Ebene lautet $\vec{n} = \begin{pmatrix} 1 \\ -1 \\ -4 \end{pmatrix}$.

### 1. Lotgerade $g$ aufstellen
$$
\begin{aligned}
g: \vec{x} = \begin{pmatrix} 6 \\ 2 \\ 1 \end{pmatrix} + t \cdot \begin{pmatrix} 1 \\ -1 \\ -4 \end{pmatrix}
\end{aligned}
$$

### 2. Lotfußpunkt $L$ berechnen
Setze die Koordinaten von $g$ in $E$ ein:
$$
\begin{aligned}
(6 + t) - (2 - t) - 4(1 - 4t) = 18 \\\\
6 + t - 2 + t - 4 + 16t = 18 \\\\
18t = 18 \\\\
t = 1
\end{aligned}
$$

Einsetzen von $t = 1$ in $g$ liefert den Lotfußpunkt $L$:
$$
\begin{aligned}
\vec{OL} = \begin{pmatrix} 6 \\ 2 \\ 1 \end{pmatrix} + 1 \cdot \begin{pmatrix} 1 \\ -1 \\ -4 \end{pmatrix} = \begin{pmatrix} 7 \\ 1 \\ -3 \end{pmatrix} \implies L(7 \mid 1 \mid -3)
\end{aligned}
$$

### 3. Bildpunkt $P'$ berechnen
$$
\begin{aligned}
\vec{OP'} = \vec{OP} + 2 \cdot \vec{PL} = \begin{pmatrix} 6 \\ 2 \\ 1 \end{pmatrix} + 2 \cdot \begin{pmatrix} 1 \\ -1 \\ -4 \end{pmatrix} = \begin{pmatrix} 8 \\ 0 \\ -7 \end{pmatrix}
\end{aligned}
$$

**Ergebnis a):** Der Bildpunkt lautet $P'(8 \mid 0 \mid -7)$.

---

## Teil b)

Gegeben sind $P(-8 \mid 13 \mid -1)$ und $E: \left(\vec{x} - \begin{pmatrix} -2 \\ 5 \\ 3 \end{pmatrix}\right) \cdot \begin{pmatrix} 3 \\ -4 \\ 2 \end{pmatrix} = 0$.

Der Normalenvektor lautet $\vec{n} = \begin{pmatrix} 3 \\ -4 \\ 2 \end{pmatrix}$.

### 1. Lotgerade $g$ aufstellen
$$
\begin{aligned}
g: \vec{x} = \begin{pmatrix} -8 \\ 13 \\ -1 \end{pmatrix} + t \cdot \begin{pmatrix} 3 \\ -4 \\ 2 \end{pmatrix}
\end{aligned}
$$

### 2. Lotfußpunkt $L$ berechnen
Setze $g$ für $\vec{x}$ in $E$ ein:
$$
\begin{aligned}
\left( \begin{pmatrix} -8 + 3t \\ 13 - 4t \\ -1 + 2t \end{pmatrix} - \begin{pmatrix} -2 \\ 5 \\ 3 \end{pmatrix} \right) \cdot \begin{pmatrix} 3 \\ -4 \\ 2 \end{pmatrix} = 0 \\\\
\begin{pmatrix} -6 + 3t \\ 8 - 4t \\ -4 + 2t \end{pmatrix} \cdot \begin{pmatrix} 3 \\ -4 \\ 2 \end{pmatrix} = 0 \\\\
3(-6 + 3t) - 4(8 - 4t) + 2(-4 + 2t) = 0 \\\\
-18 + 9t - 32 + 16t - 8 + 4t = 0 \\\\
29t - 58 = 0 \\\\
t = 2
\end{aligned}
$$

Einsetzen von $t = 2$ in $g$ liefert den Lotfußpunkt $L$:
$$
\begin{aligned}
\vec{OL} = \begin{pmatrix} -8 \\ 13 \\ -1 \end{pmatrix} + 2 \cdot \begin{pmatrix} 3 \\ -4 \\ 2 \end{pmatrix} = \begin{pmatrix} -2 \\ 5 \\ 3 \end{pmatrix} \implies L(-2 \mid 5 \mid 3)
\end{aligned}
$$

### 3. Bildpunkt $P'$ berechnen
$$
\begin{aligned}
\vec{OP'} = \vec{OP} + 2 \cdot \vec{PL} = \begin{pmatrix} -8 \\ 13 \\ -1 \end{pmatrix} + 2 \cdot \begin{pmatrix} 6 \\ -8 \\ 4 \end{pmatrix} = \begin{pmatrix} 4 \\ -3 \\ 7 \end{pmatrix}
\end{aligned}
$$

**Ergebnis b):** Der Bildpunkt lautet $P'(4 \mid -3 \mid 7)$.

