# Extremale Fläche - Tipp

Um den Parameter $a$ für einen minimalen Flächeninhalt zu finden, folge diesen Schritten:

---

### 1. Funktion vorbereiten
Multipliziere den Funktionsterm $f(x) = x(x - a)(x - 2)$ vollständig aus. Das macht das Integrieren im nächsten Schritt wesentlich einfacher.

### 2. Zielfunktion aufstellen
Der Graph schließt mit der x-Achse zwei Teilflächen ein:
* Teilfläche $A_1$ im Intervall $[0; a]$ (oberhalb der x-Achse)
* Teilfläche $A_2$ im Intervall $[a; 2]$ (unterhalb der x-Achse)

Die Gesamte Fläche $A(a)$ ist die Summe der Beträge:
$$A(a) = \int_{0}^{a} f(x) \, dx - \int_{a}^{2} f(x) \, dx$$
*(Hinweis: Das Minus vor dem zweiten Integral sorgt dafür, dass die negative Fläche positiv gezählt wird.)*

### 3. Extremwert bestimmen
Du hast nun eine Funktion $A(a)$, die nur noch vom Parameter $a$ abhängt.
1.  Bilde die Ableitung $A'(a)$.
2.  Setze die Ableitung gleich Null ($A'(a) = 0$), um das Minimum zu finden.
3.  Überprüfe mit der zweiten Ableitung oder durch Überlegung, ob es sich wirklich um ein Minimum handelt.

### 4. Flächeninhalt berechnen
Vergiss nicht, am Ende den gefundenen Wert für $a$ wieder in deine Formel für $A(a)$ einzusetzen, um den minimalen Flächeninhalt anzugeben.