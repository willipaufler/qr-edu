# Designervase - Tipp

![Designervase](../../../assets/images/designervase_light.png#only-light){width="60%"}
![Designervase](../../../assets/images/designervase_dark.png#only-dark){width="60%"}
/// caption
Graph der Desigernvase und schematische Darstellung der Vase in der Box.
///

### Aufgabe a) Modellierung der Kontur
Um die Funktion 3. Grades $f(x) = ax^3 + bx^2 + cx + d$ aufzustellen, benötigst du vier Bedingungen aus dem Text:

1. **Punkte einsetzen:** Nutze den Bodenradius bei $x=0$, den Radius an der breitesten Stelle bei $x=6$ und den Radius der Öffnung bei $x=20$. 
2. **Achtung Durchmesser:** Bei $x=6$ ist der *Durchmesser* 10 cm angegeben. Der Funktionswert $f(6)$ entspricht dem Radius.
3. **Die vierte Bedingung:** "Breiteste Stelle" bedeutet mathematisch, dass dort ein lokales Maximum vorliegt. Die Steigung der Tangente (1. Ableitung) muss dort also null sein: $f'(6)=0$.
4. **LGS:** Nutze den CAS, um das System aus diesen vier Gleichungen zu lösen.

### Aufgabe b) Schaumstoffvolumen
1. **Box-Maße:** Die Box umschließt die Vase komplett. Da der maximale Radius $5 \, \text{cm}$ beträgt und überall $1 \, \text{cm}$ Schaumstoff hinkommt, berechne die Breite der Box über den Durchmesser plus Polsterung. 
2. **Höhe:** Die Vase ist $20 \, \text{cm}$ hoch. Addiere $1 \, \text{cm}$ für den Boden und $1 \, \text{cm}$ für den Deckel der Box.
3. **Rechnung:** $V_{Schaum} = V_{Box} - V_{Vase}$.

### Aufgabe c) Gewicht der Vase
1. **Zwei Volumina:** Berechne das Außenvolumen $V_a$ (Integral von $f$ über $[0; 20]$).
2. **Innenform:** Das Innenvolumen $V_i$ berechnest du mit $g(x) = f(x) - 0,5$. Da der Boden $0,5 \, \text{cm}$ dick ist, startet das Integral erst bei $x=0,5$.
3. **Masse:** $m = (V_a - V_i) \cdot \rho$. Achte darauf, im CAS mit exakten Werten zu rechnen, um Rundungsfehler zu vermeiden!