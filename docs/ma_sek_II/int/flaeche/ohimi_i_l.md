# Flächenberechnung oHiMi - Lösung

### Teilaufgabe a) Nachweis der Tangente
Gegeben: $f(x) = -x^2 + 4$, $g(x) = -4x + 8$, Punkt $P(2|0)$.

1.  **Punktprobe:**
    * $f(2) = -(2)^2 + 4 = -4 + 4 = 0$ ✔️
    * $g(2) = -4(2) + 8 = -8 + 8 = 0$ ✔️  
    Der Punkt $P(2|0)$ liegt auf beiden Graphen.

2.  **Steigungsvergleich:**
    * Ableitung bilden: $f'(x) = -2x$
    * Steigung an der Stelle $x = 2$: $f'(2) = -2 \cdot 2 = -4$
    * Die Steigung der Geraden $g(x) = -4x + 8$ ist ebenfalls $m = -4$.
    * Da Punkt und Steigung übereinstimmen, ist $g$ die Tangente an $f$ in $P$.

---

### Teilaufgabe b) Flächeninhalt
Die Fläche wird begrenzt durch $x = 0$ ($y$-Achse) und $x = 2$ (Berührpunkt). Im Intervall $[0; 2]$ liegt die Gerade $g$ über der Parabel $f$.

1.  **Differenzfunktion aufstellen:**

    $h(x) = g(x) - f(x) = (-4x + 8) - (-x^2 + 4)$

    $h(x) = x^2 - 4x + 4$

2.  **Integral berechnen:**

    \begin{align*}
    A &= \int_{0}^{2} (x^2 - 4x + 4) \, dx\\
    &= \left[ \frac{1}{3}x^3 - 2x^2 + 4x \right]_{0}^{2}\\
    &= \left( \frac{1}{3} \cdot 2^3 - 2 \cdot 2^2 + 4 \cdot 2 \right) - (0)\\
    &= \frac{8}{3} - 8 + 8\\
    &= \frac{8}{3} \approx 2,67
    \end{align*}

**Ergebnis:** Der Flächeninhalt beträgt $\frac{8}{3}$ Flächeneinheiten.