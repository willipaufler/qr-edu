# Beobachtungsturm - Lösung

### a) Nachweis der horizontalen Ausläufe
Zuerst bilden wir die Ableitung:
$h(x) = -0,05x^3 + 0,3x^2 \implies h'(x) = -0,15x^2 + 0,6x$

* **An der Stelle $x=0$:** $h'(0) = -0,15(0)^2 + 0,6(0) = 0$.
* **An der Stelle $x=4$:** $h'(4) = -0,15(16) + 0,6(4) = -2,4 + 2,4 = 0$.

An beiden Stellen ist die Tangente waagerecht, der Hang läuft also horizontal aus.

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

$m = h'(3) = -0,15(3)^2 + 0,6(3) = -1,35 + 1,8 = 0,45$.  
Die Gleichung der Sichtlinie lautet somit $t(x) = 0,45x$.

**3. Koordinaten des Aussichtspunktes $B$ ($x=4$):**

$y_B = t(4) = 0,45 \cdot 4 = 1,8$.  
Der Aussichtspunkt hat die Koordinaten **$B(4 | 1,8)$**.

**4. Turmhöhe berechnen:**

Geländehöhe am Punkt $x=4$:
$h(4) = -0,05(4)^3 + 0,3(4)^2 = -3,2 + 4,8 = 1,6$.

Die Differenz beträgt: $1,8 - 1,6 = 0,2$ Längeneinheiten.
Da $1\,\text{LE} = 100\,\text{m}$ entspricht, ergibt sich:
$0,2 \cdot 100\,\text{m} = 20\,\text{m}$.

**Ergebnis:** Der Aussichtspunkt liegt bei $B(4 | 1,8)$. Der Turm muss eine Höhe von **20 Metern** haben.