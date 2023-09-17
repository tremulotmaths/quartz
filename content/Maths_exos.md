# Aide pour les exercices à résoudre
## Exercice 78 p 138

Pour obtenir une expression de $h'(x)$, puis celle de $h''(x)$ de l'énoncé de l'exercice...il faut simplement le faire tranquillement ! ;)
$h$ est définie sur $I=[10;50]$ par $h(x)=\dfrac{90}{1+\text{e}^{-0,25x+6}}$.
Pour dériver $h$, on peut l'écrire sous la forme $\dfrac{u}{v}$ ou $90\times \dfrac{1}{v}$ avec $v(x)=1+\text{e}^{-0,25x+6}$.
Pour plus de simplicité (ou de fainéantise ;)), je choisis la deuxième version.
La fonction $v$ étant dérivable sur $I$ et ne s'annulant pas sur $I$, $h$ est dérivable sur $I$ et $h'=90\times \left(\dfrac{-v'}{v^2}\right)$.
$\forall x\in I$, $v'(x)=0-0,25\text{e}^{-0,25x+6}=-0,25\text{e}^{-0,25x+6}$.
Par conséquent, pour tout $x\in I$, $h'(x)=90\times \dfrac{0,25\text{e}^{-0,25x+6}}{\left(1+\text{e}^{-0,25x+6}\right)^2}$,
soit $h'(x)=\dfrac{22,5\text{e}^{-0,25x+6}}{\left(1+\text{e}^{-0,25x+6}\right)^2}$.
Ainsi $h'$ est de la forme $\dfrac{w}{z}$ avec $w(x)=22,5\text{e}^{-0,25x+6}$ et $z(x)=\left(1+\text{e}^{-0,25x+6}\right)^2$.
- $w$ est dérivable sur $I$
- $z$ est dérivable sur $I$ et ne s'annule pas sur $I$
Par quotient, $h'$ est dérivable sur $I$ et $h''=\dfrac{w'z-wz'}{z^2}$.
- $\forall x\in I$, $w'(x)=22,5\times \left(-0,25\text{e}^{-0,25x+6}\right)=-5,625\text{e}^{-0,25x+6}$
- $\forall x\in I$, $z'(x)=2\times \left(-0,25\text{e}^{-0,25x+6}\right)\times \left(1+\text{e}^{-0,25x+6}\right)=-0,5\text{e}^{-0,25x+6}\left(1+\text{e}^{-0,25x+6}\right)$
Par conséquent, pour tout $x\in I$,
$h''(x)=\dfrac{-5,625\text{e}^{-0,25x+6}\times \left(1+\text{e}^{-0,25x+6}\right)^2-22,5\text{e}^{-0,25x+6}\times \left[-0,5\text{e}^{-0,25x+6}\left(1+\text{e}^{-0,25x+6}\right)\right]}{\left(1+\text{e}^{-0,25x+6}\right)^4}$
En factorisant le numérateur par $\text{e}^{-0,25x+6}\left(1+\text{e}^{-0,25x+6}\right)$, on obtient :
$h''(x)=\dfrac{\text{e}^{-0,25x+6}\left(1+\text{e}^{-0,25x+6}\right)\left[-5,625\left(1+\text{e}^{-0,25x+6}\right)+11,25\text{e}^{-0,25x+6}\right]}{\left(1+\text{e}^{-0,25x+6}\right)^4}$
En simplifiant l'expression entre crochet, on obtient :
$h''(x)=\dfrac{\text{e}^{-0,25x+6}\left(1+\text{e}^{-0,25x+6}\right)\left(-5,625+5,625\text{e}^{-0,25x+6}\right)}{\left(1+\text{e}^{-0,25x+6}\right)^4}$
En factorisant le numérateur par $5,625$ et en simplifiant l'expression par $\left(1+\text{e}^{-0,25x+6}\right)$, on obtient :
$h''(x)=\dfrac{5,625\text{e}^{-0,25x+6}\left(-1+\text{e}^{-0,25x+6}\right)}{\left(1+\text{e}^{-0,25x+6}\right)^3}$
ce qui correspond à l'expression de l'énoncé.