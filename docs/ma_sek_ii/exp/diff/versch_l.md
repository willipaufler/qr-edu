# Verschobene Welt (ohne CAS) - Lösung

Gegeben sind die Funktion $f(x) = e^{2x}$ und ihre Ableitung $f'(x) = 2e^{2x}$[cite: 7].

---

### Teilaufgabe a)

* **Zuordnung:** 
  - Der flachere Graph, der durch den Punkt $(0 \mid 1)$ verläuft, gehört zu $f(x) = e^{2x}$ (da $f(0) = e^0 = 1$).
  - Der steilere Graph, der durch den Punkt $(0 \mid 2)$ verläuft, gehört zur Ableitung $f'(x) = 2e^{2x}$ (da $f'(0) = 2e^0 = 2$).
* **Begründung:** Der $y$-Achsenabschnitt von $f$ ist $1$, während der von $f'$ bei $2$ liegt. Zudem wächst $f'$ wegen des Faktors $2$ an jeder Stelle doppelt so schnell.

---

### Teilaufgabe b)

Wir schreiben den konstanten Faktor $2$ als e-Funktion um, indem wir $2 = e^{\ln(2)}$ nutzen:
$$
\begin{aligned}
f'(x) &= 2 \cdot e^{2x} \\\\
&= e^{\ln(2)} \cdot e^{2x} \\\\
&= e^{2x + \ln(2)}
\end{aligned}
$$

Nun klammern wir im Exponenten den Faktor $2$ aus:
$$
\begin{aligned}
f'(x) &= e^{2 \cdot \left(x + \frac{\ln(2)}{2}\right)} = f\left(x + \frac{\ln(2)}{2}\right)
\end{aligned}
$$

Da das Ersetzen von $x$ durch $x + c$ einer Verschiebung des Graphen nach **links** um $\frac{\ln(2)}{2}$ entspricht, ist der Graph von $f'$ exakt der um $\frac{\ln(2)}{2}$ nach links verschobene Graph von $f$.

---

### Teilaufgabe c)

Schauen wir uns die ersten Ableitungen an:
- $f'(x) = 2 \cdot e^{2x}$ (Faktor $2^1$)
- $f''(x) = 2 \cdot 2 \cdot e^{2x} = 2^2 \cdot e^{2x}$ (Faktor $2^2$)
- $\vdots$
- $f^{(10)}(x) = 2^{10} \cdot e^{2x}$

Wir schreiben den Faktor $2^{10}$ mithilfe des gleichen Tricks als e-Funktion um:
$$
\begin{aligned}
2^{10} &= e^{\ln(2^{10})} = e^{10 \cdot \ln(2)}
\end{aligned}
$$

Einsetzen in die zehnte Ableitung:
$$
\begin{aligned}
f^{(10)}(x) &= e^{10 \cdot \ln(2)} \cdot e^{2x} \\\\
&= e^{2x + 10\ln(2)} \\\\
&= e^{2(x + 5\ln(2))} \\\\
&= f(x + 5\ln(2))
\end{aligned}
$$

Die zehnte Ableitung $f^{(10)}$ ist demnach im Vergleich zu $f$ um $5\ln(2)$ Einheiten in negative $x$-Richtung (nach links) verschoben (ca. $3{,}47$ Einheiten).