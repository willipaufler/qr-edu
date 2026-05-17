# Rechteck im Dreieck - Tipp


* **Hauptbedingung aufstellen:**  
Der Flächeninhalt des Rechtecks berechnet sich durch das Produkt seiner Seitenlängen. Wenn die Breite mit $x$ und die Höhe mit $y$ bezeichnet wird, gilt:
$A(x, y) = x \cdot y$

* **Nebenbedingung über Ähnlichkeit (Strahlensatz) aufstellen:**  
Das obere, abgeschnittene Dreieck über dem Rechteck ist ebenfalls gleichseitig und hat die Seitenlänge $x$. Seine Höhe beträgt $h_{oben} = \frac{\sqrt{3}}{2} \cdot x$. (Pythoagoras)  
Die Gesamthöhe des großen Dreiecks beträgt $h_{gesamt} = \frac{\sqrt{3}}{2} \cdot 2 = \sqrt{3}$.  
Da gilt $h_{gesamt} = h_{oben} + y$, kannst du daraus eine Beziehung zwischen $x$ und $y$ herstellen.

* **Alternativer Weg für die Nebenbedingung:**  
Betrachte die kleinen rechtwinkligen Dreiecke links oder rechts unten neben dem Rechteck.  
Die Grundseite eines solchen Dreiecks beträgt $\frac{2 - x}{2} = 1 - \frac{1}{2}x$.  
Da es sich um ein halbes gleichseitiges Dreieck handelt, beträgt der Innenwinkel $60^\circ$.  
Über den Tangens gilt:
$\tan(60^\circ) = \frac{y}{1 - \frac{1}{2}x}$ und damit $\sqrt{3} = \frac{y}{1 - \frac{1}{2}x}$

* **Zielfunktion und Extremum:**  
Löse die Nebenbedingung nach $y$ auf, setze sie in die Hauptbedingung ein und bestimme das Maximum der so entstandenen quadratischen Funktion mithilfe der ersten Ableitung.