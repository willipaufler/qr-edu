# Anstieg an einer Stelle - Lösung

### a) Bestimmen von $f(-2)$ und Aufstellen des Differenzenquotienten
Gegeben ist $f(x) = 4x^2 - 4x$ und $x_0 = -2$.

Zuerst bestimmen wir den Funktionswert an der Stelle $-2$:
$$ 
\begin{aligned} f(-2) &= 4 \cdot (-2)^2 - 4 \cdot (-2) \\\\ &= 4 \cdot 4 + 8 \\\\ &= 24 \end{aligned} 
$$

Nun stellen wir den Differenzenquotienten auf:
$$ 
\begin{aligned} \frac{f(-2+h) - f(-2)}{h} &= \frac{4(-2+h)^2 - 4(-2+h) - 24}{h} \end{aligned} 
$$

### b) Bestimmen des Anstiegs mit dem Grenzwert

#### Alternative 1: h-Methode
Wir vereinfachen den Zähler des Ausdrucks aus Teilaufgabe a) unter Anwendung der binomischen Formel:
$$ 
\begin{aligned} \frac{4(4 - 4h + h^2) + 8 - 4h - 24}{h} &= \frac{16 - 16h + 4h^2 + 8 - 4h - 24}{h} \\\\ &= \frac{4h^2 - 20h}{h} \end{aligned} 
$$

Nun berechnen wir den Grenzwert $f'(-2)$:
$$ 
\begin{aligned} f'(-2) &= \lim_{h \to 0} \frac{4h^2 - 20h}{h} \\\\ &= \lim_{h \to 0} \frac{h \cdot (4h - 20)}{h} \\\\ &= \lim_{h \to 0} (4h - 20) \\\\ &= -20 \end{aligned} 
$$

#### Alternative 2: $x \to x_0$-Methode
Hierbei nutzen wir den Grenzwert für $x \to -2$:
$$ 
\begin{aligned} f'(-2) &= \lim_{x \to -2} \frac{f(x) - f(-2)}{x - (-2)} \\\\ &= \lim_{x \to -2} \frac{4x^2 - 4x - 24}{x + 2} \end{aligned} 
$$

Wir klammern im Zähler die $4$ aus und faktorisieren den quadratischen Ausdruck (z. B. durch Polynomdivision oder Vieta):
$$ 
\begin{aligned} f'(-2) &= \lim_{x \to -2} \frac{4(x^2 - x - 6)}{x + 2} \\\\ &= \lim_{x \to -2} \frac{4(x - 3)(x + 2)}{x + 2} \\\\ &= \lim_{x \to -2} 4(x - 3) \\\\ &= 4(-2 - 3) \\\\ &= -20 \end{aligned} 
$$

Der Anstieg der Funktion $f$ an der Stelle $x_0 = -2$ beträgt somit in beiden Fällen $-20$.