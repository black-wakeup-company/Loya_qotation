# Loyal Qotation V1

MVP PWA de création et gestion de Qotations pour Loyal Engineering.

## Fonctionnalités
- Création, modification, suppression et recherche de Qotations
- Calcul automatique USD
- Statuts Brouillon / Envoyée / Acceptée / Refusée
- Paramètres du nom, coordonnées et logo
- Thème brillant / sombre
- Impression A4 / PDF via la boîte d'impression du navigateur
- Zone « Fait à / Le » et signatures en bas du document
- Stockage local dans le navigateur
- PWA hors connexion

## Utilisation
Ouvrir `index.html` pour un test local simple.
Pour l'installation PWA et le service worker, servir le dossier avec un serveur HTTP (par exemple GitHub Pages ou `python -m http.server`).

## Sécurité
- PIN modifiable depuis Paramètres
- PIN initial : 1234
- Code de réinitialisation : 0509


## Cahier des charges V1 — dernière mise à jour
- Qotation partout; USD uniquement; logo Loyal Engineering; PDF A4 avec signatures et « Fait à / Le ».
- Thèmes clair/sombre.
- PIN modifiable, réinitialisation 0509, demande configurable à chaque ouverture / 5 / 15 / 30 min / 1 h / jamais.
- PWA Android/iPhone avec icônes 192, 512, 1024 et Apple Touch Icon.
- Gestion de factures exclue de la V1.


### Dernière mise à jour
- PDF : titre **QOTATION** uniquement à la place de « DEVIS / COTATION ».
- Sécurité : un seul emplacement pour le code de déverrouillage, avec délai configurable et réinitialisation 0509.
- Sauvegarde : choix de dossier sur navigateurs compatibles, téléchargement JSON de secours et restauration.
