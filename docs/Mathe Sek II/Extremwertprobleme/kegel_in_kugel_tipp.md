# Kegel in Kugel - Tipp

### Aufgabe a) Extremwertbestimmung mit ($R=9$)

### 1. Skizze und Nebenbedingung

![Kegel in Kugel](/assets/images/kegel_in_kugel_light.png#only-light){width="60%"}
![Kegel in Kugel](/assets/images/kegel_in_kugel_dark.png#only-dark){width="60%"}
/// caption
Achsenschnitt der Kugel mit Kegel.
///

Betrachte den Achsenschnitt der Kugel. Die Grundfläche des Kegels hat den Radius $r$. Der Abstand dieser Fläche zum Kugelmittelpunkt ist $|h - R|$.  
Der Durchmesser des Kegelgrundkreises liegt im Achsenschnitt unterhalb des Mittelpunktes der Kugel. Zu jedem Durchmesser des Kegelgrundkreises oberhalb des Mittelpunktes gibt es einen zugehörigen Durchmesser unterhalb des Mittelpunktes mit gleicher Länge aber größerer Kegelhöhe. Daher genügt es für die Extremwertbetrachtung nur die Kegel mit einer Höhe von mindestens $|h - R|$ zu betrachten.

* Nutze den Satz des Pythagoras im rechtwinkligen Dreieck innerhalb der Kugel:
$$
r^2 + (h - R)^2 = R^2
$$

* Isoliere $r^2$, um es in die Volumenformel $V = \frac{1}{3}\pi r^2 h$ einzusetzen.



### Ableitung und Optimierung
* Die Zielfunktion $V(h)$ ist ein Polynom 3. Grades.
* Das Maximum liegt an der Stelle, an der $V'(h) = 0$ und $V''(h) < 0$ ist.

---

### Aufgabe b) *Zusatz* Allgemeiner Fall und Verhältnis
* Führe für Teil 2 die Rechnung mit dem Parameter $R$ statt der Zahl 9 durch.
* Nutze für das Verhältnis die Formeln $V_{\text{Kegel}} = \frac{1}{3}\pi r^2 h$ und $V_{\text{Kugel}} = \frac{4}{3}\pi R^3$.
