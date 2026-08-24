# Nächtlicher Einsatz am Bauernhof - Tipp

### Zu Teilaufgabe a)

* **Startpunkt bestimmen:** Berechne die Koordinaten des Mittelpunkts $M_{DA}$ der Hofseite $DA$ zwischen $D(0 \mid 0 \mid 0)$ und $A(40 \mid 0 \mid 0)$:

$$
\vec{OM_{DA}} = \frac{1}{2} (\vec{OD} + \vec{OA})
$$

* **Geradengleichung:** Verwende $M_{DA}$ als Stützpunkt und den Verbindungsvektor $\vec{M_{DA}C}$ als Richtungsvektor der Geraden $g$.

### Zu Teilaufgabe b)

* **Minimaler Abstand:** Der Bewegungsmelder schlägt genau dann Alarm, wenn der kleinste Abstand der Geraden $g$ (Laufweg) zum Punkt $M(0 \mid 30 \mid 4)$ kleiner oder gleich der Reichweite von $10\,\text{m}$ ist.
* **Lotfußpunktverfahren:**
    * Stelle den allgemeinen Verbindungsvektor $\vec{S_t M}$ zwischen einem beliebigen Punkt $S_t$ auf der Geraden $g$ und dem Punkt $M$ auf.
    * Bestimme den Parameter $t$ über die Orthogonalitätsbedingung $\vec{S_t M} \cdot \vec{v}_g = 0$.
    * Prüfe, ob $t$ im relevanten Bereich $[0; 20]$ liegt (Strecke zwischen $M_{DA}$ und $C$).
    * Berechne den Betrag des Vektors $|\vec{S_t M}|$ und vergleiche ihn mit den $10\,\text{m}$ Reichweite.
* **Alternativ über das Kreuzprodukt:** Nutze die Formel $d = \frac{|(\vec{OM} - \vec{OM_{DA}}) \times \vec{v}_g|}{|\vec{v}_g|}$.