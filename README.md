# CV en HTML/CSS/JS de Aya Trabelsi

Ce projet est une version HTML/CSS/JS simple du CV d'Aya Trabelsi, convertie à partir du thème Hugo Profile.

## Structure du projet

```
html-cv/
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── hero.svg
│   └── me.png
└── index.html
```

## Comment utiliser ce projet

1. **Visualisation locale**
   - Ouvrez simplement le fichier `index.html` dans votre navigateur

2. **Personnalisation**
   - Modifiez le contenu dans `index.html` pour mettre à jour vos informations
   - Personnalisez les styles dans `css/style.css`
   - Ajoutez des fonctionnalités dans `js/main.js`

3. **Images**
   - Remplacez les images dans le dossier `images/`:
     - `me.png` - Votre photo de profil
     - `hero.svg` - L'image d'en-tête de votre page d'accueil

## Personnalisation des couleurs

Vous pouvez facilement modifier les couleurs du site en éditant les variables CSS dans le fichier `css/style.css`:

```css
:root {
    --primary-color: #007bff;     /* Couleur principale */
    --secondary-color: #6c757d;   /* Couleur secondaire */
    --background-color: #ffffff;  /* Couleur de fond */
    --text-color: #343a40;        /* Couleur du texte */
    --section-alt-bg: #f8f9fa;    /* Couleur de fond alternative */
    --border-color: #dee2e6;      /* Couleur des bordures */
}
```

## Déploiement

Vous pouvez déployer ce site sur n'importe quel service d'hébergement statique:

1. **GitHub Pages**
   - Créez un dépôt GitHub
   - Téléversez tous les fichiers
   - Activez GitHub Pages dans les paramètres du dépôt

2. **Netlify**
   - Créez un compte sur [Netlify](https://www.netlify.com/)
   - Glissez-déposez le dossier `html-cv` sur l'interface de Netlify

3. **Vercel**
   - Créez un compte sur [Vercel](https://vercel.com/)
   - Importez votre dépôt GitHub
   - Vercel détectera automatiquement qu'il s'agit d'un site statique

## Ressources utiles

- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) 