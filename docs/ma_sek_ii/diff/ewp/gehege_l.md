# Hasengehege im Garten - Lösung

### a) Bestimmen der Maße für minimale Gesamtkosten

**1. Aufstellen der Bedingungen:**
Wir definieren die Gesamtlänge des rechteckigen Geheges als $x$ und die Breite (an der auch die Zwischenwand anliegt) als $y$ (mit $x, y > 0$).

Die Kosten setzen sich wie folgt zusammen:

* Zwei Außenwände der Länge $x$ zu je $4\text{ €/m}$: $2 \cdot 4 \cdot x = 8x$
* Zwei Außenwände der Länge $y$ zu je $4\text{ €/m}$: $2 \cdot 4 \cdot y = 8y$
* Eine Zwischenwand der Länge $y$ zu $2\text{ €/m}$: $1 \cdot 2 \cdot y = 2y$

Hauptbedingung (Kostenfunktion):
$K(x, y) = 8x + 8y + 2y = 8x + 10y$

Nebenbedingung (Flächeninhalt):
$$
\begin{aligned} 
x \cdot y &= 20 \\\\ 
y &= \frac{20}{x} 
\end{aligned}
$$

**2. Aufstellen der Zielfunktion:**
Setzt man die Nebenbedingung in die Hauptbedingung ein, erhält man die Zielfunktion $K(x)$:
$$
\begin{aligned} 
K(x) &= 8x + 10 \cdot \frac{20}{x} \\\\ 
K(x) &= 8x + \frac{200}{x} 
\end{aligned}
$$

**3. Bestimmung des Minimums:**
Wir bilden die ersten beiden Ableitungen der Zielfunktion nach $x$:
$K'(x) = 8 - \frac{200}{x^2}$
$K''(x) = \frac{400}{x^3}$

Notwendige Bedingung für ein Extremum ist $K'(x) = 0$:
$$
\begin{aligned} 
8 - \frac{200}{x^2} &= 0 \\\\ 
x^2 &= 25 
\end{aligned}
$$

Da eine Länge positiv sein muss ($x > 0$), folgt:
$x = 5$

Hinreichende Bedingung prüfen:
$K''(5) = \frac{400}{5^3} = \frac{400}{125} = \frac{16}{5} > 0 \implies$ Es handelt sich um ein lokales Minimum.

**4. Berechnung der gesuchten Maße und Kosten:**
Die optimale Gesamtlänge beträgt $x = 5\text{ m}$.
Die dazugehörige Breite $y$ berechnet sich durch die Nebenbedingung:
$y = \frac{20}{5} = 4$

Die minimale Gesamtkosten betragen:
$K(5) = 8 \cdot 5 + \frac{200}{5} = 40 + 40 = 80$

Das Gehege muss eine Gesamtlänge von $5\text{ m}$ und eine Breite von $4\text{ m}$ besitzen (wobei die Zwischenwand $4\text{ m}$ lang ist). Die minimalen Kosten belaufen sich auf $80\text{ €}$.