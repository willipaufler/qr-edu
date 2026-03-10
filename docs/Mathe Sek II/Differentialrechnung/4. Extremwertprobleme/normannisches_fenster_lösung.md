# Normannisches Fenster - Lösung

### 1. Aufstellen der Gleichungen
**Nebenbedingung (Fläche):**
Die Fläche ist konstant $A = 4\,\rm m^2$.
$$
4 = d \cdot h + \frac{1}{2} \pi \left(\frac{d}{2}\right)^2 = d \cdot h + \frac{\pi}{8}d^2
$$
Umgestellt nach $h$:
$$
h = \frac{4 - \frac{\pi}{8}d^2}{d} = \frac{4}{d} - \frac{\pi}{8}d
$$

**Zielfunktion (Rahmenlänge):**
Minimiert werden soll die äußere Rahmenlänge $L$:
$$
L(d, h) = d + 2h + \frac{\pi}{2}d
$$
Einsetzen von $h$:
$$
\begin{aligned}
L(d) &= d + 2\left(\frac{4}{d} - \frac{\pi}{8}d\right) + \frac{\pi}{2}d \\\\
&= d + \frac{8}{d} - \frac{\pi}{4}d + \frac{\pi}{2}d \\\\
&= \frac{8}{d} + d \left(1 + \frac{\pi}{4}\right)
\end{aligned}
$$

### 2. Extremwertberechnung
Ableitung nach $d$ bilden:
$$
L'(d) = -\frac{8}{d^2} + 1 + \frac{\pi}{4}
$$
Setze $L'(d) = 0$:
$$
\frac{8}{d^2} = 1 + \frac{\pi}{4}
$$
$$
d^2 = \frac{8}{1 + \frac{\pi}{4}} \approx 4,482
$$
$$
d \approx \sqrt{4,482} \approx 2,117\,\rm m
$$

### 3. Berechnung der Höhe $h$
Setze $d \approx 2,117$ in die Formel für $h$ ein:
$$
h = \frac{4}{2,117} - \frac{\pi}{8} \cdot 2,117 \approx 1,058\,\rm m
$$

### 4. Ergebnis
Damit die Rahmenlänge bei einer Fläche von $4\,\rm m^2$ minimal wird, müssen die Maße wie folgt gewählt werden:

* **Breite $d \approx 2,12\,\rm m$**
* **Höhe $h \approx 1,06\,\rm m$**

Interessanterweise gilt beim Optimum $h = \frac{d}{2}$. Das bedeutet, der rechteckige Teil des Fensters ist genau halb so hoch wie breit, womit die Gesamthöhe des Fensters gleich seiner Breite ist.
