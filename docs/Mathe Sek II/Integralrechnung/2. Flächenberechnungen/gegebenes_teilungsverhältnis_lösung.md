# Gegebenes Teilungsverhältnis - Lösung

### Teilaufgabe a) Berechnung des Flächeninhalts

* **Nullstellen berechnen:**

\begin{align*}
x^3 - \frac{11}{2}x^2 + 7x = 0\\
x(x^2 - 5,5x + 7) = 0
\end{align*}

Die erste Nullstelle ist bei $x_1 = 0$.  
Mittels p-q-Formel und $x^2 - 5,5x + 7 = 0$ erhält man, dass die zweite Nullstelle bei $x_2 = 2$ und die dritte Nullstelle bei $x_3 = 3,5$ ist.


* **Teilflächen berechnen:**

\begin{align*}
A_1 &= \int_{0}^{2} (x^3 - 5,5x^2 + 7x) \, dx\\ 
&= [\frac{1}{4}x^4 - \frac{11}{6}x^3 + 3,5x^2]_0^2\\
&= 4 - \frac{44}{3} + 14 = \frac{10}{3} \approx 3,33
\end{align*}

und

\begin{align*}
A_2 = \int_{2}^{3,5} (x^3 - 5,5x^2 + 7x) \, dx\\ 
&= [\dots]_2^{3,5} \approx -1,55
\end{align*}
   
* **Gesamtfläche:**  
   $A_{ges} = \frac{10}{3} + |-1,55| = 4,88$ FE

---

### Teilaufgabe b) Gerade $x = a$
Die Gesamtfläche beträgt ca. $4,88$ FE. Ein Drittel davon ($1:2$ Teilung) ist:
$A_{teil} = 4,88 / 3 \approx 1,627  $ FE.

Da die erste Teilfläche $A_1$ bereits $3,33$ FE groß ist, muss die Gerade $x = a$ innerhalb des ersten Intervalls $[0; 2]$ liegen.

**Ansatz:**

$$\int_{0}^{a} (x^3 - 5,5x^2 + 7x) \, dx = 1,627$$
$$[\frac{1}{4}x^4 - \frac{11}{6}x^3 + 3,5x^2]_0^a = 1,627$$
$$\frac{1}{4}a^4 - \frac{11}{6}a^3 + 3,5a^2 = 1,627$$

Diese Gleichung 4. Grades wird üblicherweise mit einem WTR/CAS gelöst.
**Ergebnis:** $a \approx 0,886$ (für den linksseitigen Teil $1/3$). Die negative Lösung $a\approx -0,59$ entfällt im Intervall $[0; 2]$.