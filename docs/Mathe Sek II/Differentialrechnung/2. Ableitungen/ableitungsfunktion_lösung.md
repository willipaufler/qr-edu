# Ableitungsfunktion - Lösung

### a) Aufstellen des Differenzenquotienten
Gegeben ist $f(x) = -2x^2 + x$.

Der Differenzenquotient an der Stelle $x_0$ lautet:
$$ 
\begin{aligned} \frac{f(x_0 + h) - f(x_0)}{h} &= \frac{-2(x_0 + h)^2 + (x_0 + h) - (-2x_0^2 + x_0)}{h} \end{aligned} 
$$

### b) Berechnung der Ableitungsfunktion mit dem Grenzwert

#### Alternative 1: h-Methode
Zuerst vereinfachen wir den Zähler (Anwendung der ersten binomischen Formel und Auflösen der Klammern):
$$ 
\begin{aligned} \frac{-2(x_0^2 + 2x_0h + h^2) + x_0 + h + 2x_0^2 - x_0}{h} &= \frac{-2x_0^2 - 4x_0h - 2h^2 + x_0 + h + 2x_0^2 - x_0}{h} \\\\ &= \frac{-4x_0h - 2h^2 + h}{h} \end{aligned} 
$$

Nun bilden wir den Grenzwert für $h \to 0$:
$$ 
\begin{aligned} f'(x_0) &= \lim_{h \to 0} \frac{h \cdot (-4x_0 - 2h + 1)}{h} \\\\ &= \lim_{h \to 0} (-4x_0 - 2h + 1) \\\\ &= -4x_0 + 1 \end{aligned} 
$$

#### Alternative 2: $x \to x_0$-Methode
Hierbei betrachten wir den Grenzwert, während $x$ gegen die feste Stelle $x_0$ läuft:
$$ 
\begin{aligned} f'(x_0) &= \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0} \\\\ &= \lim_{x \to x_0} \frac{(-2x^2 + x) - (-2x_0^2 + x_0)}{x - x_0} \\\\ &= \lim_{x \to x_0} \frac{-2x^2 + x + 2x_0^2 - x_0}{x - x_0} \end{aligned} 
$$

Wir sortieren den Zähler um, um den Faktor $(x - x_0)$ durch Ausklammern oder Anwendung des 3. Binoms sichtbar zu machen:
$$ 
\begin{aligned} f'(x_0) &= \lim_{x \to x_0} \frac{-2(x^2 - x_0^2) + (x - x_0)}{x - x_0} \\\\ &= \lim_{x \to x_0} \frac{-2(x - x_0)(x + x_0) + 1(x - x_0)}{x - x_0} \\\\ &= \lim_{x \to x_0} \frac{(x - x_0) \cdot [-2(x + x_0) + 1]}{x - x_0} \\\\ &= \lim_{x \to x_0} (-2x - 2x_0 + 1) \\\\ &= -2x_0 - 2x_0 + 1 \\\\ &= -4x_0 + 1 \end{aligned} 
$$

Die Ableitungsfunktion lautet somit $f'(x_0) = -4x_0 + 1$  
oder als "typische Funktion" $f'(x) = -4x + 1$