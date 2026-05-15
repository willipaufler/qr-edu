# Rotationsvolumen - Tipp

### Aufgabe a) Bestimmung der Tangente
Um die Gleichung der Tangente $t(x) = m \cdot x + c$ an der Stelle $x_0$ aufzustellen, beachte folgende Schritte:

1. **Punkt bestimmen:** Berechne zuerst den Funktionswert an der Stelle $x = 1$, also $f(1)$. Die Tangente berührt den Graphen im Punkt $P(1 | f(1))$.
2. **Steigung bestimmen:** Die Steigung $m$ der Tangente entspricht der Ableitung der Funktion an dieser Stelle. Bilde $f'(x)$ und berechne $m = f'(1)$.
3. **Gleichung aufstellen:** Setze den Punkt $P$ und die Steigung $m$ in die allgemeine Geradengleichung $y = m \cdot x + c$ ein, um den y-Achsenabschnitt $c$ zu bestimmen.

---

### Aufgabe b) Volumen des Rotationskörpers
Hier hilft eine Skizze der Tangente im Koordinatensystem:

1. **Grenzen finden:** "Im 1. Quadranten" bedeutet, dass die Fläche von der Tangente, der $x$-Achse und der $y$-Achse eingeschlossen wird. Suche die Nullstelle der Tangente ($x$-Achse) und den Schnittpunkt mit der $y$-Achse ($x=0$).
2. **Körper benennen:** Wenn eine schräge Gerade um die $x$-Achse rotiert, entsteht eine bekannte geometrische Form. Stell dir vor, wie die Oberkante eines Trichters entsteht.
3. **Volumen berechnen:** Nutze die Formel für das Rotationsvolumen:
   $$V = \pi \cdot \int_{a}^{b} (t(x))^2 \, dx$$
   Setze für $t(x)$ deine Tangentengleichung aus Aufgabe a) ein.

---

### Aufgabe c) Untersuchung mit Parametern (CAS)
In dieser Teilaufgabe arbeitest du nicht mehr mit einer festen Zahl, sondern mit dem Parameter $a.$

1. **Allgemeine Tangente:** Bestimme die Tangentengleichung $t_a(x)$ in Abhängigkeit von $a$. Nutze dafür die allgemeine Punkt-Steigungs-Form:
   $$t_a(x) = f'(a) \cdot (x - a) + f(a)$$
2. **Volumenfunktion aufstellen:** Berechne das Rotationsvolumen $V(a)$ in Abhängigkeit von $a$. Die Vorgehensweise bleibt dieselbe wie in b), nur dass deine Grenzen und deine Funktion den Buchstaben $a$ enthalten.
3. **Zusammenhang prüfen:** Untersuche, was passiert, wenn du $a$ durch $2a$ ersetzt. Berechne das Verhältnis:
   $$
   \begin{aligned}
   \frac{V(2a)}{V(a)}
   \end{aligned}
   $$
   Wenn das Ergebnis $0,5$ (also $\frac{1}{2}$) ist, ist die Aussage verifiziert.