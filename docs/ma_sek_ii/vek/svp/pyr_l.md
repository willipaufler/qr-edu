# Pyramidenvolumen mit Parameter - Lösung

### a) Nachweis des Parallelogramms

Wir bestimmen die Gegenvektoren $\vec{AB}$ und $\vec{DC}$:
$$
\vec{AB} = \begin{pmatrix} 3 - 1 \\\\ 4 - 2 \\\\ 4 - 3 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix}, \quad \vec{DC} = \begin{pmatrix} 5 - 3 \\\\ 3 - 1 \\\\ 2 - 1 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix}
$$
Da $\vec{AB} = \vec{DC}$ gilt, sind die gegenüberliegenden Seiten parallel und gleich lang. Das Viereck $ABCD$ ist somit ein Parallelogramm.

---

### b) Volumenbestimmung in Abhängigkeit von $t$

1. **Kreuzprodukt der Grundflächevektoren ($\vec{AB} \times \vec{AD}$):**
   $$
   \vec{AD} = \begin{pmatrix} 3 - 1 \\\\ 1 - 2 \\\\ 1 - 3 \end{pmatrix} = \begin{pmatrix} 2 \\\\ -1 \\\\ -2 \end{pmatrix}
   $$
   $$
   \vec{AB} \times \vec{AD} = \begin{pmatrix} 2 \\\\ 2 \\\\ 1 \end{pmatrix} \times \begin{pmatrix} 2 \\\\ -1 \\\\ -2 \end{pmatrix} = \begin{pmatrix} 2 \cdot (-2) - 1 \cdot (-1) \\\\ 1 \cdot 2 - 2 \cdot (-2) \\\\ 2 \cdot (-1) - 2 \cdot 2 \end{pmatrix} = \begin{pmatrix} -3 \\\\ 6 \\\\ -6 \end{pmatrix}
   $$

2. **Kantenvektor zur Spitze ($\vec{AS_t}$):**
   $$
   \vec{AS_t} = \begin{pmatrix} t - 1 \\\\ 6 - 2 \\\\ 8 - 3 \end{pmatrix} = \begin{pmatrix} t - 1 \\\\ 4 \\\\ 5 \end{pmatrix}
   $$

3. **Spatprodukt und Pyramidenvolumen:**
   $$
   (\vec{AB} \times \vec{AD}) \cdot \vec{AS_t} = \begin{pmatrix} -3 \\\\ 6 \\\\ -6 \end{pmatrix} \cdot \begin{pmatrix} t - 1 \\\\ 4 \\\\ 5 \end{pmatrix} = -3t - 3
   $$
   Eingesetzt in die Volumenformel:
   $$
   V(t) = \frac{1}{3} \cdot |-3t - 3| = \frac{1}{3} \cdot 3 \cdot |-t - 1| = \mathbf{|t + 1|}
   $$

---

### c) Bestimmung von $t$ für $V = 5\text{ VE}$

Wir lösen die Betragsgleichung $|t + 1| = 5$:

* **Fall 1:** $t + 1 = 5 \implies \mathbf{t_1 = 4}$
* **Fall 2:** $t + 1 = -5 \implies \mathbf{t_2 = -6}$

Für die Parameterwerte **$t = 4$** und **$t = -6$** besitzt die Pyramide ein Volumen von genau $5\text{ VE}$.

---

### d) Sonderfall $V = 0\text{ VE}$
Das Volumen wird Null, falls:
$$
\begin{aligned}
|t + 1| = 0 \implies \mathbf{t = -1}
\end{aligned}
$$

**Geometrische Bedeutung:**

* Für $t = -1$ liegt die Pyramidenspitze $S_{-1}(-1|6|8)$ direkt in der Ebene der Grundfläche $ABCD$. Es existiert kein dreidimensionaler Körper mehr.
* Die drei aufspannenden Vektoren $\vec{AB}$, $\vec{AD}$ und $\vec{AS_{-1}}$ liegen in einer gemeinsamen Ebene. Sie sind linear abhängig bzw. **komplanar**.

---

### e) Untersuchung auf eine gerade Pyramide

Eine Pyramide ist gerade, wenn der Vektor von der Mitte der Grundfläche zur Spitze ($\vec{MS_t}$) parallel zum Normalenvektor der Ebene (Vektor senkrecht zur Grundfläche) verläuft.

1. **Mittelpunkt $M$ der Grundfläche:**
   $$
   \vec{OM} = \frac{1}{2} \cdot (\vec{OA} + \vec{OC}) = \frac{1}{2} \cdot \left[ \begin{pmatrix} 1 \\\\ 2 \\\\ 3 \end{pmatrix} + \begin{pmatrix} 5 \\\\ 3 \\\\ 2 \end{pmatrix} \right] = \begin{pmatrix} 3 \\\\ 2{,}5 \\\\ 2{,}5 \end{pmatrix}
   $$

2. **Vektor von $M$ zur Spitze $S_t$:**
   $$
   \vec{MS_t} = \vec{OS_t} - \vec{OM} = \begin{pmatrix} t \\\\ 6 \\\\ 8 \end{pmatrix} - \begin{pmatrix} 3 \\\\ 2{,}5 \\\\ 2{,}5 \end{pmatrix} = \begin{pmatrix} t - 3 \\\\ 3{,}5 \\\\ 5{,}5 \end{pmatrix}
   $$

3. **Prüfung auf Kollinearität mit dem vereinfachten Normalenvektor $\vec{n}_0 = \begin{pmatrix} -1 \\ 2 \\ -2 \end{pmatrix}$:**
   $$
   \begin{pmatrix} t - 3 \\\\ 3{,}5 \\\\ 5{,}5 \end{pmatrix} = k \cdot \begin{pmatrix} -1 \\\\ 2 \\\\ -2 \end{pmatrix}
   $$

   Daraus ergibt sich das lineare Gleichungssystem:

   * (I) $t - 3 = -1k$
   * (II) $3{,}5 = 2k \implies k = 1{,}75$
   * (III) $5{,}5 = -2k \implies k = -2{,}75$

**Fazit:** Aus den Gleichungen (II) und (III) folgt ein Widerspruch ($1{,}75 \neq -2{,}75$). Es gibt somit **keinen** Wert für den Parameter $t$, der die Pyramide zu einer geraden Pyramide macht. Die Pyramide bleibt für alle $t \in \mathbb{R}$ schief.