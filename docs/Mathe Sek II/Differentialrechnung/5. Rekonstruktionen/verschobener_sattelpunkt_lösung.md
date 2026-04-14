# Wanted - Verschobener Sattelpunkt - Lösung

### a) Mathematische Bedingungen
Die allgemeine Funktionsgleichung und ihre Ableitungen lauten:

$$\begin{aligned}
f(x) &= ax^3 + bx^2 + cx + d \\\\
f'(x) &= 3ax^2 + 2bx + c \\\\
f''(x) &= 6ax + 2b
\end{aligned}$$

Aus dem Aufgabentext ergeben sich folgende vier Bedingungen:

1. $f(0) = 0$ (verläuft durch den Ursprung)
2. $f(-1) = -\frac{1}{3}$ (Punkt des Sattelpunkts)
3. $f'(-1) = 0$ (waagerechte Tangente im Sattelpunkt)
4. $f''(-1) = 0$ (Wendepunkteigenschaft des Sattelpunkts)

### b) Ermittlung der Funktionsgleichung
Wir setzen die Bedingungen in die Gleichungen ein:

1. $f(0) = 0 \implies d = 0$
2. $f''(-1) = 0 \implies 6a(-1) + 2b = 0 \implies -6a + 2b = 0 \implies b = 3a$
3. $f'(-1) = 0 \implies 3a(-1)^2 + 2b(-1) + c = 0 \implies 3a - 2b + c = 0$
4. $f(-1) = -\frac{1}{3} \implies a(-1)^3 + b(-1)^2 + c(-1) + d = -\frac{1}{3} \implies -a + b - c = -\frac{1}{3}$

Nutze $b = 3a$ in Bedingung 3:
$$
\begin{aligned}
3a - 2(3a) + c &= 0 \\\\
3a - 6a + c &= 0 \\\\
-3a + c &= 0 \implies c = 3a
\end{aligned}
$$

Setze $b=3a$ und $c=3a$ in Bedingung 4 ein:
$$
\begin{aligned}
-a + (3a) - (3a) &= -\frac{1}{3} \\\\
-a &= -\frac{1}{3} \\\\
a &= \frac{1}{3}
\end{aligned}
$$

Daraus folgen:
$$
\begin{aligned}
b &= 3 \cdot \frac{1}{3} = 1 \\\\
c &= 3 \cdot \frac{1}{3} = 1
\end{aligned}
$$

Die gesuchte Funktionsgleichung lautet:
$$ f(x) = \frac{1}{3}x^3 + x^2 + x $$