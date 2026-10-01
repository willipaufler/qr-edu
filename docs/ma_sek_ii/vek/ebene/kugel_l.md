# Lösung – Gerade, Ebene und Kugel

## Teil a) Erklärung der Eindeutigkeit des Schnittpunkts

Der Vektoransatz
$$
r \cdot \begin{pmatrix} -2 \\\\ -1 \\\\ 0 \end{pmatrix} + s \cdot \begin{pmatrix} 5 \\\\ 3 \\\\ 4 \end{pmatrix} + t \cdot \begin{pmatrix} 5 \\\\ 11 \\\\ -4 \end{pmatrix} = \begin{pmatrix} 0 \\\\ 0 \\\\ 0 \end{pmatrix}
$$
prüft die lineare Unabhängigkeit der Richtungsvektoren. 

Wenn nur die triviale Lösung $r = s = t = 0$ existiert, bedeutet dies:
1. Der Richtungsvektor $\vec{v}_g$ der Geraden lässt sich nicht als Linearkombination der Spannvektoren der Ebene darstellen.
2. Die Gerade verläuft somit weder parallel zur Ebene noch liegt sie in ihr.
3. Daraus folgt zwingend, dass sich Ebene und Gerade in **genau einem Punkt** schneiden.

---

## Teil b) Schnittwinkel $\alpha$ und Schnittpunkt $S$

### 1. Normalenvektor und Koordinatenform der Ebene $E$
Kreuzprodukt der Spannvektoren:
$$
\begin{aligned}
\vec{n} = \begin{pmatrix} -2 \\\\ -1 \\\\ 0 \end{pmatrix} \times \begin{pmatrix} 5 \\\\ 3 \\\\ 4 \end{pmatrix} = \begin{pmatrix} -4 - 0 \\\\ 0 - (-8) \\\\ -6 - (-5) \end{pmatrix} = \begin{pmatrix} -4 \\\\ 8 \\\\ -1 \end{pmatrix} \quad \implies \text{gewählt: } \vec{n} = \begin{pmatrix} 4 \\\\ -8 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Einsetzen des Stützpunkts $A(-10 \mid 0 \mid -10)$ für $d$:
$$
\begin{aligned}
d = 4(-10) - 8(0) + 1(-10) = -50 \implies E: 4x_1 - 8x_2 + x_3 = -50
\end{aligned}
$$

### 2. Schnittwinkel $\alpha$
Zunächst wird der Winkel $\beta$ zwischen der Normalen der Ebene und der Geraden berechnet.
$$
\begin{aligned}
\cos(\beta) = \frac{\left| \begin{pmatrix} 5 \\\\ 11 \\\\ -4 \end{pmatrix} \cdot \begin{pmatrix} 4 \\\\ -8 \\\\ 1 \end{pmatrix} \right|}{\left| \begin{pmatrix} 5 \\\\ 11 \\\\ -4 \end{pmatrix} \right| \cdot \left| \begin{pmatrix} 4 \\\\ -8 \\\\ 1 \end{pmatrix} \right|} = \frac{4\sqrt{2}}{9} \approx 0,6285 \\\\
\beta = \arccos\left(\frac{4\sqrt{2}}{9}\right) \approx 51,06^\circ
\end{aligned}
$$

Somit ist $\alpha=90^\circ-\beta=38,94^\circ$


### 3. Schnittpunkt $S$
Einsetzen der Geradengleichung $g(t)$ in $E$:
$$
\begin{aligned}
4(3 + 5t) - 8(12 + 11t) + (-2 - 4t) = -50 \\\\
-72t = 36 \\\\
t = -\frac{1}{2}
\end{aligned}
$$

Einsetzen von $t = -0,5$ in $g$:
$$
\begin{aligned}
\vec{OS} = \begin{pmatrix} 3 \\\\ 12 \\\\ -2 \end{pmatrix} - 0,5 \cdot \begin{pmatrix} 5 \\\\ 11 \\\\ -4 \end{pmatrix} = \begin{pmatrix} 0,5 \\\\ 6,5 \\\\ 0 \end{pmatrix} \implies S(0,5 \mid 6,5 \mid 0)
\end{aligned}
$$

---

