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

### 4. Endergebnis
Der gesuchte Parameter ist **$a = 0,5$**.
Die maximale Fläche beträgt:
$$
A(0,5) = 1,5 \cdot 0,5 - 2 \cdot (0,5)^3 = 0,75 - 0,25 = \mathbf{0,5}
$$
