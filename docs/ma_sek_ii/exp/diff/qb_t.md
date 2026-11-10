# Querbeet (ohne CAS) - Tipp

### Teilaufgabe a)
- **Notwendige Bedingung:** Leite die Funktion $f(x)$ ab und setze die 1. Ableitung gleich 0:
  $$
  f'(x) = 0
  $$
- Beachte beim Ableiten: $e$ ist eine Konstante (Eulersche Zahl), also ist der Term $-ex$ linear bezüglich $x$. Seine Ableitung ist einfach $-e$. Die Ableitung von $e^x$ ist $e^x$.
- **Hinweis zur Gleichung:** Aus $-e + e^x = 0$ folgt $e^x = e^1$. Durch Exponentenvergleich oder Anwenden des natürlichen Logarithmus ($\ln$) erhältst du $x$.
- **Hinreichende Bedingung:** Prüfe mit der 2. Ableitung $f''(x)$, ob $f''(x_0) > 0$ gilt.
- **Punktkoordinaten:** Setze die $x$-Koordinate in die Ursprungsfunktion $f(x)$ ein, um den $y$-Wert des Tiefpunkts zu berechnen.

---

### Teilaufgabe b)
- Die allgemeine Tangentengleichung lautet:
  $$
  y = m \cdot x + n
  $$
- **Schritt 1 ($y$-Wert des Berührpunkts):** Berechne $f(0)$, indem du $x = 0$ in $f(x)$ einsetzt (Denke daran: $e^0 = 1$).
- **Schritt 2 (Steigung $m$):** Berechne $m = f'(0)$ mithilfe deiner 1. Ableitung aus Teilaufgabe a).
- **Schritt 3 ($y$-Achsenabschnitt $n$):** Der $y$-Wert an der Stelle $x = 0$ entspricht bereits direkt dem $y$-Achsenabschnitt $n$. Alternativ setzt du Punkt und Steigung in $y = m \cdot x + n$ ein und löst nach $n$ auf.

---

### Teilaufgabe c)
- Eine Spiegelung des Graphen einer Funktion $f(x)$ an der $y$-Achse entspricht der Ersetzung von $x$ durch $-x$:
  $$
  g(x) = f(-x)
  $$
- Ersetze in der Funktionsgleichung $f(x) = -ex + e^x$ jedes $x$ durch $(-x)$ und vereinfache das Ergebnis.