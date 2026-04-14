# Rotationsvolumen - Lösung

### Lösung zu a)
Gegeben ist $f(x) = \frac{1}{x} = x^{-1}$.

**1. Ableitung bilden:**
$$f'(x) = -1 \cdot x^{-2} = -\frac{1}{x^2}$$

**2. Punkt und Steigung an der Stelle $x=1$:**
$$
\begin{aligned}
f(1) &= \frac{1}{1} = 1 \implies P(1|1) \\\\
f'(1) &= -\frac{1}{1^2} = -1 \implies m = -1
\end{aligned}
$$

**3. Tangentengleichung berechnen ($y = mx + c$):**
$$
\begin{aligned}
1 &= -1 \cdot 1 + c \\\\
1 &= -1 + c \quad | +1 \\\\
c &= 2
\end{aligned}
$$
Die Tangentengleichung lautet: **$t(x) = -x + 2$**.

---

### Lösung zu b)
**1. Geometrische Form:**
Die Tangente $t(x) = -x + 2$ schneidet die $y$-Achse bei $2$ und die $x$-Achse bei $x=2$ (Nullstelle). Die Fläche im 1. Quadranten ist ein rechtwinkliges Dreieck. Bei Rotation um die $x$-Achse entsteht ein **gerader Kreiskegel**.

**2. Volumenberechnung per Integral:**
Die Integrationsgrenzen liegen zwischen $x=0$ und der Nullstelle $x=2$.
$$
\begin{aligned}
V &= \pi \cdot \int_{0}^{2} (-x + 2)^2 \, dx \\\\
  &= \pi \cdot \int_{0}^{2} (x^2 - 4x + 4) \, dx \\\\
  &= \pi \cdot \left[ \frac{1}{3}x^3 - 2x^2 + 4x \right]_{0}^{2} \\\\
  &= \pi \cdot \left( \left( \frac{1}{3} \cdot 8 - 2 \cdot 4 + 4 \cdot 2 \right) - 0 \right) \\\\
  &= \pi \cdot \left( \frac{8}{3} - 8 + 8 \right) \\\\
  &= \mathbf{\frac{8}{3}\pi}
\end{aligned}
$$

---

### Lösung zu c) (Kurzverifikation)
Allgemeine Tangente an $f(x)$ bei $x=a$:
$$
\begin{aligned}
t_a(x) &= f'(a)(x-a) + f(a) \\\\
       &= -\frac{1}{a^2}(x-a) + \frac{1}{a} \\\\
       &= -\frac{1}{a^2}x + \frac{1}{a} + \frac{1}{a} = -\frac{1}{a^2}x + \frac{2}{a}
\end{aligned}
$$
Die Nullstelle liegt bei $x=2a$. Das Volumen berechnet sich zu:
$$
\begin{aligned}
V(a) &= \pi \int_{0}^{2a} \left(-\frac{1}{a^2}x + \frac{2}{a}\right)^2 \, dx \\\\
     &= \dots = \frac{8}{3a}\pi
\end{aligned}
$$
Da $a$ im Nenner steht, bewirkt eine Verdopplung von $a$ eine Halbierung des Volumens $V(2a) = \frac{1}{2} V(a)$. Die Aussage ist **wahr**.