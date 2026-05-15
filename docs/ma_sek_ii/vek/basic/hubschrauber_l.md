# Rettungseinsatz im Gebirge - Lösung

### a) Berechnen der Geschwindigkeit
Verschiebungsvektor $\vec{v}$ pro Minute im Koordinatensystem:
$$
\begin{aligned}
\vec{v} &= \vec{PQ} \\\\
\vec{v} &= \begin{pmatrix} 41 - 20 \\\\ 78 - 50 \\\\ 8 - 8 \end{pmatrix} = \begin{pmatrix} 21 \\\\ 28 \\\\ 0 \end{pmatrix}
\end{aligned}
$$

Berechnung der Länge im Koordinatensystem (in LE):
$$
\begin{aligned}
|\vec{v}| &= \sqrt{21^2 + 28^2 + 0^2} = 35
\end{aligned}
$$

Umrechnung in km/min ($1$ LE = $100$ m = $0,1$ km):
$$
\begin{aligned}
v_{min} &= 35 \cdot 0,1= 3,5 \text{ km/min}
\end{aligned}
$$

Umrechnung in km/h:
$$
\begin{aligned}
v_{h} &= 3,5 \cdot 60 = 210 \text{ km/h}
\end{aligned}
$$

Die Geschwindigkeit beträgt $210$ km/h.

### b) Bestimmen der Position nach weiteren 4, also insgesamt 5 Minuten
Wir addieren das Fünffache des Minutenvektors zum Startpunkt $P$:
$$
\begin{aligned}
\vec{r}_5 &= \vec{OP} + 5 \cdot \vec{v} \\\\
\vec{r}_5 &= \begin{pmatrix} 20 \\\\ 50 \\\\ 8 \end{pmatrix} + 5 \cdot \begin{pmatrix} 21 \\\\ 28 \\\\ 0 \end{pmatrix} = \begin{pmatrix} 125 \\\\ 190 \\\\ 8 \end{pmatrix}
\end{aligned}
$$

Der Hubschrauber befindet sich nach 5 Minuten im Punkt $R(125 \mid 190 \mid 8)$.