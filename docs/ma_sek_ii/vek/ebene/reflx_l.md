# Lösung – Reflexion

## Teil a) Nachweis, dass der Lichtstrahl auf den Spiegel trifft

### 1. Geradengleichung für den Lichtstrahl
Mit Stützpunkt $P(6 \mid 5 \mid 1)$ und dem (gekürzten) Richtungsvektor $\vec{u} = \frac{1}{2}\vec{v} = \begin{pmatrix} -24 \\ -35 \\ 2 \end{pmatrix}$:
$$
\begin{aligned}
g: \vec{x} = \begin{pmatrix} 6 \\ 5 \\ 1 \end{pmatrix} + t \cdot \begin{pmatrix} -24 \\ -35 \\ 2 \end{pmatrix} \quad (t \ge 0)
\end{aligned}
$$

### 2. Schnittpunkt $S$ mit der Ebene $E: 2x + 3y + 4z = 2$
Setze die Koordinaten von $g$ in $E$ ein:
$$
\begin{aligned}
2(6 - 24t) + 3(5 - 35t) + 4(1 + 2t) &= 2 \\\\
12 - 48t + 15 - 105t + 4 + 8t &= 2 \\\\
31 - 145t &= 2 \\\\
145t &= 29 \implies t = \frac{29}{145} = 0{,}2
\end{aligned}
$$

Einsetzen von $t = 0{,}2$ in $g$:
$$
\begin{aligned}
\vec{OS} = \begin{pmatrix} 6 \\ 5 \\ 1 \end{pmatrix} + 0{,}2 \cdot \begin{pmatrix} -24 \\ -35 \\ 2 \end{pmatrix} = \begin{pmatrix} 1{,}2 \\ -2 \\ 1{,}4 \end{pmatrix} \implies S(1{,}2 \mid -2 \mid 1{,}4)
\end{aligned}
$$

### 3. Prüfen des Abstands zum Mittelpunkt $M(1 \mid -2 \mid 1{,}5)$
Verbindungsvektor $\vec{MS}$:
$$
\begin{aligned}
\vec{MS} = \begin{pmatrix} 1{,}2 - 1 \\ -2 - (-2) \\ 1{,}4 - 1{,}5 \end{pmatrix} = \begin{pmatrix} 0{,}2 \\ 0 \\ -0{,}1 \end{pmatrix}
\end{aligned}
$$

Abstand $d(S, M)$:
$$
\begin{aligned}
|\vec{MS}| = \sqrt{0{,}2^2 + 0^2 + (-0{,}1)^2} = \sqrt{0{,}04 + 0{,}01} = \sqrt{0{,}05} \approx 0{,}224\text{ m}
\end{aligned}
$$

Da der Durchmesser des Spiegels $1\text{ m}$ beträgt, ist der Radius $r = 0{,}5\text{ m}$.  
Wegen $d(S, M) \approx 0{,}224\text{ m} \le 0{,}5\text{ m}$ liegt der Schnittpunkt $S$ auf der Spiegelfläche. Der Lichtstrahl trifft somit auf den Spiegel.

---

## Teil b) Gleichung des reflektierten Lichtstrahls

### Standard-Schulweg (Spiegelung des Punktes $P$ an Ebene $E$)

#### 1. Lotgerade $l$ durch $P(6 \mid 5 \mid 1)$ senkrecht zu $E$
Der Normalenvektor der Ebene $E$ lautet $\vec{n} = \begin{pmatrix} 2 \\ 3 \\ 4 \end{pmatrix}$.

$$
\begin{aligned}
l: \vec{x} = \begin{pmatrix} 6 \\ 5 \\ 1 \end{pmatrix} + r \cdot \begin{pmatrix} 2 \\ 3 \\ 4 \end{pmatrix}
\end{aligned}
$$

#### 2. Schnittpunkt $L$ der Lotgeraden mit der Ebene $E$ (Lotfußpunkt)
Setze die Koordinaten von $l$ in $E: 2x + 3y + 4z = 2$ ein:
$$
\begin{aligned}
2(6 + 2r) + 3(5 + 3r) + 4(1 + 4r) &= 2 \\\\
12 + 4r + 15 + 9r + 4 + 16r &= 2 \\\\
31 + 29r &= 2 \\\\
29r &= -29 \implies r = -1
\end{aligned}
$$

