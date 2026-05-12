# Zahlenrätsel - Lösung

## Aufgabe a)
1. **Definitionen:** Summanden $x$ und $y$. Nebenbedingung: $x + y = 60 \Rightarrow y = 60 - x$.
2. **Zielfunktion:** $$
   P(x) = x \cdot (60 - x) = 60x - x^2
   $$
3. **Optimierung:**
   $$
   P'(x) = 60 - 2x
   $$
   Setze $P'(x) = 0$:
   $$
   60 - 2x = 0 \Rightarrow x = 30
   $$
4. **Ergebnis:**
   Der zweite Summand ist $y = 60 - 30 = 30$.
   Die Zahl 60 muss in **30 und 30** zerlegt werden. Das maximale Produkt beträgt **900**.

## Aufgabe b)
1. **Definitionen:**
   Summanden $x$ und $y$. Nebenbedingung: $x = 12 - y$.
2. **Zielfunktion:**
   $$
   S(y) = (12 - y) + \frac{9}{y} = 12 - y + 9y^{-1}
   $$
3. **Ableitung und Untersuchung:**
   $$
   S'(y) = -1 - 9y^{-2} = -1 - \frac{9}{y^2}
   $$
   Setzt man $S'(y) = 0$, erhält man:
   $$
   -1 = \frac{9}{y^2} \Rightarrow y^2 = -9
   $$
   Dies hat keine reelle Lösung. 
4. **Interpretation und Randwerte:**
   Da die Ableitung $S'(y)$ für alle positiven $y$ immer negativ ist ($S'(y) < 0$), fällt der Wert der Summe im gesamten Verlauf stetig ab.
   Das bedeutet, die Summe wird umso kleiner, je größer $y$ gewählt wird. Da $x$ positiv sein muss ($x > 0$), kann $y$ maximal gegen 12 gehen.  
   **Ergebnis:** Ein lokales Minimum im Inneren existiert nicht; der Wert minimiert sich am Rand des Definitionsbereichs ($y \to 12, x \to 0$).
