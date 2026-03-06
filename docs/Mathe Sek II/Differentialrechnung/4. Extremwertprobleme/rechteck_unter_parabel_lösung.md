# Rechteck unter der Parabel - Lösung

### a) Maximaler Umfang
**1. Zielfunktion aufstellen:**
$$
U(x) = 2 \cdot (2x) + 2 \cdot (6 - x^2) = 4x + 12 - 2x^2 = -2x^2 + 4x + 12
$$

**2. Extremwert berechnen:**
Wir bilden die erste Ableitung und setzen sie null:
$$
U'(x) = -4x + 4
$$
$$
-4x + 4 = 0 \implies 4x = 4 \implies x = 1
$$

**3. Überprüfung (Art des Extremums):**
$$
U''(x) = -4
$$
Da $U''(1) = -4 < 0$ ist, liegt an der Stelle $x = 1$ ein lokales Maximum vor.

**4. Abmessungen berechnen:**

* Breite: $b = 2x = 2 \cdot 1 = \mathbf{2}$
* Höhe: $h = 6 - 1^2 = \mathbf{5}$
* Maximaler Umfang: $U(1) = 2 \cdot 2 + 2 \cdot 5 = \mathbf{14}$

---

### b) Maximaler Flächeninhalt



**1. Zielfunktion aufstellen:**
$$
A(x) = (2x) \cdot (6 - x^2) = 12x - 2x^3
$$

**2. Extremwert berechnen:**
Erste Ableitung null setzen:
$$
A'(x) = 12 - 6x^2
$$
$$
12 - 6x^2 = 0 \implies 6x^2 = 12 \implies x^2 = 2 \implies x = \sqrt{2} \approx 1,41
$$

**3. Überprüfung (Art des Extremums):**
$$
A''(x) = -12x
$$
$$
A''(\sqrt{2}) = -12\sqrt{2} < 0 \implies \text{lokales Maximum}
$$

**4. Abmessungen berechnen:**

* Breite: $b = 2 \cdot \sqrt{2} = \mathbf{2\sqrt{2}} \approx \mathbf{2,83}$
* Höhe: $h = 6 - (\sqrt{2})^2 = 6 - 2 = \mathbf{4}$
* Maximaler Flächeninhalt: $A(\sqrt{2}) = 2\sqrt{2} \cdot 4 = \mathbf{8\sqrt{2}} \approx \mathbf{11,31}$

**5. Randwertbetrachtung:**
An den Rändern des Intervalls $[0; \sqrt{6}]$ gilt:

* $A(0) = 0$
* $A(\sqrt{6}) = 0$
Das berechnete Maximum bei $x = \sqrt{2}$ ist somit das absolute Maximum.