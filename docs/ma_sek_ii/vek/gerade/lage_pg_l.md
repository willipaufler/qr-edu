# Lagebeziehung zwischen Punkt und Gerade - Lösung

### a) Untersuchung des Punktes $P(5 \mid 6 \mid 2)$

**1. Punktprobe:**

Gleichsetzen des Ortsvektors von $P$ mit der Geradengleichung $g$:
$$
\begin{aligned}
\begin{pmatrix} 5 \\\\ 6 \\\\ 2 \end{pmatrix} &= \begin{pmatrix} 1 \\\\ 4 \\\\ -2 \end{pmatrix} + t \begin{pmatrix} 2 \\\\ 1 \\\\ 2 \end{pmatrix}
\end{aligned}
$$

Zeilenweises Aufstellen der Gleichungen:
$$
\begin{aligned}
(1) \quad 5 &= 1 + 2t \implies 2t = 4 \implies t = 2 \\\\
(2) \quad 6 &= 4 + t \implies t = 2 \\\\
(3) \quad 2 &= -2 + 2t \implies 2t = 4 \implies t = 2
\end{aligned}
$$

Da für alle drei Koordinaten der eindeutige Parameterwert $t = 2$ entsteht, liegt der Punkt $P$ auf der Geraden $g$.

**Ergebnis:** Der Punkt $P$ liegt auf der Geraden $g$ ($P \in g$). Der Abstand beträgt $0\,\text{LE}$.

---

### b) Untersuchung des Punktes $Q(1 \mid 7 \mid 1)$

**1. Punktprobe:**

Gleichsetzen des Ortsvektors von $Q$ mit der Geradengleichung $g$:
$$
\begin{aligned}
\begin{pmatrix} 1 \\\\ 7 \\\\ 1 \end{pmatrix} &= \begin{pmatrix} 1 \\\\ 4 \\\\ -2 \end{pmatrix} + t \begin{pmatrix} 2 \\\\ 1 \\\\ 2 \end{pmatrix}
\end{aligned}
$$

Zeilenweises Aufstellen der Gleichungen:
$$
\begin{aligned}
(1) \quad 1 &= 1 + 2t \implies 2t = 0 \implies t = 0 \\\\
(2) \quad 7 &= 4 + t \implies t = 3
\end{aligned}
$$

Da $t = 0 \neq 3$ ist, führt die Punktprobe zu einem Widerspruch. Der Punkt $Q$ liegt nicht auf der Geraden $g$ ($Q \notin g$).

**2. Abstandsberechnung Weg 1: Lotfußpunktverfahren**

Ein allgemeiner Punkt auf der Geraden $g$ hat die Form $S_t(1 + 2t \mid 4 + t \mid -2 + 2t)$.

Der Verbindungsvektor von $S_t$ zum Punkt $Q(1 \mid 7 \mid 1)$ lautet:
$$
\begin{aligned}
\vec{S_t Q} &= \begin{pmatrix} 1 - (1 + 2t) \\\\ 7 - (4 + t) \\\\ 1 - (-2 + 2t) \end{pmatrix} = \begin{pmatrix} -2t \\\\ 3 - t \\\\ 3 - 2t \end{pmatrix}
\end{aligned}
$$

Der Verbindungsvektor muss senkrecht zum Richtungsvektor $\vec{v} = \begin{pmatrix} 2 \\ 1 \\ 2 \end{pmatrix}$ der Geraden $g$ stehen:
$$
\begin{aligned}
\vec{S_t Q} \cdot \vec{v} &= 0 \\\\
\begin{pmatrix} -2t \\\\ 3 - t \\\\ 3 - 2t \end{pmatrix} \cdot \begin{pmatrix} 2 \\\\ 1 \\\\ 2 \end{pmatrix} &= 0 \\\\
-4t + 3 - t + 6 - 4t &= 0 \\\\
t &= 1
\end{aligned}
$$

Einsetzen von $t = 1$ in den Verbindungsvektor $\vec{S_t Q}$:
$$
\begin{aligned}
\vec{S_1 Q} &= \begin{pmatrix} -2 \cdot 1 \\\\ 3 - 1 \\\\ 3 - 2 \cdot 1 \end{pmatrix} = \begin{pmatrix} -2 \\\\ 2 \\\\ 1 \end{pmatrix}
\end{aligned}
$$

Betrag berechnen (Länge des Lotvektors):
$$
\begin{aligned}
d(Q, g) = |\vec{S_1 Q}| &= \sqrt{(-2)^2 + 2^2 + 1^2} = \sqrt{4 + 4 + 1} = \sqrt{9} = 3
\end{aligned}
$$

**3. Abstandsberechnung Weg 2: Alternativ über das Kreuzprodukt**

Mit dem Stützpunkt $A(1 \mid 4 \mid -2)$ und dem Richtungsvektor $\vec{v} = \begin{pmatrix} 2 \\ 1 \\ 2 \end{pmatrix}$ der Geraden $g$:

Verbindungsvektor $\vec{AQ} = \vec{OQ} - \vec{OA}$:
$$
\begin{aligned}
\vec{AQ} &= \begin{pmatrix} 1 - 1 \\\\ 7 - 4 \\\\ 1 - (-2) \end{pmatrix} = \begin{pmatrix} 0 \\\\ 3 \\\\ 3 \end{pmatrix}
\end{aligned}
$$

Kreuzprodukt $\vec{AQ} \times \vec{v}$ berechnen:
$$
\begin{aligned}
\vec{AQ} \times \vec{v} &= \begin{pmatrix} 0 \\\\ 3 \\\\ 3 \end{pmatrix} \times \begin{pmatrix} 2 \\\\ 1 \\\\ 2 \end{pmatrix} = \begin{pmatrix} 3 \cdot 2 - 3 \cdot 1 \\\\ 3 \cdot 2 - 0 \cdot 2 \\\\ 0 \cdot 1 - 3 \cdot 2 \end{pmatrix} = \begin{pmatrix} 3 \\\\ 6 \\\\ -6 \end{pmatrix}
\end{aligned}
$$

Beträge berechnen:
$$
\begin{aligned}
|\vec{AQ} \times \vec{v}| &= \sqrt{3^2 + 6^2 + (-6)^2} = \sqrt{9 + 36 + 36} = \sqrt{81} = 9 \\\\
|\vec{v}| &= \sqrt{2^2 + 1^2 + 2^2} = \sqrt{4 + 1 + 4} = \sqrt{9} = 3
\end{aligned}
$$

Einsetzen in die Abstandsformel:
$$
\begin{aligned}
d(Q, g) &= \frac{|\vec{AQ} \times \vec{v}|}{|\vec{v}|} = \frac{9}{3} = 3
\end{aligned}
$$

**Ergebnis:** Der Punkt $Q$ liegt nicht auf $g$. Der Abstand des Punktes $Q$ zur Geraden $g$ beträgt genau $3\,\text{LE}$.