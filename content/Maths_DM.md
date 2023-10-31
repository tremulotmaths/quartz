# Aide pour le devoir maison de mathématiques en cours (DM 3)
## ♾️ Remarques avant de démarrer
- Mes réponses à vos questions sont là pour vous aider à trouver par vous même en vous rappelant ce qui vous manque.
- Si une de mes réponses ne suffit pas à vous débloquer, vous revenez évidemment vers moi pour me le dire.
- Have fun!

## ♾️ Exercice 1

### 1. a)
#### ❓Question
Je ne comprends pas comment remplir l'algorithme python à la question 1. a)

####  💡 Réponse
Cette fonction python doit permettre de calculer les termes de la suite $(T_n)$.

Autrement dit, `T(n)` doit renvoyer la valeur $T_n$.

Comme la suite $(T_n)$ est définie par $\begin{cases}T_0=0,9\\T_{n+1}=T_n-0,1T_n^2\end{cases}$ la fonction python `T(n)` doit calculer le bon terme de la suite.

La suite étant définie par récurrence, si l'on souhaite calculer $T_{10}$ (avec `T(10)`), on doit connaître la valeur de $T_9$ puisque $T_{10}=T_9-0,1T_9^2$.

Or pour calculer $T_9$, on connaître $T_8$, etc.

Par conséquent, pour calculer $T_{10}$, on part de la valeur de $T_0$ qui est connue.

Grâce à celle-ci, on calcule $T_1$.

Grâce à la valeur de $T_1$, on calcule $T_2$.

etc.

De proche en proche, on obtient $T_{10}$.

La fonction python proposée suit le même principe :

- on initialise `T` (variable qui va successivement contenir les valeurs $T_n$ jusqu'à celle cherchée) à $T_0$, c'est-à-dire `0.9`
- on écrit une boucle permettant de calculer de proche en proche les valeurs successives de $T_n$ jusqu'à celle cherchée
- on sort de la boucle quand on a calculé la valeur dont l'indice a été donné en paramètre de la fonction python

### 1. b)
#### ❓Question


####  💡 Réponse


### 1. c)
#### ❓Question


####  💡 Réponse


### 2. a)
#### ❓Question



####  💡 Réponse



### 2. b)
#### ❓Question

Je ne vois pas comment passer l'hérédité de la récurrence. Pourriez-vous m'aider ?

####  💡 Réponse

On est dans un cas où le passage de la proposition $\mathcal{P}_n$ à $\mathcal{P}_{n+1}$ ne se fera pas avec les opérations de base.

Mais contrairement à ce que ma phrase pourrait laisser penser...cela va aller plus vite !

La proposition $\mathcal{P}_n$ correspond à $0\leq T_{n+1}\leq T_n\leq 1$.

Comme la fonction $f$ est une fonction croissante sur l'intervalle $[0;1]$, on en déduit :

$f(0)\leq f(T_{n+1})\leq f(T_n)\leq f(1)$

Je vous laisse terminer...en une ligne.


### 2. c) Question à passer (nécessite le théorème 10 du chapitre)

### 3.
#### ❓Question

####  💡 Réponse


### 4.
#### ❓Question

####  💡 Réponse


