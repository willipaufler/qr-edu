# Achsensymmetrische Funktion - Lösung

### a) Mathematische Bedingungen
Aufgrund der Achsensymmetrie zur y-Achse wählen wir den Ansatz:
$$
\begin{aligned}
f(x) &= ax^4 + cx^2 + e \\\\
f'(x) &= 4ax^3 + 2cx
\end{aligned}
$$

Daraus ergeben sich folgende Bedingungen:

1.  **Schnittpunkt y-Achse:** $f(0) = -4$
2.  **Punkt des Hochpunkts:** $f(2) = 4$
3.  **Waagerechte Tangente:** $f'(2) = 0$

### b) Ermittlung der Funktionsgleichung

**Schritt 1: Parameter $e$ bestimmen**
Aus $f(0) = -4$ folgt direkt:
$$
\begin{aligned}
a \cdot 0^4 + c \cdot 0^2 + e &= -4 \\\\
e &= -4
\end{aligned}
$$

**Schritt 2: Gleichungssystem für $a$ und $c$ aufstellen**
Wir setzen $e = -4$ und den Punkt $H(2|4)$ in $f(x)$ sowie $x=2$ in $f'(x)$ ein:

I.  $f(2) = 4 \implies a \cdot 2^4 + c \cdot 2^2 - 4 = 4$  
II. $f'(2) = 0 \implies 4a \cdot 2^3 + 2c \cdot 2 = 0$

Vereinfacht:

I.  $16a + 4c = 8$  
II. $32a + 4c = 0$

**Schritt 3: Gleichungssystem lösen**
Subtrahiere Gleichung I von Gleichung II:
$$
\begin{aligned}
(32a + 4c) - (16a + 4c) &= 0 - 8 \\\\
16a &= -8 \\\\
a &= -0,5
\end{aligned}
$$

Setze $a = -0,5$ in Gleichung II ein:
$$
\begin{aligned}
32 \cdot (-0,5) + 4c &= 0 \\\\
-16 + 4c &= 0 \\\\
4c &= 16 \\\\
c &= 4
\end{aligned}
$$

**Ergebnis:**
Die gesuchte Funktionsgleichung lautet:
$$
\begin{aligned}
f(x) = -0,5x^4 + 4x^2 - 4
\end{aligned}
$$