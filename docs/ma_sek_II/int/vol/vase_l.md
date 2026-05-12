# Designervase - Lösung

![Designervase](../../../assets/images/designervase_light.png#only-light){width="60%"}
![Designervase](../../../assets/images/designervase_dark.png#only-dark){width="60%"}
/// caption
Graph der Desigernvase und schematische Darstellung der Vase in der Box.
///

### Lösung zu a)
**Bedingungen für das Gleichungssystem:**

1. $f(0) = 2$
2. $f(6) = 5$
3. $f'(6) = 0$
4. $f(20) = 3$

**Ergebnis der Modellierung (via CAS):**
$$
\begin{aligned}
f(x) = \frac{43}{11760}x^3 - \frac{187}{1470}x^2 + \frac{1109}{980}x + 5 \\\\
f(x) \approx 0,00366x^3 - 0,12721x^2 + 1,13163x + 2
\end{aligned}
$$

---

### Lösung zu b)
**1. Maße der Box:**
Der maximale Radius der Vase ist $r_{max} = 8 \, \text{cm}$. Mit $1 \, \text{cm}$ Schaumstoffschicht an jeder Seite ergibt sich für die Breite und Tiefe:
$$
\begin{aligned}
b = 2 \cdot (5 \, \text{cm} + 1 \, \text{cm}) = 12 \, \text{cm}
\end{aligned}
$$
Für die Höhe der Box addieren wir zur Vasenhöhe ($20 \, \text{cm}$) jeweils $1 \, \text{cm}$ für Boden und Deckel:
$$
\begin{aligned}
h_{Box} = 20 + 1 + 1 = 22 \, \text{cm}
\end{aligned}
$$
$$
\begin{aligned}
V_{Box} = 12 \cdot 12 \cdot 22 = \mathbf{3168 \, \text{cm}^3}
\end{aligned}
$$

**2. Volumen des Schaumstoffs:**
Das Außenvolumen der Vase $V_a$ beträgt laut CAS:
$$
\begin{aligned}
V_a = \pi \cdot \int_{0}^{20} (f(x))^2 \, dx \approx 901,0 \, \text{cm}^3
\end{aligned}
$$
Daraus ergibt sich das Schaumstoffvolumen:
$$
\begin{aligned}
V_{Schaum} = 3168,00 \, \text{cm}^3 - 901,0 \, \text{cm}^3 = \mathbf{2267,0 \, \text{cm}^3}
\end{aligned}
$$

---

### Lösung zu c)
**1. Glasvolumen:**
Das Glasvolumen ergibt sich aus der Differenz von Außenvolumen und Innenvolumen ($V_i$ auf dem Intervall $[0,5; 20]$):
$$
\begin{aligned}
V_{Glas} = \pi \cdot \int_{0}^{20} (f(x))^2 \, dx - \pi \cdot \int_{0,5}^{20} (f(x)-0,5)^2 \, dx
\end{aligned}
$$
Laut CAS-Berechnung beträgt dieses Differenzvolumen:
$$
\begin{aligned}
V_{Glas} \approx 219,7 \, \text{cm}^3
\end{aligned}
$$

**2. Gewicht der Vase:**
Multiplikation mit der Dichte $\rho = 2,5 \, \text{g/cm}^3$:
$$
\begin{aligned}
m = 219,7 \cdot 2,5 = 549,3 \, \text{g}
\end{aligned}
$$
Die leere Vase wiegt somit ca. **$550 \, \text{kg}$**.

---

??? tip "Hinweis zur Rechengenauigkeit"
    Verwenden Sie im CAS immer die exakten Brüche oder die im System gespeicherten Variablen. Bereits kleinste Rundungen bei den Koeffizienten können zu Abweichungen führen.