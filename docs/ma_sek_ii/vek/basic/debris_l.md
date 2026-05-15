# Lösung: Mission Debris-Control

### a) Prüfung auf Komplanarität

#### Option 1: Lösung mit CAS
Der Ansatz: $0=r\cdot \vec{v}_1 + s\cdot \vec{v}_2+t\cdot \vec{v}_3$ liefert neben der trivialen Lösung $r=s=t=0$ keine Lösung.  
**Ergebnis:** Die Vektoren sind **nicht komplanar**.


#### Option 2: Händische Lösung
Untersuchung auf Linearkombination: $r \cdot \vec{v}_1 + s \cdot \vec{v}_2 = \vec{v}_3$

**Gleichungssystem:**
$$
\begin{aligned}
(1)&& \quad \frac{11}{10}r + \frac{9}{10}s &= \frac{21}{20} \\\\
(2)&& \quad \frac{31}{10}r + \frac{29}{10}s &= \frac{31}{10} \\\\
(3)&& \quad \frac{4}{10}r + \frac{6}{10}s &= \frac{11}{20}
\end{aligned}
$$

**Lösen über (1) und (2):**
Multiplikation von (2) mit 10 liefert: $31r + 29s = 31 \implies s = \frac{31}{29}(1-r)$.  
Einsetzen in (1) und zuvor Multiplikation mit 20:
$$
\begin{aligned}
22r + 18s &= 21 \\\\
22r + 18 \cdot \left(\frac{31}{29}(1-r)\right) &= 21 \\\\
80r &= 51 \implies \mathbf{r = \frac{51}{80}}
\end{aligned}
$$

Berechnung von $s$:
$$
\begin{aligned}
s &= \frac{31}{29} \cdot \left(1 - \frac{51}{80}\right) \\\\
s &= \frac{31}{29} \cdot \frac{29}{80} \implies \mathbf{s = \frac{31}{80}}
\end{aligned}
$$

**Überprüfung in (3):**
$$
\begin{aligned}
\frac{4}{10} \cdot \frac{51}{80} + \frac{6}{10} \cdot \frac{31}{80} &= \frac{11}{20} \\\\
\frac{204}{800} + \frac{186}{800} &= \frac{440}{800} \\\\
\frac{390}{800} &\neq \frac{440}{800}
\end{aligned}
$$
**Ergebnis:** Da $\frac{39}{80} \neq \frac{44}{80}$, liegt ein Widerspruch vor. Die Vektoren sind **nicht komplanar**.


---

### b) Ermittlung von $\vec{v}_4$
Impulserhaltung (gekürzt durch den Faktor 100):
$$10 \cdot \vec{v}_S = 2 \cdot \vec{v}_1 + 3 \cdot \vec{v}_2 + 4 \cdot \vec{v}_3 + 1 \cdot \vec{v}_4$$

**Berechnung:**
$$
\begin{aligned}
\vec{v}_4 &= \begin{pmatrix} 10 \\\\ 30 \\\\ 5 \end{pmatrix} - \begin{pmatrix} 2,2 \\\\ 6,2 \\\\ 0,8 \end{pmatrix} - \begin{pmatrix} 2,7 \\\\ 8,7 \\\\ 1,8 \end{pmatrix} - \begin{pmatrix} 4,2 \\\\ 12,4 \\\\ 2,2 \end{pmatrix} \\\\
\vec{v}_4 &= \mathbf{\begin{pmatrix} 0,9 \\\\ 2,7 \\\\ 0,2 \end{pmatrix}}
\end{aligned}
$$

---

### c) Interpretation und Betrag von $\vec{u}$
**Interpretation:** Der Vektor $\vec{u}$ ist der Differenzvektor zwischen der Geschwindigkeit nach und vor dem Zerbrechen. Er beschreibt die zusätzliche Beschleunigung bzw. Ablenkung (nach Betrag und Richtung), die das vierte Fragment durch das Ereignis erfahren hat.

**Berechnung des Betrags:**
$$
\begin{aligned}
\vec{u} &= \begin{pmatrix} -0,1 \\\\ -0,3 \\\\ -0,3 \end{pmatrix} \\\\
|\vec{u}| &= \sqrt{\left(-0,1\right)^2 + \left(-0,3\right)^2 + \left(-0,3\right)^2} \approx \mathbf{0,436 \, \text{km/s}}
\end{aligned}
$$