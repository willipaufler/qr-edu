# Rund ums Dreieck - Lösung

### a) Nachweis der Dreieckseigenschaften und Berechnung des Mittelpunkts

Wir bestimmen zunächst die Verbindungsvektoren zwischen den Punkten $A$, $B$ und $C$:
$$
\begin{aligned}
\vec{AB} &= \begin{pmatrix} -3 - 4 \\\\ 5 - 7 \\\\ 6 - (-2) \end{pmatrix} = \begin{pmatrix} -7 \\\\ -2 \\\\ 8 \end{pmatrix} \\\\
\vec{BC} &= \begin{pmatrix} 1 - (-3) \\\\ -5 - 5 \\\\ 7 - 6 \end{pmatrix} = \begin{pmatrix} 4 \\\\ -10 \\\\ 1 \end{pmatrix} \\\\
\vec{AC} &= \begin{pmatrix} 1 - 4 \\\\ -5 - 7 \\\\ 7 - (-2) \end{pmatrix} = \begin{pmatrix} -3 \\\\ -12 \\\\ 9 \end{pmatrix}
\end{aligned}
$$
Da $\vec{AB}$ kein Vielfaches von $\vec{AC}$ bzw. $\vec{BC}$ ist, liegen die Punkte nicht auf einer gemeinsamen Geraden und bilden somit ein Dreieck.

Für den Nachweis der Rechtwinkligkeit prüfen wir das Skalarprodukt von $\vec{BA}$ und $\vec{BC}$:
$$
\begin{aligned}
\vec{BA} \cdot \vec{BC} &= \begin{pmatrix} 7 \\\\ 2 \\\\ -8 \end{pmatrix} \cdot \begin{pmatrix} 4 \\\\ -10 \\\\ 1 \end{pmatrix} \\\\
&= 7 \cdot 4 + 2 \cdot (-10) + (-8) \cdot 1 \\\\
&= 0
\end{aligned}
$$
Da das Skalarprodukt gleich $0$ ist, stehen die Seiten $AB$ und $BC$ senklecht aufeinander. Der rechte Winkel liegt am Eckpunkt $B$. Die gegenüberliegende side $AC$ ist somit die Hypotenuse.

Jetzt prüfen wir die Längen der beiden Katheten auf Gleichschenkligkeit:
$$
\begin{aligned}
|\vec{AB}| &= \sqrt{(-7)^2 + (-2)^2 + 8^2} = \sqrt{117} \\\\
|\vec{BC}| &= \sqrt{4^2 + (-10)^2 + 1^2}  = \sqrt{117}
\end{aligned}
$$
Wegen $|\vec{AB}| = |\vec{BC}|$ ist das Dreieck gleichschenklig.

Nun berechnen wir den Mittelpunkt $M$ der Hypotenuse $AC$:
$$
\begin{aligned}
\vec{OM} &= \frac{1}{2} \cdot (\vec{OA} + \vec{OC}) \\\\
&= \frac{1}{2} \cdot \left[ \begin{pmatrix} 4 \\\\ 7 \\\\ -2 \end{pmatrix} + \begin{pmatrix} 1 \\\\ -5 \\\\ 7 \end{pmatrix} \right] \\\\
&= \frac{1}{2} \cdot \begin{pmatrix} 5 \\\\ 2 \\\\ 5 \end{pmatrix} = \begin{pmatrix} \frac{5}{2} \\\\ 1 \\\\ \frac{5}{2} \end{pmatrix}
\end{aligned}
$$
Der Mittelpunkt der Hypotenuse lautet somit $M\left(\frac{5}{2} \middle| 1 \middle| \frac{5}{2}\right)$.

### b) Bestimmen des Punktes M und seine geometrische Bedeutung

Nach dem Satz des Thales im Raum (Thaleskreis-Analogon) ist der Mittelpunkt der Hypotenuse eines rechtwinkligen Dreiecks stets der Mittelpunkt des Umkreises. Dieser Punkt hat zu allen drei Ecken $A$, $B$ und $C$ denselben Abstand.

Der in Teilaufgabe a) berechnete Punkt $M\left(\frac{5}{2} \middle| 1 \middle| \frac{5}{2}\right)$ besitzt exakt die geforderte $y$-Koordinate $y=1$.

Geometrische Bedeutung: Der Punkt $M$ ist der **Umkreismittelpunkt** des Dreiecks $ABC$.

### c) Spiegelung des Eckpunktes und Bestimmung der Vierecksart

Der Eckpunkt, welcher der Hypotenuse gegenüberliegt, ist $B(-3|5|6)$. Für die Spiegelung am Punkt $M$ bestimmen wir zuerst den Verbindungsvektor $\vec{BM}$:
$$
\begin{aligned}
\vec{BM} &= \vec{OM} - \vec{OB} \\\\
&= \begin{pmatrix} \frac{5}{2} \\\\ 1 \\\\ \frac{5}{2} \end{pmatrix} - \begin{pmatrix} -3 \\\\ 5 \\\\ 6 \end{pmatrix} \\\\
&= \begin{pmatrix} \frac{11}{2} \\\\ -4 \\\\ -\frac{7}{2} \end{pmatrix}
\end{aligned}
$$
Nun berechnen wir den Ortsvektor des Spiegelpunktes $D$ über den Ansatz $\vec{OD} = \vec{OB} + 2\cdot\vec{BM}$:
$$
\begin{aligned}
\vec{OD} &= \begin{pmatrix} -3 \\\\ 5 \\\\ 6 \end{pmatrix} + 2 \cdot \begin{pmatrix} \frac{11}{2} \\\\ -4 \\\\ -\frac{7}{2} \end{pmatrix} \\\\
&= \begin{pmatrix} 8 \\\\ -3 \\\\ -1 \end{pmatrix}
\end{aligned}
$$
Der Spiegelpunkt lautet somit $D(8|-3|-1)$.

Untersuchung der Vierecksart $ABCD$:

* Die Diagonalen $AC$ und $BD$ schneiden und halbieren sich im gemeinsamen Punkt $M$ (durch die Spiegelung bedingt). Ein Viereck mit sich halbierenden Diagonalen ist ein Parallelogramm.
* Am Eckpunkt $B$ liegt ein rechter Winkel vor ($\vec{AB} \perp \vec{BC}$). Ein Parallelogramm mit einem rechten Winkel ist ein Rechteck.
* Die beiden an $B$ anliegenden Seiten sind gleich lang ($|\vec{AB}| = |\vec{BC}|$). Ein Rechteck mit zwei gleich langen, benachbarten Seiten ist ein Quadrat.

Das Viereck $ABCD$ ist somit ein **Quadrat**.