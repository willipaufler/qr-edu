# Punktsymmetrische Funktion - Lösung

### a) Mathematische Bedingungen
Da der Wendepunkt im Ursprung liegt, ist die Funktion punktsymmetrisch zum Ursprung. 
Allgemeiner Ansatz:
$$
\begin{aligned}
f(x) &= ax^3 + cx \\\\
f'(x) &= 3ax^2 + c
\end{aligned}
$$

Aus dem Aufgabentext ergeben sich folgende Bedingungen:
1.  **Wendetangente:** Die Steigung der Tangente $y = -3x$ ist $-3$. Da der Wendepunkt bei $x=0$ liegt, gilt:
    $f'(0) = -3$
2.  **Nullstelle:** Der Graph schneidet die x-Achse bei $x=2$:
    $f(2) = 0$

### b) Ermittlung der Funktionsgleichung

**Schritt 1: Parameter $c$ bestimmen**
Wir setzen $x=0$ in die erste Ableitung ein:
$$
\begin{aligned}
f'(0) &= -3 \\\\
3a(0)^2 + c &= -3 \\\\
c &= -3
\end{aligned}
$$

**Schritt 2: Parameter $a$ bestimmen**
Wir nutzen die Nullstelle $f(2) = 0$ mit dem bereits bekannten $c = -3$:
$$
\begin{aligned}
f(2) &= 0 \\\\
a \cdot 2^3 + (-3) \cdot 2 &= 0 \\\\
8a - 6 &= 0 \\\\
8a &= 6 \\\\
a &= \frac{6}{8} = \frac{3}{4}
\end{aligned}
$$

**Ergebnis:**
Die gesuchte Funktionsgleichung lautet:
$$
\begin{aligned}
f(x) = \frac{3}{4}x^3 - 3x
\end{aligned}
$$