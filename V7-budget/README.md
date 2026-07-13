# Mon Budget — Édition neutre premium

Application web personnelle de gestion budgétaire, installable sur iPhone et déployable gratuitement sur Vercel.

## Fonctionnalités

- Revenus et dépenses, fixes ou variables
- Budgets mensuels personnalisables
- Objectifs d’épargne et d’investissement
- Comptes, patrimoine et calendrier financier
- Analyses, graphiques et recommandations locales
- Sauvegarde automatique dans IndexedDB
- Export/import JSON
- Mode clair et sombre
- PWA installable sur iPhone

## Lancer localement

```bash
npm install
npm run dev
```

## Vérifier la production

```bash
npm run build
npm run start
```

## Déploiement Vercel

Importez le dépôt GitHub dans Vercel. Aucun réglage ou domaine payant n’est requis.

> Les données restent sur l’appareil utilisé. Exportez régulièrement une sauvegarde JSON.

## Navigation mobile
La barre de navigation inférieure contient désormais : Accueil, Transactions, Calendrier, Comptes et Analyses. Les sections Budgets et Objectifs ont été retirées de la navigation.

## Correctifs de cette version
- Suppression des menus « ... » sans action sur les cartes de l’accueil.
- Remplacement de « Vos priorités du mois » par la vue du patrimoine suivi.
- Modification et suppression des comptes depuis l’onglet Comptes.
- Nom d’accueil personnalisable dans Paramètres.
- Aucun package-lock.json inclus afin de laisser Vercel installer les dépendances depuis package.json.
