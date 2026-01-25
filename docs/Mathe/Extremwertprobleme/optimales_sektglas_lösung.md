# Das optimale Sektglas - Lösung

### 1. Nebenbedingung aufstellen
Aus dem Satz des Pythagoras im Querschnitt ergibt sich:
$$r^2 + (h - 9)^2 = 9^2$$
$$r^2 + h^2 - 18h + 81 = 81$$
$$r^2 = 18h - h^2$$

### 2. Zielfunktion erstellen
Einsetzen von $r^2$ in die Volumenformel des Kegels:
$$V(h) = \frac{1}{3} \pi \cdot (18h - h^2) \cdot h$$
$$V(h) = \frac{\pi}{3} (18h^2 - h^3)$$

### 3. Extremwert bestimmen
Ableitungen bilden:
$$V'(h) = \frac{\pi}{3} (36h - 3h^2) = \pi (12h - h^2)$$
$$V''(h) = \pi (12 - 2h)$$

Notwendige Bedingung $V'(h) = 0$:
$$h(12 - h) = 0$$
Da $h > 0$ sein muss, folgt **$h = 12\,\rm cm$**.

Hinreichende Bedingung prüfen:
$$V''(12) = \pi (12 - 24) = -12\pi < 0 \implies \text{Maximum}$$

Zugehöriger Radius $r$:
$$r^2 = 18(12) - 12^2 = 216 - 144 = 72 \implies r = \sqrt{72} \approx 8,49\,\rm cm$$

### 4. Volumenvergleich (Analyse)
Maximales Kegelvolumen:
$$V_{Kegel} = \frac{\pi}{3} \cdot 72 \cdot 12 = 288\pi \approx 904,78\,\rm cm^3$$

Kugelvolumen:
$$V_{Kugel} = \frac{4}{3} \pi \cdot 9^3 = 972\pi \approx 3053,63\,\rm cm^3$$

Prozentualer Anteil:
$$\frac{288\pi}{972\pi} = \frac{288}{972} = \frac{8}{27} \approx 29,6\,\%$$

**Ergebnis:** Der Kelch hat bei einer Höhe von **$12\,\rm cm$** und einem Radius von ca. **$8,49\,\rm cm$** sein maximales Volumen. Er füllt dabei knapp **$30\,\%$** der Dekokugel aus.
