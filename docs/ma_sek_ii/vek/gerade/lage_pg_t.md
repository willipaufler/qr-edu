# Lagebeziehung zwischen Punkt und Gerade - Tipp

### Zu Teilaufgabe a)

* **Punktprobe:** Setze den Ortsvektor des Punktes $P$ in die Geradengleichung $g$ ein.
* Entsteht für alle drei Koordinatenzeilen derselbe Parameterwert $t$, liegt der Punkt $P$ auf der Geraden $g$. Der Abstand beträgt in diesem Fall $0$.

### Zu Teilaufgabe b)

* **Punktprobe:** Führe zuerst die Punktprobe für $Q$ analog zu Teilaufgabe a) durch. Führt das System zu einem Widerspruch, liegt $Q$ nicht auf $g$.
* **Abstandsberechnung – Alternative 1 (Lotfußpunktverfahren):**

    * Stelle den allgemeinen Verbindungsvektor $\vec{S_t Q}$ zwischen einem beliebigen Geradenpunkt $S_t(1+2t \mid 4+t \mid -2+2t)$ und dem Punkt $Q(1 \mid 7 \mid 1)$ auf.
    * Bestimme $t$ über die Orthogonalitätsbedingung $\vec{S_t Q} \cdot \vec{v}_g = 0$.
    * Berechne den Betrag des Vektors $\vec{S_t Q}$ für diesen Parameter $t$, um den Abstand $d(Q, g)$ zu erhalten.

* **Abstandsberechnung – Alternative 2 (Kreuzprodukt-Formel):**
  Nutze die Formel für den Abstand eines Punktes $Q$ von einer Geraden mit Stützpunkt $A$ und Richtungsvektor $\vec{v}$:
$$
d(Q, g) = \frac{|(\vec{OQ} - \vec{OA}) \times \vec{v}|}{|\vec{v}|}
$$