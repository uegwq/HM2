
TARGET DECK
Höhere Mathematik II

Differenzierbarkeit
--
## Definition
***
$f$ heißt in $x_0\in D$ differenzierbar $\iff$ es existiert eine $m\times n$-Matrix $A$ mit
$\lim_{h\rightarrow 0}\frac{f(x_0+h)-f(x_0)-Ah}{\Vert h \Vert}$
$A$ ist wenn sie existiert die Jaxobimatrix.
## Satz dazu
***
1. $f$ ist in $x_0$ differenzierbar $\iff$ Alle $f_j$ sind in $x_0$ differenzierbar. In diesem fall gilt
	1. $f$ ist in $x_0$ stetig
	2. $f$ ist in $x_0$ partiell differenzierbar
	3. Die Matrix $A$ ist eindeutig die Jacobimatrix.
2. Ist $f$ in $x_0$ differenzierbar, so heißt $f'(x_0):=J_f(x_0)$ die Ableitung von $f$ in $x_0$.
## Anderer Satz mit partiellen Ableitungen wie Kapitel 6
***
$$\text{Existieren alle partiellen Ableitungen } \frac{\partial f_j}{\partial x_k} \text{ auf } D \text{ und sind in } x_0 \text{ stetig, so ist } f \text{ in } x_0 \text{ differenzierbar.}
\]$$
$$
\text{Ist } f \in C^1(D, \mathbb{R}^m), \text{ so ist } f \text{ auf } D \text{ differenzierbar.}
$$
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt