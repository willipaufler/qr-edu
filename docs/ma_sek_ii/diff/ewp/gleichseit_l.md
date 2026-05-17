# Rechteck im Dreieck - Lösung

### a) Bestimmen der Maße und des maximalen Flächeninhalts

**1. Hauptbedingung aufstellen:**
Die Breite des Rechtecks sei $x$ und die Höhe sei $y$. Der Flächeninhalt $A$ soll maximiert werden:
$$
\begin{aligned}
A(x, y) &= x \cdot y
\end{aligned}
$$


**2. Nebenbedingung aufstellen:**
Die Gesamthöhe $h$ des gleichseitigen Dreiecks mit Seitenlänge $a = 2$ berechnet sich über Pythagoras oder die Standardformel:
$$
\begin{aligned}
h &= \frac{\sqrt{3}}{2} \cdot a \\\\
&= \frac{\sqrt{3}}{2} \cdot 2 = \sqrt{3}
\end{aligned}
$$

Das kleine Dreieck, das oben auf dem Rechteck „sitzt“, ist ebenfalls gleichseitig und hat die Seitenlänge $x$. Seine Höhe $h_{oben}$ beträgt:
$$
\begin{aligned}
h_{oben} = \frac{\sqrt{3}}{2} \cdot x
\end{aligned}
$$

Aus der Skizze ist ersichtlich, dass die Gesamthöhe $h$ die Summe aus der Höhe des oberen Dreiecks $h_{oben}$ und der Rechteckshöhe $y$ ist:
$$
\begin{aligned}
 h &= h_{oben} + y \\\\ 
 \sqrt{3} &= \frac{\sqrt{3}}{2} \cdot x + y \\\\ 
 y &= \sqrt{3} - \frac{\sqrt{3}}{2} \cdot x 
 \end{aligned}
 $$

**3. Zielfunktion aufstellen:**
Setzt man die nach $y$ umgestellte Nebenbedingung in die Hauptbedingung ein, erhält man die Zielfunktion in Abhängigkeit von $x$:
$$
\begin{aligned} 
A(x) &= x \cdot \left(\sqrt{3} - \frac{\sqrt{3}}{2} \cdot x\right) \\\\ 
A(x) &= \sqrt{3}x - \frac{\sqrt{3}}{2}x^2 
\end{aligned}
$$

Der sinnvolle Definitionsbereich für die Breite ist $x \in (0; 2)$.

**4. Bestimmung des Maximums:**
Wir bilden die ersten beiden Ableitungen der Zielfunktion:
$$
\begin{aligned}
A'(x) &= \sqrt{3} - \sqrt{3}x\\\\
A''(x) &= -\sqrt{3}
\end{aligned}
$$

Notwendige Bedingung für ein Extremum ist $A'(x) = 0$:
$$
\begin{aligned} 
\sqrt{3} - \sqrt{3}x &= 0 \\\\ 
\sqrt{3}x &= \sqrt{3} \\\\ 
x &= 1 
\end{aligned}
$$

Hinreichende Bedingung prüfen:
$A''(1) = -\sqrt{3} < 0 \implies$ Es handelt sich um ein lokales Maximum.

**5. Berechnung der gesuchten Werte:**
Die optimale Breite des Rechtecks beträgt $x = 1$.
Die dazugehörige Höhe $y$ berechnet sich durch Einsetzen in die Nebenbedingung:
$y = \sqrt{3} - \frac{\sqrt{3}}{2} \cdot 1 = \frac{\sqrt{3}}{2}$

Der maximale Flächeninhalt $A$ beträgt:
$A(1) = 1 \cdot \frac{\sqrt{3}}{2} = \frac{\sqrt{3}}{2}$

Das Rechteck hat somit die Seitenlängen $x = 1$ und $y = \frac{\sqrt{3}}{2}$.  
Der maximale Flächeninhalt beträgt $A = \frac{\sqrt{3}}{2}$.