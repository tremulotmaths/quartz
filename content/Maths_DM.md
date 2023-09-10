# Aide pour le devoir maison de mathématiques en cours (DM 1)
## ♾️ Remarques avant de démarrer
- Mes réponses à vos questions sont là pour vous aider à trouver par vous même en vous rappelant ce qui vous manque.
- Si une de mes réponses ne suffit pas à vous débloquer, vous revenez évidemment vers moi pour me le dire.
- Have fun!

## ♾️ Exercice 1

### 1.
#### ❓Question

J'utilise la formule $y=f'(a)(x-a)+f(a)$, avec $a=1$. Et $f'(x)= \dfrac{1}{2\sqrt{1}}$.
Je ne sais pas si je suis censé faire intervenir la formule avec $h$ et le faire tendre vers 0 ou non
####  💡 Réponse
La formule est correcte.
Concernant la dérivée, j'imagine que tu veux dire $f'(x)=\dfrac{1}{2\sqrt{x}}$ ou $f'(1)=\dfrac{1}{2\sqrt{1}}$...mais pas un mix des deux.
On a effectivement $f'(1)=\dfrac{1}{2\sqrt{1}}$, et comme $\sqrt{1}=1$...on obtient $f'(1)=\dfrac{1}{2}$.
Comme $f(1)$ ce simplifie bien également...tu devrais trouver une équation de tangente proche...de ce qui apparaît dans la question **2.**

### 2. a)
#### ❓Question
####  💡 Réponse

### 2. b)
#### ❓Question
####  💡 Réponse

### 2. c)
#### ❓Question
####  💡 Réponse

### 2. d)
#### ❓Question

Pour la d) de l'exercice 1 je ne sais pas comment déterminer le signe de la fonction $d$ à cause de sa forme je sais qu'elle est négative (sauf en $x=1$) en faisant des essais mais je ne sais pas comment le prouver.

####  💡 Réponse

Lorsque cela paraît compliqué...c'est que la solution est beaucoup plus simple.
Si tu réponds à la question 2.b) en dressant un tableau de variations et tu ajoutes à ce tableau la valeur obtenue à la question 2.c)...cela devrait te paraître beaucoup plus simple.
Pour en dire un peu plus...je crois que la valeur en $1$ est le maximum de la fonction $d$...

### 2. e)
#### ❓Question

Dans la question 2. e) du DM 1, il est demandé d’interpréter le résultat de la question 2. d) en termes de positions relatives entre la courbe $\mathcal{C}$ et la tangente $\mathcal{T}$. C’est à dire qu’il faut déterminer la position de la tangente par rapport à sa courbe à l’aide du signe de $d(x)$ ? J’ai peut être mal compris la question mais si je l’ai bien compris, je ne sait pas comment m’y prendre…
####  💡 Réponse

Tu as bien compris.

#### ❓Question

Je ne comprends pas comment répondre à la question 2)e) de l’exercice 1. pouvez vous m’aider ?
####  💡 Réponse

$d(x)$ a été défini comme la différence entre $f(x)$ et $\dfrac{1}{2}x+\dfrac{1}{2}$ (ce qui correspond à la fonction affine représentée par la tangente $\mathcal{T}$).
Or le signe de la différence entre deux quantités permet de déterminer la quantité qui est supérieure à l'autre.
Autrement dit, avec deux quantités $A$ et $B$, 
$A-B>0\Leftrightarrow A>B$.
Ici, $d(x)>0\Leftrightarrow f(x)-\left(\dfrac{1}{2}x+\dfrac{1}{2}\right)>0\Leftrightarrow f(x)>\dfrac{1}{2}x+\dfrac{1}{2}$,
et $d(x)<0\Leftrightarrow f(x)-\left(\dfrac{1}{2}x+\dfrac{1}{2}\right)<0\Leftrightarrow f(x)<\dfrac{1}{2}x+\dfrac{1}{2}$.
Or lorsque $f(x)>\dfrac{1}{2}x+\dfrac{1}{2}$ sur un intervalle $I$, la courbe de $f$ est au-dessus de la droite $\mathcal{T}$ sur cet intervalle.
De même, lorsque $f(x)<\dfrac{1}{2}x+\dfrac{1}{2}$ sur un intervalle $I$, la courbe de $f$ est au-dessous de la droite $\mathcal{T}$ sur cet intervalle.


## ♾️ Exercice 2

#### ❓Question

Est ce que dans l'exercice 2 du dm de maths, toutes les lignes de code doivent être utilisées ?  
Et quant aux questions suivantes ( fonction cube etc..) doivent-elles êtres faites sur python?

####  💡 Réponse

Non, toutes les lignes ne sont pas à utiliser.
Et tout l'exercice doit bien être traité avec Python.

## ♾️ Exercice 3

#### ❓Question

Pour l'exercice 3 en utilisant la formule de dérivé $f(x)=\dfrac{u(x)}{v(x)}$, 
$f'(x)=\dfrac{u'(x)v(x)-u(x)v'(x)}{v(x)^2}$.
En développant je me retrouve avec : $\dfrac{nx²\text{e}^{nx}-\text{e}^{nx}}{x²}$ 
Je voulais d'abord savoir s'il était bon de développer $\left(nx\text{e}^{nx}\right)x = nx²\text{e}^{nx}$
Et ensuite si mon développement était bon si je devais m'arrêter là ou continuer.

####  💡 Réponse

Pour justifier que la fonction $f_n$ admet un minimum, étudier les variations de $f_n$ est une bonne idée.
Cela revient, ici, à étudier le signe de $f_n'(x)$ sur $]0;+\infty[$.
Par contre, le numérateur de ta dérivée est faux.
C'est certainement dû à la mauvaise dérivée de la fonction $x\mapsto \text{e}^{nx}$, qui est $x\mapsto n\text{e}^{nx}$ et non $x\mapsto nx\text{e}^{nx}$.
Ensuite, dernier point : pour étudier le signe d'une expression (pour laquelle on n'a pas de formules particulières), on...factorise.
Il suffira donc de factoriser le numérateur de la dérivée et d'étudier le signe de chacun des facteurs.
Sinon, l'égalité $\left(nx\text{e}^{nx}\right)x = nx²\text{e}^{nx}$ est bien vraie...même si, elle n'est plus utile une fois l'erreur corrigée.