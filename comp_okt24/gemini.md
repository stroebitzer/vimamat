Gerne! Hier sind die detaillierten Lösungswege und Erklärungen zu allen vier Aufgaben aus der vorliegenden Kompensationsprüfung.

---

## Aufgabe 1: Poolbillard

**a1) Ermitteln des Vektors $\vec{AB}$**

* Um den Vektor zwischen zwei Punkten zu berechnen, zieht man die Koordinaten des Anfangspunkts von den Koordinaten des Endpunkts ab (Spitze minus Schaft).

* Die Punkte sind $A=(18|6)$ und $B=(12|0)$.

* Die Rechnung lautet:

$$\vec{AB} = \binom{12}{0} - \binom{18}{6} = \binom{-6}{-6}$$

**a2) Kennzeichnen der Größe $z$**

* Die vorgegebene Formel lautet $z = \sin(90^\circ - \alpha) \cdot \overline{AC}$.

* Nach den Regeln der Trigonometrie ist $\sin(90^\circ - \alpha)$ identisch mit $\cos(\alpha)$.
* In einem rechtwinkeligen Dreieck berechnet man den Cosinus als Quotient aus Ankathete und Hypotenuse. Wenn die Strecke $\overline{AC}$ die Hypotenuse darstellt, dann entspricht $z$ der Ankathete.
* Geometrisch bedeutet das: Wenn man von Punkt C das Lot auf die Gerade durch A und B fällt, ist $z$ die Strecke vom Punkt A bis zum Lotfußpunkt auf dieser Geraden.

**b1) Gleichungssystem für v und h erstellen**

* Wir definieren $v$ als die Anzahl der "Vollen" und $h$ als die Anzahl der "Halben".

* Auf dem Tisch liegen insgesamt die weiße Kugel, die schwarze Kugel, sowie die Vollen und Halben. Die Gesamtzahl der Kugeln ist somit $v + h + 2$.

* Die erste Bedingung besagt, dass **50%** aller Kugeln "Volle" sind. Daraus folgt die Gleichung:

$$v = 0,5 \cdot (v + h + 2)$$

* Die zweite Bedingung besagt, dass dreimal so viele "Volle" wie "Halbe" auf dem Tisch liegen. Daraus folgt die Gleichung:

$$v = 3 \cdot h$$

---

## Aufgabe 2: Seilbahn

**a1) Zurückgelegter Weg im Zeitintervall $[0; 11]$**

* In einem Geschwindigkeit-Zeit-Diagramm entspricht der zurückgelegte Weg der Fläche unter dem Graphen der Funktion.

* Die Fläche kann berechnet werden, indem man den Flächeninhalt des großen Rechtecks (Breite 11, Höhe 5) nimmt und das leere Trapez im oberen Bereich abzieht.

* Die Rechnung dazu lautet:

$$11 \cdot 5 - \frac{11 + 5}{2} \cdot 4,5 = 19$$

* Der zurückgelegte Weg beträgt demnach **19 m**.

**a2) Graph der Beschleunigung-Zeit-Funktion**

* Die Beschleunigung ist die Steigung (Änderungsrate) der Geschwindigkeit.

* Im Zeitintervall von **0 bis 3 Sekunden** sinkt die Geschwindigkeit linear von 5 auf 0,5 m/s. Die Steigung beträgt

$$\frac{0,5 - 5}{3} = -1,5\text{ m/s}^2$$

.

* Im Zeitintervall von **3 bis 8 Sekunden** bleibt die Geschwindigkeit konstant bei 0,5 m/s. Die Steigung ist in diesem Bereich **0 m/s²**.

* Im Zeitintervall von **8 bis 11 Sekunden** steigt die Geschwindigkeit linear von 0,5 auf 5 m/s. Die Steigung beträgt

$$\frac{5 - 0,5}{3} = 1,5\text{ m/s}^2$$

.

**b1) Interpretation der Berechnung**

* Die Rechnung

$$\frac{2100\text{ m} - 1102\text{ m}}{370\text{ s}} \approx 2,7\text{ m/s}$$

 teilt die zurückgelegte Höhendifferenz durch die Fahrtdauer.

* Das Ergebnis beschreibt die mittlere Änderungsrate der Höhe der Seilbahngondel.

* Im Sachzusammenhang bedeutet das: Die Höhe der Gondel nimmt pro Sekunde um durchschnittlich rund 2,7 Meter zu.

---

## Aufgabe 3: Brötchenteig

**a1) Gleichung der Funktion $V$ aufstellen**

* Das Volumen wächst exponentiell, daher nutzen wir die Formel $V(t) = V_0 \cdot a^t$, wobei $t$ die Zeit in Stunden ist.

