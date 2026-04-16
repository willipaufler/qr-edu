# Wendepunkte - Lösung

### a) Bestimmen der Wendepunkte von $f(x) = x^3 + 6x^2 - 10x$
Ableitungen bilden:
$$\begin{aligned}
f'(x) &= 3x^2 + 12x - 10 \\\\
f''(x) &= 6x + 12 \\\\
f'''(x) &= 6
\end{aligned}
$$
Notwendige Bedingung $f''(x) = 0$:
$$\begin{aligned}
6x + 12 &= 0 \\\\
6x &= -12 \\\\
x_w &= -2
\end{aligned}
$$
Art des Wendepunktes ($f'''(-2) = 6 > 0$):
$f'''(-2) = 6 > 0 \implies$ Rechts-Links-Wendepunkt (W)
Punktkoordinaten: $f(-2) = (-2)^3 + 6(-2)^2 - 10(-2) = -8 + 24 + 20 = 36 \implies W(-2|36)$.

Wendetangente $t(x) = m \cdot x + n$:
Steigung $m = f'(-2) = 3(-2)^2 + 12(-2) - 10 = 12 - 24 - 10 = -22$.
$$\begin{aligned}
y &= m \cdot x + n \\\\
36 &= -22 \cdot (-2) + n \\\\
36 &= 44 + n \\\\
n &= -8
\end{aligned}
$$
Gleichung: $t(x) = -22x - 8$

### b) Bestimmen der Wendepunkte von $f(x) = x - 6x^{-1} + 10x^{-2}$
Ableitungen bilden:
$$\begin{aligned}
f'(x) &= 1 + 6x^{-2} - 20x^{-3} \\\\
f''(x) &= -12x^{-3} + 60x^{-4} \\\\
f'''(x) &= 36x^{-4} - 240x^{-5}
\end{aligned}
$$
Notwendige Bedingung $f''(x) = 0$:
$$\begin{aligned}
-\frac{12}{x^3} + \frac{60}{x^4} &= 0 \quad | \cdot x^4 \\\\
-12x + 60 &= 0 \\\\
12x &= 60 \\\\
x_w &= 5
\end{aligned}
$$
Art des Wendepunktes ($f'''(5) = 36 \cdot 5^{-4} - 240 \cdot 5^{-5} = 0,0576 - 0,0768 = -0,0192 < 0$):
$f'''(5) < 0 \implies$ Links-Rechts-Wendepunkt (W)
Punktkoordinaten: $f(5) = 5 - \frac{6}{5} + \frac{10}{25} = 5 - 1,2 + 0,4 = 4,2 \implies W(5|4,2)$.

Wendetangente:
Steigung $m = f'(5) = 1 + \frac{6}{25} - \frac{20}{125} = 1 + 0,24 - 0,16 = 1,08$.
$$\begin{aligned}
4,2 &= 1,08 \cdot 5 + n \\\\
4,2 &= 5,4 + n \\\\
n &= -1,2
\end{aligned}
$$
Gleichung: $t(x) = 1,08x - 1,2$

### c) Bestimmen der Wendepunkte von $f(x) = \frac{1}{2}x^4 + x^3$
Ableitungen bilden:
$$\begin{aligned}
f'(x) &= 2x^3 + 3x^2 \\\\
f''(x) &= 6x^2 + 6x \\\\
f'''(x) &= 12x + 6
\end{aligned}
$$
Notwendige Bedingung $f''(x) = 0$:
$$\begin{aligned}
6x^2 + 6x &= 0 \\\\
6x(x + 1) &= 0 \\\\
x_{w1} &= 0, \quad x_{w2} = -1
\end{aligned}
$$
Art der Wendepunkte:

* $f'''(0) = 6 > 0 \implies$ Rechts-Links-Wendepunkt ($W_1$)
* $f'''(-1) = -12 + 6 = -6 < 0 \implies$ Links-Rechts-Wendepunkt ($W_2$)

**Besonderheit bei $W_1$:**  
Da zusätzlich $f'(0) = 0$ gilt, ist $W_1(0|0)$ ein Wendepunkt mit waagerechter Tangente, also ein **Sattelpunkt**.

Punktkoordinaten und Tangenten:

1. $W_1(0|0)$: $m = f'(0) = 0 \implies t_1(x) = 0$
2. $W_2(-1|-0,5)$: $m = f'(-1) = 2(-1)^3 + 3(-1)^2 = -2 + 3 = 1$.
$$\begin{aligned}
-0,5 &= 1 \cdot (-1) + n \\\\
-0,5 &= -1 + n \\\\
n &= 0,5
\end{aligned}
$$
Gleichung: $t_2(x) = x + 0,5$