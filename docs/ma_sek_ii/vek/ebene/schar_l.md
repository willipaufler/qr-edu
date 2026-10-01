# Lösung – Ebenenschar

## Teil a) Schnittgerade von $E_1$ und $E_2$

Die Ebenen lauten:
$$
\begin{aligned}
E_1: 3x - y + z = 0 \\\\
E_2: 3x - 2y + z = 0
\end{aligned}
$$

### Weg 1: Lineares Gleichungssystem (Standard)
Subtraktion $(E_1 - E_2)$:
$$
\begin{aligned}
y = 0
\end{aligned}
$$

Einsetzen von $y = 0$ in $E_1$:
$$
\begin{aligned}
3x + z = 0 \implies z = -3x
\end{aligned}
$$

Wählen wir den Parameter $x = t$, ergibt sich die Schnittgerade $g$:
$$
\begin{aligned}
\begin{cases} x = t \\\\ y = 0 \\\\ z = -3t \end{cases} \implies g: \vec{x} = t \cdot \begin{pmatrix} 1 \\\\ 0 \\\\ -3 \end{pmatrix}
\end{aligned}
$$


### Weg 2: Eleganter Weg über Ursprung & Kreuzprodukt
1. **Stützvektor:** Da bei beiden Ebenen die rechte Seite gleich $0$ ist, verläuft sowohl $E_1$ als auch $E_2$ durch den Ursprung. Somit ist $O(0 \mid 0 \mid 0)$ ein gemeinsamer Schnittpunkt und dient als Stützvektor $\vec{p} = \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix}$.

2. **Richtungsvektor:** Der Richtungsvektor $\vec{v}_g$ steht senkrecht auf den Normalenvektoren $\vec{n}_1 = \begin{pmatrix} 3 \\ -1 \\ 1 \end{pmatrix}$ und $\vec{n}_2 = \begin{pmatrix} 3 \\ -2 \\ 1 \end{pmatrix}$:
$$
\begin{aligned}
\vec{v}_g = \vec{n}_1 \times \vec{n}_2 = \begin{pmatrix} 3 \\\\ -1 \\\\ 1 \end{pmatrix} \times \begin{pmatrix} 3 \\\\ -2 \\\\ 1 \end{pmatrix} = \begin{pmatrix} -1 \cdot 1 - 1 \cdot (-2) \\\\ 1 \cdot 3 - 3 \cdot 1 \\\\ 3 \cdot (-2) - (-1) \cdot 3 \end{pmatrix} = \begin{pmatrix} 1 \\\\ 0 \\\\ -3 \end{pmatrix}
\end{aligned}
$$

Daraus folgt direkt dieselbe Schnittgerade:
$$
\begin{aligned}
g: \vec{x} = t \cdot \begin{pmatrix} 1 \\\\ 0 \\\\ -3 \end{pmatrix}
\end{aligned}
$$
---

## Teil b) Nachweis der gemeinsamen Schnittgerade

Einsetzen der Komponenten von $g(t)$ ($x = t$, $y = 0$, $z = -3t$) in die allgemeine Schargleichung $E_a$:
$$
\begin{aligned}
3(t) - a(0) + (-3t) = 0 \\\\
3t - 3t = 0 \\\\
0 = 0
\end{aligned}
$$

Da die Gleichung für jedes $a \in \mathbb{R}$ und jedes $t \in \mathbb{R}$ erfüllt ist, liegt die Gerade $g$ vollständig in allen Ebenen der Schar $E_a$.

---

## Teil c) Ebene $F_a$ parallel zu $E_a$ durch $P(1 \mid 2 \mid -3)$

Da $F_a$ parallel zu $E_a$ verläuft, übernimmt sie den Normalenvektor $\vec{n} = \begin{pmatrix} 3 \\ -a \\ 1 \end{pmatrix}$:
$$
\begin{aligned}
F_a: 3x - ay + z = d
\end{aligned}
$$

Einsetzen von $P(1 \mid 2 \mid -3)$ zur Bestimmung von $d$:
$$
\begin{aligned}
d = 3(1) - a(2) + (-3) = 3 - 2a - 3 = -2a
\end{aligned}
$$

Gleichung der Ebene $F_a$:
$$
\begin{aligned}
F_a: 3x - ay + z = -2a
\end{aligned}
$$

---

## Teil d) Identität von $E_a$ und $F_a$

Die Ebenen $E_a: 3x - ay + z = 0$ und $F_a: 3x - ay + z = -2a$ stimmen in den Koeffizienten auf der linken Seite überein. Sie sind somit genau dann identisch, wenn auch die rechten Seiten übereinstimmen:
$$
\begin{aligned}
-2a = 0 \implies a = 0
\end{aligned}
$$

Für $a = 0$ sind die Ebenen $E_0$ und $F_0$ identisch.

---

## Teil e) Scharebenen mit Abstand $1\text{ LE}$ zu $R(0 \mid 0 \mid 4)$

Berechnung des Abstands $d(R, E_a)$ mit der Hesseschen Normalenform:
$$
\begin{aligned}
d(R, E_a) = \frac{|3(0) - a(0) + 4|}{\sqrt{3^2 + (-a)^2 + 1^2}} = \frac{4}{\sqrt{10 + a^2}}
\end{aligned}
$$

Bedingung $d(R, E_a) = 1$:
$$
\begin{aligned}
\frac{4}{\sqrt{10 + a^2}} = 1 \implies \sqrt{10 + a^2} = 4 \\\\
10 + a^2 = 16 \\\\
a^2 = 6 \implies a = \pm\sqrt{6}
\end{aligned}
$$

Die gesuchten Ebenen der Schar sind:
$$
\begin{aligned}
E_{\sqrt{6}}: 3x - \sqrt{6}y + z = 0 \\\\
E_{-\sqrt{6}}: 3x + \sqrt{6}y + z = 0
\end{aligned}
$$