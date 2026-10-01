# Lösung – Ebenenschar (oHiMi)

## Teil a) Orthogonalität von $g$ und $E_a$

Der Normalenvektor der Ebenenschar lautet $\vec{n}_a = \begin{pmatrix} 2a \\ 1 \\ -a \end{pmatrix}$. 

Die Gerade $g$ steht genau dann senkrecht auf $E_a$, wenn $\vec{n}_a$ und der Richtungsvektor $\vec{v}_g = \begin{pmatrix} 2 \\ 2 \\ -1 \end{pmatrix}$ kollinear sind:
$$
\begin{aligned}
\begin{pmatrix} 2a \\\\ 1 \\\\ -a \end{pmatrix} = k \cdot \begin{pmatrix} 2 \\\\ 2 \\\\ -1 \end{pmatrix}
\end{aligned}
$$

Gleichungssystem zeilenweise:
$$
\begin{aligned}
(1) \quad 2a = 2k \\\\
(2) \quad 1 = 2k \implies k = 0,5 \\\\
(3) \quad -a = -k
\end{aligned}
$$

Einsetzen von $k = 0,5$ in $(1)$ oder $(3)$:
$$
\begin{aligned}
2a = 2(0,5) \implies a = 0,5
\end{aligned}
$$

Für $a = 0,5$ verläuft die Gerade $g$ senkrecht zur Ebene $E_{0,5}$.

---

## Teil b) Gerade $g$ liegt in der Ebene $E_a$

### 1. Bestimmung von $a$ über den Stützpunkt
Damit die Gerade in $E_a$ liegt, muss ihr Stützpunkt $P(2 \mid 1 \mid 2)$ in $E_a$ liegen:
$$
\begin{aligned}
2a(2) + 1 - a(2) = 2 \\\\
4a + 1 - 2a = 2 \\\\
2a + 1 = 2 \\\\
2a = 1 \implies a = 0,5
\end{aligned}
$$

Somit lautet die relevante Ebene $E_{0,5}: x + y - 0,5z = 2$ mit dem Normalenvektor $\vec{n}_{0,5} = \begin{pmatrix} 1 \\ 1 \\ -0,5 \end{pmatrix}$.

### 2. Bestimmung von $b$ über das Skalarprodukt
Zusätzlich muss der Richtungsvektor $\vec{v} = \begin{pmatrix} 2 \\ b \\ 2 \end{pmatrix}$ orthogonal zum Normalenvektor $\vec{n}_{0,5}$ stehen:
$$
\begin{aligned}
\vec{v} \cdot \vec{n}_{0,5} = 0 \\\\
\begin{pmatrix} 2 \\\\ b \\\\ 2 \end{pmatrix} \cdot \begin{pmatrix} 1 \\\\ 1 \\\\ -0,5 \end{pmatrix} = 0 \\\\
2 \cdot 1 + b \cdot 1 + 2 \cdot (-0,5) = 0 \\\\
2 + b - 1 = 0 \\\\
b + 1 = 0 \implies b = -1
\end{aligned}
$$

Für $a = 0,5$ und $b = -1$ liegt die Gerade $g$ vollständig in der Ebene $E_{0,5}$.