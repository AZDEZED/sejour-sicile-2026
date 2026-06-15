# Première mise en ligne sur GitHub Pages depuis un Mac

## 1. Décompresser le fichier ZIP

- Double-cliquer sur le ZIP téléchargé.
- Ouvrir le dossier obtenu.
- Le dossier doit contenir notamment `docs`, `public`, `src`, `package.json` et `index.html`.

## 2. Créer un dépôt GitHub

- Ouvrir GitHub dans le navigateur.
- Cliquer sur le bouton `New` ou `New repository`.
- Nom conseillé : `sejour-sicile-2026`.
- Choisir `Public`.
- Ne pas ajouter de README, de licence ou de fichier gitignore à cette étape.
- Cliquer sur `Create repository`.

## 3. Importer les fichiers

- Dans le dépôt vide, cliquer sur `uploading an existing file`.
- Dans le Finder, ouvrir le dossier décompressé.
- Sélectionner tous les éléments situés à l'intérieur du dossier.
- Les glisser dans la zone de dépôt GitHub.
- Vérifier que le dossier `docs` apparaît bien au premier niveau du dépôt.
- Saisir par exemple `Première version du site Sicile 2026` dans le champ du commentaire.
- Cliquer sur `Commit changes`.

Important : il faut déposer le contenu du dossier décompressé, et non créer un dossier supplémentaire contenant tout le projet.

## 4. Activer GitHub Pages

- Ouvrir l'onglet `Settings` du dépôt.
- Dans la colonne de gauche, cliquer sur `Pages`.
- Dans la zone `Build and deployment`, choisir `Deploy from a branch`.
- Sélectionner la branche `main`.
- Sélectionner le dossier `/docs`.
- Cliquer sur `Save`.

## 5. Ouvrir le site

- Attendre une à trois minutes.
- Actualiser la page `Settings > Pages`.
- GitHub affichera l'adresse publique du site.
- Ouvrir cette adresse et vérifier l'affichage du site, des images, du bouton WhatsApp et du PDF du trousseau.

## 6. Pour les mises à jour suivantes

Le code source se trouve dans le dossier `src`. Après chaque nouvelle version, il faudra reconstruire le site puis remplacer le contenu du dossier `docs` par la nouvelle version compilée.
