# Flächenberechnung oHiMi - Tipp

Hier sind hilfreiche Strategien, um die Aufgabe ohne Taschenrechner zu lösen:

---

### Zu Teilaufgabe a) (Tangentennachweis)
Eine Gerade $g(x)$ ist genau dann eine Tangente an $f(x)$ im Punkt $P(x_0|y_0)$, wenn zwei Bedingungen erfüllt sind:
1.  **Gemeinsamer Punkt:** Der Punkt muss auf beiden Graphen liegen ($f(x_0) = g(x_0) = y_0$).
2.  **Gleiche Steigung:** Die Ableitung der Funktion an dieser Stelle muss der Steigung der Geraden entsprechen ($f'(x_0) = m_g$).

### Zu Teilaufgabe b) (Flächeninhalt)
Um die Fläche zwischen zwei Graphen $f$ und $g$ sowie der $y$-Achse zu berechnen, gehst du so vor:
1.  **Grenzen bestimmen:** Die linke Grenze ist die $y$-Achse ($x = 0$). Die rechte Grenze ist der Schnittpunkt/Berührpunkt der beiden Graphen (aus Aufg. a bekannt: $x = 2$).
2.  **Oben minus Unten:** Überlege (oder skizziere kurz), welcher Graph im Intervervall $[0; 2]$ höher liegt. Die Fläche berechnet sich durch:
    $$A = \int_{x_1}^{x_2} (\text{obere Funktion} - \text{untere Funktion}) \, dx$$
3.  **Stammfunktion bilden:** Integriere den Differenzterm $(\dots - \dots)$ sorgfältig.