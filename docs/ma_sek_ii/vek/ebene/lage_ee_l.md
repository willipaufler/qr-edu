# Lösung – Lagebeziehung Ebene-Ebene

## Teil a)

### 1. Koordinatengleichungen aufstellen

**Ebene $E_{ABC}$:**

$$
\begin{aligned}
\vec{AB} = \begin{pmatrix} 2 \\ 0 \\ -2 \end{pmatrix}, \quad \vec{AC} = \begin{pmatrix} 0 \\ 5 \\ 0 \end{pmatrix} \\
\vec{n}_1 = \begin{pmatrix} 2 \\ 0 \\ -2 \end{pmatrix} \times \begin{pmatrix} 0 \\ 5 \\ 0 \end{pmatrix} = \begin{pmatrix} 10 \\ 0 \\ 10 \end{pmatrix} \quad \implies \text{gewählt: } \vec{n}_1 = \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix}
\end{aligned}
$$

Einsetzen von $A(0 \mid 1 \mid -1)$:
$$
\begin{aligned}
1(0) + 0(1) + 1(-1) = -1 \implies E_{ABC}: x_1 + x_3 = -1
\end{aligned}
$$

**Ebene $E_{DEF}$:**

$$
\begin{aligned}
\vec{DE} = \begin{pmatrix} 0 \\ 1 \\ 2 \end{pmatrix}, \quad \vec{DF} = \begin{pmatrix} 1 \\ 3 \\ 3 \end{pmatrix} \\
\vec{n}_2 = \begin{pmatrix} 0 \\ 1 \\ 2 \end{pmatrix} \times \begin{pmatrix} 1 \\ 3 \\ 3 \end{pmatrix} = \begin{pmatrix} -3 \\ 2 \\ -1 \end{pmatrix}
\end{aligned}
$$

Einsetzen von $D(1 \mid 0 \mid -2)$:
$$
\begin{aligned}
-3(1) + 2(0) - 1(-2) = -1 \implies E_{DEF}: -3x_1 + 2x_2 - x_3 = -1
\end{aligned}
$$

---

### 2. Lagebeziehung & Schnittwinkel

Da $\vec{n}_1 = \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix}$ und $\vec{n}_2 = \begin{pmatrix} -3 \\ 2 \\ -1 \end{pmatrix}$ keine Vielfachen voneinander sind, **schneiden** sich die Ebenen.

**Schnittwinkel $\alpha$:**
$$
\begin{aligned}
\cos(\alpha) = \frac{|\vec{n}_1 \cdot \vec{n}_2|}{|\vec{n}_1| \cdot |\vec{n}_2|} = \frac{2}{\sqrt{7}} \approx 0,7559 \\\\
\alpha = \arccos\left(\frac{2}{\sqrt{7}}\right) \approx 40,89^\circ
\end{aligned}
$$

---

### 3. Schnittgerade $s$

Aus $E_{ABC}$ folgt $x_3 = -1 - x_1$. Einsetzen in $E_{DEF}$:
$$
\begin{aligned}
-3x_1 + 2x_2 - (-1 - x_1) = -1 \\\\
-2x_1 + 2x_2 + 1 = -1 \\\\
2x_2 = 2x_1 - 2 \implies x_2 = x_1 - 1
\end{aligned}
$$

Wählen wir den Parameter $x_1 = t$:
$$
\begin{aligned}
\begin{cases} x_1 = t \\\\ x_2 = t - 1 \\\\ x_3 = -1 - t \end{cases} \implies s: \vec{x} = \begin{pmatrix} 0 \\\\ -1 \\\\ -1 \end{pmatrix} + t \cdot \begin{pmatrix} 1 \\\\ 1 \\\\ -1 \end{pmatrix}
\end{aligned}
$$

---

## Teil b)

### 1. Koordinatengleichungen aufstellen

**Ebene $E_{ABC}$:**

$$
\begin{aligned}
\vec{AB} = \begin{pmatrix} 3 \\ -2 \\ 1 \end{pmatrix}, \quad \vec{AC} = \begin{pmatrix} -3 \\ 2 \\ 7 \end{pmatrix} \\
\vec{n}_1 = \begin{pmatrix} 3 \\ -2 \\ 1 \end{pmatrix} \times \begin{pmatrix} -3 \\ 2 \\ 7 \end{pmatrix} = \begin{pmatrix} -16 \\ -24 \\ 0 \end{pmatrix} \quad \implies \text{gewählt: } \vec{n}_1 = \begin{pmatrix} 2 \\ 3 \\ 0 \end{pmatrix}
\end{aligned}
$$

Einsetzen von $A(-1 \mid 1 \mid -1)$:
$$
\begin{aligned}
2(-1) + 3(1) + 0(-1) = 1 \implies E_{ABC}: 2x_1 + 3x_2 = 1
\end{aligned}
$$

**Ebene $E_{DEF}$:**
$$
\begin{aligned}
\vec{DE} &= \begin{pmatrix} -1,5 \\\\ 1 \\\\ 1 \end{pmatrix}, \quad \vec{DF} = \begin{pmatrix} 3 \\\\ -2 \\\\ -5 \end{pmatrix} \\\\
\vec{n}_2 &= \begin{pmatrix} -1,5 \\\\ 1 \\\\ 1 \end{pmatrix} \times \begin{pmatrix} 3 \\\\ -2 \\\\ -5 \end{pmatrix} = \begin{pmatrix} -3 \\\\ -4,5 \\\\ 0 \end{pmatrix} \quad \implies \text{gewählt: } \vec{n}_2 = \begin{pmatrix} 2 \\\\ 3 \\\\ 0 \end{pmatrix}
\end{aligned}
$$

---

### 2. Lagebeziehung (Parallelitätsprüfung)

Da $\vec{n}_1 = \vec{n}_2 = \begin{pmatrix} 2 \\ 3 \\ 0 \end{pmatrix}$, sind die Normalenvektoren identisch. Die Ebenen sind somit **parallel**.

**Punktprobe mit $D(1 \mid -1 \mid -2)$ in $E_{ABC}$:**
$$
\begin{aligned}
2(1) + 3(-1) = -1 \neq 1
\end{aligned}
$$
Da der Punkt $D$ die Gleichung von $E_{ABC}$ nicht erfüllt, sind die Ebenen **echt parallel**.

---

### 3. Abstand der Ebenen

Verwendung der Hesseschen Normalenform von $E_{ABC}$ mit dem Punkt $D(1 \mid -1 \mid -2)$:
$$
\begin{aligned}
d(E_{ABC}, E_{DEF}) = \frac{|2(1) + 3(-1) - 1|}{\sqrt{2^2 + 3^2 + 0^2}} = \frac{|-2|}{\sqrt{13}} = \frac{2}{\sqrt{13}} = \frac{2\sqrt{13}}{13} \approx 0,555 \text{ LE}
\end{aligned}
$$