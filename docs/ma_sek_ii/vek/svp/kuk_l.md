# Kurz und knapp - Lösung

### a) Interpretation des positiven Skalarprodukts

Aus einem Skalarprodukt größer als $0$ kann geschlussfolgert werden, dass die beiden Vektoren einen **spitzen Winkel** einschließen ($0^\circ \le \alpha < 90^\circ$).

**Begründung:** Die geometrische Formel für das Skalarprodukt lautet:
$$
\vec{a} \cdot \vec{b} = |\vec{a}| \cdot |\vec{b}| \cdot \cos(\alpha)
$$
Da die Beträge $|\vec{a}|$ und $|\vec{b}|$ für Nicht-Nullvektoren stets positiv sind, hängt das Vorzeichen des Skalarprodukts allein vom Kosinus des eingeschlossenen Winkels $\alpha$ ab. Da $\vec{a} \cdot \vec{b} > 0$ gilt, muss auch $\cos(\alpha) > 0$ sein. Im für Vektoren relevanten Intervall $[0^\circ; 180^\circ]$ ist der Kosinus genau dann positiv, wenn der Winkel kleiner als $90^\circ$ ist.

---

### b) Kreuzprodukt eines Vektors mit sich selbst

Das Kreuzprodukt eines Vektors mit sich selbst ergibt immer den **Nullvektor**:
$$
\vec{a} \times \vec{a} = \begin{pmatrix} 0 \\\\ 0 \\\\ 0 \end{pmatrix} = \vec{0}
$$

**Interpretation:**

Das Kreuzprodukt beschreibt den Flächeninhalt des Parallelogramms, das von zwei Vektoren aufgespannt wird. Ein Vektor und er selbst können kein Parallelogramm aufspannen (der Flächeninhalt ist $0$).

---

### c) Orthogonalität von Folgevektoren

**Nein**, daraus folgt im Allgemeinen nicht, dass $\vec{b} \cdot \vec{c} = 0$ ist.

**Begründung (Gegenbeispiel):** Wir wählen als Vektor $\vec{a}$ die gegebene $z$-Achse und für $\vec{b}$ und $\vec{c}$ zweimal den gleichen Vektor auf der $x$-Achse:
$$
\vec{a} = \begin{pmatrix} 0 \\\\ 0 \\\\ 1 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix}, \quad \vec{c} = \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix}
$$
Es gilt:
$$
\begin{aligned}
\vec{a} \cdot \vec{b} &= 0 \cdot 1 + 0 \cdot 0 + 1 \cdot 0 = 0 \quad (\vec{a} \perp \vec{b}) \\\\
\vec{a} \cdot \vec{c} &= 0 \cdot 1 + 0 \cdot 0 + 1 \cdot 0 = 0 \quad (\vec{a} \perp \vec{c})
\end{aligned}
$$
Berechnet man nun jedoch $\vec{b} \cdot \vec{c}$, erhält man:
$$
\vec{b} \cdot \vec{c} = \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix} \cdot \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix} = 1 \cdot 1 + 0 \cdot 0 + 0 \cdot 0 = 1 \neq 0
$$
Zwei Vektoren, die senkrecht auf einem dritten Vektor stehen, können im dreidimensionalen Raum parallel zueinander liegen oder jeden beliebigen anderen Winkel zueinander einnehmen.

---

### d) Lage des Punktes $P(0|5|0)$

* **Koordinatenachsen:** Der Punkt $P$ liegt exakt auf der **$y$-Achse** (bzw. $x_2$-Achse) im Abstand von 5 Einheiten vom Ursprung.
* **Koordinatenebenen:** Da die $x$- und die $z$-Koordinate gleich $0$ sind, liegt der Punkt gleichzeitig auf folgenden zwei Ebenen:
    * in der **$xy$-Ebene** ($x_1x_2$-Ebene)
    * in der **$yz$-Ebene** ($x_2x_3$-Ebene)


### e) Fehlende Assoziativität des Kreuzprodukts

**Nein**, das Assoziativgesetz gilt für das Kreuzprodukt im Allgemeinen nicht.

**Begründung (Gegenbeispiel):**
Wir wählen als Vektoren die Standard-Basisvektoren der Koordinatenachsen:
$$
\vec{a} = \vec{e}_1 = \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix}, \quad \vec{b} = \vec{e}_1 = \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix}, \quad \vec{c} = \vec{e}_2 = \begin{pmatrix} 0 \\\\ 1 \\\\ 0 \end{pmatrix}
$$

Nun berechnen wir beide Seiten der vermeintlichen Gleichung getrennt voneinander:

1. **Linke Seite: $(\vec{a} \times \vec{b}) \times \vec{c}$**
   Zuerst berechnen wir die Klammer $(\vec{e}_1 \times \vec{e}_1)$. Da das Kreuzprodukt eines Vektors mit sich selbst den Nullvektor ergibt (siehe Teilaufgabe b), gilt:
   $$
   \vec{e}_1 \times \vec{e}_1 = \begin{pmatrix} 0 \\\\ 0 \\\\ 0 \end{pmatrix} = \vec{0}
   $$
   Das Gesamtergebnis der linken Seite lautet somit:
   $$
   (\vec{e}_1 \times \vec{e}_1) \times \vec{e}_2 = \vec{0} \times \vec{e}_2 = \begin{pmatrix} 0 \\\\ 0 \\\\ 0 \end{pmatrix}
   $$

2. **Rechte Seite: $\vec{a} \times (\vec{b} \times \vec{c})$**
   Zuerst berechnen wir die Klammer $(\vec{e}_1 \times \vec{e}_2)$. Das Kreuzprodukt der ersten beiden Basisvektoren ergibt den dritten Basisvektor:
   $$
   \vec{e}_1 \times \vec{e}_2 = \vec{e}_3 = \begin{pmatrix} 0 \\\\ 0 \\\\ 1 \end{pmatrix}
   $$
   Nun bilden wir das Kreuzprodukt von $\vec{e}_1$ mit diesem Ergebnis:
   $$
   \vec{e}_1 \times \vec{e}_3 = \begin{pmatrix} 1 \\\\ 0 \\\\ 0 \end{pmatrix} \times \begin{pmatrix} 0 \\\\ 0 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 0 \cdot 1 - 0 \cdot 0 \\\\ 0 \cdot 0 - 1 \cdot 1 \\\\ 1 \cdot 0 - 0 \cdot 0 \end{pmatrix} = \begin{pmatrix} 0 \\\\ -1 \\\\ 0 \end{pmatrix} = -\vec{e}_2
   $$

**Vergleich der Ergebnisse:**
Da die linke Seite den Nullvektor $\vec{0}$ liefert, die rechte Seite jedoch den Vektor $-\vec{e}_2$, gilt:
$$
\begin{pmatrix} 0 \\\\ 0 \\\\ 0 \end{pmatrix} \neq \begin{pmatrix} 0 \\\\ -1 \\\\ 0 \end{pmatrix} \implies (\vec{a} \times \vec{b}) \times \vec{c} \neq \vec{a} \times (\vec{b} \times \vec{c})
$$
Damit ist bewiesen, dass das Kreuzprodukt nicht assoziativ ist.