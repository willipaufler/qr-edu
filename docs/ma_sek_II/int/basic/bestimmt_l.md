# Bestimmte Integrale - Lösung

Hier sind die vollständigen Rechenwege im Detail:

### a) $\int_{1}^{2} (x^3 - 2x + 5) \, dx$
* **Stammfunktion:** $F(x)=\frac{1}{4}x^4 - x^2 + 5x$
* **Berechnung:**

\begin{align*}
\int_{1}^{2} (x^3 - 2x + 5) \, dx &= [\frac{1}{4}x^4 - x^2 + 5x]_1^2 \\
&= (\frac{1}{4} \cdot 2^4 - 2^2 + 5 \cdot 2) - (\frac{1}{4} \cdot 1^4 - 1^2 + 5 \cdot 1) \\
&= (4 - 4 + 10) - (0,25 - 1 + 5) \\
&= 10 - 4,25 \\
&= 5,75
\end{align*}

---

### b) $\int_{1}^{2} (\frac{3}{x^2} + x) \, dx$
* **Stammfunktion:** $F(x)=-\frac{3}{x} + \frac{1}{2}x^2$ (da $\frac{3}{x^2} = 3x^{-2}$)
* **Berechnung:**

\begin{align*}
\int_{1}^{2} (3x^{-2} + x) \, dx &= [-\frac{3}{x} + \frac{1}{2}x^2]_1^2 \\
&= (-\frac{3}{2} + \frac{1}{2} \cdot 4) - (-\frac{3}{1} + \frac{1}{2} \cdot 1) \\
&= (-1,5 + 2) - (-3 + 0,5) \\
&= 0,5 - (-2,5) \\
&= 3
\end{align*}

---

### c) $\int_{1}^{4} (\sqrt{x} + \frac{1}{\sqrt{x}}) \, dx$
* **Stammfunktion:** $F(x)=\frac{2}{3}x^{\frac{3}{2}} + 2x^{\frac{1}{2}}$
* **Berechnung:**

\begin{align*}
\int_{1}^{4} (x^{\frac{1}{2}} + x^{-\frac{1}{2}}) \, dx &= [\frac{2}{3}x\sqrt{x} + 2\sqrt{x}]_1^4 \\
&= (\frac{2}{3} \cdot 4 \cdot 2 + 2 \cdot 2) - (\frac{2}{3} \cdot 1 + 2 \cdot 1) \\
&= (\frac{16}{3} + 4) - (\frac{2}{3} + 2) \\
&= \frac{28}{3} - \frac{8}{3} = \frac{20}{3} \\
&\approx 6,67
\end{align*}

---

### d) $\int_{0}^{\pi} (3\sin(x) - \cos(x)) \, dx$
* **Stammfunktion:** $F(x)=-3\cos(x) - \sin(x)$
* **Berechnung:**

\begin{align*}
\int_{0}^{\pi} (3\sin(x) - \cos(x)) \, dx &= [-3\cos(x) - \sin(x)]_0^{\pi} \\
&= (-3\cos(\pi) - \sin(\pi)) - (-3\cos(0) - \sin(0)) \\
&= (-3 \cdot (-1) - 0) - (-3 \cdot 1 - 0) \\
&= 3 - (-3) \\
&= 6
\end{align*}

---

### e) $\int_{0}^{2} (0,5x - 1)^3 \, dx$
* **Stammfunktion:** $F(x)=\frac{1}{4 \cdot 0,5}(0,5x - 1)^4 = 0,5(0,5x - 1)^4$
* **Berechnung:**

\begin{align*}
\int_{0}^{2} (0,5x - 1)^3 \, dx &= [0,5(0,5x - 1)^4]_0^2 \\
&= (0,5(0,5 \cdot 2 - 1)^4) - (0,5(0,5 \cdot 0 - 1)^4) \\
&= (0,5 \cdot 0^4) - (0,5 \cdot (-1)^4) \\
&= 0 - 0,5 \\
&= -0,5
\end{align*}

---

### f) $\int_{1}^{2} \frac{1}{(x + 1)^3} \, dx$
* **Stammfunktion:** $F(x)=-\frac{1}{2}(x + 1)^{-2} = -\frac{1}{2(x+1)^2}$
* **Berechnung:**

\begin{align*}
\int_{1}^{2} (x + 1)^{-3} \, dx &= [-\frac{1}{2(x+1)^2}]_1^2 \\
&= (-\frac{1}{2(2+1)^2}) - (-\frac{1}{2(1+1)^2}) \\
&= (-\frac{1}{18}) - (-\frac{1}{8}) \\
&= -\frac{4}{72} + \frac{9}{72} \\
&= \frac{5}{72} \approx 0,069
\end{align*}