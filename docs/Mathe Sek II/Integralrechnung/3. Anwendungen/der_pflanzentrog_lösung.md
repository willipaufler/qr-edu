# Der Pflanztrog - Lösung

### a) Maximale Höhe
Der tiefste Punkt liegt beim Scheitelpunkt $S(0|-4)$. Da die Oberkante bei $y=0$ liegt, beträgt die Tiefe $4 \text{ LE}$.
**Ergebnis:** Die maximale Höhe beträgt **$4 \text{ dm}$**.

### b) Maximales Fassungsvermögen
Für die **Querschnittsfläche** gilt.

\begin{align*}
A &= |\int_{-4}^{4} (\frac{1}{4}x^2 - 4) \, dx|\\
&= |[(\frac{1}{12}x^3 - 4x)]_{-4}^{4}|\\
&= |(\frac{64}{12} - 16) - (-\frac{64}{12} + 16)|\\
&= |(5,33 - 16) - (-5,33 + 16)|\\
&= |-21,33|= 21,33 \text{ dm}^2
\end{align*}

Das **Volumen** lässt sich mithilfe der Querschnittsfläche und der Länge $L = 12 \text{ m} = 120 \text{ dm}$ berechnen:

$$V =  A \cdot L= 21,33 \text{ dm}^2 \cdot 120 \text{ dm} = 2560 \text{ dm}^3$$



**Ergebnis:** Das Fassungsvermögen beträgt **$2560 \text{ Liter}$**.

### c) Zeitpunkt bei $1 \text{ dm}$ Wasserhöhe
1. Wenn das Wasser $1 \text{ dm}$ hoch steht, füllt es den Bereich von $y = -4$ bis $y = -3$.
2. Schnittstellen für $f(x) = -3$: $\frac{1}{4}x^2 - 4 = -3 \implies x^2 = 4 \implies x = \pm 2$.
3. Flächeninhalt des Wassers: 

\begin{align*}
A_W &= \int_{-2}^{2} (-3 - (\frac{1}{4}x^2 - 4)) \, dx\\
&= [(\frac{1}{12}x^3 - 4x)]_{-2}^{2}\\
&= (2 - \frac{8}{12}) - (-2 + \frac{8}{12})\\
&= \frac{4}{3} - (-\frac{4}{3}) = \frac{8}{3} \text{ dm}^2.
\end{align*}

4. Wasservolumen: $V_W =A_W \cdot L = \frac{8}{3} \cdot 120 = 320 \text{ Liter}$.
5. Zeit: $t = 320 \text{ l} / 15 \frac{\text{l}}{\text{min}} \approx 21,33 \text{ min}$.
**Ergebnis:** Nach ca. **$21 \text{ min}$ und $20 \text{ sek}$** steht das Wasser $1 \text{ dm}$ hoch.

### d) Wasserstand nach $10 \text{ min}$
1. Wasservolumen: $V = 10 \text{ min} \cdot 15 \frac{\text{l}}{\text{min}} = 150 \text{ l}$.
2. Querschnittsfläche des Wassers: $A_W = 150 \text{ l} / 120 \text{ dm} = 1,25 \text{ dm}^2$.
3. Das Wasser steht erreicht nach 10 min eine Höhe von $-4+h$.  
Für die Integrationsgrenzen ergibt sich mit:

$$f(x)=-4+h \Leftrightarrow x=\pm \sqrt{4h}$$



Mit diesen Integrationsgrenzen erhält man die Höhe durch Integration:
$$\int_{-\sqrt{4h}}^{\sqrt{4h}} ((-4+h) - f(x)) \, dx = 1,25.$$

   Durch Lösen der Gleichung (CAS) ergibt sich: $h\approx 0,61.$  
**Ergebnis:** Die Höhe beträgt ca. **$0,61 \text{ dm}$**.