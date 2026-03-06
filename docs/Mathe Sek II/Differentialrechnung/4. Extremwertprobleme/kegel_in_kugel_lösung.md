# Kegel in Kugel - Lösung

### Aufgabe a) Extremwertbestimmung ($R = 9$)

![Kegel in Kugel](../../../assets/images/kegel_in_kugel_light.png#only-light){width="60%"}
![Kegel in Kugel](../../../assets/images/kegel_in_kugel_dark.png#only-dark){width="60%"}
/// caption
Achsenschnitt der Kugel mit Kegel.
///

#### 1. Zielfunktion

Nebenbedingung (Pythagoras): $r^2 = 9^2 - (h - 9)^2 = 18h - h^2$.
Einsetzen in $V = \frac{1}{3}\pi r^2 h$:
$$
V(h) = \frac{\pi}{3}(18h^2 - h^3)
$$

#### 2. Optimierung
$$
V'(h) = \frac{\pi}{3}(36h - 3h^2) = \pi(12h - h^2)
$$
Setze $V'(h) = 0$:
$$
\pi h(12 - h) = 0 \implies h = 12\,\rm (da\ h > 0)
$$
Prüfung: $V''(h) = \pi(12 - 2h) \Rightarrow V''(12) = -12\pi < 0$ (Maximum).

#### 3. Ergebnisse

* **Höhe:** $h = 12$
* **Radius:** $r = \sqrt{18(12) - 12^2} = \sqrt{72} = 6\sqrt{2} \approx 8,49$
* **Max. Volumen:** $V(12) = \frac{\pi}{3}(18 \cdot 12^2 - 12^3) = 288\pi \approx 904,78$

---

### Aufgabe b) *Zusatz:* Allgemeine Untersuchung

#### Allgemeines Maximum

Zielfunktion mit Parameter $R$:
$$
r^2 = R^2 - (h - R)^2 = 2hR - h^2$$
$$
V(h) = \frac{\pi}{3}(2Rh^2 - h^3)
$$
Ableiten nach $h$:
$$
V'(h) = \frac{\pi}{3}(4Rh - 3h^2)
$$
Nullstelle von $V'(h)$:
$$
h(4R - 3h) = 0 \implies \mathbf{h = \frac{4}{3}R}
$$

#### Volumenverhältnis
Berechnung von $r^2$ an der Stelle $h = \frac{4}{3}R$:
$$
r^2 = 2(\frac{4}{3}R)R - (\frac{4}{3}R)^2 = \frac{8}{3}R^2 - \frac{16}{9}R^2 = \frac{8}{9}R^2
$$
Maximales Kegelvolumen:
$$
V_{\text{max}} = \frac{1}{3}\pi \cdot \frac{8}{9}R^2 \cdot \frac{4}{3}R = \frac{32}{81}\pi R^3
$$
Verhältnis zum Kugelvolumen ($V_{\text{Kugel}} = \frac{4}{3}\pi R^3$):
$$
\frac{V_{\text{Kegel}}}{V_{\text{Kugel}}} = \frac{\frac{32}{81}\pi R^3}{\frac{4}{3}\pi R^3} = \frac{32}{81} \cdot \frac{3}{4} = \mathbf{\frac{8}{27} \approx 29,6\,\%}
$$
