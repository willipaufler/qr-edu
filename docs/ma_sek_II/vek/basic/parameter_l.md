# Vektoren mit Parametern - Lösung

### a) Bestimmen von t für gleiche Beträge
Gleichsetzen der quadrierten Beträge:
$$
\begin{aligned} (t+1)^2 + 16 + 4 &= (4-2t)^2 + 4 + 1 \\\\
t^2 + 2t + 1 + 20 &= 16 - 16t + 4t^2 + 5 \\\\
0 &= 3t^2 - 18t \\\\
0 &= 3t(t - 6) \end{aligned}
$$
Die Lösungen sind $t_{1} = 0$ und $t_{2} = 6$.

### b) Untersuchung auf Kollinearität
Ansatz: $\vec{a} = k \cdot \vec{b}$
$$
\begin{aligned} (1) && t+1 &= k \cdot (4-2t) \\\\
(2) && 4 &= k \cdot (-2) && \implies k = -2 \\\\
(3) && -2 &= k \cdot 1 && \implies k = -2 \end{aligned}
$$
Einsetzen von $k = -2$ in (1):
$$
\begin{aligned} t+1 &= -2 \cdot (4-2t) \\\\
t+1 &= -8 + 4t \\\\
9 &= 3t \\\\
t &= 3 \end{aligned}
$$
Für $t = 3$ sind die Vektoren kollinear.

### c) Ermitteln des t-unabhängigen komplanaren Vektors
Um $t$ in der ersten Komponente zu eliminieren, wählen wir die Kombination $2 \cdot \vec{a} + 1 \cdot \vec{b}$:
$$
\begin{aligned} \vec{v} &= 2 \cdot \vec{a} + \vec{b} \\\\
\vec{v} &= 2 \cdot \begin{pmatrix} t+1 \\\\ 4 \\\\ -2 \end{pmatrix} + \begin{pmatrix} 4-2t \\\\ -2 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 6 \\\\ 6 \\\\ -3 \end{pmatrix} 
\end{aligned}
$$
Da $\vec{v}$ als Linearkombination von $\vec{a}$ und $\vec{b}$ darstellbar ist, ist sind $\vec{v}$, $\vec{a}$ und $\vec{b}$ komplanar. Das Ergebnis ist unabhängig von $t$.


### d) Bestimmung von $t$ für den Einheitsvektor

**1. Berechnung der Linearkombination $\vec{c}$:**
$$
\begin{aligned}
\vec{c} &= \frac{2}{3} \begin{pmatrix} t+1 \\\\ 4 \\\\ -2 \end{pmatrix} + \begin{pmatrix} 4-2t \\\\ -2 \\\\ 1 \end{pmatrix} = \begin{pmatrix} -\frac{4}{3}t + \frac{14}{3} \\\\ \frac{2}{3} \\\\ -\frac{1}{3} \end{pmatrix}
\end{aligned}
$$

**2. Aufstellen der Betragsgleichung:**
Ein Einheitsvektor erfüllt $|\vec{c}|^2 = 1$.
$$
\begin{aligned}
\left(-\frac{4}{3}t + \frac{14}{3}\right)^2 + \left(\frac{2}{3}\right)^2 + \left(-\frac{1}{3}\right)^2 &= 1 \\\\
\left(\frac{-4t+14}{3}\right)^2 + \frac{4}{9} + \frac{1}{9} &= 1 \\\\
\frac{(-4t+14)^2}{9} + \frac{5}{9} &= \frac{9}{9} \quad | \cdot 9 \\\\
(-4t+14)^2 &= 4
\end{aligned}
$$

**3. Lösen der Gleichung:**
Anstatt die Klammer mühsam aufzulösen, ziehen wir direkt die Wurzel (Vorsicht: zwei Fälle!):
$$
\begin{aligned}
-4t + 14 &= 2 \quad &&\text{oder} \quad -4t + 14 = -2 \\\\
-4t &= -12 \quad &&\text{oder} \quad -4t = -16 \\\\
\mathbf{t_1} &= \mathbf{3} \quad \quad &&\text{oder} \quad \mathbf{t_2 = 4}
\end{aligned}
$$

**Ergebnis:** Für $t=3$ oder $t=4$ ist der Vektor $\vec{c}$ ein Einheitsvektor.