Einsetzen von $r = -1$ in $l$:
$$
\begin{aligned}
\vec{OL} = \begin{pmatrix} 6 \\ 5 \\ 1 \end{pmatrix} + (-1) \cdot \begin{pmatrix} 2 \\ 3 \\ 4 \end{pmatrix} = \begin{pmatrix} 4 \\ 2 \\ -3 \end{pmatrix} \implies L(4 \mid 2 \mid -3)
\end{aligned}
$$

#### 3. Spiegelpunkt $P'$ von $P$ an $L$
$$
\begin{aligned}
\vec{OP'} = \vec{OP} + 2 \cdot \vec{PL} = \begin{pmatrix} 6 \\ 5 \\ 1 \end{pmatrix} + 2 \cdot \begin{pmatrix} 4 - 6 \\ 2 - 5 \\ -3 - 1 \end{pmatrix} = \begin{pmatrix} 6 \\ 5 \\ 1 \end{pmatrix} + 2 \cdot \begin{pmatrix} -2 \\ -3 \\ -4 \end{pmatrix} = \begin{pmatrix} 2 \\ -1 \\ -7 \end{pmatrix}
\end{aligned}
$$

Der gespiegelte Punkt ist $P'(2 \mid -1 \mid -7)$.

#### 4. Richtungsvektor des reflektierten Strahl ($\vec{u}_{\text{refl}}$)
Der reflektierte Strahl verläuft vom Schnittpunkt $S(1{,}2 \mid -2 \mid 1{,}4)$ weg in Verlängerung von $P'$ durch $S$, also in Richtung des Vektors $\vec{P'S}$:

$$
\begin{aligned}
\vec{P'S} = \begin{pmatrix} 1{,}2 - 2 \\ -2 - (-1) \\ 1{,}4 - (-7) \end{pmatrix} = \begin{pmatrix} -0{,}8 \\ -1 \\ 8{,}4 \end{pmatrix}
\end{aligned}
$$

Multiplikation mit $5$ liefert einen ganzzahligen Richtungsvektor:

$$
\begin{aligned}
\vec{u}_{\text{refl}} = 5 \cdot \begin{pmatrix} -0{,}8 \\ -1 \\ 8{,}4 \end{pmatrix} = \begin{pmatrix} -4 \\ -5 \\ 42 \end{pmatrix}
\end{aligned}
$$

#### 5. Gleichung des reflektierten Lichtstrahls
$$
\begin{aligned}
g_{\text{refl}}: \vec{x} = \begin{pmatrix} 1{,}2 \\ -2 \\ 1{,}4 \end{pmatrix} + k \cdot \begin{pmatrix} -4 \\ -5 \\ 42 \end{pmatrix} \quad (k \ge 0)
\end{aligned}
$$

---

### Alternative (für Experten: Vektorprojektion)
Man spiegelt den einfallenden Richtungsvektor $\vec{u} = \begin{pmatrix} -24 \\ -35 \\ 2 \end{pmatrix}$ direkt an der Normalenrichtung $\vec{n} = \begin{pmatrix} 2 \\ 3 \\ 4 \end{pmatrix}$:

$$
\begin{aligned}
\vec{u}_{\text{refl}} &= \vec{u} - 2 \cdot \frac{\vec{u} \cdot \vec{n}}{|\vec{n}|^2} \cdot \vec{n} \\\\
&= \begin{pmatrix} -24 \\ -35 \\ 2 \end{pmatrix} - 2 \cdot \frac{-145}{29} \cdot \begin{pmatrix} 2 \\ 3 \\ 4 \end{pmatrix} \\\\
&= \begin{pmatrix} -24 \\ -35 \\ 2 \end{pmatrix} + 10 \cdot \begin{pmatrix} 2 \\ 3 \\ 4 \end{pmatrix} = \begin{pmatrix} -4 \\ -5 \\ 42 \end{pmatrix}
\end{aligned}
$$