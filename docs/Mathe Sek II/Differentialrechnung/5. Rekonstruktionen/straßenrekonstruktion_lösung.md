# Straßenrekonstruktion - Lösung

### a) Analyse der Bedingungen

**1. Steigung der alten Straße:**
Die Bundesstraße ist eine Gerade durch $A(0|4)$ und $B(4|0)$.
$$
\begin{aligned}
m &= \frac{y_2 - y_1}{x_2 - x_1} \\\\
m &= \frac{0 - 4}{4 - 0} = -1
\end{aligned}
$$
Damit die Mündung "knickfrei" ist, muss die Umgehungsstraße in $A$ und $B$ ebenfalls die Steigung $f'(x) = -1$ besitzen.

**2. Aufstellen der mathematischen Bedingungen:**
Wir haben folgende 5 Anforderungen:

1. $f(0) = 4$ (Punkt $A$)
2. $f'(0) = -1$ (Knickfrei in $A$)
3. $f(4) = 0$ (Punkt $B$)
4. $f'(4) = -1$ (Knickfrei in $B$)
5. $f(2) = 1$ (Punkt $C$)

**3. Ermittlung des Mindestgrades:**
Da wir **5 Bedingungen** haben, benötigen wir eine Funktion mit 5 Parametern ($a, b, c, d, e$). Dies entspricht einer ganzrationalen Funktion **4. Grades**.
Ansatz: $f(x) = ax^4 + bx^3 + cx^2 + dx + e$

---

### b) Bestimmung der Funktionsgleichung

**Aufstellen des Gleichungssystems:**
Unter Verwendung der Ableitung $f'(x) = 4ax^3 + 3bx^2 + 2cx + d$ ergeben sich:
$$
\begin{aligned}
&\text{I. } & f(0) = 4 &\implies e = 4 \\\\
&\text{II. } & f'(0) = -1 &\implies d = -1 \\\\
&\text{III. } & f(4) = 0 &\implies a(4)^4 + b(4)^3 + c(4)^2 + (-1)(4) + 4 = 0 \\\\
&\text{IV. } & f'(4) = -1 &\implies 4a(4)^3 + 3b(4)^2 + 2c(4) + (-1) = -1 \\\\
&\text{V. } & f(2) = 1 &\implies a(2)^4 + b(2)^3 + c(2)^2 + (-1)(2) + 4 = 1
&\end{aligned}
$$

**Vereinfachtes System:**
$$
\begin{aligned}
256a + 64b + 16c &= 0 \\\\
256a + 48b + 8c &= 0 \\\\
16a + 8b + 4c &= -1
\end{aligned}
$$

**Lösung via CAS:**
Durch Lösen des Systems erhält man:
$$
\begin{aligned}
a &= -\frac{1}{16} = -0,0625 \\\\
b &= \frac{1}{2} = 0,5 \\\\
c &= -1 \\\\
d &= -1 \\\\
e &= 4
\end{aligned}
$$

**Ergebnis:**
Die Funktionsgleichung der Umgehungsstraße lautet:
$$
\begin{aligned}
f(x) = -0,0625x^4 + 0,5x^3 - x^2 - x + 4
\end{aligned}
$$