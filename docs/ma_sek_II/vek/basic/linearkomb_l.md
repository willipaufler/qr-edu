# Fließbandarbeit - Lösung

### a) Linearkombination im $\mathbb{R}^2$
Ansatz: $\begin{pmatrix} 0 \\ 5 \end{pmatrix} = r \cdot \begin{pmatrix} 2 \\ 3 \end{pmatrix} + s \cdot \begin{pmatrix} 4 \\ 1 \end{pmatrix}$
$$
\begin{aligned} (1) && 0 &= 2r + 4s && \implies r = -2s \\\\
(2) && 5 &= 3r + s \end{aligned}
$$

Einsetzen von (1) in (2):
$$
\begin{aligned} 5 &= 3(-2s) + s \\\\
5 &= -5s \\\\
s &= -1 \end{aligned}
$$
Daraus folgt $r = 2$.
Lösung: $\vec{c} = 2\vec{a} - \vec{b}$

### b) Linearkombination im $\mathbb{R}^3$
Ansatz: $\begin{pmatrix} -9 \\ 12 \\ -6 \end{pmatrix} = r \cdot \begin{pmatrix} 2 \\ -1 \\ -2 \end{pmatrix} + s \cdot \begin{pmatrix} -4 \\ 5 \\ -2 \end{pmatrix}$
liefert folgende Gleichungen: 
$$
\begin{aligned} 
(1) && -9 &= 2r - 4s \\\\
(2) && 12 &= -r + 5s && \implies r = 5s - 12 \\\\
(3) && -6 &= -2r - 2s \end{aligned}
$$

Einsetzen von (2) in (1):
$$
\begin{aligned} 
-9 &= 2(5s - 12) - 4s \\\\
15 &= 6s \\\\
s &= \frac{5}{2} \end{aligned}
$$
Daraus folgt $r = 5(\frac{5}{2}) - 12 = \frac{1}{2}$.

Überprüfung mit (3):
$$
\begin{aligned} -6 &= -2\left(\frac{1}{2}\right) - 2\left(\frac{5}{2}\right) \\\\
-6 &= -6 \quad (\text{wahr}) \end{aligned}
$$
Lösung: $\vec{c} = \frac{1}{2}\vec{a} + \frac{5}{2}\vec{b}$

### c) Untersuchung auf Lösbarkeit
Ansatz: $\begin{pmatrix} 3 \\ 3 \\ 5 \end{pmatrix} = r \cdot \begin{pmatrix} 1 \\ 2 \\ 0 \end{pmatrix} + s \cdot \begin{pmatrix} 2 \\ 1 \\ 0 \end{pmatrix}$

Betrachtung der 3. Zeile:
$$
\begin{aligned} (3) && 5 &= r \cdot 0 + s \cdot 0 \\\\
&& 5 &= 0 \quad (\text{falsch}) \end{aligned}
$$
Da die dritte Gleichung einen Widerspruch liefert, kann $\vec{c}$ nicht als Linearkombination von $\vec{a}$ und $\vec{b}$ dargestellt werden. Der Vektor $\vec{c}$ liegt nicht in der von $\vec{a}$ und $\vec{b}$ aufgespannten Ebene (xy-Ebene).