* Zum Zeitpunkt $t = 0$ beträgt das Volumen 56 cm³, somit ist der Startwert $V_0 = 56$.

* Nach 30 Minuten, also zum Zeitpunkt $t = 0,5$ Stunden, beträgt das Volumen 89 cm³.

* Setzt man das in die Gleichung ein, erhält man:

$$89 = 56 \cdot a^{0,5}$$

* Löst man nach $a$ auf, ergibt sich $a \approx 2,525$. Die Funktionsgleichung lautet somit:

$$V(t) = 56 \cdot 2,525^t$$

**a2) Widerlegung von Norberts Behauptung**

* Die Verdoppelungszeit $T$ bedeutet, dass sich das Volumen des Teiges in dieser Zeit genau verdoppelt (mit 2 multipliziert wird).

* Für das erste Brötchen mit 60 cm³ ergibt sich nach dieser Zeit ein Volumen von:

$$60\text{ cm}^3 \cdot 2 = 120\text{ cm}^3$$

* Für das zweite Brötchen, das um 5 cm³ kleiner ist (also 55 cm³ hat), ergibt sich:

$$(60\text{ cm}^3 - 5\text{ cm}^3) \cdot 2 = 110\text{ cm}^3$$

* Die Differenz der Volumina beträgt nach der Verdoppelungszeit nun

$$120\text{ cm}^3 - 110\text{ cm}^3 = 10\text{ cm}^3$$

. Da **10 cm³ $\neq$ 5 cm³** ist, ist die Behauptung falsch.

**b1) Zeitpunkt für 75% der Dichte berechnen**

* Gesucht ist der Zeitpunkt $t$, an dem die Dichte $D(t)$ genau 75% (also den Faktor 0,75) des Startwerts $D_0$ beträgt.

* Die Gleichung lautet:

$$D_0 \cdot 0,75 = D_0 \cdot 0,9847^t$$

* Kürzt man $D_0$ auf beiden Seiten, bleibt:

$$0,75 = 0,9847^t$$

* Durch Lösen der Exponentialgleichung (z.B. mit Logarithmus) erhält man $t \approx 18,65$.

* Nach rund 18,7 Minuten sinkt die Dichte somit auf 75% des ursprünglichen Wertes.

---

## Aufgabe 4: Socken

**a1) Wahrscheinlichkeit für 2 grüne Socken beim 3. Ziehen**

* Es gibt insgesamt 11 Socken (4 grüne, 7 violette) und es wird 3-mal ohne Zurücklegen gezogen.

* Joe soll erst nach dem 3. Zug genau 2 grüne Socken haben. Das bedeutet, der dritte gezogene Socken *muss zwingend* grün sein.

* Bei den ersten beiden Zügen muss genau ein grüner und ein violetter Socken gezogen werden. Dafür gibt es zwei mögliche Reihenfolgen: (Grün, Violett) oder (Violett, Grün).
* Die Wahrscheinlichkeit für diese Pfade berechnet sich wie folgt:

$$2 \cdot \frac{4}{11} \cdot \frac{7}{10} \cdot \frac{3}{9} = 0,169...$$

* Die Wahrscheinlichkeit beträgt rund **17%**.

**b1) Formel für die Anzahl der Möglichkeiten $m$**

* In der Lade befinden sich insgesamt 9 Socken, wovon $n$ Stück weiß und der Rest blau sind.

* Socken derselben Farbe sind nicht voneinander unterscheidbar. Die Anzahl der Anordnungsmöglichkeiten $m$ wird daher mit dem Binomialkoeffizienten für Kombinationen ohne Beachtung der Reihenfolge berechnet.

* Die Formel lautet:

$$m = \binom{9}{n}$$

**c1) Beschreibung des Ereignisses E**

* Es gibt insgesamt 14 Socken (6 rote und 8 schwarze) und es wird 2-mal ohne Zurücklegen gezogen.

* Der Term $\frac{6}{14} \cdot \frac{8}{13}$ beschreibt die Wahrscheinlichkeit, zuerst einen roten und dann einen schwarzen Socken zu ziehen.

* Der Faktor $2$ in der Formel $1 - 2 \cdot \frac{6}{14} \cdot \frac{8}{13}$ berücksichtigt, dass die zwei unterschiedlichen Farben in zwei Reihenfolgen (Rot-Schwarz oder Schwarz-Rot) gezogen werden können.

* Man berechnet hier also $1 - P(\text{zwei unterschiedliche Farben})$. Das Gegenereignis dazu bedeutet, dass beide gezogenen Socken die gleiche Farbe haben müssen.

* Das Ereignis E lautet demnach: "Joe zieht 2 Socken gleicher Farbe".
