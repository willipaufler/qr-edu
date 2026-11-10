# Ableitungen (ohne CAS) - Tipp

### Teilaufgabe a) $f_1(x) = e^{4x}$
- Hier handelt es sich um eine elementare Verkettung: Die äußere Funktion ist die e-Funktion, die innere Funktion ist linear ($4x$).
- Wende die **Kettenregel** an: Ableitung der äußeren Funktion mal die innere Ableitung ($4$).

---

### Teilaufgabe b) $f_2(x) = 2x \cdot e^x$
- Hier liegt eine Multiplikation von zwei Termen vor, die $x$ enthalten. Verwende die **Produktregel** ($u \cdot v$)' = $u'v + uv'$.
- Der Faktor $2x$ hat die Ableitung $2$, und $e^x$ bleibt beim Ableiten unverändert.

---

### Teilaufgabe c) $f_3(x) = x^2 e^{-2x}$
- Für diesen Term benötigst du die **Produktregel**.
- Für den zweiten Faktor ($e^{-2x}$) musst du zusätzlich die Kettenregel (innere Ableitung $-2$) anwenden.

---

### Teilaufgabe d) $f_4(x) = \frac{x + 1}{e^x}$
- Hier liegt ein Bruch vor. Nutze die **Quotientenregel** $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$.
- Alternativ kannst du den Term als Produkt schreiben: $f_4(x) = (x + 1) \cdot e^{-x}$ und die Produktregel nutzen.

---

### Teilaufgabe e) $f_5(x) = e^{\sin(x)}$
- Wende die **Kettenregel** an: Äußere Ableitung ($e^{\sin(x)}$) mal innere Ableitung ($\cos(x)$).

---

### Teilaufgabe f) $f_6(x) = \sqrt{2x^2 + e^{-x}}$
- Nutze die Kettenregel für Wurzeln ($\left(\sqrt{u}\right)' = \frac{1}{2\sqrt{u}} \cdot u'$).
- Leite den inneren Term $2x^2 + e^{-x}$ termweise ab (beim e-Term greift wieder die Kettenregel).

---

### Teilaufgabe g) $f_7(x) = \ln(3x + 3)$
- Die Ableitung der äußeren Logarithmusfunktion $\ln(u)$ ist $\frac{1}{u}$.
- Wende die **Kettenregel** an: Multipliziere $\frac{1}{3x + 3}$ mit der inneren Ableitung von $3x + 3$ (welche $3$ beträgt) und kürze anschließend.

---

### Teilaufgabe h) $f_8(x) = x \cdot \ln(x)$
- Nutze die **Produktregel** ($u \cdot v$)' = $u'v + uv'$ mit $u = x$ und $v = \ln(x)$.
- Beachte die Grundableitung $(\ln(x))' = \frac{1}{x}$.