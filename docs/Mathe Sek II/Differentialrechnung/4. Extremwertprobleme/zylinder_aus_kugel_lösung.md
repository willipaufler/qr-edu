# Zylinder in der Kugel - Lösung

### 1. Aufstellen der Gleichungen
**Nebenbedingung (Satz des Pythagoras):**
Im Schnitt durch die Kugel gilt für den Zusammenhang zwischen Kugelradius $R$, Zylinderradius $r$ und Zylinderhöhe $h$:
$$
r^2 + \left(\frac{h}{2}\right)^2 = R^2 \implies r^2 = R^2 - \frac{h^2}{4}
$$
Mit $R = 10\,\rm cm$ folgt:
$$
r^2 = 100 - \frac{h^2}{4}
$$

**Zielfunktion (Volumen):**
$$
V(h) = \pi \cdot r^2 \cdot h = \pi \cdot \left(100 - \frac{h^2}{4}\right) \cdot h
$$
$$
V(h) = \pi \cdot \left(100h - \frac{1}{4}h^3\right)
$$

### 2. Bestimmung des Maximums
Erste Ableitung bilden:
$$
V'(h) = \pi \cdot \left(100 - \frac{3}{4}h^2\right)
$$
Notwendige Bedingung $V'(h) = 0$:
$$
100 - \frac{3}{4}h^2 = 0 \implies \frac{3}{4}h^2 = 100 \implies h^2 = \frac{400}{3}
$$
$$
h = \sqrt{\frac{400}{3}} = \frac{20}{\sqrt{3}} \approx 11,55\,\rm cm
$$

### 3. Berechnung der restlichen Maße
**Radius $r$:**
$$
r^2 = 100 - \frac{\frac{400}{3}}{4} = 100 - \frac{100}{3} = \frac{200}{3}
$$
$$
r = \sqrt{\frac{200}{3}} \approx 8,16\,\rm cm
$$

**Maximales Volumen $V$:**
$$
V_{max} = \pi \cdot \frac{200}{3} \cdot \frac{20}{\sqrt{3}} \approx 2418,40\,\rm cm^3
$$

### 4. Ergebnis
Der Zylinder mit dem größten Volumen hat eine Höhe von ca. **$11,55\,\rm cm$** und einen Radius von ca. **$8,16\,\rm cm$**. Das maximale Volumen beträgt etwa **$2418,40\,\rm cm^3$**.

*Hinweis: Allgemein gilt für dieses Problem immer $h = \frac{2R}{\sqrt{3}}$.*
