
L'objet le plus simple :
```js
let o1 = {}
```

Des objets plus fournis :
```js
let o2 = {prenom : "toto", nom : "dupont", langages : ['js', "python"]}
```
<br><br>

#### 1)
- Afficher __o1__, __o2__ avec un `console.log()`
- Modifier le prénom de __o2__ en "tata"
- Ajouter la propriété "prenom" à __o1__ de 2 manières distinctes.
- Supprimer la propriété "prenom" de __o1__
- question : cette syntaxe est-elle correcte ?
```js
let o3 = {"prenom" : "titi", "nom" : "dupont", "langages" : ['js', "python"]}
```
<br><br>
  
#### 2)
- Créer un tableau vide A
- Créer un tableau B avec les valeurs de 1 à 5 incluses
- Créer un tableau C, le remplir avec les valeurs de 1 à 5 incluses
- Enlever la dernière valeur de B
- Rajouter une nouvelle valeur à B
<br><br>

#### 3)
```js
let D = [1, 2, 3, 1, 4, 1, 6]
```  

- 0 est-il dans le tableau D ?
- 1 est-il dans ce tableau ?
- Quel est le premier indice de la valeur 1 dans le tableau ?
- Quel est le second indice de la valeur 1 dans le tableau ?
- Enlever la première valeur de 1 dans le tableau
<br><br>

#### 4)
- "js" appartient-il aux _langages_ de __o2__ ?
- Rajouter 'bash' aux _langages_ de __o2__
- Afficher les valeurs des _langages_ de __o2__ avec une boucle __for__
- Afficher les valeurs des _langages_ de __o2__ avec le mot clef __map__
- Afficher le nom et la valeur de toutes les propriétés de l'objet __o2__ avec le mot clef *for*
<br><br>

##### Exercice : 
Créer un tableau E de taille 100 composé avec des entiers entre 0 et 9 inclus pris aléatoirement.  
Ecrire le code qui enlève toutes les valeurs égales à 1 dans ce tableau.  
Créer un nouveau tableau F avec les valeurs de E comprises entres les indices 10(inclus) à 20(non-inclus).  
Inverser le tableau F.  
Ce programme est-il fiable à 100% ?