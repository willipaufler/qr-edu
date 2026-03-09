# Flächen zwischen zwei Funktionsgraphen - Lösung

### Teilaufgabe a) Flächeninhalt
1. **Schnittpunkte:** $\frac{1}{2}x^2 = -\frac{1}{4}x^2 + \frac{3}{4}x + \frac{3}{2} \implies \frac{3}{4}x^2 - \frac{3}{4}x - \frac{3}{2} = 0 \implies x^2 - x - 2 = 0$.
   Schnittstellen: $x_1 = -1, x_2 = 2$.
2. **Differenzfunktion:** $h(x) = g(x) - f(x) = -\frac{3}{4}x^2 + \frac{3}{4}x + \frac{3}{2}$.
3. **Integral:** 

\begin{align*}
A &= \int_{-1}^{2} (-\frac{3}{4}x^2 + \frac{3}{4}x + \frac{3}{2}) \, dx\\ 
&= [-\frac{1}{4}x^3 + \frac{3}{8}x^2 + \frac{3}{2}x]_{-1}^{2}\\
&= (-2 + 1,5 + 3) - (0,25 + 0,375 - 1,5)\\
&= 2,5 - (-0,875) = 3,375 = \frac{27}{8} FE.
\end{align*} 

---

### Teilaufgabe b) Teilungsverhältnis
Aus den **Schnittpunkten** von $f$ und $g$, nämlich $P_1(-1 | 0,5)$ und $P_2(2 | 2)$ lässt sich die **Steigung der Geraden** bestimmen

$$m = \frac{2 - 0,5}{2 - (-1)} = \frac{1,5}{3} = 0,5.$$

Mithilfe der Punktanstiegsform ergibt sich die Geradengleichung: 

$$s(x) = 0,5x + 1.$$

Die **Fläche zwischen der Parabel $g$ und über der Geraden $s$** ist

$$A_{oben} = \int_{-1}^{2} (g(x) - s(x)) \, dx.$$

Da beide Funktionen (Parabel $g$ und Gerade $s$) die gleichen Schnittpunkte haben, entsteht hier ein Segment.
   Rechnung: $A_{oben} = \dots = 1,125$ FE.  
Die **Restfläche:** ist:

$$A_{unten} = 3,375 - 1,125 = 2,25 FE.$$

Daher ist das **Teilungsverhältnis**:

$$\frac{A_{oben}}{A_{unten}} = \frac{1,125}{2,25} = 1 : 2.$$


---

### Teilaufgabe c) Ursprungsgerade (CAS)
Eine Ursprungsgerade kann durch die Funktiono $u$ mit $u(x) = m \cdot x$ beschrieben werden.


* **Schnittpunkt mit $f$:** $u(x) = f(x) \rightarrow$ relevanter Schnittpunkt $S(0|0)$
* **Schnittpunkt mit $g$:** $u(x) = g(x) \rightarrow$

$$x_{\pm} = -2m + \frac{3 \pm \sqrt{16m^2 - 24m + 33}}{2}$$

Anhand einer Skizze macht man sich klar, dass die Stelle mit dem größeren x-Wert relevant für die Aufgabe ist. $\rightarrow x_+$

Weiterhin muss $u$ monoton wachsend sein. Zur Absicherung kann man sich vergewissern, dass bei Teilung der Fläche mit der Geraden $x = 0$, die Teilfläche auf der positiven x-Achse größer ist.

---

#### Ansatz:
$$\frac{A}{2} = \int_{-1}^{0} (g(x) - f(x)) \, dx + \int_{0}^{x_+} (g(x) - u(x)) \, dx$$

**liefert:** $m = 1,959$

---

### Teilaufgabe d) Verhundertfachung
Damit die Fläche bei Formbehalt verhundertfacht wird, nutzen wir den Streckfaktor $k = \sqrt{100} = 10$.
Regel: $f_{neu}(x) = k \cdot f(\frac{x}{k})$.

1. **Für $f(x)$:** $f_1(x) = 10 \cdot \frac{1}{2}(\frac{x}{10})^2 = 10 \cdot \frac{1}{2} \cdot \frac{x^2}{100} = \frac{1}{20}x^2$.
2. **Für $g(x)$:** $g_1(x) = 10 \cdot (-\frac{1}{4}(\frac{x}{10})^2 + \frac{3}{4}(\frac{x}{10}) + \frac{3}{2}) = -\frac{1}{40}x^2 + \frac{3}{4}x + 15$.

**Ergebnis:** Die neuen Funktionen sind $f_1(x) = 0,05x^2$ und $g_1(x) = -0,025x^2 + 0,75x + 15$.