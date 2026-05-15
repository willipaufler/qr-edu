# Schnittwinkel - Lösung

### a) Schnittpunkt und Schnittwinkel von f und g
**1. Schnittstelle berechnen:**
$$
\begin{aligned}
x^2 - 6x + 8 &= x^3 + 2x^2 + 2x + 8 \\\\
0 &= x^3 + x^2 + 8x \\\\
0 &= x \cdot (x^2 + x + 8)
\end{aligned}
$$
Die einzige reelle Lösung ist $x_s = 0$. 
Der Schnittpunkt ist $S(0|f(0))$, also $S(0|8)$.

**2. Steigungen an der Schnittstelle:**

$f'(x) = 2x - 6 \Rightarrow m_1 = f'(0) = -6$  
$g'(x) = 3x^2 + 4x + 2 \Rightarrow m_2 = g'(0) = 2$

**3. Schnittwinkel berechnen (Weg 1: Differenz der Steigungswinkel)**

Zuerst berechnen wir die einzelnen Steigungswinkel $\alpha_1$ und $\alpha_2$ zur positiven $x$-Achse:
$$
\begin{aligned}
\alpha_1 &= \arctan(m_1) = \arctan(-6) \approx -80,54^\circ \\\\
\alpha_2 &= \arctan(m_2) = \arctan(2) \approx 63,43^\circ
\end{aligned}
$$

Der Schnittwinkel $\gamma$ ist die Differenz dieser Winkel. Da der Winkel stets als spitzer Winkel angegeben wird, nutzen wir Betragsstriche und korrigieren, falls der berechnete Wert größer als $90^\circ$ ist:
$$
\begin{aligned}
\tilde{\gamma} &= |\alpha_1 - \alpha_2| \\\\
\tilde{\gamma} &= |-80,54^\circ - 63,43^\circ| \\\\
\tilde{\gamma} &= |-143,97^\circ| = 143,97^\circ
\end{aligned}
$$

Da der Schnittwinkel als der spitze Winkel zwischen den Geraden definiert ist, berechnen wir den Nebenwinkel:
$$
\begin{aligned}
\gamma &= 180^\circ - 143,97^\circ \\\\
\gamma &\approx 36,03^\circ
\end{aligned}
$$

**Alternative (Weg 2: Schnittwinkelformel):**
Direkte Berechnung über die Formel:
$$
\begin{aligned}
\tan(\gamma) &= \left| \frac{m_1 - m_2}{1 + m_1 \cdot m_2} \right| \\\\
\tan(\gamma) &= \left| \frac{-6 - 2}{1 + (-6) \cdot 2} \right| = \left| \frac{-8}{-11} \right| = \frac{8}{11} \\\\
\gamma &= \arctan\left(\frac{8}{11}\right) \approx 36,03^\circ
\end{aligned}
$$

---

### b) Schnittwinkel im zweiten Quadranten
**1. Schnittstellen berechnen:**
$$
\begin{aligned}
0,5x^2 + x + 3 &= 0,5x + 4 \\\\
0,5x^2 + 0,5x - 1 &= 0 \\\\
x^2 + x - 2 &= 0 \\\\
(x+2)(x-1) &= 0
\end{aligned}
$$
Schnittstellen sind $x_1 = -2$ und $x_2 = 1$.
Da der Schnittpunkt im **zweiten Quadranten** liegen muss ($x < 0$), ist nur $x_s = -2$ relevant.
$f(-2) = 0,5(-2)^2 + (-2) + 3 = 2 - 2 + 3 = 3 \Rightarrow S(-2|3)$.

**2. Steigungen berechnen:**
$f'(x) = x + 1 \Rightarrow m_1 = f'(-2) = -1$
$g'(x) = 0,5 \Rightarrow m_2 = 0,5$

**3. Schnittwinkel berechnen:**
$$
\begin{aligned}
\alpha_1 &= \arctan(-1) = -45^\circ \\\\
\alpha_2 &= \arctan(0,5) \approx 26,57^\circ \\\\
\gamma &= |26,57^\circ - (-45^\circ)| = 71,57^\circ
\end{aligned}
$$

**Ergebnis:** Der Schnittwinkel im zweiten Quadranten beträgt ca. $71,57^\circ$.