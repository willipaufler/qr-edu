# Geteilter Rotationskörper - Lösung

### Zu Teilaufgabe a)
Es entsteht ein **Zylinder** mit Radius $r=1$ und Höhe $h=1$.

$$
\begin{aligned}
V_{Gesamt} &= \pi \cdot \int_{0}^{1} 1^2 \, dx= \pi \cdot [x]_0^1=\pi
\end{aligned}
$$

### Zu Teilaufgabe b)
* **Körper:** Durch die Rotation von $g$ entsteht im Inneren ein **Kegel**. Der zweite Teilkörper ist der Rest des Zylinders (ein Hohlkörper).
* **Volumen des Kegels:**
$$
\begin{aligned}
V_g &= \pi \cdot \int_{0}^{1} x^2 \, dx \\\\
V_g &= \pi \cdot \left[ \frac{1}{3}x^3 \right]_0^1 = \frac{1}{3}\pi
\end{aligned}
$$
* **Verhältnis:** Das Volumen des Kegels ist $\frac{1}{3}\pi$, das Restvolumen ist $\pi - \frac{1}{3}\pi = \frac{2}{3}\pi$. Das Verhältnis der Volumina beträgt somit **1 : 2**.

??? info "Fläche vs. Volumen"
    Es ist ein häufiger Trugschluss zu glauben, dass eine flächenhalbierende Gerade auch das Rotationsvolumen halbiert. 
    
    Obwohl die Gerade $g(x) = x$ die Fläche unter $f(x) = 1$ im Intervall $[0; 1]$ exakt **halbiert** ($A_{Dreieck} = 0,5$), beträgt das Volumen des Kegels nur **ein Drittel** des Zylinders.
    
    **Warum ist das so?**
    Bei der Rotation wird der Radius quadriert ($V \sim r^2$). Da die Radien der Geraden $g(x)$ im Intervall $[0; 1]$ (außer am Endpunkt) kleiner als $1$ sind, bewirkt das Quadrieren ein stärkeres „Schrumpfen“ des Volumens im Vergleich zur Fläche:
    $$
    \begin{aligned}
    \text{Fläche:} \quad & \int_{0}^{1} x \, dx = \frac{1}{2} \\\\
    \text{Volumen:} \quad & \pi \cdot \int_{0}^{1} x^2 \, dx = \frac{1}{3}\pi
    \end{aligned}
    $$
    Zudem haben weiter außen liegende Flächenanteile bei der Rotation einen größeren Umfang und erzeugen daher mehr Volumen als Anteile nahe der Drehachse.

### Zu Teilaufgabe c)
Das Zielvolumen des inneren Körpers ist $V_{innen} = \frac{\pi}{2}$. Da ein Kegel bei $m=1$ nur $\frac{\pi}{3}$ füllen würde, muss $m > 1$ gelten. Die Gerade schneidet die Zylinderwand $f(x)=1$ bei $x_S = \frac{1}{m}$.

$$
\begin{aligned}
V_{innen} &= \pi \cdot \int_{0}^{\frac{1}{m}} (mx)^2 \, dx + \pi \cdot \int_{\frac{1}{m}}^{1} 1^2 \, dx = \frac{\pi}{2} \quad | : \pi \\\\
\frac{1}{2} &= \left[ \frac{m^2}{3}x^3 \right]_0^{\frac{1}{m}} + [x]_{\frac{1}{m}}^1 \\\\
\frac{1}{2} &= \left( \frac{m^2}{3} \cdot \frac{1}{m^3} \right) + \left( 1 - \frac{1}{m} \right) \\\\
\frac{1}{2} &= \frac{1}{3m} + 1 - \frac{1}{m} \\\\
\frac{1}{2} &= 1 - \frac{2}{3m} \\\\
\frac{2}{3m} &= \frac{1}{2} \\\\
3m &= 4 \\\\
m &= \mathbf{\frac{4}{3}}
\end{aligned}
$$

**Ergebnis:** Die Steigung der Geraden muss **$m = \frac{4}{3}$** betragen.