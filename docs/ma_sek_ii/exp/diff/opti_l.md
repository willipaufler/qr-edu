# Optimierungsaufgabe - Lösung

Gegeben ist die Funktion $f$ mit $f(x) = e^{0{,}25x} - 1$ und der Punkt $Q(6 \mid 0)$.

---

### Zielfunktion für den Umfang aufstellen

Die Eckpunkte des Rechtecks sind $P(a \mid f(a))$ und $Q(6 \mid 0)$. Da die Seiten parallel zu den Koordinatenachsen verlaufen, ergeben sich die Seitenlängen zu:
- Breite (in $x$-Richtung): $6 - a$
- Höhe (in $y$-Richtung): $f(a) = e^{0{,}25a} - 1$

Für den Umfang $U$ eines Rechtecks gilt $U = 2 \cdot (\text{Breite} + \text{Höhe})$. Einsetzen liefert die Zielfunktion in Abhängigkeit von $a$:
$$
\begin{aligned}
U(a) &= 2 \cdot \left((6 - a) + e^{0{,}25a} - 1\right) \\\\
&= 2 \cdot \left(5 - a + e^{0{,}25a}\right) \\\\
&= 10 - 2a + 2e^{0{,}25a}
\end{aligned}
$$

---

### Notwendige Bedingung für Extremwerte ($U'(a) = 0$)

Wir bilden die erste Ableitung der Zielfunktion (unter Anwendung der Kettenregel):
$$
\begin{aligned}
U'(a) &= -2 + 2 \cdot 0{,}25 e^{0{,}25a} \\\\
&= -2 + 0{,}5 e^{0{,}25a}
\end{aligned}
$$

Setzen der Ableitung gleich Null:
$$
\begin{aligned}
-2 + 0{,}5 e^{0{,}25a} &= 0 \\\\
0{,}5 e^{0{,}25a} &= 2 \\\\
e^{0{,}25a} &= 4
\end{aligned}
$$

Anwenden des natürlichen Logarithmus ($\ln$) auf beiden Seiten:
$$
\begin{aligned}
0{,}25a &= \ln(4) \\\\
a &= \frac{\ln(4)}{0{,}25} = 4 \cdot \ln(4)
\end{aligned}
$$

Berechnung des numerischen Wertes zur Kontrolle des Intervalls $0 < a < 6$:
$$
\begin{aligned}
a = 4 \cdot \ln(4) \approx 4 \cdot 1{,}3863 = 5{,}545 \quad (\text{liegt im Intervall } ]0; 6[)
\end{aligned}
$$

---

### Hinreichende Bedingung und Art des Extremums

Wir bilden die zweite Ableitung $U''(a)$:
$$
\begin{aligned}
U''(a) &= 0{,}5 \cdot 0{,}25 e^{0{,}25a} \\\\
&= 0{,}125 e^{0{,}25a}
\end{aligned}
$$

Einsetzen des gefundenen Wertes $a = 4\ln(4)$:
$$
\begin{aligned}
U''(4\ln(4)) &= 0{,}125 e^{0{,}25 \cdot 4\ln(4)} \\\\
&= 0{,}125 e^{\ln(4)} \\\\
&= 0{,}125 \cdot 4 = 0{,}5 > 0
\end{aligned}
$$

Da $U''(4\ln(4)) > 0$ gilt, liegt an dieser Stelle ein **Minimum** des Umfangs vor.

---

### Koordinaten des Punktes $P$ bestimmen

Die $x$-Koordinate ist $a = 4\ln(4)$. Nun berechnen wir die $y$-Koordinate $f(a)$:
$$
\begin{aligned}
f(4\ln(4)) &= e^{0{,}25 \cdot 4\ln(4)} - 1 \\\\
&= e^{\ln(4)} - 1 \\\\
&= 4 - 1 \\\\
&= 3
\end{aligned}
$$

Der gesuchte Punkt ist somit **$P(4\ln(4) \mid 3)$** (bzw. dezimal ca. $P(5{,}55 \mid 3)$).