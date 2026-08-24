# Kleinstes Dreieck - Lösung

### a) Beschreibung der Lage im Raum

* **Punkte $Q$ und $P$:** Der Punkt $Q(8 \mid 6 \mid 0)$ liegt in der $x_1 x_2$-Ebene. Der Punkt $P(8 \mid 6 \mid 5)$ liegt vertikal darüber im Abstand von $5\,\text{LE}$. Die Strecke $PQ$ verläuft somit parallel zur $x_3$-Achse.
* **Gerade $g$:** Da sowohl die $x_3$-Koordinate des Stützvektors als auch die des Richtungsvektors $0$ betragen, verläuft die Gerade $g$ komplett in der $x_1 x_2$-Ebene.

---

### b) Bestimmung des Punktes $S$ und des minimalen Flächeninhalts

**1. Ansatz über den minimalen Abstand:**

Für das Dreieck $PQS$ wählen wir die Strecke $PQ$ als Grundseite:
$$
\begin{aligned}
g_{\text{Dreieck}} &= |\vec{PQ}| = \left| \begin{pmatrix} 8-8 \\\\ 6-6 \\\\ 5-0 \end{pmatrix} \right| = \left| \begin{pmatrix} 0 \\\\ 0 \\\\ 5 \end{pmatrix} \right| = 5
\end{aligned}
$$

Der Flächeninhalt berechnet sich durch $A = \frac{1}{2} \cdot |\vec{PQ}| \cdot h$. Da $|\vec{PQ}| = 5$ konstant ist, ist der Flächeninhalt genau dann minimal, wenn der Abstand $h$ des Punktes $S \in g$ zur Strecke $PQ$ (bzw. zum Punkt $Q$, da $g$ in der $x_1 x_2$-Ebene liegt) minimal ist.

Ein allgemeiner Punkt $S_t$ auf der Geraden $g$ hat die Koordinaten:
$$
\begin{aligned}
S_t(8 + 2t \mid 14 - t \mid 0)
\end{aligned}
$$

**2. Orthogonalitätsbedingung aufstellen:**

Der Verbindungsvektor $\vec{QS}_t$ lautet:
$$
\begin{aligned}
\vec{QS}_t &= \begin{pmatrix} 8 + 2t - 8 \\\\ 14 - t - 6 \\\\ 0 - 0 \end{pmatrix} = \begin{pmatrix} 2t \\\\ 8 - t \\\\ 0 \end{pmatrix}
\end{aligned}
$$

Der Vektor $\vec{QS}_t$ muss orthogonal zum Richtungsvektor $\vec{v} = \begin{pmatrix} 2 \\ -1 \\ 0 \end{pmatrix}$ der Geraden $g$ sein:
$$
\begin{aligned}
\vec{QS}_t \cdot \vec{v} &= 0 \\\\
\begin{pmatrix} 2t \\ 8 - t \\ 0 \end{pmatrix} \cdot \begin{pmatrix} 2 \\ -1 \\ 0 \end{pmatrix} &= 0 \\\\
2t \cdot 2 + (8 - t) \cdot (-1) + 0 \cdot 0 &= 0 \\\\
4t - 8 + t &= 0 \\\\
5t &= 8 \\\\
t &= \frac{8}{5} = 1{,}6
\end{aligned}
$$

**3. Koordinaten des Punktes $S$ berechnen:**

Einsetzen von $t = \frac{8}{5}$ in die Geradengleichung:
$$
\begin{aligned}
\vec{OS} &= \begin{pmatrix} 8 \\\\ 14 \\\\ 0 \end{pmatrix} + \frac{8}{5} \begin{pmatrix} 2 \\\\ -1 \\\\ 0 \end{pmatrix} = \begin{pmatrix} \frac{56}{5} \\\\ \frac{62}{5} \\\\ 0 \end{pmatrix}
\end{aligned}
$$

Der gesuchte Punkt lautet $S\left(\frac{56}{5} \mid \frac{62}{5} \mid 0\right)$ bzw. $S(11{,}2 \mid 12{,}4 \mid 0)$.

**4. Minimalen Flächeninhalt berechnen:**

Länge des Verbindungsvektors $\vec{QS}$ (Höhe $h$):
$$
\begin{aligned}
\vec{QS} &= \begin{pmatrix} 2 \cdot \frac{8}{5} \\\\ 8 - \frac{8}{5} \\\\ 0 \end{pmatrix} = \begin{pmatrix} \frac{16}{5} \\\\ \frac{32}{5} \\\\ 0 \end{pmatrix} \\\\
h = |\vec{QS}| &= \sqrt{\left(\frac{16}{5}\right)^2 + \left(\frac{32}{5}\right)^2 + 0^2} = \sqrt{\frac{256}{25} + \frac{1024}{25}} = \sqrt{\frac{1280}{25}} = \frac{16\sqrt{5}}{5} \approx 7{,}16
\end{aligned}
$$

Flächeninhalt $A_{\text{min}}$:
$$
\begin{aligned}
A_{\text{min}} &= \frac{1}{2} \cdot 5 \cdot \frac{16\sqrt{5}}{5} = 8\sqrt{5} \approx 17{,}89\,\text{FE}
\end{aligned}
$$

Der minimale Flächeninhalt des Dreiecks $PQS$ beträgt $8\sqrt{5}$ (ca. $17{,}89$) Flächeneinheiten.