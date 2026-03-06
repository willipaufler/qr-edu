# Stammfunktion mit Eigenschaft - Tipps

Um eine spezifische Stammfunktion zu finden, die eine bestimmte Bedingung erfüllt, gehst du am besten in zwei Schritten vor:

---

### 1. Die allgemeine Stammfunktion finden
Bestimme zuerst die Menge aller Stammfunktionen, indem du die Integrationskonstante $C$ hinzufügst:
$$F(x) = \int f(x) \, dx + C$$

### 2. Die Konstante $C$ berechnen
Nutze die gegebene Eigenschaft, um eine Gleichung aufzustellen und nach $C$ aufzulösen:

* **Punkt gegeben:** Verläuft die Funktion durch $(x_0 | y_0)$, setze $F(x_0) = y_0$.
* **Koordinatenursprung:** Dies ist der Punkt $(0 | 0)$. Setze also $F(0) = 0$.
* **Nullstelle bei $x_n$:** Das bedeutet, der Funktionswert an dieser Stelle ist Null. Setze $F(x_n) = 0$.
* **Genau eine Nullstelle:** Überlege dir, wie der Graph der Stammfunktion (oft eine Parabel) verschoben sein muss, damit er die x-Achse nur berührt ($D = 0$ oder Scheitelpunkt auf der x-Achse).

### Hilfreiche Grundintegrale:
* $x^n \to \frac{1}{n+1}x^{n+1}$
* $\sqrt{x} = x^{1/2} \to \frac{2}{3}x^{3/2}$
* $\sin(x) \to -\cos(x)$