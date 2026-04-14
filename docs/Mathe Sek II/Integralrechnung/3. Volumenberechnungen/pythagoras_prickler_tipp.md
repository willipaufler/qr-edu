# Pythagoras-Prickler - Tipp

### Aufgabe a) Die Stiellänge berechnen
Um zu zeigen, dass der Stiel etwa $10\text{ cm}$ lang ist, musst du die Tiefe des Kegels berechnen.

1.  **Volumen-Formel:** Nutze die Formel für das Volumen eines Kegels: $V = \frac{1}{3} \pi r^2 h$.
2.  **Radius bestimmen:** Der maximale Durchmesser beträgt $11,4\text{ cm}$. Wie groß ist der Radius $r$?
3.  **Kegelhöhe isolieren:** Stelle die Formel nach $h$ um und setze $V = 270\text{ cm}^3$ sowie deinen Radius ein.
4.  **Differenz:** Ziehe die berechnete Kegelhöhe von der Gesamthöhe ($18\text{ cm}$) ab.

---

### Aufgabe b) Vorhandene Flüssigkeitsmenge
Beachte für beide Optionen: $5\text{ cl} = 50\text{ ml} = 50\text{ cm}^3$.

**Option 1: Integralrechnung (Rotationsvolumen)**
* **Funktion aufstellen:** Modelliere die Glaswand als Ursprungsgerade $f(x) = m \cdot x$. Die Steigung $m$ ist das Verhältnis von Radius zu Kegelhöhe ($m = \frac{r}{h_k}$).
* **Ansatz:** Die Differenz der Volumina zwischen der unbekannten alten Höhe $h_1$ und der neuen Höhe $h_1 + 1$ muss exakt $50\text{ cm}^3$ ergeben:
    $$\pi \cdot \int_{0}^{h_1 + 1} (m \cdot x)^2 \, dx - \pi \cdot \int_{0}^{h_1} (m \cdot x)^2 \, dx = 50$$

**Option 2: Ähnlichkeit (Strahlensatz)**
* **Volumenverhältnis:** Es gilt der Zusammenhang $V(h) = c \cdot h^3$.
* **Konstante bestimmen:** Berechne $c$ mit den Werten aus Teil a), indem du $c = \frac{V_{max}}{h_k^3}$ rechnest.
* **Gleichung:** Löse die Gleichung $c \cdot (h_1 + 1)^3 - c \cdot h_1^3 = 50$ nach $h_1$ auf.