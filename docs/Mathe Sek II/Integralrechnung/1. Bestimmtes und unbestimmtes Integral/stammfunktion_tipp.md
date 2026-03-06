# Stammfunktion - Tipp

Um die Aufgaben erfolgreich zu lösen, solltest du die folgenden Regeln im Hinterkopf behalten:

---

### 1. Die Potenzregel (umgekehrt angewendet)
Wenn du eine Funktion $f(x) = x^n$ hast, lautet die Stammfunktion:
$$F(x) = \frac{1}{n+1} x^{n+1}$$
*Vergiss nicht: Exponent um eins erhöhen und durch den neuen Exponenten teilen!*

### 2. Umschreiben ist alles!
Oft hilft es, Brüche oder Wurzeln als Potenzen zu schreiben, bevor man rechnet:
* **Brüche:** $\frac{1}{x^n} = x^{-n}$
* **Wurzeln:** $\sqrt[n]{x^m} = x^{\frac{m}{n}}$

### 3. Kettenregel rückwärts (Lineare Substitution)
Wenn im Inneren einer Funktion ein linearer Term steht (z.B. $\cos(ax+b)$), musst du beim Aufleiten durch die innere Ableitung (die Zahl vor dem $x$) teilen:
$$f(x) = \sin(ax+b) \implies F(x) = -\frac{1}{a} \cos(ax+b)$$

### 4. Von $F(x)$ zu $f(x)$
In den Teilaufgaben **c, f, h** ist $F(x)$ gegeben und $f(x)$ gesucht. Hier musst du einfach nur **ableiten**, da gilt: $f(x) = F'(x)$. Benutze hierfür die normale Kettenregel.