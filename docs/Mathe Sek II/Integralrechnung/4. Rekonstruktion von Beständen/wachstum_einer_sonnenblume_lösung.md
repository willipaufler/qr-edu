### Lösung zu a) Berechnung der Anfangshöhe

**Variante: Über den Gesamtzuwachs (Bestandsrekonstruktion)**
Bei dieser Methode berechnen wir zuerst, wie viel die Sonnenblume im Zeitraum von $t=0$ bis $t=32$ insgesamt gewachsen ist, und ziehen diesen Zuwachs von der Endhöhe ab.

1. **Berechnung des Integrals (Zuwachs):**
   Wir berechnen das bestimmte Integral der Wachstumsrate $w(t)$ im Intervall $[0; 32]$:
   $$
   \begin{aligned}
   \Delta h &= \int_{0}^{32} \left( -\frac{3}{1024}t^2 + \frac{3}{32}t + \frac{9}{4} \right) dt \\\\
   \Delta h &= \left[ -\frac{1}{1024}t^3 + \frac{3}{64}t^2 + \frac{9}{4}t \right]_{0}^{32} \\\\
   \Delta h &= \left( -\frac{32^3}{1024} + \frac{3 \cdot 32^2}{64} + \frac{9 \cdot 32}{4} \right) - (0) \\\\
   \Delta h &= (-32 + 48 + 72) - 0 \\\\
   \Delta h &= 88
   \end{aligned}
   $$
   Die Sonnenblume ist in den ersten 32 Tagen also insgesamt **$88\,\text{cm}$** gewachsen.

2. **Bestimmung der Anfangshöhe:**
   Da die Pflanze nach 32 Tagen $108\,\text{cm}$ hoch ist, muss sie zu Beginn folgende Höhe gehabt haben:
   $$
   \begin{aligned}
   h(0) = h(32) - \Delta h = 108\,\text{cm} - 88\,\text{cm} = \mathbf{20\,\text{cm}}
   \end{aligned}
   $$

---

### Lösung zu b) Ermittlung der Funktionsgleichung
Die Bestandsfunktion $h(t)$ setzt sich aus dem Anfangsbestand $h(0)$ und dem Zuwachs bis zum Zeitpunkt $t$ zusammen:
$$
\begin{aligned}
h(t) = h(0) + \int_{0}^{t} w(x) \, dx
\end{aligned}
$$

Eingesetzt ergibt das:
$$
\begin{aligned}
h(t) &= 20 + \left( -\frac{1}{1024}t^3 + \frac{3}{64}t^2 + \frac{9}{4}t \right)\\\\
h(t) &= -\frac{1}{1024}t^3 + \frac{3}{64}t^2 + \frac{9}{4}t + 20
\end{aligned}
$$

---

### c) Interpretation im Sachzusammenhang
* $\int_{t_0}^{t_1} w(t)dt$: Dieser Term gibt das **Gesamtwachstum** (die Höhenzunahme) der Sonnenblume im Zeitraum vom Tag $t_0$ bis zum Tag $t_1$ in Zentimetern an.
* $\frac{1}{t_1-t_0} \cdot \int_{t_0}^{t_1} w(t)dt$: Dies ist der **Mittelwert** der Funktion $w(t)$. Er gibt die **durchschnittliche Wachstumsrate** der Sonnenblume im Zeitraum $[t_0; t_1]$ in cm/Tag an. Der zweite Term beschreibt also die konstante Rate, mit der die Blume hätte wachsen müssen, um im selben Zeitraum den gleichen Höhenzuwachs zu erzielen.