# Abenteuer auf dem Campingplatz - Lösung

### a) Koordinaten der Wäscheklammern
Zuerst berechnen wir den Vektor $\vec{AB}$:
$$
\begin{aligned}
\vec{AB} = \vec{B} - \vec{A} = \begin{pmatrix} 4-3 \\\\ 5-2 \\\\ 1,5-1 \end{pmatrix} = \begin{pmatrix} 1 \\\\ 3 \\\\ 0,5 \end{pmatrix}
\end{aligned}
$$

Die Klammern teilen die Strecke in Fünftel:

*   **$K_1$ Verhältnis $1:4 \implies \frac{1}{5}$):  
** $\vec{OK_1} = \vec{OA} + 0,2 \cdot \vec{AB} = \begin{pmatrix} 3 \\ 2 \\ 1 \end{pmatrix} + \begin{pmatrix} 0,2 \\ 0,6 \\ 0,1 \end{pmatrix}= \begin{pmatrix} 3,2 \\ 2,6 \\ 1,1 \end{pmatrix}$ also $K_1(3,2 | 2,6 | 1,1)$
* analog ergibt sich für die weiteren Klammern: $K_2(3,4 | 3,2 | 1,2)$, $K_3(3,6 | 3,8 | 1,3)$ und $K_4(3,8 | 4,4 | 1,4)$


### b) Wurde die Wäsche getroffen?
**1. Berechnung des Mittelpunkts $M$:**
$$
\begin{aligned} \vec{OM} &= \vec{OA} + 0,5 \cdot \vec{AB} \\\\
\vec{OM} &= \begin{pmatrix} 3 \\\\ 2 \\\\ 1 \end{pmatrix} + 0,5 \cdot \begin{pmatrix} 1 \\\\ 3 \\\\ 0,5 \end{pmatrix} = \begin{pmatrix} 3,5 \\\\ 3,5 \\\\ 1,25 \end{pmatrix} \end{aligned}
$$
Der Mittelpunkt liegt bei $M(3,5 \mid 3,5 \mid 1,25)$.

**2. Abstand von $K_2$ zu $M$:**
Die $K_2$ und $K_3$ liegen am nächsten am Mittelpunkt. Da sie symmetrisch um den Mittelpunkt liegen, genügt zu überprüfen, ob einer der Punkte getroffen wurde.
Wir nutzen die Koordinaten von $K_2(3,4 \mid 3,2 \mid 1,2)$ aus Aufgabenteil a):
$$
\begin{aligned} \vec{K_2M} &= \vec{OM} - \vec{OK_2} = \begin{pmatrix} 0,1 \\\\ 0,3 \\\\ 0,05 \end{pmatrix}\
\end{aligned}
$$

Abstand im Modell (in LE):
$$
\begin{aligned} |\vec{K_2M}| &= \sqrt{0,1^2 + 0,3^2 + 0,05^2}\approx 0,3202 
\end{aligned}
$$

**3. Umrechnung und Vergleich:**
Da $1 \text{ LE} = 1 \text{ m} = 100 \text{ cm}$ ist, beträgt der Abstand:
$$ 0,3202 \cdot 100 \text{ cm} \approx 32,02 \text{ cm} $$

**Prüfung:**

*   Das Kleidungsstück ragt von $K_2$ aus $20 \text{ cm}$ in Richtung Mittelpunkt.
*   Der Vogel trifft die Leine mit $5 \text{ cm}$ Abstand zum Mittelpunkt.
*   Ein Treffer erfolgt nur, wenn der Abstand $d(K_2, M) \le 20 \text{ cm} + 5 \text{ cm} = 25 \text{ cm}$ wäre.

**Ergebnis:**
Da $32,02 \text{ cm} > 25 \text{ cm}$ ist, wurde kein Kleidungsstück getroffen. Der Vogel hat die Lücke zwischen den Wäschestücken getroffen.