# Bestimmte Integrale - Tipp

Um bestimmte Integrale erfolgreich zu berechnen, solltest du nach folgendem Schema vorgehen:

---

### 1. Stammfunktion $F(x)$ finden
Wende die passenden Regeln an:
* **Potenzregel:** $\int x^n \, dx = \frac{1}{n+1}x^{n+1}$
* **Trigonometrie:** $\int \sin(x) \, dx = -\cos(x)$ und $\int \cos(x) \, dx = \sin(x)$
* **Lineare Substitution:** Bei Termen wie $(ax+b)^n$ musst du am Ende durch die innere Ableitung $a$ teilen.

### 2. Umschreiben vor dem Integrieren
Oft sieht man die Lösung erst nach einer kleinen Umformung:
* $\frac{1}{x^n} = x^{-n}$
* $\sqrt{x} = x^{0,5}$ oder $x^{\frac{1}{2}}$

### 3. Der Hauptsatz (HDI)
Setze die Grenzen in deine Stammfunktion ein:
$$\int_{a}^{b} f(x) \, dx = [F(x)]_{a}^{b} = F(b) - F(a)$$
*Vorsicht bei negativen Zahlen: Nutze Klammern beim Abziehen der unteren Grenze, um Vorzeichenfehler zu vermeiden!*