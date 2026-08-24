# Geradenscharen und Spurpunkte - Lösung

### a) Bestimmung von $a$ und $b$, Spurpunkten und Flächeninhalt

**1. Parameter $a$ bestimmen:**

Damit die Gerade $g_{a,b}$ nur zwei Spurpunkte besitzt, muss sie parallel zu einer Koordinatenebene sein. Dazu muss ein Eintrag des Richtungsvektors Null werden:
$$
\begin{aligned}
1 - \frac{a}{2} &= 0 \implies a = 2
\end{aligned}
$$

Für $a = 2$ lautet die Geradengleichung:
$$
\begin{aligned}
g_{2,b}: \vec{x} &= \begin{pmatrix} 0 \\\\ 3 \\\\ 3 \end{pmatrix} + s \begin{pmatrix} 1 \\\\ 0 \\\\ b \end{pmatrix}
\end{aligned}
$$

**2. Spurpunkte in Abhängigkeit von $b$ berechnen:**

* **$x_2 x_3$-Spurpunkt $S_{23}$ ($x_1 = 0$):**
$$
\begin{aligned}
0 + s &= 0 \implies s = 0 \implies S_{23}(0 \mid 3 \mid 3)
\end{aligned}
$$

* **$x_1 x_2$-Spurpunkt $S_{12}$ ($x_3 = 0$):**
$$
\begin{aligned}
3 + b \cdot s &= 0 \implies s = -\frac{3}{b} \implies S_{12}\left(-\frac{3}{b} \;\mid\; 3 \;\mid\; 0\right)
\end{aligned}
$$

*(Hinweis: Der $x_1 x_3$-Spurpunkt existiert nicht, da $x_2 = 3 \neq 0$ konstant ist.)*

**3. Parameter $b$ für Gleichschenkligkeit bestimmen:**

Das Dreieck ist gleichschenklig, wenn die Abstände der Spurpunkte vom Ursprung $O(0 \mid 0 \mid 0)$ gleich groß sind:
$$
\begin{aligned}
|\vec{OS_{23}}| &= \sqrt{0^2 + 3^2 + 3^2} = \sqrt{18} \\\\
|\vec{OS_{12}}| &= \sqrt{\left(-\frac{3}{b}\right)^2 + 3^2 + 0^2} = \sqrt{\frac{9}{b^2} + 9}
\end{aligned}
$$

Gleichsetzen der Längen:
$$
\begin{aligned}
\sqrt{\frac{9}{b^2} + 9} &= \sqrt{18} \quad \Big| \, (\dots)^2 \\\\
\frac{9}{b^2} + 9 &= 18 \\\\
\frac{9}{b^2} &= 9 \implies b^2 = 1 \implies b = 1 \quad (\text{oder } b = -1)
\end{aligned}
$$

Für $b = 1$ lautet der zweite Spurpunkt $S_{12}(-3 \mid 3 \mid 0)$.

**4. Flächeninhalt für $b = 1$:**

Kreuzprodukt der Ortsvektoren von $S_{23}(0 \mid 3 \mid 3)$ und $S_{12}(-3 \mid 3 \mid 0)$:
$$
\begin{aligned}
\vec{OS_{23}} \times \vec{OS_{12}} &= \begin{pmatrix} 0 \\\\ 3 \\\\ 3 \end{pmatrix} \times \begin{pmatrix} -3 \\\\ 3 \\\\ 0 \end{pmatrix} = \begin{pmatrix} 3 \cdot 0 - 3 \cdot 3 \\\\ 3 \cdot (-3) - 0 \cdot 0 \\\\ 0 \cdot 3 - 3 \cdot (-3) \end{pmatrix} = \begin{pmatrix} -9 \\\\ -9 \\\\ 9 \end{pmatrix}
\end{aligned}
$$

Flächeninhalt $A$:
$$
\begin{aligned}
A &= \frac{1}{2} \cdot \left| \begin{pmatrix} -9 \\ -9 \\ 9 \end{pmatrix} \right| = \frac{1}{2} \sqrt{(-9)^2 + (-9)^2 + 9^2} = \frac{1}{2} \sqrt{243} = \frac{9}{2}\sqrt{3} \approx 7{,}79\,\text{FE}
\end{aligned}
$$

---

### b) Nachweis des gemeinsamen Schnittpunktes $P$ ($b = 1$)

Für $b = 1$ lautet die Geradenschar:
$$
\begin{aligned}
g_a: \vec{x} &= \begin{pmatrix} 0 \\\\ 1+a \\\\ 3 \end{pmatrix} + s \begin{pmatrix} 1 \\\\ 1-\frac{a}{2} \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Zeilenweise Betrachtung:
$$
\begin{aligned}
(1) \quad x_1 &= s \\\\
(2) \quad x_2 &= 1 + a + s\left(1 - \frac{a}{2}\right) = 1 + s + a\left(1 - \frac{s}{2}\right) \\\\
(3) \quad x_3 &= 3 + s
\end{aligned}
$$

