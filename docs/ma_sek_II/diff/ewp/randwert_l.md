# Rechteck mit Randwert - Lösung

### 1. Zielfunktion
Die Fläche berechnet sich aus Höhe $f(x)$ und Breite $(4-x)$:
$$
\begin{aligned}
A(x) &= (4-x) \cdot \left( \frac{7}{16}x^2 + 2 \right) \\\\
&= -\frac{7}{16}x^3 + \frac{7}{4}x^2 - 2x + 8
\end{aligned}
$$

### 2. Lokale Extrempunkte
Wir bilden die Ableitung und setzen sie Null:
$$
A'(x) = -\frac{21}{16}x^2 + \frac{14}{4}x - 2 = 0
$$
Mittels Taschenrechner ergibt sich:

* $x_1   \approx 0,83$
* $x_2  \approx 1,83$

### 3. Nachweis der Art der Extrempunkte

Um die Art der Extrempunkte zu bestimmen, bilden wir die zweite Ableitung $A''(x)$:
$$
\begin{aligned}
A''(x) &= -\frac{42}{16}x + \frac{14}{4} \\\\
&= -\frac{21}{8}x + 3{,}5
\end{aligned}
$$

Nun setzen wir die kritischen Werte $x_1$ und $x_2$ in $A''(x)$ ein:

**Untersuchung von $x_1 \approx 0{,}83$:**
$$
\begin{aligned}
A''(0{,}83) &\approx -\frac{21}{8} \cdot 0{,}83 + 3{,}5 \\\\
&\approx 1{,}32 > 0 \implies \text{lokales Minimum}
\end{aligned}
$$

**Untersuchung von $x_2 \approx 1{,}83$:**
$$
\begin{aligned}
A''(1{,}83) &\approx -\frac{21}{8} \cdot 1{,}83 + 3{,}5 \\\\
&\approx -1{,}30 < 0 \implies \text{lokales Maximum}
\end{aligned}
$$





Der Funktionswert am lokalen Maximum:
$$
A(1,83) \approx (4 - 1,83) \cdot f(1,83) \approx 7,51
$$

### 4. Randwertbetrachtung
Da wir ein globales Maximum im Intervall $[0, 4]$ suchen, müssen wir die Grenzen prüfen:

* **Rechter Rand ($x = 4$):**
$$
A(4) = (4 - 4) \cdot f(4) = 0
$$
(Das Rechteck hat die Breite 0).

* **Linker Rand ($x = 0$):**
$$
A(0) = (4 - 0) \cdot f(0) = 4 \cdot 2 = 8.
$$

### 5. Endergebnis
Der Vergleich zeigt: $A(0) = 8$ ist größer als das lokale Maximum $A(1,83) \approx 7,51$.

Die Fläche des Rechtecks wird also maximal, wenn der Punkt $Q$ auf der y-Achse liegt:

* **Optimaler Punkt:** $Q(0 | 2)$
* **Maximaler Flächeninhalt:** $A_{max} = 8$

**Fazit:** Das "rechnerische" Maximum der Kurve ist hier nur ein lokales Maximum; das globale Maximum liegt am Rand. Wird die Zielfunktion auf einem abgeschlossenen Intervall betrachtet, ist eine Randwertbetrachtung notwendig.
#
