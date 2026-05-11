# Ableitungsregeln II - Lösung

### a) Bestimmen von $f'(x)$ (Kettenregel)
Umschreiben: $f(x) = (x^2 + 1)^{\frac{1}{2}}$
$$ 
\begin{aligned} f'(x) &= \frac{1}{2}(x^2 + 1)^{-\frac{1}{2}} \cdot 2x \\\\ &= \frac{x}{\sqrt{x^2 + 1}} \end{aligned} 
$$

### b) Bestimmen von $g'(x)$ (Kettenregel)
$$ 
\begin{aligned} g'(x) &= 10(2x + 1)^9 \cdot 2 \\\\ &= 20(2x + 1)^9 \end{aligned} 
$$

### c) Bestimmen von $f_3'(x)$ (Quotientenregel)
$u = x^2 + 1, u' = 2x$ und $v = x - 2, v' = 1$
$$ 
\begin{aligned} f_3'(x) &= \frac{2x(x - 2) - (x^2 + 1) \cdot 1}{(x - 2)^2} \\\\ &= \frac{2x^2 - 4x - x^2 - 1}{(x - 2)^2} \\\\ &= \frac{x^2 - 4x - 1}{(x - 2)^2} \end{aligned} 
$$

### d) Bestimmen von $f_4'(x)$ (Kettenregel mit Parameter)
$$ 
\begin{aligned} f_4'(x) &= 3(ax - a)^2 \cdot a \\\\ &= 3a(ax - a)^2 \end{aligned} 
$$

### e) Bestimmen von $f_5'(x)$

#### Alternative 1: Produktregel
$u = x + 2, u' = 1$ und $v = x^{\frac{1}{2}}, v' = \frac{1}{2\sqrt{x}}$
$$ 
\begin{aligned} f_5'(x) &= 1 \cdot \sqrt{x} + (x + 2) \cdot \frac{1}{2\sqrt{x}} \\\\ &= \sqrt{x} + \frac{x + 2}{2\sqrt{x}} \end{aligned} 
$$

#### Alternative 2: Ausmultiplizieren
Zuerst vereinfachen:
$$ 
\begin{aligned} f_5(x) &= (x + 2) \cdot x^{\frac{1}{2}} \\\\ &= x^{\frac{3}{2}} + 2x^{\frac{1}{2}} \end{aligned} 
$$
Nun ableiten:
$$ 
\begin{aligned} f_5'(x) &= \frac{3}{2}x^{\frac{1}{2}} + 2 \cdot \frac{1}{2}x^{-\frac{1}{2}} \\\\ &= \frac{3}{2}\sqrt{x} + \frac{1}{\sqrt{x}} \end{aligned} 
$$

### f) Bestimmen von $f_6'(x)$
Hier berechnen wir zunächst die Ableitung mit der Produktregel (siehe oben) und fassen das Ergebnis durch Ausmultiplizieren zusammen:
$$ 
\begin{aligned} f_6'(x) &= \frac{1}{2\sqrt{x}}(2x + 1)^2 + \sqrt{x} \cdot 4(2x + 1) \\\\ &= \frac{(4x^2 + 4x + 1)}{2\sqrt{x}} + 4\sqrt{x}(2x + 1) \\\\ &= \frac{4x^2 + 4x + 1}{2\sqrt{x}} + \frac{8x(2x + 1)}{2\sqrt{x}} \\\\ &= \frac{4x^2 + 4x + 1 + 16x^2 + 8x}{2\sqrt{x}} \\\\ &= \frac{20x^2 + 12x + 1}{2\sqrt{x}} \end{aligned} 
$$

#### Alternative: Erst Ausmultiplizieren, dann Ableiten
Zuerst die binomische Formel auflösen:
$$ 
\begin{aligned} f_6(x) &= \sqrt{x} \cdot (4x^2 + 4x + 1) \\\\ &= 4x^{2,5} + 4x^{1,5} + x^{0,5} \end{aligned} 
$$
Ableiten:
$$ 
\begin{aligned} f_6'(x) &= 10x^{1,5} + 6x^{0,5} + 0,5x^{-0,5} \\\\ &= 10\sqrt{x^3} + 6\sqrt{x} + \frac{1}{2\sqrt{x}} \end{aligned} 
$$
(Hinweis: Beide Formen sind mathematisch identisch, die Bruchdarstellung ist oft für weitere Berechnungen praktischer.)