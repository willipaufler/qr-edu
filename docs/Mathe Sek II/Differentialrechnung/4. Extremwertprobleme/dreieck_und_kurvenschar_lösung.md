# Dreieck und Kurvenschar - Lösung

### 1. Bestimmung der Eckpunkte
Zuerst berechnen wir die Nullstellen, um die Grundseite $g$ zu bestimmen:
$$
f_a(x) = x \cdot \left( \frac{3-4a^2}{16a^2}x - \frac{3-4a^2}{4a} \right) = 0
$$

* $x_1 = 0$
* $x_2 = 4a$ (durch Nullsetzen der Klammer)
* **Grundseite:** $g = 4a - 0 = 4a$

Der Scheitelpunkt liegt bei $x_s = \frac{0 + 4a}{2} = 2a$. Der y-Wert (Höhe $h$) ist:
$$
h = |f_a(2a)| = \left| \frac{3-4a^2}{16a^2} \cdot (2a)^2 - \frac{3-4a^2}{4a} \cdot 2a \right|
$$
$$
h = \left| \frac{3-4a^2}{4} - \frac{3-4a^2}{2} \right| = \left| -\frac{3-4a^2}{4} \right| = \frac{|3-4a^2|}{4}
$$

### 2. Aufstellen der Flächenfunktion
$$
A(a) = \frac{1}{2} \cdot g \cdot h = \frac{1}{2} \cdot 4a \cdot \frac{|3-4a^2|}{4} = \frac{1}{2} |3a - 4a^3|
$$

Da für das Intervall $[\frac{1}{5}, \frac{4}{5}]$ der Ausdruck $3a - 4a^3$ positiv bleibt, betrachten wir:
$$
A(a) = 1,5a - 2a^3
$$

### 3. Optimierung
Ableitungen bilden:

* $A'(a) = 1,5 - 6a^2$
* $A''(a) = -12a$

Notwendige Bedingung $A'(a) = 0$:
$$
1,5 - 6a^2 = 0 \implies 6a^2 = 1,5 \implies a^2 = 0,25 \implies \mathbf{a = 0,5}
$$

Hinreichende Bedingung:
$A''(0,5) = -12 \cdot 0,5 = -6 < 0 \implies$ **Maximum**.


### 4. Randwertbetrachtung
Um sicherzustellen, dass das lokale Maximum bei $a = 0,5$ auch das globale Maximum im Intervall $[\frac{1}{5}, \frac{4}{5}]$ (entspricht $[0,2; 0,8]$) ist, prüfen wir die Funktionswerte an den Grenzen:

* **Linker Randwert ($a = 0,2$):**
$$
A(0,2) = 1,5 \cdot 0,2 - 2 \cdot (0,2)^3 = 0,3 - 0,016 = 0,284
$$

* **Lokales Maximum ($a = 0,5$):**
$$
A(0,5) = 0,5
$$

* **Rechter Randwert ($a = 0,8$):**
$$
A(0,8) = 1,5 \cdot 0,8 - 2 \cdot (0,8)^3 = 1,2 - 1,024 = 0,176
$$

Da $0,5 > 0,284$ und $0,5 > 0,176$, ist das globale Maximum im gegebenen Intervall tatsächlich bei $a = 0,5$.

### 5. Endergebnis
Der gesuchte Parameter ist **$a = 0,5$**.
Die maximale Fläche beträgt:
$$
A(0,5) = 1,5 \cdot 0,5 - 2 \cdot (0,5)^3 = 0,75 - 0,25 = 0,5
$$