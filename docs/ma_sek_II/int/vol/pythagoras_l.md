# Pythagoras-Prickler - Lösung

### Lösung zu a)
**Gegeben:** $V = 270\text{ cm}^3$, $d = 11,4\text{ cm} \implies r = 5,7\text{ cm}$, $H_{ges} = 18\text{ cm}$.

**Berechnung der Kegelhöhe $h_k$:**
$$
\begin{aligned}
270 &= \frac{1}{3} \cdot \pi \cdot 5,7^2 \cdot h_k \\\\
h_k &= \frac{810}{\pi \cdot 32,49} \\\\
h_k &\approx 7,94\text{ cm}
\end{aligned}
$$

**Berechnung der Stiellänge $L$:**
$$
\begin{aligned}
L &= 18\text{ cm} - 7,94\text{ cm} \\\\
L &= 10,06\text{ cm} \approx \mathbf{10\text{ cm}}
\end{aligned}
$$

---

### Lösung zu b)
Gegeben: $\Delta V = 50\text{ cm}^3$ und $\Delta h = 1\text{ cm}$.

#### Option 1: Integralrechnung
Die Steigung der Randfunktion $f(x) = m \cdot x$ beträgt $m = \frac{5,7}{7,94} \approx 0,7179$.
$$
50 = \pi \cdot \int_{h}^{h+1} (0,7179 \cdot x)^2 \, dx
$$
Aulösen mit dem CAS liefert:
$$
h \approx 5,05\text{ cm}
$$

Altes Volumen: $V_{alt} = 0,5397 \cdot 5,05^3 \approx \mathbf{69,5\text{ ml}}$.  
  
  
#### Option 2: Ähnlichkeit (Strahlensatz)
Wir nutzen den Volumenfaktor $c = \frac{270}{7,94^3} \approx 0,539$.
$$
\begin{aligned}
V(h) &= 0,539 \cdot h^3 \\\\
0,539 \cdot (h_1 + 1)^3 - 0,539 \cdot h_1^3 &= 50 \\\\
(h_1 + 1)^3 - h_1^3 &= \frac{50}{0,539} \approx 92,76
\end{aligned}
$$
Die Lösung der quadratischen Gleichung $3h_1^2 + 3h_1 - 91,76 = 0$ ergibt $h_1 \approx 5,05\text{ cm}$.
Eingesetzt in $V(h_1)$:
$$
\begin{aligned}
V_{alt} &= 0,539 \cdot 5,05^3 \approx \mathbf{69,4\text{ ml}}
\end{aligned}
$$
Zuvor befanden sich ca. **$69\text{ ml}$** Flüssigkeit im Glas.


---

??? abstract "🍸 Das offizielle Rezept: Pythagoras-Prickler"
    **Ein Drink nach dem Gesetz der Geometrie!**

    Um den perfekten mathematischen Rauschzustand zu erreichen, müssen die Zutaten im exakten quadratischen Verhältnis zueinander stehen. Nur so ergibt die Mischung eine perfekte Hypotenuse im Glas!

    **Zutaten:**

    * **3 cl** naturtrüber Apfelsaft (die erste Kathete $a$)
    * **4 cl** Bitter-Lemon (die zweite Kathete $b$)
    * **5 cl** eiskaltes Club-Soda (die erfrischende Hypotenuse $c$)

    **Zubereitung:**

    1. Gießen Sie zuerst den Apfelsaft und das Bitter-Lemon in das kegelförmige Glas.
    2. Rühren Sie kurz um, damit sich die Katheten vereinen.
    3. Krönen Sie das Ganze mit dem Club-Soda.

    **Mathematischer Serviervorschlag:**
    Genießen Sie den Drink in vollen Zügen, denn wie schon die alten Griechen wussten:
    $$
    \begin{aligned}
    a^2 + b^2 &= c^2 \\\\
    3^2 + 4^2 &= 5^2 \\\\
    9 + 16 &= 25
    \end{aligned}
    $$
    *Prost! Aber Vorsicht: Wer zu viel mischt, teilt womöglich durch Null.*