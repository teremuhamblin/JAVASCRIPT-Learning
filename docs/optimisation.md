📄 optimisation.md

`markdown

Optimisation JavaScript — JAVASCRIPT-Learning

Ce document présente les techniques d’optimisation pour améliorer les performances.

Web Workers
Permet d’exécuter du code en parallèle.

Lazy Loading
Chargement des ressources uniquement quand nécessaire.

Debounce & Throttle
Réduction des appels répétitifs.

Exemple debounce
`js
function debounce(fn, delay) {
    let timer;
    return (...args) => {
        clearTimeout(timer);
        timer = setTimeout(() => fn(...args), delay);
    };
}
`

Optimisation DOM
- Minimiser les reflows
- Grouper les modifications
- Utiliser documentFragment

Optimisation mémoire
- Nettoyer les timers
- Libérer les références inutiles

Ces techniques sont utilisées dans les versions 7.0+ du projet.
`

---
