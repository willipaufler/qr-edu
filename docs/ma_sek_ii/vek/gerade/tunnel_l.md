# Tunnelprojekt - Lösung

### a) Nachweis des Treffpunkts und Bestimmung der Koordinaten

**1. Geradengleichungen aufstellen:**

Für Bohrer 1 ab $S_1(235 \mid 100 \mid 1000)$:
$$
g: \vec{x} = \begin{pmatrix} 235 \\\\ 100 \\\\ 1000 \end{pmatrix} + r \begin{pmatrix} 10{,}3 \\\\ 0 \\\\ 1 \end{pmatrix}
$$

Für Bohrer 2 ab $S_2(1125 \mid 1200 \mid 1200)$:
$$
h: \vec{x} = \begin{pmatrix} 1125 \\\\ 1200 \\\\ 1200 \end{pmatrix} + s \begin{pmatrix} -15 \\\\ -44 \\\\ -6 \end{pmatrix}
$$

**2. Gleichsetzen zur Schnittpunktbestimmung:**

$$
\begin{aligned}
\begin{pmatrix} 235 \\ 100 \\ 1000 \end{pmatrix} + r \begin{pmatrix} 10{,}3 \\ 0 \\ 1 \end{pmatrix} &= \begin{pmatrix} 1125 \\ 1200 \\ 1200 \end{pmatrix} + s \begin{pmatrix} -15 \\ -44 \\ -6 \end{pmatrix}
\end{aligned}
$$

Daraus ergibt sich das zeilenweise Gleichungssystem:
$$
\begin{aligned}
(1) \quad 235 + 10{,}3 r &= 1125 - 15 s \\\\
(2) \quad 100 &= 1200 - 44 s \\\\
(3) \quad 1000 + r &= 1200 - 6 s
\end{aligned}
$$

Aus Gleichung $(2)$ folgt $s$:
$$
\begin{aligned}
100 &= 1200 - 44 s \\\\
-1100 &= -44 s \\\\
s &= 25
\end{aligned}
$$

Einsetzen von $s = 25$ in Gleichung $(3)$:
$$
\begin{aligned}
1000 + r &= 1200 - 6 \cdot 25 \\\\
1000 + r &= 1200 - 150 \\\\
1000 + r &= 1050 \\\\
r &= 50
\end{aligned}
$$

Überprüfung in Gleichung $(1)$ mit $r = 50$ und $s = 25$:
$$
\begin{aligned}
235 + 10{,}3 \cdot 50 &= 1125 - 15 \cdot 25 \\\\
235 + 515 &= 1125 - 375 \\\\
750 &= 750 \quad \text{(wahre Aussage)}
\end{aligned}
$$

Die Schächte schneiden sich.

**3. Treffpunkt $T$ berechnen:**

Einsetzen von $r = 50$ in $g$:
$$
\begin{aligned}
\vec{OT} &= \begin{pmatrix} 235 \\\\ 100 \\\\ 1000 \end{pmatrix} + 50 \begin{pmatrix} 10{,}3 \\\\ 0 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 235 + 515 \\\\ 100 + 0 \\\\ 1000 + 50 \end{pmatrix} = \begin{pmatrix} 750 \\\\ 100 \\\\ 1050 \end{pmatrix}
\end{aligned}
$$

Der Treffpunkt der beiden Bohrer lautet $T(750 \mid 100 \mid 1050)$.

---

### b) Berechnung der Bohrstrecken und der Gesamtdauer

**1. Längen der Bohrstrecken über Abstände berechnen:**

Verbindungsvektor von $S_1(235 \mid 100 \mid 1000)$ nach $T(750 \mid 100 \mid 1050)$:
$$
\begin{aligned}
\vec{S_1 T} & = \begin{pmatrix} 515 \\\\ 0 \\\\ 50 \end{pmatrix}
\end{aligned}
$$

Abstand $d_1 = |\vec{S_1 T}|$:
$$
\begin{aligned}
d_1 &= \sqrt{515^2 + 0^2 + 50^2} \approx 517{,}42\,\text{m}
\end{aligned}
$$

Verbindungsvektor von $S_2(1125 \mid 1200 \mid 1200)$ nach $T(750 \mid 100 \mid 1050)$:
$$
\begin{aligned}
\vec{S_2 T} &= \begin{pmatrix} -375 \\\\ -1100 \\\\ -150 \end{pmatrix}
\end{aligned}
$$

Abstand $d_2 = |\vec{S_2 T}|$:
$$
\begin{aligned}
d_2 &= \sqrt{(-375)^2 + (-1100)^2 + (-150)^2} \approx 1171{,}80\,\text{m}
\end{aligned}
$$

**2. Benötigte Zeiten berechnen:**

Die Bohrgeschwindigkeit beträgt $v = 120\,\frac{\text{cm}}{\text{h}} = 1{,}2\,\frac{\text{m}}{\text{h}}$.

Dauer für Bohrer 1 ($t_1$):
$$
\begin{aligned}
t_1 &= \frac{d_1}{v} = \frac{517{,}42\,\text{m}}{1{,}2\,\frac{\text{m}}{\text{h}}} \approx 431{,}18\,\text{Stunden}
\end{aligned}
$$

Dauer für Bohrer 2 ($t_2$):
$$
\begin{aligned}
t_2 &= \frac{d_2}{v} = \frac{1171{,}80\,\text{m}}{1{,}2\,\frac{\text{m}}{\text{h}}} \approx 976{,}50\,\text{Stunden}
\end{aligned}
$$

**3. Gesamtdauer in Tagen:**

Da beide Bohrer gleichzeitig arbeiten, endet das Bauvorhaben, wenn der langsamere/länger brauchende Bohrer (Bohrer 2) am Treffpunkt eintrifft:
$$
\begin{aligned}
t_{\text{ges}} &= \frac{976{,}50\,\text{h}}{24\,\frac{\text{h}}{\text{Tag}}} \approx 40{,}69\,\text{Tage}
\end{aligned}
$$

Das Bauvorhaben dauert insgesamt ca. $40{,}7$ Tage (bzw. ca. $40$ Tage und $16$ Stunden).