# Dreieck unter Tangente - Lösung

### a) Bestimmen des Intervalls für $x_0$

Die Funktion lautet $f(x) = (x - 1)^2 = x^2 - 2x + 1$. Ihre Ableitung ist $f'(x) = 2(x - 1) = 2x - 2$.

Die Tangentengleichung im Punkt $P(x_0 \mid f(x_0))$ wird aufgestellt:
$$
\begin{aligned} 
t(x) &= f'(x_0) \cdot (x - x_0) + f(x_0) \\\\ 
t(x) &= 2(x_0 - 1) \cdot (x - x_0) + (x_0 - 1)^2 \\\\ 
t(x) &= 2(x_0 - 1)x - 2x_0(x_0 - 1) + (x_0 - 1)^2 \\\\ 
t(x) &= 2(x_0 - 1)x - 2x_0^2 + 2x_0 + x_0^2 - 2x_0 + 1 \\\\ 
t(x) &= 2(x_0 - 1)x - x_0^2 + 1 
\end{aligned}
$$

Damit die Tangente mit den Koordinatenachsen ein Dreieck im ersten Quadranten bildet, müssen sowohl der $y$-Achsenabschnitt als auch die Nullstelle positiv sein.

* **$y$-Achsenabschnitt ($x=0$):**
$$
\begin{aligned} 
y_0 = t(0) &= -x_0^2 + 1 \\\\ 
-x_0^2 + 1 &> 0 \implies x_0^2 < 1 \implies -1 < x_0 < 1 
\end{aligned}
$$

* **Nullstelle ($t(x)=0$):**
$$
\begin{aligned} 
2(x_0 - 1)x - x_0^2 + 1 &= 0 \\\\ 
2(x_0 - 1)x &= x_0^2 - 1 \\\\ 
2(x_0 - 1)x &= (x_0 - 1)(x_0 + 1) 
\end{aligned}
$$

Für $x_0 \neq 1$ darf durch $(x_0 - 1)$ geteilt werden:
$$
\begin{aligned} 
2x &= x_0 + 1 \\\\ x_N &= \frac{x_0 + 1}{2} 
\end{aligned}
$$

Damit die Nullstelle $x_N > 0$ ist, muss gilt:
$$
\begin{aligned} \frac{x_0 + 1}{2} &> 0 \\\\ 
x_0 + 1 &> 0 \implies x_0 > -1 
\end{aligned}
$$

Da das Dreieck im ersten Quadranten liegen soll, betrachten wir nur positive Stellen für die Berührung bzw. den Verlauf. Aus $y_0 > 0$ folgt $x_0 < 1$. Da für $x_0 < 0$ die Tangente eine positive Steigung hätte und die $x$-Achse im negativen Bereich schneiden würde, muss $x_0$ im Interval $x_0 \in [0; 1)$ liegen.

Das gesuchte Intervall lautet somit $x_0 \in [0; 1)$.

### b) Berechnen des Punktes $P$ für maximalen Flächeninhalt

**1. Aufstellen der Zielfunktion:**
Das rechtwinklige Dreieck hat die Grundseite $x_N = \frac{x_0 + 1}{2}$ and die Höhe $y_0 = 1 - x_0^2$.
Die Zielfunktion für den Flächeninhalt lautet:
$$
\begin{aligned} 
A(x_0) &= \frac{1}{2} \cdot x_N \cdot y_0 \\\\ 
A(x_0) &= \frac{1}{2} \cdot \frac{x_0 + 1}{2} \cdot (1 - x_0^2) \\\\ 
A(x_0) &= \frac{1}{4} (x_0 + 1)(1 - x_0^2) \\\\ 
A(x_0) &= \frac{1}{4} (x_0 - x_0^3 + 1 - x_0^2) \\\\ 
A(x_0) &= -\frac{1}{4}x_0^3 - \frac{1}{4}x_0^2 + \frac{1}{4}x_0 + \frac{1}{4} 
\end{aligned}
$$

**2. Bestimmung des Maximums:**
Wir bilden die Ableitungen nach $x_0$:
$$
\begin{aligned}
A'(x_0) &= -\frac{3}{4}x_0^2 - \frac{1}{2}x_0 + \frac{1}{4}\\\\
A''(x_0) &= -\frac{3}{2}x_0 - \frac{1}{2}
\end{aligned}
$$

Notwendige Bedingung $A'(x_0) = 0$:
$$
\begin{aligned} -\frac{3}{4}x_0^2 - \frac{1}{2}x_0 + \frac{1}{4} &= 0 \\\\ x_0^2 + \frac{2}{3}x_0 - \frac{1}{3} &= 0 
\end{aligned}
$$

Anwendung der p-q-Formel:
$$
\begin{aligned} 
x_0 &= -\frac{1}{3} \pm \sqrt{\left(\frac{1}{3}\right)^2 - \left(-\frac{1}{3}\right)}  \\\\ x_0 &= -\frac{1}{3} \pm \sqrt{\frac{4}{9}} \\\\ x_0 &= -\frac{1}{3} \pm \frac{2}{3} 
\end{aligned}
$$

Dies liefert die zwei Lösungen:
$x_{0,1} = \frac{1}{3}$ und $x_{0,2} = -1$

Da $x_{0,2} = -1$ nicht im zulässigen Intervall $[0; 1)$ liegt, untersuchen wir nur $x_{0,1} = \frac{1}{3}$ mit der hinreichenden Bedingung:
$A''\left(\frac{1}{3}\right) = -\frac{3}{2} \cdot \frac{1}{3} - \frac{1}{2} = -\frac{1}{2} - \frac{1}{2} = -1 < 0 \implies$ Es handelt sich um ein lokales Maximum.

**3. Bestimmung des Punktes $P$:**  
Der $y$-Wert des Kurvenpunktes berechnet sich durch Einsetzen in $f(x)$:
$f\left(\frac{1}{3}\right) = \left(\frac{1}{3} - 1\right)^2 = \frac{4}{9}$

Der gesuchte Punkt lautet somit $P\left(\frac{1}{3} \mid \frac{4}{9}\right)$.