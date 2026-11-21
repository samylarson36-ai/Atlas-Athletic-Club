# Atlas Athletic Club

Projet d’entraînement : site vitrine d’une salle de sport fictive à Bonapriso, Douala. Le nom, les adresses, les téléphones, les tarifs et les personnes sont **fictifs** et ne correspondent à aucune entreprise réelle.

## Pages

- `index.html` : Accueil : présentation de la salle, activités, coachs, tarifs, avis et formulaire de séance d’essai
- `planning.html` : Planning hebdomadaire des 16 cours collectifs, filtrable par type
- `tarifs.html` : Comparatif des formules Essentiel, Premium et Duo, options et FAQ

## Fonctionnalités

- Planning de cours filtrable (musculation, cardio, boxe, mobilité)
- Trois formules d’abonnement et tableau comparatif
- Formulaire d’essai qui ouvre la messagerie (`mailto:`)
- Illustrations vectorielles (SVG) générées pour les coachs et la salle
- Design responsive (mobile, tablette, ordinateur) avec menu burger
- Aucune dépendance : HTML, CSS et JavaScript natifs, polices Google Fonts

## Structure

```
atlas-athletic-club/
├── index.html
├── css/style.css
├── js/main.js
├── img/            illustrations SVG
├── favicon.svg
└── README.md
```

## Lancer en local

Ouvre `index.html` dans un navigateur. Pour un test plus proche de la production :

```
python3 -m http.server 8000
```

puis rends-toi sur `http://localhost:8000`.

## Déployer

- **Vercel** : importe le dépôt, aucun réglage de build (site statique).
- **GitHub Pages** : Settings → Pages → branche `main`, dossier `/ (root)`.

## Personnaliser

- Remplace l’adresse `.example` des formulaires par ton e-mail : attribut `data-mail` dans `index.html`.
- Les couleurs sont des variables au début de `css/style.css` : `--ac` (orange) et `--hero` (fond du bandeau).
- Remplace les fichiers de `img/` par de vraies photos en gardant les mêmes noms (adapte l’extension dans les balises `<img>` si besoin).
