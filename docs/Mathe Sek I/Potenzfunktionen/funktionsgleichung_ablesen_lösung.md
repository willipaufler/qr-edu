# Funktionsgleichung ablesen - Lösung



#### 1. Bestimmung von $f(x)$ (Grad 3)
Der Sattelpunkt liegt bei $S(0|1)$. Die Form ist $f(x) = a\cdot x+^3 + 1$.
Ein weiterer Punkt (z.B. der Punkt bei $P(2|-1)$) hilft, $a$ zu bestimmen:

\begin{align*}
-1 &= a\cdot 2^3 + 1 \\
-2 &= 8\cdot a \\
a &= -\frac{1}{4}
\end{align*}

**Gleichung:** $f(x) = -\frac{1}{4}x^3 + 1$

* **Definitionsbereich:** $D = \mathbb{R}$
* **Wertebereich:** $W = \mathbb{R}$

#### 2. Bestimmung von $g(x)$ (Exponent -2)
Die senkrechte Asymptote liegt bei $x = -1$, die waagerechte bei $y = 1$.
Form: $g(x) = \frac{a}{(x + 1)^2} + 1$.
Punktprobe mit $Q(0|2)$: 

\begin{align*}
2 &= \frac{a}{(0 + 1)^2} + 1 \\\
1 &= \frac{a}{1} \\
a &= 1
\end{align*}

**Gleichung:** $g(x) = \frac{1}{(x + 1)^2} + 1$

* **Definitionsbereich:** $D = \mathbb{R} \setminus \{-1\}$
* **Wertebereich:** $W = \{y \in \mathbb{R} \mid y > 1\}$

#### 3. Funktion $h(x)$ und Schnittpunkte
Die Funktion $y = x^4$ wird um 2 nach links und 1 nach oben verschoben:
**Gleichung:** $h(x) = (x + 2)^4 + 1$

**Schnittpunkte mit $f(x)$:** Ansatz

$$
h(x) = f(x)
$$

Der CAS liefert:

* $x_1=-4$, mit $f(x_1)=17$ folgt der erste Schnittpunkt $S_1(-4|17)$
* $x_2\approx-1,1929$, mit $f(x_2)\approx 1,4244$ folgt der zweite Schnittpunkt $S_2(-1,1929|1,4244)$

