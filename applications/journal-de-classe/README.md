# Mon Journal de Classe — GitHub Pages / PWA

Cette version est préparée pour être déposée telle quelle dans un dépôt GitHub et publiée avec GitHub Pages.

## Fichiers

- `index.html` : application Journal de Classe, basée directement sur la version fournie.
- `manifest.webmanifest` : manifeste PWA.
- `service-worker.js` : fonctionnement hors ligne après une première ouverture via GitHub Pages.
- `icons/` : icônes de l'application.
- `JOURNAL-CLASSE-WBE-SOURCE-ORIGINALE.html` : copie intacte du fichier source fourni.

## Publication GitHub Pages

1. Créer un dépôt GitHub.
2. Envoyer tous les fichiers et dossiers contenus dans ce ZIP à la racine du dépôt.
3. Dans **Settings > Pages**, choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`.
4. Ouvrir ensuite l'adresse GitHub Pages générée.

## Données

Le passage au format PWA ne supprime pas les mécanismes de sauvegarde existants de l'application. Les données locales restent liées au navigateur et au site sur lequel l'application est utilisée. Utiliser les fonctions de sauvegarde/restauration déjà présentes dans le Journal pour transférer les données entre appareils ou adresses différentes.
