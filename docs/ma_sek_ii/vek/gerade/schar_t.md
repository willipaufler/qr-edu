# Geradenscharen und Spurpunkte - Tipp

### Zu Teilaufgabe a)

* **Nur zwei Spurpunkte:** Eine Komponente des Richtungsvektors muss $0$ werden. Da zwei Komponenten des Richungsvektors konstant sind, muss die $x_2$-Komponente $1 - \frac{a}{2} = 0$ gesetzt werden.
* **Spurpunkte:** Berechne den Schnittpunkt mit der $x_2 x_3$-Ebene ($x_1=0$) und der $x_1 x_2$-Ebene ($x_3=0$).
* **Gleichschenkligkeit:** Setze die Längen der Ortsvektoren $|\vec{OS_{23}}| = |\vec{OS_{12}}|$ gleich und löse nach $b$ auf.
* **Flächeninhalt:** Nutze nach dem Einsetzen von $b$ die Formel $A = \frac{1}{2} |\vec{OS_{23}} \times \vec{OS_{12}}|$.

### Zu Teilaufgabe b)

* **Gemeinsamer Punkt:** Setze $b=1$. Suche den Wert für den Geradenparameter $s$, für den der Scharparameter $a$ aus der $x_2$-Zeile verschwindet.
* Nutze diesen Geradenparameter, um dann den Punkt zu bestimmen.

### Zu Teilaufgabe c)

* **Orthogonal zu allen Schargeraden - Weg 1 (Skalarprodukt):** Ein Richtungsvektor $\vec{u} = \begin{pmatrix} u_1 \\ u_2 \\ u_3 \end{pmatrix}$ muss für **jedes** $a$ die Bedingung $\vec{v}_a \cdot \vec{u} = 0$ erfüllen:

$$
1 \cdot u_1 + \left(1-\frac{a}{2}\right) \cdot u_2 + 1 \cdot u_3 = 0
$$

* Sortiere nach Termen mit und ohne $a$. Beide Teile müssen unabhängig voneinander Null ergeben.

* **Orthogonal zu allen Schargeraden – Weg 2 (Kreuzprodukt):** 
  Wähle zwei konkrete Werte für $a$ (z. B. $a = 0$ und $a = 2$), um zwei Richtungsvektoren $\vec{v}_{a=0}$ und $\vec{v}_{a=2}$ zu erhalten. Berechne deren Kreuzprodukt:
  
  $$ \vec{u} = \vec{v}_{a=0} \times \vec{v}_{a=2} $$