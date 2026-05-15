# Wasserfontäne - Lösung

### Option 1: Allgemeiner Ansatz
Zuerst definieren wir die allgemeine Funktion und ihre Ableitung:
$$
\begin{aligned}
f(x) &= ax^2 + bx + c \\\\
f'(x) &= 2ax + b
\end{aligned}
$$

Aus dem Sachkontext entnehmen wir folgende Bedingungen (mit der unbekannten Scheitelstelle $x_s$):

1. $f(0) = 0,25$
2. $f(0,5) = 0$
3. $f(x_s) = 0,45$
4. $f'(x_s) = 0$

---


Man gibt das Gleichungssystem direkt in das CAS ein:

**Ergebnis:** $a = -5; b = 2; c = 0,25; x_s = 0,2$

### Option 2: Ansatz über die Scheitelpunktform
Hier nutzt man die Scheitelpunktform $f(x) = a(x - x_s)^2 + y_s$. Da die maximale Höhe $y_s = 0,45$ bekannt ist, reduziert sich der Ansatz auf:
$$
\begin{aligned}
f(x) = a(x - x_s)^2 + 0,45
\end{aligned}
$$

Nun müssen nur noch die zwei bekannten Punkte eingesetzt werden, um ein System für $a$ und $x_s$ zu erhalten:

1. $f(0) = 0,25 \implies 0,25 = a(0 - x_s)^2 + 0,45$
2. $f(0,5) = 0 \implies 0 = a(0,5 - x_s)^2 + 0,45$


**Ergebnis:** $a = -5; x_s = 0,2$

---

### Ergebnis
Die gesuchte Funktionsgleichung lautet:
$$
\begin{aligned}
f(x) = -5x^2 + 2x + 0,25 \quad \text{ oder }\quad  f(x) = -5(x - 0,2)^2 + 0,45
\end{aligned}
$$