# Es regnet - Tipp

### Zu Teilaufgabe a) Zuflussmenge
Die Funktion $z(t)$ gibt an, wie viel Liter pro Stunde zufließen. Um die Gesamtmenge zu erhalten, musst du die Rate über den Zeitraum aufsummieren.
* **Vorgehen:** Berechne das Integral $\int_{0}^{4} z(t) \, dt$.

### Zu Teilaufgabe b) Füllhöhe
Das Volumen eines Zylinders berechnet sich durch $V = G \cdot h$, also $V = \pi \cdot r^2 \cdot h$.

* **Einheiten:** Achte darauf, dass $1\,\text{Liter} = 1000\,\text{cm}^3$ entspricht. Wenn der Radius in cm gegeben ist, solltest du das Volumen in $\text{cm}^3$ umrechnen, um die Höhe in cm zu erhalten.
* **Bestand:** Die Höhe $H(t)$ bezieht sich auf das Gesamtvolumen (Anfangsbestand + Zufluss).

### Zu Teilaufgabe c) Hahn offen
Ab $t = 2,5$ gibt es zwei Prozesse:

1. Der Regen fließt weiter mit $z(t)$ zu.
2. Wasser fließt mit einer konstanten Rate ab.


**Ansatz:** Suche den Zeitpunkt $T$, für den gilt: 
$$
\begin{aligned}\int_{2,5}^{T} (\text{Zufluss} - \text{Abfluss}) \, dt + (\text{Volumenzuwachs bis 2,5h}) = 0
\end{aligned}
$$ 
oder einfacher: Wann ist das zusätzliche Volumen seit Beginn des Schauers wieder abgeflossen?  
**Achtung Einheit:** Der Abfluss ist in Litern pro **Minute** angegeben. Rechne diesen erst in Liter pro **Stunde** um, damit er zur Funktion $z(t)$ passt.