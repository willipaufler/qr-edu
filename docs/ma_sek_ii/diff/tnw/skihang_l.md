# Beobachtungsturm - Lösung

### a) Nachweis der horizontalen Ausläufe
Zuerst bilden wir die Ableitung:
$$
\begin{aligned}
h(x) &= -0,05x^3 + 0,3x^2\\\\
h'(x) &= -0,15x^2 + 0,6x
\end{aligned}
$$


* **An der Stelle $x=0$:** 
$$
\begin{aligned}
h'(0) = -0,15\cdot0^2 + 0,6\cdot 0 = 0.
\end{aligned}
$$
* **An der Stelle $x=4$:** 
$$
\begin{aligned}
h'(4) &= -0,15\cdot 4^2 + 0,6\cdot 4\\\\
 &= -2,4 + 2,4 = 0.
\end{aligned}
$$

An beiden Stellen ist der Anstieg der Tangente Null, der Hang läuft also horizontal aus.

---

### b) Berechnung des Aussichtspunktes und der Turmhöhe

**1. Berührstelle $u$ der Sichtlinie finden:**

Die Sichtlinie ist eine Ursprungsgerade ($c=0$), daher gilt die Bedingung $h'(u) = \frac{h(u)}{u}$:
$$
\begin{aligned}
-0,15u^2 + 0,6u &= \frac{-0,05u^3 + 0,3u^2}{u} \\\\
-0,15u^2 + 0,6u &= -0,05u^2 + 0,3u \\\\
0,1u^2 - 0,3u &= 0 \\\\
0,1u(u - 3) &= 0
\end{aligned}
$$
Die Lösung $u=3$ liefert die Stelle, an der der Blick den Hügel streift.

**2. Steigung der Sichtlinie:**

$$
\begin{aligned}
m &= h'(3) = -0,15\cdot 3^2 + 0,6 \cdot 3\\\\
 &= 0,45
\end{aligned}
$$
Die Gleichung der Sichtlinie lautet somit $t(x) = 0,45x$.

**3. Koordinaten des Aussichtspunktes $B$ an der Stelle $x=4$**

$y_B = t(4) = 0,45 \cdot 4 = 1,8$.  
Der Aussichtspunkt hat die Koordinaten **$B(4 | 1,8)$**.

**4. Turmhöhe berechnen:**

Geländehöhe am Punkt $x=4$:
$$
\begin{aligned}
h(4) &= -0,05\cdot 4^3 + 0,3\cdot 4^2 \\\\
 &= 1,6
\end{aligned}
$$

Die Differenz beträgt: $1,8 - 1,6 = 0,2$ Längeneinheiten.  
Da $1\,\text{LE} = 100\,\text{m}$ entspricht, ergibt sich:
$0,2 \cdot 100\,\text{m} = 20\,\text{m}$.

**Ergebnis:** Der Aussichtspunkt liegt bei $B(4 | 1,8)$. Der Turm muss eine Höhe von **20 Metern** haben.