# Flächenberechnung oHiMi II - Lösung

### Teilaufgabe a) Nachweis des Flächeninhalts
Gesucht ist $A = \int_{0}^{2} (-x^3 + 3x^2) \, dx$.

1.  **Stammfunktion bilden:**
    $F(x) = [-\frac{1}{4}x^4 + x^3]$
2.  **Grenzen einsetzen:**
    $A = \left( -\frac{1}{4} \cdot 2^4 + 2^3 \right) - (0)$
    $A = \left( -\frac{1}{4} \cdot 16 + 8 \right)$
    $A = -4 + 8 = 4$
**Ergebnis:** Der Flächeninhalt beträgt exakt 4 FE. ✔️

---

### Teilaufgabe b) Bestimmung der y-Koordinate $y_s$
Die Gerade $g$ geht durch $S(0|y_s)$ und $H(2|4)$.
* Steigung $m = \frac{4 - y_s}{2 - 0} = 2 - 0,5y_s$
* Gleichung: $g(x) = (2 - 0,5y_s)x + y_s$

**Flächenberechnung:**
Die Fläche zwischen $f$ und $g$ im Intervall $[0;2]$ soll 4 FE betragen. Da $f(x)$ im Punkt $H(2|4)$ endet und dort den Wert 4 hat, während $g(x)$ dort ebenfalls durchgeht, berechnen wir:
$$\int_{0}^{2} (g(x) - f(x)) \, dx = 4$$

Wir wissen bereits: $\int_{0}^{2} f(x) \, dx = 4$ (aus Aufg. a).
Also folgt:
$$\int_{0}^{2} g(x) \, dx - \int_{0}^{2} f(x) \, dx = 4$$
$$\int_{0}^{2} g(x) \, dx - 4 = 4 \implies \int_{0}^{2} g(x) \, dx = 8$$

Die Fläche unter der Geraden $g$ ist ein Trapez mit den parallelen Seiten $y_s$ und $4$ sowie der Breite $2$:
$$A_{\text{Trapez}} = \frac{y_s + 4}{2} \cdot 2 = 8$$
$$y_s + 4 = 8 \implies y_s = 4$$

**Alternative:** Wäre die Gerade unterhalb der Kurve, müsste man $f(x) - g(x)$ rechnen. Dies würde jedoch zu $y_s = -4$ führen (je nach Lage der Graphen). Da die Gerade durch $H(2|4)$ geht und die Fläche 4 FE betragen soll, ist $y_s = 4$ die Lösung (in diesem Fall ist $g(x)$ eine waagerechte Gerade).

**Ergebnis:** Die y-Koordinate des Schnittpunktes $S$ ist $y_s = 4$.