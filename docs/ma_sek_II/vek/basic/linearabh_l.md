# Lineare Abhängigkeit - Lösung

### a) Prüfung über Linearkombination
Ansatz: $r \begin{pmatrix} 3 \\ -3 \\ -3 \end{pmatrix} + s \begin{pmatrix} -3 \\ 5 \\ -3 \end{pmatrix} = \begin{pmatrix} -4 \\ 7 \\ -5 \end{pmatrix}$
$$
\begin{aligned} 
(1) && 3r - 3s &= -4 \\\\
(2) && -3r + 5s &= 7 \\\\
(3) && -3r - 3s &= -5 \end{aligned}
$$
Addiert man (1) und (2): $2s = 3 \implies s = 1,5$.  
Einsetzen in (1): $3r - 4,5 = -4 \implies 3r = 0,5 \implies r = \frac{1}{6}$.  
Prüfung in (3): $-3(\frac{1}{6}) - 3(1,5) = -0,5 - 4,5 = -5$.  
Das System ist lösbar. Die Vektoren sind **linear abhängig**.

### b) Prüfung über Linearkombination
Ansatz: $r \begin{pmatrix} 3 \\ -2 \\ 1 \end{pmatrix} + s \begin{pmatrix} -5 \\ 1 \\ 0 \end{pmatrix} = \begin{pmatrix} -3 \\ -1 \\ -2 \end{pmatrix}$
$$
\begin{aligned} (1) && 3r - 5s &= -3 \\\\
(2) && -2r + s &= -1 \implies s = 2r - 1 \\\\
(3) && r &= -2 \end{aligned}
$$
Einsetzen von $r = -2$ in (2): $s = 2(-2) - 1 = -5$.  
Prüfung in (1): $3(-2) - 5(-5) = -6 + 25 = 19 \neq -3$.  
Das System liefert einen Widerspruch. Die Vektoren sind **linear unabhängig**.

### c) Prüfung durch "scharfes Auge"
Betrachtet man $\vec{a}$ und $\vec{b}$, erkennt man sofort:
$$ \vec{b} = -2 \cdot \vec{a} $$
Da $\vec{b}$ ein Vielfaches von $\vec{a}$ ist, sind diese beiden Vektoren kollinear. Damit lässt sich der Nullvektor durch $2\vec{a} + 1\vec{b} + 0\vec{c} = \vec{0}$ darstellen.
Da es eine Linearkombination des Nullvektors gibt, bei der nicht alle Koeffizienten Null sind, sind die Vektoren **linear abhängig**.