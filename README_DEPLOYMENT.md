# Observatoire des métiers - version GitHub Pages

Contenu du dossier à déposer à la racine du repository GitHub :

- `index.html` : page principale du site ;
- `app_data_part1.js` : première partie des données ;
- `app_data_part2.js` : seconde partie des données ;
- `.nojekyll` : fichier vide évitant que GitHub Pages applique un traitement Jekyll inutile.

Important : les deux fichiers `app_data_part1.js` puis `app_data_part2.js` doivent être dans le même dossier que `index.html`.

Ordre de chargement dans le HTML :

```html
<script src="app_data_part1.js"></script>
<script src="app_data_part2.js"></script>
```

GitHub Pages cherchera automatiquement un fichier `index.html` placé à la racine de la source de publication.
