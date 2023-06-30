# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ❌ / ✔️
- les normes `ecmascript` ❌ / ✔️
- l'utilisation de l'`asynchrone` ❌ / ✔️
- les spécifités du mot-clef `this` ❌ / ✔️

#### Les structures de base du language
Le JavaScript est un langage de programmation dynamique généralement utilisé pour donner vie aux pages web en permettant des actions interactives.

Elles utilisent des élémelents structurels de base suivant :

Variables : En JavaScript, les variables peuvent être déclarées en utilisant les mots-clés "var", "let" ou "const". Elles sont utilisées pour stocker des valeurs pour une utilisation ultérieure.

```let nom = 'John'; // déclaration d'une variable avec "let"
const PI = 3.14; // déclaration d'une constante avec "const"
Types de données : JavaScript a plusieurs types de données : nombre (Number), chaîne de caractères (String), booléen (Boolean), objet (Object), tableau (Array), null et indéfini (Undefined).```

Opérateurs : JavaScript a de nombreux opérateurs, y compris les opérateurs arithmétiques (+, -, *, /, %), les opérateurs de comparaison (==, !=, <, >), les opérateurs logiques (&&, ||) et bien d'autres.

Structures de contrôle : Les structures de contrôle, comme dans beaucoup d'autres langages de programmation, comprennent les instructions conditionnelles "if", "else if" et "else", ainsi que les boucles "for", "while" et "do while".

if (condition) {
    // code à exécuter si la condition est vraie
} else {
    // code à exécuter si la condition est fausse
}

for(let i = 0; i < 10; i++) {
    // code à exécuter pour chaque itération
}

Fonctions : Les fonctions en JavaScript sont des blocs de code réutilisables. Elles peuvent prendre des arguments et renvoyer une valeur.
function nomDeLaFonction(argument1, argument2) {
    // code à exécuter
    return resultat;
}

Objets : En JavaScript, presque tout est un objet. Les objets sont des collections de paires clé-valeur (également appelées propriétés).

let voiture = {
    marque: 'Toyota',
    modele: 'Corolla',
    annee: 2005
};

Tableaux : Un tableau est un objet global utilisé pour stocker plusieurs valeurs dans une seule variable.
let fruits = ['Pomme', 'Banane', 'Cerise'];
Événements : Les événements sont des actions ou des occurrences qui se produisent dans le système que vous programmez, souvent déclenchées par l'utilisateur interagissant avec le système.

Erreur et gestion des exceptions : On peut utiliser des blocs "try...catch" pour gérer les exceptions et gérer les erreurs.


#### les normes `ecmascript`

ECMAScript (ou ES) est un standard pour les scripts, dont JavaScript est une implémentation.
ECMAScript définit la syntaxe et les fonctionnalités du langage, mais il ne définit pas les fonctionnalités qui sont liées à l'exécution du code dans un navigateur (par exemple, manipuler le DOM, ou Document Object Model). Ces fonctionnalités sont généralement définies par des standards séparés.
Le but du standard ECMAScript est de s'assurer que le langage de script reste stable et qu'il existe une norme de référence pour les personnes qui développent des produits compatibles, comme les moteurs JavaScript pour les navigateurs.


#### Les specificités de l'asynchrone

En JavaScript, il y a plusieurs façons de gérer l'asynchronisme : les rappels (callbacks), les promesses et les mots-clés async/await qui sont basés sur les promesses. L'asynchronisme est utile lorsqu'on effectue des opérations qui peuvent prendre du temps, comme des appels API, des lectures de fichiers, des opérations de base de données, etc.

##### Rappels (Callbacks)
 Un rappel est une fonction qui est passée en argument à une autre fonction et qui est exécutée une fois l'opération asynchrone terminée. C'est la manière la plus ancienne de gérer l'asynchronisme en JavaScript, mais elle peut mener à ce qu'on appelle l'"enfer des callbacks" (callback hell) si on a plusieurs opérations asynchrones qui dépendent les unes des autres.

##### Promesse
Une promesse est un objet qui représente l'achèvement ou l'échec d'une opération asynchrone. Une promesse peut être dans l'un des trois états suivants : en attente (pending), accomplie (fulfilled) ou rejetée (rejected). Les promesses peuvent être chaînées et sont donc une meilleure solution pour gérer plusieurs opérations asynchrones dépendantes.

##### asynch/await

Les mots-clés async et await ont été introduits en ES2017 pour rendre l'écriture de code asynchrone encore plus facile et lisible. Une fonction marquée avec async renvoie une promesse, et l'utilisation de await à l'intérieur d'une fonction async fait que l'exécution de la fonction est mise en pause jusqu'à ce que la promesse soit résolue.
'await' ne peut être utilisé qu'à l'intérieur d'une fonction async, et il fait que l'exécution de la fonction soit mise en pause jusqu'à ce que la promesse soit résolue ou rejetée.

## 💻 Je code en Javascript

### Un exemple de code commenté ❌ / ✔️

```javascript
(e) => mc2;
```

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

