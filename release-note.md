# Release Notes — Silo Trésorerie (domain-treasury)

Toutes les versions publiées de ce dépôt respectent la spécification [SemVer 2.0.0](https://semver.org/lang/fr/).

---

## [0.0.1] - 2026-11-07

### Type de release
**Version initiale** (mise en place et validation de la structure autonome multi-dépôts)

### Résumé
Première version stable du silo Trésorerie (`domain-treasury`), regroupant `treasury-api` et `treasury-core` avec import du BOM centralisé, cycle de build autonome et configuration de déploiement GitHub Packages.

### Changements par composant
- **`treasury-api`** : contrats, ports, interfaces de service (calcul de trésorerie) (aucun changement métier).
- **`treasury-core`** : moteur de calcul pur, et persistance JPA des revenus, charges, ponctuels, virements et variables.

### Rétro-compatibilité & Compatibilité binaire
Non applicable : version initiale, aucune version antérieure publiée.
