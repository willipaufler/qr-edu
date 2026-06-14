# Lotfußpunkt im Dreieck - Lösung

### a) Bestimmung des Lotfußpunktes $H$ via Projektion

Zuerst bestimmen wir die benötigten Vektoren:
$$
\vec{AB} = \begin{pmatrix} 7 - 1 \\\\ 5 - (-1) \\\\ 5 - 2 \end{pmatrix} = \begin{pmatrix} 6 \\\\ 6 \\\\ 3 \end{pmatrix}, \quad \vec{AC} = \begin{pmatrix} 2 - 1 \\\\ 3 - (-1) \\\\ 1 - 2 \end{pmatrix} = \begin{pmatrix} 1 \\\\ 4 \\\\ -1 \end{pmatrix}
$$

Jetzt berechnen wir die Bestandteile für die Projektionsformel:

* **Skalarprodukt:** $\vec{AC} \cdot \vec{AB} = 1 \cdot 6 + 4 \cdot 6 + (-1) \cdot 3 = 27$
* **Quadrat der Länge:** $|\vec{AB}|^2 = 6^2 + 6^2 + 3^2 = 81$

Daraus ergibt sich der Vektor $\vec{AH}$:
$$
\vec{AH} = \frac{\vec{AC} \cdot \vec{AB}}{|\vec{AB}|^2} \cdot \vec{AB} = \frac{27}{81} \cdot \begin{pmatrix} 6 \\\\ 6 \\\\ 3 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix}
$$

Den Ortsvektor des Lotfußpunktes $H$ erhalten wir durch Addition zu $A$:
$$
\vec{OH} = \vec{OA} + \vec{AH} = \begin{pmatrix} 1 \\\\ -1 \\\\ 2 \end{pmatrix} + \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 3 \\\\ 1 \\\\ 3 \end{pmatrix} \implies \mathbf{H(3 \mid 1 \mid 3)}
$$

---

### b) Längen und Flächeninhalt des Dreiecks

**Länge der Grundseite $c = |\vec{AB}|$:**
$$
|\vec{AB}| = \sqrt{81} = 9\text{ LE}
$$

**Länge der Höhe $h_c = |\vec{CH}|$:**
Zuerst bestimmen wir den Höhenvektor $\vec{CH}$:
$$
\vec{CH} = \vec{OH} - \vec{OC} = \begin{pmatrix} 3 - 2 \\\\ 1 - 3 \\\\ 3 - 1 \end{pmatrix} = \begin{pmatrix} 1 \\\\ -2 \\\\ 2 \end{pmatrix}
$$
Nun berechnen wir dessen Betrag:
$$
|\vec{CH}| = \sqrt{1^2 + (-2)^2 + 2^2} = 3\text{ LE}
$$

**Berechnung des Flächeninhalts:**
$$
A_{\Delta} = \frac{1}{2} \cdot g \cdot h = \frac{1}{2} \cdot |\vec{AB}| \cdot |\vec{CH}| = \frac{1}{2} \cdot 9 \cdot 3 = \mathbf{13{,}5\text{ FE}}
$$

---

### c) Berechnung der Innenwinkel

**Winkel $\alpha$ (bei Punkt $A$):**
Aufgespannt von $\vec{AB}$ und $\vec{AC}$. Länge von $|\vec{AC}| = \sqrt{1^2 + 4^2 + (-1)^2} = \sqrt{18} = 3\sqrt{2}$.
$$
\cos(\alpha) = \frac{\vec{AB} \cdot \vec{AC}}{|\vec{AB}| \cdot |\vec{AC}|} = \frac{27}{9 \cdot 3\sqrt{2}} = \frac{27}{27\sqrt{2}} = \frac{1}{\sqrt{2}} \implies \mathbf{\alpha = 45^\circ}
$$

**Winkel $\beta$ (bei Punkt $B$):**
Aufgespannt von $\vec{BA} = \begin{pmatrix} -6 \\ -6 \\ -3 \end{pmatrix}$ und $\vec{BC} = \begin{pmatrix} -5 \\ -2 \\ -4 \end{pmatrix}$. Länge von $|\vec{BC}| = \sqrt{25 + 4 + 16} = \sqrt{45} = 3\sqrt{5}$.
$$
\cos(\beta) = \frac{\vec{BA} \cdot \vec{BC}}{|\vec{BA}| \cdot |\vec{BC}|} = \frac{30 + 12 + 12}{27\sqrt{5}} =  \approx 0{,}8944 \implies \mathbf{\beta \approx 26{,}57^\circ}
$$

**Winkel $\gamma$ (bei Punkt $C$):**
Über die Innenwinkelsumme:
$$
\gamma = 180^\circ - 45^\circ - 26{,}57^\circ = \mathbf{108{,}43^\circ}
$$