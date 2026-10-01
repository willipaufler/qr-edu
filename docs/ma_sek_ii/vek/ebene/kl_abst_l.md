# Lösung – Ebenenschar mit kleinstem Abstand

## Teil a) Nachweis, dass $P$ in keiner Scharebene liegt

Einsetzen von $P(0,75 \mid 1 \mid 0)$ in $E_k$:
$$
\begin{aligned}
k \cdot 0,75 + \sqrt{1 - k^2} \cdot 1 + 3 \cdot 0 = 4 \\\\
\frac{3}{4}k + \sqrt{1 - k^2} = 4 \\\\
\sqrt{1 - k^2} = 4 - \frac{3}{4}k
\end{aligned}
$$

**Abschätzung für $k \in [-1, 1]$:**

* **Linke Seite:** Da $k^2 \ge 0$, gilt $\sqrt{1 - k^2} \le 1$.
* **Rechte Seite:** Da $k \le 1$, ist $\frac{3}{4}k \le 0,75$. Daher gilt $4 - \frac{3}{4}k \ge 3,25$.

Da die linke Seite höchstens $1$ und die rechte Seite mindestens $3,25$ beträgt, existiert kein $k \in [-1, 1]$, welches die Gleichung erfüllt. Punkt $P$ liegt somit in keiner Ebene der Schar $E_k$.

---

## Teil b) Ebene mit geringstem Abstand zu $P$

### 1. Betrag des Normalenvektors
$$
\begin{aligned}
|\vec{n}_k| = \sqrt{k^2 + \left(\sqrt{1 - k^2}\right)^2 + 3^2} = \sqrt{k^2 + 1 - k^2 + 9} = \sqrt{10}
\end{aligned}
$$

### 2. Abstandsfunktion $d(k)$
Mit der Hesseschen Normalenform ergibt sich:
$$
\begin{aligned}
d(k) = \frac{\left|\frac{3}{4}k + \sqrt{1 - k^2} - 4\right|}{\sqrt{10}}
\end{aligned}
$$

Aus Teil a) ist bekannt, dass $\frac{3}{4}k + \sqrt{1 - k^2} \le 1,75 < 4$. Daher ist der Term im Betrag stets negativ und es gilt:
$$
\begin{aligned}
d(k) = \frac{4 - \left(\frac{3}{4}k + \sqrt{1 - k^2}\right)}{\sqrt{10}}
\end{aligned}
$$

Der Abstand $d(k)$ ist genau dann minimal, wenn der Hilfsterm $f(k) = \frac{3}{4}k + \sqrt{1 - k^2}$ maximal wird.

### 3. Extremwertberechnung für $f(k)$
Ableitung bilden:
$$
\begin{aligned}
f'(k) = \frac{3}{4} + \frac{1}{2\sqrt{1 - k^2}} \cdot (-2k) = \frac{3}{4} - \frac{k}{\sqrt{1 - k^2}}
\end{aligned}
$$

**Notwendige Bedingung $f'(k) = 0$:**
$$
\begin{aligned}
\frac{3}{4} - \frac{k}{\sqrt{1 - k^2}} = 0 \implies \frac{k}{\sqrt{1 - k^2}} = \frac{3}{4}
\end{aligned}
$$

Quadrieren (beide Seiten sind positiv, da $k > 0$):
$$
\begin{aligned}
\frac{k^2}{1 - k^2} = \frac{9}{16} \\\\
16k^2 = 9(1 - k^2) \\\\
16k^2 = 9 - 9k^2 \\\\
25k^2 = 9 \implies k^2 = \frac{9}{25} \implies k = 0,6 \quad (\text{da } k > 0)
\end{aligned}
$$

**Hinreichende Bedingung $f''(k) < 0$):**
Bilden der 2. Ableitung von $f'(k) = \frac{3}{4} - k(1 - k^2)^{-\frac{1}{2}}$ mit Produkt- und Kettenregel:
$$
\begin{aligned}
f''(k) = -\frac{1}{(1 - k^2)^{\frac{3}{2}}}
\end{aligned}
$$

Einsetzen von $k = 0,6$:
$$
\begin{aligned}
f''(0,6) = -\frac{1}{(1 - 0,36)^{\frac{3}{2}}} = -\frac{1}{(0,64)^{\frac{3}{2}}} = -\frac{1}{0,512} \approx -1,953 < 0 \implies \text{Maximum}
\end{aligned}
$$



### 4. Einsetzen des optimalen Parameters
Für $k = 0,6$ berechnet sich der Koeffizient vor $y$:
$$
\begin{aligned}
\sqrt{1 - 0,6^2} = \sqrt{1 - 0,36} = \sqrt{0,64} = 0,8
\end{aligned}
$$

Die Ebene der Schar mit dem geringsten Abstand zu $P$ lautet somit:
$$
\begin{aligned}
E_{0,6}: 0,6x + 0,8y + 3z = 4 \quad \text{bzw.} \quad 3x + 4y + 15z = 20
\end{aligned}
$$