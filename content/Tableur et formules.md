Voici quelques unes des formules les plus utilisées dans les feuilles de calculs sur un tableur.

## Remarque
Une formule démarre toujours par le symbole =

## Formules usuelles
### Somme de valeurs
Pour calculer la somme des valeurs comprises entre les cellules `A1` et `A7`, voici plusieurs possibilités :
- `=SOMME(A1:A7)`
- `=A1+A2+A3+A4+A5+A6+A7`
### Moyenne de valeurs
Pour calculer la moyenne des valeurs comprises entre les cellules `A1` et `A7` :
- `=MOYENNE(A1:A7)`
### Quotient de valeurs
Pour diviser le contenu de la cellule `A2` par le contenu de la cellule `A10` :
- `=A2/A10`
Si on veut pouvoir étirer la formule précédente vers la droite sans que `A10` ne soit modifié dans la formule on ajoute un `$` devant l'information qui serait modifiée en étirant la formule :
- `=A2/$A10`
### Conditions
Pour afficher `VRAI` si le contenu de la cellule `A1` est strictement supérieur à 100 et `FAUX` sinon, voici plusieurs possibilités :
- `=SI(A1>100;"VRAI";"FAUX")`
- `=(A1>100)` (parenthèses inutiles)
La deuxième écriture renvoie un **booléen**, c'est-à-dire la valeur `VRAI` ou `FAUX` en fonction de la vérification de la condition écrite.

Voici d'autres conditions :
- `=(A1=100)` teste si la valeur contenue dans la cellule `A1` est égale à 100
- `=(A1<>100)` teste si la valeur contenue dans la cellule `A1` est différente de 100
- `=(A1<=100)` teste si la valeur contenue dans la cellule `A1` est inférieure ou égale à 100

Lorsque l'on utilise des booléens, on peut les combiner avec les opérations logiques `OU` et `ET` par exemple :
- `=ET(A1>100, A2>100)` renvoie `VRAI` si les **deux** valeurs contenues dans les cellules `A1`  et `A2` sont supérieures strictement à 100
- `=OU(A1>100;A2>100)` renvoie `VRAI` si **au moins** une des deux valeurs contenues dans les cellules `A1`  et `A2` sont supérieures strictement à 100

Lorsque l'on souhaite compter le nombre de cellules d'une plage de cellules vérifiant une condition :
- `=NB.SI(A1:B5;">100")` dénombre le nombre de cellules dans le tableau délimité par les cellules `A1` et `B5` contenant une valeur strictement supérieure à 100

### Autres exemples
- Vous avez d'autres exemples à la page 181 de votre manuel.
- Vous trouverez également sur internet de nombreux sites vous donnant des formules avec des exemples. Voici quelques pages web qui vous en donnent :
	- https://blog.hubspot.fr/marketing/fonctions-excel
	- https://www.maths-et-tiques.fr/index.php/maths-et-numerique-clg/3-tableur