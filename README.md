# AquaManager — MVP 1

Prototype mobile-first pour gérer plusieurs aquariums, leurs mesures et les entretiens.

## Contenu
- `index.html` : application complète (interface + logique)
- `manifest.webmanifest` : configuration PWA
- `sw.js` : cache hors-ligne simple

## Fonctions
- Plusieurs aquariums (eau douce, récifal, saumâtre)
- Saisie et historique des mesures : GH, KH, pH, NO3, NO2, NH4, PO4, température
- Entretiens ponctuels ou récurrents
- Export / import JSON
- Stockage local dans le navigateur

## Mise en ligne sur iPhone
Une PWA doit être servie depuis une adresse HTTPS. Déploie ces fichiers sur un hébergement statique HTTPS (par exemple un hébergement web personnel), puis sur l'iPhone :
1. Ouvre l'adresse dans Safari.
2. Appuie sur Partager.
3. Choisis « Sur l'écran d'accueil ».
4. Active « Ouvrir comme app » si l'option est proposée.

## Important
Cette première version stocke les données dans le navigateur de l'appareil. Effacer les données du site peut les supprimer : utilise régulièrement l'export JSON. Il n'y a pas encore de synchronisation entre appareils, de notifications système, de graphiques avancés, ni de comptes utilisateurs.
