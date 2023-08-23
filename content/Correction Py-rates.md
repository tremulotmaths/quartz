## Le site
[Py-rates](https://py-rates.fr/)

## Quelques remarques
- Vous trouverez ci-dessous une correction des niveaux accessibles sur ce sites au 20/12/22
- Il vous faudra effectuer plusieurs essais, car sur certains niveaux, on ne voit pas le trésor dès le début

## Niveau 1
```Python
# Ecrire le code de son programme ci-dessous
avancer()
droite()
avancer()
gauche()
avancer()
droite()
for _ in range(17):
	avancer()
ouvrir()
```

## Niveau 2
```Python
for _ in range(6):
	sauter()
	avancer()
avancer()
gauche()
avancer()
avancer()
for _ in range(9):
	coup()
	avancer()
avancer()
avancer()
ouvrir()
```

## Niveau 3
```Python
sauter_hauteur(4)
avancer()
sauter_hauteur(3)
avancer()
avancer()
for _ in range(4):
	message = lire_nombre()
	avancer()
	sauter_hauteur(message)
	avancer()
	avancer()
ouvrir()
```

## Niveau 4
```Python
for _ in range(5):
	avancer()
	message = lire_chaine()
	if message == "gau":
		gauche()
	else:
		droite()
	avancer()
avancer()
avancer()
ouvrir()
```

## Niveau 5
```Python
avancer()
sauter_haut()
for _ in range(5):
	hauteur = mesurer_hauteur()
	if hauteur == 0:
		avancer()
	elif hauteur == 1:
		sauter()
	else:
		sauter_haut()
	avancer()
	avancer()
ouvrir()
```

## Niveau 6
```Python
for i in range(6):
	sauter_hauteur(i)
	avancer()
ouvrir()
```

## Niveau 7
```Python
for i in range(7):
	tirer(i+2)
	tourner()
tirer(3)
```

## Niveau 8
```Python
avancer()
while detecter_obstacle():
	coup()
for _ in range(3):
	avancer()
droite()
for _ in range(5):
	avancer()
while detecter_obstacle():
	coup()
	avancer()
ouvrir()
```