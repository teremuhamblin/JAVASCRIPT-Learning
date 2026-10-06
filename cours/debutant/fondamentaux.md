`markdown

Cours Débutant — Les Fondamentaux de JavaScript

🎯 Objectifs
- Comprendre les bases du langage
- Manipuler les variables, types, opérateurs
- Utiliser les conditions et les boucles
- Écrire vos premiers scripts simples

---

1. Introduction à JavaScript
JavaScript est un langage interprété, orienté objet, utilisé principalement pour rendre les pages web interactives.

Il s’exécute dans :
- les navigateurs (Chrome, Firefox…)
- Node.js (serveur, scripts, outils)

---

2. Variables

Déclaration
`js
let x = 10;
const PI = 3.14;
var old = "ancienne syntaxe";
`

Types principaux
- number  
- string  
- boolean  
- object  
- array  
- null  
- undefined  

---

3. Opérateurs

Mathématiques
`js
let a = 5 + 3;   // 8
let b = 10 / 2;  // 5
`

Comparaison
`js
5 > 3
5 === "5"   // false
5 == "5"    // true (à éviter)
`

---

4. Conditions
`js
let age = 20;

if (age >= 18) {
    console.log("Adulte");
} else {
    console.log("Mineur");
}
`

---

5. Boucles

for
`js
for (let i = 0; i < 5; i++) {
    console.log(i);
}
`

while
`js
let n = 0;
while (n < 3) {
    n++;
}
`

---

6. Fonctions simples
`js
function saluer(nom) {
    return "Bonjour " + nom;
}
`

---

7. Mini‑projet : Calculatrice simple
`js
function calcul(a, b, op) {
    if (op === "+") return a + b;
    if (op === "-") return a - b;
    if (op === "") return a  b;
    if (op === "/") return a / b;
}
`

---

✔️ Résultat attendu
Vous maîtrisez les bases nécessaires pour passer au niveau intermédiaire.
`

---
