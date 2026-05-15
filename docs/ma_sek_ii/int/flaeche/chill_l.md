# Grill und Chill Lounge - Lösung

### 1. Bestimmung der nördlichen Grenzfunktion $g(x)$
Allgemeiner Ansatz: $g(x) = ax^3 + bx^2 + cx + d$
Bedingungen für Trassierung:

* $g(2)=2$ und $g(4)=4$ (versatzfrei)
* $g'(2)=0$ und $g'(4)=0$ (knickfrei)

Daraus ergibt sich das System:

I. $8a + 4b + 2c + d = 2$  
II. $64a + 16b + 4c + d = 4$  
III. $12a + 4b + c = 0$  
IV. $48a + 8b + c = 0$

Das Gleichungssystem lässt sich auch mithilfe des CAS lösen.

**Lösung:** $a = -0,5$; $b = 4,5$; $c = -12$; $d = 12$  
$\implies g(x) = -0,5x^3 + 4,5x^2 - 12x + 12$

---

### Teilaufgabe a) Die Nord-Süd-Teilung
Gesucht ist $t$, sodass die Fläche halbiert wird:

\begin{align*}
\int_{2}^{t} g(x) \, dx &= \int_{t}^{4} g(x) \, dx \\
\text{Liefert: } t_1 &\approx 3,199 \\
t_2 &\approx 6,523 \text{ (entfällt, da außerhalb des Intervalls)}
\end{align*}

**Ergebnis:** Die Nord-Süd-Linie liegt bei **$x \approx 3,2$**.

---

### Teilaufgabe b) Zaun durch den Wendepunkt
1. **Wendepunkt berechnen:** $g''(x) = -3x + 9 = 0 \implies x_w = 3$. $g(3) = 3$. Wendepunkt $W(3|3)$.
2. **Lineare Funktion des Zauns:** $f(x) = mx + 3 - 3m$ (geht durch $W$).
3. **Nullstelle des Zauns:** $f(x_0) = 0 \implies x_0 = 3 - \frac{3}{m}$.
4. **Flächenansatz:**

   $\int_{2}^{3} g(x) \, dx + \int_{3}^{3-\frac{3}{m}} f(x) \, dx = \frac{1}{2} \int_{2}^{4} g(x) \, dx$  
   Dies liefert für die Steigung: **$m = -7,2$**.
5. **Abstandsberechnung:**

   * Nullstelle $x_0 = 3 - \frac{3}{-7,2} = \frac{41}{12} \approx 3,417$.
   * Peters südwestliches Grundstücksende liegt bei $x=4$.
   * Abstand $d = 4 - \frac{41}{12} = \frac{7}{12} \text{ LE}$.
6. **Umrechnung:** $\frac{7}{12} \text{ LE} \cdot 10 \text{ m/LE} \approx 5,833 \text{ m}$.

**Ergebnis:** Der Abstand zum südwestlichen Grundstücksende beträgt ca. **$5,83 \text{ m}$**.