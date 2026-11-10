# Skipiste - Tipp

### Teilaufgabe a) Höhendifferenz bestimmen
- Der Beginn der Skipiste liegt an der Stelle $x = 0$, das Ende an der Stelle $x = 1000$.
- Berechne die Höhen $f(0)$ und $f(1000)$ durch Einsetzen in die Funktionsgleichung. (Beachte: $e^0 = 1$).
- Die Höhendifferenz ist der Betrag der Differenz dieser beiden Höhenwerte.

---

### Teilaufgabe b) Durchschnittliches Gefälle bestimmen
- Das durchschnittliche Gefälle (oder die durchschnittliche Änderungsrate) über ein Intervall $[x_1; x_2]$ berechnest du über den Differenzenquotienten:
  $$
  m_{\text{avg}} = \frac{f(x_2) - f(x_1)}{x_2 - x_1}
  $$
- Setze $x_1 = 0$ und $x_2 = 1000$ ein. Ein negatives Vorzeichen zeigt an, dass es bergab geht.

---

### Teilaufgabe c) Stelle mit extremster Steigung bestimmen
- Die Steigung an jeder Stelle $x$ wird durch die 1. Ableitung $f'(x)$ beschrieben.
- „Extremste Steigung“ (hier maximales Gefälle bzw. betragsmäßig stärkster Abfall) bedeutet, dass du die Extrempunkte der Ableitungsfunktion $f'(x)$ suchen musst. 
- Das führt auf die **2. Ableitung**: Setze $f''(x) = 0$, um den Kandidaten (Wendepunkt des Graphen von $f$) zu finden. Prüfe mit $f'''(x) \neq 0$.

---

### Teilaufgabe d) Steigungswinkel prüfen
- Berechne die maximale Steigung (bzw. das maximale Gefälle) an der in Teil c) gefundenen Stelle als Funktionswert der 1. Ableitung: $m = f'(x_{\text{max}})$.
- Der Steigungswinkel $\alpha$ ergibt sich über den Tangens:
  $$
  |\tan(\alpha)| = |m| \quad \implies \quad \alpha = \arctan(|m|)
  $$
- Vergleiche den Winkel $\alpha$ mit dem Schwellenwert von $30^\circ$.