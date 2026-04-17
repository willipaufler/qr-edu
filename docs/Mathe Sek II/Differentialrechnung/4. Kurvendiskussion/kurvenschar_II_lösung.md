# Kurvenschar II - Lösung

### a) Wendepunkt ermitteln
Ableitungen:
$$\begin{aligned}
f_a'(x) &= x^2 + 2ax + a^2 \\\\
f_a''(x) &= 2x + 2a \\\\
f_a'''(x) &= 2
\end{aligned}
$$
Notwendige Bedingung $f_a''(x) = 0$:
$$\begin{aligned}
2x + 2a &= 0 \\\\
x_W &= -a
\end{aligned}
$$
Nachweis: Da $f_a'''(-a) = 2 \neq 0$, liegt an der Stelle $x = -a$ immer ein Wendepunkt vor.
$y$-Koordinate:
$$\begin{aligned}
f_a(-a) &= \frac{1}{3}(-a)^3 + a(-a)^2 + a^2(-a) \\\\
&= -\frac{1}{3}a^3 + a^3 - a^3 \\\\
&= -\frac{1}{3}a^3
\end{aligned}
$$
Ergebnis: $W(-a \mid -\frac{1}{3}a^3)$.

### b) Ortskurve der Wendepunkte
1. $x = -a \implies a = -x$
2. Einsetzen in $y = -\frac{1}{3}a^3$:
$$\begin{aligned}
y &= -\frac{1}{3}(-x)^3 \\\\
y &= \frac{1}{3}x^3
\end{aligned}
$$
Ergebnis: Alle Wendepunkte liegen auf der Ortskurve $y = \frac{1}{3}x^3$.

### c) Nachweis der Nicht-Existenz von Extrempunkten
Notwendige Bedingung $f_a'(x) = 0$:
$$\begin{aligned}
x^2 + 2ax + a^2 &= 0
\end{aligned}
$$
Anwendung der binomischen Formel oder $p-q$-Formel:
$$\begin{aligned}
(x + a)^2 &= 0 \\\\
x_{1,2} &= -a
\end{aligned}
$$ 
Es gibt also für jedes $a$ nur **genau eine** potenzielle Extremstelle bei $x = -a$. 
Da dies aber gleichzeitig die Stelle des Wendepunkts ist (siehe Aufgabenteil a), handelt es sich hierbei um einen **Sattelpunkt** (Extremum zweiter Art), nicht um ein lokales Minimum oder Maximum.

**Sonderfall $a=0$:**  
Für $a=0$ lautet die Funktion $f_0(x) = \frac{1}{3}x^3$. Auch hier liegt bei $x=0$ lediglich ein Sattelpunkt vor. Somit hat die Schar für kein $a$ klassische Extrempunkte.