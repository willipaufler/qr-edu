# Extremale Fläche - Lösung

### 1. Vorbereitung
$f(x) = x(x - a)(x - 2) = x(x^2 - 2x - ax + 2a) = x^3 - (a+2)x^2 + 2ax$

Stammfunktion: $F(x) = \frac{1}{4}x^4 - \frac{a+2}{3}x^3 + ax^2$

### 2. Aufstellen der Flächenfunktion $A(a)$
$A(a) = [F(x)]_0^a - [F(x)]_a^2 = (F(a) - F(0)) - (F(2) - F(a)) = 2F(a) - F(2)$

Einsetzen der Werte:
* $F(a) = \frac{1}{4}a^4 - \frac{a+2}{3}a^3 + a^3 = \frac{1}{4}a^4 - \frac{1}{3}a^4 - \frac{2}{3}a^3 + a^3 = -\frac{1}{12}a^4 + \frac{1}{3}a^3$
* $F(2) = \frac{1}{4}(16) - \frac{a+2}{3}(8) + 4a = 4 - \frac{8}{3}a - \frac{16}{3} + 4a = \frac{4}{3}a - \frac{4}{3}$

$A(a) = 2(-\frac{1}{12}a^4 + \frac{1}{3}a^3) - (\frac{4}{3}a - \frac{4}{3}) = -\frac{1}{6}a^4 + \frac{2}{3}a^3 - \frac{4}{3}a + \frac{4}{3}$

### 3. Ableiten und Nullsetzen
$A'(a) = -\frac{4}{6}a^3 + 2a^2 - \frac{4}{3} = -\frac{2}{3}a^3 + 2a^2 - \frac{4}{3}$

Setze $A'(a) = 0$:
$-\frac{2}{3}a^3 + 2a^2 - \frac{4}{3} = 0 \quad | \cdot (-\frac{3}{2})$
$a^3 - 3a^2 + 2 = 0$

Durch Probieren finden wir die Nullstelle **$a = 1$** (denn $1-3+2 = 0$).
*(Weitere Nullstellen liegen außerhalb des Intervalls $0 \leq a < 2$.)*

### 4. Minimaler Flächeninhalt
Setze $a = 1$ in $A(a)$ ein:
$A(1) = -\frac{1}{6}(1)^4 + \frac{2}{3}(1)^3 - \frac{4}{3}(1) + \frac{4}{3}$
$A(1) = -\frac{1}{6} + \frac{2}{3} = -\frac{1}{6} + \frac{4}{6} = \frac{3}{6} = 0,5$

**Ergebnis:**
Der Flächeninhalt wird für **$a = 1$** minimal. Der minimale Flächeninhalt beträgt **$0,5$ FE**.