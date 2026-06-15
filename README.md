# Séjour Sicile 2026 - CIE Thalès

Site public d'information destiné aux jeunes et aux familles.

## Première mise en ligne

Le dossier `docs` contient déjà la version construite et prête à être publiée sur GitHub Pages. Il n'est pas nécessaire d'installer une application ni d'exécuter du code pour cette première publication.

1. Créer un dépôt GitHub public.
2. Importer tous les fichiers et dossiers de ce projet dans le dépôt.
3. Ouvrir `Settings > Pages`.
4. Choisir `Deploy from a branch`.
5. Sélectionner la branche `main` et le dossier `/docs`.
6. Enregistrer et attendre la publication.

## Contenu du site

- programme et grandes étapes
- groupe et équipe d'encadrement
- roadbook jour par jour
- vie collective et cadre du séjour
- trousseau validé
- PDF téléchargeable du trousseau
- contact WhatsApp

## Source du site

Le code React se trouve dans `src`. Le projet utilise Vite et Tailwind CSS. Pour reconstruire le site plus tard :

```bash
npm install
npm run build
```

Le contenu du dossier `dist` obtenu doit ensuite remplacer le contenu du dossier `docs`.
