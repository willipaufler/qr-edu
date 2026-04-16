# Wasserfontäne - Tipp

Hier sind die Hinweise zur Modellierung des Wasserstrahls:

1.  **Koordinatensystem festlegen:** Lege die Düse auf die y-Achse. Damit ist der Startpunkt der Fontäne der y-Achsenabschnitt bei $S(0 | 0,25)$.

2.  **Bedingungen aus dem Text:**
    * **Startpunkt:** Der Strahl startet bei $x=0$ in einer Höhe von $0,25$. Also: $f(0) = 0,25$.
    * **Endpunkt:** Der Strahl landet bei $x=0,5$ auf dem Boden ($y=0$). Also: $f(0,5) = 0$.
    * **Maximalhöhe:** Der höchste Punkt liegt bei $0,45\text{ m}$. Das bedeutet, der Funktionswert eines Hochpunkts ist $0,45$. **Achtung:** Da du die Stelle $x$ des Hochpunkts noch nicht kennst, nutze die Bedingung für das Maximum: $f(x_{max}) = 0,45$ und $f'(x_{max}) = 0$.

3.  **Allgemeiner Ansatz:** Da es eine Parabel 2. Grades ist, verwende:
    $$ f(x) = ax^2 + bx + c $$


Eine weitere elegante Lösung gibt es über die Scheitelpunktform einer Parabel $f(x)=a(x-x_s)^2+y_s$.