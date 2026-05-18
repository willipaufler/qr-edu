# Lösung: Optimimaler Ticketpreis

### 1. Aufstellen der Nachfragefunktion $n(p)$
Die Nachfrage verhält sich linear zum Preis $p$. Da pro Euro Preiserhöhung $20$ Besucher weniger kommen, beträgt die Steigung $m = -20$.
Mit dem Startpunkt ($500$ Besucher bei $20\,\text{€}$) bestimmen wir den Y-Achsenabschnitt $b$:
$$
\begin{aligned}
n(p) &= -20 \cdot p + b\\\\
500 &= -20 \cdot 20 + b\\\\
500 &= -400 + b \implies b = 900
\end{aligned}
$$

Die Nachfragefunktion lautet somit:
$$
\begin{aligned}
n(p) = 900 - 20p
\end{aligned}
$$

### 2. Aufstellen der Gewinnfunktion $G(p)$
Der Gewinn ergibt sich aus dem Produkt von Ticketpreis und Besucheranzahl:
$$
\begin{aligned}
G(p) &= p \cdot n(p) = p \cdot (900 - 20p)\\\\
G(p) &= -20p^2 + 900p
\end{aligned}
$$

### 3. Extremwertberechnung
Um das Gewinnmaximum zu ermitteln, bilden wir die Ableitungen nach $p$:
$$
\begin{aligned}
G'(p) &= -40p + 900\\\\
G''(p) &= -40
\end{aligned}
$$


Notwendige Bedingung $G'(p) = 0$ setzen:
$$
\begin{aligned}
-40p + 900 &= 0\\\\
p &= \frac{900}{40} = \mathbf{22,50}
\end{aligned}
$$

Hinreichende Bedingung prüfen:
$$
\begin{aligned}
G''(22,50) = -40 < 0 \implies \text{lokales Maximum}
\end{aligned}
$$

### 4. Berechnung des maximalen Gewinns
Setze den optimalen Preis $p = 22,50\,\text{€}$ in die Gewinnfunktion ein:
$$
\begin{aligned}
G(22,50) &= -20 \cdot (22,50)^2 + 900 \cdot 22,50\\\\
&= \mathbf{10125}
\end{aligned}
$$

### 5. Ergebnis
* Der optimale Ticketpreis liegt bei **$22,50\,\text{€}$**.
* Bei diesem Preis kommen noch $n(22,50) = 900 - 20 \cdot 22,50 = 450$ Besucher.
* Der maximal erzielbare Gewinn beträgt **$10.125\,\text{€}$**.