
TARGET DECK
Höhere Mathematik II

Definitionen des $\Bbb R^n$
--
## Definition $\Bbb R^n$
***
$\mathbb{R}^n := \{ (x_1, \ldots, x_n) : x_1, \ldots, x_n \in \mathbb{R} \}$
## Definition Operationen auf $\Bbb R^n$
***
a) Die Zahl $x \cdot y := x \cdot y := x_1 y_1 + \ldots + x_n y_n$ wird Skalarprodukt von $x$ und $y$ genannt.

b) Die Zahl $\| x \| := \sqrt{x \cdot x} = \left( x_1^2 + \ldots + x_n^2 \right)^{\frac{1}{2}}$ wird als die Norm oder die Länge von $x$ bezeichnet.  Bemerke: $\| x \|^2 = x \cdot x$. Im Falle von $n = 1$ gilt $\| x \| = |x|$.

c) Die Zahl $\| x - y \|$ wird als Abstand zwischen $x$ und $y$ bezeichnet. Bemerke: $\| x - y \| = \| y - x \|$. 
## Eigenschaften der Operationen
***
a) $(x + y) \cdot z = x \cdot z + y \cdot z$, $x \cdot y = y \cdot x$.
b) $(\alpha x) \cdot y = \alpha (x \cdot y) = x \cdot (\alpha y)$.
c) $\| x \| \geq 0$; $\| x \| = 0 \Leftrightarrow x = 0 = (0, \ldots, 0)$.
d) $\| \alpha x \| = |\alpha| \| x \|$.
e) $|x \cdot y| \leq \| x \| \| y \|$ (Cauchy-Schwarz-Ungleichung (CSU)).
f) $\| x + y \| \leq \| x \| + \| y \|$ (Dreiecksungleichung).
g) $| \| x \| - \| y \| | \leq \| x - y \|$.
h) $\forall j \in \{1, \ldots, n\} : |x_j| \leq \| x \| \leq \sum_{k=1}^n |x_k|$.

e) die CSU gilt genau dann Gleichheit, wenn $x$ und $y$ linear abhängig sind.
## Siehe auch
***
* [[Epsilon-Umgebung in Rn]]
* [[Matrix]]
* [[Partielle Ableitung]]