## Teil c) Berührpunkt $F$ und Kugelradius $R$

### 1. Lotgerade $h$ aufstellen
Die Lotgerade geht durch $M(-13 \mid 20 \mid 0)$ und hat den Normalenvektor $\vec{n}$ als Richtungsvektor:
$$
\begin{aligned}
h: \vec{x} = \begin{pmatrix} -13 \\\\ 20 \\\\ 0 \end{pmatrix} + k \cdot \begin{pmatrix} 4 \\\\ -8 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

### 2. Berührpunkt $F$ berechnen (Schnitt von $h$ mit $E$)
$$
\begin{aligned}
4(-13 + 4k) - 8(20 - 8k) + (k) = -50 \\
81k = 162 \\
k = 2
\end{aligned}
$$

Einsetzen von $k = 2$ in $h$:
$$
\begin{aligned}
\vec{OF} = \begin{pmatrix} -13 \\\\ 20 \\\\ 0 \end{pmatrix} + 2 \cdot \begin{pmatrix} 4 \\\\ -8 \\\\ 1 \end{pmatrix} = \begin{pmatrix} -5 \\\\ 4 \\\\ 2 \end{pmatrix} \implies F(-5 \mid 4 \mid 2)
\end{aligned}
$$

### 3. Kugelradius $R$
$$
\begin{aligned}
R = |\vec{MF}| = \left| \begin{pmatrix} -5 \\ 4 \\ 2 \end{pmatrix} - \begin{pmatrix} -13 \\ 20 \\ 0 \end{pmatrix} \right| = \left| \begin{pmatrix} 8 \\ -16 \\ 2 \end{pmatrix} \right| = \sqrt{64 + 256 + 4} = \sqrt{324} = 18
\end{aligned}
$$

---

## Teil d) Nachweis der Tangenteneigenschaft

### Kniffliger Weg: Berechnung von $T$ als Lotfußpunkt von $M$ auf $g$

Ein Punkt $T$ auf $g$ ist genau dann der Berührpunkt einer Tangente von $M$ an $g$, wenn der Verbindungsvektor $\vec{MT}$ senkrecht auf dem Richtungsvektor $\vec{v}_g$ steht:

1. **Verbindungsvektor in Abhängigkeit von $t$:**
$$
\begin{aligned}
\vec{MT}(t) = \begin{pmatrix} 3 + 5t \\\\ 12 + 11t \\\\ -2 - 4t \end{pmatrix} - \begin{pmatrix} -13 \\\\ 20 \\\\ 0 \end{pmatrix} = \begin{pmatrix} 16 + 5t \\\\ -8 + 11t \\\\ -2 - 4t \end{pmatrix}
\end{aligned}
$$

2. **Orthogonalitätsbedingung ($\vec{MT}(t) \cdot \vec{v}_g = 0$):**
$$
\begin{aligned}
\begin{pmatrix} 16 + 5t \\\\ -8 + 11t \\\\ -2 - 4t \end{pmatrix} \cdot \begin{pmatrix} 5 \\\\ 11 \\\\ -4 \end{pmatrix} = 0 \\\\
5(16 + 5t) + 11(-8 + 11t) - 4(-2 - 4t) = 0 \\\\
80 + 25t - 88 + 121t + 8 + 16t = 0 \implies 162t = 0 \implies t = 0
\end{aligned}
$$

3. **Koordinaten von $T$:**
Für $t = 0$ ergibt sich aus der Geradengleichung direkt der Stützpunkt:
$$
\begin{aligned}
T(3 \mid 12 \mid -2)
\end{aligned}
$$

4. **Radiusprüfung:**
Der Abstand von $M$ zu $T$ beträgt:
$$
\begin{aligned}
|\vec{MT}| = \left| \begin{pmatrix} 16 \\\\ -8 \\\\ -2 \end{pmatrix} \right| = \sqrt{16^2 + (-8)^2 + (-2)^2} = \sqrt{256 + 64 + 4} = \sqrt{324} = 18
\end{aligned}
$$

Da $|\vec{MT}| = R = 18$ und der Vektor orthogonal zu $g$ steht, berührt die Gerade $g$ die Kugel im Punkt $T(3 \mid 12 \mid -2)$ und ist somit eine **Tangente**.