Damit $x_2$ unabhängig von $a$ ist, muss der Term $1 - \frac{s}{2} = 0$ werden:
$$
\begin{aligned}
1 - \frac{s}{2} &= 0 \implies s = 2
\end{aligned}
$$

Einsetzen von $s = 2$ in alle drei Koordinatenzeilen:
$$
\begin{aligned}
x_1 &= 2 \\\\
x_2 &= 1 + 2 + a\left(1 - \frac{2}{2}\right) = 3 \\\\
x_3 &= 3 + 2 = 5
\end{aligned}
$$

Alle Geraden der Schar schneiden sich unabhängig von $a$ im gemeinsamen Punkt **$P(2 \mid 3 \mid 5)$**.

---

### c) Bestimmung einer zu allen Schargeraden orthogonalen Geraden $h$

#### Weg 1: Skalarprodukt 
Ein Richtungsvektor $\vec{u} = \begin{pmatrix} u_1 \\ u_2 \\ u_3 \end{pmatrix}$ der gesuchten Geraden $h$ muss senkrecht zu $\vec{v}_a = \begin{pmatrix} 1 \\ 1-\frac{a}{2} \\ 1 \end{pmatrix}$ stehen:

$$
\begin{aligned}
\vec{v}_a \cdot \vec{u} &= 0 \\\\
1 \cdot u_1 + \left(1 - \frac{a}{2}\right) u_2 + 1 \cdot u_3 &= 0 \\\\
u_1 + u_2 - \frac{a}{2} u_2 + u_3 &= 0
\end{aligned}
$$

Sortiert nach Termen mit und ohne $a$:
$$
\begin{aligned}
(u_1 + u_2 + u_3) + a \cdot \left(-\frac{1}{2} u_2\right) &= 0
\end{aligned}
$$

Damit diese Gleichung für jedes $a \in \mathbb{R}$ erfüllt ist, müssen beide Ausdrücke Null sein:
$$
\begin{aligned}
(1) \quad -\frac{1}{2} u_2 &= 0 \implies u_2 = 0 \\\\
(2) \quad u_1 + u_2 + u_3 &= 0 \xrightarrow{u_2 = 0} u_1 + u_3 = 0 \implies u_3 = -u_1
\end{aligned}
$$

Wählen wir frei $u_1 = 1 \implies u_3 = -1$. Ein orthogonaler Richtungsvektor lautet somit $\vec{u} = \begin{pmatrix} 1 \\ 0 \\ -1 \end{pmatrix}$.

Als Stützpunkt wählen wir den gemeinsamen Schnittpunkt $P(2 \mid 3 \mid 5)$:

$$
\begin{aligned}
h: \vec{x} &= \begin{pmatrix} 2 \\ 3 \\ 5 \end{pmatrix} + k \begin{pmatrix} 1 \\ 0 \\ -1 \end{pmatrix} \quad \text{mit } k \in \mathbb{R}
\end{aligned}
$$

#### Weg 2: Kreuzprodukt

Wir wählen zwei konkrete Parameterwerte für $a$, um zwei Richtungsvektoren der Schar zu erhalten:

Für $a = 0$:
$$
\begin{aligned}
\vec{v}_{a=0} &= \begin{pmatrix} 1 \\\\ 1 - 0 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 1 \\\\ 1 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Für $a = 2$:
$$
\begin{aligned}
\vec{v}_{a=2} &= \begin{pmatrix} 1 \\\\ 1 - 1 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 1 \\\\ 0 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Das Kreuzprodukt dieser beiden Vektoren liefert einen Vektor, der senkrecht auf beiden liegt:

$$
\begin{aligned}
\vec{u} &= \vec{v}_{a=0} \times \vec{v}_{a=2} = \begin{pmatrix} 1 \\ 1 \\ 1 \end{pmatrix} \times \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix} \\\\
&= \begin{pmatrix} 1 \cdot 1 - 1 \cdot 0 \\ 1 \cdot 1 - 1 \cdot 1 \\ 1 \cdot 0 - 1 \cdot 1 \end{pmatrix} = \begin{pmatrix} 1 \\ 0 \\ -1 \end{pmatrix}
\end{aligned}
$$

Da die Schar linear von $a$ abhängt, steht der Vektor $\vec{u} = \begin{pmatrix} 1 \\ 0 \\ -1 \end{pmatrix}$ automatisch senkrecht auf **allen** Richtungsvektoren $\vec{v}_a$ der Schar.

Als Stützpunkt wählen wir den gemeinsamen Schnittpunkt $P(2 \mid 3 \mid 5)$:

$$
\begin{aligned}
h: \vec{x} &= \begin{pmatrix} 2 \\ 3 \\ 5 \end{pmatrix} + k \begin{pmatrix} 1 \\ 0 \\ -1 \end{pmatrix} \quad \text{mit } k \in \mathbb{R}
\end{aligned}
$$