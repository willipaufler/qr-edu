# Tangente durch äußeren Punkt (ohne CAS) - Lösung

Gegeben ist die Funktion $f$ mit $f(x) = 2 \cdot e^{0{,}25x}$ und der Punkt $Q(2 \mid 0)$.

---

### 1. Ableitung bilden
Wir bestimmen zunächst die 1. Ableitung von $f(x)$ (unter Verwendung der Kettenregel):
$$
\begin{aligned}
f'(x) &= 2 \cdot 0{,}25 \cdot e^{0{,}25x} \\\\
&= 0{,}5 \cdot e^{0{,}25x}
\end{aligned}
$$

---

### 2. Ansatz mit allgemeinem Berührpunkt
Da der Punkt $Q$ nicht auf dem Graphen liegt, definieren wir einen allgemeinen Berührpunkt $P(u \mid f(u))$ auf dem Graphen:
$$
P\left(u \mid 2 \cdot e^{0{,}25u}\right)
$$

Die Steigung $m_t$ der Tangente in diesem Punkt ist einerseits die Ableitung an der Stelle $u$:
$$
\begin{aligned}
m_t &= f'(u) = 0{,}5 \cdot e^{0{,}25u}
\end{aligned}
$$

Andererseits lässt sich die Steigung der Geraden durch die Punkte $P$ und $Q(2 \mid 0)$ über das Steigungsdreieck ausdrücken:
$$
\begin{aligned}
m_t &= \frac{f(u) - 0}{u - 2} = \frac{2 \cdot e^{0{,}25u}}{u - 2}
\end{aligned}
$$

---

### 3. Gleichung für $u$ aufstellen und lösen
Wir setzen die beiden Terme für die Steigung $m_t$ einander gleich:
$$
\begin{aligned}
0{,}5 \cdot e^{0{,}25u} &= \frac{2 \cdot e^{0{,}25u}}{u - 2}
\end{aligned}
$$

Da $e^{0{,}25u} \neq 0$ für alle reellen Zahlen $u$ gilt, können wir die Gleichung durch $e^{0{,}25u}$ teilen:
$$
\begin{aligned}
0{,}5 &= \frac{2}{u - 2}
\end{aligned}
$$

Multiplikation mit $(u - 2)$:
$$
\begin{aligned}
0{,}5 \cdot (u - 2) &= 2 \\\\
0{,}5u - 1 &= 2 \\\\
0{,}5u &= 3 \\\\
u &= 6
\end{aligned}
$$

---

### 4. Berührpunkt und Tangentengleichung bestimmen
Wir setzen $u = 6$ in die Funktionsgleichung ein, um die $y$-Koordinate des Berührpunkts zu erhalten:
$$
\begin{aligned}
f(6) &= 2 \cdot e^{0{,}25 \cdot 6} \\\\
&= 2 \cdot e^{1{,}5}
\end{aligned}
$$
Der Berührpunkt ist $P\left(6 \mid 2e^{1{,}5}\right)$.

Nun berechnen wir die Tangentensteigung $m$ an der Stelle $u = 6$:
$$
\begin{aligned}
m = f'(6) &= 0{,}5 \cdot e^{0{,}25 \cdot 6} \\\\
&= 0{,}5 \cdot e^{1{,}5}
\end{aligned}
$$

Einsetzen von Steigung $m$ und dem Punkt $Q(2 \mid 0)$ (oder $P$) in die lineare Gleichung $y = m \cdot x + n$:
$$
\begin{aligned}
0 &= (0{,}5 \cdot e^{1{,}5}) \cdot 2 + n \\\\
0 &= e^{1{,}5} + n \\\\
n &= -e^{1{,}5}
\end{aligned}
$$

Die gesuchte Tangentengleichung lautet somit:
$$
\begin{aligned}
t(x) &= 0{,}5e^{1{,}5}x - e^{1{,}5}
\end{aligned}
$$
*(Alternativ ausgeklammert: $t(x) = e^{1{,}5} \cdot (0{,}5x - 1)$)*