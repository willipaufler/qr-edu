# Gebrochen-rationale Funktion II - Lösung

### a) Asymptoten und Definitionsbereich
* **Definitionsbereich:** $5x - 5 = 0 \implies x = 1$. Also $D_f = \mathbb{R} \setminus \{1\}$.
* **Vertikale Asymptote:** Da $x=1$ eine Nullstelle des Nenners, aber nicht des Zählers ist, ist $x = 1$ eine Polstelle.
* **Schräge Asymptote (Polynomdivision):**
$(x^2 + 2x + 3) : (5x - 5) = 0,2x + 0,6 + \text{Rest}$  
Ausführen der Polynomdivision
$$
\begin{aligned}
&(x^2 + 2x + 3) : (5x - 5) = 0,2x +0,6 +\frac{6}{5x-5}\\\\
-&(x^2 - x) \quad \quad \quad  \\\\
&\overline{\quad \quad \quad 3x + 3} \quad  \\\\
& \quad \quad -( 3x - 3) \quad  \\\\
&\quad \quad \quad \overline{\quad  \quad \quad 6} 
\end{aligned}
$$





Somit ist $y = 0,2x + 0,6$ die schräge Asymptote.

### b) Extrempunkte
**1. Ableitung:**
$u = x^2 + 2x + 3 \implies u' = 2x + 2$
$v = 5x - 5 \implies v' = 5$
$$
\begin{aligned}
f'(x) &= \frac{(2x+2)(5x-5) - (x^2+2x+3) \cdot 5}{(5x-5)^2} \\\\
f'(x) &= \frac{10x^2 - 10x + 10x - 10 - 5x^2 - 10x - 15}{(5x-5)^2}\\\\
f'(x) &= \frac{5x^2 - 10x - 25}{(5x-5)^2}
\end{aligned}
$$

**Notwendige Bedingung $f'(x) = 0$:**
$x^2 - 2x - 5 = 0 \implies x_{1,2} = \frac{2 \pm \sqrt{4 - 4 \cdot (-5)}}{2} = \frac{2 \pm \sqrt{24}}{2} = 1 \pm \sqrt{6}$
$x_1 = 1 + \sqrt{6}; \quad x_2 = 1 - \sqrt{6}$

**2. Ableitung (Nachweis):**
An den Stellen $x_{1,2}$ gilt für den Zähler $u$ von $f'$ der Wert Null. Die Ableitung des Zählers ist $u'(x) = 2x - 2$.

* $f''(1+\sqrt{6}) = \frac{2\sqrt{6} \cdot 30}{pos.} > 0 \implies \mathbf{Tiefpunkt}$
* $f''(1-\sqrt{6}) = \frac{-2\sqrt{6} \cdot 30}{pos.} < 0 \implies \mathbf{Hochpunkt}$

**Y-Koordinaten (Exakt):**
Wir nutzen $f(x) = 0,2x + 0,6 + \frac{6}{5x-5}$:

* $f(1+\sqrt{6}) = 0,8 + 0,4\sqrt{6} \approx 1,7798$$
* $f(1-\sqrt{6}) = 0,8 - 0,4\sqrt{6} \approx -0,1798$


**Ergebnis:** $T(1+\sqrt{6} \mid 0,8+0,4\sqrt{6})$ und $H(1-\sqrt{6} \mid 0,8-0,4\sqrt{6})$.


### c) Schnittwinkel mit der y-Achse
1. **Schnittpunkt:** $f(0) = \frac{3}{-5} = -0,6 \implies S_y(0 | -0,6)$.
2. **Steigung bei $x=0$:**
$f'(0) = \frac{5(0)^2 - 10(0) - 25}{(5 \cdot 0 - 5)^2}  = -1$.
3. **Winkel:**
$\tan(\alpha) = -1 \implies \alpha = -45^\circ$.  
Der Graph schneidet die x-Achse im $45^\circ$-Winkel.  
Winkel zur y-Achse: $\beta = 90^\circ - 45^\circ = 45^\circ$.