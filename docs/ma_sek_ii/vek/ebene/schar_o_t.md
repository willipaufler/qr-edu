# Tipp – Ebenenschar (oHiMi)

## Für Teil a) (Gerade steht senkrecht auf Ebene)
* Eine Gerade steht genau dann senkrecht auf einer Ebene, wenn ihr Richtungsvektor $\vec{v}_g$ parallel (kollinear) zum Normalenvektor $\vec{n}_a$ der Ebene verläuft:
  $$
  \begin{aligned}
  \vec{n}_a = k \cdot \vec{v}_g \quad (k \neq 0)
  \end{aligned}
  $$
* Lies den Normalenvektor $\vec{n}_a = \begin{pmatrix} 2a \\ 1 \\ -a \end{pmatrix}$ ab und stelle ein Gleichungssystem Zeile für Zeile auf, um $k$ und $a$ zu bestimmen.

---

## Für Teil b) (Gerade liegt vollständig in der Ebene)
Damit eine Gerade $g: \vec{x} = \vec{p} + s \cdot \vec{v}$ vollständig in einer Ebene $E_a$ liegt, müssen **zwei Bedingungen** gleichzeitig erfüllt sein:
1. **Punktprobe für den Stützpunkt:** Der Stützpunkt $P(2 \mid 1 \mid 2)$ muss in $E_a$ liegen. Setze ihn in die Ebenengleichung ein, um den Scharparameter $a$ zu berechnen.
2. **Orthogonalität des Richtungsvektors:** Der Richtungsvektor $\vec{v}$ muss senkrecht zum Normalenvektor $\vec{n}_a$ stehen. Das Skalarprodukt muss null ergeben:
   $$
   \begin{aligned}
   \vec{v} \cdot \vec{n}_a = 0
   \end{aligned}
   $$
   Nutze das bereits berechnete $a$, um daraus den Parameter $b$ zu bestimmen.