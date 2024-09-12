
TARGET DECK
Höhere Mathematik II

Fourierreihe
--
## Definition
***
Voraussetzung:
$f:\Bbb R\mapsto \Bbb R$, und $f$ ist Riemann-Integrierbar und $2-\pi$-Periodisch (man kann alles aber auch für jegliche Perioden definierten ofc lolz). Dann gilt:
$f \text{ "}=\text" \frac{a_0}{2}+\sum^\infty_{n=0}a_ncos(nx)+b_nsin(nx)$  
$\implies$ Fourierreihe
Es gilt für die Fourierkoeffizienten:
$(a_n)_{n\in\Bbb N}=\frac{1}{\pi}\int^\pi_{-\pi}f(x)cos(nx)dx$
$(b_n)_{n\in\Bbb N}=\frac{1}{\pi}\int^\pi_{-\pi}f(x)sin(nx)dx$
##  Wann konvergiert die Fourierreihe?
***
- $f$ ist stückweise glatt $\implies$ Fourierreihe konvergiert (nicht unbedingt gegen $f$ xd, an den Sprungstellen (falls es sie gibt) Konvergiert die Funktion (aber auch bei allen Punkten eigentlich) gegen den durchschnitt des links- und rechtsseitigen Grenzwertes)
- $f$ ist stetig $\implies$ Fourierreihe konvergiert gegen $f$
## Weiterer wichtiger Satz
***
- Ist $f$ gerade, so beschreiben wir die Fourierreihe von $f$ nur durch Cosinusterme
- Ist $f$ ungerade, so beschreiben wir die Fourierreihe von $f$ nur durch Sinusterme
## Siehe auch
***
* [[Komplexe Fourierreihen]]