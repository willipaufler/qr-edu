# Bremsvorgang - Lösung

### Lösung zu a) Bestimmung des Haltezeitpunktes
Um den Zeitpunkt des Stillstands zu finden, suchen wir die Nullstelle der Geschwindigkeitsfunktion $v(t)$.
$$
\begin{aligned}
v(t) &= 0 \\\\
30 - 1,2t^2 &= 0 \quad | -30 \\\\
-1,2t^2 &= -30 \quad | :(-1,2) \\\\
t^2 &= 25 \quad | \sqrt{\dots} \\\\
t &= 5 \quad (t = -5 \text{ entfällt im Sachzusammenhang})
\end{aligned}
$$

**Ergebnis:** Das Fahrzeug kommt nach **5 Sekunden** zum Stillstand.

---

### Lösung zu b) Berechnung des Bremsweges
Der zurückgelegte Weg $s$ entspricht dem Integral der Geschwindigkeit über der Zeit im Intervall $[0; 5]$.
$$
\begin{aligned}
s &= \int_{0}^{5} (30 - 1,2t^2) \, dt \\\\
s &= \left[ 30t - \frac{1,2}{3}t^3 \right]_0^5 \\\\
s &= \left[ 30t - 0,4t^3 \right]_0^5 \\\\
s &= (30 \cdot 5 - 0,4 \cdot 5^3) - (30 \cdot 0 - 0,4 \cdot 0^3) \\\\
s &= (150 - 0,4 \cdot 125) - 0 \\\\
s &= 150 - 50 \\\\
s &= 100
\end{aligned}
$$

**Ergebnis:** Der gesamte Bremsweg beträgt **100 Meter**.


### Lösung zu c) Interpretation der Rechnung
Die Rechnung untersucht den Zeitpunkt $t_1$, an dem das Fahrzeug genau **50 Meter** seines Bremsweges zurückgelegt hat.

1. **Bedeutung von $t_1$:** Nach ca. $1,74$ Sekunden hat das Auto die Hälfte des gesamten Bremsweges (50 von 100 Metern) absolviert.
2. **Geschwindigkeit:** Zum diesem Zeitpunkt $t_1$ beträgt die Restgeschwindigkeit des PKW noch ca. $26,37\,\text{m/s}$ (das sind ca. $95\,\text{km/h}$).

**Interpretation:**
Obwohl bereits die Hälfte der Bremsstrecke zurückgelegt wurde, hat sich die Geschwindigkeit nur geringfügig von $108\,\text{km/h}$ auf $95\,\text{km/h}$ verringert. Dies verdeutlicht, dass die Geschwindigkeit während eines Bremsvorgangs nicht linear abnimmt und das Fahrzeug auf den ersten Metern noch eine sehr hohe kinetische Energie besitzt.