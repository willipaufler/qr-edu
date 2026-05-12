# Gebrochen-rationale Kurvenschar - Lösung

### a) Definitionsbereich und Asymptoten
* **Definitionsbereich:** $x^2 - x = 0 \implies x(x-1) = 0$. Also $D_{f_a} = \mathbb{R} \setminus \{0; 1\}$.
* **Vertikale Asymptoten:** Da $a > 0$, sind $x = 0$ und $x = 1$ Polstellen.
* **Verhalten im Unendlichen:** $\lim_{x \to \pm \infty} \frac{2x^2 - a}{x^2 - x} = 2$.
* **Waagerechte Asymptote:** $y = 2$.

### b) Nachweis: Keine Extrema für $a \le 2$
**1. Ableitung:**
$u = 2x^2 - a \implies u' = 4x$
$v = x^2 - x \implies v' = 2x - 1$
$$
\begin{aligned}
f_a'(x) &= \frac{4x(x^2 - x) - (2x^2 - a)(2x - 1)}{(x^2 - x)^2} \\\\
&= \frac{4x^3 - 4x^2 - (4x^3 - 2x^2 - 2ax + a)}{(x^2 - x)^2}\\\\
&= \frac{-2x^2 + 2ax - a}{(x^2 - x)^2}
\end{aligned}
$$


Notwendige Bedingung $f_a'(x) = 0 \implies -2x^2 + 2ax - a = 0 \implies x^2 - ax + 0,5a = 0$.
**p-q-Formel:** $x_{1,2} = \frac{a\pm\sqrt{a^2-2a}}{2}$.

Falls $a<2$ so ist der Term unter der Wurzel negativ. Demnach sind $x_{1,2}$ nicht definiert und es gibt keine Extrempunkte.

Falls $a =2$, dann ist  $x_{1,2}=1$.  Es gibt eine doppelte Nullstelle und theoretisch einen Sattelpunkt, aber keine lokalen Extrema. Da aber $x=1$ nicht im Definitionsbereich von $f_a$ liegt. Gibt es diesen Sattelpunkt nicht. Es würde eine sogenannte hebbare Lücke entstehen.

### c) Extrempunkt auf $y = x$
Für $a > 2$ sind die Extremstellen: $x_{1,2} = \frac{a \pm \sqrt{a^2 - 2a}}{2}$.  
Die größere Koordinate ist 
$$
\begin{aligned}
x = \frac{a + \sqrt{a^2 - 2a}}{2}
\end{aligned}
$$

Damit dieser Punkt auf $y = x$ liegt, muss $f_a(x) = x$ gelten. 
Mittels CAS ergibt sich:
$$
\begin{aligned}
f_a\left(\frac{a + \sqrt{a^2 - 2a}}{2}\right) &= \frac{a + \sqrt{a^2 - 2a}}{2} \\\\
a&= 3,125 \implies x = 2,5
\end{aligned}
$$
Der y-Wert ist $f_{3,125}(2,5)=2,5$.

**Ergebnis:** $a = 3,125$ führt zu $x = 2,5$.
Der Extrempunkt ist $E(2,5 \mid 2,5)$.