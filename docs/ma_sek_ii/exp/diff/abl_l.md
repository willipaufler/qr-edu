# Ableitungen (ohne CAS) - Lösung

Bestimmen Sie die erste Ableitung der folgenden Funktionen:

---

### Teilaufgabe a)

Gegeben ist $f_1(x) = e^{4x}$.

Mit der Kettenregel (äußere Ableitung mal innere Ableitung):
$$
\begin{aligned}
f_1'(x) &= e^{4x} \cdot 4 = 4e^{4x}
\end{aligned}
$$

---

### Teilaufgabe b)

Gegeben ist $f_2(x) = 2x \cdot e^x$.

Mit der Produktregel ($u = 2x \implies u' = 2$ und $v = e^x \implies v' = e^x$):
$$
\begin{aligned}
f_2'(x) &= 2 \cdot e^x + 2x \cdot e^x \\\\
&= 2(1 + x)e^x
\end{aligned}
$$

---

### Teilaufgabe c)

Gegeben ist $f_3(x) = x^2 e^{-2x}$.

Mit der Produktregel ($u = x^2 \implies u' = 2x$ und $v = e^{-2x} \implies v' = -2e^{-2x}$):
$$
\begin{aligned}
f_3'(x) &= 2x \cdot e^{-2x} + x^2 \cdot \left(-2e^{-2x}\right) \\\\
&= 2x(1 - x)e^{-2x}
\end{aligned}
$$

---

### Teilaufgabe d)

Gegeben ist $f_4(x) = \frac{x + 1}{e^x}$.

Mit der Quotientenregel ($u = x + 1 \implies u' = 1$ und $v = e^x \implies v' = e^x$):
$$
\begin{aligned}
f_4'(x) &= \frac{1 \cdot e^x - (x + 1) \cdot e^x}{(e^x)^2} \\\\
&= \frac{e^x \cdot (1 - x - 1)}{e^{2x}} \\\\
&= \frac{-x}{e^x} \quad (\text{bzw. } -x \cdot e^{-x})
\end{aligned}
$$

---

### Teilaufgabe e)

Gegeben ist $f_5(x) = e^{\sin(x)}$.

Mit der Kettenregel:
$$
\begin{aligned}
f_5'(x) &= e^{\sin(x)} \cdot \cos(x)
\end{aligned}
$$

---

### Teilaufgabe f)

Gegeben ist $f_6(x) = \sqrt{2x^2 + e^{-x}}$.

Mit der Kettenregel für Wurzeln:
$$
\begin{aligned}
f_6'(x) &= \frac{1}{2\sqrt{2x^2 + e^{-x}}} \cdot \left(4x - e^{-x}\right) \\\\
&= \frac{4x - e^{-x}}{2\sqrt{2x^2 + e^{-x}}}
\end{aligned}
$$

---

### Teilaufgabe g)

Gegeben ist $f_7(x) = \ln(3x + 3)$.

Mit der Kettenregel ($u = 3x + 3 \implies u' = 3$):
$$
\begin{aligned}
f_7'(x) &= \frac{1}{3x + 3} \cdot 3 \\\\
&= \frac{3}{3(x + 1)} \\\\
&= \frac{1}{x + 1}
\end{aligned}
$$

---

### Teilaufgabe h)

Gegeben ist $f_8(x) = x \cdot \ln(x)$.

Mit der Produktregel ($u = x \implies u' = 1$ und $v = \ln(x) \implies v' = \frac{1}{x}$):
$$
\begin{aligned}
f_8'(x) &= 1 \cdot \ln(x) + x \cdot \frac{1}{x} \\\\
&= \ln(x) + 1
\end{aligned}
$$