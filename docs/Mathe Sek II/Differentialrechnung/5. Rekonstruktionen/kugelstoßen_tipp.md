# Kugelstoßen - Tipp

Hier sind die Hinweise zur Modellierung der Flugkurve:

1.  **Start- und Landepunkt:** 
    * Die Kugel startet bei $x = 0$ in einer bestimmten Höhe.
    * Die Kugel landet bei $x = 19,5$ auf dem Boden ($y = 0$).

2.  **Der Aufprallwinkel:** 
    * Ein Winkel am Boden gibt dir die Steigung der Tangente an dieser Stelle an. 
    * Es gilt: $f'(x) = \tan(\alpha)$. 
    * Beachte: Da die Kugel fällt, ist die Steigung negativ. Ein Aufprallwinkel von $30^\circ$ zur Horizontalen entspricht also einer Steigung von $\tan(-30^\circ)$.

3.  **Abstoßwinkel und Höhe:**
    * Die maximale Höhe ist der Funktionswert am Scheitelpunkt ($f'(x) = 0$).
    * Der Abstoßwinkel ist der Steigungswinkel am Startpunkt ($x = 0$). Berechne diesen über $\alpha = \arctan(f'(0))$.