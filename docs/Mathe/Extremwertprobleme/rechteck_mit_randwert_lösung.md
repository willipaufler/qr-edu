# Rechteck mit Randwert - Lösung

### 1. Zielfunktion
Die Fläche berechnet sich aus Höhe $f(x)$ und Breite $(4-x)$:
$$
A(x) = (4-x) \cdot \left( \frac{7}{16}x^2 + 2 \right) = -\frac{7}{16}x^3 + \frac{7}{4}x^2 - 2x + 8
$$

### 2. Lokale Extrempunkte
Wir bilden die Ableitung und setzen sie Null:
$$
A'(x) = -\frac{21}{16}x^2 + \frac{14}{4}x - 2 = 0
$$
Multiplikation mit $-16$:
$$
21x^2 - 56x + 32 = 0
$$
Mit der Mitternachtsformel ergeben sich:
* $x_1 = \frac{56 - \sqrt{56^2 - 4 \cdot 21 \cdot 32}}{2 \cdot 21} = \frac{56 - \sqrt{448}}{42} \approx 0,83$ (lokales Minimum)
* $x_2 = \frac{56 + \sqrt{448}}{42} \approx 1,83$ (lokales Maximum)

Der Funktionswert am lokalen Maximum:
$$
A(1,83) \approx (4 - 1,83) \cdot f(1,83) \approx 2,17 \cdot 3,46 \approx 7,51
$$

### 3. Randwertbetrachtung
Da wir ein globales Maximum im Intervall $[0, 4]$ suchen, müssen wir die Grenzen prüfen:

* **Rechter Rand ($x = 4$):**
$$
A(4) = (4 - 4) \cdot f(4) = 0
$$
(Das Rechteck hat die Breite 0).

* **Linker Rand ($x = 0$):**
$$
A(0) = (4 - 0) \cdot f(0) = 4 \cdot 2 = 8
$$

, highlighting that A(0)=8 is the highest point]

### 4. Endergebnis
Der Vergleich zeigt: $A(0) = 8$ ist größer als das lokale Maximum $A(1,83) \approx 7,51$.

Die Fläche des Rechtecks wird also maximal, wenn der Punkt $Q$ auf der y-Achse liegt:
* **Optimaler Punkt:** $Q(0 | 2)$
* **Maximaler Flächeninhalt:** $A_{max} = 8$

**Fazit:** Das "rechnerische" Maximum der Kurve ist hier nur ein relatives Maximum; das absolute Maximum liegt am Rand.
