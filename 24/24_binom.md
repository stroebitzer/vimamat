Die Binomialverteilung ist eines der wichtigsten Modelle in der Wahrscheinlichkeitsrechnung. Sie hilft dir dabei, die Wahrscheinlichkeit für eine bestimmte Anzahl von „Treffern“ zu berechnen, wenn du ein Experiment mehrmals unter genau den gleichen Bedingungen wiederholst.

Stell dir vor, du wirfst eine Münze oder ziehst Lose aus einer Urne (mit Zurücklegen). Genau für solche Szenarien ist die Binomialverteilung gedacht.

Hier ist die schrittweise Erklärung, wie sie funktioniert:

### 1. Wann darf man die Binomialverteilung anwenden?

Damit ein Experiment binomialverteilt ist, müssen vier strenge Bedingungen erfüllt sein (man nennt das auch eine **Bernoulli-Kette**):

* **Nur zwei mögliche Ergebnisse:** Es gibt bei jedem Versuch nur "Treffer" (Erfolg) oder "Niete" (Misserfolg). *Beispiel: Münzwurf (Kopf oder Zahl) oder Würfeln (Eine 6 würfeln = Treffer, keine 6 würfeln = Niete).*
* **Konstante Wahrscheinlichkeit:** Die Wahrscheinlichkeit $p$ für einen Treffer muss bei jedem einzelnen Versuch immer gleich bleiben.
* **Unabhängigkeit:** Das Ergebnis eines Versuchs darf das Ergebnis der anderen Versuche nicht beeinflussen (z. B. beim Ziehen aus einer Urne muss die Kugel wieder zurückgelegt werden).
* **Feste Anzahl von Versuchen:** Das Experiment wird genau $n$-mal durchgeführt.

### 2. Die magische Formel

Wenn alle Bedingungen erfüllt sind, kannst du die Wahrscheinlichkeit berechnen, dass du bei $n$ Versuchen genau $k$ Treffer erzielst. Die Zufallsvariable $X$ steht dabei für die Anzahl der Treffer. Die Formel lautet:

$$P(X = k) = \binom{n}{k} \cdot p^k \cdot (1-p)^{n-k}$$

**Was bedeuten die einzelnen Teile der Formel?**

* **$P(X = k)$**: Die Wahrscheinlichkeit, genau $k$ Treffer zu erzielen.
* **$n$**: Die Gesamtzahl der Versuche.
* **$k$**: Die gewünschte Anzahl der Treffer.
* **$p$**: Die Wahrscheinlichkeit für einen Treffer bei einem *einzelnen* Versuch.
* **$(1-p)$**: Die Wahrscheinlichkeit für eine Niete (oft auch $q$ genannt).
* **$p^k$**: Die Wahrscheinlichkeit, dass genau $k$ Treffer hintereinander eintreten.
* **$(1-p)^{n-k}$**: Die Wahrscheinlichkeit, dass die restlichen $n-k$ Versuche Nieten sind.
* **$\binom{n}{k}$ (Binomialkoeffizient)**: Spricht man "n über k". Er berechnet, auf wie viele verschiedene Arten man die $k$ Treffer auf die $n$ Versuche verteilen kann (denn es ist ja egal, ob der Treffer beim ersten, dritten oder letzten Versuch passiert).

### 3. Ein praktisches Beispiel

Stell dir vor, du wirfst einen normalen Spielwürfel **3-mal** ($n = 3$).
Dein Ziel (Treffer) ist es, eine **6** zu würfeln. Die Wahrscheinlichkeit dafür ist bei jedem Wurf **$p = \frac{1}{6}$**. Die Nieten-Wahrscheinlichkeit $(1-p)$ ist also **$\frac{5}{6}$**.

Wie hoch ist die Wahrscheinlichkeit, bei den 3 Würfen **genau 2-mal** eine 6 zu würfeln ($k = 2$)?

Wir setzen in die Formel ein:

$$P(X = 2) = \binom{3}{2} \cdot \left(\frac{1}{6}\right)^2 \cdot \left(\frac{5}{6}\right)^{3-2}$$

* $\binom{3}{2} = 3$ (Es gibt 3 Möglichkeiten: 6-6-X, 6-X-6 oder X-6-6)
* $\left(\frac{1}{6}\right)^2 \approx 0,0277$
* $\left(\frac{5}{6}\right)^1 \approx 0,8333$

$$P(X = 2) = 3 \cdot 0,0277 \cdot 0,8333 \approx 0,0694$$

Die Wahrscheinlichkeit, bei 3 Würfen genau zwei 6er zu würfeln, liegt also bei etwa **6,94%**.

### 4. Der Erwartungswert

Ein weiterer wichtiger Begriff bei der Binomialverteilung ist der **Erwartungswert $E(X)$** (oder $\mu$). Er sagt dir, wie viele Treffer du *durchschnittlich* erwarten kannst, wenn du die Versuchsreihe sehr oft durchführst. Die Formel ist wunderbar einfach:

$$E(X) = n \cdot p$$

*Beispiel:* Wenn du eine Münze 100-mal wirfst ($n = 100$) und die Wahrscheinlichkeit für "Kopf" $p = 0,5$ ist, dann ist der Erwartungswert $100 \cdot 0,5 = 50$. Du erwartest also im Schnitt 50-mal "Kopf". Genau das repräsentiert auch immer den höchsten "Balken" (oder die Spitze) in der grafischen Darstellung der Verteilung, wie in deinem Bild aus der vorherigen Frage!
