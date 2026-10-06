# 🤝 CONTRIBUTING
## JAVASCRIPT-Learning

Merci de votre intérêt pour le projet JAVASCRIPT-Learning.  
Ce document explique comment contribuer efficacement, proprement et dans le respect du cadre pédagogique du projet.

---

🧭 Principes généraux

- Contribuer dans un esprit constructif, respectueux et pédagogique.
- Respecter les règles définies dans .RULES.md.
- Favoriser la clarté, la structure et la qualité du code.
- Toujours tester son code avant de proposer une contribution.

---

🛠️ Comment contribuer

1. Fork & Branch
- Forker le dépôt.
- Créer une branche dédiée à votre contribution :
  `
  feature/nom-de-la-fonction
  fix/nom-du-bug
  docs/amelioration-doc
  `
- Ne jamais travailler directement sur main.

2. Style du code
- Utiliser un JavaScript clair, moderne et lisible.
- Favoriser :
  - const / let
  - fonctions fléchées
  - modules ES
  - commentaires utiles
- Éviter :
  - var
  - code non structuré
  - duplication inutile

3. Structure des contributions
Les contributions doivent respecter la structure du projet :

`
cours/
├── debutant/
├── intermediaire/
├── avance/
└── expert/

docs/
├── introduction.md
├── structure.md
├── guide_pedagogique.md
...
`

Toute modification doit être cohérente avec cette organisation.

---

🧪 Tests & Vérifications

Avant toute PR :
- Vérifier que le code fonctionne dans un navigateur ou Node.js.
- Vérifier que les exemples sont corrects.
- Vérifier que les fichiers Markdown sont valides.
- Vérifier que les liens internes fonctionnent.

Pour les versions 6.0+ :
- Ajouter des tests Jest si nécessaire.

---

📝 Rédaction des Pull Requests

Chaque PR doit contenir :
- un titre clair ;
- un résumé précis des modifications ;
- les fichiers impactés ;
- la raison de la contribution ;
- un avant/après si pertinent.

Exemple :

`
Ajout du module "DOM avancé" dans cours/intermediaire/
`

---

📚 Documentation

Toute contribution impactant la logique du projet doit mettre à jour :
- docs/structure.md
- docs/guide_pedagogique.md
- ou tout autre fichier concerné.

---

🔐 Respect du cadre pédagogique

Le projet JAVASCRIPT-Learning est un espace :
- d’apprentissage,
- de progression,
- de partage,
- de collaboration.

Les contributions doivent renforcer cet objectif.

---

✔️ Merci de contribuer à JAVASCRIPT-Learning.
`

---
