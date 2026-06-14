# Pyramidenvolumen mit Parameter - Tipp

### Zu Teilaufgabe a)
* Ein Viereck ist ein Parallelogramm, wenn gegenüberliegende Seiten parallel und gleich lang sind. Prüfe, ob die Vektoren $\vec{AB}$ und $\vec{DC}$ identisch sind.

### Zu Teilaufgabe b)
* **Formel nutzen:** Das Volumen einer Pyramide mit einer parallelogrammförmigen Grundfläche berechnet sich über:
  $$
  V = \frac{1}{3} \cdot |(\vec{AB} \times \vec{AD}) \cdot \vec{AS_t}|
  $$
* Stelle zuerst den Vektor $\vec{AS_t}$ auf, in dessen $x$-Koordinate der Parameter $t$ steht. Berechne dann das Kreuzprodukt der Grundenseiten und anschließend das Skalarprodukt mit $\vec{AS_t}$. Vergiss am Ende nicht, den Betrag zu ziehen und mit $\frac{1}{3}$ zu multiplizieren.

### Zu Teilaufgabe c)
* Setze deine Volumenformel gleich $5$: $|t + 1| = 5$.
* **Achtung, Betrag:** Löse die Gleichung für zwei Fälle auf ($t + 1 = 5$ und $t + 1 = -5$). Es gibt zwei mathematisch korrekte Lösungen!

### Zu Teilaufgabe d)
* Wenn das Volumen null wird, hat die Pyramide keine „Höhe“ mehr. Überlege, was das für die Position der Spitze $S_t$ relativ zur Ebene $ABCD$ bedeutet und welcher Fachbegriff für Vektoren gesucht ist, die in einer gemeinsamen Ebene liegen.

### Zu Teilaufgabe e)
* **Definition:** Eine Pyramide ist genau dann *gerade*, wenn ihre Spitze $S_t$ senkrecht über dem geometrischen Mittelpunkt $M$ der Grundfläche liegt.
* **Vorgehen:** 1. Berechne den Mittelpunkt $M$ des Parallelogramms über die Formel $\vec{OM} = \frac{1}{2}(\vec{OA} + \vec{OC})$.
  2. Bestimme den Verbindungsvektor $\vec{MS_t}$ von der Mitte zur Spitze.
  3. Prüfe, ob dieser Vektor parallel (kollinear) zum Normalenvektor der Grundfläche sein kann. Setze dazu $\vec{MS_t} = k \cdot \vec{n}_0$ mit $\vec{n}_0 = \begin{pmatrix} -1 \\\\ 2 \\\\ -2 \end{pmatrix}$ an und untersuche das entstehende Gleichungssystem auf Widersprüche.