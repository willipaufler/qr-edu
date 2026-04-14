# Durchatmen - Lösung

### Zu Teilaufgabe a)
Die Funktion $f(t) = 0,125\pi \cdot \sin\left(\frac{\pi}{2}t\right)$ hat den Faktor $k = \frac{\pi}{2}$ im Argument.
Die Periodendauer $T$ (Dauer eines Atemzugs) berechnet sich durch:

$$
\begin{aligned}
T &= \frac{2\pi}{k} = \frac{2\pi}{\frac{\pi}{2}} \\\\
T &= \mathbf{4\,\text{s}}
\end{aligned}
$$

Anzahl der Atemzüge pro Minute ($60\,\text{s}$):

$$
\begin{aligned}
n &= \frac{60\,\text{s}}{4\,\text{s}} = \mathbf{15\,\text{Atemzüge/min}}
\end{aligned}
$$

### Zu Teilaufgabe b)
Das Lungenvolumen $V(t)$ ist das Integral der Rate $f(t)$:

$$
\begin{aligned}
V(t) &= \int 0,125\pi \cdot \sin\left(\frac{\pi}{2}t\right) \, dt \\\\
V(t) &= 0,125\pi \cdot \left( -\frac{1}{\frac{\pi}{2}} \cdot \cos\left(\frac{\pi}{2}t\right) \right) + C \\\\
V(t) &= -0,25 \cdot \cos\left(\frac{\pi}{2}t\right) + C
\end{aligned}
$$

Bestimmung von $C$ mit $V(0) = 3$:

$$
\begin{aligned}
3 &= -0,25 \cdot \cos(0) + C \\\\
3 &= -0,25 \cdot 1 + C \\\\
C &= 3,25
\end{aligned}
$$

Die Funktionsgleichung lautet: **$V(t) = -0,25 \cdot \cos\left(\frac{\pi}{2}t\right) + 3,25$**.

Berechnung für $t = 2\,\text{s}$:

$$
\begin{aligned}
V(2) &= -0,25 \cdot \cos\left(\frac{\pi}{2} \cdot 2\right) + 3,25 \\\\
V(2) &= -0,25 \cdot \cos(\pi) + 3,25 \\\\
V(2) &= -0,25 \cdot (-1) + 3,25 \\\\
V(2) &= \mathbf{3,5\,\text{l}}
\end{aligned}
$$

### Zu Teilaufgabe c)
Berechnung des Integrals:

$$
\begin{aligned}
\int_{0}^{4} f(t) \, dt &= \left[ -0,25 \cdot \cos\left(\frac{\pi}{2}t\right) \right]_0^4 \\\\
&= (-0,25 \cdot \cos(2\pi)) - (-0,25 \cdot \cos(0)) \\\\
&= -0,25 \cdot 1 + 0,25 \cdot 1 \\\\
&= \mathbf{0}
\end{aligned}
$$

**Interpretation:**
Das Integral über den Zeitraum von 4 Sekunden ist Null. Dies bedeutet, dass die Netto-Veränderung des Volumens über einen vollständigen Atemzug Null beträgt (eingeatmetes Volumen = ausgeatmetes Volumen). 
Zum Zeitpunkt $t = 4\,\text{s}$ ist das Lungenvolumen also wieder identisch mit dem Anfangsvolumen von **$3\,\text{l}$**.

??? info "Zusatz: Atemzugvolumen"
    Das in b) berechnete Volumen $V(2) = 3,5\,\text{l}$ stellt das maximale Volumen am Ende der Einatmungsphase dar. Die Differenz zum Startvolumen ($3,5 - 3,0 = 0,5\,\text{l}$) ist das sogenannte Atemzugvolumen (Tidalvolumen).