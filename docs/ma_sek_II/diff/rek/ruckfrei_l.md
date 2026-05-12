# Ruckfreie Trassierung - Lösung

### Aufgabe a)
#### Mathematische Begründung
Eine Funktion $f(x) = a_n x^n + ... + a_2 x^2 + a_1 x + a_0$ hat an der Stelle $x = 0$ folgende Eigenschaften:
$$
f(0) = a_0, \quad f'(0) = a_1, \quad f''(0) = 2a_2
$$

Da die Trasse entlang der negativen $x$-Achse die Steigung $0$ und die Krümmung $0$ besitzt, muss für einen ruckfreien Übergang gelten:

* $f(0) = 0$ (versatzfrei)
* $f'(0) = 0$ (knickfrei)
* $f''(0) = 0$ (krümmungsstetig/ruckfrei)

Dies ist genau dann erfüllt, wenn $a_0 = 0, a_1 = 0$ und $a_2 = 0$ gilt, der Term also keine Glieder mit $x^2$ und $x$ (und kein Absolutglied) enthält.

### Aufgabe b)
#### Aufstellen des Gleichungssystems
Aus a) folgt der Ansatz:
$$
f(x) = ax^5 + bx^4 + cx^3
$$

Die Bedingungen am Punkt $Q(1|0)$ mit $g(x) = 2,5x^2 - 4x + 1,5$ lauten:

* $f(1) = g(1) = 0$
* $f'(1) = g'(1) = 1$
* $f''(1) = g''(1) = 5$

Dies führt zu folgenden Gleichungen:

1. $a + b + c = 0$
2. $5a + 4b + 3c = 1$
3. $20a + 12b + 6c = 5$

??? note "Vollständige Lösung des LGS"
    #### Explizite Lösung des LGS
    Zuerst eliminieren wir $c$ durch Umstellen von Gleichung I:
    $$
    c = -a - b \quad (\text{I.a})
    $$

    Einsetzen von I.a in II und III:
    
    \begin{align}
    \text{II. neu:} \quad & 5a + 4b + 3(-a - b) = 1 \implies 2a + b = 1 \\
    \text{III. neu:} \quad & 20a + 12b + 6(-a - b) = 5 \implies 14a + 6b = 5
    \end{align}
    

    Nun eliminieren wir $b$, indem wir die neue Gleichung II mit $-6$ multiplizieren und zu III addieren:
    
    \begin{aligned}
    -12a - 6b &= -6 \\
    14a + 6b &= 5 \\
    \hline
    2a &= -1 \implies a = -0,5
    \end{aligned}
    

    Rückwärtseinsetzen zur Bestimmung von $b$ und $c$:

    * $2(-0,5) + b = 1 \implies -1 + b = 1 \implies b = 2$
    * $c = -(-0,5) - 2 \implies c = -1,5$

Durch Lösen des Systems erhält man die Koeffizienten:

* $a = -0,5$
* $b = 2$
* $c = -1,5$

#### Endgültige Funktion
Die gesuchte Funktionsgleichung lautet:
$$
f(x) = -0,5x^5 + 2x^4 - 1,5x^3
$$