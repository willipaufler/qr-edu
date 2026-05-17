# Extremwertproblem - Zahlenrätsel - Lösung

### a) Bestimmen von zwei Summanden mit maximalem Produkt

**1. Aufstellen der Bedingungen und der Zielfunktion:**

Die beiden Summanden seien $x$ und $y$. Das Produkt $P$ soll maximiert werden.
Hauptbedingung:
$$
\begin{aligned}
P(x, y) &= x \cdot y
\end{aligned}
$$

Nebenbedingung:
$$
\begin{aligned}
x + y = 60 \implies y = 60 - x
\end{aligned}
$$

Einsetzen der Nebenbedingung in die Hauptbedingung liefert die Zielfunktion:
$$
\begin{aligned}
P(x) = x \cdot (60 - x) = 60x - x^2
\end{aligned}
$$


**2. Bestimmung des Maximums:**

Um das Maximum zu berechnen, bilden wir die ersten beiden Ableitungen nach $x$:
$$
\begin{aligned}
P'(x) &= 60 - 2x \\\\
P''(x) &= -2
\end{aligned}
$$

Notwendige Bedingung für ein Extremum ist $P'(x) = 0$:
$$
\begin{aligned} 60 - 2x &= 0 \\\\ x &= 30 \end{aligned}$$

Hinreichende Bedingung prüfen:
$P''(30) = -2 < 0 \implies$ Es handelt sich um ein lokales Maximum.

**3. Berechnung des zweiten Summanden:**

Setzt man $x = 30$ in die umgestellte Nebenbedingung ein, erhält man:
$y = 60 - 30 = 30$

Die beiden gesuchten Summanden lauten somit $30$ und $30$. Ihr maximales Produkt beträgt $30 \cdot 30 = 900$.

### b) Zerlegung der Zahl 30 für ein maximales Produkt

**1. Aufstellen der Bedingungen und der Zielfunktion:**
Der erste Summand sei $x$ und der zweite Summand sei $y$ (mit $x, y > 0$). Das Produkt $P$ soll maximiert werden.
Hauptbedingung:
$$
\begin{aligned}
P(x, y) &= x \cdot y
\end{aligned}
$$

Nebenbedingung:
$$
\begin{aligned}
 x + y &= 30 \\\\ y &= 30 - x 
 \end{aligned}
 $$

Einsetzen von $y$ in die Hauptbedingung liefert die Zielfunktion:
$$
\begin{aligned}
P(x) &= x^2 \cdot (30 - x) \\\\ P(x) &= 30x^2 - x^3 
\end{aligned}
$$

**2. Bestimmung des Maximums:**
Wir bilden die ersten beiden Ableitungen der Zielfunktion:
$$
\begin{aligned}
P'(x) &= 60x - 3x^2 \\\\
P''(x) &= 60 - 6x
\end{aligned}
$$


Notwendige Bedingung für ein Extremum ist $P'(x) = 0$:
$$
\begin{aligned} 
60x - 3x^2 &= 0 \\\\ 
3x \cdot (20 - x) &= 0 
\end{aligned}
$$

Daraus ergeben sich die Nullstellen der Ableitung:
$x_1 = 0$ oder $x_2 = 20.$

Da die Summanden positiv sein müssen ($x > 0$), entfällt $x_1 = 0$.  
Wir prüfen $x_2 = 20$ mit der hinreichenden Bedingung:
$P''(20) = -60 < 0 \implies$ Es handelt sich um ein lokales Maximum.

**3. Berechnung des zweiten Summanden:**
Setzt man $x = 20$ in die nach $y$ umgestellte Nebenbedingung ein, erhält man:
$y = 30 - 20 = 10$

Die beiden gesuchten Summanden lauten somit $20$ (als erster Summand) und $10$ (als zweiter Summand). Das maximale Produkt beträgt $20^2 \cdot 10 = 400 \cdot 10 = 4000$.