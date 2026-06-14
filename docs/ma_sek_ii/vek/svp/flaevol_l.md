# Flächen und Volumen - Lösung

### 1) Berechnung von D und des Flächeninhalts des Parallelogramms

**Berechnung des Punktes $D$:**
Da die Punkte $A$, $B$, $C$ und $D$ ein Parallelogramm in dieser Reihenfolge bilden, muss der Vektor $\vec{AD}$ gleich dem Vektor $\vec{BC}$ sein.

Zuerst bestimmen wir den Verbindungsvektor $\vec{BC}$:
$$
\vec{BC} = \vec{OC} - \vec{OB} = \begin{pmatrix} 3 - 3 \\\\ 1 - 4 \\\\ 0 - (-3) \end{pmatrix} = \begin{pmatrix} 0 \\\\ -3 \\\\ 3 \end{pmatrix}
$$

Diesen hängen wir an den Ortsvektor von $A$ an, um zu $D$ zu gelangen:
$$
\vec{OD} = \vec{OA} + \vec{BC} = \begin{pmatrix} 1 \\\\ -2 \\\\ 3 \end{pmatrix} + \begin{pmatrix} 0 \\\\ -3 \\\\ 3 \end{pmatrix} = \begin{pmatrix} 1 \\\\ -5 \\\\ 6 \end{pmatrix}
$$
Der gesuchte Punkt lautet somit **$D(1|-5|6)$**.

**Berechnung des Flächeninhalts:**
Der Flächeninhalt des Parallelogramms entspricht dem Betrag des Kreuzprodukts der aufspannenden Vektoren $\vec{AB}$ und $\vec{BC}$.

Wir bestimmen $\vec{AB}$:
$$
\vec{AB} = \begin{pmatrix} 3 - 1 \\\\ 4 - (-2) \\\\ -3 - 3 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 6 \\\\ -6 \end{pmatrix}
$$

Nun bilden wir das Kreuzprodukt $\vec{AB} \times \vec{BC}$:
$$
\vec{AB} \times \vec{BC} = \begin{pmatrix} 2 \\\\ 6 \\\\ -6 \end{pmatrix} \times \begin{pmatrix} 0 \\\\ -3 \\\\ 3 \end{pmatrix} = \begin{pmatrix} 6 \cdot 3 - (-6) \cdot (-3) \\\\ (-6) \cdot 0 - 2 \cdot 3 \\\\ 2 \cdot (-3) - 6 \cdot 0 \end{pmatrix} = \begin{pmatrix} 18 - 18 \\\\ -6 \\\\ -6 \end{pmatrix} = \begin{pmatrix} 0 \\\\ -6 \\\\ -6 \end{pmatrix}
$$

Der Flächeninhalt $A_{\text{Para}}$ ist der Betrag dieses Vektors:
$$
A_{\text{Para}} = \sqrt{0^2 + (-6)^2 + (-6)^2} = \sqrt{0 + 36 + 36} = \sqrt{72} = 6\sqrt{2} \approx 8{,}49\text{ FE}
$$
Der Flächeninhalt des Parallelogramms beträgt **$6\sqrt{2}\text{ FE}$** (ca. $8{,}49\text{ Flächeneinheiten}$).

---

### 2) Flächeninhalt der Dreiecke ABC und ABD

Jede Diagonale teilt ein Parallelogramm in zwei flächengleiche Dreiecke. 

* Das Dreieck $ABC$ entsteht durch die Halbierung des Parallelogramms entlang der Diagonale $AC$.
* Das Dreieck $ABD$ entsteht durch die Halbierung des Parallelogramms entlang der Diagonale $BD$.

Daraus folgt direkt ohne weiteren Rechenaufwand:
$$
A_{ABC} = A_{ABD} = \frac{1}{2} \cdot A_{\text{Para}} = \frac{1}{2} \cdot 6\sqrt{2} = 3\sqrt{2} \approx 4{,}24\text{ FE}
$$
Beide Dreiecke besitzen einen Flächeninhalt von **$3\sqrt{2}\text{ FE}$** (ca. $4{,}24\text{ Flächeneinheiten}$).

---

### 3) Vektor senkrecht zu allen Seiten des Parallelogramms

Ein Vektor steht senkrecht auf allen Seiten des Parallelogramms, wenn er senkrecht auf der aufgespannten Ebene steht (Normalenvektor). Das in Teilaufgabe 1 berechnete Kreuzprodukt erfüllt genau diese Eigenschaft:
$$
\vec{n} = \begin{pmatrix} 0 \\\\ -6 \\\\ -6 \end{pmatrix}
$$
Für die spätere Weiterarbeit ist es mathematisch und rechnerisch am elegantesten, hieraus direkt den **Normaleneinheitsvektor** $\vec{n}_0$ (einen Normalenvektor mit der Länge 1) zu bestimmen.

