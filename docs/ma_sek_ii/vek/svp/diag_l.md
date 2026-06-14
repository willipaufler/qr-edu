# Raumdiagonale - Lösung



### a) Schnittwinkel der Flächendiagonalen
Wir wählen die Vektoren für zwei Flächendiagonalen, die im Ursprung entspringen und auf den Seitenflächen liegen:
$$
\begin{aligned}
\vec{u} = \begin{pmatrix} a \\\\ a \\\\ 0 \end{pmatrix} \quad \text{und} \quad \vec{v} = \begin{pmatrix} a \\\\ 0 \\\\ a \end{pmatrix}
\end{aligned}
$$

Die Längen der Vektoren betragen jeweils:
$$
\begin{aligned}
|\vec{u}| = |\vec{v}| = \sqrt{a^2 + a^2 + 0} = a\sqrt{2}
\end{aligned}
$$

Eingesetzt in die Winkelformel:
$$
\begin{aligned}
\cos(\beta) = \frac{|a \cdot a + a \cdot 0 + 0 \cdot a|}{a\sqrt{2} \cdot a\sqrt{2}} = \frac{a^2}{2a^2} = 0{,}5
\end{aligned}
$$

Daraus ergibt sich der Winkel **$\beta = 60^\circ$**.

---

### b) Schnittwinkel der Raumdiagonalen
Wir betrachten die Vektoren vom Mittelpunkt des Würfels $M(0{,}5a|0{,}5a|0{,}5a)$ zu zwei benachbarten Ecken auf einer Kante:
$$
\begin{aligned}
\vec{u} = \begin{pmatrix} 0{,}5a \\ 0{,}5a \\ 0{,}5a \end{pmatrix} \quad \text{und} \quad \vec{v} = \begin{pmatrix} -0{,}5a \\ 0{,}5a \\ 0{,}5a \end{pmatrix}
\end{aligned}
$$

Die Längen der halben Raumdiagonalen betragen jeweils:
$$
\begin{aligned}
|\vec{u}| = |\vec{v}| = \sqrt{0{,}25a^2 + 0{,}25a^2 + 0{,}25a^2} = \sqrt{0{,}75a^2} = \frac{a\sqrt{3}}{2}
\end{aligned}
$$

Eingesetzt in die Winkelformel:
$$
\begin{aligned}
\cos(\alpha) = \frac{|-0{,}25a^2 + 0{,}25a^2 + 0{,}25a^2|}{\frac{a\sqrt{3}}{2} \cdot \frac{a\sqrt{3}}{2}} = \frac{0{,}25a^2}{0{,}75a^2} = \frac{1}{3}
\end{aligned}
$$

Daraus ergibt sich der Winkel **$\alpha \approx 70{,}53^\circ$**.

---

### c) Geometrischer Vergleich ohne Rechnung
* **Das Dreieck der Flächendiagonalen:** Verbindet man die Endpunkte der beiden betrachteten Flächendiagonalen, entsteht eine dritte Flächendiagonale des Würfels. Das resultierende Dreieck besteht also aus drei identischen Flächendiagonalen (alle haben die Länge $a\sqrt{2}$). Es ist somit **gleichseitig**, weshalb jeder Innenwinkel – und damit auch der Schnittwinkel – exakt **60°** betragen muss.
* **Das Dreieck der Raumdiagonalen:** Zwei halbe Raumdiagonalen bilden zusammen mit einer Würfelkante ein Dreieck. Die Schenkel haben die Länge $s = \frac{a\sqrt{3}}{2} \approx 0{,}866a$, während die Basis (die Würfelkante) die Länge $a$ besitzt.
* **Argumentation:** Da die Basis $a$ größer ist als die Schenkel ($a > 0{,}866a$), handelt es sich um ein gleichschenkliges Dreieck, bei dem die **längste Seite dem gesuchten Schnittwinkel gegenüberliegt**. Ein Dreieck mit einer längeren Basis wird im Vergleich zum gleichseitigen Dreieck "breiter aufgespreizt". Daraus folgt zwingend, dass der gegenüberliegende Winkel größer als **60°** sein muss ($\alpha > \beta$).






