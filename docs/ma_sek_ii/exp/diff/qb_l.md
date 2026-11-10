# Querbeet (ohne CAS) - Lösung

Gegeben ist die Funktion $f$ mit $f(x) = -ex + e^x$.

---

### Teilaufgabe a)

#### 1. Ableitungen bilden
$$
\begin{aligned}
f'(x) &= -e + e^x \\
f''(x) &= e^x
\end{aligned}
$$

#### 2. Notwendige Bedingung für Extremstellen: $f'(x) = 0$
$$
\begin{aligned}
-e + e^x &= 0 \\
e^x &= e \\
x &= 1
\end{aligned}
$$

#### 3. Hinreichende Bedingung prüfen: $f''(1) \neq 0$
$$
\begin{aligned}
f''(1) &= e^1 = e > 0 \quad \implies \text{Tiefpunkt bei } x = 1
\end{aligned}
$$

#### 4. y-Koordinate berechnen
$$
\begin{aligned}
f(1) &= -e \cdot 1 + e^1 \\
&= -e + e \\
&= 0
\end{aligned}
$$

Der Tiefpunkt des Graphen liegt bei **$T(1 \mid 0)$**.

---

### Teilaufgabe b)

#### 1. y-Koordinate des Berührpunkts $P(0 \mid f(0))$ bestimmen
$$
\begin{aligned}
f(0) &= -e \cdot 0 + e^0 \\\\
&= 0 + 1 \\\\
&= 1
\end{aligned}
$$
Der Berührpunkt ist somit $P(0 \mid 1)$.

#### 2. Steigung $m$ an der Stelle $x = 0$ berechnen
$$
\begin{aligned}
m = f'(0) &= -e + e^0 \\
&= -e + 1 \\
&= 1 - e
\end{aligned}
$$

#### 3. Tangentengleichung aufstellen
Da der Berührpunkt bei $x = 0$ den $y$-Achsenabschnitt $n = 1$ hat, lautet die Tangentengleichung:
$$
\begin{aligned}
t(x) &= (1 - e)x + 1
\end{aligned}
$$

---

### Teilaufgabe c)

Für die Spiegelung an der $y$-Achse gilt $g(x) = f(-x)$:
$$
\begin{aligned}
g(x) &= -e \cdot (-x) + e^{-x} \\\\
&= ex + e^{-x}
\end{aligned}
$$

Die zugehörige Funktionsgleichung lautet **$g(x) = ex + e^{-x}$** (bzw. $g(x) = ex + \frac{1}{e^x}$).