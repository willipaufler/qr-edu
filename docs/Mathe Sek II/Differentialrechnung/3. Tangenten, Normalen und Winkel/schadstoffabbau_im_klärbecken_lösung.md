# Schadstoffabbau im Klärbecken - Lösung

### a) Konzentration zum Zeitpunkt $t_0 = 4$
Wir berechnen den Funktionswert an der Stelle $4$:
$$
\begin{aligned}
f(4) &= \frac{200}{4+1} \\\\
f(4) &= \frac{200}{5} = 40
\end{aligned}
$$
**Ergebnis:** Zum Zeitpunkt des Katalysatorzusatzes beträgt die Konzentration $40$ mg/l.

---

### b) Lineare Gleichung für den weiteren Verlauf (Tangente)
Zuerst bilden wir die Ableitung von $f(t) = 200 \cdot (t+1)^{-1}$:
$$
\begin{aligned}
f'(t) &= -200 \cdot (t+1)^{-2} \cdot 1 \\\\
f'(t) &= -\frac{200}{(t+1)^2}
\end{aligned}
$$

**Bedingungen für die Tangente $t(t) = m \cdot t + c$:**

**I: Gemeinsamer Anstieg ($m = f'(4)$)**
$$
\begin{aligned}
m &= -\frac{200}{(4+1)^2} \\\\
m &= -\frac{200}{25} = -8
\end{aligned}
$$
Die Abbaurate beträgt ab jetzt konstant $8$ mg/(l·h).

**II: Gemeinsamer Punkt ($B(4 | 40)$)**
Wir setzen den Punkt in die Geradengleichung ein, um $c$ zu bestimmen:
$$
\begin{aligned}
40 &= -8 \cdot 4 + c \\\\
40 &= -32 + c \\\\
c &= 72
\end{aligned}
$$

**Ergebnis:** Die Gleichung für den weiteren Konzentrationsverlauf lautet $t(t) = -8t + 72$.

---

### c) Zeitpunkt der Schadstofffreiheit
Wir suchen die Nullstelle der Tangente:
$$
\begin{aligned}
0 &= -8t + 72 \\\\
8t &= 72 \\\\
t &= 9
\end{aligned}
$$

**Ergebnis:** Das Becken ist nach insgesamt $9$ Stunden (also $5$ Stunden nach Zusatz des Katalysators) schadstofffrei.