
TARGET DECK
Höhere Mathematik II

lineares Differentialgleichungssystem
--
## Definition
***
Es sei $A=(a_{jk})$ eine reelle $n\times n$ Matrix und $b_j:I\rightarrow\Bbb R$ stetig. Die betrachten das sogenannte lineare Differentialgleichungssystem
$\begin{matrix} y'_1(x)=a_{11}y_1(x) + a_{12}y_2(x) + \dots + a_{1n}y_n(x) + b_1(x) \\  y'_2(x)=a_{21}y_1(x) + a_{22}y_2(x) + \dots + a_{2n}y_n(x) +b_2(x) \\ \dots \\  y'_n(x)=a_{n1}y_1(x) + a_{n2}y_2(x) + \dots + a_{nn}y_n(x)+ b_n(x) \end{matrix}$
man schreibt dann halt $y'(x)=Ay(x)+b(x)$ (inhomogenes System) oder falls $b(x)=0$ $y'(x)=Ay(x)$ (homogenes System)
## Lösung
***
Idee: Lösung von dem homogenen System ist:
$$e^{xA}=\sum^\infty_{k=0}\frac 1 {k!}(xA)^k$$Schreibe $A$ über Jordan-Normalform
$A=S^{-1}JS$
$\rightsquigarrow e^{tA}=S^{-1}e^{tJ}S \rightsquigarrow$ Rechne $S^{-1}e^{tJ}$.
#### Vorbemerkung
Ist $\lambda\in\Bbb R$ Eigenwert von $A$, $v\in\Bbb R^n\setminus\{0\}$ Eigenvektor.....? :(

### Methode
1. Bestimme alle Eigenwerte $\lambda_1\dots,\lambda_r$ von $A$.
	(d.h. $r\le n$) und deren algebraische Vielfachheiten $K_1,\dots,K_r$. d.h. $p(\lambda)=(-1)^n(\lambda-\lambda_1)^{K_1} \cdot\dots\cdot(\lambda-\lambda_n)^{K_n}$
		Dann nehmen wir alle Eigenwerte, und sortieren sie nach 
		1. reele,
		2. rein Komplexe,
		3. komplexe die nicht auch einen realteil haben 
		4. komplexe, die konjugiert sind (also negatives Vorzeichen vor dem Imaginärteil)
		5. Werfe die 4. weg und schreibt die in einer Menge $M$ auf.
2. Wir nehmen uns jetzt einen Beliebigen Eigenwert $\lambda_j\in M$ und wir bestimmen eine Basis $V_j:=kern(A-\lambda_jI)^{k_j}$.
   Dies machen wir so:
	  Bestimme eine Basis von $kern (𝐴 − 𝜆_𝑗𝐼)$, ergänze diese zu einer Basis von $kern (𝐴 − 𝜆_𝑗𝐼) ^2,\dots$. (bis $K_j$)
3. Jez hamma basis $V_j$ für alle Eigenwerte $\lambda_j$ lolz. Setzt $$y(x):=e^{\lambda_jx}\left(v+\frac x {1!}(A-\lambda_jI)v+\frac{x^2}{2!}(A-\lambda_jI) ^2+\dots+\frac{x^{k_j-1}}{(k_j-1)!}(A-\lambda_jI)^{k_j-1}v\right)$$ (j ist die Nummer von dem Eigenwert den wir gerade behandeln, wir suchen uns ein $\lambda_j$ aus und definieren und so dann die Funktion.)
   So es gibt jetzt zwei Möglichkeiten:
	Fall 1:
	$y(x)$ ist Reelwertig, dann ist $y(x)$ eine Lösung des homogenen Systems
	Falls 2:
	$y(x)$ ist komplexwertig, dann zerlege $y(x)=y^{(1)}(x)+iy^{(2)}(x)$
	 $y^{(1)},y^{(2)}$ sind Lösungen des homogenen Systems.
4. Führe 3. für alle $\lambda_j\in M$ und Basisvektoren $v$ von $V_j$ durch

## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt