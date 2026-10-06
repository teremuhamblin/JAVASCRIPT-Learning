`markdown

Cours Avancé — Asynchronisme, API, Modules

🎯 Objectifs
- Comprendre l’asynchronisme
- Utiliser fetch() et les API
- Maîtriser async/await
- Organiser le code avec les modules ES

---

1. Promises
`js
const promesse = new Promise((resolve) => {
    setTimeout(() => resolve("OK"), 1000);
});
`

---

2. async / await
`js
async function charger() {
    const data = await promesse;
    console.log(data);
}
`

---

3. API — fetch()
`js
async function getUsers() {
    const res = await fetch("https://jsonplaceholder.typicode.com/users");
    const data = await res.json();
    console.log(data);
}
`

---

4. Modules ES

export
`js
export function saluer() {
    return "Salut !";
}
`

import
`js
import { saluer } from "./utils.js";
`

---

5. Gestion d’erreurs
`js
try {
    let x = JSON.parse("erreur");
} catch (e) {
    console.error("Erreur détectée");
}
`

---

6. Mini‑projet : Tableau dynamique depuis API
- Récupérer des données
- Afficher dans un tableau HTML
- Mettre à jour en temps réel

---

✔️ Résultat attendu
Vous êtes capable de créer des applications web modernes et robustes.
`

---
