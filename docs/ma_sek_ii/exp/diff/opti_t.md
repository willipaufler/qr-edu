# Optimierungsaufgabe - Tipp

### Skizze und Rechteckseiten
- Zeichne dir den Graphen von $f(x) = e^{0{,}25x} - 1$ und den Punkt $Q(6 \mid 0)$ in ein Koordinatensystem ein.
- Da $P(a \mid f(a))$ und $Q(6 \mid 0)$ gegenüberliegende Eckpunkte eines achsenparallelen Rechtecks sind, bestimmen sich die Seitenlängen des Rechtecks aus den Differenzen der Koordinaten:
  - Die Länge des Rechtecks in $x$-Richtung beträgt $(6 - a)$.
  - Die Höhe des Rechtecks in $y$-Richtung beträgt $f(a)$ (da der Punkt $Q$ auf der $x$-Achse bei $y = 0$ liegt).

---

### Zielfunktion aufstellen
- Stelle die allgemeine Formel für den Umfang $U$ eines Rechtecks auf:
  $$
  U = 2 \cdot (\text{Länge} + \text{Breite})
  $$
- Ersetze Länge und Breite durch die Terme in Abhängigkeit von $a$:
  $$
  U(a) = 2 \cdot ((6 - a) + f(a))
  $$
- Setze den Funktionsterm $f(a) = e^{0{,}25a} - 1$ ein und vereinfache die Zielfunktion.

---

### Extremwert bestimmen
- Bestimme die 1. Ableitung $U'(a)$ der Zielfunktion.
- Setze $U'(a) = 0$, um den Kandidaten für das Minimum zu finden.
- Nutze den natürlichen Logarithmus ($\ln$), um die Gleichung nach $a$ aufzulösen.
- Prüfe mit der 2. Ableitung $U''(a)$, ob tatsächlich ein Minimum vorliegt (und beachte das Intervall $0 < a < 6$). Zum Schluss berechnest du die y-Koordinate von $P$.