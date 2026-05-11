# Kurvenschar I - Lösung

### a) Extrempunkt bestimmen
Ableitungen:
$$\begin{aligned}
f_a'(x) &= 2x + a \\\\
f_a''(x) &= 2
\end{aligned}
$$
Notwendige Bedingung $f_a'(x) = 0$:
$$\begin{aligned}
2x + a &= 0 \\\\
2x &= -a \\\\
x_E &= -\frac{1}{2}a
\end{aligned}
$$
Art des Extrempunkts:
Da $f_a''(x) = 2 > 0$ für alle $x$, handelt es sich immer um einen **Tiefpunkt**.

$y$-Koordinate:
$$\begin{aligned}
f_a(-\frac{1}{2}a) &= (-\frac{1}{2}a)^2 + a \cdot (-\frac{1}{2}a) + a \\\\
&= \frac{1}{4}a^2 - \frac{1}{2}a^2 + a \\\\
&= -\frac{1}{4}a^2 + a
\end{aligned}
$$
Ergebnis: $T(-\frac{1}{2}a \mid -\frac{1}{4}a^2 + a)$.

### b) Nachweis des gemeinsamen Punktes $P(-1|1)$
Wir setzen $x = -1$ in die Schargleichung ein:
$$\begin{aligned}
f_a(-1) &= (-1)^2 + a \cdot (-1) + a \\\\
&= 1 - a + a \\\\
&= 1
\end{aligned}
$$
Da das Ergebnis $1$ unabhängig vom Parameter $a$ ist, liegt der Punkt $P(-1|1)$ auf jedem Graphen der Schar.

### c) Allgemeine Tangentengleichung an $P$
1. Steigung $m$ berechnen:
$$\begin{aligned}
m &= f_a'(-1) = 2 \cdot (-1) + a \\\\
m &= a - 2
\end{aligned}
$$
2. $n$ bestimmen mit $y = m \cdot x + n$:
$$\begin{aligned}
1 &= (a - 2) \cdot (-1) + n \\\\
1 &= -a + 2 + n \\\\
n &= a - 1
\end{aligned}
$$
Ergebnis: Die allgemeine Tangentengleichung lautet $t_a(x) = (a - 2)x + a - 1$.