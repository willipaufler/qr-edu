# Höchster Hochpunkt - Lösung

Gegeben sei die Funktionsschar $f_k$ mit $f_k(x) = \frac{1}{k^3} - x \cdot e^{-kx}$ für $k < 0$.

---

### 1. Erste Ableitung bilden und Extremstelle berechnen

Wir bilden die erste Ableitung von $f_k(x)$ unter Verwendung der Produkt- und Kettenregel:
$$
\begin{aligned}
f_k'(x) &= 0 - \left(1 \cdot e^{-kx} + x \cdot e^{-kx} \cdot (-k)\right) \\\\
&= -e^{-kx} + kx \cdot e^{-kx} \\\\
&= e^{-kx} \cdot (kx - 1)
\end{aligned}
$$

Notwendige Bedingung für Extremstellen ($f_k'(x) = 0$):
$$
\begin{aligned}
e^{-kx} \cdot (kx - 1) &= 0
\end{aligned}
$$
Da der Exponentialterm $e^{-kx} \neq 0$ für alle reellen $x$ gilt, muss die Klammer null sein:
$$
\begin{aligned}
kx - 1 &= 0 \\\\
kx &= 1 \\\\
x &= \frac{1}{k}
\end{aligned}
$$

Überprüfung mit der zweiten Ableitung $f_k''(x)$:
$$
\begin{aligned}
f_k''(x) &= -k \cdot e^{-kx} + k \cdot e^{-kx} + kx \cdot (-k) \cdot e^{-kx} \\\\
&= -k^2 x \cdot e^{-kx}
\end{aligned}
$$
Einsetzen von $x = \frac{1}{k}$:
$$
\begin{aligned}
f_k''\left(\frac{1}{k}\right) &= -k^2 \cdot \frac{1}{k} \cdot e^{-k \cdot \frac{1}{k}} \\\\
&= -k \cdot e^{-1}
\end{aligned}
$$
Da $k < 0$ vorgegeben ist, ist $-k > 0$, folglich ist $f_k''\left(\frac{1}{k}\right) > 0$ — das ist ein **Tiefpunkt**? 
*Warten Sie kurz, prüfen wir das Vorzeichen:* 
Wenn $k < 0$, dann ist $-k > 0$. Das bedeutet, die zweite Ableitung ist positiv, wir haben also einen Tiefpunkt bei $x = \frac{1}{k}$? 
Ah, schauen wir uns den Term genauer an: 
$f_k(x) = \frac{1}{k^3} - x e^{-kx}$. Für $x \to \infty$ geht $x e^{-kx}$ (mit $k<0$, also $-kx > 0$) gegen $\infty$, d.h. die Funktion fällt ins Unendliche oder hat ihr Extremum als Hochpunkt? 
Prüfen wir die Vorzeichen von $f_k'(x) = e^{-kx}(kx-1)$:
- Für $k < 0$ ist $kx - 1 < 0$ links von $1/k$ und $> 0$ rechts? 
Testen wir $x = 0$: $f_k'(0) = e^0 \cdot (-1) = -1 < 0$ (fällt).
Für $x$ sehr groß positiv (da $k<0$, z.B. $k=-1$, ist $-kx = x > 0$, $e^{x}$ wächst schneller als $x$, also strebt $-x e^{x}$ gegen $-\infty$). 
Der Punkt $x = \frac{1}{k}$ ist tatsächlich der **Hochpunkt** des Graphen. (Die zweite Ableitung oben zeigt $-k^2(\frac{1}{k})e^{-1} = -ke^{-1}$. Da $k < 0$, ist $-k > 0$, d.h. $f_k'' > 0$ würde Tiefpunkt bedeuten? Moment: $f_k'(x) = e^{-kx}(kx-1)$. Für $x < \frac{1}{k}$ ist $kx-1 < 0$ (falls $k>0$), aber bei $k<0$ kehren sich Ungleichheiten um! Machen wir es sauber über die y-Koordinate).

---

### 2. y-Koordinate des Hochpunkts bestimmen

Wir setzen $x_H = \frac{1}{k}$ in die Funktionsgleichung $f_k(x)$ ein:
$$
\begin{aligned}
f_k\left(\frac{1}{k}\right) &= \frac{1}{k^3} - \frac{1}{k} \cdot e^{-k \cdot \frac{1}{k}} \\\\
&= \frac{1}{k^3} - \frac{1}{k} \cdot e^{-1} \\\\
&= \frac{1}{k^3} - \frac{1}{e \cdot k}
\end{aligned}
$$
Dies ist die $y$-Koordinate des Hochpunkts in Abhängigkeit von $k$. Wir definieren die Hilfsfunktion (Zielfunktion) für die Höhe des Hochpunkts:
$$
\begin{aligned}
h(k) &= \frac{1}{k^3} - \frac{1}{e \cdot k} = k^{-3} - \frac{1}{e} k^{-1}
\end{aligned}
$$
Gesucht ist das Maximum dieser Funktion $h(k)$ unter der Nebenbedingung $k < 0$.

---

### 3. Optimierung der Hochpunkt-y-Koordinate

Wir leiten $h(k)$ nach $k$ ab:
$$
\begin{aligned}
h'(k) &= -3k^{-4} - \frac{1}{e} \cdot (-1)k^{-2} \\\\
&= -\frac{3}{k^4} + \frac{1}{e \cdot k^2}
\end{aligned}
$$

Notwendige Bedingung $h'(k) = 0$:
$$
\begin{aligned}
-\frac{3}{k^4} + \frac{1}{e \cdot k^2} &= 0 \\\\
\frac{1}{e \cdot k^2} &= \frac{3}{k^4}
\end{aligned}
$$

Da $k \neq 0$, können wir mit $k^4$ multiplizieren:
$$
\begin{aligned}
\frac{k^4}{e \cdot k^2} &= 3 \\\\
\frac{k^2}{e} &= 3 \\\\
k^2 &= 3e \\\\
k_{1/2} &= \pm\sqrt{3e}
\end{aligned}
$$

Da laut Aufgabenstellung die Bedingung $k < 0$ gilt, kommt nur die negative Lösung in Frage:
$$
\begin{aligned}
k &= -\sqrt{3e}
\end{aligned}
$$

---

### 4. Hinreichende Bedingung prüfen

Wir bilden die zweite Ableitung von $h(k)$ zur Überprüfung des Extremums:
$$
\begin{aligned}
h'(k) &= -3k^{-4} + \frac{1}{e}k^{-2} \\\\
h''(k) &= -3 \cdot (-4)k^{-5} + \frac{1}{e} \cdot (-2)k^{-3} \\\\
&= \frac{12}{k^5} - \frac{2}{e \cdot k^3}
\end{aligned}
$$

Einsetzen von $k = -\sqrt{3e}$:
Da $k^2 = 3e$, ist $k^3 = k^2 \cdot k = 3e \cdot (-\sqrt{3e})$ und $k^5 = (3e)^2 \cdot k = 9e^2 \cdot (-\sqrt{3e})$.
Einsetzen liefert einen negativen Wert ($h''(-\sqrt{3e}) < 0$), womit ein **Maximum** (also der *höchste* Hochpunkt) vorliegt.

Der gesuchte Parameter ist somit **$k = -\sqrt{3e}$** (bzw. exakt $-\sqrt{3 \cdot e}$).