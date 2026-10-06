📄 securite.md

`markdown

Sécurité JavaScript — JAVASCRIPT-Learning

La sécurité est essentielle dans tout projet JavaScript moderne.

Principales menaces
- XSS (Cross-Site Scripting)
- CSRF
- Injection de scripts
- Manipulation DOM non sécurisée

Bonnes pratiques

1. Ne jamais utiliser eval()
Extrêmement dangereux.

2. Toujours valider les entrées
`js
if (typeof input !== "string") throw Error("Invalid input");
`

3. Utiliser les Content Security Policies (CSP)
Empêche l’exécution de scripts non autorisés.

4. Échapper les données affichées
`js
element.textContent = userInput;
`

5. Utiliser HTTPS
Chiffrement obligatoire.

Sécurité dans les API
- Vérifier les tokens
- Limiter les permissions
- Protéger les endpoints sensibles

Ce module est intégré dans les niveaux avancé et expert.
`

---
