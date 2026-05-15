# Äußere Tangenten - Lösung

### a) Anzahl der Tangenten in Abhängigkeit von $a$
Gegeben ist $f(x) = x^2$ und der Punkt $P_a(a|a)$.   
Zuerst bilden wir die Ableitung: $f'(x) = 2x$.

Die allgemeine Tangentengleichung an einer unbekannten Berührstelle $u$ lautet:
$$
\begin{aligned}
y &= f'(u) \cdot (x - u) + f(u)\\\\
y &= 2u \cdot (x - u) + u^2\\\\
y &= 2ux - u^2
\end{aligned}
$$

Da die Tangente durch den Punkt $P_a(a|a)$ verlaufen soll, setzen wir $x = a$ und $y = a$ ein:
$$
\begin{aligned}
a &= 2u \cdot a - u^2\\\\
0 &= u^2 - 2au + a
\end{aligned}
$$

Um die Anzahl der möglichen Berührstellen $u$ (und damit die Anzahl der Tangenten) zu bestimmen, nutzen wir die **$pq$-Formel** mit $p = -2a$ und $q = a$:
$$
\begin{aligned}
u_{1,2} &= -\frac{-2a}{2} \pm \sqrt{\left(\frac{-2a}{2}\right)^2 - a}\\\\
u_{1,2} &= a \pm \sqrt{a^2 - a}
\end{aligned}
$$

> **Wichtiger Hinweis:** Der Term unter der Wurzel entscheidet über die Anzahl der Lösungen. In der Mathematik nennt man diesen Term **Diskriminante** ($D = a^2 - a$).

### Fallunterscheidung nach der Diskriminante:

1.  **Zwei Tangenten ($D > 0$):**
    Wenn $a^2 - a > 0$ ist (also $a < 0$ oder $a > 1$), ergeben sich zwei verschiedene Werte für $u$. Es existieren somit zwei Tangenten.
2.  **Eine Tangente ($D = 0$):**
    Wenn $a^2 - a = 0$ ist (also $a = 0$ oder $a = 1$), gibt es nur eine Lösung. Der Punkt $P_a$ liegt in diesem Fall direkt auf dem Graphen von $f$.
3.  **Keine Tangente ($D < 0$):**
    Wenn $a^2 - a < 0$ ist (also $0 < a < 1$), ist der Wert unter der Wurzel negativ. Es gibt keine reelle Lösung; der Punkt liegt im "Inneren" der Parabel.

---

### b) Orthogonale Tangenten
Die Lösungen für die Berührstellen $u$ aus der Gleichung $u^2 - 2au + a = 0$ sind:
$u_{1,2} = a \pm \sqrt{a^2 - a}$

Die Steigungen an den Berührstellen $u_1$ und $u_2$ sind:  
$m_1 = f'(u_1) = 2u_1$  
$m_2 = f'(u_2) = 2u_2$

Zwei Tangenten stehen senkrecht (orthogonal) zueinander, wenn das Produkt ihrer Steigungen gilt:  
$m_1 \cdot m_2 = -1$

Einsetzen in die Bedingung:  
$(2u_1) \cdot (2u_2) = -1 \implies 4 \cdot (u_1 \cdot u_2) = -1$

Um den Wert für $a$ zu finden, gibt es zwei Wege:

### Weg 1: Der elegante Weg (Satz von Vieta)

!!! note "Der Satz von Vieta"
    Für eine quadratische Gleichung der Form $u^2 + pu + q = 0$ mit den Lösungen $u_1$ und $u_2$ gilt immer:

    * $u_1 + u_2 = -p$
    * $u_1 \cdot u_2 = q$

In unserer Gleichung $u^2 - 2au + a = 0$ entspricht das $q$ dem Parameter $a$.
Ohne die Wurzeln einzeln berechnen zu müssen, wissen wir also sofort:  
$$
\begin{aligned}
(u_1 \cdot u_2) = a
\end{aligned}
$$

Eingesetzt in unsere Orthogonalitätsbedingung:
$$
\begin{aligned}
4 \cdot a = -1 \implies a = -0,25
\end{aligned}
$$

---

### Weg 2: Der rechnerische Weg (Taschenrechner/Substitution)

Falls man den Satz von Vieta nicht parat hat, nutzt man die expliziten Lösungen der $pq$-Formel aus Aufgabenteil a):
$$
\begin{aligned}
u_1 = a + \sqrt{a^2 - a} \quad \text{und} \quad u_2 = a - \sqrt{a^2 - a}
\end{aligned}
$$

Wir setzen diese in $4 \cdot (u_1 \cdot u_2) = -1$ ein:
$$
\begin{aligned}
4 \cdot \left( (a + \sqrt{a^2 - a}) \cdot (a - \sqrt{a^2 - a}) \right) = -1
\end{aligned}
$$

Unter Anwendung der **3. Binomischen Formel** $(x+y)(x-y) = x^2 - y^2$ vereinfacht sich der Term in der Klammer:
$$
\begin{aligned}
4 \cdot \left( a^2 - (\sqrt{a^2 - a})^2 \right) &= -1\\\\
4a = -1 \implies a &= -0,25
\end{aligned}
$$

**Ergebnis:** Für den Parameterwert **$a = -0,25$** stehen die beiden Tangenten senkrecht zueinander.