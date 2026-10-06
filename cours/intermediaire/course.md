`markdown

Cours Intermédiaire — Logique, Fonctions, DOM

🎯 Objectifs
- Maîtriser les fonctions avancées
- Manipuler tableaux et objets
- Modifier le DOM
- Créer des interactions utilisateur

---

1. Fonctions avancées

Fonctions anonymes
`js
const f = function() {
    console.log("Anonyme");
};
`

Fonctions fléchées
`js
const add = (a, b) => a + b;
`

---

2. Tableaux
`js
let fruits = ["pomme", "banane", "orange"];
fruits.push("kiwi");
`

Méthodes utiles :
- map()
- filter()
- reduce()

---

3. Objets
`js
let user = {
    nom: "Alex",
    age: 25,
    saluer() {
        console.log("Salut !");
    }
};
`

---

4. DOM — Manipulation de la page web

Sélection
`js
const titre = document.getElementById("titre");
`

Modification
`js
titre.textContent = "Nouveau titre";
`

Événements
`js
button.addEventListener("click", () => {
    alert("Clique !");
});
`

---

5. Mini‑projet : Compteur interactif
`js
let n = 0;

document.getElementById("plus").onclick = () => {
    n++;
    document.getElementById("affiche").textContent = n;
};
`

---

✔️ Résultat attendu
Vous savez créer des pages web interactives et structurées.
`

---
