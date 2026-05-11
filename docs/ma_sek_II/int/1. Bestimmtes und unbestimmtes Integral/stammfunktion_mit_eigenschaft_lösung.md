# Stammfunktion mit Eigenschaft - Lösung

Hier sind die Berechnungen für die spezifischen Stammfunktionen:

### a) $f_1(x) = x^2 - 1$ durch $P(0|1)$
* **Allgemeine Stammfunktion:** $F_C(x) = \frac{1}{3}x^3 - x + C$
* **Berechnung von $C$:**

\begin{align*}
F_C(0) &= 1 \\
\frac{1}{3}(0)^3 - 0 + C &= 1 \\
C &= 1
\end{align*}

**Ergebnis:** $F(x) = \frac{1}{3}x^3 - x + 1$

---

### b) $f_2(x) = \sqrt{x}$ mit Nullstelle bei $x=1$
* **Umformung:** $f_2(x) = x^{0,5}$
* **Allgemeine Stammfunktion:** $F_C(x) = \frac{2}{3}x^{1,5} + C = \frac{2}{3}\sqrt{x^3} + C$
* **Berechnung von $C$:**

\begin{align*}
F_C(1) &= 0 \\
\frac{2}{3}(1)^{1,5} + C &= 0 \\
\frac{2}{3} + C &= 0 \\
C &= -\frac{2}{3}
\end{align*}

**Ergebnis:** $F(x) = \frac{2}{3}x^{1,5} - \frac{2}{3}$

---

### c) $f_3(x) = 2x + 2$ mit genau einer Nullstelle
* **Allgemeine Stammfunktion:** $F_C(x) = x^2 + 2x + C$
* **Bedingung:** Eine quadratische Funktion hat genau eine Nullstelle, wenn ihr Scheitelpunkt auf der x-Achse liegt (Diskriminante der p-q-Formel ist 0).
* **Berechnung von $C$:**

\begin{align*}
x^2 + 2x + C &= 0 \\
x_{1,2} &= -1 \pm \sqrt{1^2 - C} \\
\text{Bedingung: } 1 - C &= 0 \\
C &= 1
\end{align*}

**Ergebnis:** $F(x) = x^2 + 2x + 1$ (entspricht $(x+1)^2$)

---

### d) $f_4(x) = \sin(x)$ durch den Ursprung $O(0|0)$
* **Allgemeine Stammfunktion:** $F_C(x) = -\cos(x) + C$
* **Berechnung von $C$:**

\begin{align*}
F_C(0) &= 0 \\
-\cos(0) + C &= 0 \\
-1 + C &= 0 \\
C &= 1
\end{align*}

**Ergebnis:** $F(x) = -\cos(x) + 1$