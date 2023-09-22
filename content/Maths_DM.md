# Aide pour le devoir maison de mathématiques en cours (DM 2)
## ♾️ Remarques avant de démarrer
- Mes réponses à vos questions sont là pour vous aider à trouver par vous même en vous rappelant ce qui vous manque.
- Si une de mes réponses ne suffit pas à vous débloquer, vous revenez évidemment vers moi pour me le dire.
- Have fun!

## ♾️ Exercice 1

### 1.
#### ❓Question


####  💡 Réponse


### 2.
#### ❓Question

Pour la question 2, j'ai fait ceci :
```
def liste_carrés(n):
	return[n**2 for k in range(1,n)]
def sum(n):
	s=6/n
	for k in range(1,n+1):
		s=s*k**2
	return s
```
Mais je ne sais pas si c'est correct.

####  💡 Réponse

- Tu peux vérifier en copiant ce code dans le notebook Jupyter sur Capytale (code 07cf-1876511) et en exécutant le code.
- Ta première fonction n'est pas tout à fait correct car `range(a, b)` donne les entiers `n` compris entre `a` et `b`...mais `a` est **inclus** et `b`...**exclu**.
- Donc pour générer les entiers de $1$ à `n` (inclus), on écrit `range(1, n+1)`.
- Pour ta deuxième fonction, celle-ci doit s'appeler `u`. Le code commence donc par : `def u(n):`
- Ensuite il est demandé d'utiliser la fonction Python `sum` qui permet d'obtenir la somme des termes d'une liste. Comme dans l'expression de $u_n$, on rencontre la somme des carrés des entiers et comme la fonction `liste_carrés` donne justement la liste des carrées des entiers...


### 3.
#### ❓Question
Pour la question 3, je l'ai comprise mais je ne sais pas comment le faire en python. Auriez-vous quelques indices à me donner ?

####  💡 Réponse
Voici un code à compléter : `L = [u(n) for n in ...]`

### 4. a)
#### ❓Question
####  💡 Réponse


### 4. b)
#### ❓Question
Pour la question 4. b), je l'ai comprise mais je ne sais pas comment le faire en python. Auriez-vous quelques indices à me donner ?

####  💡 Réponse
Il suffit d'exécuter la fonction avec la bonne valeur pour la variable. Est-ce suffisamment clair avec ce vocabulaire ?

### 5. a)
#### ❓Question


####  💡 Réponse


### 5. b)
#### ❓Question


####  💡 Réponse


### 5. c)
#### ❓Question


####  💡 Réponse


### 6.
#### ❓Question


####  💡 Réponse



### 7.
#### ❓Question


####  💡 Réponse


