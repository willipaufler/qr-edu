# Tangente durch äußeren Punkt (ohne CAS) - Tipp

### Ansatz über den Berührpunkt
- Da der Punkt $Q(2 \mid 0)$ nicht auf dem Graphen von $f$ liegt (prüfe das nach!), kannst du die Tangentengleichung nicht direkt über $f'(2)$ berechnen.
- **Wähle einen allgemeinen Berührpunkt** $P(u \mid f(u))$ auf dem Graphen:
  $$
  P\left(u \mid 2 \cdot e^{0{,}25u}\right)
  $$

---

### Steigung auf zwei Wegen bestimmen
- **Weg 1 (Ableitung):** Die Steigung $m$ der Tangente im Punkt $P$ ist gleich der Ableitung an der Stelle $u$:
  $$
  m = f'(u)
  $$
- **Weg 2 (Zwei-Punkte-Form):** Die Steigung der Sekante/Tangente zwischen dem Berührpunkt $P(u \mid f(u))$ und dem äußeren Punkt $Q(2 \mid 0)$ lässt sich mit der Steigungsformel $m = \frac{y_2 - y_1}{x_2 - x_1}$ berechnen:
  $$
  m = \frac{2 \cdot e^{0{,}25u} - 0}{u - 2}
  $$

---

### Gleichung nach $u$ auflösen
- Setze beide Terme für die Steigung $m$ gleich:
  $$
  f'(u) = \frac{2 \cdot e^{0{,}25u} - 0}{u - 2}
  $$
- Löse diese Gleichung nach $u$ auf (der Faktor $e^{0{,}25u}$ kürzt sich dabei heraus oder lässt sich ausklammern).
- Berechne anschließend die konkrete Tangentengleichung $y = m \cdot x + n$ (oder in Punkt-Steigungs-Form).