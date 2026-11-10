# Skipiste - Lösung

Gegeben ist die Funktion $f(x) = 275 \cdot e^{-(0{,}002x)^2} + 1000$ für $0 \le x \le 1000$.

---

### Teilaufgabe a)

Wir berechnen die Höhen am Anfang ($x = 0$) und am Ende ($x = 1000$):
$$
\begin{aligned}
f(0) &= 275 \cdot e^{-(0{,}002 \cdot 0)^2} + 1000 \\\\
&= 275 \cdot e^0 + 1000 \\\\
&= 275 \cdot 1 + 1000 = 1275
\end{aligned}
$$

$$
\begin{aligned}
f(1000) &= 275 \cdot e^{-(0{,}002 \cdot 1000)^2} + 1000 \\\\
&= 275 \cdot e^{-2^2} + 1000 \\\\
&= 275 \cdot e^{-4} + 1000 \\\\
&\approx 275 \cdot 0{,}0183 + 1000 \approx 5{,}03 + 1000 = 1005{,}03
\end{aligned}
$$

Die Höhendifferenz beträgt:
$$
\begin{aligned}
\Delta h &= |f(1000) - f(0)| = |1005{,}03 - 1275| = 269{,}97
\end{aligned}
$$
Die Höhendifferenz zwischen Beginn und Ende der Skipiste beträgt ca. **$270\text{ m}$**.

---

### Teilaufgabe b)

Das durchschnittliche Gefälle über die Gesamtlänge von $x = 0$ bis $x = 1000$ ist:
$$
\begin{aligned}
m_{\text{avg}} &= \frac{f(1000) - f(0)}{1000 - 0} \\\\
&= \frac{1005{,}03 - 1275}{1000} \\\\
&= \frac{-269{,}97}{1000} \\\\
&= -0{,}26997
\end{aligned}
$$
Das durchschnittliche Gefälle beträgt ca. **$-27\,\%$** (bzw. ein Gefälle von ca. $27\,\%$).

---

### Teilaufgabe c)

Um die Stelle mit der extremsten Steigung zu finden, bestimmen wir die 1. Ableitung von $f(x)$ (mit der Kettenregel):
$$
\begin{aligned}
f'(x) &= 275 \cdot e^{-(0{,}002x)^2} \cdot (-2 \cdot 0{,}002x \cdot 0{,}002) \\\\
&= 275 \cdot e^{-(0{,}002x)^2} \cdot (-0{,}000008x) \\\\
&= -0{,}0022x \cdot e^{-(0{,}002x)^2}
\end{aligned}
$$

Für die Extremwerte dieser Steigung bilden wir die 2. Ableitung $f''(x)$ und setzen sie gleich null (Produkt- und Kettenregel):
$$
\begin{aligned}
f''(x) &= -0{,}0022 \cdot e^{-(0{,}002x)^2} + (-0{,}0022x) \cdot e^{-(0{,}002x)^2} \cdot (-0{,}000008x) \\\\
&= e^{-(0{,}002x)^2} \cdot \left(-0{,}0022 + 0{,}0000000176x^2\right)
\end{aligned}
$$

Setzen $f''(x) = 0$ (da der Exponentialterm ungleich Null ist):
$$
\begin{aligned}
-0{,}0022 + 0{,}0000000176x^2 &= 0 \\\\
0{,}0000000176x^2 &= 0{,}0022 \\\\
x^2 &= \frac{0{,}0022}{0{,}0000000176} = 125000 \\\\
x &\approx \pm 353{,}55
\end{aligned}
$$

Da das Intervall $0 \le x \le 1000$ betrachtet wird, liegt die gesuchte Stelle bei **$x \approx 353{,}56\text{ m}$** (im negativen Gefällebereich betragsmäßig maximal).

---

### Teilaufgabe d)

Wir berechnen die Steigung an der Stelle $x \approx 353{,}55$:
$$
\begin{aligned}
f'(353{,}55) &= -0{,}0022 \cdot 353{,}55 \cdot e^{-(0{,}002 \cdot 353{,}55)^2} \\\\
&= -0{,}7778 \cdot e^{-0{,}5} \\\\
&\approx -0{,}7778 \cdot 0{,}6065 \\\\
&\approx -0{,}4717
\end{aligned}
$$

Der Betrag der Steigung ist $|m| \approx 0{,}4717$. Den Steigungswinkel $\alpha$ berechnen wir über den Arkustangens:
$$
\begin{aligned}
\tan(\alpha) &= 0{,}4717 \\\\
\alpha &= \arctan(0{,}4717) \approx 25{,}26^\circ
\end{aligned}
$$

Da der maximale Steigungswinkel ca. $25{,}3^\circ$ beträgt und somit **unter $30^\circ$** liegt, ist der Einsatz einer Seilwinde **nicht erforderlich**.