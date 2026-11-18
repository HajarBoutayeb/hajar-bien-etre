# Hajar — Suivi bien-être

<img src="icon-512.png" width="120" alt="Icône de l'application Hajar">

**Hajar** est une application personnelle de suivi bien-être : nutrition, corps, habitudes et dépenses — synchronisée entre le téléphone et l'ordinateur grâce à Firebase.

![Hajar — identité visuelle](app-visual.png)

*Identité visuelle de l'application.*

## Fonctionnalités

- 🥗 **Nutrition** — suivi des repas, calories et macros, avec base d'aliments intégrée
- 💪 **Corps** — poids, masse grasse, masse musculaire, mensurations et IMC
- ✅ **Habitudes** — grille de suivi quotidien (spiritualité, santé, apprentissage…)
- 💰 **Dépenses** — suivi des dépenses
- 🔄 **Synchronisation** — les mêmes données sur téléphone et ordinateur, en temps réel
- 📴 **Mode hors-ligne** — l'application fonctionne aussi sans connexion

## Utilisation

1. Ouvrir l'application : https://hajarboutayeb.github.io/hajar-bien-etre/
2. Créer un compte (e-mail + mot de passe) ou se connecter
3. Les données se synchronisent automatiquement entre tous les appareils avec le même compte

Une version Android (APK) est aussi disponible, construite à partir de ce même code.

## Technologies

- HTML, CSS, JavaScript (application monopage)
- Firebase Authentication (connexion e-mail / mot de passe)
- Cloud Firestore (données synchronisées, règles de sécurité par utilisateur)
- GitHub Pages (hébergement)

## Confidentialité

Les données personnelles sont stockées dans Firebase et protégées par des règles de sécurité : chaque utilisateur ne peut voir et modifier que ses propres données. Ce dépôt contient uniquement le code de l'application — aucune donnée personnelle.
