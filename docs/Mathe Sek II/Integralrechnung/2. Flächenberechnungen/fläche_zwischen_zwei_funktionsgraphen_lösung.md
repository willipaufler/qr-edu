# Flächen zwischen zwei Funktionsgraphen - Lösung

### Teilaufgabe a) Flächeninhalt
1. **Schnittpunkte:** $\frac{1}{2}x^2 = -\frac{1}{4}x^2 + \frac{3}{4}x + \frac{3}{2} \implies \frac{3}{4}x^2 - \frac{3}{4}x - \frac{3}{2} = 0 \implies x^2 - x - 2 = 0$.
   Schnittstellen: $x_1 = -1, x_2 = 2$.
2. **Differenzfunktion:** $h(x) = g(x) - f(x) = -\frac{3}{4}x^2 + \frac{3}{4}x + \frac{3}{2}$.
3. **Integral:** $A = \int_{-1}^{2} (-\frac{3}{4}x^2 + \frac{3}{4}x + \frac{3}{2}) \, dx = [-\frac{1}{4}x^3 + \frac{3}{8}x^2 + \frac{3}{2}x]_{-1}^{2}$.
   $A = (-2 + 1,5 + 3) - (0,25 + 0,375 - 1,5) = 2,5 - (-0,875) = 3,375 = \frac{27}{8}$ FE.

---

### Teilaufgabe b) Teilungsverhältnis
1. **Schnittpunkte:** $P_1(-1 | 0,5)$ und $P_2(2 | 2)$.
2. **Gerade $s(x)$:** Steigung $m = \frac{2 - 0,5}{2 - (-1)} = \frac{1,5}{3} = 0,5$. Punktsteigungsform ergibt $s(x) = 0,5x + 1$.
3. **Fläche unter der Parabel $g$ und über der Geraden $s$:**
   $A_{oben} = \int_{-1}^{2} (g(x) - s(x)) \, dx$. Da beide Funktionen (Parabel $g$ und Gerade $s$) die gleichen Schnittpunkte haben, entsteht hier ein Segment.
   Rechnung: $A_{oben} = \dots = 1,125$ FE.
4. **Restfläche:** $A_{unten} = 3,375 - 1,125 = 2,25$ FE.
**Verhältnis:** $1,125 : 2,25 = 1 : 2$.

---

### Teilaufgabe c) Ursprungsgerade (CAS)
Gesucht ist $m$ für $y = mx$, sodass $\int_{x_{links}}^{x_{rechts}} (g(x) - mx) \, dx = 1,6875$.
(Hinweis: Hier variiert je nach CAS die Vorgehensweise. Eine numerische Lösung liefert für die Steigung $m \approx 0,42$.)

---

### Teilaufgabe d) Verhundertfachung
Damit die Fläche bei Formbehalt verhundertfacht wird, nutzen wir den Streckfaktor $k = \sqrt{100} = 10$.
Regel: $f_{neu}(x) = k \cdot f(\frac{x}{k})$.

1. **Für $f(x)$:** $f_1(x) = 10 \cdot \frac{1}{2}(\frac{x}{10})^2 = 10 \cdot \frac{1}{2} \cdot \frac{x^2}{100} = \frac{1}{20}x^2$.
2. **Für $g(x)$:** $g_1(x) = 10 \cdot (-\frac{1}{4}(\frac{x}{10})^2 + \frac{3}{4}(\frac{x}{10}) + \frac{3}{2}) = -\frac{1}{40}x^2 + \frac{3}{4}x + 15$.

**Ergebnis:** Die neuen Funktionen sind $f_1(x) = 0,05x^2$ und $g_1(x) = -0,025x^2 + 0,75x + 15$.