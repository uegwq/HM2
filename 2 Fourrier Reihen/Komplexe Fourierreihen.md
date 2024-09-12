
TARGET DECK
Höhere Mathematik II

Komplexe Fourierreihen
--
## Definition
***
Es sei $f:\Bbb R \rightarrow \Bbb C$ 2$\pi$-periodisch und Riemann-Integrierbar, d.h. Re(f) und Im(f) integrierbar.
Dann sind:
$$c_n=\frac{1}{2\pi}\int^\pi_{-\pi}f(x)e^{-inx}$$die komplexen Fourierkoeffizienten. Die komplexe Fourierreihe ist demnach definiert als:
$$\sum^\infty_{n=-\infty}c_ne^{inx}$$
## Zusammenhang mit reellen Fourierreihen
***
Es sei $f:\Bbb R \rightarrow \Bbb C$ 2$\pi$-periodisch
$c_n=\frac{1}{2}(a_n-b_n)$
$c_0=\frac{a_0}{2}$
$c_{-n}=\bar{c_n}=\frac{1}{2}(a_n+b_n)$
## Konvergenz komplexer Fourierreihen
***
$\sum^\infty_{n=-\infty}c_ne^{inx}$ konvergiert $\iff$
$\lim_{n\rightarrow\infty}\sum^n_{k=-n}c_ke^{ikx}$ existiert.
Bemerkung: Wenn $f$ stückweise Glatt ist, konvergiert die Fourierreihe gegen $\frac{f(x^+)+f(x^-)}{2}$.
## Parsevalsche Gleichung
***
Sei $f:\Bbb R\rightarrow \Bbb R$ 2$\pi$-periodisch und Riemann integrierbar mit reellen Fourierkoeffizienten $a_n$ und $b_n$.  
Dann gilt:
$$\frac{a_0^2}{2}+\sum^\infty_{n=1}(a_n^2+b_n^2)=\frac{1}{\pi}\int^\pi_{-\pi}f(x)^2dx$$
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt