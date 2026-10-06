📄 architecture.md

`markdown

Architecture JavaScript — JAVASCRIPT-Learning

Ce document présente les architectures professionnelles utilisées dans les projets JavaScript modernes.

MVC — Model View Controller
Séparation claire :
- Model : données
- View : interface
- Controller : logique

MVVM — Model View ViewModel
Adapté aux frameworks modernes (Vue, Angular).

Clean Architecture
Couches indépendantes :
- Domain
- Application
- Infrastructure
- UI

Patterns de conception

Singleton
Instance unique pour un module.

Observer
Système d’abonnement / notification.

Factory
Création d’objets structurée.

Module Pattern
Organisation du code en blocs isolés.

Organisation recommandée
```text
src/
├── models/
├── views/
├── controllers/
├── services/
└── utils/
```

Cette architecture est utilisée dans les versions avancées du projet.
`

---
