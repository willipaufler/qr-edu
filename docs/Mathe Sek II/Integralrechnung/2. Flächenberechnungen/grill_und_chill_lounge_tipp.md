# Grill und Chill Lounge - Tipp



### 1. Rekonstruktion der Randfunktion

* Die nördliche Begrenzung ist eine Funktion 3. Grades: $g(x) = ax^3 + bx^2 + cx + d$.
* **Bedingungen:** Der Garten muss "knickfrei" anschließen. Das bedeutet:
  1. $g(2) = 2$ und $g(4) = 4$ (Punkte verbinden).
  2. $g'(2) = 0$ und $g'(4) = 0$ (waagerechte Tangenten an den Übergängen).
* Löse das daraus resultierende Gleichungssystem, um $g(x)$ zu bestimmen.

### 2. Zu Teilaufgabe a) (Nord-Süd-Linie)

* Die "Nord-Süd-Linie" ist eine vertikale Gerade $x = t$.
* Diese soll die Fläche des neuen Gartens halbieren.
* **Ansatz:** $\int_{2}^{t} g(x) \, dx = \int_{t}^{4} g(x) \, dx$ oder $\int_{2}^{t} g(x) \, dx = \frac{1}{2} \int_{2}^{4} g(x) \, dx$.
* Löse die Integralgleichung nach $t$ auf.

### 3. Zu Teilaufgabe b) (Zaun durch den Wendepunkt)

* **Wendepunkt:** Bestimme zuerst $W(x_w | y_w)$ durch $g''(x) = 0$.
* **Gerade:** Der Zaun ist eine lineare Funktion $f(x) = mx + n$, die durch $W$ verläuft.
* **Flächenbedingung:** Der Zaun teilt die Fläche so, dass "Jans zusätzlicher Garten bis zum Wendepunkt plus der Garten unterhalb des Zauns halb so groß ist wie der gesamte Garten".
* Beachte den Maßstab: $1 \text{ LE} = 10 \text{ m}$.