Dazu kürzen wir den Vektor zunächst durch $-6$:
$$
\vec{n} = \begin{pmatrix} 0 \\\\ 1 \\\\ 1 \end{pmatrix}
$$
Die Länge dieses Vektors beträgt $|\vec{n}| = \sqrt{0^2 + 1^2 + 1^2} = \sqrt{2}$. Durch Division des Vektors durch seine Länge erhalten wir den Normaleneinheitsvektor:
$$
\vec{n}_0 = \frac{1}{\sqrt{2}} \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 1 \end{pmatrix}
$$

---

### 4) Bestimmung der Pyramidenspitze S und Anzahl der Punkte

**Schritt 1: Höhe $h$ berechnen**
Die Volumenformel einer Pyramide lautet:
$$
V = \frac{1}{3} \cdot G \cdot h
$$
Mit dem gegebenen Volumen $V = 8\text{ VE}$ und der Grundfläche $G = 6\sqrt{2}\text{ FE}$ setzen wir an:
$$
8 = \frac{1}{3} \cdot 6\sqrt{2} \cdot h \implies 8 = 2\sqrt{2} \cdot h \implies h = \frac{8}{2\sqrt{2}} = \frac{4}{\sqrt{2}} = 2\sqrt{2} \approx 2{,}83\text{ LE}
$$

**Schritt 2: Diagonalenmittelpunkt $M$ (Lotfußpunkt) berechnen**
Der Mittelpunkt der Diagonalen liegt genau in der Mitte der Strecke $AC$:
$$
\begin{aligned}
\vec{OM} &= \frac{1}{2} \cdot (\vec{OA} + \vec{OC}) \\\\
&= \frac{1}{2} \cdot \left[ \begin{pmatrix} 1 \\\\ -2 \\\\ 3 \end{pmatrix} + \begin{pmatrix} 3 \\\\ 1 \\\\ 0 \end{pmatrix} \right] \\\\
&= \begin{pmatrix} 2 \\\\ -0{,}5 \\\\ 1{,}5 \end{pmatrix}
\end{aligned}
$$

**Schritt 3: Spitze $S$ bestimmen**
Wir nutzen den in Teilaufgabe 3 vorbereiteten Normaleneinheitsvektor $\vec{n}_0$. Da dieser exakt die Länge 1 besitzt, können wir die Höhe $h = 2\sqrt{2}$ direkt als Skalar multiplizieren und vom Mittelpunkt $M$ aus in beide Richtungen abtragen:
$$
\begin{aligned}
\vec{OS} &= \vec{OM} \pm h \cdot \vec{n}_0 \\\\
&= \begin{pmatrix} 2 \\\\ -0{,}5 \\\\ 1{,}5 \end{pmatrix} \pm 2\sqrt{2} \cdot \frac{1}{\sqrt{2}} \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 1 \end{pmatrix} \\\\
&= \begin{pmatrix} 2 \\\\ -0{,}5 \\\\ 1{,}5 \end{pmatrix} \pm 2 \cdot \begin{pmatrix} 0 \\\\ 1 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Daraus ergeben sich die zwei möglichen Punkte für die Spitze:
$$
\vec{OS}_1 = \begin{pmatrix} 2 \\\\ -0{,}5 \\\\ 1{,}5 \end{pmatrix} + \begin{pmatrix} 0 \\\\ 2 \\\\ 2 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 1{,}5 \\\\ 3{,}5 \end{pmatrix} \implies S_1(2 \mid 1{,}5 \mid 3{,}5)
$$
$$
\vec{OS}_2 = \begin{pmatrix} 2 \\\\ -0{,}5 \\\\ 1{,}5 \end{pmatrix} - \begin{pmatrix} 0 \\\\ 2 \\\\ 2 \end{pmatrix} = \begin{pmatrix} 2 \\\\ -2{,}5 \\\\ -0{,}5 \end{pmatrix} \implies S_2(2 \mid -2{,}5 \mid -0{,}5)
$$

**Anzahl solcher Punkte:**
Es gibt exakt **zwei** solcher Punkte, da man die errechnete Höhe senkrecht zur Grundfläche sowohl in die eine Richtung („nach oben“) als auch in die entgegengesetzte Richtung („nach unten“) abtragen kann.