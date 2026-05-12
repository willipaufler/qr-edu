# Rettungseinsatz im Gebirge - Lösung

### a) Berechnen der Geschwindigkeit
Verschiebungsvektor $\vec{v}$ pro Minute im Koordinatensystem:
$$
\begin{aligned}
\vec{v} &= \vec{PQ} \\\\
\vec{v} &= \begin{pmatrix} 4,1 - 2 \\\\ 7,8 - 5 \\\\ 0,8 - 0,8 \end{pmatrix} = \begin{pmatrix} 2,1 \\\\ 2,8 \\\\ 0 \end{pmatrix}
\end{aligned}
$$

Berechnung der Länge im Koordinatensystem (in LE):
$$
\begin{aligned}
|\vec{v}| &= \sqrt{2,1^2 + 2,8^2 + 0^2} = 3,5
\end{aligned}
$$

Umrechnung in km/min ($1$ LE = $100$ m = $0,1$ km):
$$
\begin{aligned}
v_{min} &= 3,5 \cdot 0,1= 0,35 \text{ km/min}
\end{aligned}
$$

Umrechnung in km/h:
$$
\begin{aligned}
v_{h} &= 0,35 \cdot 60 = 210 \text{ km/h}
\end{aligned}
$$

Die Geschwindigkeit beträgt $210$ km/h.

### b) Bestimmen der Position nach weiteren 4, also insgesamt 5 Minuten
Wir addieren das Fünffache des Minutenvektors zum Startpunkt $P$:

$$
\begin{aligned}
\vec{r}_{5} &= \vec{OP} + 5 \cdot \vec{v} \\\\
\vec{r}_{5} &= \begin{pmatrix} 2 \\\\ 5 \\\\ 0,8 \end{pmatrix} + 5 \cdot \begin{pmatrix} 2,1 \\\\ 2,8 \\\\ 0 \end{pmatrix}= \begin{pmatrix} 12,5 \\\\ 19 \\\\ 0,8 \end{pmatrix}
\end{aligned}
$$

Der Hubschrauber befindet sich nach 5 Minuten im Punkt $R(12,5 \mid 19 \mid 0,8)$.