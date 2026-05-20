# Olympiaschanze - Lösung

### a) Bestimmen des Punktes $P$ mit größtem Gefälle und der Steigung
Ableitungen der Profilfunktion:
$$\begin{aligned}
h'(x) &= 1,731 \cdot 10^{-4}x^2 - 2,54 \cdot 10^{-2}x \\\\
h''(x) &= 3,462 \cdot 10^{-4}x - 2,54 \cdot 10^{-2}
\end{aligned}
$$
Notwendige Bedingung für den Wendepunkt $h''(x) = 0$:
$$\begin{aligned}
3,462 \cdot 10^{-4}x - 2,54 \cdot 10^{-2} &= 0 \\\\
3,462 \cdot 10^{-4}x &= 0,0254 \\\\
x_w &\approx 73,37
\end{aligned}
$$
Punktkoordinaten (Einsetzen in $h(x)$):
$h(73,37) \approx 45,34 \implies P(73,37|45,34)$.

Steigung in Prozent:
$h'(73,37) \approx -0,9317$
Das Gefälle beträgt an dieser Stelle ca. $93,17\%$.

### b) Berechnung der Entfernung von der Grundkante zur Hillsize
1. Horizontale Entfernung $x_H$ bestimmen ($h'(x) = \tan(-32^\circ) \approx -0,6249$):
$$\begin{aligned}
-0,6249 &= 1,731 \cdot 10^{-4}x^2 - 0,0254x \\\\
0 &= 1,731 \cdot 10^{-4}x^2 - 0,0254x + 0,6249 \\\\
x_H &\approx 115,48
\end{aligned}
$$
2. Koordinaten des Landepunktes $H$:
$h(115,48) \approx 10,26 \implies H(115,48|10,26)$.

3. Direkte Entfernung von der Grundkante $S(0|90,7)$ zu $H(115,48|10,26)$:
$$
\begin{aligned}
s_H &= \sqrt{(x_H - 0)^2 + (h(x_H) - 90,7)^2} \\\\
s_H &= \sqrt{115,48^2 + (10,26 - 90,7)^2} \\\\
s_H &\approx 140,73
\end{aligned}
$$
Ergebnis: Die direkte Entfernung von der Grundkante beträgt ca. $140,73\,\text{m}$.

### c) Entscheidung und Verfeinerung des Verfahrens
**Entscheidung:**
Die tatsächliche Hillsize entlang des Hangprofils ist **größer** als die in b) berechnete Entfernung. Die direkte Verbindung (Sehne) ist geometrisch immer der kürzeste Weg; jede Kurve, die von dieser Geraden abweicht, ist länger.

**Verfeinerung des Verfahrens:**
Um sich dem exakten Wert der Kurvenlänge anzunähern, verwendet man eine Summe aus vielen kleinen Sehnenabschnitten:

1. Unterteilung des Intervalls $[0; 115,48]$ in $n$ Teilintervalle (z. B. Zentimeter-Schritte).
2. Berechnung der Teil-Längen $s_i$ zwischen den Punkten $P_i$ und $P_{i+1}$ auf dem Graphen:
$$
\begin{aligned}
s_i &= \sqrt{(x_{i+1}-x_i)^2 + (h(x_{i+1})-h(x_i))^2}
\end{aligned}
$$
3. Die Summe aller $s_i$ ergibt die Länge des Hangprofils. Je kleiner die Intervalle gewählt werden, desto präziser nähert sich dieses „Sehnenpolygon“ der tatsächlichen Länge der Schanze an.