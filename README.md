# Cahier de cotes P5-P6

Application de gestion des cotations P5/P6 préparée pour GitHub Pages et installable comme Progressive Web App (PWA).

## Fichiers

- `index.html` : application principale
- `manifest.webmanifest` : manifeste PWA
- `service-worker.js` : fonctionnement hors ligne
- `icons/` : icônes PWA locales

## Publication sur GitHub Pages

1. Créer un dépôt GitHub.
2. Déposer tous les fichiers et dossiers de ce projet à la racine de la branche principale.
3. Ouvrir **Settings → Pages**.
4. Choisir le déploiement depuis une branche.
5. Sélectionner la branche principale et le dossier racine `/`.
6. Enregistrer.
7. Ouvrir l’URL GitHub Pages fournie par GitHub.

Les chemins sont relatifs et compatibles avec une adresse du type :
`https://utilisateur.github.io/cahier-de-cotes/`

## Installation

### PC / macOS / Android
Lorsque le navigateur fournit le mécanisme PWA officiel, le bouton **Installer l’application** apparaît.

### iPhone / iPad
Dans Safari : **Partager → Ajouter à l’écran d’accueil → Ouvrir comme app web**.

## Hors ligne

Après une première ouverture réussie sur GitHub Pages, les ressources essentielles sont mises en cache. L’application peut ensuite redémarrer hors ligne pour ses fonctions locales.

## Sauvegarde des données

Les données restent enregistrées avec le stockage local déjà utilisé par l’application. La PWA ne remplace pas une sauvegarde externe.

Utiliser régulièrement **Exporter une sauvegarde** et conserver le fichier obtenu ailleurs.

## Mises à jour

À chaque future version nécessitant un rafraîchissement du cache, modifier `CACHE_NAME` dans `service-worker.js`, par exemple `cahier-cotes-v2`.
