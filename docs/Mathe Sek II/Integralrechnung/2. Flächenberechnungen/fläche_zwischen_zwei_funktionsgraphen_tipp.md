# Fläche zwischen zwei Funktionsgraphen - Tipp

Hier sind Hinweise, wie du die einzelnen Teilaufgaben dieser komplexen Analyse löst:

---

### Zu Teilaufgabe a)
* **Schnittpunkte finden:** Setze $f(x) = g(x)$. Multipliziere die gesamte Gleichung mit dem Hauptnenner (4), um die Brüche loszuwerden. Du erhältst eine quadratische Gleichung.
* **Integral berechnen:** Nutze das Integral der Differenzfunktion $h(x) = g(x) - f(x)$ zwischen den gefundenen Schnittstellen. Prüfe vorher, welche Funktion im Intervall "oben" liegt.

### Zu Teilaufgabe b)
* **Sekante bestimmen:** Berechne die y-Werte der Schnittpunkte aus a) und stelle die Geradengleichung $s(x) = mx + b$ durch diese zwei Punkte auf.
* **Teilflächen:** Die Gerade teilt die Fläche in zwei Teile. Berechne das Integral zwischen der oberen Funktion (Parabel $g$) und der Geraden $s$. Das Verhältnis der Teilfläche zur Restfläche (Gesamtfläche minus Teilfläche) ist das Teilungsverhältnis.

### Zu Teilaufgabe c)
* **Ursprungsgerade:** Eine Ursprungsgerade hat die Form $y = mx$.
* **Ansatz:** Die Fläche von der linken Schnittstelle ($x = -1$) bis zur neuen Schnittstelle mit der Geraden (abhängig von $m$) unter der Differenzfunktion muss genau der Hälfte des Ergebnisses aus a) entsprechen. Nutze hierfür dein CAS-Gerät.

### Zu Teilaufgabe d)
* **Streckungsfaktor:** Eine Verhundertfachung des Flächeninhalts bei gleicher Form entspricht einer **zentrischen Streckung**. 
* **Wichtig:** Wenn die Fläche um den Faktor $k^2 = 100$ wachsen soll, müssen die Längen (x- und y-Werte) um den Faktor $k = 10$ gestreckt werden. Ersetze $x$ durch $\frac{x}{10}$ und multipliziere den gesamten Funktionsterm mit $10$.