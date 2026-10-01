# Tipp – Ebenenschar mit kleinstem Abstand

## Für Teil a)
* Setze die Koordinaten von $P(0,75 \mid 1 \mid 0)$ in die Schargleichung $E_k$ ein und forme nach dem Wurzelterm um:
  $$
  \begin{aligned}
  \sqrt{1 - k^2} = 4 - \frac{3}{4}k
  \end{aligned}
  $$
* Schätze den maximalen Wert der linken Seite und den minimalen Wert der rechten Seite für das Intervall $k \in [-1, 1]$ ab, um zu zeigen, dass die Gleichung keine Lösung besitzt.

---

## Für Teil b)
* **Abstandsfunktion aufstellen:** Der Betrag des Normalenvektors ist für alle $k$ konstant:
  $$
  \begin{aligned}
  |\vec{n}_k| = \sqrt{k^2 + \left(\sqrt{1 - k^2}\right)^2 + 3^2} = \sqrt{k^2 + 1 - k^2 + 9} = \sqrt{10}
  \end{aligned}
  $$
* Die Abstandsfunktion lautet somit:
  $$
  \begin{aligned}
  d(k) = \frac{\left|\frac{3}{4}k + \sqrt{1 - k^2} - 4\right|}{\sqrt{10}}
  \end{aligned}
  $$
* Da der Term im Betrag für alle $k \in [-1, 1]$ negativ ist, wird der Abstand $d(k)$ genau dann minimal, wenn die innere Funktion $f(k) = \frac{3}{4}k + \sqrt{1 - k^2}$ maximal wird.
* Bestimme das Maximum von $f(k)$ mittels der 1. Ableitung $f'(k) = 0$.