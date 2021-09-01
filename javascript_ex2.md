
```js
let props = ['nom', 'prenoms', 'langages']
let vals = ["", "", []]
let o4 = {}
```

#### 5) référence ou copie ?
- Rajouter les propriétés (ou attributs) _props_ avec les valeurs _vals_ à l'objet __o4__
- Créer un nouvel objet __o5__ qui soit une copie de __o4__ ( utiliser _Object.assign()_ )
- Rajouter une valeur à _langages_ pour l'objet __o4__
- Afficher les _langages_ de __o5__
- Corriger pour que les _langages_ de __o4__ et __o5__ soient indépendants


#### 6) référence ou copie

On utilisera la notation :
```js
f = (tab, v) => { /*...*/ }
```

- Écrire une fonction qui rajoute la valeur _v_ à la fin d'un tableau _tab_.
- Créer un tableau G vide et lui appliquer cette fonction. Quelle est la valeur de A ?
- Que fait le code suivant ?
```js
const g = (ch1, ch2) => { ch1 += ch2 }
let ch1 = ""
const ch2 = "ok"
g(ch1)
console.log(ch1)
```
- Expliquer la différence de comportement avec la fonction _f_.
