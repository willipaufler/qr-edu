# Logarithmische Kurvendiskussion (ohne CAS) - Lösung

Gegeben ist die Funktion $f(x) = x \cdot \ln(x) - x$ für $x > 0$.

---

### Teilaufgabe a)

* **Definitionsbereich:** Da der natürliche Logarithmus nur für positive Argumente definiert ist, lautet der Definitionsbereich:
  $$
  D_f = ]0; \infty[
  $$
* **Verhalten für $x \to \infty$:** 
  Wenn $x$ gegen unendlich strebt, wächst sowohl der Faktor $x$ als auch der Term $\ln(x)$ über alle Grenzen. Der Term $-x$ fällt dagegen ins Gewicht, wird aber vom wachsenden $x \cdot \ln(x)$ dominiert:
  $$
  \lim_{x \to \infty} (x \cdot \ln(x) - x) = \infty
  $$

---

### Teilaufgabe b)

Wir setzen den Funktionsterm gleich Null, um die Nullstellen zu berechnen:
$$
\begin{aligned}
x \cdot \ln(x) - x &= 0
\end{aligned}
$$

Wir klammern $x$ aus:
$$
\begin{aligned}
x \cdot (\ln(x) - 1) &= 0
\end{aligned}
$$

Nach dem Satz vom Nullprodukt muss mindestens ein Faktor null sein:
1. $x = 0$ (entfällt, da $0 \notin D_f$)
2. $\ln(x) - 1 = 0 \implies \ln(x) = 1 \implies x = e^1 = e$

Die Funktion besitzt genau eine Nullstelle bei **$x = e$** (bzw. den Punkt $(e \mid 0)$).

---

### Teilaufgabe c)

* **1. Ableitung bilden:**
  Wir leiten $f(x) = x \cdot \ln(x) - x$ mit der Produktregel ab ($u = x \implies u' = 1$ und $v = \ln(x) \implies v' = \frac{1}{x}$):
  $$
  \begin{aligned}
  f'(x) &= 1 \cdot \ln(x) + x \cdot \frac{1}{x} - 1 \\\\
  &= \ln(x) + 1 - 1 \\\\
  &= \ln(x)
  \end{aligned}
  $$

* **Notwendige Bedingung für Extremstellen ($f'(x) = 0$):**
  $$
  \begin{aligned}
  \ln(x) &= 0 \\\\
  x &= e^0 = 1
  \end{aligned}
  $$

* **Hinreichende Bedingung (2. Ableitung):**
  Wir bilden die zweite Ableitung (Ableitung von $\ln(x)$ ist $\frac{1}{x}$):
  $$
  \begin{aligned}
  f''(x) &= \frac{1}{x}
  \end{aligned}
  $$
  Einsetzen der Extremstelle $x = 1$:
  $$
  \begin{aligned}
  f''(1) &= \frac{1}{1} = 1 > 0
  \end{aligned}
  $$
  Da $f''(1) > 0$ gilt, liegt an der Stelle $x = 1$ ein **Tiefpunkt** vor.

* **y-Koordinate berechnen:**
  Wir setzen $x = 1$ in die ursprüngliche Funktionsgleichung ein:
  $$
  \begin{aligned}
  f(1) &= 1 \cdot \ln(1) - 1 \\\\
  &= 1 \cdot 0 - 1 \\\\
  &= -1
  \end{aligned}
  $$

Der Tiefpunkt des Graphen liegt somit bei **$T(1 \mid -1)$**.