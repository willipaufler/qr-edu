# Kugelstoßen - Lösung

### a) Modellierung der Flugkurve
Wir nutzen den Ansatz $f(x) = ax^2 + bx + c$ und die Ableitung $f'(x) = 2ax + b$.

**Mathematische Bedingungen:**
$$
\begin{aligned}
\text{I. } & f(0) = 1,5 &&\implies c = 1,5 \\\\
\text{II. } & f(19,5) = 0 &&\implies a(19,5)^2 + b(19,5) + 1,5 = 0 \\\\
\text{III. } & f'(19,5) = \tan(-30^\circ) &&\implies 2a(19,5) + b = -\tan(30^\circ)
\end{aligned}
$$

**Ergebnis der Parameter (auf 4 Dezimalstellen gerundet):**
Basierend auf der CAS-Berechnung ergeben sich folgende Werte:

* $a = -0,0257$
* $b = 0,4235$
* $c = 1,5000$

**Funktionsgleichung:**
$$
\begin{aligned}
f(x) = -0,0257x^2 + 0,4235x + 1,5
\end{aligned}
$$

---

### b) Maximale Flughöhe und Abstoßwinkel

**1. Maximale Flughöhe:**
Zuerst bestimmen wir die Stelle des Maximums ($f'(x) = 0$):
$$
\begin{aligned}
2 \cdot (-0,0257)x + 0,4235 &= 0 \\\\
-0,0514x &= -0,4235 \\\\
x &\approx 8,2393
\end{aligned}
$$

Die maximale Höhe berechnet sich durch Einsetzen der Stelle $x$ in die Funktion $f(x)$:
$$
\begin{aligned}
f(8,2393) &= -0,0257(8,2393)^2 + 0,4235(8,2393) + 1,5 \\\\
f(8,2393) &\approx 3,2446
\end{aligned}
$$
Die maximale Flughöhe der Kugel beträgt ca. **3,2446 m**.

**2. Abstoßwinkel:**
Der Abstoßwinkel $\alpha$ entspricht dem Steigungswinkel der Tangente am Startpunkt ($x = 0$):
$$
\begin{aligned}
f'(0) &= b = 0,4235 \\\\
\alpha &= \arctan(0,4235) \\\\
\alpha &\approx 22,9513^\circ
\end{aligned}
$$
Der Abstoßwinkel beträgt ca. **22,9513°**.