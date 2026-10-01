# Tipp – Gerade, Ebene und Kugel

## Teil a)
* Der Ansatz prüft die **lineare Unabhängigkeit** der beiden Richtungsvektoren der Ebene und des Richtungsvektors der Geraden.
* Existiert nur die triviale Lösung $r = s = t = 0$, lässt sich der Richtungsvektor der Geraden nicht durch die Richtungsvektoren der Ebene darstellen.
* Das bedeutet: Die Gerade verläuft weder parallel zur Ebene noch liegt sie in ihr, wodurch genau ein Schnittpunkt existieren muss.

---

## Teil b)
* **Schnittwinkel $\alpha$:** 
    * Berechne zuerst den Normalenvektor $\vec{n} = \vec{u} \times \vec{v}$ der Ebene $E$.
    * Nutze die Formel $\sin(\alpha) = \frac{|\vec{v}_g \cdot \vec{n}|}{|\vec{v}_g| \cdot |\vec{n}|}$.
* **Schnittpunkt $S$:**
     * Wandle $E$ in die Koordinatenform um ($n_1 x_1 + n_2 x_2 + n_3 x_3 = d$).
     * Setze die Koordinaten der Geraden $g(t)$ in die Koordinatengleichung ein, um den Parameter $t_S$ zu bestimmen.
     * Setze $t_S$ in $g$ ein, um den Ortsvektor von $S$ zu berechnen.

---

## Teil c)
* Der Berührpunkt $F$ ist der **Lotfußpunkt** des Kugelmittelpunkts $M$ auf die Ebene $E$.
* Stelle eine Lotgerade $h$ auf: Stützpunkt ist $M$, Richtungsvektor ist der Normalenvektor $\vec{n}$ der Ebene $E$.
* Schneide $h$ mit $E$, um $F$ zu erhalten.
* Der Radius $R$ ist der Abstand zwischen Mittelpunkt und Berührpunkt: $R = |\vec{MF}|$.

---

## Teil d)
* **Weg 1 (Direkter Nachweis für gegebenes $T$):**
    * Überprüfe, ob $T$ auf der Kugel liegt ($|\vec{MT}| = R$).
    * Überprüfe, ob der Berührradius orthogonal zur Geraden steht ($\vec{MT} \cdot \vec{v}_g = 0$).

* **Weg 2 (Kniffliger – Berechnen von $T$ als Lotfußpunkt):**
    * $T$ muss der Lotfußpunkt von $M$ auf die Gerade $g$ sein.
    * Drücke den allgemeinen Punkt $T(t)$ auf $g$ aus und fordere $\vec{MT}(t) \cdot \vec{v}_g = 0$.
    * Bestimme $t$, erhalte $T$ und zeige anschließend, dass der Abstand $|\vec{MT}|$ exakt dem Kugelradius $R$ entspricht.