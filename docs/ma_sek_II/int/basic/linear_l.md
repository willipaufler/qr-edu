# Stammfunktion einer linearen Funktion - Lösung

Gegeben ist $f(x) = -\frac{1}{2}x + \frac{1}{2}$ mit der Nullstelle bei $x = 1$.

---

### a) Jede Stammfunktion von $f$ ist eine quadratische Funktion.

* **Aussage:** Richtig
* **Begründung:** Beim Integrieren einer linearen Funktion (Polynom 1. Grades) erhöht sich der Grad um 1. Die Stammfunktion hat die Form $F(x) = -\frac{1}{4}x^2 + \frac{1}{2}x + C$, was eine quadratische Funktion darstellt.

### b) Jede Stammfunktion von $f$ hat an der Stelle $x = 1$ ein lokales Minimum.

* **Aussage:** Falsch
* **Begründung:** An der Stelle $x = 1$ gilt $f(1) = 0$, also hat $F$ dort eine Extremstelle ($F'(1)=0$). Da $f$ (die Steigung von $F$) dort jedoch einen Vorzeichenwechsel von **Plus nach Minus** hat, liegt ein lokales **Maximum** vor.

### c) Wenn $F$ eine Stammfunktion von $f$ ist, so ist $F''(0) = 0$.

* **Aussage:** Falsch
* **Begründung:** Es gilt $F''(x) = f'(x)$. Die Ableitung $f'(x)$ entspricht der Steigung der Geraden $f$. Da die Steigung überall $m = -\frac{1}{2}$ beträgt, gilt $F''(0) = -0,5$ und nicht $0$.

### d) Es ist $\int_{0}^{2} f(x) \, dx = 0$.

* **Aussage:** Richtig
* **Begründung:** 

\begin{align*}
\int_{0}^{2} (-\frac{1}{2}x + \frac{1}{2}) \, dx &= [-\frac{1}{4}x^2 + \frac{1}{2}x]_0^2 \\
&= (-\frac{1}{4} \cdot 4 + \frac{1}{2} \cdot 2) - 0 \\
&= (-1 + 1) = 0
\end{align*}

Grafisch: Die Fläche im Intervall $[0;1]$ (oberhalb der x-Achse) ist genau so groß wie die Fläche im Intervall $[1;2]$ (unterhalb der x-Achse).

### e) Es gibt Stammfunktionen von $f$, die an der Stelle $x = 0$ eine waagerechte Tangente haben.

* **Aussage:** Falsch
* **Begründung:** Eine waagerechte Tangente bei $F$ setzt voraus, dass $F'(0) = 0$ gilt. Da $F'(0) = f(0)$ ist und man am Graphen (oder der Gleichung) ablesen kann, dass $f(0) = 0,5$ ist, hat keine Stammfunktion dort eine waagerechte Tangente.