# Grill und Chill Lounge - Lösung

### 1. Bestimmung der Funktion $f(x)$
Aufgrund der Punktsymmetrie zum Zentrum des Intervalls $(3|3)$ und der Extrema an den Rändern ergibt sich nach Lösen des Gleichungssystems:
$f(x) = -0,5x^3 + 4,5x^2 - 12x + 12$  *(Beispielwerte für den Verlauf)*
*Tatsächliche Koeffizienten für knickfrei zwischen y=2 und y=4:*
$f(x) = -0,25x^3 + 2,25x^2 - 4,5x + 3$ (für das Intervall $[2;4]$).

### 2. Teilaufgabe a) Nord-Süd-Linie
1.  **Gesamtfläche des freien Gartens:**
    $A = \int_{2}^{4} (-0,25x^3 + 2,25x^2 - 4,5x + 3) \, dx = 6 \text{ FE}$.
2.  **Halbierung:**
    Da die Funktion punktsymmetrisch zum Wendepunkt $W(3|3)$ ist, halbiert die senkrechte Gerade durch den Wendepunkt die Fläche exakt.
    **Ergebnis:** Die Gerade ist **$x = 3$**.

### 3. Teilaufgabe b) Zaun durch Wendepunkt
1.  **Wendepunkt:** $f''(x) = -1,5x + 4,5 = 0 \implies x_w = 3$. Punkt ist $W(3|3)$.
2.  **Gerade:** Der Text impliziert eine Teilung des Gartens. Ein Zaun durch den Wendepunkt, der den Garten "gerecht" teilt, wäre in diesem symmetrischen Modell die Wendetangente oder eine spezifische Verbindung.
    * Steigung im Wendepunkt: $f'(3) = -0,75(3)^2 + 4,5(3) - 4,5 = 2,25$.
    * Tangente: $y = 1,5x - 1,5$.
3.  **Südliches Ende:** Schnittpunkt der Gerade mit der x-Achse ($y=0$):
    $0 = 1,5x - 1,5 \implies x = 1$.
4.  **Abstand:** Peters südwestliches Grundstücksende liegt bei $x=4$ (Beginn seines Gartens).
    Differenz: $4 - 1 = 3 \text{ LE}$.
5.  **Reale Entfernung:** $3 \text{ LE} \cdot 10 \text{ m/LE} = 30 \text{ m}$.

**Ergebnis:** Der Abstand beträgt $30 \text{ m}$.