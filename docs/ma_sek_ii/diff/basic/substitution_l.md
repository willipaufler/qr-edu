# Substitutionsmethode - Lösung

### a) Berechnung der Nullstellen von $f(x) = x^4 - 10x^2 + 9$
**1. Substitution:**
Setze $u = x^2$. Daraus folgt $u^2 = x^4$.
$$
\begin{aligned}
u^2 - 10u + 9 &= 0
\end{aligned}
$$
**2. Lösung der quadratischen Gleichung ($pq$-Formel):**
$$
\begin{aligned}
u_{1,2} &= 5 \pm \sqrt{(-5)^2 - 9} \\\\
u_{1,2} &= 5 \pm \sqrt{16} \\\\
u_{1,2} &= 5 \pm 4 \\\\
u_1 = 9&; \quad u_2 = 1
\end{aligned}
$$
**3. Resubstitution ($x = \pm \sqrt{u}$):**
$$
\begin{aligned}
x^2 = 9 &\Rightarrow x_1 = 3; \quad x_2 = -3 \\\\
x^2 = 1 &\Rightarrow x_3 = 1; \quad x_4 = -1
\end{aligned}
$$
Die Nullstellen sind $L = \{-3; -1; 1; 3\}$.

---

### b) Berechnung der Nullstellen von $f(x) = x^5 - 20x^3 + 64x$
**1. Ausklammern:**
Aus der Gleichung $0 = x^5 - 20x^3 + 64x$ lässt sich ein $x$ ausklammern, es gilt:
$$
\begin{aligned}
0&=x^5 - 20x^3 + 64x \\\\
&=x(x^4 - 20x^2 + 64)
\end{aligned}
$$

Ein Produkt ist genau dann Null, wenn mindestens einer der Faktoren Null ist. Die erste Nullstelle lautet daher $x=0$.  
Die übrigen Nullstellen erhalten wir, indem wir den Term in der Klammer Null setzen.

**2. Substitution:**
Setze $u = x^2$.
$$
\begin{aligned}
u^2 - 20u + 64 &= 0
\end{aligned}
$$
**3. Lösung der quadratischen Gleichung:**
$$
\begin{aligned}
u_{1,2} &= 10 \pm \sqrt{(-10)^2 - 64} \\\\
u_{1,2} &= 10 \pm \sqrt{36} \\\\
u_{1,2} &= 10 \pm 6 \\\\
u_1 = 16&; \quad u_2 = 4
\end{aligned}
$$
**4. Resubstitution:**
$$
\begin{aligned}
x^2 = 16 &\Rightarrow x_1 = 4; \quad x_2 = -4 \\\\
x^2 = 4 &\Rightarrow x_3 = 2; \quad x_4 = -2
\end{aligned}
$$

Die Nullstellen sind $L = \{-4; -2; 0; 2; 4\}$.