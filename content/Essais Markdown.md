# Essais Markdown
- Titres
# Titre h1
## Titre h2
### Titre h3
#### Titre h4
etc...

- <a id="FormulesLaTeX">Formules $\LaTeX$</a>
Entre balises `$...$` avec `Obsidian`.
$\begin{cases}y = 2x+1\\y = x-7\end{cases}$

- Listes à puces
- Item 1
- Item 2

- Liste numérotée
1. Première partie
2. Deuxième partie

- Cases à cocher
- [ ] Essai1
- [ ] Essai2
- [x] Essai 3

- Lien url vers site internet
Le lien directement : https://obsidian.md
Avec un texte alternatif : [Lien vers le site d'Obsidian](https://obsidian.md)

- Image 
![Texte alternatif](wall-e-and-eve.png)

- Fichier
[Lien vers image précédente](./wall-e-and-eve.png)
[Lien vers vidéo](./video.mp4)

<html>
<video autosize: true controls>
  <source src="https://www.youtube.com/watch?v=xyz" type="video/mp4">
</video>
</html>

[Lien vers un doc pdf](./document.pdf)

- Code brut
```python
def f(x):
	return x**2
```

Ce `code` est un exemple de code en ligne.

- Ligne horizontale
---
***

- Citation
> Ceci est une citation sur deux paragraphes. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

- Commentaires (syntaxe HTML)
```
Commentaires non visibles : <!-- Commentaires non visibles -->
```
donne :
Commentaires non visibles : <!-- Commentaires non visibles -->

Autre possibilité :
```markdown
Avant commentaire

[comment]: # Commentaire visible
Après commentaire
```
donne :
Avant commentaire

[comment]: # Commentaire visible
Après commentaire


- Tableaux
Tableau **sans alignement** :
```markdown
Titre colonne 1 | Titre colonne 1 | Titre colonne 1 
 --- | --- | --- 
Cellule 1.1 | Cellule 1.2 | Cellule 1.3 
Cellule 2.1 | Cellule 2.2 | Cellule 2.3 
```
donne :
Titre colonne 1 | Titre colonne 1 | Titre colonne 1 
 --- | --- | --- 
Cellule 1.1 | Cellule 1.2 | Cellule 1.3 
Cellule 2.1 | Cellule 2.2 | Cellule 2.3 
Avec **alignement** :
```markdown
Titre colonne 1 (droite) | Titre colonne 1 (centré) | Titre colonne 1 (gauche)
 ---: | :---: | :--- 
Cellule 1.1 | Cellule 1.2 | Cellule 1.3 
Cellule 2.1 | Cellule 2.2 | Cellule 2.3 
```
donne
Titre colonne 1 (droite) | Titre colonne 1 (centré) | Titre colonne 1 (gauche)
 ---: | :---: | :--- 
Cellule 1.1 | Cellule 1.2 | Cellule 1.3 
Cellule 2.1 | Cellule 2.2 | Cellule 2.3 

- Texte avec de la couleur
Le langage `markdown` ne le permet pas. On doit utiliser des balises `HTML`.
Un exemple :
Some Markdown text with <span style="color:blue">some blue text</span>.

- Adding an anchor
First, add an anchor as regular HTML in your Markdown element. Here, it is right at a heading.

`### <a id="MyHeading"></a>My Heading ###`

Now, I can link it using a standard Markdown link.

`Where is my [heading](#MyHeading)?`

Comment utiliser des [formules $\LaTeX$](#FormulesLaTeX) ?

- Notes de bas de page
```markdown
Bonjour[^1]
[^1]: Note de bas de page 1
```
donne :

Bonjour[^1]
Au revoir[^2]

Du texte intermédiaire *en italique*, **en gras**.
Du texte intermédiaire *en italique*, **en gras**.
Du texte intermédiaire *en italique*, **en gras**.
Du texte intermédiaire *en italique*, **en gras**.
Du texte intermédiaire *en italique*, **en gras**.
Du texte intermédiaire *en italique*, **en gras**.

Les notes de bas de page :

[^1]: Note de bas de page 1
[^2]: Note de bas de page 2