# Flächenberechnung oHiMi II - Tipp

Hier sind Hilfestellungen, um die Aufgabe strukturiert anzugehen:

---

### Zu Teilaufgabe a)
* **Fläche unter einem Graphen:** Erinnere dich an die Grundformel für die Fläche zwischen Graph und x-Achse: $A = \int_{a}^{b} f(x) \, dx$.
* **Grenzen:** Die Grenzen sind im Text direkt gegeben ($0 \leq x \leq 2$).
* **Potenzregel:** Achte beim Integrieren von $-x^3$ und $3x^2$ auf die Vorzeichen und die neuen Nenner.

### Zu Teilaufgabe b)
* **Geradengleichung aufstellen:** Die Gerade $g$ verläuft durch $S(0|y_s)$ und $H(2|4)$. Nutze die allgemeine Form $g(x) = mx + b$. Hierbei ist $b$ direkt dein gesuchtes $y_s$.
* **Flächenansatz:** Die Fläche zwischen $f$, der y-Achse und der Geraden $g$ im Intervall $[0;2]$ lässt sich als Differenzintegral schreiben:
    $$A = \int_{0}^{2} (g(x) - f(x)) \, dx \quad \text{oder} \quad A = \int_{0}^{2} (f(x) - g(x)) \, dx$$
* **Geometrischer Trick:** Da du aus Aufg. a) weißt, dass $\int_0^2 f(x) dx = 4$ ist, kannst du die Fläche auch als Differenz zwischen der Fläche unter der Geraden (ein Trapez!) und der Fläche unter der Kurve betrachten (oder umgekehrt, je nachdem wie die Gerade liegt).
* **Gleichung lösen:** Setze den Flächeninhalt gleich $4$ und löse nach der Unbekannten $y_s$ auf.