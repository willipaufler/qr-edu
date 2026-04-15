# Quadratische Funktion - Lösung

### a) Bestimmen der Nullstellen und des Scheitelpunkts
**Nullstellen berechnen ($f(x) = 0$):**
$$
\begin{aligned}
0 &= x^2 + 4x \\\\
0 &= x \cdot (x + 4) \\\\
x_1 &= 0 \\\\
x_2 &= -4
\end{aligned}
$$

**Scheitelpunkt berechnen (Alternative 1: Symmetrie):**
Da Parabeln achsensymmetrisch zu ihrem Scheitelpunkt sind, liegt der $x$-Wert des Scheitelpunkts exakt in der Mitte der Nullstellen:
$$
\begin{aligned}
x_s &= \frac{x_1 + x_2}{2} = \frac{0 + (-4)}{2} = -2 \\\\
y_s &= f(-2) = (-2)^2 + 4 \cdot (-2) = 4 - 8 = -4
\end{aligned}
$$

**Scheitelpunkt berechnen (Alternative 2: Quadratische Ergänzung):**
Überführung der allgemeinen Form in die Scheitelpunktform:
$$
\begin{aligned}
f(x) &= x^2 + 4x \\\\
f(x) &= x^2 + 4x + \left(\frac{4}{2}\right)^2 - \left(\frac{4}{2}\right)^2 \\\\
f(x) &= (x^2 + 4x + 4) - 4 \\\\
f(x) &= (1 \cdot (x + 2))^2 - 4
\end{aligned}
$$
Aus der Scheitelpunktform $f(x) = a(x-x_s)^2 + y_s$ lässt sich der Scheitelpunkt $S(-2|-4)$ direkt ablesen.

### b) Angabe des Wertebereichs
Unter Voraussetzung von $D = \mathbb{R}$ und da die Parabel nach oben geöffnet ist, stellt der Scheitelpunkt das absolute Minimum dar.
$$
\begin{aligned}
W = \{y \in \mathbb{R} \mid y \geq -4\} \text{ bzw. } W = [-4; \infty)
\end{aligned}
$$

### c) Beschreiben des Monotonieverhaltens
Der Scheitelpunkt bei $x = -2$ trennt die Bereiche unterschiedlicher Monotonie:
$$
\begin{aligned}
\text{Für } x \in (-\infty; -2]: & \text{ streng monoton fallend} \\\\
\text{Für } x \in [-2; \infty): & \text{ streng monoton steigend}
\end{aligned}
$$