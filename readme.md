# Introduction

L'objectif du document est la création d'une *cheat sheet* ou "feuille de triche". 

L'ensemble des fonctions que vous devez documenter se trouvent dans ce document, à vous de  remplir les espaces vides 😉

Ce document pourra vous suivre tout au long de vos études, n'hésitez à le compléter au fur et à mesure.

---

Pour compléter le document, vous utiliserez la fonction **fork** de GitHub pour copier ce projet dans votre espace personnel.

[Si besoin, rendez-vous dans ce dépôt pour revoir les bases de Javascript](https://github.com/Maxence-Machu/javascript-basic-memo)

---

## La fonction GetElementByID()

### Que fait la fonction ?
La méthode getElementById() renvoie un objet qui représente l'élément dont la propriété  id correspond à la chaîne de caractères spécifiée.
Étant donné que les ID d'élément doivent être uniques, s'ils sont spécifiés, ils constituent un moyen utile d'accéder rapidement à un élément spécifique.

### Pourquoi l'utiliser ?
La fonction getElementById doit être utilisée si l'on veut utiliser un élément du DOM en HTML grâce à Javascript 

#### Note supplémentaire
La fonction getElementByID est à ne pas confondre avec la fonction *getElementsByClassName*. 
Les ID dans une page web sont uniques, on ne peut donc pas récupérer plusieurs éléments avec cette fonction. 

### Exemple de code:
```javascript
let element = document.getElementByID('mon-element');
console.log(element);
```

## La fonction GetElementsByClassName()


### Que fait la fonction ?

renvoi la liste des elements appartenant à une classe 

### Pourquoi l'utiliser ?

La fonction getElementsByClassName doit être utilisée si l'on veut utiliser une liste d'éléments du DOM en HTML grâce à Javascript.

### Exemple de code:
```javascript
let liste_paragraphe = document.getElementsByClassName("paragraphe");

console.log(liste_paragraphe[0]);
```

## La fonction querySelector() et querySelectorAll()

### Que fait la fonction ?

Retourne le premier élément que contient la classe ".maclasse":

### Pourquoi l'utiliser ?

rapide efficace

### Exemple de code:
```javascript
let el = document.querySelector(".maclasse");
```

## La fonction addEventListener()

### Que fait la fonction ?

creer une fonction quand il y a un event ?  click -> event (lance une fonction quand il y a un event)

### Pourquoi l'utiliser ?
...

### Exemple de code:
```javascript
// CODE
```

## La fonction stopPropagation()

### Que fait la fonction ?
...

### Pourquoi l'utiliser ?
...

### Exemple de code:
```javascript
// CODE
```

## La fonction addEventListener('mousemove', maFonction)

### Que fait la fonction ?
...

### Pourquoi l'utiliser ?
...

### Exemple de code:
```javascript
// CODE
```

## La fonction parseInt()

### Que fait la fonction ?

La fonction parseInt() analyse une chaîne de caractère fournie en argument et renvoie un entier exprimé dans une base donnée.

### Pourquoi l'utiliser ?

pour changer un string en int 

### Exemple de code:
```javascript
function roughScale(x, base) {
  const parsed = parseInt(x, base);
  if (isNaN(parsed)) { return 0; }
  return parsed * 100;
}

console.log(roughScale(' 0xF', 16));
// expected output: 1500

console.log(roughScale('321', 2));
// expected output: 0
```


## La variable "event" dans le code suivant:

### Code:
```javascript
element.addEventListener('event-name', function(event)){
console.log(event);}
```

### Qu'est-ce que cette variable ?
...

### Pourquoi l'utiliser ?
...


