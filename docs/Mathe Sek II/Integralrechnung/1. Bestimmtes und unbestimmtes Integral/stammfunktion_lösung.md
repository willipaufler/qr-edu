# Stammfunktion - Lösung

Zur Übersichtlichkeit wurde die Integrationskonstante $C=0$ gesetzt.

| Aufgabe | Gegeben | Gesucht (Ergebnis) |
| :--- | :--- | :--- |
| **a)** | $f(x) = x^4 + 5x^3 + 1$ | $F(x) = \frac{1}{5}x^5 + \frac{5}{4}x^4 + x$ |
| **b)** | $f(x) = 3x^2 + \frac{1}{x^2}$ | $F(x) = x^3 - \frac{1}{x}$ |
| **c)** | $F(x) = \frac{3}{2}x^{\frac{3}{2}}$ | $f(x) = \frac{9}{4}x^{\frac{1}{2}}$ (bzw. $\frac{9}{4}\sqrt{x}$) |
| **d)** | $f(x) = \sqrt{x^3} + \sqrt[3]{x^2}$ | $F(x) = \frac{2}{5}x^{\frac{5}{2}} + \frac{3}{5}x^{\frac{5}{3}}$ |
| **e)** | $f(x) = 2 \cos(2x)$ | $F(x) = \sin(2x)$ |
| **f)** | $F(x) = (3x^2 + x)^2$ | $f(x) = (12x + 2)(3x^2 + x)$ |
| **g)** | $f(x) = (2x + 2)^4$ | $F(x) = \frac{1}{10}(2x + 2)^5$ |
| **h)** | $F(t) = \sin(3t + 2)$ | $f(t) = 3 \cos(3t + 2)$ |

---

### Kurze Erläuterungen:
* **Aufgabe d):** $\sqrt{x^3} = x^{3/2}$. Aufgeleitet: $\frac{1}{3/2 + 1}x^{5/2} = \frac{2}{5}x^{5/2}$.
* **Aufgabe f):** Hier wurde $F(x)$ abgeleitet ($f = F'$). Mit der Kettenregel: $2 \cdot (3x^2 + x)^1 \cdot (6x + 1)$. Zusammengefasst: $(12x + 2)(3x^2 + x)$.
* **Aufgabe g):** Aufleiten mit linearer Substitution. Äußere Aufleitung $\frac{1}{5}(\dots)^5$, dann teilen durch die innere Ableitung $2$. Also $\frac{1}{5 \cdot 2} = \frac{1}{10}$.