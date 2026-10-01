# Tipp – Lagebeziehung Ebene-Ebene

## Allgemeine Vorgehensweise
1. **Normalenvektoren bestimmen:** Berechne für beide Ebenen jeweils den Normalenvektor via Kreuzprodukt der Spannvektoren:
   $$
   \begin{aligned}
   \vec{n}_1 = \vec{AB} \times \vec{AC}, \quad \vec{n}_2 = \vec{DE} \times \vec{DF}
   \end{aligned}
   $$
2. **Kollinearität prüfen:**
   * Sind $\vec{n}_1$ und $\vec{n}_2$ **nicht kollinear** (keine Vielfachen voneinander), **schneiden** sich die Ebenen.
   * Sind $\vec{n}_1$ und $\vec{n}_2$ **kollinear**, sind die Ebenen **parallel** (echt parallel oder identisch).

---

## Für Teil a)
* Wandle beide Ebenen in Koordinatenform um.
* **Schnittwinkel:** Nutze die Formel:
  $$
  \begin{aligned}
  \cos(\alpha) = \frac{|\vec{n}_1 \cdot \vec{n}_2|}{|\vec{n}_1| \cdot |\vec{n}_2|}
  \end{aligned}
  $$
* **Schnittgerade:** Löse das aus den zwei Koordinatengleichungen bestehende Gleichungssystem, indem du eine Variable als Parameter (z. B. $x_1 = t$) wählst.

---

## Für Teil b)
* Wenn die Normalenvektoren kollinear sind, mache eine **Punktprobe**: Setze einen Punkt der Ebene $E_{DEF}$ (z. B. $D$) in die Koordinatengleichung von $E_{ABC}$ ein.
* Erfüllt der Punkt die Gleichung, sind die Ebenen **identisch**.
* Erfüllt er sie nicht, sind sie **echt parallel**. Berechne den Abstand mit der Hesseschen Normalenform:
  $$
  \begin{aligned}
  d(E_1, E_2) = \frac{|n_1 d_1 + n_2 d_2 + n_3 d_3 - c|}{\sqrt{n_1^2 + n_2^2 + n_3^2}}
  \end{aligned}
  $$